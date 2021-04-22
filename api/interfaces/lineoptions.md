---
title: "Interface: LineOptions"
---

# Interface: LineOptions

## Hierarchy

* [*CommonElementOptions*](commonelementoptions.md)

  ↳ **LineOptions**

## Properties

### backgroundColor

• **backgroundColor**: [*Color*](../README.md#color)

Inherited from: [CommonElementOptions](commonelementoptions.md).[backgroundColor](commonelementoptions.md#backgroundcolor)

Defined in: [index.esm.d.ts:1588](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1588)

___

### borderCapStyle

• **borderCapStyle**: CanvasLineCap

Line cap style. See MDN.

**`default`** 'butt'

Defined in: [index.esm.d.ts:1656](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1656)

___

### borderColor

• **borderColor**: [*Color*](../README.md#color)

Inherited from: [CommonElementOptions](commonelementoptions.md).[borderColor](commonelementoptions.md#bordercolor)

Defined in: [index.esm.d.ts:1587](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1587)

___

### borderDash

• **borderDash**: *number*[]

Line dash. See MDN.

**`default`** []

Defined in: [index.esm.d.ts:1661](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1661)

___

### borderDashOffset

• **borderDashOffset**: *number*

Line dash offset. See MDN.

**`default`** 0.0

Defined in: [index.esm.d.ts:1666](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1666)

___

### borderJoinStyle

• **borderJoinStyle**: CanvasLineJoin

Line join style. See MDN.

**`default`** 'miter'

Defined in: [index.esm.d.ts:1671](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1671)

___

### borderWidth

• **borderWidth**: *number*

Inherited from: [CommonElementOptions](commonelementoptions.md).[borderWidth](commonelementoptions.md#borderwidth)

Defined in: [index.esm.d.ts:1586](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1586)

___

### capBezierPoints

• **capBezierPoints**: *boolean*

  true to keep Bézier control inside the chart, false for no restriction.

**`default`** true

Defined in: [index.esm.d.ts:1676](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1676)

___

### cubicInterpolationMode

• **cubicInterpolationMode**: *default* \| *monotone*

Interpolation mode to apply.

**`default`** 'default'

Defined in: [index.esm.d.ts:1681](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1681)

___

### segment

• **segment**: *object*

#### Type declaration:

Name | Type |
:------ | :------ |
`backgroundColor` | [*Scriptable*](../README.md#scriptable)<[*Color*](../README.md#color), [*ScriptableLineSegmentContext*](scriptablelinesegmentcontext.md)\> |
`borderCapStyle` | [*Scriptable*](../README.md#scriptable)<CanvasLineCap, [*ScriptableLineSegmentContext*](scriptablelinesegmentcontext.md)\> |
`borderColor` | [*Scriptable*](../README.md#scriptable)<[*Color*](../README.md#color), [*ScriptableLineSegmentContext*](scriptablelinesegmentcontext.md)\> |
`borderDash` | [*Scriptable*](../README.md#scriptable)<number[], [*ScriptableLineSegmentContext*](scriptablelinesegmentcontext.md)\> |
`borderDashOffset` | [*Scriptable*](../README.md#scriptable)<number, [*ScriptableLineSegmentContext*](scriptablelinesegmentcontext.md)\> |
`borderJoinStyle` | [*Scriptable*](../README.md#scriptable)<CanvasLineJoin, [*ScriptableLineSegmentContext*](scriptablelinesegmentcontext.md)\> |
`borderWidth` | [*Scriptable*](../README.md#scriptable)<number, [*ScriptableLineSegmentContext*](scriptablelinesegmentcontext.md)\> |

Defined in: [index.esm.d.ts:1693](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1693)

___

### stepped

• **stepped**: *boolean* \| *before* \| *after* \| *middle*

true to show the line as a stepped line (tension will be ignored).

**`default`** false

Defined in: [index.esm.d.ts:1691](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1691)

___

### tension

• **tension**: *number*

Bézier curve tension (0 for no Bézier curves).

**`default`** 0

Defined in: [index.esm.d.ts:1686](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1686)
