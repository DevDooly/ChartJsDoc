---
title: "Interface: LegendElement"
---

# Interface: LegendElement

## Hierarchy

* [*Element*](../README.md#element)

* [*LayoutItem*](layoutitem.md)

  ↳ **LegendElement**

## Properties

### active

• `Readonly` **active**: *boolean*

Inherited from: Element.active

Defined in: [element.d.ts:6](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/element.d.ts#L6)

___

### bottom

• **bottom**: *number*

Bottom edge of the item. Set by layout system and cannot be used in update

Inherited from: [LayoutItem](layoutitem.md).[bottom](layoutitem.md#bottom)

Defined in: [layout.d.ts:41](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/layout.d.ts#L41)

___

### fullSize

• **fullSize**: *boolean*

if true, and the item is horizontal, then push vertical boxes down

Inherited from: [LayoutItem](layoutitem.md).[fullSize](layoutitem.md#fullsize)

Defined in: [layout.d.ts:17](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/layout.d.ts#L17)

___

### height

• **height**: *number*

Height of item. Must be valid after update()

Inherited from: [LayoutItem](layoutitem.md).[height](layoutitem.md#height)

Defined in: [layout.d.ts:25](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/layout.d.ts#L25)

___

### left

• **left**: *number*

Left edge of the item. Set by layout system and cannot be used in update

Inherited from: [LayoutItem](layoutitem.md).[left](layoutitem.md#left)

Defined in: [layout.d.ts:29](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/layout.d.ts#L29)

___

### options

• `Readonly` **options**: *object*

#### Type declaration:

Inherited from: Element.options

Defined in: [element.d.ts:7](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/element.d.ts#L7)

___

### position

• **position**: [*LayoutPosition*](../README.md#layoutposition)

The position of the item in the chart layout. Possible values are

Inherited from: [LayoutItem](layoutitem.md).[position](layoutitem.md#position)

Defined in: [layout.d.ts:9](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/layout.d.ts#L9)

___

### right

• **right**: *number*

Right edge of the item. Set by layout system and cannot be used in update

Inherited from: [LayoutItem](layoutitem.md).[right](layoutitem.md#right)

Defined in: [layout.d.ts:37](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/layout.d.ts#L37)

___

### top

• **top**: *number*

Top edge of the item. Set by layout system and cannot be used in update

Inherited from: [LayoutItem](layoutitem.md).[top](layoutitem.md#top)

Defined in: [layout.d.ts:33](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/layout.d.ts#L33)

___

### weight

• **weight**: *number*

The weight used to sort the item. Higher weights are further away from the chart area

Inherited from: [LayoutItem](layoutitem.md).[weight](layoutitem.md#weight)

Defined in: [layout.d.ts:13](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/layout.d.ts#L13)

___

### width

• **width**: *number*

Width of item. Must be valid after update()

Inherited from: [LayoutItem](layoutitem.md).[width](layoutitem.md#width)

Defined in: [layout.d.ts:21](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/layout.d.ts#L21)

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

### beforeLayout

▸ `Optional`**beforeLayout**(): *void*

Called before the layout process starts

**Returns:** *void*

Inherited from: [LayoutItem](layoutitem.md)

Defined in: [layout.d.ts:46](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/layout.d.ts#L46)

___

### draw

▸ **draw**(`chartArea`: [*ChartArea*](chartarea.md)): *void*

Draws the element

#### Parameters:

Name | Type |
:------ | :------ |
`chartArea` | [*ChartArea*](chartarea.md) |

**Returns:** *void*

Inherited from: [LayoutItem](layoutitem.md)

Defined in: [layout.d.ts:50](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/layout.d.ts#L50)

___

### getPadding

▸ `Optional`**getPadding**(): [*ChartArea*](chartarea.md)

Returns an object with padding on the edges

**Returns:** [*ChartArea*](chartarea.md)

Inherited from: [LayoutItem](layoutitem.md)

Defined in: [layout.d.ts:54](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/layout.d.ts#L54)

___

### getProps

▸ **getProps**<P\>(`props`: [P], `final?`: *boolean*): *Pick*<{}, P\>

#### Type parameters:

Name | Type |
:------ | :------ |
`P` | *never* |

#### Parameters:

Name | Type |
:------ | :------ |
`props` | [P] |
`final?` | *boolean* |

**Returns:** *Pick*<{}, P\>

Inherited from: Element.getProps

Defined in: [element.d.ts:11](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/element.d.ts#L11)

▸ **getProps**<P, P2\>(`props`: [P, P2], `final?`: *boolean*): *Pick*<{}, P \| P2\>

#### Type parameters:

Name | Type |
:------ | :------ |
`P` | *never* |
`P2` | *never* |

#### Parameters:

Name | Type |
:------ | :------ |
`props` | [P, P2] |
`final?` | *boolean* |

**Returns:** *Pick*<{}, P \| P2\>

Inherited from: Element.getProps

Defined in: [element.d.ts:12](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/element.d.ts#L12)

▸ **getProps**<P, P2, P3\>(`props`: [P, P2, P3], `final?`: *boolean*): *Pick*<{}, P \| P2 \| P3\>

#### Type parameters:

Name | Type |
:------ | :------ |
`P` | *never* |
`P2` | *never* |
`P3` | *never* |

#### Parameters:

Name | Type |
:------ | :------ |
`props` | [P, P2, P3] |
`final?` | *boolean* |

**Returns:** *Pick*<{}, P \| P2 \| P3\>

Inherited from: Element.getProps

Defined in: [element.d.ts:13](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/element.d.ts#L13)

▸ **getProps**<P, P2, P3, P4\>(`props`: [P, P2, P3, P4], `final?`: *boolean*): *Pick*<{}, P \| P2 \| P3 \| P4\>

#### Type parameters:

Name | Type |
:------ | :------ |
`P` | *never* |
`P2` | *never* |
`P3` | *never* |
`P4` | *never* |

#### Parameters:

Name | Type |
:------ | :------ |
`props` | [P, P2, P3, P4] |
`final?` | *boolean* |

**Returns:** *Pick*<{}, P \| P2 \| P3 \| P4\>

Inherited from: Element.getProps

Defined in: [element.d.ts:17](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/element.d.ts#L17)

▸ **getProps**<P, P2, P3, P4, P5\>(`props`: [P, P2, P3, P4, P5], `final?`: *boolean*): *Pick*<{}, P \| P2 \| P3 \| P4 \| P5\>

#### Type parameters:

Name | Type |
:------ | :------ |
`P` | *never* |
`P2` | *never* |
`P3` | *never* |
`P4` | *never* |
`P5` | *never* |

#### Parameters:

Name | Type |
:------ | :------ |
`props` | [P, P2, P3, P4, P5] |
`final?` | *boolean* |

**Returns:** *Pick*<{}, P \| P2 \| P3 \| P4 \| P5\>

Inherited from: Element.getProps

Defined in: [element.d.ts:21](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/element.d.ts#L21)

▸ **getProps**(`props`: *never*[], `final?`: *boolean*): *object*

#### Parameters:

Name | Type |
:------ | :------ |
`props` | *never*[] |
`final?` | *boolean* |

**Returns:** *object*

Inherited from: Element.getProps

Defined in: [element.d.ts:25](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/element.d.ts#L25)

___

### hasValue

▸ **hasValue**(): *boolean*

**Returns:** *boolean*

Inherited from: Element.hasValue

Defined in: [element.d.ts:10](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/element.d.ts#L10)

___

### isHorizontal

▸ **isHorizontal**(): *boolean*

returns true if the layout item is horizontal (ie. top or bottom)

**Returns:** *boolean*

Inherited from: [LayoutItem](layoutitem.md)

Defined in: [layout.d.ts:58](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/layout.d.ts#L58)

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

### update

▸ **update**(`width`: *number*, `height`: *number*, `margins?`: [*ChartArea*](chartarea.md)): *void*

Takes two parameters: width and height.

#### Parameters:

Name | Type |
:------ | :------ |
`width` | *number* |
`height` | *number* |
`margins?` | [*ChartArea*](chartarea.md) |

**Returns:** *void*

Inherited from: [LayoutItem](layoutitem.md)

Defined in: [layout.d.ts:64](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/layout.d.ts#L64)
