---
title: "Interface: BarControllerDatasetOptions"
---

# Interface: BarControllerDatasetOptions

## Hierarchy

* [*ControllerDatasetOptions*](controllerdatasetoptions.md)

* [*ScriptableAndArrayOptions*](../README.md#scriptableandarrayoptions)<[*BarOptions*](baroptions.md), [*ScriptableContext*](scriptablecontext.md)<*bar*\>\>

* [*AnimationOptions*](../README.md#animationoptions)<*bar*\>

  ↳ **BarControllerDatasetOptions**

## Properties

### animation

• **animation**: *false* \| [*AnimationSpec*](../README.md#animationspec)<*bar*\> & { `onComplete?`: (`event`: [*AnimationEvent*](animationevent.md)) => *void* ; `onProgress?`: (`event`: [*AnimationEvent*](animationevent.md)) => *void*  }

Inherited from: AnimationOptions.animation

Defined in: [index.esm.d.ts:1533](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1533)

___

### animations

• **animations**: [*AnimationsSpec*](../README.md#animationsspec)<*bar*\>

Inherited from: AnimationOptions.animations

Defined in: [index.esm.d.ts:1543](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1543)

___

### backgroundColor

• **backgroundColor**: [*ScriptableAndArray*](../README.md#scriptableandarray)<[*Color*](../README.md#color), [*ScriptableContext*](scriptablecontext.md)<*bar*\>\>

Inherited from: ScriptableAndArrayOptions.backgroundColor

Defined in: [index.esm.d.ts:1588](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1588)

___

### barPercentage

• **barPercentage**: *number*

Percent (0-1) of the available width each bar should be within the category width. 1.0 will take the whole category width and put the bars right next to each other.

**`default`** 0.9

Defined in: [index.esm.d.ts:103](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L103)

___

### barThickness

• **barThickness**: *number* \| *flex*

Manually set width of each bar in pixels. If set to 'flex', it computes "optimal" sample widths that globally arrange bars side by side. If not set (default), bars are equally sized based on the smallest interval.

Defined in: [index.esm.d.ts:113](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L113)

___

### base

• **base**: [*ScriptableAndArray*](../README.md#scriptableandarray)<number, [*ScriptableContext*](scriptablecontext.md)<*bar*\>\>

The base value for the bar in data units along the value axis.

Inherited from: ScriptableAndArrayOptions.base

Defined in: [index.esm.d.ts:1854](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1854)

___

### borderColor

• **borderColor**: [*ScriptableAndArray*](../README.md#scriptableandarray)<[*Color*](../README.md#color), [*ScriptableContext*](scriptablecontext.md)<*bar*\>\>

Inherited from: ScriptableAndArrayOptions.borderColor

Defined in: [index.esm.d.ts:1587](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1587)

___

### borderRadius

• **borderRadius**: [*ScriptableAndArray*](../README.md#scriptableandarray)<number \| [*BorderRadius*](borderradius.md), [*ScriptableContext*](scriptablecontext.md)<*bar*\>\>

Border radius

**`default`** 0

Inherited from: ScriptableAndArrayOptions.borderRadius

Defined in: [index.esm.d.ts:1866](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1866)

___

### borderSkipped

• **borderSkipped**: [*ScriptableAndArray*](../README.md#scriptableandarray)<*false* \| *start* \| *end* \| *left* \| *right* \| *bottom* \| *top*, [*ScriptableContext*](scriptablecontext.md)<*bar*\>\>

  Skipped (excluded) border: 'start', 'end', 'left',  'right', 'bottom', 'top' or false (none).

**`default`** 'start'

Inherited from: ScriptableAndArrayOptions.borderSkipped

Defined in: [index.esm.d.ts:1860](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1860)

___

### borderWidth

• **borderWidth**: [*ScriptableAndArray*](../README.md#scriptableandarray)<number, [*ScriptableContext*](scriptablecontext.md)<*bar*\>\>

Inherited from: ScriptableAndArrayOptions.borderWidth

Defined in: [index.esm.d.ts:1586](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1586)

___

### categoryPercentage

• **categoryPercentage**: *number*

Percent (0-1) of the available width each category should be within the sample width.

**`default`** 0.8

Defined in: [index.esm.d.ts:108](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L108)

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

### hoverBackgroundColor

• **hoverBackgroundColor**: [*ScriptableAndArray*](../README.md#scriptableandarray)<[*Color*](../README.md#color), [*ScriptableContext*](scriptablecontext.md)<*bar*\>\>

Inherited from: ScriptableAndArrayOptions.hoverBackgroundColor

Defined in: [index.esm.d.ts:1594](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1594)

___

### hoverBorderColor

• **hoverBorderColor**: [*ScriptableAndArray*](../README.md#scriptableandarray)<[*Color*](../README.md#color), [*ScriptableContext*](scriptablecontext.md)<*bar*\>\>

Inherited from: ScriptableAndArrayOptions.hoverBorderColor

Defined in: [index.esm.d.ts:1593](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1593)

___

### hoverBorderWidth

• **hoverBorderWidth**: [*ScriptableAndArray*](../README.md#scriptableandarray)<number, [*ScriptableContext*](scriptablecontext.md)<*bar*\>\>

Inherited from: ScriptableAndArrayOptions.hoverBorderWidth

Defined in: [index.esm.d.ts:1592](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1592)

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

### maxBarThickness

• **maxBarThickness**: *number*

Set this to ensure that bars are not sized thicker than this.

Defined in: [index.esm.d.ts:118](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L118)

___

### minBarLength

• **minBarLength**: *number*

Set this to ensure that bars have a minimum length in pixels.

Defined in: [index.esm.d.ts:123](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L123)

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

• **pointStyle**: [*PointStyle*](../README.md#pointstyle)

Point style for the legend

**`default`** 'circle;

Defined in: [index.esm.d.ts:129](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L129)

___

### stack

• **stack**: *string*

The ID of the group to which this dataset belongs to (when stacked, each group will be a separate stack).

Inherited from: [ControllerDatasetOptions](controllerdatasetoptions.md).[stack](controllerdatasetoptions.md#stack)

Defined in: [index.esm.d.ts:77](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L77)

___

### transitions

• **transitions**: [*TransitionsSpec*](../README.md#transitionsspec)<*bar*\>

Inherited from: AnimationOptions.transitions

Defined in: [index.esm.d.ts:1544](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1544)

___

### xAxisID

• **xAxisID**: *string*

The ID of the x axis to plot this dataset on.

Defined in: [index.esm.d.ts:93](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L93)

___

### yAxisID

• **yAxisID**: *string*

The ID of the y axis to plot this dataset on.

Defined in: [index.esm.d.ts:97](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L97)
