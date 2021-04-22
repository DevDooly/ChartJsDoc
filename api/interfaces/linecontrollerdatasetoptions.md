---
title: "Interface: LineControllerDatasetOptions"
---

# Interface: LineControllerDatasetOptions

## Hierarchy

* [*ControllerDatasetOptions*](controllerdatasetoptions.md)

* [*ScriptableAndArrayOptions*](../README.md#scriptableandarrayoptions)<[*PointPrefixedOptions*](pointprefixedoptions.md), [*ScriptableContext*](scriptablecontext.md)<*line*\>\>

* [*ScriptableOptions*](../README.md#scriptableoptions)<[*LineOptions*](lineoptions.md), [*ScriptableContext*](scriptablecontext.md)<*line*\>\>

* [*AnimationOptions*](../README.md#animationoptions)<*line*\>

  ↳ **LineControllerDatasetOptions**

## Properties

### animation

• **animation**: *false* \| [*AnimationSpec*](../README.md#animationspec)<*line*\> & { `onComplete?`: (`event`: [*AnimationEvent*](animationevent.md)) => *void* ; `onProgress?`: (`event`: [*AnimationEvent*](animationevent.md)) => *void*  }

Inherited from: AnimationOptions.animation

Defined in: [index.esm.d.ts:1533](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1533)

___

### animations

• **animations**: [*AnimationsSpec*](../README.md#animationsspec)<*line*\>

Inherited from: AnimationOptions.animations

Defined in: [index.esm.d.ts:1543](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1543)

___

### backgroundColor

• **backgroundColor**: [*Scriptable*](../README.md#scriptable)<[*Color*](../README.md#color), [*ScriptableContext*](scriptablecontext.md)<*line*\>\>

Inherited from: ScriptableOptions.backgroundColor

Defined in: [index.esm.d.ts:1588](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1588)

___

### borderCapStyle

• **borderCapStyle**: [*Scriptable*](../README.md#scriptable)<CanvasLineCap, [*ScriptableContext*](scriptablecontext.md)<*line*\>\>

Line cap style. See MDN.

**`default`** 'butt'

Inherited from: ScriptableOptions.borderCapStyle

Defined in: [index.esm.d.ts:1656](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1656)

___

### borderColor

• **borderColor**: [*Scriptable*](../README.md#scriptable)<[*Color*](../README.md#color), [*ScriptableContext*](scriptablecontext.md)<*line*\>\>

Inherited from: ScriptableOptions.borderColor

Defined in: [index.esm.d.ts:1587](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1587)

___

### borderDash

• **borderDash**: [*Scriptable*](../README.md#scriptable)<number[], [*ScriptableContext*](scriptablecontext.md)<*line*\>\>

Line dash. See MDN.

**`default`** []

Inherited from: ScriptableOptions.borderDash

Defined in: [index.esm.d.ts:1661](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1661)

___

### borderDashOffset

• **borderDashOffset**: [*Scriptable*](../README.md#scriptable)<number, [*ScriptableContext*](scriptablecontext.md)<*line*\>\>

Line dash offset. See MDN.

**`default`** 0.0

Inherited from: ScriptableOptions.borderDashOffset

Defined in: [index.esm.d.ts:1666](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1666)

___

### borderJoinStyle

• **borderJoinStyle**: [*Scriptable*](../README.md#scriptable)<CanvasLineJoin, [*ScriptableContext*](scriptablecontext.md)<*line*\>\>

Line join style. See MDN.

**`default`** 'miter'

Inherited from: ScriptableOptions.borderJoinStyle

Defined in: [index.esm.d.ts:1671](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1671)

___

### borderWidth

• **borderWidth**: [*Scriptable*](../README.md#scriptable)<number, [*ScriptableContext*](scriptablecontext.md)<*line*\>\>

Inherited from: ScriptableOptions.borderWidth

Defined in: [index.esm.d.ts:1586](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1586)

___

### capBezierPoints

• **capBezierPoints**: [*Scriptable*](../README.md#scriptable)<boolean, [*ScriptableContext*](scriptablecontext.md)<*line*\>\>

  true to keep Bézier control inside the chart, false for no restriction.

**`default`** true

Inherited from: ScriptableOptions.capBezierPoints

Defined in: [index.esm.d.ts:1676](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1676)

___

### clip

• **clip**: *number* \| [*ChartArea*](chartarea.md)

How to clip relative to chartArea. Positive value allows overflow, negative value clips that many pixels inside chartArea. 0 = clip at chartArea. Clipping can also be configured per side: clip: {left: 5, top: false, right: -2, bottom: 0}

Inherited from: [ControllerDatasetOptions](controllerdatasetoptions.md).[clip](controllerdatasetoptions.md#clip)

Defined in: [index.esm.d.ts:64](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L64)

___

### cubicInterpolationMode

• **cubicInterpolationMode**: [*Scriptable*](../README.md#scriptable)<*default* \| *monotone*, [*ScriptableContext*](scriptablecontext.md)<*line*\>\>

Interpolation mode to apply.

**`default`** 'default'

Inherited from: ScriptableOptions.cubicInterpolationMode

Defined in: [index.esm.d.ts:1681](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1681)

___

### hidden

• **hidden**: *boolean*

Configures the visibility state of the dataset. Set it to true, to hide the dataset from the chart.

**`default`** false

Inherited from: [ControllerDatasetOptions](controllerdatasetoptions.md).[hidden](controllerdatasetoptions.md#hidden)

Defined in: [index.esm.d.ts:82](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L82)

___

### hoverBackgroundColor

• **hoverBackgroundColor**: [*Scriptable*](../README.md#scriptable)<[*Color*](../README.md#color), [*ScriptableContext*](scriptablecontext.md)<*line*\>\>

Inherited from: ScriptableOptions.hoverBackgroundColor

Defined in: [index.esm.d.ts:1594](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1594)

___

### hoverBorderCapStyle

• **hoverBorderCapStyle**: [*Scriptable*](../README.md#scriptable)<CanvasLineCap, [*ScriptableContext*](scriptablecontext.md)<*line*\>\>

Inherited from: ScriptableOptions.hoverBorderCapStyle

Defined in: [index.esm.d.ts:1705](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1705)

___

### hoverBorderColor

• **hoverBorderColor**: [*Scriptable*](../README.md#scriptable)<[*Color*](../README.md#color), [*ScriptableContext*](scriptablecontext.md)<*line*\>\>

Inherited from: ScriptableOptions.hoverBorderColor

Defined in: [index.esm.d.ts:1593](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1593)

___

### hoverBorderDash

• **hoverBorderDash**: [*Scriptable*](../README.md#scriptable)<number[], [*ScriptableContext*](scriptablecontext.md)<*line*\>\>

Inherited from: ScriptableOptions.hoverBorderDash

Defined in: [index.esm.d.ts:1706](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1706)

___

### hoverBorderDashOffset

• **hoverBorderDashOffset**: [*Scriptable*](../README.md#scriptable)<number, [*ScriptableContext*](scriptablecontext.md)<*line*\>\>

Inherited from: ScriptableOptions.hoverBorderDashOffset

Defined in: [index.esm.d.ts:1707](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1707)

___

### hoverBorderJoinStyle

• **hoverBorderJoinStyle**: [*Scriptable*](../README.md#scriptable)<CanvasLineJoin, [*ScriptableContext*](scriptablecontext.md)<*line*\>\>

Inherited from: ScriptableOptions.hoverBorderJoinStyle

Defined in: [index.esm.d.ts:1708](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1708)

___

### hoverBorderWidth

• **hoverBorderWidth**: [*Scriptable*](../README.md#scriptable)<number, [*ScriptableContext*](scriptablecontext.md)<*line*\>\>

Inherited from: ScriptableOptions.hoverBorderWidth

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

### pointBackgroundColor

• **pointBackgroundColor**: [*ScriptableAndArray*](../README.md#scriptableandarray)<[*Color*](../README.md#color), [*ScriptableContext*](scriptablecontext.md)<*line*\>\>

The fill color for points.

Inherited from: ScriptableAndArrayOptions.pointBackgroundColor

Defined in: [index.esm.d.ts:1783](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1783)

___

### pointBorderColor

• **pointBorderColor**: [*ScriptableAndArray*](../README.md#scriptableandarray)<[*Color*](../README.md#color), [*ScriptableContext*](scriptablecontext.md)<*line*\>\>

The border color for points.

Inherited from: ScriptableAndArrayOptions.pointBorderColor

Defined in: [index.esm.d.ts:1787](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1787)

___

### pointBorderWidth

• **pointBorderWidth**: [*ScriptableAndArray*](../README.md#scriptableandarray)<number, [*ScriptableContext*](scriptablecontext.md)<*line*\>\>

The width of the point border in pixels.

Inherited from: ScriptableAndArrayOptions.pointBorderWidth

Defined in: [index.esm.d.ts:1791](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1791)

___

### pointHitRadius

• **pointHitRadius**: [*ScriptableAndArray*](../README.md#scriptableandarray)<number, [*ScriptableContext*](scriptablecontext.md)<*line*\>\>

The pixel size of the non-displayed point that reacts to mouse events.

Inherited from: ScriptableAndArrayOptions.pointHitRadius

Defined in: [index.esm.d.ts:1795](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1795)

___

### pointHoverBackgroundColor

• **pointHoverBackgroundColor**: [*ScriptableAndArray*](../README.md#scriptableandarray)<[*Color*](../README.md#color), [*ScriptableContext*](scriptablecontext.md)<*line*\>\>

Point background color when hovered.

Inherited from: ScriptableAndArrayOptions.pointHoverBackgroundColor

Defined in: [index.esm.d.ts:1814](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1814)

___

### pointHoverBorderColor

• **pointHoverBorderColor**: [*ScriptableAndArray*](../README.md#scriptableandarray)<[*Color*](../README.md#color), [*ScriptableContext*](scriptablecontext.md)<*line*\>\>

Point border color when hovered.

Inherited from: ScriptableAndArrayOptions.pointHoverBorderColor

Defined in: [index.esm.d.ts:1818](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1818)

___

### pointHoverBorderWidth

• **pointHoverBorderWidth**: [*ScriptableAndArray*](../README.md#scriptableandarray)<number, [*ScriptableContext*](scriptablecontext.md)<*line*\>\>

Border width of point when hovered.

Inherited from: ScriptableAndArrayOptions.pointHoverBorderWidth

Defined in: [index.esm.d.ts:1822](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1822)

___

### pointHoverRadius

• **pointHoverRadius**: [*ScriptableAndArray*](../README.md#scriptableandarray)<number, [*ScriptableContext*](scriptablecontext.md)<*line*\>\>

The radius of the point when hovered.

Inherited from: ScriptableAndArrayOptions.pointHoverRadius

Defined in: [index.esm.d.ts:1826](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1826)

___

### pointRadius

• **pointRadius**: [*ScriptableAndArray*](../README.md#scriptableandarray)<number, [*ScriptableContext*](scriptablecontext.md)<*line*\>\>

The radius of the point shape. If set to 0, the point is not rendered.

Inherited from: ScriptableAndArrayOptions.pointRadius

Defined in: [index.esm.d.ts:1799](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1799)

___

### pointRotation

• **pointRotation**: [*ScriptableAndArray*](../README.md#scriptableandarray)<number, [*ScriptableContext*](scriptablecontext.md)<*line*\>\>

The rotation of the point in degrees.

Inherited from: ScriptableAndArrayOptions.pointRotation

Defined in: [index.esm.d.ts:1803](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1803)

___

### pointStyle

• **pointStyle**: [*ScriptableAndArray*](../README.md#scriptableandarray)<[*PointStyle*](../README.md#pointstyle), [*ScriptableContext*](scriptablecontext.md)<*line*\>\>

Style of the point.

Inherited from: ScriptableAndArrayOptions.pointStyle

Defined in: [index.esm.d.ts:1807](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1807)

___

### segment

• **segment**: [*Scriptable*](../README.md#scriptable)<{ `backgroundColor`: [*Scriptable*](../README.md#scriptable)<[*Color*](../README.md#color), [*ScriptableLineSegmentContext*](scriptablelinesegmentcontext.md)\> ; `borderCapStyle`: [*Scriptable*](../README.md#scriptable)<CanvasLineCap, [*ScriptableLineSegmentContext*](scriptablelinesegmentcontext.md)\> ; `borderColor`: [*Scriptable*](../README.md#scriptable)<[*Color*](../README.md#color), [*ScriptableLineSegmentContext*](scriptablelinesegmentcontext.md)\> ; `borderDash`: [*Scriptable*](../README.md#scriptable)<number[], [*ScriptableLineSegmentContext*](scriptablelinesegmentcontext.md)\> ; `borderDashOffset`: [*Scriptable*](../README.md#scriptable)<number, [*ScriptableLineSegmentContext*](scriptablelinesegmentcontext.md)\> ; `borderJoinStyle`: [*Scriptable*](../README.md#scriptable)<CanvasLineJoin, [*ScriptableLineSegmentContext*](scriptablelinesegmentcontext.md)\> ; `borderWidth`: [*Scriptable*](../README.md#scriptable)<number, [*ScriptableLineSegmentContext*](scriptablelinesegmentcontext.md)\>  }, [*ScriptableContext*](scriptablecontext.md)<*line*\>\>

Inherited from: ScriptableOptions.segment

Defined in: [index.esm.d.ts:1693](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1693)

___

### showLine

• **showLine**: *boolean*

Defined in: [index.esm.d.ts:195](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L195)

___

### spanGaps

• **spanGaps**: *number* \| *boolean*

If true, lines will be drawn between points with no or null data. If false, points with NaN data will create a break in the line. Can also be a number specifying the maximum gap length to span. The unit of the value depends on the scale used.

**`default`** false

Defined in: [index.esm.d.ts:193](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L193)

___

### stack

• **stack**: *string*

The ID of the group to which this dataset belongs to (when stacked, each group will be a separate stack).

Inherited from: [ControllerDatasetOptions](controllerdatasetoptions.md).[stack](controllerdatasetoptions.md#stack)

Defined in: [index.esm.d.ts:77](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L77)

___

### stepped

• **stepped**: [*Scriptable*](../README.md#scriptable)<boolean \| *before* \| *after* \| *middle*, [*ScriptableContext*](scriptablecontext.md)<*line*\>\>

true to show the line as a stepped line (tension will be ignored).

**`default`** false

Inherited from: ScriptableOptions.stepped

Defined in: [index.esm.d.ts:1691](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1691)

___

### tension

• **tension**: [*Scriptable*](../README.md#scriptable)<number, [*ScriptableContext*](scriptablecontext.md)<*line*\>\>

Bézier curve tension (0 for no Bézier curves).

**`default`** 0

Inherited from: ScriptableOptions.tension

Defined in: [index.esm.d.ts:1686](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1686)

___

### transitions

• **transitions**: [*TransitionsSpec*](../README.md#transitionsspec)<*line*\>

Inherited from: AnimationOptions.transitions

Defined in: [index.esm.d.ts:1544](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1544)

___

### xAxisID

• **xAxisID**: *string*

The ID of the x axis to plot this dataset on.

Defined in: [index.esm.d.ts:183](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L183)

___

### yAxisID

• **yAxisID**: *string*

The ID of the y axis to plot this dataset on.

Defined in: [index.esm.d.ts:187](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L187)
