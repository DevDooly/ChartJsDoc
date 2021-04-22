---
title: "Interface: TickOptions"
---

# Interface: TickOptions

## Properties

### backdropColor

• **backdropColor**: [*Scriptable*](../README.md#scriptable)<[*Color*](../README.md#color), [*ScriptableScaleContext*](scriptablescalecontext.md)\>

Color of label backdrops.

**`default`** 'rgba(255, 255, 255, 0.75)'

Defined in: [index.esm.d.ts:2700](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2700)

___

### backdropPadding

• **backdropPadding**: *number* \| [*ChartArea*](chartarea.md)

Padding of tick backdrop.

**`default`** 2

Defined in: [index.esm.d.ts:2705](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2705)

___

### callback

• **callback**: (`tickValue`: *string* \| *number*, `index`: *number*, `ticks`: [*Tick*](tick.md)[]) => *string* \| *number*

Returns the string representation of the tick value as it should be displayed on the chart. See callback.

#### Type declaration:

▸ (`tickValue`: *string* \| *number*, `index`: *number*, `ticks`: [*Tick*](tick.md)[]): *string* \| *number*

#### Parameters:

Name | Type |
:------ | :------ |
`tickValue` | *string* \| *number* |
`index` | *number* |
`ticks` | [*Tick*](tick.md)[] |

**Returns:** *string* \| *number*

Defined in: [index.esm.d.ts:2710](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2710)

Defined in: [index.esm.d.ts:2710](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2710)

___

### color

• **color**: [*Scriptable*](../README.md#scriptable)<[*Color*](../README.md#color), [*ScriptableScaleContext*](scriptablescalecontext.md)\>

Color of tick

**`see`** Defaults.color

Defined in: [index.esm.d.ts:2720](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2720)

___

### display

• **display**: *boolean*

If true, show tick labels.

**`default`** true

Defined in: [index.esm.d.ts:2715](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2715)

___

### font

• **font**: [*Scriptable*](../README.md#scriptable)<[*FontSpec*](fontspec.md), [*ScriptableScaleContext*](scriptablescalecontext.md)\>

see Fonts

Defined in: [index.esm.d.ts:2724](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2724)

___

### major

• **major**: *object*

#### Type declaration:

Name | Type | Description |
:------ | :------ | :------ |
`enabled` | *boolean* | If true, major ticks are generated. A major tick will affect autoskipping and major will be defined on ticks in the scriptable options context.  **`default`** false  |

Defined in: [index.esm.d.ts:2750](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2750)

___

### padding

• **padding**: *number*

Sets the offset of the tick labels from the axis

Defined in: [index.esm.d.ts:2728](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2728)

___

### showLabelBackdrop

• **showLabelBackdrop**: [*Scriptable*](../README.md#scriptable)<boolean, [*ScriptableScaleContext*](scriptablescalecontext.md)\>

If true, draw a background behind the tick labels.

**`default`** false

Defined in: [index.esm.d.ts:2733](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2733)

___

### textStrokeColor

• **textStrokeColor**: [*Scriptable*](../README.md#scriptable)<[*Color*](../README.md#color), [*ScriptableScaleContext*](scriptablescalecontext.md)\>

The color of the stroke around the text.

**`default`** undefined

Defined in: [index.esm.d.ts:2738](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2738)

___

### textStrokeWidth

• **textStrokeWidth**: [*Scriptable*](../README.md#scriptable)<number, [*ScriptableScaleContext*](scriptablescalecontext.md)\>

Stroke width around the text.

**`default`** 0

Defined in: [index.esm.d.ts:2743](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2743)

___

### z

• **z**: *number*

z-index of tick layer. Useful when ticks are drawn on chart area. Values <= 0 are drawn under datasets, > 0 on top.

**`default`** 0

Defined in: [index.esm.d.ts:2748](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2748)
