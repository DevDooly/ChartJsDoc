---
title: "Chart.js - v3.1.1"
---

# Chart.js - v3.1.1

## Table of contents

### Enumerations

- [DecimationAlgorithm](enums/decimationalgorithm.md)
- [UpdateModeEnum](enums/updatemodeenum.md)

### Classes

- [Animation](classes/animation.md)
- [Animations](classes/animations.md)
- [Animator](classes/animator.md)
- [BasePlatform](classes/baseplatform.md)
- [BasicPlatform](classes/basicplatform.md)
- [Chart](classes/chart.md)
- [DatasetController](classes/datasetcontroller.md)
- [DomPlatform](classes/domplatform.md)
- [Scale](classes/scale.md)

### Interfaces

- [ActiveDataPoint](interfaces/activedatapoint.md)
- [ActiveElement](interfaces/activeelement.md)
- [AnimationEvent](interfaces/animationevent.md)
- [ArcBorderRadius](interfaces/arcborderradius.md)
- [ArcElement](interfaces/arcelement.md)
- [ArcHoverOptions](interfaces/archoveroptions.md)
- [ArcOptions](interfaces/arcoptions.md)
- [ArcProps](interfaces/arcprops.md)
- [BarControllerChartOptions](interfaces/barcontrollerchartoptions.md)
- [BarControllerDatasetOptions](interfaces/barcontrollerdatasetoptions.md)
- [BarElement](interfaces/barelement.md)
- [BarHoverOptions](interfaces/barhoveroptions.md)
- [BarOptions](interfaces/baroptions.md)
- [BarProps](interfaces/barprops.md)
- [BorderRadius](interfaces/borderradius.md)
- [BubbleControllerDatasetOptions](interfaces/bubblecontrollerdatasetoptions.md)
- [BubbleDataPoint](interfaces/bubbledatapoint.md)
- [CartesianScaleOptions](interfaces/cartesianscaleoptions.md)
- [CartesianScaleTypeRegistry](interfaces/cartesianscaletyperegistry.md)
- [ChartArea](interfaces/chartarea.md)
- [ChartComponent](interfaces/chartcomponent.md)
- [ChartConfiguration](interfaces/chartconfiguration.md)
- [ChartData](interfaces/chartdata.md)
- [ChartDatasetProperties](interfaces/chartdatasetproperties.md)
- [ChartEvent](interfaces/chartevent.md)
- [ChartMeta](interfaces/chartmeta.md)
- [ChartTypeRegistry](interfaces/charttyperegistry.md)
- [CommonElementOptions](interfaces/commonelementoptions.md)
- [CommonHoverOptions](interfaces/commonhoveroptions.md)
- [ComplexFillTarget](interfaces/complexfilltarget.md)
- [ControllerDatasetOptions](interfaces/controllerdatasetoptions.md)
- [CoreChartOptions](interfaces/corechartoptions.md)
- [CoreInteractionOptions](interfaces/coreinteractionoptions.md)
- [CoreScaleOptions](interfaces/corescaleoptions.md)
- [DatasetControllerChartComponent](interfaces/datasetcontrollerchartcomponent.md)
- [DateAdapter](interfaces/dateadapter.md)
- [Defaults](interfaces/defaults.md)
- [DoughnutAnimationOptions](interfaces/doughnutanimationoptions.md)
- [DoughnutController](interfaces/doughnutcontroller.md)
- [DoughnutControllerChartOptions](interfaces/doughnutcontrollerchartoptions.md)
- [DoughnutControllerDatasetOptions](interfaces/doughnutcontrollerdatasetoptions.md)
- [Element](interfaces/element.md)
- [ElementChartOptions](interfaces/elementchartoptions.md)
- [ElementOptionsByType](interfaces/elementoptionsbytype.md)
- [ExtendedPlugin](interfaces/extendedplugin.md)
- [FillerControllerDatasetOptions](interfaces/fillercontrollerdatasetoptions.md)
- [FillerOptions](interfaces/filleroptions.md)
- [FontSpec](interfaces/fontspec.md)
- [GridLineOptions](interfaces/gridlineoptions.md)
- [InteractionItem](interfaces/interactionitem.md)
- [InteractionModeMap](interfaces/interactionmodemap.md)
- [InteractionOptions](interfaces/interactionoptions.md)
- [LayoutItem](interfaces/layoutitem.md)
- [LegendElement](interfaces/legendelement.md)
- [LegendItem](interfaces/legenditem.md)
- [LegendOptions](interfaces/legendoptions.md)
- [LineControllerChartOptions](interfaces/linecontrollerchartoptions.md)
- [LineControllerDatasetOptions](interfaces/linecontrollerdatasetoptions.md)
- [LineElement](interfaces/lineelement.md)
- [LineHoverOptions](interfaces/linehoveroptions.md)
- [LineOptions](interfaces/lineoptions.md)
- [LineProps](interfaces/lineprops.md)
- [ParsingOptions](interfaces/parsingoptions.md)
- [Plugin](interfaces/plugin.md)
- [PluginChartOptions](interfaces/pluginchartoptions.md)
- [PluginOptionsByType](interfaces/pluginoptionsbytype.md)
- [Point](interfaces/point.md)
- [PointElement](interfaces/pointelement.md)
- [PointHoverOptions](interfaces/pointhoveroptions.md)
- [PointOptions](interfaces/pointoptions.md)
- [PointPrefixedHoverOptions](interfaces/pointprefixedhoveroptions.md)
- [PointPrefixedOptions](interfaces/pointprefixedoptions.md)
- [PointProps](interfaces/pointprops.md)
- [PolarAreaController](interfaces/polarareacontroller.md)
- [PolarAreaControllerChartOptions](interfaces/polarareacontrollerchartoptions.md)
- [PolarAreaControllerDatasetOptions](interfaces/polarareacontrollerdatasetoptions.md)
- [RadarControllerDatasetOptions](interfaces/radarcontrollerdatasetoptions.md)
- [RadialLinearScale](interfaces/radiallinearscale.md)
- [RadialScaleTypeRegistry](interfaces/radialscaletyperegistry.md)
- [Registry](interfaces/registry.md)
- [ScaleTypeRegistry](interfaces/scaletyperegistry.md)
- [ScatterDataPoint](interfaces/scatterdatapoint.md)
- [ScriptableContext](interfaces/scriptablecontext.md)
- [ScriptableLineSegmentContext](interfaces/scriptablelinesegmentcontext.md)
- [ScriptableScaleContext](interfaces/scriptablescalecontext.md)
- [ScriptableTooltipContext](interfaces/scriptabletooltipcontext.md)
- [Segment](interfaces/segment.md)
- [Tick](interfaces/tick.md)
- [TickOptions](interfaces/tickoptions.md)
- [TimeScale](interfaces/timescale.md)
- [TitleOptions](interfaces/titleoptions.md)
- [TooltipCallbacks](interfaces/tooltipcallbacks.md)
- [TooltipItem](interfaces/tooltipitem.md)
- [TooltipLabelStyle](interfaces/tooltiplabelstyle.md)
- [TooltipModel](interfaces/tooltipmodel.md)
- [TooltipOptions](interfaces/tooltipoptions.md)
- [TypedRegistry](interfaces/typedregistry.md)
- [VisualElement](interfaces/visualelement.md)

