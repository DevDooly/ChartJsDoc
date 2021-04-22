---
title: "Interface: TooltipItem<TType>"
---

# Interface: TooltipItem<TType\>

## Type parameters

Name | Type |
:------ | :------ |
`TType` | [*ChartType*](../README.md#charttype) |

## Properties

### chart

• **chart**: [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\>

The chart the tooltip is being shown on

Defined in: [index.esm.d.ts:2575](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2575)

___

### dataIndex

• **dataIndex**: *number*

Index of this data item in the dataset

Defined in: [index.esm.d.ts:2610](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2610)

___

### dataset

• **dataset**: [*ChartDataset*](../README.md#chartdataset)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[]\>

The dataset the item comes from

Defined in: [index.esm.d.ts:2600](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2600)

___

### datasetIndex

• **datasetIndex**: *number*

Index of the dataset the item comes from

Defined in: [index.esm.d.ts:2605](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2605)

___

### element

• **element**: [*Element*](../README.md#element)<{}, {}\>

The chart element (point, arc, bar, etc.) for this tooltip item

Defined in: [index.esm.d.ts:2615](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2615)

___

### formattedValue

• **formattedValue**: *string*

Formatted value for the tooltip

Defined in: [index.esm.d.ts:2595](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2595)

___

### label

• **label**: *string*

Label for the tooltip

Defined in: [index.esm.d.ts:2580](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2580)

___

### parsed

• **parsed**: *UnionToIntersection*<[*ParsedDataType*](../README.md#parseddatatype)<TType\>\>

Parsed data values for the given `dataIndex` and `datasetIndex`

Defined in: [index.esm.d.ts:2585](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2585)

___

### raw

• **raw**: *unknown*

Raw data values for the given `dataIndex` and `datasetIndex`

Defined in: [index.esm.d.ts:2590](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2590)
