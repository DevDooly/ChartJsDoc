---
title: "Interface: CoreInteractionOptions"
---

# Interface: CoreInteractionOptions

## Hierarchy

* **CoreInteractionOptions**

  ↳ [*TooltipOptions*](tooltipoptions.md)

## Properties

### axis

• **axis**: *x* \| *y* \| *xy*

Can be set to 'x', 'y', or 'xy' to define which directions are used in calculating distances. Defaults to 'x' for 'index' mode and 'xy' in dataset and 'nearest' modes.

Defined in: [index.esm.d.ts:1349](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1349)

___

### intersect

• **intersect**: *boolean*

if true, the hover mode only applies when the mouse position intersects an item on the chart.

**`default`** true

Defined in: [index.esm.d.ts:1344](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1344)

___

### mode

• **mode**: *x* \| *y* \| *dataset* \| *index* \| *point* \| *nearest*

Sets which elements appear in the tooltip. See Interaction Modes for details.

**`default`** 'nearest'

Defined in: [index.esm.d.ts:1339](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1339)
