---
title: "Interface: ControllerDatasetOptions"
---

# Interface: ControllerDatasetOptions

## Hierarchy

* [*ParsingOptions*](parsingoptions.md)

  ↳ **ControllerDatasetOptions**

  ↳↳ [*BarControllerDatasetOptions*](barcontrollerdatasetoptions.md)

  ↳↳ [*BubbleControllerDatasetOptions*](bubblecontrollerdatasetoptions.md)

  ↳↳ [*LineControllerDatasetOptions*](linecontrollerdatasetoptions.md)

  ↳↳ [*DoughnutControllerDatasetOptions*](doughnutcontrollerdatasetoptions.md)

  ↳↳ [*RadarControllerDatasetOptions*](radarcontrollerdatasetoptions.md)

## Properties

### clip

• **clip**: *number* \| [*ChartArea*](chartarea.md)

How to clip relative to chartArea. Positive value allows overflow, negative value clips that many pixels inside chartArea. 0 = clip at chartArea. Clipping can also be configured per side: clip: {left: 5, top: false, right: -2, bottom: 0}

Defined in: [index.esm.d.ts:64](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L64)

___

### hidden

• **hidden**: *boolean*

Configures the visibility state of the dataset. Set it to true, to hide the dataset from the chart.

**`default`** false

Defined in: [index.esm.d.ts:82](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L82)

___

### indexAxis

• **indexAxis**: *x* \| *y*

The base axis of the chart. 'x' for vertical charts and 'y' for horizontal charts.

**`default`** 'x'

Defined in: [index.esm.d.ts:60](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L60)

___

### label

• **label**: *string*

The label for the dataset which appears in the legend and tooltips.

Defined in: [index.esm.d.ts:68](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L68)

___

### normalized

• **normalized**: *boolean*

Chart.js is fastest if you provide data with indices that are unique, sorted, and consistent across datasets and provide the normalized: true option to let Chart.js know that you have done so.

Inherited from: [ParsingOptions](parsingoptions.md).[normalized](parsingoptions.md#normalized)

Defined in: [index.esm.d.ts:52](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L52)

___

### order

• **order**: *number*

The drawing order of dataset. Also affects order for stacking, tooltip and legend.

Defined in: [index.esm.d.ts:72](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L72)

___

### parsing

• **parsing**: *false* \| { [key: string]: *string*;  }

How to parse the dataset. The parsing can be disabled by specifying parsing: false at chart options or dataset. If parsing is disabled, data must be sorted and in the formats the associated chart type and scales use internally.

Inherited from: [ParsingOptions](parsingoptions.md).[parsing](parsingoptions.md#parsing)

Defined in: [index.esm.d.ts:43](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L43)

___

### stack

• **stack**: *string*

The ID of the group to which this dataset belongs to (when stacked, each group will be a separate stack).

Defined in: [index.esm.d.ts:77](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L77)
