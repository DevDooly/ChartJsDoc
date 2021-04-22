---
title: "Class: Chart<TType, TData, TLabel>"
---

# Class: Chart<TType, TData, TLabel\>

## Type parameters

Name | Type | Default |
:------ | :------ | :------ |
`TType` | [*ChartType*](../README.md#charttype) | [*ChartType*](../README.md#charttype) |
`TData` | - | TType[] |
`TLabel` | - | *unknown* |

## Constructors

### constructor

\+ **new Chart**<TType, TData, TLabel\>(`item`: [*ChartItem*](../README.md#chartitem), `config`: [*ChartConfiguration*](../interfaces/chartconfiguration.md)<TType, TData, TLabel\>): [*Chart*](chart.md)<TType, TData, TLabel\>

#### Type parameters:

Name | Type | Default |
:------ | :------ | :------ |
`TType` | *bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar* | *bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar* |
`TData` | - | [*ChartTypeRegistry*](../interfaces/charttyperegistry.md)[TType][*defaultDataPoint*][] |
`TLabel` | - | *unknown* |

#### Parameters:

Name | Type |
:------ | :------ |
`item` | [*ChartItem*](../README.md#chartitem) |
`config` | [*ChartConfiguration*](../interfaces/chartconfiguration.md)<TType, TData, TLabel\> |

**Returns:** [*Chart*](chart.md)<TType, TData, TLabel\>

Defined in: [index.esm.d.ts:455](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L455)

## Properties

### aspectRatio

• `Readonly` **aspectRatio**: *number*

Defined in: [index.esm.d.ts:447](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L447)

___

### attached

• `Readonly` **attached**: *boolean*

Defined in: [index.esm.d.ts:452](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L452)

___

### boxes

• `Readonly` **boxes**: [*LayoutItem*](../interfaces/layoutitem.md)[]

Defined in: [index.esm.d.ts:448](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L448)

___

### canvas

• `Readonly` **canvas**: HTMLCanvasElement

Defined in: [index.esm.d.ts:442](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L442)

___

### chartArea

• `Readonly` **chartArea**: [*ChartArea*](../interfaces/chartarea.md)

Defined in: [index.esm.d.ts:450](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L450)

___

### config

• `Readonly` **config**: [*ChartConfiguration*](../interfaces/chartconfiguration.md)<TType, TData, TLabel\>

Defined in: [index.esm.d.ts:444](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L444)

___

### ctx

• `Readonly` **ctx**: CanvasRenderingContext2D

Defined in: [index.esm.d.ts:443](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L443)

___

### currentDevicePixelRatio

• `Readonly` **currentDevicePixelRatio**: *number*

Defined in: [index.esm.d.ts:449](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L449)

___

### data

• **data**: [*ChartData*](../interfaces/chartdata.md)<TType, TData, TLabel\>

Defined in: [index.esm.d.ts:454](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L454)

___

### height

• `Readonly` **height**: *number*

Defined in: [index.esm.d.ts:446](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L446)

___

### id

• `Readonly` **id**: *string*

Defined in: [index.esm.d.ts:441](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L441)

___

### options

• **options**: *DeepPartial*<[*CoreChartOptions*](../interfaces/corechartoptions.md)<TType\> & [*ElementChartOptions*](../interfaces/elementchartoptions.md) & [*PluginChartOptions*](../interfaces/pluginchartoptions.md)<TType\> & [*DatasetChartOptions*](../README.md#datasetchartoptions)<TType\> & [*ScaleChartOptions*](../README.md#scalechartoptions)<TType\> & [*ChartTypeRegistry*](../interfaces/charttyperegistry.md)[TType][*chartOptions*]\>

Defined in: [index.esm.d.ts:455](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L455)

___

### platform

• `Readonly` **platform**: [*BasePlatform*](baseplatform.md)

Defined in: [index.esm.d.ts:440](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L440)

___

### scales

• `Readonly` **scales**: *object*

#### Type declaration:

Defined in: [index.esm.d.ts:451](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L451)

___

### width

• `Readonly` **width**: *number*

Defined in: [index.esm.d.ts:445](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L445)

___

### defaults

▪ `Static` `Readonly` **defaults**: [*Defaults*](../interfaces/defaults.md)

Defined in: [index.esm.d.ts:494](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L494)

___

### instances

▪ `Static` `Readonly` **instances**: *object*

#### Type declaration:

Defined in: [index.esm.d.ts:497](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L497)

___

### overrides

▪ `Static` `Readonly` **overrides**: [*Overrides*](../README.md#overrides)

Defined in: [index.esm.d.ts:495](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L495)

___

### registry

▪ `Static` `Readonly` **registry**: [*Registry*](../interfaces/registry.md)

Defined in: [index.esm.d.ts:498](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L498)

___

### version

▪ `Static` `Readonly` **version**: *string*

Defined in: [index.esm.d.ts:496](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L496)

## Methods

### bindEvents

▸ **bindEvents**(): *void*

**Returns:** *void*

Defined in: [index.esm.d.ts:488](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L488)

___

### buildOrUpdateControllers

▸ **buildOrUpdateControllers**(): *void*

**Returns:** *void*

Defined in: [index.esm.d.ts:465](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L465)

___

### buildOrUpdateScales

▸ **buildOrUpdateScales**(): *void*

**Returns:** *void*

Defined in: [index.esm.d.ts:464](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L464)

___

### clear

▸ **clear**(): [*Chart*](chart.md)<TType, TData, TLabel\>

**Returns:** [*Chart*](chart.md)<TType, TData, TLabel\>

Defined in: [index.esm.d.ts:459](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L459)

___

### destroy

▸ **destroy**(): *void*

**Returns:** *void*

Defined in: [index.esm.d.ts:486](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L486)

___

### draw

▸ **draw**(): *void*

**Returns:** *void*

Defined in: [index.esm.d.ts:469](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L469)

___

### ensureScalesHaveIDs

▸ **ensureScalesHaveIDs**(): *void*

**Returns:** *void*

Defined in: [index.esm.d.ts:463](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L463)

___

### getActiveElements

▸ **getActiveElements**(): [*ActiveElement*](../interfaces/activeelement.md)[]

**Returns:** [*ActiveElement*](../interfaces/activeelement.md)[]

Defined in: [index.esm.d.ts:483](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L483)

___

### getDataVisibility

▸ **getDataVisibility**(`index`: *number*): *boolean*

#### Parameters:

Name | Type |
:------ | :------ |
`index` | *number* |

**Returns:** *boolean*

Defined in: [index.esm.d.ts:479](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L479)

___

### getDatasetMeta

▸ **getDatasetMeta**(`datasetIndex`: *number*): [*ChartMeta*](../interfaces/chartmeta.md)<[*Element*](../README.md#element)<{}, {}\>, [*Element*](../README.md#element)<{}, {}\>\>

#### Parameters:

Name | Type |
:------ | :------ |
`datasetIndex` | *number* |

**Returns:** [*ChartMeta*](../interfaces/chartmeta.md)<[*Element*](../README.md#element)<{}, {}\>, [*Element*](../README.md#element)<{}, {}\>\>

Defined in: [index.esm.d.ts:474](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L474)

___

### getElementsAtEventForMode

▸ **getElementsAtEventForMode**(`e`: Event, `mode`: *string*, `options`: [*InteractionOptions*](../interfaces/interactionoptions.md), `useFinalPosition`: *boolean*): [*InteractionItem*](../interfaces/interactionitem.md)[]

#### Parameters:

Name | Type |
:------ | :------ |
`e` | Event |
`mode` | *string* |
`options` | [*InteractionOptions*](../interfaces/interactionoptions.md) |
`useFinalPosition` | *boolean* |

**Returns:** [*InteractionItem*](../interfaces/interactionitem.md)[]

Defined in: [index.esm.d.ts:471](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L471)

___

### getSortedVisibleDatasetMetas

▸ **getSortedVisibleDatasetMetas**(): [*ChartMeta*](../interfaces/chartmeta.md)<[*Element*](../README.md#element)<{}, {}\>, [*Element*](../README.md#element)<{}, {}\>\>[]

**Returns:** [*ChartMeta*](../interfaces/chartmeta.md)<[*Element*](../README.md#element)<{}, {}\>, [*Element*](../README.md#element)<{}, {}\>\>[]

Defined in: [index.esm.d.ts:473](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L473)

___

### getVisibleDatasetCount

▸ **getVisibleDatasetCount**(): *number*

**Returns:** *number*

Defined in: [index.esm.d.ts:475](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L475)

___

### hide

▸ **hide**(`datasetIndex`: *number*): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`datasetIndex` | *number* |

**Returns:** *void*

Defined in: [index.esm.d.ts:480](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L480)

___

### isDatasetVisible

▸ **isDatasetVisible**(`datasetIndex`: *number*): *boolean*

#### Parameters:

Name | Type |
:------ | :------ |
`datasetIndex` | *number* |

**Returns:** *boolean*

Defined in: [index.esm.d.ts:476](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L476)

___

### notifyPlugins

▸ **notifyPlugins**(`hook`: *string*, `args?`: *Record*<string, unknown\>): *boolean* \| *void*

#### Parameters:

Name | Type |
:------ | :------ |
`hook` | *string* |
`args?` | *Record*<string, unknown\> |

**Returns:** *boolean* \| *void*

Defined in: [index.esm.d.ts:492](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L492)

___

### render

▸ **render**(): *void*

**Returns:** *void*

Defined in: [index.esm.d.ts:468](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L468)

___

### reset

▸ **reset**(): *void*

**Returns:** *void*

Defined in: [index.esm.d.ts:466](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L466)

___

### resize

▸ **resize**(`width?`: *number*, `height?`: *number*): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`width?` | *number* |
`height?` | *number* |

**Returns:** *void*

Defined in: [index.esm.d.ts:462](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L462)

___

### setActiveElements

▸ **setActiveElements**(`active`: [*ActiveDataPoint*](../interfaces/activedatapoint.md)[]): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`active` | [*ActiveDataPoint*](../interfaces/activedatapoint.md)[] |

**Returns:** *void*

Defined in: [index.esm.d.ts:484](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L484)

___

### setDatasetVisibility

▸ **setDatasetVisibility**(`datasetIndex`: *number*, `visible`: *boolean*): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`datasetIndex` | *number* |
`visible` | *boolean* |

**Returns:** *void*

Defined in: [index.esm.d.ts:477](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L477)

___

### show

▸ **show**(`datasetIndex`: *number*): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`datasetIndex` | *number* |

**Returns:** *void*

Defined in: [index.esm.d.ts:481](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L481)

___

### stop

▸ **stop**(): [*Chart*](chart.md)<TType, TData, TLabel\>

**Returns:** [*Chart*](chart.md)<TType, TData, TLabel\>

Defined in: [index.esm.d.ts:460](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L460)

___

### toBase64Image

▸ **toBase64Image**(`type?`: *string*, `quality?`: *unknown*): *string*

#### Parameters:

Name | Type |
:------ | :------ |
`type?` | *string* |
`quality?` | *unknown* |

**Returns:** *string*

Defined in: [index.esm.d.ts:487](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L487)

___

### toggleDataVisibility

▸ **toggleDataVisibility**(`index`: *number*): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`index` | *number* |

**Returns:** *void*

Defined in: [index.esm.d.ts:478](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L478)

___

### unbindEvents

▸ **unbindEvents**(): *void*

**Returns:** *void*

Defined in: [index.esm.d.ts:489](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L489)

___

### update

▸ **update**(`mode?`: *resize* \| *reset* \| *none* \| *hide* \| *show* \| *normal* \| *active*): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`mode?` | *resize* \| *reset* \| *none* \| *hide* \| *show* \| *normal* \| *active* |

**Returns:** *void*

Defined in: [index.esm.d.ts:467](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L467)

___

### updateHoverStyle

▸ **updateHoverStyle**(`items`: [*Element*](../README.md#element)<{}, {}\>, `mode`: *dataset*, `enabled`: *boolean*): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`items` | [*Element*](../README.md#element)<{}, {}\> |
`mode` | *dataset* |
`enabled` | *boolean* |

**Returns:** *void*

Defined in: [index.esm.d.ts:490](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L490)

___

### getChart

▸ `Static`**getChart**(`key`: *string* \| HTMLCanvasElement \| CanvasRenderingContext2D): [*Chart*](chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](../interfaces/scatterdatapoint.md) \| [*BubbleDataPoint*](../interfaces/bubbledatapoint.md))[], unknown\>

#### Parameters:

Name | Type |
:------ | :------ |
`key` | *string* \| HTMLCanvasElement \| CanvasRenderingContext2D |

**Returns:** [*Chart*](chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](../interfaces/scatterdatapoint.md) \| [*BubbleDataPoint*](../interfaces/bubbledatapoint.md))[], unknown\>

Defined in: [index.esm.d.ts:499](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L499)

___

### register

▸ `Static`**register**(...`items`: [*ChartComponentLike*](../README.md#chartcomponentlike)[]): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`...items` | [*ChartComponentLike*](../README.md#chartcomponentlike)[] |

**Returns:** *void*

Defined in: [index.esm.d.ts:500](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L500)

___

### unregister

▸ `Static`**unregister**(...`items`: [*ChartComponentLike*](../README.md#chartcomponentlike)[]): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`...items` | [*ChartComponentLike*](../README.md#chartcomponentlike)[] |

**Returns:** *void*

Defined in: [index.esm.d.ts:501](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L501)
