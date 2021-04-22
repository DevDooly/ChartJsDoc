---
title: "Interface: LineElement<T, O>"
---

# Interface: LineElement<T, O\>

## Type parameters

Name | Type | Default |
:------ | :------ | :------ |
`T` | [*LineProps*](lineprops.md) | [*LineProps*](lineprops.md) |
`O` | [*LineOptions*](lineoptions.md) | [*LineOptions*](lineoptions.md) |

## Hierarchy

* [*Element*](../README.md#element)<T, O\>

* [*VisualElement*](visualelement.md)

  ↳ **LineElement**

## Properties

### active

• `Readonly` **active**: *boolean*

Inherited from: Element.active

Defined in: [element.d.ts:6](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/element.d.ts#L6)

___

### options

• `Readonly` **options**: O

Inherited from: Element.options

Defined in: [element.d.ts:7](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/element.d.ts#L7)

___

### points

• **points**: [*Point*](point.md)[]

Defined in: [index.esm.d.ts:1715](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1715)

___

### segments

• `Readonly` **segments**: [*Segment*](segment.md)[]

Defined in: [index.esm.d.ts:1716](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1716)

___

### x

• `Readonly` **x**: *number*

Inherited from: Element.x

Defined in: [element.d.ts:4](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/element.d.ts#L4)

___

### y

• `Readonly` **y**: *number*

Inherited from: Element.y

Defined in: [element.d.ts:5](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/element.d.ts#L5)

## Methods

### draw

▸ **draw**(`ctx`: CanvasRenderingContext2D): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`ctx` | CanvasRenderingContext2D |

**Returns:** *void*

Inherited from: [VisualElement](visualelement.md)

Defined in: [index.esm.d.ts:1577](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1577)

___

### first

▸ **first**(): *false* \| [*Point*](point.md)

**Returns:** *false* \| [*Point*](point.md)

Defined in: [index.esm.d.ts:1717](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1717)

___

### getCenterPoint

▸ **getCenterPoint**(`useFinalPosition?`: *boolean*): *object*

#### Parameters:

Name | Type |
:------ | :------ |
`useFinalPosition?` | *boolean* |

**Returns:** *object*

Name | Type |
:------ | :------ |
`x` | *number* |
`y` | *number* |

Inherited from: [VisualElement](visualelement.md)

Defined in: [index.esm.d.ts:1581](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1581)

___

### getProps

▸ **getProps**<P\>(`props`: [P], `final?`: *boolean*): *Pick*<T, P\>

#### Type parameters:

Name | Type |
:------ | :------ |
`P` | *string* \| *number* \| *symbol* |

#### Parameters:

Name | Type |
:------ | :------ |
`props` | [P] |
`final?` | *boolean* |

**Returns:** *Pick*<T, P\>

Inherited from: Element.getProps

Defined in: [element.d.ts:11](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/element.d.ts#L11)

▸ **getProps**<P, P2\>(`props`: [P, P2], `final?`: *boolean*): *Pick*<T, P \| P2\>

#### Type parameters:

Name | Type |
:------ | :------ |
`P` | *string* \| *number* \| *symbol* |
`P2` | *string* \| *number* \| *symbol* |

#### Parameters:

Name | Type |
:------ | :------ |
`props` | [P, P2] |
`final?` | *boolean* |

**Returns:** *Pick*<T, P \| P2\>

Inherited from: Element.getProps

Defined in: [element.d.ts:12](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/element.d.ts#L12)

▸ **getProps**<P, P2, P3\>(`props`: [P, P2, P3], `final?`: *boolean*): *Pick*<T, P \| P2 \| P3\>

#### Type parameters:

Name | Type |
:------ | :------ |
`P` | *string* \| *number* \| *symbol* |
`P2` | *string* \| *number* \| *symbol* |
`P3` | *string* \| *number* \| *symbol* |

#### Parameters:

Name | Type |
:------ | :------ |
`props` | [P, P2, P3] |
`final?` | *boolean* |

**Returns:** *Pick*<T, P \| P2 \| P3\>

Inherited from: Element.getProps

Defined in: [element.d.ts:13](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/element.d.ts#L13)

▸ **getProps**<P, P2, P3, P4\>(`props`: [P, P2, P3, P4], `final?`: *boolean*): *Pick*<T, P \| P2 \| P3 \| P4\>

#### Type parameters:

Name | Type |
:------ | :------ |
`P` | *string* \| *number* \| *symbol* |
`P2` | *string* \| *number* \| *symbol* |
`P3` | *string* \| *number* \| *symbol* |
`P4` | *string* \| *number* \| *symbol* |

#### Parameters:

Name | Type |
:------ | :------ |
`props` | [P, P2, P3, P4] |
`final?` | *boolean* |

**Returns:** *Pick*<T, P \| P2 \| P3 \| P4\>

Inherited from: Element.getProps

Defined in: [element.d.ts:17](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/element.d.ts#L17)

▸ **getProps**<P, P2, P3, P4, P5\>(`props`: [P, P2, P3, P4, P5], `final?`: *boolean*): *Pick*<T, P \| P2 \| P3 \| P4 \| P5\>

#### Type parameters:

Name | Type |
:------ | :------ |
`P` | *string* \| *number* \| *symbol* |
`P2` | *string* \| *number* \| *symbol* |
`P3` | *string* \| *number* \| *symbol* |
`P4` | *string* \| *number* \| *symbol* |
`P5` | *string* \| *number* \| *symbol* |

#### Parameters:

Name | Type |
:------ | :------ |
`props` | [P, P2, P3, P4, P5] |
`final?` | *boolean* |

**Returns:** *Pick*<T, P \| P2 \| P3 \| P4 \| P5\>

Inherited from: Element.getProps

Defined in: [element.d.ts:21](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/element.d.ts#L21)

▸ **getProps**(`props`: keyof T[], `final?`: *boolean*): T

#### Parameters:

Name | Type |
:------ | :------ |
`props` | keyof T[] |
`final?` | *boolean* |

**Returns:** T

Inherited from: Element.getProps

Defined in: [element.d.ts:25](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/element.d.ts#L25)

___

### getRange

▸ `Optional`**getRange**(`axis`: *x* \| *y*): *number*

#### Parameters:

Name | Type |
:------ | :------ |
`axis` | *x* \| *y* |

**Returns:** *number*

Inherited from: [VisualElement](visualelement.md)

Defined in: [index.esm.d.ts:1582](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1582)

___

### hasValue

▸ **hasValue**(): *boolean*

**Returns:** *boolean*

Inherited from: Element.hasValue

Defined in: [element.d.ts:10](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/element.d.ts#L10)

___

### inRange

▸ **inRange**(`mouseX`: *number*, `mouseY`: *number*, `useFinalPosition?`: *boolean*): *boolean*

#### Parameters:

Name | Type |
:------ | :------ |
`mouseX` | *number* |
`mouseY` | *number* |
`useFinalPosition?` | *boolean* |

**Returns:** *boolean*

Inherited from: [VisualElement](visualelement.md)

Defined in: [index.esm.d.ts:1578](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1578)

___

### inXRange

▸ **inXRange**(`mouseX`: *number*, `useFinalPosition?`: *boolean*): *boolean*

#### Parameters:

Name | Type |
:------ | :------ |
`mouseX` | *number* |
`useFinalPosition?` | *boolean* |

**Returns:** *boolean*

Inherited from: [VisualElement](visualelement.md)

Defined in: [index.esm.d.ts:1579](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1579)

___

### inYRange

▸ **inYRange**(`mouseY`: *number*, `useFinalPosition?`: *boolean*): *boolean*

#### Parameters:

Name | Type |
:------ | :------ |
`mouseY` | *number* |
`useFinalPosition?` | *boolean* |

**Returns:** *boolean*

Inherited from: [VisualElement](visualelement.md)

Defined in: [index.esm.d.ts:1580](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1580)

___

### interpolate

▸ **interpolate**(`point`: [*Point*](point.md), `property`: *x* \| *y*): [*Point*](point.md) \| [*Point*](point.md)[]

#### Parameters:

Name | Type |
:------ | :------ |
`point` | [*Point*](point.md) |
`property` | *x* \| *y* |

**Returns:** [*Point*](point.md) \| [*Point*](point.md)[]

Defined in: [index.esm.d.ts:1719](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1719)

___

### last

▸ **last**(): *false* \| [*Point*](point.md)

**Returns:** *false* \| [*Point*](point.md)

Defined in: [index.esm.d.ts:1718](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1718)

___

### path

▸ **path**(`ctx`: CanvasRenderingContext2D): *boolean*

#### Parameters:

Name | Type |
:------ | :------ |
`ctx` | CanvasRenderingContext2D |

**Returns:** *boolean*

Defined in: [index.esm.d.ts:1721](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1721)

___

### pathSegment

▸ **pathSegment**(`ctx`: CanvasRenderingContext2D, `segment`: [*Segment*](segment.md), `params`: *Record*<string, unknown\>): *boolean*

#### Parameters:

Name | Type |
:------ | :------ |
`ctx` | CanvasRenderingContext2D |
`segment` | [*Segment*](segment.md) |
`params` | *Record*<string, unknown\> |

**Returns:** *boolean*

Defined in: [index.esm.d.ts:1720](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1720)

___

### tooltipPosition

▸ **tooltipPosition**(`useFinalPosition?`: *boolean*): [*Point*](point.md)

#### Parameters:

Name | Type |
:------ | :------ |
`useFinalPosition?` | *boolean* |

**Returns:** [*Point*](point.md)

Inherited from: Element.tooltipPosition

Defined in: [element.d.ts:9](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/element.d.ts#L9)

___

### updateControlPoints

▸ **updateControlPoints**(`chartArea`: [*ChartArea*](chartarea.md)): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`chartArea` | [*ChartArea*](chartarea.md) |

**Returns:** *void*

Defined in: [index.esm.d.ts:1714](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1714)
