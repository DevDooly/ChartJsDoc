---
title: "Interface: VisualElement"
---

# Interface: VisualElement

## Hierarchy

* **VisualElement**

  ↳ [*ArcElement*](arcelement.md)

  ↳ [*LineElement*](lineelement.md)

  ↳ [*PointElement*](pointelement.md)

  ↳ [*BarElement*](barelement.md)

## Methods

### draw

▸ **draw**(`ctx`: CanvasRenderingContext2D): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`ctx` | CanvasRenderingContext2D |

**Returns:** *void*

Defined in: [index.esm.d.ts:1577](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1577)

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

Defined in: [index.esm.d.ts:1581](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1581)

___

### getRange

▸ `Optional`**getRange**(`axis`: *x* \| *y*): *number*

#### Parameters:

Name | Type |
:------ | :------ |
`axis` | *x* \| *y* |

**Returns:** *number*

Defined in: [index.esm.d.ts:1582](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1582)

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

Defined in: [index.esm.d.ts:1580](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1580)
