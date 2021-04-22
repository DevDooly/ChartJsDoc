---
title: "Interface: ChartConfiguration<TType, TData, TLabel>"
---

# Interface: ChartConfiguration<TType, TData, TLabel\>

## Type parameters

Name | Type | Default |
:------ | :------ | :------ |
`TType` | [*ChartType*](../README.md#charttype) | [*ChartType*](../README.md#charttype) |
`TData` | - | TType[] |
`TLabel` | - | *unknown* |

## Properties

### data

• **data**: [*ChartData*](chartdata.md)<TType, TData, TLabel\>

Defined in: [index.esm.d.ts:3362](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L3362)

___

### options

• `Optional` **options**: *DeepPartial*<[*CoreChartOptions*](corechartoptions.md)<TType\> & [*ElementChartOptions*](elementchartoptions.md) & [*PluginChartOptions*](pluginchartoptions.md)<TType\> & [*DatasetChartOptions*](../README.md#datasetchartoptions)<TType\> & [*ScaleChartOptions*](../README.md#scalechartoptions)<TType\> & [*ChartTypeRegistry*](charttyperegistry.md)[TType][*chartOptions*]\>

Defined in: [index.esm.d.ts:3363](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L3363)

___

### plugins

• `Optional` **plugins**: [*Plugin*](plugin.md)<TType, Record<string, unknown\>\>[]

Defined in: [index.esm.d.ts:3364](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L3364)

___

### type

• **type**: TType

Defined in: [index.esm.d.ts:3361](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L3361)
