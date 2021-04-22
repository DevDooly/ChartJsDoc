---
title: "Interface: CoreChartOptions<TType>"
---

# Interface: CoreChartOptions<TType\>

## Type parameters

Name | Type |
:------ | :------ |
`TType` | [*ChartType*](../README.md#charttype) |

## Hierarchy

* [*ParsingOptions*](parsingoptions.md)

* [*AnimationOptions*](../README.md#animationoptions)<TType\>

  ↳ **CoreChartOptions**

  ↳↳ [*Defaults*](defaults.md)

## Properties

### animation

• **animation**: *false* \| [*AnimationSpec*](../README.md#animationspec)<TType\> & { `onComplete?`: (`event`: [*AnimationEvent*](animationevent.md)) => *void* ; `onProgress?`: (`event`: [*AnimationEvent*](animationevent.md)) => *void*  }

Inherited from: AnimationOptions.animation

Defined in: [index.esm.d.ts:1533](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1533)

___

### animations

• **animations**: [*AnimationsSpec*](../README.md#animationsspec)<TType\>

Inherited from: AnimationOptions.animations

Defined in: [index.esm.d.ts:1543](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1543)

___

### aspectRatio

• **aspectRatio**: *number*

Canvas aspect ratio (i.e. width / height, a value of 1 representing a square canvas). Note that this option is ignored if the height is explicitly defined either as attribute or via the style.

**`default`** 2

Defined in: [index.esm.d.ts:1399](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1399)

___

### backgroundColor

• **backgroundColor**: [*Color*](../README.md#color)

base background color

**`see`** Defaults.backgroundColor

Defined in: [index.esm.d.ts:1373](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1373)

___

### borderColor

• **borderColor**: [*Color*](../README.md#color)

base border color

**`see`** Defaults.borderColor

Defined in: [index.esm.d.ts:1378](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1378)

___

### color

• **color**: [*Color*](../README.md#color)

base color

**`see`** Defaults.color

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

Defined in: [index.esm.d.ts:1354](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1354)

___

### devicePixelRatio

• **devicePixelRatio**: *number*

Override the window's default devicePixelRatio.

**`default`** window.devicePixelRatio

Defined in: [index.esm.d.ts:1416](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1416)

___

### events

• **events**: (*mousemove* \| *mouseout* \| *click* \| *touchstart* \| *touchmove*)[]

The events option defines the browser events that the chart should listen to for tooltips and hovering.

**`default`** ['mousemove', 'mouseout', 'click', 'touchstart', 'touchmove']

Defined in: [index.esm.d.ts:1426](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1426)

___

### font

• **font**: [*FontSpec*](fontspec.md)

base font

**`see`** Defaults.font

Defined in: [index.esm.d.ts:1383](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1383)

___

### hover

• **hover**: [*CoreInteractionOptions*](coreinteractionoptions.md)

Defined in: [index.esm.d.ts:1420](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1420)

___

### indexAxis

• **indexAxis**: *x* \| *y*

The base axis of the chart. 'x' for vertical charts and 'y' for horizontal charts.

**`default`** 'x'

Defined in: [index.esm.d.ts:1362](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1362)

___

### interaction

• **interaction**: [*CoreInteractionOptions*](coreinteractionoptions.md)

Defined in: [index.esm.d.ts:1418](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1418)

___

### layout

• **layout**: *object*

#### Type declaration:

Name | Type |
:------ | :------ |
`padding` | [*Scriptable*](../README.md#scriptable)<number \| [*ChartArea*](chartarea.md), [*ScriptableContext*](scriptablecontext.md)<TType\>\> |

Defined in: [index.esm.d.ts:1438](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1438)

___

### locale

• **locale**: *string*

Locale used for number formatting (using `Intl.NumberFormat`).

**`default`** user's browser setting

Defined in: [index.esm.d.ts:1405](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1405)

___

### maintainAspectRatio

• **maintainAspectRatio**: *boolean*

Maintain the original canvas aspect ratio (width / height) when resizing.

**`default`** true

Defined in: [index.esm.d.ts:1393](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1393)

___

### normalized

• **normalized**: *boolean*

Chart.js is fastest if you provide data with indices that are unique, sorted, and consistent across datasets and provide the normalized: true option to let Chart.js know that you have done so.

Inherited from: [ParsingOptions](parsingoptions.md).[normalized](parsingoptions.md#normalized)

Defined in: [index.esm.d.ts:52](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L52)

___

### parsing

• **parsing**: *false* \| { [key: string]: *string*;  }

How to parse the dataset. The parsing can be disabled by specifying parsing: false at chart options or dataset. If parsing is disabled, data must be sorted and in the formats the associated chart type and scales use internally.

Inherited from: [ParsingOptions](parsingoptions.md).[parsing](parsingoptions.md#parsing)

Defined in: [index.esm.d.ts:43](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L43)

___

### responsive

• **responsive**: *boolean*

Resizes the chart canvas when its container does (important note...).

**`default`** true

Defined in: [index.esm.d.ts:1388](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1388)

___

### transitions

• **transitions**: [*TransitionsSpec*](../README.md#transitionsspec)<TType\>

Inherited from: AnimationOptions.transitions

Defined in: [index.esm.d.ts:1544](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1544)

## Methods

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

Defined in: [index.esm.d.ts:1410](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1410)
