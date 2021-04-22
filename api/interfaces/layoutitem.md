---
title: "Interface: LayoutItem"
---

# Interface: LayoutItem

## Hierarchy

* **LayoutItem**

  ↳ [*Scale*](../classes/scale.md)

  ↳ [*LegendElement*](legendelement.md)

## Properties

### bottom

• **bottom**: *number*

Bottom edge of the item. Set by layout system and cannot be used in update

Defined in: [layout.d.ts:41](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/layout.d.ts#L41)

___

### fullSize

• **fullSize**: *boolean*

if true, and the item is horizontal, then push vertical boxes down

Defined in: [layout.d.ts:17](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/layout.d.ts#L17)

___

### height

• **height**: *number*

Height of item. Must be valid after update()

Defined in: [layout.d.ts:25](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/layout.d.ts#L25)

___

### left

• **left**: *number*

Left edge of the item. Set by layout system and cannot be used in update

Defined in: [layout.d.ts:29](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/layout.d.ts#L29)

___

### position

• **position**: [*LayoutPosition*](../README.md#layoutposition)

The position of the item in the chart layout. Possible values are

Defined in: [layout.d.ts:9](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/layout.d.ts#L9)

___

### right

• **right**: *number*

Right edge of the item. Set by layout system and cannot be used in update

Defined in: [layout.d.ts:37](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/layout.d.ts#L37)

___

### top

• **top**: *number*

Top edge of the item. Set by layout system and cannot be used in update

Defined in: [layout.d.ts:33](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/layout.d.ts#L33)

___

### weight

• **weight**: *number*

The weight used to sort the item. Higher weights are further away from the chart area

Defined in: [layout.d.ts:13](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/layout.d.ts#L13)

___

### width

• **width**: *number*

Width of item. Must be valid after update()

Defined in: [layout.d.ts:21](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/layout.d.ts#L21)

## Methods

### beforeLayout

▸ `Optional`**beforeLayout**(): *void*

Called before the layout process starts

**Returns:** *void*

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

Defined in: [layout.d.ts:50](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/layout.d.ts#L50)

___

### getPadding

▸ `Optional`**getPadding**(): [*ChartArea*](chartarea.md)

Returns an object with padding on the edges

**Returns:** [*ChartArea*](chartarea.md)

Defined in: [layout.d.ts:54](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/layout.d.ts#L54)

___

### isHorizontal

▸ **isHorizontal**(): *boolean*

returns true if the layout item is horizontal (ie. top or bottom)

**Returns:** *boolean*

Defined in: [layout.d.ts:58](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/layout.d.ts#L58)

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

Defined in: [layout.d.ts:64](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/layout.d.ts#L64)
