---
title: "Interface: Plugin<TType, O>"
---

# Interface: Plugin<TType, O\>

## Type parameters

Name | Type | Default |
:------ | :------ | :------ |
`TType` | [*ChartType*](../README.md#charttype) | [*ChartType*](../README.md#charttype) |
`O` | - | AnyObject |

## Hierarchy

* [*ExtendedPlugin*](extendedplugin.md)<TType\>

  ↳ **Plugin**

## Properties

### id

• **id**: *string*

Defined in: [index.esm.d.ts:746](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L746)

## Methods

### afterBuildTicks

▸ `Optional`**afterBuildTicks**(`chart`: [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\>, `args`: { `scale`: [*Scale*](../classes/scale.md)<[*CoreScaleOptions*](corescaleoptions.md)\>  }, `options`: O): *void*

**`desc`** Called after scale has build its ticks. This hook is called separately for each scale in the chart.

#### Parameters:

Name | Type | Description |
:------ | :------ | :------ |
`chart` | [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\> | The chart instance.   |
`args` | *object* | The call arguments.   |
`args.scale` | [*Scale*](../classes/scale.md)<[*CoreScaleOptions*](corescaleoptions.md)\> | The scale.   |
`options` | O | The plugin options.    |

**Returns:** *void*

Defined in: [index.esm.d.ts:905](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L905)

___

### afterDataLimits

▸ `Optional`**afterDataLimits**(`chart`: [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\>, `args`: { `scale`: [*Scale*](../classes/scale.md)<[*CoreScaleOptions*](corescaleoptions.md)\>  }, `options`: O): *void*

**`desc`** Called after scale data limits are calculated. This hook is called separately for each scale in the chart.

#### Parameters:

Name | Type | Description |
:------ | :------ | :------ |
`chart` | [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\> | The chart instance.   |
`args` | *object* | The call arguments.   |
`args.scale` | [*Scale*](../classes/scale.md)<[*CoreScaleOptions*](corescaleoptions.md)\> | The scale.   |
`options` | O | The plugin options.    |

**Returns:** *void*

Defined in: [index.esm.d.ts:889](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L889)

___

### afterDatasetDraw

▸ `Optional`**afterDatasetDraw**(`chart`: [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\>, `args`: { `index`: *number* ; `meta`: [*ChartMeta*](chartmeta.md)<[*Element*](../README.md#element)<{}, {}\>, [*Element*](../README.md#element)<{}, {}\>\>  }, `options`: O): *void*

**`desc`** Called after the `chart` datasets at the given `args.index` have been drawn
(datasets are drawn in the reverse order). Note that this hook will not be called
if the datasets drawing has been previously cancelled.

#### Parameters:

Name | Type | Description |
:------ | :------ | :------ |
`chart` | [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\> | The chart instance.   |
`args` | *object* | The call arguments.   |
`args.index` | *number* | The dataset index.   |
`args.meta` | [*ChartMeta*](chartmeta.md)<[*Element*](../README.md#element)<{}, {}\>, [*Element*](../README.md#element)<{}, {}\>\> | The dataset metadata.   |
`options` | O | The plugin options.    |

**Returns:** *void*

Defined in: [index.esm.d.ts:987](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L987)

___

### afterDatasetUpdate

▸ `Optional`**afterDatasetUpdate**(`chart`: [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\>, `args`: { `cancelable`: *false* ; `index`: *number* ; `meta`: [*ChartMeta*](chartmeta.md)<[*Element*](../README.md#element)<{}, {}\>, [*Element*](../README.md#element)<{}, {}\>\> ; `mode`: *resize* \| *reset* \| *none* \| *hide* \| *show* \| *normal* \| *active*  }, `options`: O): *void*

**`desc`** Called after the `chart` datasets at the given `args.index` has been updated. Note
that this hook will not be called if the datasets update has been previously cancelled.

#### Parameters:

Name | Type | Description |
:------ | :------ | :------ |
`chart` | [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\> | The chart instance.   |
`args` | *object* | The call arguments.   |
`args.cancelable` | *false* | - |
`args.index` | *number* | The dataset index.   |
`args.meta` | [*ChartMeta*](chartmeta.md)<[*Element*](../README.md#element)<{}, {}\>, [*Element*](../README.md#element)<{}, {}\>\> | The dataset metadata.   |
`args.mode` | *resize* \| *reset* \| *none* \| *hide* \| *show* \| *normal* \| *active* | The update mode.   |
`options` | O | The plugin options.    |

**Returns:** *void*

Defined in: [index.esm.d.ts:864](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L864)

___

### afterDatasetsDraw

▸ `Optional`**afterDatasetsDraw**(`chart`: [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\>, `args`: *Record*<string, never\>, `options`: O, `cancelable`: *false*): *void*

**`desc`** Called after the `chart` datasets have been drawn. Note that this hook
will not be called if the datasets drawing has been previously cancelled.

#### Parameters:

Name | Type | Description |
:------ | :------ | :------ |
`chart` | [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\> | The chart instance.   |
`args` | *Record*<string, never\> | The call arguments.   |
`options` | O | The plugin options.    |
`cancelable` | *false* | - |

**Returns:** *void*

Defined in: [index.esm.d.ts:964](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L964)

___

### afterDatasetsUpdate

▸ `Optional`**afterDatasetsUpdate**(`chart`: [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\>, `args`: { `cancelable`: *true* ; `mode`: *resize* \| *reset* \| *none* \| *hide* \| *show* \| *normal* \| *active*  }, `options`: O): *void*

**`desc`** Called after the `chart` datasets have been updated. Note that this hook
will not be called if the datasets update has been previously cancelled.

**`since`** version 2.1.5

#### Parameters:

Name | Type | Description |
:------ | :------ | :------ |
`chart` | [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\> | The chart instance.   |
`args` | *object* | The call arguments.   |
`args.cancelable` | *true* | - |
`args.mode` | *resize* \| *reset* \| *none* \| *hide* \| *show* \| *normal* \| *active* | The update mode.   |
`options` | O | The plugin options.   |

**Returns:** *void*

Defined in: [index.esm.d.ts:841](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L841)

___

### afterDraw

▸ `Optional`**afterDraw**(`chart`: [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\>, `args`: *Record*<string, never\>, `options`: O): *void*

**`desc`** Called after the `chart` has been drawn. Note that this hook will not be called
if the drawing has been previously cancelled.

#### Parameters:

Name | Type | Description |
:------ | :------ | :------ |
`chart` | [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\> | The chart instance.   |
`args` | *Record*<string, never\> | The call arguments.   |
`options` | O | The plugin options.    |

**Returns:** *void*

Defined in: [index.esm.d.ts:947](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L947)

___

### afterEvent

▸ `Optional`**afterEvent**(`chart`: [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\>, `args`: { `cancelable`: *false* ; `changed?`: *boolean* ; `event`: [*ChartEvent*](chartevent.md) ; `replay`: *boolean*  }, `options`: O): *void*

**`desc`** Called after the `event` has been consumed. Note that this hook
will not be called if the `event` has been previously discarded.

#### Parameters:

Name | Type | Description |
:------ | :------ | :------ |
`chart` | [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\> | The chart instance.   |
`args` | *object* | The call arguments.   |
`args.cancelable` | *false* | - |
`args.changed?` | *boolean* | - |
`args.event` | [*ChartEvent*](chartevent.md) | The event object.   |
`args.replay` | *boolean* | True if this event is replayed from `Chart.update`   |
`options` | O | The plugin options.    |

**Returns:** *void*

Defined in: [index.esm.d.ts:1008](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1008)

___

### afterInit

▸ `Optional`**afterInit**(`chart`: [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\>, `args`: *Record*<string, never\>, `options`: O): *void*

**`desc`** Called after `chart` has been initialized and before the first update.

#### Parameters:

Name | Type | Description |
:------ | :------ | :------ |
`chart` | [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\> | The chart instance.   |
`args` | *Record*<string, never\> | The call arguments.   |
`options` | O | The plugin options.    |

**Returns:** *void*

Defined in: [index.esm.d.ts:785](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L785)

___

### afterLayout

▸ `Optional`**afterLayout**(`chart`: [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\>, `args`: *Record*<string, never\>, `options`: O): *void*

**`desc`** Called after the `chart` has been laid out. Note that this hook will not
be called if the layout update has been previously cancelled.

#### Parameters:

Name | Type | Description |
:------ | :------ | :------ |
`chart` | [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\> | The chart instance.   |
`args` | *Record*<string, never\> | The call arguments.   |
`options` | O | The plugin options.    |

**Returns:** *void*

Defined in: [index.esm.d.ts:913](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L913)

___

### afterRender

▸ `Optional`**afterRender**(`chart`: [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\>, `args`: *Record*<string, never\>, `options`: O): *void*

**`desc`** Called after the `chart` has been fully rendered (and animation completed). Note
that this hook will not be called if the rendering has been previously cancelled.

#### Parameters:

Name | Type | Description |
:------ | :------ | :------ |
`chart` | [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\> | The chart instance.   |
`args` | *Record*<string, never\> | The call arguments.   |
`options` | O | The plugin options.    |

**Returns:** *void*

Defined in: [index.esm.d.ts:930](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L930)

___

### afterTooltipDraw

▸ `Optional`**afterTooltipDraw**(`chart`: [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\>, `args`: { `tooltip`: [*TooltipModel*](tooltipmodel.md)<TType\>  }, `options`: *Record*<string, unknown\>): *void*

**`desc`** Called after drawing the `tooltip`. Note that this hook will not
be called if the tooltip drawing has been previously cancelled.

#### Parameters:

Name | Type | Description |
:------ | :------ | :------ |
`chart` | [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\> | The chart instance.   |
`args` | *object* | The call arguments.   |
`args.tooltip` | [*TooltipModel*](tooltipmodel.md)<TType\> | The tooltip.   |
`options` | *Record*<string, unknown\> | The plugin options.    |

**Returns:** *void*

Inherited from: [ExtendedPlugin](extendedplugin.md)

Defined in: [index.esm.d.ts:2388](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2388)

___

### afterUpdate

▸ `Optional`**afterUpdate**(`chart`: [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\>, `args`: { `mode`: *resize* \| *reset* \| *none* \| *hide* \| *show* \| *normal* \| *active*  }, `options`: O): *void*

**`desc`** Called after `chart` has been updated and before rendering. Note that this
hook will not be called if the chart update has been previously cancelled.

#### Parameters:

Name | Type | Description |
:------ | :------ | :------ |
`chart` | [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\> | The chart instance.   |
`args` | *object* | The call arguments.   |
`args.mode` | *resize* \| *reset* \| *none* \| *hide* \| *show* \| *normal* \| *active* | The update mode   |
`options` | O | The plugin options.    |

**Returns:** *void*

Defined in: [index.esm.d.ts:804](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L804)

___

### beforeBuildTicks

▸ `Optional`**beforeBuildTicks**(`chart`: [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\>, `args`: { `scale`: [*Scale*](../classes/scale.md)<[*CoreScaleOptions*](corescaleoptions.md)\>  }, `options`: O): *void*

**`desc`** Called before scale bulds its ticks. This hook is called separately for each scale in the chart.

#### Parameters:

Name | Type | Description |
:------ | :------ | :------ |
`chart` | [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\> | The chart instance.   |
`args` | *object* | The call arguments.   |
`args.scale` | [*Scale*](../classes/scale.md)<[*CoreScaleOptions*](corescaleoptions.md)\> | The scale.   |
`options` | O | The plugin options.    |

**Returns:** *void*

Defined in: [index.esm.d.ts:897](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L897)

___

### beforeDataLimits

▸ `Optional`**beforeDataLimits**(`chart`: [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\>, `args`: { `scale`: [*Scale*](../classes/scale.md)<[*CoreScaleOptions*](corescaleoptions.md)\>  }, `options`: O): *void*

**`desc`** Called before scale data limits are calculated. This hook is called separately for each scale in the chart.

#### Parameters:

Name | Type | Description |
:------ | :------ | :------ |
`chart` | [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\> | The chart instance.   |
`args` | *object* | The call arguments.   |
`args.scale` | [*Scale*](../classes/scale.md)<[*CoreScaleOptions*](corescaleoptions.md)\> | The scale.   |
`options` | O | The plugin options.    |

**Returns:** *void*

Defined in: [index.esm.d.ts:881](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L881)

___

### beforeDatasetDraw

▸ `Optional`**beforeDatasetDraw**(`chart`: [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\>, `args`: { `index`: *number* ; `meta`: [*ChartMeta*](chartmeta.md)<[*Element*](../README.md#element)<{}, {}\>, [*Element*](../README.md#element)<{}, {}\>\>  }, `options`: O): *boolean* \| *void*

**`desc`** Called before drawing the `chart` dataset at the given `args.index` (datasets
are drawn in the reverse order). If any plugin returns `false`, the datasets drawing
is cancelled until another `render` is triggered.

#### Parameters:

Name | Type | Description |
:------ | :------ | :------ |
`chart` | [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\> | The chart instance.   |
`args` | *object* | The call arguments.   |
`args.index` | *number* | The dataset index.   |
`args.meta` | [*ChartMeta*](chartmeta.md)<[*Element*](../README.md#element)<{}, {}\>, [*Element*](../README.md#element)<{}, {}\>\> | The dataset metadata.   |
`options` | O | The plugin options.   |

**Returns:** *boolean* \| *void*

`false` to cancel the chart datasets drawing.

Defined in: [index.esm.d.ts:976](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L976)

___

### beforeDatasetUpdate

▸ `Optional`**beforeDatasetUpdate**(`chart`: [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\>, `args`: { `cancelable`: *true* ; `index`: *number* ; `meta`: [*ChartMeta*](chartmeta.md)<[*Element*](../README.md#element)<{}, {}\>, [*Element*](../README.md#element)<{}, {}\>\> ; `mode`: *resize* \| *reset* \| *none* \| *hide* \| *show* \| *normal* \| *active*  }, `options`: O): *boolean* \| *void*

**`desc`** Called before updating the `chart` dataset at the given `args.index`. If any plugin
returns `false`, the datasets update is cancelled until another `update` is triggered.

#### Parameters:

Name | Type | Description |
:------ | :------ | :------ |
`chart` | [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\> | The chart instance.   |
`args` | *object* | The call arguments.   |
`args.cancelable` | *true* | - |
`args.index` | *number* | The dataset index.   |
`args.meta` | [*ChartMeta*](chartmeta.md)<[*Element*](../README.md#element)<{}, {}\>, [*Element*](../README.md#element)<{}, {}\>\> | The dataset metadata.   |
`args.mode` | *resize* \| *reset* \| *none* \| *hide* \| *show* \| *normal* \| *active* | The update mode.   |
`options` | O | The plugin options.   |

**Returns:** *boolean* \| *void*

`false` to cancel the chart datasets drawing.

Defined in: [index.esm.d.ts:853](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L853)

___

### beforeDatasetsDraw

▸ `Optional`**beforeDatasetsDraw**(`chart`: [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\>, `args`: { `cancelable`: *true*  }, `options`: O): *boolean* \| *void*

**`desc`** Called before drawing the `chart` datasets. If any plugin returns `false`,
the datasets drawing is cancelled until another `render` is triggered.

#### Parameters:

Name | Type | Description |
:------ | :------ | :------ |
`chart` | [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\> | The chart instance.   |
`args` | *object* | The call arguments.   |
`args.cancelable` | *true* | - |
`options` | O | The plugin options.   |

**Returns:** *boolean* \| *void*

`false` to cancel the chart datasets drawing.

Defined in: [index.esm.d.ts:956](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L956)

___

### beforeDatasetsUpdate

▸ `Optional`**beforeDatasetsUpdate**(`chart`: [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\>, `args`: { `mode`: *resize* \| *reset* \| *none* \| *hide* \| *show* \| *normal* \| *active*  }, `options`: O): *boolean* \| *void*

**`desc`** Called before updating the `chart` datasets. If any plugin returns `false`,
the datasets update is cancelled until another `update` is triggered.

**`since`** version 2.1.5

#### Parameters:

Name | Type | Description |
:------ | :------ | :------ |
`chart` | [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\> | The chart instance.   |
`args` | *object* | The call arguments.   |
`args.mode` | *resize* \| *reset* \| *none* \| *hide* \| *show* \| *normal* \| *active* | The update mode.   |
`options` | O | The plugin options.   |

**Returns:** *boolean* \| *void*

false to cancel the datasets update.

Defined in: [index.esm.d.ts:831](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L831)

___

### beforeDraw

▸ `Optional`**beforeDraw**(`chart`: [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\>, `args`: { `cancelable`: *true*  }, `options`: O): *boolean* \| *void*

**`desc`** Called before drawing `chart` at every animation frame. If any plugin returns `false`,
the frame drawing is cancelled untilanother `render` is triggered.

#### Parameters:

Name | Type | Description |
:------ | :------ | :------ |
`chart` | [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\> | The chart instance.   |
`args` | *object* | The call arguments.   |
`args.cancelable` | *true* | - |
`options` | O | The plugin options.   |

**Returns:** *boolean* \| *void*

`false` to cancel the chart drawing.

Defined in: [index.esm.d.ts:939](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L939)

___

### beforeElementsUpdate

▸ `Optional`**beforeElementsUpdate**(`chart`: [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\>, `args`: *Record*<string, never\>, `options`: O): *void*

**`desc`** Called during the update process, before any chart elements have been created.
This can be used for data decimation by changing the data array inside a dataset.

#### Parameters:

Name | Type | Description |
:------ | :------ | :------ |
`chart` | [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\> | The chart instance.   |
`args` | *Record*<string, never\> | The call arguments.   |
`options` | O | The plugin options.    |

**Returns:** *void*

Defined in: [index.esm.d.ts:812](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L812)

___

### beforeEvent

▸ `Optional`**beforeEvent**(`chart`: [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\>, `args`: { `cancelable`: *true* ; `event`: [*ChartEvent*](chartevent.md) ; `replay`: *boolean*  }, `options`: O): *boolean* \| *void*

**`desc`** Called before processing the specified `event`. If any plugin returns `false`,
the event will be discarded.

#### Parameters:

Name | Type | Description |
:------ | :------ | :------ |
`chart` | [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\> | The chart instance.   |
`args` | *object* | The call arguments.   |
`args.cancelable` | *true* | - |
`args.event` | [*ChartEvent*](chartevent.md) | The event object.   |
`args.replay` | *boolean* | True if this event is replayed from `Chart.update`   |
`options` | O | The plugin options.    |

**Returns:** *boolean* \| *void*

Defined in: [index.esm.d.ts:997](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L997)

___

### beforeInit

▸ `Optional`**beforeInit**(`chart`: [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\>, `args`: *Record*<string, never\>, `options`: O): *void*

**`desc`** Called before initializing `chart`.

#### Parameters:

Name | Type | Description |
:------ | :------ | :------ |
`chart` | [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\> | The chart instance.   |
`args` | *Record*<string, never\> | The call arguments.   |
`options` | O | The plugin options.    |

**Returns:** *void*

Defined in: [index.esm.d.ts:778](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L778)

___

### beforeLayout

▸ `Optional`**beforeLayout**(`chart`: [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\>, `args`: { `cancelable`: *true*  }, `options`: O): *boolean* \| *void*

**`desc`** Called before laying out `chart`. If any plugin returns `false`,
the layout update is cancelled until another `update` is triggered.

#### Parameters:

Name | Type | Description |
:------ | :------ | :------ |
`chart` | [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\> | The chart instance.   |
`args` | *object* | The call arguments.   |
`args.cancelable` | *true* | - |
`options` | O | The plugin options.   |

**Returns:** *boolean* \| *void*

`false` to cancel the chart layout.

Defined in: [index.esm.d.ts:873](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L873)

___

### beforeRender

▸ `Optional`**beforeRender**(`chart`: [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\>, `args`: { `cancelable`: *true*  }, `options`: O): *boolean* \| *void*

**`desc`** Called before rendering `chart`. If any plugin returns `false`,
the rendering is cancelled until another `render` is triggered.

#### Parameters:

Name | Type | Description |
:------ | :------ | :------ |
`chart` | [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\> | The chart instance.   |
`args` | *object* | The call arguments.   |
`args.cancelable` | *true* | - |
`options` | O | The plugin options.   |

**Returns:** *boolean* \| *void*

`false` to cancel the chart rendering.

Defined in: [index.esm.d.ts:922](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L922)

___

### beforeTooltipDraw

▸ `Optional`**beforeTooltipDraw**(`chart`: [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\>, `args`: { `tooltip`: [*TooltipModel*](tooltipmodel.md)<TType\>  }, `options`: *Record*<string, unknown\>): *boolean* \| *void*

**`desc`** Called before drawing the `tooltip`. If any plugin returns `false`,
the tooltip drawing is cancelled until another `render` is triggered.

#### Parameters:

Name | Type | Description |
:------ | :------ | :------ |
`chart` | [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\> | The chart instance.   |
`args` | *object* | The call arguments.   |
`args.tooltip` | [*TooltipModel*](tooltipmodel.md)<TType\> | The tooltip.   |
`options` | *Record*<string, unknown\> | The plugin options.   |

**Returns:** *boolean* \| *void*

`false` to cancel the chart tooltip drawing.

Inherited from: [ExtendedPlugin](extendedplugin.md)

Defined in: [index.esm.d.ts:2379](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2379)

___

### beforeUpdate

▸ `Optional`**beforeUpdate**(`chart`: [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\>, `args`: { `cancelable`: *true* ; `mode`: *resize* \| *reset* \| *none* \| *hide* \| *show* \| *normal* \| *active*  }, `options`: O): *boolean* \| *void*

**`desc`** Called before updating `chart`. If any plugin returns `false`, the update
is cancelled (and thus subsequent render(s)) until another `update` is triggered.

#### Parameters:

Name | Type | Description |
:------ | :------ | :------ |
`chart` | [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\> | The chart instance.   |
`args` | *object* | The call arguments.   |
`args.cancelable` | *true* | - |
`args.mode` | *resize* \| *reset* \| *none* \| *hide* \| *show* \| *normal* \| *active* | The update mode   |
`options` | O | The plugin options.   |

**Returns:** *boolean* \| *void*

`false` to cancel the chart update.

Defined in: [index.esm.d.ts:795](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L795)

___

### destroy

▸ `Optional`**destroy**(`chart`: [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\>, `args`: *Record*<string, never\>, `options`: O): *void*

Called after the chart has been destroyed.

#### Parameters:

Name | Type | Description |
:------ | :------ | :------ |
`chart` | [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\> | The chart instance.   |
`args` | *Record*<string, never\> | The call arguments.   |
`options` | O | The plugin options.    |

**Returns:** *void*

Defined in: [index.esm.d.ts:1023](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1023)

___

### install

▸ `Optional`**install**(`chart`: [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\>, `args`: *Record*<string, never\>, `options`: O): *void*

**`desc`** Called when plugin is installed for this chart instance. This hook is also invoked for disabled plugins (options === false).

**`since`** 3.0.0

#### Parameters:

Name | Type | Description |
:------ | :------ | :------ |
`chart` | [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\> | The chart instance.   |
`args` | *Record*<string, never\> | The call arguments.   |
`options` | O | The plugin options.   |

**Returns:** *void*

Defined in: [index.esm.d.ts:755](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L755)

___

### reset

▸ `Optional`**reset**(`chart`: [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\>, `args`: *Record*<string, never\>, `options`: O): *void*

**`desc`** Called during chart reset

**`since`** version 3.0.0

#### Parameters:

Name | Type | Description |
:------ | :------ | :------ |
`chart` | [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\> | The chart instance.   |
`args` | *Record*<string, never\> | The call arguments.   |
`options` | O | The plugin options.   |

**Returns:** *void*

Defined in: [index.esm.d.ts:820](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L820)

___

### resize

▸ `Optional`**resize**(`chart`: [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\>, `args`: { `size`: { `height`: *number* ; `width`: *number*  }  }, `options`: O): *void*

**`desc`** Called after the chart as been resized.

#### Parameters:

Name | Type | Description |
:------ | :------ | :------ |
`chart` | [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\> | The chart instance.   |
`args` | *object* | The call arguments.   |
`args.size` | *object* | The new canvas display size (eq. canvas.style width & height).   |
`args.size.height` | *number* | - |
`args.size.width` | *number* | - |
`options` | O | The plugin options.    |

**Returns:** *void*

Defined in: [index.esm.d.ts:1016](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1016)

___

### start

▸ `Optional`**start**(`chart`: [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\>, `args`: *Record*<string, never\>, `options`: O): *void*

**`desc`** Called when a plugin is starting. This happens when chart is created or plugin is enabled.

**`since`** 3.0.0

#### Parameters:

Name | Type | Description |
:------ | :------ | :------ |
`chart` | [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\> | The chart instance.   |
`args` | *Record*<string, never\> | The call arguments.   |
`options` | O | The plugin options.   |

**Returns:** *void*

Defined in: [index.esm.d.ts:763](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L763)

___

### stop

▸ `Optional`**stop**(`chart`: [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\>, `args`: *Record*<string, never\>, `options`: O): *void*

**`desc`** Called when a plugin stopping. This happens when chart is destroyed or plugin is disabled.

**`since`** 3.0.0

#### Parameters:

Name | Type | Description |
:------ | :------ | :------ |
`chart` | [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\> | The chart instance.   |
`args` | *Record*<string, never\> | The call arguments.   |
`options` | O | The plugin options.   |

**Returns:** *void*

Defined in: [index.esm.d.ts:771](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L771)

___

### uninstall

▸ `Optional`**uninstall**(`chart`: [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\>, `args`: *Record*<string, never\>, `options`: O): *void*

Called after chart is destroyed on all plugins that were installed for that chart. This hook is also invoked for disabled plugins (options === false).

**`since`** 3.0.0

#### Parameters:

Name | Type | Description |
:------ | :------ | :------ |
`chart` | [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\> | The chart instance.   |
`args` | *Record*<string, never\> | The call arguments.   |
`options` | O | The plugin options.   |

**Returns:** *void*

Defined in: [index.esm.d.ts:1031](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1031)
