---
title: "Interface: ExtendedPlugin<TType, O, Model>"
---

# Interface: ExtendedPlugin<TType, O, Model\>

## Type parameters

Name | Type | Default |
:------ | :------ | :------ |
`TType` | [*ChartType*](../README.md#charttype) | - |
`O` | - | AnyObject |
`Model` | - | [*TooltipModel*](tooltipmodel.md)<TType\> |

## Hierarchy

* **ExtendedPlugin**

  ↳ [*Plugin*](plugin.md)

## Methods

### afterTooltipDraw

▸ `Optional`**afterTooltipDraw**(`chart`: [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\>, `args`: { `tooltip`: Model  }, `options`: O): *void*

**`desc`** Called after drawing the `tooltip`. Note that this hook will not
be called if the tooltip drawing has been previously cancelled.

#### Parameters:

Name | Type | Description |
:------ | :------ | :------ |
`chart` | [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\> | The chart instance.   |
`args` | *object* | The call arguments.   |
`args.tooltip` | Model | The tooltip.   |
`options` | O | The plugin options.    |

**Returns:** *void*

Defined in: [index.esm.d.ts:2388](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2388)

___

### beforeTooltipDraw

▸ `Optional`**beforeTooltipDraw**(`chart`: [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\>, `args`: { `tooltip`: Model  }, `options`: O): *boolean* \| *void*

**`desc`** Called before drawing the `tooltip`. If any plugin returns `false`,
the tooltip drawing is cancelled until another `render` is triggered.

#### Parameters:

Name | Type | Description |
:------ | :------ | :------ |
`chart` | [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\> | The chart instance.   |
`args` | *object* | The call arguments.   |
`args.tooltip` | Model | The tooltip.   |
`options` | O | The plugin options.   |

**Returns:** *boolean* \| *void*

`false` to cancel the chart tooltip drawing.

Defined in: [index.esm.d.ts:2379](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2379)
