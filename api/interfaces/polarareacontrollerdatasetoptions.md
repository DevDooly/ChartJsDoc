---
title: "Interface: PolarAreaControllerDatasetOptions"
---

# Interface: PolarAreaControllerDatasetOptions

## Hierarchy

* [*DoughnutControllerDatasetOptions*](doughnutcontrollerdatasetoptions.md)

  ↳ **PolarAreaControllerDatasetOptions**

## Properties

### angle

• **angle**: *number*

Arc angle to cover. - for polar only

**`default`** circumference / (arc count)

Defined in: [index.esm.d.ts:334](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L334)

___

### animation

• **animation**: *false* \| [*AnimationSpec*](../README.md#animationspec)<*doughnut*\> & { `onComplete?`: (`event`: [*AnimationEvent*](animationevent.md)) => *void* ; `onProgress?`: (`event`: [*AnimationEvent*](animationevent.md)) => *void*  }

Inherited from: [DoughnutControllerDatasetOptions](doughnutcontrollerdatasetoptions.md).[animation](doughnutcontrollerdatasetoptions.md#animation)

Defined in: [index.esm.d.ts:1533](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1533)

___

### animations

• **animations**: [*AnimationsSpec*](../README.md#animationsspec)<*doughnut*\>

Inherited from: [DoughnutControllerDatasetOptions](doughnutcontrollerdatasetoptions.md).[animations](doughnutcontrollerdatasetoptions.md#animations)

Defined in: [index.esm.d.ts:1543](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1543)

___

### backgroundColor

• **backgroundColor**: [*ScriptableAndArray*](../README.md#scriptableandarray)<[*Color*](../README.md#color), [*ScriptableContext*](scriptablecontext.md)<*doughnut*\>\>

Inherited from: [DoughnutControllerDatasetOptions](doughnutcontrollerdatasetoptions.md).[backgroundColor](doughnutcontrollerdatasetoptions.md#backgroundcolor)

Defined in: [index.esm.d.ts:1588](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1588)

___

### borderAlign

• **borderAlign**: [*ScriptableAndArray*](../README.md#scriptableandarray)<*center* \| *inner*, [*ScriptableContext*](scriptablecontext.md)<*doughnut*\>\>

Arc stroke alignment.

Inherited from: [DoughnutControllerDatasetOptions](doughnutcontrollerdatasetoptions.md).[borderAlign](doughnutcontrollerdatasetoptions.md#borderalign)

Defined in: [index.esm.d.ts:1624](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1624)

___

### borderColor

• **borderColor**: [*ScriptableAndArray*](../README.md#scriptableandarray)<[*Color*](../README.md#color), [*ScriptableContext*](scriptablecontext.md)<*doughnut*\>\>

Inherited from: [DoughnutControllerDatasetOptions](doughnutcontrollerdatasetoptions.md).[borderColor](doughnutcontrollerdatasetoptions.md#bordercolor)

Defined in: [index.esm.d.ts:1587](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1587)

___

### borderRadius

• **borderRadius**: [*ScriptableAndArray*](../README.md#scriptableandarray)<number \| [*ArcBorderRadius*](arcborderradius.md), [*ScriptableContext*](scriptablecontext.md)<*doughnut*\>\>

Sets the border radius for arcs

**`default`** 0

Inherited from: [DoughnutControllerDatasetOptions](doughnutcontrollerdatasetoptions.md).[borderRadius](doughnutcontrollerdatasetoptions.md#borderradius)

Defined in: [index.esm.d.ts:1633](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1633)

___

### borderWidth

• **borderWidth**: [*ScriptableAndArray*](../README.md#scriptableandarray)<number, [*ScriptableContext*](scriptablecontext.md)<*doughnut*\>\>

Inherited from: [DoughnutControllerDatasetOptions](doughnutcontrollerdatasetoptions.md).[borderWidth](doughnutcontrollerdatasetoptions.md#borderwidth)

Defined in: [index.esm.d.ts:1586](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1586)

___

### circumference

• **circumference**: *number*

Sweep to allow arcs to cover.

**`default`** 360

Inherited from: [DoughnutControllerDatasetOptions](doughnutcontrollerdatasetoptions.md).[circumference](doughnutcontrollerdatasetoptions.md#circumference)

Defined in: [index.esm.d.ts:242](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L242)

___

### clip

• **clip**: *number* \| [*ChartArea*](chartarea.md)

How to clip relative to chartArea. Positive value allows overflow, negative value clips that many pixels inside chartArea. 0 = clip at chartArea. Clipping can also be configured per side: clip: {left: 5, top: false, right: -2, bottom: 0}

Inherited from: [DoughnutControllerDatasetOptions](doughnutcontrollerdatasetoptions.md).[clip](doughnutcontrollerdatasetoptions.md#clip)

Defined in: [index.esm.d.ts:64](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L64)

___

### hidden

• **hidden**: *boolean*

Configures the visibility state of the dataset. Set it to true, to hide the dataset from the chart.

**`default`** false

Inherited from: [DoughnutControllerDatasetOptions](doughnutcontrollerdatasetoptions.md).[hidden](doughnutcontrollerdatasetoptions.md#hidden)

Defined in: [index.esm.d.ts:82](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L82)

___

### hoverBackgroundColor

• **hoverBackgroundColor**: [*ScriptableAndArray*](../README.md#scriptableandarray)<[*Color*](../README.md#color), [*ScriptableContext*](scriptablecontext.md)<*doughnut*\>\>

Inherited from: [DoughnutControllerDatasetOptions](doughnutcontrollerdatasetoptions.md).[hoverBackgroundColor](doughnutcontrollerdatasetoptions.md#hoverbackgroundcolor)

Defined in: [index.esm.d.ts:1594](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1594)

___

### hoverBorderColor

• **hoverBorderColor**: [*ScriptableAndArray*](../README.md#scriptableandarray)<[*Color*](../README.md#color), [*ScriptableContext*](scriptablecontext.md)<*doughnut*\>\>

Inherited from: [DoughnutControllerDatasetOptions](doughnutcontrollerdatasetoptions.md).[hoverBorderColor](doughnutcontrollerdatasetoptions.md#hoverbordercolor)

Defined in: [index.esm.d.ts:1593](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1593)

___

### hoverBorderWidth

• **hoverBorderWidth**: [*ScriptableAndArray*](../README.md#scriptableandarray)<number, [*ScriptableContext*](scriptablecontext.md)<*doughnut*\>\>

Inherited from: [DoughnutControllerDatasetOptions](doughnutcontrollerdatasetoptions.md).[hoverBorderWidth](doughnutcontrollerdatasetoptions.md#hoverborderwidth)

Defined in: [index.esm.d.ts:1592](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1592)

___

### hoverOffset

• **hoverOffset**: [*ScriptableAndArray*](../README.md#scriptableandarray)<number, [*ScriptableContext*](scriptablecontext.md)<*doughnut*\>\>

Inherited from: [DoughnutControllerDatasetOptions](doughnutcontrollerdatasetoptions.md).[hoverOffset](doughnutcontrollerdatasetoptions.md#hoveroffset)

Defined in: [index.esm.d.ts:1637](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1637)

___

### indexAxis

• **indexAxis**: *x* \| *y*

The base axis of the chart. 'x' for vertical charts and 'y' for horizontal charts.

**`default`** 'x'

Inherited from: [DoughnutControllerDatasetOptions](doughnutcontrollerdatasetoptions.md).[indexAxis](doughnutcontrollerdatasetoptions.md#indexaxis)

Defined in: [index.esm.d.ts:60](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L60)

___

### label

• **label**: *string*

The label for the dataset which appears in the legend and tooltips.

Inherited from: [DoughnutControllerDatasetOptions](doughnutcontrollerdatasetoptions.md).[label](doughnutcontrollerdatasetoptions.md#label)

Defined in: [index.esm.d.ts:68](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L68)

___

### normalized

• **normalized**: *boolean*

Chart.js is fastest if you provide data with indices that are unique, sorted, and consistent across datasets and provide the normalized: true option to let Chart.js know that you have done so.

Inherited from: [DoughnutControllerDatasetOptions](doughnutcontrollerdatasetoptions.md).[normalized](doughnutcontrollerdatasetoptions.md#normalized)

Defined in: [index.esm.d.ts:52](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L52)

___

### offset

• **offset**: [*ScriptableAndArray*](../README.md#scriptableandarray)<number, [*ScriptableContext*](scriptablecontext.md)<*doughnut*\>\>

Arc offset (in pixels).

Inherited from: [DoughnutControllerDatasetOptions](doughnutcontrollerdatasetoptions.md).[offset](doughnutcontrollerdatasetoptions.md#offset)

Defined in: [index.esm.d.ts:1628](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1628)

___

### order

• **order**: *number*

The drawing order of dataset. Also affects order for stacking, tooltip and legend.

Inherited from: [DoughnutControllerDatasetOptions](doughnutcontrollerdatasetoptions.md).[order](doughnutcontrollerdatasetoptions.md#order)

Defined in: [index.esm.d.ts:72](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L72)

___

### parsing

• **parsing**: *false* \| { [key: string]: *string*;  }

How to parse the dataset. The parsing can be disabled by specifying parsing: false at chart options or dataset. If parsing is disabled, data must be sorted and in the formats the associated chart type and scales use internally.

Inherited from: [DoughnutControllerDatasetOptions](doughnutcontrollerdatasetoptions.md).[parsing](doughnutcontrollerdatasetoptions.md#parsing)

Defined in: [index.esm.d.ts:43](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L43)

___

### rotation

• **rotation**: *number*

Starting angle to draw this dataset from.

**`default`** 0

Inherited from: [DoughnutControllerDatasetOptions](doughnutcontrollerdatasetoptions.md).[rotation](doughnutcontrollerdatasetoptions.md#rotation)

Defined in: [index.esm.d.ts:248](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L248)

___

### stack

• **stack**: *string*

The ID of the group to which this dataset belongs to (when stacked, each group will be a separate stack).

Inherited from: [DoughnutControllerDatasetOptions](doughnutcontrollerdatasetoptions.md).[stack](doughnutcontrollerdatasetoptions.md#stack)

Defined in: [index.esm.d.ts:77](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L77)

___

### transitions

• **transitions**: [*TransitionsSpec*](../README.md#transitionsspec)<*doughnut*\>

Inherited from: [DoughnutControllerDatasetOptions](doughnutcontrollerdatasetoptions.md).[transitions](doughnutcontrollerdatasetoptions.md#transitions)

Defined in: [index.esm.d.ts:1544](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1544)

___

### weight

• **weight**: *number*

The relative thickness of the dataset. Providing a value for weight will cause the pie or doughnut dataset to be drawn with a thickness relative to the sum of all the dataset weight values.

**`default`** 1

Inherited from: [DoughnutControllerDatasetOptions](doughnutcontrollerdatasetoptions.md).[weight](doughnutcontrollerdatasetoptions.md#weight)

Defined in: [index.esm.d.ts:254](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L254)
