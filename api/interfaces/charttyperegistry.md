---
title: "Interface: ChartTypeRegistry"
---

# Interface: ChartTypeRegistry

## Properties

### bar

• **bar**: *object*

#### Type declaration:

Name | Type |
:------ | :------ |
`chartOptions` | [*BarControllerChartOptions*](barcontrollerchartoptions.md) |
`datasetOptions` | [*BarControllerDatasetOptions*](barcontrollerdatasetoptions.md) |
`defaultDataPoint` | *number* |
`parsedDataType` | BarParsedData |
`scales` | *linear* \| *logarithmic* \| *category* \| *time* \| *timeseries* |

Defined in: [index.esm.d.ts:3243](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L3243)

___

### bubble

• **bubble**: *object*

#### Type declaration:

Name | Type |
:------ | :------ |
`chartOptions` | *unknown* |
`datasetOptions` | [*BubbleControllerDatasetOptions*](bubblecontrollerdatasetoptions.md) |
`defaultDataPoint` | [*BubbleDataPoint*](bubbledatapoint.md) |
`parsedDataType` | BubbleParsedData |
`scales` | *linear* \| *logarithmic* \| *category* \| *time* \| *timeseries* |

Defined in: [index.esm.d.ts:3264](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L3264)

___

### doughnut

• **doughnut**: *object*

#### Type declaration:

Name | Type |
:------ | :------ |
`chartOptions` | [*DoughnutControllerChartOptions*](doughnutcontrollerchartoptions.md) |
`datasetOptions` | [*DoughnutControllerDatasetOptions*](doughnutcontrollerdatasetoptions.md) |
`defaultDataPoint` | *number* |
`parsedDataType` | *number* |
`scales` | *linear* \| *logarithmic* \| *category* \| *time* \| *timeseries* |

Defined in: [index.esm.d.ts:3278](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L3278)

___

### line

• **line**: *object*

#### Type declaration:

Name | Type |
:------ | :------ |
`chartOptions` | [*LineControllerChartOptions*](linecontrollerchartoptions.md) |
`datasetOptions` | [*LineControllerDatasetOptions*](linecontrollerdatasetoptions.md) & [*FillerControllerDatasetOptions*](fillercontrollerdatasetoptions.md) |
`defaultDataPoint` | *number* \| [*ScatterDataPoint*](scatterdatapoint.md) |
`parsedDataType` | CartesianParsedData |
`scales` | *linear* \| *logarithmic* \| *category* \| *time* \| *timeseries* |

Defined in: [index.esm.d.ts:3250](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L3250)

___

### pie

• **pie**: *object*

#### Type declaration:

Name | Type |
:------ | :------ |
`chartOptions` | [*DoughnutControllerChartOptions*](doughnutcontrollerchartoptions.md) |
`datasetOptions` | [*DoughnutControllerDatasetOptions*](doughnutcontrollerdatasetoptions.md) |
`defaultDataPoint` | *number* |
`parsedDataType` | *number* |
`scales` | *linear* \| *logarithmic* \| *category* \| *time* \| *timeseries* |

Defined in: [index.esm.d.ts:3271](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L3271)

___

### polarArea

• **polarArea**: *object*

#### Type declaration:

Name | Type |
:------ | :------ |
`chartOptions` | [*PolarAreaControllerChartOptions*](polarareacontrollerchartoptions.md) |
`datasetOptions` | [*PolarAreaControllerDatasetOptions*](polarareacontrollerdatasetoptions.md) |
`defaultDataPoint` | *number* |
`parsedDataType` | RadialParsedData |
`scales` | *radialLinear* |

Defined in: [index.esm.d.ts:3285](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L3285)

___

### radar

• **radar**: *object*

#### Type declaration:

Name | Type |
:------ | :------ |
`chartOptions` | [*LineControllerChartOptions*](linecontrollerchartoptions.md) |
`datasetOptions` | [*RadarControllerDatasetOptions*](radarcontrollerdatasetoptions.md) |
`defaultDataPoint` | *number* |
`parsedDataType` | RadialParsedData |
`scales` | *radialLinear* |

Defined in: [index.esm.d.ts:3292](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L3292)

___

### scatter

• **scatter**: *object*

#### Type declaration:

Name | Type |
:------ | :------ |
`chartOptions` | [*LineControllerChartOptions*](linecontrollerchartoptions.md) |
`datasetOptions` | [*LineControllerDatasetOptions*](linecontrollerdatasetoptions.md) |
`defaultDataPoint` | *number* \| [*ScatterDataPoint*](scatterdatapoint.md) |
`parsedDataType` | CartesianParsedData |
`scales` | *linear* \| *logarithmic* \| *category* \| *time* \| *timeseries* |

Defined in: [index.esm.d.ts:3257](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L3257)
