---
title: "Interface: CartesianScaleOptions"
---

# Interface: CartesianScaleOptions

## Hierarchy

* [*CoreScaleOptions*](corescaleoptions.md)

  ↳ **CartesianScaleOptions**

## Properties

### alignToPixels

• **alignToPixels**: *boolean*

Align pixel values to device pixels

Inherited from: [CoreScaleOptions](corescaleoptions.md).[alignToPixels](corescaleoptions.md#aligntopixels)

Defined in: [index.esm.d.ts:1077](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1077)

___

### axis

• **axis**: *x* \| *y*

  Which type of axis this is. Possible values are: 'x', 'y'. If not set, this is inferred from the first character of the ID which should be 'x' or 'y'.

Defined in: [index.esm.d.ts:2767](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2767)

___

### display

• **display**: *boolean* \| *auto*

Controls the axis global visibility (visible when true, hidden when false). When display: 'auto', the axis is visible only if at least one associated dataset is visible.

**`default`** true

Inherited from: [CoreScaleOptions](corescaleoptions.md).[display](corescaleoptions.md#display)

Defined in: [index.esm.d.ts:1073](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1073)

___

### grid

• **grid**: [*GridLineOptions*](gridlineoptions.md)

Defined in: [index.esm.d.ts:2785](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2785)

___

### max

• **max**: *number*

User defined maximum value for the scale, overrides maximum value from data.

Defined in: [index.esm.d.ts:2777](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2777)

___

### min

• **min**: *number*

User defined minimum value for the scale, overrides minimum value from data.

Defined in: [index.esm.d.ts:2772](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2772)

___

### offset

• **offset**: *boolean*

  If true, extra space is added to the both edges and the axis is scaled to fit into the chart area. This is set to true for a bar chart by default.

**`default`** false

Defined in: [index.esm.d.ts:2783](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2783)

___

### position

• **position**: *left* \| *right* \| *bottom* \| *top* \| *center* \| { [scale: string]: *number*;  }

Position of the axis.

Defined in: [index.esm.d.ts:2763](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2763)

___

### reverse

• **reverse**: *boolean*

Reverse the scale.

**`default`** false

Inherited from: [CoreScaleOptions](corescaleoptions.md).[reverse](corescaleoptions.md#reverse)

Defined in: [index.esm.d.ts:1082](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1082)

___

### stacked

• `Optional` **stacked**: *boolean* \| *single*

  If true, data will be comprised between datasets of data

**`default`** false

Defined in: [index.esm.d.ts:2802](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2802)

___

### ticks

• **ticks**: [*TickOptions*](tickoptions.md) & { `align`: *start* \| *end* \| *center* ; `autoSkip`: *boolean* ; `autoSkipPadding`: *number* ; `crossAlign`: *center* \| *near* \| *far* ; `labelOffset`: *number* ; `maxRotation`: *number* ; `minRotation`: *number* ; `mirror`: *boolean* ; `padding`: *number* ; `sampleSize`: *number*  }

Defined in: [index.esm.d.ts:2804](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2804)

___

### title

• **title**: *object*

#### Type declaration:

Name | Type |
:------ | :------ |
`color` | [*Color*](../README.md#color) |
`display` | *boolean* |
`font` | [*FontSpec*](fontspec.md) |
`padding` | *object* |
`padding.bottom` | *number* |
`padding.top` | *number* |
`text` | *string* \| *string*[] |

Defined in: [index.esm.d.ts:2787](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2787)

___

### weight

• **weight**: *number*

The weight used to sort the axis. Higher weights are further away from the chart area.

**`default`** true

Inherited from: [CoreScaleOptions](corescaleoptions.md).[weight](corescaleoptions.md#weight)

Defined in: [index.esm.d.ts:1087](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1087)

## Methods

### afterBuildTicks

▸ **afterBuildTicks**(`axis`: [*Scale*](../classes/scale.md)<[*CoreScaleOptions*](corescaleoptions.md)\>): *void*

Callback that runs after ticks are created. Useful for filtering ticks.

#### Parameters:

Name | Type |
:------ | :------ |
`axis` | [*Scale*](../classes/scale.md)<[*CoreScaleOptions*](corescaleoptions.md)\> |

**Returns:** *void*

Inherited from: [CoreScaleOptions](corescaleoptions.md)

Defined in: [index.esm.d.ts:1115](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1115)

___

### afterCalculateTickRotation

▸ **afterCalculateTickRotation**(`axis`: [*Scale*](../classes/scale.md)<[*CoreScaleOptions*](corescaleoptions.md)\>): *void*

Callback that runs after tick rotation is determined.

#### Parameters:

Name | Type |
:------ | :------ |
`axis` | [*Scale*](../classes/scale.md)<[*CoreScaleOptions*](corescaleoptions.md)\> |

**Returns:** *void*

Inherited from: [CoreScaleOptions](corescaleoptions.md)

Defined in: [index.esm.d.ts:1131](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1131)

___

### afterDataLimits

▸ **afterDataLimits**(`axis`: [*Scale*](../classes/scale.md)<[*CoreScaleOptions*](corescaleoptions.md)\>): *void*

Callback that runs after data limits are determined.

#### Parameters:

Name | Type |
:------ | :------ |
`axis` | [*Scale*](../classes/scale.md)<[*CoreScaleOptions*](corescaleoptions.md)\> |

**Returns:** *void*

Inherited from: [CoreScaleOptions](corescaleoptions.md)

Defined in: [index.esm.d.ts:1107](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1107)

___

### afterFit

▸ **afterFit**(`axis`: [*Scale*](../classes/scale.md)<[*CoreScaleOptions*](corescaleoptions.md)\>): *void*

Callback that runs after the scale fits to the canvas.

#### Parameters:

Name | Type |
:------ | :------ |
`axis` | [*Scale*](../classes/scale.md)<[*CoreScaleOptions*](corescaleoptions.md)\> |

**Returns:** *void*

Inherited from: [CoreScaleOptions](corescaleoptions.md)

Defined in: [index.esm.d.ts:1139](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1139)

___

### afterSetDimensions

▸ **afterSetDimensions**(`axis`: [*Scale*](../classes/scale.md)<[*CoreScaleOptions*](corescaleoptions.md)\>): *void*

Callback that runs after dimensions are set.

#### Parameters:

Name | Type |
:------ | :------ |
`axis` | [*Scale*](../classes/scale.md)<[*CoreScaleOptions*](corescaleoptions.md)\> |

**Returns:** *void*

Inherited from: [CoreScaleOptions](corescaleoptions.md)

Defined in: [index.esm.d.ts:1099](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1099)

___

### afterTickToLabelConversion

▸ **afterTickToLabelConversion**(`axis`: [*Scale*](../classes/scale.md)<[*CoreScaleOptions*](corescaleoptions.md)\>): *void*

Callback that runs after ticks are converted into strings.

#### Parameters:

Name | Type |
:------ | :------ |
`axis` | [*Scale*](../classes/scale.md)<[*CoreScaleOptions*](corescaleoptions.md)\> |

**Returns:** *void*

Inherited from: [CoreScaleOptions](corescaleoptions.md)

Defined in: [index.esm.d.ts:1123](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1123)

___

### afterUpdate

▸ **afterUpdate**(`axis`: [*Scale*](../classes/scale.md)<[*CoreScaleOptions*](corescaleoptions.md)\>): *void*

Callback that runs at the end of the update process.

#### Parameters:

Name | Type |
:------ | :------ |
`axis` | [*Scale*](../classes/scale.md)<[*CoreScaleOptions*](corescaleoptions.md)\> |

**Returns:** *void*

Inherited from: [CoreScaleOptions](corescaleoptions.md)

Defined in: [index.esm.d.ts:1143](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1143)

___

### beforeBuildTicks

▸ **beforeBuildTicks**(`axis`: [*Scale*](../classes/scale.md)<[*CoreScaleOptions*](corescaleoptions.md)\>): *void*

Callback that runs before ticks are created.

#### Parameters:

Name | Type |
:------ | :------ |
`axis` | [*Scale*](../classes/scale.md)<[*CoreScaleOptions*](corescaleoptions.md)\> |

**Returns:** *void*

Inherited from: [CoreScaleOptions](corescaleoptions.md)

Defined in: [index.esm.d.ts:1111](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1111)

___

### beforeCalculateTickRotation

▸ **beforeCalculateTickRotation**(`axis`: [*Scale*](../classes/scale.md)<[*CoreScaleOptions*](corescaleoptions.md)\>): *void*

Callback that runs before tick rotation is determined.

#### Parameters:

Name | Type |
:------ | :------ |
`axis` | [*Scale*](../classes/scale.md)<[*CoreScaleOptions*](corescaleoptions.md)\> |

**Returns:** *void*

Inherited from: [CoreScaleOptions](corescaleoptions.md)

Defined in: [index.esm.d.ts:1127](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1127)

___

### beforeDataLimits

▸ **beforeDataLimits**(`axis`: [*Scale*](../classes/scale.md)<[*CoreScaleOptions*](corescaleoptions.md)\>): *void*

Callback that runs before data limits are determined.

#### Parameters:

Name | Type |
:------ | :------ |
`axis` | [*Scale*](../classes/scale.md)<[*CoreScaleOptions*](corescaleoptions.md)\> |

**Returns:** *void*

Inherited from: [CoreScaleOptions](corescaleoptions.md)

Defined in: [index.esm.d.ts:1103](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1103)

___

### beforeFit

▸ **beforeFit**(`axis`: [*Scale*](../classes/scale.md)<[*CoreScaleOptions*](corescaleoptions.md)\>): *void*

Callback that runs before the scale fits to the canvas.

#### Parameters:

Name | Type |
:------ | :------ |
`axis` | [*Scale*](../classes/scale.md)<[*CoreScaleOptions*](corescaleoptions.md)\> |

**Returns:** *void*

Inherited from: [CoreScaleOptions](corescaleoptions.md)

Defined in: [index.esm.d.ts:1135](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1135)

___

### beforeSetDimensions

▸ **beforeSetDimensions**(`axis`: [*Scale*](../classes/scale.md)<[*CoreScaleOptions*](corescaleoptions.md)\>): *void*

Callback that runs before dimensions are set.

#### Parameters:

Name | Type |
:------ | :------ |
`axis` | [*Scale*](../classes/scale.md)<[*CoreScaleOptions*](corescaleoptions.md)\> |

**Returns:** *void*

Inherited from: [CoreScaleOptions](corescaleoptions.md)

Defined in: [index.esm.d.ts:1095](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1095)

___

### beforeTickToLabelConversion

▸ **beforeTickToLabelConversion**(`axis`: [*Scale*](../classes/scale.md)<[*CoreScaleOptions*](corescaleoptions.md)\>): *void*

Callback that runs before ticks are converted into strings.

#### Parameters:

Name | Type |
:------ | :------ |
`axis` | [*Scale*](../classes/scale.md)<[*CoreScaleOptions*](corescaleoptions.md)\> |

**Returns:** *void*

Inherited from: [CoreScaleOptions](corescaleoptions.md)

Defined in: [index.esm.d.ts:1119](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1119)

___

### beforeUpdate

▸ **beforeUpdate**(`axis`: [*Scale*](../classes/scale.md)<[*CoreScaleOptions*](corescaleoptions.md)\>): *void*

Callback called before the update process starts.

#### Parameters:

Name | Type |
:------ | :------ |
`axis` | [*Scale*](../classes/scale.md)<[*CoreScaleOptions*](corescaleoptions.md)\> |

**Returns:** *void*

Inherited from: [CoreScaleOptions](corescaleoptions.md)

Defined in: [index.esm.d.ts:1091](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1091)
