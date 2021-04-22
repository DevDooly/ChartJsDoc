---
title: "Interface: BubbleControllerDatasetOptions"
---

# Interface: BubbleControllerDatasetOptions

## Hierarchy

* [*ControllerDatasetOptions*](controllerdatasetoptions.md)

* [*ScriptableAndArrayOptions*](../README.md#scriptableandarrayoptions)<[*PointOptions*](pointoptions.md), [*ScriptableContext*](scriptablecontext.md)<*bubble*\>\>

  ↳ **BubbleControllerDatasetOptions**

## Properties

### backgroundColor

• **backgroundColor**: [*ScriptableAndArray*](../README.md#scriptableandarray)<[*Color*](../README.md#color), [*ScriptableContext*](scriptablecontext.md)<*bubble*\>\>

Inherited from: ScriptableAndArrayOptions.backgroundColor

Defined in: [index.esm.d.ts:1588](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1588)

___

### borderColor

• **borderColor**: [*ScriptableAndArray*](../README.md#scriptableandarray)<[*Color*](../README.md#color), [*ScriptableContext*](scriptablecontext.md)<*bubble*\>\>

Inherited from: ScriptableAndArrayOptions.borderColor

Defined in: [index.esm.d.ts:1587](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1587)

___

### borderWidth

• **borderWidth**: [*ScriptableAndArray*](../README.md#scriptableandarray)<number, [*ScriptableContext*](scriptablecontext.md)<*bubble*\>\>

Inherited from: ScriptableAndArrayOptions.borderWidth

Defined in: [index.esm.d.ts:1586](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1586)

___

### clip

• **clip**: *number* \| [*ChartArea*](chartarea.md)

How to clip relative to chartArea. Positive value allows overflow, negative value clips that many pixels inside chartArea. 0 = clip at chartArea. Clipping can also be configured per side: clip: {left: 5, top: false, right: -2, bottom: 0}

Inherited from: [ControllerDatasetOptions](controllerdatasetoptions.md).[clip](controllerdatasetoptions.md#clip)

Defined in: [index.esm.d.ts:64](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L64)

___

### hidden

• **hidden**: *boolean*

Configures the visibility state of the dataset. Set it to true, to hide the dataset from the chart.

**`default`** false

Inherited from: [ControllerDatasetOptions](controllerdatasetoptions.md).[hidden](controllerdatasetoptions.md#hidden)

Defined in: [index.esm.d.ts:82](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L82)

___

### hitRadius

• **hitRadius**: [*ScriptableAndArray*](../README.md#scriptableandarray)<number, [*ScriptableContext*](scriptablecontext.md)<*bubble*\>\>

Extra radius added to point radius for hit detection.

**`default`** 1

Inherited from: ScriptableAndArrayOptions.hitRadius

Defined in: [index.esm.d.ts:1758](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1758)

___

### hoverBackgroundColor

• **hoverBackgroundColor**: [*ScriptableAndArray*](../README.md#scriptableandarray)<[*Color*](../README.md#color), [*ScriptableContext*](scriptablecontext.md)<*bubble*\>\>

Inherited from: ScriptableAndArrayOptions.hoverBackgroundColor

Defined in: [index.esm.d.ts:1594](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1594)

___

### hoverBorderColor

• **hoverBorderColor**: [*ScriptableAndArray*](../README.md#scriptableandarray)<[*Color*](../README.md#color), [*ScriptableContext*](scriptablecontext.md)<*bubble*\>\>

Inherited from: ScriptableAndArrayOptions.hoverBorderColor

Defined in: [index.esm.d.ts:1593](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1593)

___

### hoverBorderWidth

• **hoverBorderWidth**: [*ScriptableAndArray*](../README.md#scriptableandarray)<number, [*ScriptableContext*](scriptablecontext.md)<*bubble*\>\>

Inherited from: ScriptableAndArrayOptions.hoverBorderWidth

Defined in: [index.esm.d.ts:1592](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1592)

___

### hoverRadius

• **hoverRadius**: [*ScriptableAndArray*](../README.md#scriptableandarray)<number, [*ScriptableContext*](scriptablecontext.md)<*bubble*\>\>

Point radius when hovered.

**`default`** 4

Inherited from: ScriptableAndArrayOptions.hoverRadius

Defined in: [index.esm.d.ts:1776](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1776)

___

### indexAxis

• **indexAxis**: *x* \| *y*

The base axis of the chart. 'x' for vertical charts and 'y' for horizontal charts.

**`default`** 'x'

Inherited from: [ControllerDatasetOptions](controllerdatasetoptions.md).[indexAxis](controllerdatasetoptions.md#indexaxis)

Defined in: [index.esm.d.ts:60](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L60)

___

### label

• **label**: *string*

The label for the dataset which appears in the legend and tooltips.

Inherited from: [ControllerDatasetOptions](controllerdatasetoptions.md).[label](controllerdatasetoptions.md#label)

Defined in: [index.esm.d.ts:68](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L68)

___

### normalized

• **normalized**: *boolean*

Chart.js is fastest if you provide data with indices that are unique, sorted, and consistent across datasets and provide the normalized: true option to let Chart.js know that you have done so.

Inherited from: [ControllerDatasetOptions](controllerdatasetoptions.md).[normalized](controllerdatasetoptions.md#normalized)

Defined in: [index.esm.d.ts:52](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L52)

___

### order

• **order**: *number*

The drawing order of dataset. Also affects order for stacking, tooltip and legend.

Inherited from: [ControllerDatasetOptions](controllerdatasetoptions.md).[order](controllerdatasetoptions.md#order)

Defined in: [index.esm.d.ts:72](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L72)

___

### parsing

• **parsing**: *false* \| { [key: string]: *string*;  }

How to parse the dataset. The parsing can be disabled by specifying parsing: false at chart options or dataset. If parsing is disabled, data must be sorted and in the formats the associated chart type and scales use internally.

Inherited from: [ControllerDatasetOptions](controllerdatasetoptions.md).[parsing](controllerdatasetoptions.md#parsing)

Defined in: [index.esm.d.ts:43](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L43)

___

### pointStyle

• **pointStyle**: [*ScriptableAndArray*](../README.md#scriptableandarray)<[*PointStyle*](../README.md#pointstyle), [*ScriptableContext*](scriptablecontext.md)<*bubble*\>\>

Point style

**`default`** 'circle;

Inherited from: ScriptableAndArrayOptions.pointStyle

Defined in: [index.esm.d.ts:1763](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1763)

___

### radius

• **radius**: [*ScriptableAndArray*](../README.md#scriptableandarray)<number, [*ScriptableContext*](scriptablecontext.md)<*bubble*\>\>

Point radius

**`default`** 3

Inherited from: ScriptableAndArrayOptions.radius

Defined in: [index.esm.d.ts:1753](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1753)

___

### rotation

• **rotation**: [*ScriptableAndArray*](../README.md#scriptableandarray)<number, [*ScriptableContext*](scriptablecontext.md)<*bubble*\>\>

Point rotation (in degrees).

**`default`** 0

Inherited from: ScriptableAndArrayOptions.rotation

Defined in: [index.esm.d.ts:1768](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1768)

___

### stack

• **stack**: *string*

The ID of the group to which this dataset belongs to (when stacked, each group will be a separate stack).

Inherited from: [ControllerDatasetOptions](controllerdatasetoptions.md).[stack](controllerdatasetoptions.md#stack)

Defined in: [index.esm.d.ts:77](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L77)
