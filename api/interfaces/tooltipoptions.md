---
title: "Interface: TooltipOptions<TType>"
---

# Interface: TooltipOptions<TType\>

## Type parameters

Name | Type |
:------ | :------ |
`TType` | [*ChartType*](../README.md#charttype) |

## Hierarchy

* [*CoreInteractionOptions*](coreinteractionoptions.md)

  ↳ **TooltipOptions**

## Properties

### animation

• **animation**: [*AnimationSpec*](../README.md#animationspec)<TType\>

Defined in: [index.esm.d.ts:2566](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2566)

___

### animations

• **animations**: [*AnimationsSpec*](../README.md#animationsspec)<TType\>

Defined in: [index.esm.d.ts:2567](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2567)

___

### axis

• **axis**: *x* \| *y* \| *xy*

Can be set to 'x', 'y', or 'xy' to define which directions are used in calculating distances. Defaults to 'x' for 'index' mode and 'xy' in dataset and 'nearest' modes.

Inherited from: [CoreInteractionOptions](coreinteractionoptions.md).[axis](coreinteractionoptions.md#axis)

Defined in: [index.esm.d.ts:1349](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1349)

___

### backgroundColor

• **backgroundColor**: [*Scriptable*](../README.md#scriptable)<[*Color*](../README.md#color), [*ScriptableTooltipContext*](scriptabletooltipcontext.md)<TType\>\>

Background color of the tooltip.

**`default`** 'rgba(0, 0, 0, 0.8)'

Defined in: [index.esm.d.ts:2429](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2429)

___

### bodyAlign

• **bodyAlign**: [*Scriptable*](../README.md#scriptable)<[*TextAlign*](../README.md#textalign), [*ScriptableTooltipContext*](scriptabletooltipcontext.md)<TType\>\>

Horizontal alignment of the body text lines.

**`default`** 'left'

Defined in: [index.esm.d.ts:2474](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2474)

___

### bodyColor

• **bodyColor**: [*Scriptable*](../README.md#scriptable)<[*Color*](../README.md#color), [*ScriptableTooltipContext*](scriptabletooltipcontext.md)<TType\>\>

Color of body

**`default`** '#fff'

Defined in: [index.esm.d.ts:2464](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2464)

___

### bodyFont

• **bodyFont**: [*Scriptable*](../README.md#scriptable)<[*FontSpec*](fontspec.md), [*ScriptableTooltipContext*](scriptabletooltipcontext.md)<TType\>\>

  See Fonts.

**`default`** {}

Defined in: [index.esm.d.ts:2469](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2469)

___

### bodySpacing

• **bodySpacing**: [*Scriptable*](../README.md#scriptable)<number, [*ScriptableTooltipContext*](scriptabletooltipcontext.md)<TType\>\>

Spacing to add to top and bottom of each tooltip item.

**`default`** 2

Defined in: [index.esm.d.ts:2459](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2459)

___

### borderColor

• **borderColor**: [*Scriptable*](../README.md#scriptable)<[*Color*](../README.md#color), [*ScriptableTooltipContext*](scriptabletooltipcontext.md)<TType\>\>

Color of the border.

**`default`** 'rgba(0, 0, 0, 0)'

Defined in: [index.esm.d.ts:2549](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2549)

___

### borderWidth

• **borderWidth**: [*Scriptable*](../README.md#scriptable)<number, [*ScriptableTooltipContext*](scriptabletooltipcontext.md)<TType\>\>

Size of the border.

**`default`** 0

Defined in: [index.esm.d.ts:2554](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2554)

___

### boxHeight

• **boxHeight**: [*Scriptable*](../README.md#scriptable)<number, [*ScriptableTooltipContext*](scriptabletooltipcontext.md)<TType\>\>

Height of the color box if displayColors is true.

**`default`** bodyFont.size

Defined in: [index.esm.d.ts:2539](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2539)

___

### boxWidth

• **boxWidth**: [*Scriptable*](../README.md#scriptable)<number, [*ScriptableTooltipContext*](scriptabletooltipcontext.md)<TType\>\>

Width of the color box if displayColors is true.

**`default`** bodyFont.size

Defined in: [index.esm.d.ts:2534](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2534)

___

### callbacks

• **callbacks**: [*TooltipCallbacks*](tooltipcallbacks.md)<TType, [*TooltipModel*](tooltipmodel.md)<TType\>, [*TooltipItem*](tooltipitem.md)<TType\>\>

Defined in: [index.esm.d.ts:2568](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2568)

___

### caretPadding

• **caretPadding**: [*Scriptable*](../README.md#scriptable)<number, [*ScriptableTooltipContext*](scriptabletooltipcontext.md)<TType\>\>

  Extra distance to move the end of the tooltip arrow away from the tooltip point.

**`default`** 2

Defined in: [index.esm.d.ts:2509](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2509)

___

### caretSize

• **caretSize**: [*Scriptable*](../README.md#scriptable)<number, [*ScriptableTooltipContext*](scriptabletooltipcontext.md)<TType\>\>

Size, in px, of the tooltip arrow.

**`default`** 5

Defined in: [index.esm.d.ts:2514](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2514)

___

### cornerRadius

• **cornerRadius**: [*Scriptable*](../README.md#scriptable)<number, [*ScriptableTooltipContext*](scriptabletooltipcontext.md)<TType\>\>

Radius of tooltip corner curves.

**`default`** 6

Defined in: [index.esm.d.ts:2519](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2519)

___

### displayColors

• **displayColors**: [*Scriptable*](../README.md#scriptable)<boolean, [*ScriptableTooltipContext*](scriptabletooltipcontext.md)<TType\>\>

If true, color boxes are shown in the tooltip.

**`default`** true

Defined in: [index.esm.d.ts:2529](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2529)

___

### enabled

• **enabled**: [*Scriptable*](../README.md#scriptable)<boolean, [*ScriptableTooltipContext*](scriptabletooltipcontext.md)<TType\>\>

Are on-canvas tooltips enabled?

**`default`** true

Defined in: [index.esm.d.ts:2402](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2402)

___

### filter

• **filter**: (`e`: [*TooltipItem*](tooltipitem.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*\>, `index`: *number*, `array`: [*TooltipItem*](tooltipitem.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*\>[], `data`: [*ChartData*](chartdata.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\>) => *boolean*

#### Type declaration:

▸ (`e`: [*TooltipItem*](tooltipitem.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*\>, `index`: *number*, `array`: [*TooltipItem*](tooltipitem.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*\>[], `data`: [*ChartData*](chartdata.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\>): *boolean*

#### Parameters:

Name | Type |
:------ | :------ |
`e` | [*TooltipItem*](tooltipitem.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*\> |
`index` | *number* |
`array` | [*TooltipItem*](tooltipitem.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*\>[] |
`data` | [*ChartData*](chartdata.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\> |

**Returns:** *boolean*

Defined in: [index.esm.d.ts:2423](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2423)

Defined in: [index.esm.d.ts:2423](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2423)

___

### footerAlign

• **footerAlign**: [*Scriptable*](../README.md#scriptable)<[*TextAlign*](../README.md#textalign), [*ScriptableTooltipContext*](scriptabletooltipcontext.md)<TType\>\>

Horizontal alignment of the footer text lines.

**`default`** 'left'

Defined in: [index.esm.d.ts:2499](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2499)

___

### footerColor

• **footerColor**: [*Scriptable*](../README.md#scriptable)<[*Color*](../README.md#color), [*ScriptableTooltipContext*](scriptabletooltipcontext.md)<TType\>\>

Color of footer

**`default`** '#fff'

Defined in: [index.esm.d.ts:2489](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2489)

___

### footerFont

• **footerFont**: [*Scriptable*](../README.md#scriptable)<[*FontSpec*](fontspec.md), [*ScriptableTooltipContext*](scriptabletooltipcontext.md)<TType\>\>

See Fonts

**`default`** {weight: 'bold'}

Defined in: [index.esm.d.ts:2494](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2494)

___

### footerMarginTop

• **footerMarginTop**: [*Scriptable*](../README.md#scriptable)<number, [*ScriptableTooltipContext*](scriptabletooltipcontext.md)<TType\>\>

Margin to add before drawing the footer.

**`default`** 6

Defined in: [index.esm.d.ts:2484](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2484)

___

### footerSpacing

• **footerSpacing**: [*Scriptable*](../README.md#scriptable)<number, [*ScriptableTooltipContext*](scriptabletooltipcontext.md)<TType\>\>

Spacing to add to top and bottom of each footer line.

**`default`** 2

Defined in: [index.esm.d.ts:2479](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2479)

___

### intersect

• **intersect**: *boolean*

if true, the hover mode only applies when the mouse position intersects an item on the chart.

**`default`** true

Inherited from: [CoreInteractionOptions](coreinteractionoptions.md).[intersect](coreinteractionoptions.md#intersect)

Defined in: [index.esm.d.ts:1344](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1344)

___

### itemSort

• **itemSort**: (`a`: [*TooltipItem*](tooltipitem.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*\>, `b`: [*TooltipItem*](tooltipitem.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*\>, `data`: [*ChartData*](chartdata.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\>) => *number*

Sort tooltip items.

#### Type declaration:

▸ (`a`: [*TooltipItem*](tooltipitem.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*\>, `b`: [*TooltipItem*](tooltipitem.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*\>, `data`: [*ChartData*](chartdata.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\>): *number*

#### Parameters:

Name | Type |
:------ | :------ |
`a` | [*TooltipItem*](tooltipitem.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*\> |
`b` | [*TooltipItem*](tooltipitem.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*\> |
`data` | [*ChartData*](chartdata.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\> |

**Returns:** *number*

Defined in: [index.esm.d.ts:2421](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2421)

Defined in: [index.esm.d.ts:2421](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2421)

___

### mode

• **mode**: *x* \| *y* \| *dataset* \| *index* \| *point* \| *nearest*

Sets which elements appear in the tooltip. See Interaction Modes for details.

**`default`** 'nearest'

Inherited from: [CoreInteractionOptions](coreinteractionoptions.md).[mode](coreinteractionoptions.md#mode)

Defined in: [index.esm.d.ts:1339](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1339)

___

### multiKeyBackground

• **multiKeyBackground**: [*Scriptable*](../README.md#scriptable)<[*Color*](../README.md#color), [*ScriptableTooltipContext*](scriptabletooltipcontext.md)<TType\>\>

Color to draw behind the colored boxes when multiple items are in the tooltip.

**`default`** '#fff'

Defined in: [index.esm.d.ts:2524](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2524)

___

### padding

• **padding**: [*Scriptable*](../README.md#scriptable)<number \| [*ChartArea*](chartarea.md), [*ScriptableTooltipContext*](scriptabletooltipcontext.md)<TType\>\>

Padding to add to the tooltip

**`default`** 6

Defined in: [index.esm.d.ts:2504](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2504)

___

### position

• **position**: [*Scriptable*](../README.md#scriptable)<*nearest* \| *average*, [*ScriptableTooltipContext*](scriptabletooltipcontext.md)<TType\>\>

The mode for positioning the tooltip

Defined in: [index.esm.d.ts:2410](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2410)

___

### rtl

• **rtl**: [*Scriptable*](../README.md#scriptable)<boolean, [*ScriptableTooltipContext*](scriptabletooltipcontext.md)<TType\>\>

true for rendering the legends from right to left.

Defined in: [index.esm.d.ts:2558](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2558)

___

### textDirection

• **textDirection**: [*Scriptable*](../README.md#scriptable)<string, [*ScriptableTooltipContext*](scriptabletooltipcontext.md)<TType\>\>

This will force the text direction 'rtl' or 'ltr on the canvas for rendering the tooltips, regardless of the css specified on the canvas

**`default`** canvas's default

Defined in: [index.esm.d.ts:2564](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2564)

___

### titleAlign

• **titleAlign**: [*Scriptable*](../README.md#scriptable)<[*TextAlign*](../README.md#textalign), [*ScriptableTooltipContext*](scriptabletooltipcontext.md)<TType\>\>

Horizontal alignment of the title text lines.

**`default`** 'left'

Defined in: [index.esm.d.ts:2454](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2454)

___

### titleColor

• **titleColor**: [*Scriptable*](../README.md#scriptable)<[*Color*](../README.md#color), [*ScriptableTooltipContext*](scriptabletooltipcontext.md)<TType\>\>

Color of title

**`default`** '#fff'

Defined in: [index.esm.d.ts:2434](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2434)

___

### titleFont

• **titleFont**: [*Scriptable*](../README.md#scriptable)<[*FontSpec*](fontspec.md), [*ScriptableTooltipContext*](scriptabletooltipcontext.md)<TType\>\>

See Fonts

**`default`** {weight: 'bold'}

Defined in: [index.esm.d.ts:2439](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2439)

___

### titleMarginBottom

• **titleMarginBottom**: [*Scriptable*](../README.md#scriptable)<number, [*ScriptableTooltipContext*](scriptabletooltipcontext.md)<TType\>\>

Margin to add on bottom of title section.

**`default`** 6

Defined in: [index.esm.d.ts:2449](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2449)

___

### titleSpacing

• **titleSpacing**: [*Scriptable*](../README.md#scriptable)<number, [*ScriptableTooltipContext*](scriptabletooltipcontext.md)<TType\>\>

Spacing to add to top and bottom of each title line.

**`default`** 2

Defined in: [index.esm.d.ts:2444](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2444)

___

### usePointStyle

• **usePointStyle**: [*Scriptable*](../README.md#scriptable)<boolean, [*ScriptableTooltipContext*](scriptabletooltipcontext.md)<TType\>\>

Use the corresponding point style (from dataset options) instead of color boxes, ex: star, triangle etc. (size is based on the minimum value between boxWidth and boxHeight)

**`default`** false

Defined in: [index.esm.d.ts:2544](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2544)

___

### xAlign

• **xAlign**: [*Scriptable*](../README.md#scriptable)<[*TextAlign*](../README.md#textalign), [*ScriptableTooltipContext*](scriptabletooltipcontext.md)<TType\>\>

Override the tooltip alignment calculations

Defined in: [index.esm.d.ts:2415](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2415)

___

### yAlign

• **yAlign**: [*Scriptable*](../README.md#scriptable)<[*TooltipYAlignment*](../README.md#tooltipyalignment), [*ScriptableTooltipContext*](scriptabletooltipcontext.md)<TType\>\>

Defined in: [index.esm.d.ts:2416](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2416)

## Methods

### external

▸ **external**(`args`: { `chart`: [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\> ; `tooltip`: [*TooltipModel*](tooltipmodel.md)<TType\>  }): *void*

  See external tooltip section.

#### Parameters:

Name | Type |
:------ | :------ |
`args` | *object* |
`args.chart` | [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\> |
`args.tooltip` | [*TooltipModel*](tooltipmodel.md)<TType\> |

**Returns:** *void*

Defined in: [index.esm.d.ts:2406](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2406)