## Type aliases

### AnimationOptions

Ƭ **AnimationOptions**<TType\>: *object*

#### Type parameters:

Name | Type |
:------ | :------ |
`TType` | [*ChartType*](README.md#charttype) |

#### Type declaration:

Name | Type |
:------ | :------ |
`animation` | *false* \| [*AnimationSpec*](README.md#animationspec)<TType\> & { `onComplete?`: (`this`: [*Chart*](classes/chart.md), `event`: [*AnimationEvent*](interfaces/animationevent.md)) => *void* ; `onProgress?`: (`this`: [*Chart*](classes/chart.md), `event`: [*AnimationEvent*](interfaces/animationevent.md)) => *void*  } |
`animations` | [*AnimationsSpec*](README.md#animationsspec)<TType\> |
`transitions` | [*TransitionsSpec*](README.md#transitionsspec)<TType\> |

Defined in: [index.esm.d.ts:1532](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1532)

___

### AnimationSpec

Ƭ **AnimationSpec**<TType\>: *object*

#### Type parameters:

Name | Type |
:------ | :------ |
`TType` | [*ChartType*](README.md#charttype) |

#### Type declaration:

Name | Type | Description |
:------ | :------ | :------ |
`delay`? | [*Scriptable*](README.md#scriptable)<number, [*ScriptableContext*](interfaces/scriptablecontext.md)<TType\>\> | Delay before starting the animations.  **`default`** 0  |
`duration`? | [*Scriptable*](README.md#scriptable)<number, [*ScriptableContext*](interfaces/scriptablecontext.md)<TType\>\> | The number of milliseconds an animation takes.  **`default`** 1000  |
`easing`? | [*Scriptable*](README.md#scriptable)<[*EasingFunction*](README.md#easingfunction), [*ScriptableContext*](interfaces/scriptablecontext.md)<TType\>\> | Easing function to use  **`default`** 'easeOutQuart'  |
`loop`? | [*Scriptable*](README.md#scriptable)<boolean, [*ScriptableContext*](interfaces/scriptablecontext.md)<TType\>\> |   If set to true, the animations loop endlessly.  **`default`** false  |

Defined in: [index.esm.d.ts:1476](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1476)

___

### AnimationsSpec

Ƭ **AnimationsSpec**<TType\>: *object*

#### Type parameters:

Name | Type |
:------ | :------ |
`TType` | [*ChartType*](README.md#charttype) |

#### Type declaration:

Defined in: [index.esm.d.ts:1501](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1501)

___

### BarController

Ƭ **BarController**: [*DatasetController*](classes/datasetcontroller.md)

Defined in: [index.esm.d.ts:139](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L139)

___

### BubbleController

Ƭ **BubbleController**: [*DatasetController*](classes/datasetcontroller.md)

Defined in: [index.esm.d.ts:167](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L167)

___

### CategoryScale

Ƭ **CategoryScale**<O\>: [*Scale*](classes/scale.md)<O\>

#### Type parameters:

Name | Type | Default |
:------ | :------ | :------ |
`O` | [*CategoryScaleOptions*](README.md#categoryscaleoptions) | [*CategoryScaleOptions*](README.md#categoryscaleoptions) |

Defined in: [index.esm.d.ts:2868](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2868)

___

### CategoryScaleOptions

Ƭ **CategoryScaleOptions**: [*CartesianScaleOptions*](interfaces/cartesianscaleoptions.md) & { `labels`: *string*[] \| *string*[][] ; `max`: *string* \| *number* ; `min`: *string* \| *number*  }

Defined in: [index.esm.d.ts:2862](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2862)

___

### ChartComponentLike

Ƭ **ChartComponentLike**: [*ChartComponent*](interfaces/chartcomponent.md) \| [*ChartComponent*](interfaces/chartcomponent.md)[] \| { [key: string]: [*ChartComponent*](interfaces/chartcomponent.md);  }

Defined in: [index.esm.d.ts:1034](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1034)

___

### ChartDataset

Ƭ **ChartDataset**<TType, TData\>: *DeepPartial*<{ [key in ChartType]: object & ChartTypeRegistry[key]["datasetOptions"]}[TType]\> & [*ChartDatasetProperties*](interfaces/chartdatasetproperties.md)<TType, TData\>

#### Type parameters:

Name | Type | Default |
:------ | :------ | :------ |
`TType` | [*ChartType*](README.md#charttype) | [*ChartType*](README.md#charttype) |
`TData` | - | TType[] |

Defined in: [index.esm.d.ts:3340](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L3340)

___

### ChartItem

Ƭ **ChartItem**: *string* \| CanvasRenderingContext2D \| OffscreenCanvasRenderingContext2D \| HTMLCanvasElement \| OffscreenCanvas \| { `canvas`: HTMLCanvasElement \| OffscreenCanvas  } \| *ArrayLike*<CanvasRenderingContext2D \| HTMLCanvasElement \| OffscreenCanvas\>

Defined in: [index.esm.d.ts:506](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L506)

___

### ChartOptions

Ƭ **ChartOptions**<TType\>: *DeepPartial*<[*CoreChartOptions*](interfaces/corechartoptions.md)<TType\> & [*ElementChartOptions*](interfaces/elementchartoptions.md) & [*PluginChartOptions*](interfaces/pluginchartoptions.md)<TType\> & [*DatasetChartOptions*](README.md#datasetchartoptions)<TType\> & [*ScaleChartOptions*](README.md#scalechartoptions)<TType\> & [*ChartTypeRegistry*](interfaces/charttyperegistry.md)[TType][*chartOptions*]\>

#### Type parameters:

Name | Type | Default |
:------ | :------ | :------ |
`TType` | [*ChartType*](README.md#charttype) | [*ChartType*](README.md#charttype) |

Defined in: [index.esm.d.ts:3322](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L3322)

___

### ChartType

Ƭ **ChartType**: keyof [*ChartTypeRegistry*](interfaces/charttyperegistry.md)

Defined in: [index.esm.d.ts:3301](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L3301)

___

### Color

Ƭ **Color**: *string* \| CanvasGradient \| CanvasPattern

Defined in: [color.d.ts:1](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/color.d.ts#L1)

___

### DatasetChartOptions

Ƭ **DatasetChartOptions**<TType\>: { [key in TType]: object}

#### Type parameters:

Name | Type | Default |
:------ | :------ | :------ |
`TType` | [*ChartType*](README.md#charttype) | [*ChartType*](README.md#charttype) |

Defined in: [index.esm.d.ts:3310](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L3310)

___

### DecimationOptions

Ƭ **DecimationOptions**: LttbDecimationOptions \| MinMaxDecimationOptions

Defined in: [index.esm.d.ts:1972](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1972)

___

### DefaultDataPoint

Ƭ **DefaultDataPoint**<TType\>: [*ChartTypeRegistry*](interfaces/charttyperegistry.md)[TType][*defaultDataPoint*][]

#### Type parameters:

Name | Type |
:------ | :------ |
`TType` | [*ChartType*](README.md#charttype) |

Defined in: [index.esm.d.ts:3331](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L3331)

___

### DoughnutDataPoint

Ƭ **DoughnutDataPoint**: *number*

Defined in: [index.esm.d.ts:300](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L300)

___

### EasingFunction

Ƭ **EasingFunction**: *linear* \| *easeInQuad* \| *easeOutQuad* \| *easeInOutQuad* \| *easeInCubic* \| *easeOutCubic* \| *easeInOutCubic* \| *easeInQuart* \| *easeOutQuart* \| *easeInOutQuart* \| *easeInQuint* \| *easeOutQuint* \| *easeInOutQuint* \| *easeInSine* \| *easeOutSine* \| *easeInOutSine* \| *easeInExpo* \| *easeOutExpo* \| *easeInOutExpo* \| *easeInCirc* \| *easeOutCirc* \| *easeInOutCirc* \| *easeInElastic* \| *easeOutElastic* \| *easeInOutElastic* \| *easeInBack* \| *easeOutBack* \| *easeInOutBack* \| *easeInBounce* \| *easeOutBounce* \| *easeInOutBounce*

Defined in: [index.esm.d.ts:1443](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1443)

___

### FillTarget

Ƭ **FillTarget**: *number* \| *string* \| { `value`: *number*  } \| *start* \| *end* \| *origin* \| *stack* \| *boolean*

Defined in: [index.esm.d.ts:1980](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1980)

___

### InteractionMode

Ƭ **InteractionMode**: keyof [*InteractionModeMap*](interfaces/interactionmodemap.md)

Defined in: [index.esm.d.ts:701](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L701)

___

### InteractionModeFunction

Ƭ **InteractionModeFunction**: (`chart`: [*Chart*](classes/chart.md), `e`: [*ChartEvent*](interfaces/chartevent.md), `options`: [*InteractionOptions*](interfaces/interactionoptions.md), `useFinalPosition?`: *boolean*) => [*InteractionItem*](interfaces/interactionitem.md)[]

#### Type declaration:

▸ (`chart`: [*Chart*](classes/chart.md), `e`: [*ChartEvent*](interfaces/chartevent.md), `options`: [*InteractionOptions*](interfaces/interactionoptions.md), `useFinalPosition?`: *boolean*): [*InteractionItem*](interfaces/interactionitem.md)[]

#### Parameters:

Name | Type |
:------ | :------ |
`chart` | [*Chart*](classes/chart.md) |
`e` | [*ChartEvent*](interfaces/chartevent.md) |
`options` | [*InteractionOptions*](interfaces/interactionoptions.md) |
`useFinalPosition?` | *boolean* |

**Returns:** [*InteractionItem*](interfaces/interactionitem.md)[]

Defined in: [index.esm.d.ts:663](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L663)

___

### LayoutPosition

Ƭ **LayoutPosition**: *left* \| *top* \| *right* \| *bottom* \| *center* \| *chartArea* \| { [scaleId: string]: *number*;  }

Defined in: [layout.d.ts:3](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/layout.d.ts#L3)

___

### LineController

Ƭ **LineController**: [*DatasetController*](classes/datasetcontroller.md)

Defined in: [index.esm.d.ts:211](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L211)

___

### LinearScale

Ƭ **LinearScale**<O\>: [*Scale*](classes/scale.md)<O\>

#### Type parameters:

Name | Type | Default |
:------ | :------ | :------ |
`O` | [*LinearScaleOptions*](README.md#linearscaleoptions) | [*LinearScaleOptions*](README.md#linearscaleoptions) |

Defined in: [index.esm.d.ts:2923](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2923)

___

### LinearScaleOptions

Ƭ **LinearScaleOptions**: [*CartesianScaleOptions*](interfaces/cartesianscaleoptions.md) & { `beginAtZero`: *boolean* ; `grace?`: *string* \| *number* ; `suggestedMax?`: *number* ; `suggestedMin?`: *number* ; `ticks`: { `count`: *number* ; `format`: Intl.NumberFormatOptions ; `maxTicksLimit`: *number* ; `precision`: *number* ; `stepSize`: *number*  }  }

Defined in: [index.esm.d.ts:2874](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2874)

___

### LogarithmicScale

Ƭ **LogarithmicScale**<O\>: [*Scale*](classes/scale.md)<O\>

#### Type parameters:

Name | Type | Default |
:------ | :------ | :------ |
`O` | [*LogarithmicScaleOptions*](README.md#logarithmicscaleoptions) | [*LogarithmicScaleOptions*](README.md#logarithmicscaleoptions) |

Defined in: [index.esm.d.ts:2948](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2948)

___

### LogarithmicScaleOptions

Ƭ **LogarithmicScaleOptions**: [*CartesianScaleOptions*](interfaces/cartesianscaleoptions.md) & { `suggestedMax?`: *number* ; `suggestedMin?`: *number* ; `ticks`: { `format`: Intl.NumberFormatOptions  }  }

Defined in: [index.esm.d.ts:2929](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2929)

___

### Overrides

Ƭ **Overrides**: { [key in ChartType]: CoreChartOptions<key\> & ElementChartOptions & PluginChartOptions<key\> & DatasetChartOptions<ChartType\> & ScaleChartOptions<key\> & ChartTypeRegistry[key]["chartOptions"]}

Defined in: [index.esm.d.ts:641](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L641)

___

### ParsedDataType

Ƭ **ParsedDataType**<TType\>: [*ChartTypeRegistry*](interfaces/charttyperegistry.md)[TType][*parsedDataType*]

#### Type parameters:

Name | Type | Default |
:------ | :------ | :------ |
`TType` | [*ChartType*](README.md#charttype) | [*ChartType*](README.md#charttype) |

Defined in: [index.esm.d.ts:3333](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L3333)

___

### PieAnimationOptions

Ƭ **PieAnimationOptions**: [*DoughnutAnimationOptions*](interfaces/doughnutanimationoptions.md)

Defined in: [index.esm.d.ts:319](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L319)

___

### PieController

Ƭ **PieController**: [*DoughnutController*](README.md#doughnutcontroller)

Defined in: [index.esm.d.ts:323](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L323)

___

### PieControllerChartOptions

Ƭ **PieControllerChartOptions**: [*DoughnutControllerChartOptions*](interfaces/doughnutcontrollerchartoptions.md)

Defined in: [index.esm.d.ts:318](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L318)

___

### PieControllerDatasetOptions

Ƭ **PieControllerDatasetOptions**: [*DoughnutControllerDatasetOptions*](interfaces/doughnutcontrollerdatasetoptions.md)

Defined in: [index.esm.d.ts:317](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L317)

___

### PieDataPoint

Ƭ **PieDataPoint**: [*DoughnutDataPoint*](README.md#doughnutdatapoint)

Defined in: [index.esm.d.ts:321](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L321)

___

### PointStyle

Ƭ **PointStyle**: *circle* \| *cross* \| *crossRot* \| *dash* \| *line* \| *rect* \| *rectRounded* \| *rectRot* \| *star* \| *triangle* \| HTMLImageElement \| HTMLCanvasElement

Defined in: [index.esm.d.ts:1734](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1734)

___

### PolarAreaAnimationOptions

Ƭ **PolarAreaAnimationOptions**: [*DoughnutAnimationOptions*](interfaces/doughnutanimationoptions.md)

Defined in: [index.esm.d.ts:337](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L337)

___

### RadarController

Ƭ **RadarController**: [*DatasetController*](classes/datasetcontroller.md)

Defined in: [index.esm.d.ts:386](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L386)

___

### RadarControllerChartOptions

Ƭ **RadarControllerChartOptions**: [*LineControllerChartOptions*](interfaces/linecontrollerchartoptions.md)

Defined in: [index.esm.d.ts:384](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L384)

___

### RadialLinearScaleOptions

Ƭ **RadialLinearScaleOptions**: [*CoreScaleOptions*](interfaces/corescaleoptions.md) & { `angleLines`: { `borderDash`: [*Scriptable*](README.md#scriptable)<number[], [*ScriptableScaleContext*](interfaces/scriptablescalecontext.md)\> ; `borderDashOffset`: [*Scriptable*](README.md#scriptable)<number, [*ScriptableScaleContext*](interfaces/scriptablescalecontext.md)\> ; `color`: [*Scriptable*](README.md#scriptable)<[*Color*](README.md#color), [*ScriptableScaleContext*](interfaces/scriptablescalecontext.md)\> ; `display`: *boolean* ; `lineWidth`: [*Scriptable*](README.md#scriptable)<number, [*ScriptableScaleContext*](interfaces/scriptablescalecontext.md)\>  } ; `animate`: *boolean* ; `beginAtZero`: *boolean* ; `grid`: [*GridLineOptions*](interfaces/gridlineoptions.md) ; `max`: *number* ; `min`: *number* ; `pointLabels`: { `backdropColor`: [*Scriptable*](README.md#scriptable)<[*Color*](README.md#color), [*ScriptableScaleContext*](interfaces/scriptablescalecontext.md)\> ; `backdropPadding`: [*Scriptable*](README.md#scriptable)<number \| [*ChartArea*](interfaces/chartarea.md), [*ScriptableScaleContext*](interfaces/scriptablescalecontext.md)\> ; `callback`: (`label`: *string*, `index`: *number*) => *string* ; `color`: [*Scriptable*](README.md#scriptable)<[*Color*](README.md#color), [*ScriptableScaleContext*](interfaces/scriptablescalecontext.md)\> ; `display`: *boolean* ; `font`: [*Scriptable*](README.md#scriptable)<[*FontSpec*](interfaces/fontspec.md), [*ScriptableScaleContext*](interfaces/scriptablescalecontext.md)\>  } ; `suggestedMax`: *number* ; `suggestedMin`: *number* ; `ticks`: [*TickOptions*](interfaces/tickoptions.md) & { `count`: *number* ; `format`: Intl.NumberFormatOptions ; `maxTicksLimit`: *number* ; `precision`: *number* ; `stepSize`: *number*  }  }

Defined in: [index.esm.d.ts:3045](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L3045)

___

### ScaleChartOptions

Ƭ **ScaleChartOptions**<TType\>: *object*

#### Type parameters:

Name | Type | Default |
:------ | :------ | :------ |
`TType` | [*ChartType*](README.md#charttype) | [*ChartType*](README.md#charttype) |

#### Type declaration:

Name | Type |
:------ | :------ |
`scales` | *object* |

Defined in: [index.esm.d.ts:3316](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L3316)

___

### ScaleOptions

Ƭ **ScaleOptions**<TScale\>: *DeepPartial*<[*ScaleOptionsByType*](README.md#scaleoptionsbytype)<TScale\>\>

#### Type parameters:

Name | Type | Default |
:------ | :------ | :------ |
`TScale` | [*ScaleType*](README.md#scaletype) | [*ScaleType*](README.md#scaletype) |

Defined in: [index.esm.d.ts:3308](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L3308)

___

### ScaleOptionsByType

Ƭ **ScaleOptionsByType**<TScale\>: { [key in ScaleType]: object & ScaleTypeRegistry[key]["options"]}[TScale]

#### Type parameters:

Name | Type | Default |
:------ | :------ | :------ |
`TScale` | [*ScaleType*](README.md#scaletype) | [*ScaleType*](README.md#scaletype) |

Defined in: [index.esm.d.ts:3303](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L3303)

___

### ScaleType

Ƭ **ScaleType**: keyof [*ScaleTypeRegistry*](interfaces/scaletyperegistry.md)

Defined in: [index.esm.d.ts:3205](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L3205)

___

### ScatterController

Ƭ **ScatterController**: [*LineController*](README.md#linecontroller)

Defined in: [index.esm.d.ts:226](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L226)

___

### ScatterControllerChartOptions

Ƭ **ScatterControllerChartOptions**: [*LineControllerChartOptions*](interfaces/linecontrollerchartoptions.md)

Defined in: [index.esm.d.ts:224](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L224)

___

### ScatterControllerDatasetOptions

Ƭ **ScatterControllerDatasetOptions**: [*LineControllerDatasetOptions*](interfaces/linecontrollerdatasetoptions.md)

Defined in: [index.esm.d.ts:217](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L217)

___

### Scriptable

Ƭ **Scriptable**<T, TContext\>: T \| (`ctx`: TContext, `options`: AnyObject) => T

#### Type parameters:

Name |
:------ |
`T` |
`TContext` |

Defined in: [index.esm.d.ts:34](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L34)

___

### ScriptableAndArray

Ƭ **ScriptableAndArray**<T, TContext\>: readonly T[] \| [*Scriptable*](README.md#scriptable)<T, TContext\>

#### Type parameters:

Name |
:------ |
`T` |
`TContext` |

Defined in: [index.esm.d.ts:36](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L36)

___

### ScriptableAndArrayOptions

Ƭ **ScriptableAndArrayOptions**<T, TContext\>: { [P in keyof T]: ScriptableAndArray<T[P], TContext\>}

#### Type parameters:

Name |
:------ |
`T` |
`TContext` |

Defined in: [index.esm.d.ts:37](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L37)

___

### ScriptableOptions

Ƭ **ScriptableOptions**<T, TContext\>: { [P in keyof T]: Scriptable<T[P], TContext\>}

#### Type parameters:

Name |
:------ |
`T` |
`TContext` |

Defined in: [index.esm.d.ts:35](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L35)

___

### TextAlign

Ƭ **TextAlign**: *left* \| *center* \| *right*

Defined in: [index.esm.d.ts:1574](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1574)

___

### TimeScaleOptions

Ƭ **TimeScaleOptions**: [*CartesianScaleOptions*](interfaces/cartesianscaleoptions.md) & { `adapters`: { `date`: *unknown*  } ; `bounds`: *ticks* \| *data* ; `ticks`: { `source`: *labels* \| *auto* \| *data*  } ; `time`: { `displayFormats`: { [key: string]: *string*;  } ; `isoWeekday`: *false* \| *number* ; `minUnit`: [*TimeUnit*](README.md#timeunit) ; `parser`: *string* \| (`v`: *unknown*) => *number* ; `round`: *false* \| [*TimeUnit*](README.md#timeunit) ; `stepSize`: *number* ; `tooltipFormat`: *string* ; `unit`: *false* \| [*TimeUnit*](README.md#timeunit)  }  }

Defined in: [index.esm.d.ts:2954](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2954)

___

### TimeSeriesScale

Ƭ **TimeSeriesScale**<O\>: [*TimeScale*](README.md#timescale)<O\>

#### Type parameters:

Name | Type | Default |
:------ | :------ | :------ |
`O` | [*TimeScaleOptions*](README.md#timescaleoptions) | [*TimeScaleOptions*](README.md#timescaleoptions) |

Defined in: [index.esm.d.ts:3039](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L3039)

___

### TimeUnit

Ƭ **TimeUnit**: *millisecond* \| *second* \| *minute* \| *hour* \| *day* \| *week* \| *month* \| *quarter* \| *year*

Defined in: [adapters.d.ts:1](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/adapters.d.ts#L1)

___

### TooltipXAlignment

Ƭ **TooltipXAlignment**: *left* \| *center* \| *right*

Defined in: [index.esm.d.ts:2253](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2253)

___

### TooltipYAlignment

Ƭ **TooltipYAlignment**: *top* \| *center* \| *bottom*

Defined in: [index.esm.d.ts:2254](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2254)

___

### TransitionSpec

Ƭ **TransitionSpec**<TType\>: *object*

#### Type parameters:

Name | Type |
:------ | :------ |
`TType` | [*ChartType*](README.md#charttype) |

#### Type declaration:

Name | Type |
:------ | :------ |
`animation` | [*AnimationSpec*](README.md#animationspec)<TType\> |
`animations` | [*AnimationsSpec*](README.md#animationsspec)<TType\> |

Defined in: [index.esm.d.ts:1523](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1523)

___

### TransitionsSpec

Ƭ **TransitionsSpec**<TType\>: *object*

#### Type parameters:

Name | Type |
:------ | :------ |
`TType` | [*ChartType*](README.md#charttype) |

#### Type declaration:

Defined in: [index.esm.d.ts:1528](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1528)

___

### UpdateMode

Ƭ **UpdateMode**: keyof *typeof* [*UpdateModeEnum*](enums/updatemodeenum.md)

Defined in: [index.esm.d.ts:525](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L525)

## Variables

### ArcElement

• **ArcElement**: [*ChartComponent*](interfaces/chartcomponent.md) & { `prototype`: [*ArcElement*](README.md#arcelement)<[*ArcProps*](interfaces/arcprops.md), [*ArcOptions*](interfaces/arcoptions.md)\>  }

Defined in: [index.esm.d.ts:1644](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1644)

___

### BarController

• **BarController**: [*ChartComponent*](interfaces/chartcomponent.md) & { `prototype`: [*BarController*](README.md#barcontroller)  }

Defined in: [index.esm.d.ts:140](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L140)

___

### BarElement

• **BarElement**: [*ChartComponent*](interfaces/chartcomponent.md) & { `prototype`: [*BarElement*](README.md#barelement)<[*BarProps*](interfaces/barprops.md), [*BarOptions*](interfaces/baroptions.md)\>  }

Defined in: [index.esm.d.ts:1885](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1885)

___

### BubbleController

• **BubbleController**: [*ChartComponent*](interfaces/chartcomponent.md) & { `prototype`: [*BubbleController*](README.md#bubblecontroller)  }

Defined in: [index.esm.d.ts:168](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L168)

___

### CategoryScale

• **CategoryScale**: [*ChartComponent*](interfaces/chartcomponent.md) & { `prototype`: [*CategoryScale*](README.md#categoryscale)<[*CategoryScaleOptions*](README.md#categoryscaleoptions)\>  }

Defined in: [index.esm.d.ts:2869](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2869)

___

### DoughnutController

• **DoughnutController**: [*ChartComponent*](interfaces/chartcomponent.md) & { `prototype`: [*DoughnutController*](README.md#doughnutcontroller)  }

Defined in: [index.esm.d.ts:312](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L312)

___

### Element

• **Element**: *object*

#### Type declaration:

Name | Type |
:------ | :------ |
`prototype` | [*Element*](README.md#element)<{}, {}\> |

Defined in: [element.d.ts:27](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/element.d.ts#L27)

___

### Filler

• `Const` **Filler**: [*Plugin*](interfaces/plugin.md)

Defined in: [index.esm.d.ts:1974](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1974)

___

### Interaction

• `Const` **Interaction**: *object*

#### Type declaration:

Name | Type |
:------ | :------ |
`modes` | [*InteractionModeMap*](interfaces/interactionmodemap.md) |

Defined in: [index.esm.d.ts:703](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L703)

___

### Legend

• `Const` **Legend**: [*Plugin*](interfaces/plugin.md)

Defined in: [index.esm.d.ts:2004](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2004)

___

### LineController

• **LineController**: [*ChartComponent*](interfaces/chartcomponent.md) & { `prototype`: [*LineController*](README.md#linecontroller)  }

Defined in: [index.esm.d.ts:212](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L212)

___

### LineElement

• **LineElement**: [*ChartComponent*](interfaces/chartcomponent.md) & { `prototype`: [*LineElement*](README.md#lineelement)<[*LineProps*](interfaces/lineprops.md), [*LineOptions*](interfaces/lineoptions.md)\>  }

Defined in: [index.esm.d.ts:1724](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1724)

___

### LinearScale

• **LinearScale**: [*ChartComponent*](interfaces/chartcomponent.md) & { `prototype`: [*LinearScale*](README.md#linearscale)<[*LinearScaleOptions*](README.md#linearscaleoptions)\>  }

Defined in: [index.esm.d.ts:2924](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2924)

___

### LogarithmicScale

• **LogarithmicScale**: [*ChartComponent*](interfaces/chartcomponent.md) & { `prototype`: [*LogarithmicScale*](README.md#logarithmicscale)<[*LogarithmicScaleOptions*](README.md#logarithmicscaleoptions)\>  }

Defined in: [index.esm.d.ts:2949](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2949)

___

### PieController

• **PieController**: [*ChartComponent*](interfaces/chartcomponent.md) & { `prototype`: [*DoughnutController*](README.md#doughnutcontroller)  }

Defined in: [index.esm.d.ts:324](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L324)

___

### PointElement

• **PointElement**: [*ChartComponent*](interfaces/chartcomponent.md) & { `prototype`: [*PointElement*](README.md#pointelement)<[*PointProps*](interfaces/pointprops.md), [*PointOptions*](interfaces/pointoptions.md)\>  }

Defined in: [index.esm.d.ts:1836](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1836)

___

### PolarAreaController

• **PolarAreaController**: [*ChartComponent*](interfaces/chartcomponent.md) & { `prototype`: [*PolarAreaController*](README.md#polarareacontroller)  }

Defined in: [index.esm.d.ts:352](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L352)

___

### RadarController

• **RadarController**: [*ChartComponent*](interfaces/chartcomponent.md) & { `prototype`: [*RadarController*](README.md#radarcontroller)  }

Defined in: [index.esm.d.ts:387](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L387)

___

### RadialLinearScale

• **RadialLinearScale**: [*ChartComponent*](interfaces/chartcomponent.md) & { `prototype`: [*RadialLinearScale*](README.md#radiallinearscale)<[*RadialLinearScaleOptions*](README.md#radiallinearscaleoptions)\>  }

Defined in: [index.esm.d.ts:3173](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L3173)

___

### ScatterController

• **ScatterController**: [*ChartComponent*](interfaces/chartcomponent.md) & { `prototype`: [*LineController*](README.md#linecontroller)  }

Defined in: [index.esm.d.ts:227](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L227)

___

### Ticks

• `Const` **Ticks**: *object*

#### Type declaration:

Name | Type |
:------ | :------ |
`formatters` | *object* |
`formatters.logarithmic` | [object Object] |
`formatters.numeric` | [object Object] |
`formatters.values` | [object Object] |

Defined in: [index.esm.d.ts:1268](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1268)

___

### TimeScale

• **TimeScale**: [*ChartComponent*](interfaces/chartcomponent.md) & { `prototype`: [*TimeScale*](README.md#timescale)<[*TimeScaleOptions*](README.md#timescaleoptions)\>  }

Defined in: [index.esm.d.ts:3034](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L3034)

___

### TimeSeriesScale

• **TimeSeriesScale**: [*ChartComponent*](interfaces/chartcomponent.md) & { `prototype`: [*TimeSeriesScale*](README.md#timeseriesscale)<[*TimeScaleOptions*](README.md#timescaleoptions)\>  }

Defined in: [index.esm.d.ts:3040](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L3040)

___

### Title

• `Const` **Title**: [*Plugin*](interfaces/plugin.md)

Defined in: [index.esm.d.ts:2212](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2212)

___

### Tooltip

• `Const` **Tooltip**: [*Plugin*](interfaces/plugin.md) & { `positioners`: { [key: string]: (`items`: readonly [*ActiveElement*](interfaces/activeelement.md)[], `eventPosition`: { `x`: *number* ; `y`: *number*  }) => { `x`: *number* ; `y`: *number*  } \| *false*;  } ; `getActiveElements`: () => [*ActiveElement*](interfaces/activeelement.md)[] ; `setActiveElements`: (`active`: [*ActiveDataPoint*](interfaces/activedatapoint.md)[], `eventPosition`: { `x`: *number* ; `y`: *number*  }) => *void*  }

Defined in: [index.esm.d.ts:2332](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2332)

___

### \_adapters

• `Const` **\_adapters**: *object*

#### Type declaration:

Name | Type |
:------ | :------ |
`_date` | [*DateAdapter*](interfaces/dateadapter.md) |

Defined in: [adapters.d.ts:61](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/adapters.d.ts#L61)

___

### defaults

• `Const` **defaults**: [*Defaults*](interfaces/defaults.md)

Defined in: [index.esm.d.ts:651](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L651)

___

### layouts

• `Const` **layouts**: *object*

#### Type declaration:

Name | Type |
:------ | :------ |
`addBox` | (`chart`: [*Chart*](classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](interfaces/scatterdatapoint.md) \| [*BubbleDataPoint*](interfaces/bubbledatapoint.md))[], unknown\>, `item`: [*LayoutItem*](interfaces/layoutitem.md)) => *void* |
`configure` | (`chart`: [*Chart*](classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](interfaces/scatterdatapoint.md) \| [*BubbleDataPoint*](interfaces/bubbledatapoint.md))[], unknown\>, `item`: [*LayoutItem*](interfaces/layoutitem.md), `options`: { `fullSize?`: *number* ; `position?`: [*LayoutPosition*](README.md#layoutposition) ; `weight?`: *number*  }) => *void* |
`removeBox` | (`chart`: [*Chart*](classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](interfaces/scatterdatapoint.md) \| [*BubbleDataPoint*](interfaces/bubbledatapoint.md))[], unknown\>, `layoutItem`: [*LayoutItem*](interfaces/layoutitem.md)) => *void* |
`update` | (`chart`: [*Chart*](classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](interfaces/scatterdatapoint.md) \| [*BubbleDataPoint*](interfaces/bubbledatapoint.md))[], unknown\>, `width`: *number*, `height`: *number*) => *void* |

Defined in: [index.esm.d.ts:707](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L707)

___

### registerables

• `Const` **registerables**: readonly [*ChartComponentLike*](README.md#chartcomponentlike)[]

Defined in: [index.esm.d.ts:504](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L504)

___

### registry

• `Const` **registry**: [*Registry*](interfaces/registry.md)

Defined in: [index.esm.d.ts:1060](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1060)
