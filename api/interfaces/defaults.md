---
title: "Interface: Defaults"
---

# Interface: Defaults

## Hierarchy

* [*CoreChartOptions*](corechartoptions.md)<[*ChartType*](../README.md#charttype)\>

* [*ElementChartOptions*](elementchartoptions.md)

* [*PluginChartOptions*](pluginchartoptions.md)<[*ChartType*](../README.md#charttype)\>

  ↳ **Defaults**

## Properties

### animation

• **animation**: *false* \| [*AnimationSpec*](../README.md#animationspec)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*\> & { `onComplete?`: (`event`: [*AnimationEvent*](animationevent.md)) => *void* ; `onProgress?`: (`event`: [*AnimationEvent*](animationevent.md)) => *void*  }

Inherited from: [CoreChartOptions](corechartoptions.md).[animation](corechartoptions.md#animation)

Defined in: [index.esm.d.ts:1533](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1533)

___

### animations

• **animations**: [*AnimationsSpec*](../README.md#animationsspec)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*\>

Inherited from: [CoreChartOptions](corechartoptions.md).[animations](corechartoptions.md#animations)

Defined in: [index.esm.d.ts:1543](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1543)

___

### aspectRatio

• **aspectRatio**: *number*

Canvas aspect ratio (i.e. width / height, a value of 1 representing a square canvas). Note that this option is ignored if the height is explicitly defined either as attribute or via the style.

**`default`** 2

Inherited from: [CoreChartOptions](corechartoptions.md).[aspectRatio](corechartoptions.md#aspectratio)

Defined in: [index.esm.d.ts:1399](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1399)

___

### backgroundColor

• **backgroundColor**: [*Color*](../README.md#color)

base background color

**`see`** Defaults.backgroundColor

Inherited from: [CoreChartOptions](corechartoptions.md).[backgroundColor](corechartoptions.md#backgroundcolor)

Defined in: [index.esm.d.ts:1373](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1373)

___

### borderColor

• **borderColor**: [*Color*](../README.md#color)

base border color

**`see`** Defaults.borderColor

Inherited from: [CoreChartOptions](corechartoptions.md).[borderColor](corechartoptions.md#bordercolor)

Defined in: [index.esm.d.ts:1378](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1378)

___

### color

• **color**: [*Color*](../README.md#color)

base color

**`see`** Defaults.color

Inherited from: [CoreChartOptions](corechartoptions.md).[color](corechartoptions.md#color)

Defined in: [index.esm.d.ts:1368](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1368)

___

### datasets

• **datasets**: *object*

#### Type declaration:

Name | Type |
:------ | :------ |
`bar` |  |
`bubble` |  |
`doughnut` |  |
`line` |  |
`pie` |  |
`polarArea` |  |
`radar` |  |
`scatter` |  |

Inherited from: [CoreChartOptions](corechartoptions.md).[datasets](corechartoptions.md#datasets)

Defined in: [index.esm.d.ts:1354](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1354)

___

### devicePixelRatio

• **devicePixelRatio**: *number*

Override the window's default devicePixelRatio.

**`default`** window.devicePixelRatio

Inherited from: [CoreChartOptions](corechartoptions.md).[devicePixelRatio](corechartoptions.md#devicepixelratio)

Defined in: [index.esm.d.ts:1416](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1416)

___

### elements

• **elements**: *Partial*<[*ElementOptionsByType*](elementoptionsbytype.md)\>

Inherited from: [ElementChartOptions](elementchartoptions.md).[elements](elementchartoptions.md#elements)

Defined in: [index.esm.d.ts:1897](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1897)

___

### events

• **events**: (*mousemove* \| *mouseout* \| *click* \| *touchstart* \| *touchmove*)[]

The events option defines the browser events that the chart should listen to for tooltips and hovering.

**`default`** ['mousemove', 'mouseout', 'click', 'touchstart', 'touchmove']

Inherited from: [CoreChartOptions](corechartoptions.md).[events](corechartoptions.md#events)

Defined in: [index.esm.d.ts:1426](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1426)

___

### font

• **font**: [*FontSpec*](fontspec.md)

base font

**`see`** Defaults.font

Inherited from: [CoreChartOptions](corechartoptions.md).[font](corechartoptions.md#font)

Defined in: [index.esm.d.ts:1383](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1383)

___

### hover

• **hover**: [*CoreInteractionOptions*](coreinteractionoptions.md)

Inherited from: [CoreChartOptions](corechartoptions.md).[hover](corechartoptions.md#hover)

Defined in: [index.esm.d.ts:1420](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1420)

___

### indexAxis

• **indexAxis**: *x* \| *y*

The base axis of the chart. 'x' for vertical charts and 'y' for horizontal charts.

**`default`** 'x'

Inherited from: [CoreChartOptions](corechartoptions.md).[indexAxis](corechartoptions.md#indexaxis)

Defined in: [index.esm.d.ts:1362](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1362)

___

### interaction

• **interaction**: [*CoreInteractionOptions*](coreinteractionoptions.md)

Inherited from: [CoreChartOptions](corechartoptions.md).[interaction](corechartoptions.md#interaction)

Defined in: [index.esm.d.ts:1418](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1418)

___

### layout

• **layout**: *object*

#### Type declaration:

Name | Type |
:------ | :------ |
`padding` | [*Scriptable*](../README.md#scriptable)<number \| [*ChartArea*](chartarea.md), [*ScriptableContext*](scriptablecontext.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*\>\> |

Inherited from: [CoreChartOptions](corechartoptions.md).[layout](corechartoptions.md#layout)

Defined in: [index.esm.d.ts:1438](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1438)

___

### locale

• **locale**: *string*

Locale used for number formatting (using `Intl.NumberFormat`).

**`default`** user's browser setting

Inherited from: [CoreChartOptions](corechartoptions.md).[locale](corechartoptions.md#locale)

Defined in: [index.esm.d.ts:1405](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1405)

___

### maintainAspectRatio

• **maintainAspectRatio**: *boolean*

Maintain the original canvas aspect ratio (width / height) when resizing.

**`default`** true

Inherited from: [CoreChartOptions](corechartoptions.md).[maintainAspectRatio](corechartoptions.md#maintainaspectratio)

Defined in: [index.esm.d.ts:1393](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1393)

___

### normalized

• **normalized**: *boolean*

Chart.js is fastest if you provide data with indices that are unique, sorted, and consistent across datasets and provide the normalized: true option to let Chart.js know that you have done so.

Inherited from: [CoreChartOptions](corechartoptions.md).[normalized](corechartoptions.md#normalized)

Defined in: [index.esm.d.ts:52](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L52)

___

### parsing

• **parsing**: *false* \| { [key: string]: *string*;  }

How to parse the dataset. The parsing can be disabled by specifying parsing: false at chart options or dataset. If parsing is disabled, data must be sorted and in the formats the associated chart type and scales use internally.

Inherited from: [CoreChartOptions](corechartoptions.md).[parsing](corechartoptions.md#parsing)

Defined in: [index.esm.d.ts:43](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L43)

___

### plugins

• **plugins**: [*PluginOptionsByType*](pluginoptionsbytype.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*\>

Inherited from: [PluginChartOptions](pluginchartoptions.md).[plugins](pluginchartoptions.md#plugins)

Defined in: [index.esm.d.ts:2626](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2626)

___

### responsive

• **responsive**: *boolean*

Resizes the chart canvas when its container does (important note...).

**`default`** true

Inherited from: [CoreChartOptions](corechartoptions.md).[responsive](corechartoptions.md#responsive)

Defined in: [index.esm.d.ts:1388](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1388)

___

### scale

• **scale**: [*ScaleOptionsByType*](../README.md#scaleoptionsbytype)<*linear* \| *logarithmic* \| *category* \| *time* \| *timeseries* \| *radialLinear*\>

Defined in: [index.esm.d.ts:609](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L609)

___

### scales

• **scales**: *object*

#### Type declaration:

Name | Type |
:------ | :------ |
`category` |  |
`linear` |  |
`logarithmic` |  |
`radialLinear` |  |
`time` |  |
`timeseries` |  |

Defined in: [index.esm.d.ts:610](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L610)

___

### transitions

• **transitions**: [*TransitionsSpec*](../README.md#transitionsspec)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*\>

Inherited from: [CoreChartOptions](corechartoptions.md).[transitions](corechartoptions.md#transitions)

Defined in: [index.esm.d.ts:1544](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1544)

## Methods

### describe

▸ **describe**(`scope`: *string*, `values`: *Record*<string, unknown\>): *Record*<string, unknown\>

#### Parameters:

Name | Type |
:------ | :------ |
`scope` | *string* |
`values` | *Record*<string, unknown\> |

**Returns:** *Record*<string, unknown\>

Defined in: [index.esm.d.ts:618](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L618)

___

### get

▸ **get**(`scope`: *string*): *Record*<string, unknown\>

#### Parameters:

Name | Type |
:------ | :------ |
`scope` | *string* |

**Returns:** *Record*<string, unknown\>

Defined in: [index.esm.d.ts:616](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L616)

___

### onClick

▸ **onClick**(`event`: [*ChartEvent*](chartevent.md), `elements`: [*ActiveElement*](activeelement.md)[], `chart`: [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\>): *void*

Called if the event is of type 'mouseup' or 'click'. Passed the event, an array of active elements, and the chart.

#### Parameters:

Name | Type |
:------ | :------ |
`event` | [*ChartEvent*](chartevent.md) |
`elements` | [*ActiveElement*](activeelement.md)[] |
`chart` | [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\> |

**Returns:** *void*

Inherited from: [CoreChartOptions](corechartoptions.md)

Defined in: [index.esm.d.ts:1436](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1436)

___

### onHover

▸ **onHover**(`event`: [*ChartEvent*](chartevent.md), `elements`: [*ActiveElement*](activeelement.md)[], `chart`: [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\>): *void*

Called when any of the events fire. Passed the event, an array of active elements (bars, points, etc), and the chart.

#### Parameters:

Name | Type |
:------ | :------ |
`event` | [*ChartEvent*](chartevent.md) |
`elements` | [*ActiveElement*](activeelement.md)[] |
`chart` | [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\> |

**Returns:** *void*

Inherited from: [CoreChartOptions](corechartoptions.md)

Defined in: [index.esm.d.ts:1431](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1431)

___

### onResize

▸ **onResize**(`chart`: [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\>, `size`: { `height`: *number* ; `width`: *number*  }): *void*

Called when a resize occurs. Gets passed two arguments: the chart instance and the new size.

#### Parameters:

Name | Type |
:------ | :------ |
`chart` | [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\> |
`size` | *object* |
`size.height` | *number* |
`size.width` | *number* |

**Returns:** *void*

Inherited from: [CoreChartOptions](corechartoptions.md)

Defined in: [index.esm.d.ts:1410](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1410)

___

### override

▸ **override**(`scope`: *string*, `values`: *Record*<string, unknown\>): *Record*<string, unknown\>

#### Parameters:

Name | Type |
:------ | :------ |
`scope` | *string* |
`values` | *Record*<string, unknown\> |

**Returns:** *Record*<string, unknown\>

Defined in: [index.esm.d.ts:619](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L619)

___

### route

▸ **route**(`scope`: *string*, `name`: *string*, `targetScope`: *string*, `targetName`: *string*): *void*

Routes the named defaults to fallback to another scope/name.
This routing is useful when those target values, like defaults.color, are changed runtime.
If the values would be copied, the runtime change would not take effect. By routing, the
fallback is evaluated at each access, so its always up to date.

Example:

  defaults.route('elements.arc', 'backgroundColor', '', 'color')
   - reads the backgroundColor from defaults.color when undefined locally

#### Parameters:

Name | Type | Description |
:------ | :------ | :------ |
`scope` | *string* | Scope this route applies to.   |
`name` | *string* | Property name that should be routed to different namespace when not defined here.   |
`targetScope` | *string* | The namespace where those properties should be routed to. Empty string ('') is the root of defaults.   |
`targetName` | *string* | The target name in the target scope the property should be routed to.    |

**Returns:** *void*

Defined in: [index.esm.d.ts:638](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L638)

___

### set

▸ **set**(`values`: *Record*<string, unknown\>): *Record*<string, unknown\>

#### Parameters:

Name | Type |
:------ | :------ |
`values` | *Record*<string, unknown\> |

**Returns:** *Record*<string, unknown\>

Defined in: [index.esm.d.ts:614](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L614)

▸ **set**(`scope`: *string*, `values`: *Record*<string, unknown\>): *Record*<string, unknown\>

#### Parameters:

Name | Type |
:------ | :------ |
`scope` | *string* |
`values` | *Record*<string, unknown\> |

**Returns:** *Record*<string, unknown\>

Defined in: [index.esm.d.ts:615](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L615)
