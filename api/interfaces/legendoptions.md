---
title: "Interface: LegendOptions"
---

# Interface: LegendOptions

## Properties

### align

• **align**: *start* \| *end* \| *center*

Alignment of the legend.

**`default`** 'center'

Defined in: [index.esm.d.ts:2106](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2106)

___

### display

• **display**: *boolean*

Is the legend shown?

**`default`** true

Defined in: [index.esm.d.ts:2096](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2096)

___

### fullSize

• **fullSize**: *boolean*

Marks that this box should take the full width/height of the canvas (moving other boxes). This is unlikely to need to be changed in day-to-day use.

**`default`** true

Defined in: [index.esm.d.ts:2111](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2111)

___

### labels

• **labels**: *object*

#### Type declaration:

Name | Type | Description |
:------ | :------ | :------ |
`boxHeight` | *number* | Height of the coloured box.  **`default`** fontSize  |
`boxWidth` | *number* | Width of colored box.  **`default`** 40  |
`color` | [*Color*](../README.md#color) | Color of label  **`see`** Defaults.color  |
`font` | [*FontSpec*](fontspec.md) | Font of label  **`see`** Defaults.font  |
`padding` | *number* | Padding between rows of colored boxes.  **`default`** 10  |
`pointStyle` | [*PointStyle*](../README.md#pointstyle) | Override point style for the legend. Only applies if usePointStyle is true   |
`textAlign`? | [*TextAlign*](../README.md#textalign) | Text alignment   |
`usePointStyle` | *boolean* | Label style will match corresponding point style (size is based on the minimum value between boxWidth and font.size).  **`default`** false  |
`filter` | (`item`: [*LegendItem*](legenditem.md), `data`: [*ChartData*](chartdata.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\>) => *boolean* | - |
`generateLabels` | (`chart`: [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\>) => [*LegendItem*](legenditem.md)[] | - |
`sort` | (`a`: [*LegendItem*](legenditem.md), `b`: [*LegendItem*](legenditem.md), `data`: [*ChartData*](chartdata.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\>) => *number* | - |

Defined in: [index.esm.d.ts:2130](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2130)

___

### position

• **position**: [*LayoutPosition*](../README.md#layoutposition)

Position of the legend.

**`default`** 'top'

Defined in: [index.esm.d.ts:2101](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2101)

___

### reverse

• **reverse**: *boolean*

Legend will show datasets in reverse order.

**`default`** false

Defined in: [index.esm.d.ts:2116](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2116)

___

### title

• **title**: *object*

#### Type declaration:

Name | Type | Description |
:------ | :------ | :------ |
`color` | [*Color*](../README.md#color) | Color of title  **`see`** Defaults.color  |
`display` | *boolean* | Is the legend title displayed.  **`default`** false  |
`font` | [*FontSpec*](fontspec.md) | see Fonts   |
`padding`? | *number* \| [*ChartArea*](chartarea.md) | - |
`position` | *start* \| *end* \| *center* | - |
`text` | *string* | The string title.   |

Defined in: [index.esm.d.ts:2188](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2188)

## Methods

### onClick

▸ **onClick**(`e`: [*ChartEvent*](chartevent.md), `legendItem`: [*LegendItem*](legenditem.md), `legend`: [*LegendElement*](legendelement.md)): *void*

A callback that is called when a click event is registered on a label item.

#### Parameters:

Name | Type |
:------ | :------ |
`e` | [*ChartEvent*](chartevent.md) |
`legendItem` | [*LegendItem*](legenditem.md) |
`legend` | [*LegendElement*](legendelement.md) |

**Returns:** *void*

Defined in: [index.esm.d.ts:2120](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2120)

___

### onHover

▸ **onHover**(`e`: [*ChartEvent*](chartevent.md), `legendItem`: [*LegendItem*](legenditem.md), `legend`: [*LegendElement*](legendelement.md)): *void*

A callback that is called when a 'mousemove' event is registered on top of a label item

#### Parameters:

Name | Type |
:------ | :------ |
`e` | [*ChartEvent*](chartevent.md) |
`legendItem` | [*LegendItem*](legenditem.md) |
`legend` | [*LegendElement*](legendelement.md) |

**Returns:** *void*

Defined in: [index.esm.d.ts:2124](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2124)

___

### onLeave

▸ **onLeave**(`e`: [*ChartEvent*](chartevent.md), `legendItem`: [*LegendItem*](legenditem.md), `legend`: [*LegendElement*](legendelement.md)): *void*

A callback that is called when a 'mousemove' event is registered outside of a previously hovered label item.

#### Parameters:

Name | Type |
:------ | :------ |
`e` | [*ChartEvent*](chartevent.md) |
`legendItem` | [*LegendItem*](legenditem.md) |
`legend` | [*LegendElement*](legendelement.md) |

**Returns:** *void*

Defined in: [index.esm.d.ts:2128](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2128)
