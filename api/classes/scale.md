---
title: "Class: Scale<O>"
---

# Class: Scale<O\>

## Type parameters

Name | Type | Default |
:------ | :------ | :------ |
`O` | [*CoreScaleOptions*](../interfaces/corescaleoptions.md) | [*CoreScaleOptions*](../interfaces/corescaleoptions.md) |

## Hierarchy

* [*Element*](../README.md#element)<{}, O\>

* [*LayoutItem*](../interfaces/layoutitem.md)

  ↳ **Scale**

  ↳↳ [*TimeScale*](../interfaces/timescale.md)

  ↳↳ [*RadialLinearScale*](../interfaces/radiallinearscale.md)

## Constructors

### constructor

\+ **new Scale**<O\>(`cfg`: { `chart`: [*Chart*](chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](../interfaces/scatterdatapoint.md) \| [*BubbleDataPoint*](../interfaces/bubbledatapoint.md))[], unknown\> ; `ctx`: CanvasRenderingContext2D ; `id`: *string* ; `type`: *string*  }): [*Scale*](scale.md)<O\>

#### Type parameters:

Name | Type | Default |
:------ | :------ | :------ |
`O` | [*CoreScaleOptions*](../interfaces/corescaleoptions.md) | [*CoreScaleOptions*](../interfaces/corescaleoptions.md) |

#### Parameters:

Name | Type |
:------ | :------ |
`cfg` | *object* |
`cfg.chart` | [*Chart*](chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](../interfaces/scatterdatapoint.md) \| [*BubbleDataPoint*](../interfaces/bubbledatapoint.md))[], unknown\> |
`cfg.ctx` | CanvasRenderingContext2D |
`cfg.id` | *string* |
`cfg.type` | *string* |

**Returns:** [*Scale*](scale.md)<O\>

Inherited from: Element<{}, O>.constructor

Defined in: [index.esm.d.ts:1257](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1257)

## Properties

### active

• `Readonly` **active**: *boolean*

Inherited from: Element.active

Defined in: [element.d.ts:6](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/element.d.ts#L6)

___

### axis

• **axis**: *string*

Defined in: [index.esm.d.ts:1160](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1160)

___

### bottom

• **bottom**: *number*

Bottom edge of the item. Set by layout system and cannot be used in update

Inherited from: [LayoutItem](../interfaces/layoutitem.md).[bottom](../interfaces/layoutitem.md#bottom)

Defined in: [layout.d.ts:41](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/layout.d.ts#L41)

___

### chart

• `Readonly` **chart**: [*Chart*](chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](../interfaces/scatterdatapoint.md) \| [*BubbleDataPoint*](../interfaces/bubbledatapoint.md))[], unknown\>

Defined in: [index.esm.d.ts:1150](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1150)

___

### ctx

• `Readonly` **ctx**: CanvasRenderingContext2D

Defined in: [index.esm.d.ts:1149](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1149)

___

### fullSize

• **fullSize**: *boolean*

if true, and the item is horizontal, then push vertical boxes down

Inherited from: [LayoutItem](../interfaces/layoutitem.md).[fullSize](../interfaces/layoutitem.md#fullsize)

Defined in: [layout.d.ts:17](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/layout.d.ts#L17)

___

### height

• **height**: *number*

Height of item. Must be valid after update()

Inherited from: [LayoutItem](../interfaces/layoutitem.md).[height](../interfaces/layoutitem.md#height)

Defined in: [layout.d.ts:25](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/layout.d.ts#L25)

___

### id

• `Readonly` **id**: *string*

Defined in: [index.esm.d.ts:1147](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1147)

___

### labelRotation

• **labelRotation**: *number*

Defined in: [index.esm.d.ts:1161](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1161)

___

### left

• **left**: *number*

Left edge of the item. Set by layout system and cannot be used in update

Inherited from: [LayoutItem](../interfaces/layoutitem.md).[left](../interfaces/layoutitem.md#left)

Defined in: [layout.d.ts:29](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/layout.d.ts#L29)

___

### max

• **max**: *number*

Defined in: [index.esm.d.ts:1163](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1163)

___

### maxHeight

• **maxHeight**: *number*

Defined in: [index.esm.d.ts:1153](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1153)

___

### maxWidth

• **maxWidth**: *number*

Defined in: [index.esm.d.ts:1152](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1152)

___

### min

• **min**: *number*

Defined in: [index.esm.d.ts:1162](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1162)

___

### options

• `Readonly` **options**: O

Inherited from: Element.options

Defined in: [element.d.ts:7](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/element.d.ts#L7)

___

### paddingBottom

• **paddingBottom**: *number*

Defined in: [index.esm.d.ts:1156](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1156)

___

### paddingLeft

• **paddingLeft**: *number*

Defined in: [index.esm.d.ts:1157](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1157)

___

### paddingRight

• **paddingRight**: *number*

Defined in: [index.esm.d.ts:1158](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1158)

___

### paddingTop

• **paddingTop**: *number*

Defined in: [index.esm.d.ts:1155](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1155)

___

### position

• **position**: [*LayoutPosition*](../README.md#layoutposition)

The position of the item in the chart layout. Possible values are

Inherited from: [LayoutItem](../interfaces/layoutitem.md).[position](../interfaces/layoutitem.md#position)

Defined in: [layout.d.ts:9](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/layout.d.ts#L9)

___

### right

• **right**: *number*

Right edge of the item. Set by layout system and cannot be used in update

Inherited from: [LayoutItem](../interfaces/layoutitem.md).[right](../interfaces/layoutitem.md#right)

Defined in: [layout.d.ts:37](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/layout.d.ts#L37)

___

### ticks

• **ticks**: [*Tick*](../interfaces/tick.md)[]

Defined in: [index.esm.d.ts:1164](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1164)

___

### top

• **top**: *number*

Top edge of the item. Set by layout system and cannot be used in update

Inherited from: [LayoutItem](../interfaces/layoutitem.md).[top](../interfaces/layoutitem.md#top)

Defined in: [layout.d.ts:33](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/layout.d.ts#L33)

___

### type

• `Readonly` **type**: *string*

Defined in: [index.esm.d.ts:1148](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1148)

___

### weight

• **weight**: *number*

The weight used to sort the item. Higher weights are further away from the chart area

Inherited from: [LayoutItem](../interfaces/layoutitem.md).[weight](../interfaces/layoutitem.md#weight)

Defined in: [layout.d.ts:13](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/layout.d.ts#L13)

___

### width

• **width**: *number*

Width of item. Must be valid after update()

Inherited from: [LayoutItem](../interfaces/layoutitem.md).[width](../interfaces/layoutitem.md#width)

Defined in: [layout.d.ts:21](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/layout.d.ts#L21)

___

### x

• `Readonly` **x**: *number*

Inherited from: Element.x

Defined in: [element.d.ts:4](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/element.d.ts#L4)

___

### y

• `Readonly` **y**: *number*

Inherited from: Element.y

Defined in: [element.d.ts:5](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/element.d.ts#L5)

## Methods

### afterBuildTicks

▸ **afterBuildTicks**(): *void*

**Returns:** *void*

Defined in: [index.esm.d.ts:1244](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1244)

___

### afterCalculateLabelRotation

▸ **afterCalculateLabelRotation**(): *void*

**Returns:** *void*

Defined in: [index.esm.d.ts:1250](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1250)

___

### afterDataLimits

▸ **afterDataLimits**(): *void*

**Returns:** *void*

Defined in: [index.esm.d.ts:1241](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1241)

___

### afterFit

▸ **afterFit**(): *void*

**Returns:** *void*

Defined in: [index.esm.d.ts:1253](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1253)

___

### afterSetDimensions

▸ **afterSetDimensions**(): *void*

**Returns:** *void*

Defined in: [index.esm.d.ts:1238](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1238)

___

### afterTickToLabelConversion

▸ **afterTickToLabelConversion**(): *void*

**Returns:** *void*

Defined in: [index.esm.d.ts:1247](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1247)

___

### afterUpdate

▸ **afterUpdate**(): *void*

**Returns:** *void*

Defined in: [index.esm.d.ts:1235](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1235)

___

### beforeBuildTicks

▸ **beforeBuildTicks**(): *void*

**Returns:** *void*

Defined in: [index.esm.d.ts:1242](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1242)

___

### beforeCalculateLabelRotation

▸ **beforeCalculateLabelRotation**(): *void*

**Returns:** *void*

Defined in: [index.esm.d.ts:1248](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1248)

___

### beforeDataLimits

▸ **beforeDataLimits**(): *void*

**Returns:** *void*

Defined in: [index.esm.d.ts:1239](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1239)

___

### beforeFit

▸ **beforeFit**(): *void*

**Returns:** *void*

Defined in: [index.esm.d.ts:1251](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1251)

___

### beforeLayout

▸ `Optional`**beforeLayout**(): *void*

Called before the layout process starts

**Returns:** *void*

Inherited from: [LayoutItem](../interfaces/layoutitem.md)

Defined in: [layout.d.ts:46](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/layout.d.ts#L46)

___

### beforeSetDimensions

▸ **beforeSetDimensions**(): *void*

**Returns:** *void*

Defined in: [index.esm.d.ts:1236](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1236)

___

### beforeTickToLabelConversion

▸ **beforeTickToLabelConversion**(): *void*

**Returns:** *void*

Defined in: [index.esm.d.ts:1245](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1245)

___

### beforeUpdate

▸ **beforeUpdate**(): *void*

**Returns:** *void*

Defined in: [index.esm.d.ts:1233](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1233)

___

### buildTicks

▸ **buildTicks**(): [*Tick*](../interfaces/tick.md)[]

**Returns:** [*Tick*](../interfaces/tick.md)[]

Defined in: [index.esm.d.ts:1243](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1243)

___

### calculateLabelRotation

▸ **calculateLabelRotation**(): *void*

**Returns:** *void*

Defined in: [index.esm.d.ts:1249](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1249)

___

### configure

▸ **configure**(): *void*

**Returns:** *void*

Defined in: [index.esm.d.ts:1234](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1234)

___

### determineDataLimits

▸ **determineDataLimits**(): *void*

**Returns:** *void*

Defined in: [index.esm.d.ts:1240](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1240)

___

### draw

▸ **draw**(`chartArea`: [*ChartArea*](../interfaces/chartarea.md)): *void*

Draws the element

#### Parameters:

Name | Type |
:------ | :------ |
`chartArea` | [*ChartArea*](../interfaces/chartarea.md) |

**Returns:** *void*

Inherited from: [LayoutItem](../interfaces/layoutitem.md)

Defined in: [layout.d.ts:50](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/layout.d.ts#L50)

___

### drawGrid

▸ **drawGrid**(`chartArea`: [*ChartArea*](../interfaces/chartarea.md)): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`chartArea` | [*ChartArea*](../interfaces/chartarea.md) |

**Returns:** *void*

Defined in: [index.esm.d.ts:1169](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1169)

___

### drawLabels

▸ **drawLabels**(`chartArea`: [*ChartArea*](../interfaces/chartarea.md)): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`chartArea` | [*ChartArea*](../interfaces/chartarea.md) |

**Returns:** *void*

Defined in: [index.esm.d.ts:1168](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1168)

___

### drawTitle

▸ **drawTitle**(`chartArea`: [*ChartArea*](../interfaces/chartarea.md)): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`chartArea` | [*ChartArea*](../interfaces/chartarea.md) |

**Returns:** *void*

Defined in: [index.esm.d.ts:1167](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1167)

___

### fit

▸ **fit**(): *void*

**Returns:** *void*

Defined in: [index.esm.d.ts:1252](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1252)

___

### generateTickLabels

▸ **generateTickLabels**(`ticks`: [*Tick*](../interfaces/tick.md)[]): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`ticks` | [*Tick*](../interfaces/tick.md)[] |

**Returns:** *void*

Defined in: [index.esm.d.ts:1246](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1246)

___

### getBasePixel

▸ **getBasePixel**(): *number*

Returns the pixel for the minimum chart value
The coordinate (0, 0) is at the upper-left corner of the canvas

**Returns:** *number*

Defined in: [index.esm.d.ts:1225](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1225)

___

### getBaseValue

▸ **getBaseValue**(): *number*

**Returns:** *number*

Defined in: [index.esm.d.ts:1219](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1219)

___

### getDecimalForPixel

▸ **getDecimalForPixel**(`pixel`: *number*): *number*

#### Parameters:

Name | Type |
:------ | :------ |
`pixel` | *number* |

**Returns:** *number*

Defined in: [index.esm.d.ts:1175](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1175)

___

### getLabelForValue

▸ **getLabelForValue**(`value`: *number*): *string*

Used to get the label to display in the tooltip for the given value

#### Parameters:

Name | Type |
:------ | :------ |
`value` | *number* |

**Returns:** *string*

Defined in: [index.esm.d.ts:1195](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1195)

___

### getLabels

▸ **getLabels**(): *string*[]

**Returns:** *string*[]

Defined in: [index.esm.d.ts:1232](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1232)

___

### getLineWidthForValue

▸ **getLineWidthForValue**(`value`: *number*): *number*

Returns the grid line width at given value

#### Parameters:

Name | Type |
:------ | :------ |
`value` | *number* |

**Returns:** *number*

Defined in: [index.esm.d.ts:1200](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1200)

___

### getMatchingVisibleMetas

▸ **getMatchingVisibleMetas**(`type?`: *string*): [*ChartMeta*](../interfaces/chartmeta.md)<[*Element*](../README.md#element)<{}, {}\>, [*Element*](../README.md#element)<{}, {}\>\>[]

#### Parameters:

Name | Type |
:------ | :------ |
`type?` | *string* |

**Returns:** [*ChartMeta*](../interfaces/chartmeta.md)<[*Element*](../README.md#element)<{}, {}\>, [*Element*](../README.md#element)<{}, {}\>\>[]

Defined in: [index.esm.d.ts:1165](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1165)

___

### getMinMax

▸ **getMinMax**(`canStack`: *boolean*): *object*

#### Parameters:

Name | Type |
:------ | :------ |
`canStack` | *boolean* |

**Returns:** *object*

Name | Type |
:------ | :------ |
`max` | *number* |
`min` | *number* |

Defined in: [index.esm.d.ts:1230](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1230)

___

### getPadding

▸ `Optional`**getPadding**(): [*ChartArea*](../interfaces/chartarea.md)

Returns an object with padding on the edges

**Returns:** [*ChartArea*](../interfaces/chartarea.md)

Inherited from: [LayoutItem](../interfaces/layoutitem.md)

Defined in: [layout.d.ts:54](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/layout.d.ts#L54)

___

### getPixelForDecimal

▸ **getPixelForDecimal**(`decimal`: *number*): *number*

Utility for getting the pixel location of a percentage of scale
The coordinate (0, 0) is at the upper-left corner of the canvas

#### Parameters:

Name | Type |
:------ | :------ |
`decimal` | *number* |

**Returns:** *number*

Defined in: [index.esm.d.ts:1182](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1182)

___

### getPixelForTick

▸ **getPixelForTick**(`index`: *number*): *number*

Returns the location of the tick at the given index
The coordinate (0, 0) is at the upper-left corner of the canvas

#### Parameters:

Name | Type |
:------ | :------ |
`index` | *number* |

**Returns:** *number*

Defined in: [index.esm.d.ts:1189](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1189)

___

### getPixelForValue

▸ **getPixelForValue**(`value`: *number*, `index`: *number*): *number*

Returns the location of the given data point. Value can either be an index or a numerical value
The coordinate (0, 0) is at the upper-left corner of the canvas

#### Parameters:

Name | Type |
:------ | :------ |
`value` | *number* |
`index` | *number* |

**Returns:** *number*

Defined in: [index.esm.d.ts:1209](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1209)

___

### getProps

▸ **getProps**<P\>(`props`: [P], `final?`: *boolean*): *Pick*<{}, P\>

#### Type parameters:

Name | Type |
:------ | :------ |
`P` | *never* |

#### Parameters:

Name | Type |
:------ | :------ |
`props` | [P] |
`final?` | *boolean* |

**Returns:** *Pick*<{}, P\>

Inherited from: Element.getProps

Defined in: [element.d.ts:11](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/element.d.ts#L11)

▸ **getProps**<P, P2\>(`props`: [P, P2], `final?`: *boolean*): *Pick*<{}, P \| P2\>

#### Type parameters:

Name | Type |
:------ | :------ |
`P` | *never* |
`P2` | *never* |

#### Parameters:

Name | Type |
:------ | :------ |
`props` | [P, P2] |
`final?` | *boolean* |

**Returns:** *Pick*<{}, P \| P2\>

Inherited from: Element.getProps

Defined in: [element.d.ts:12](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/element.d.ts#L12)

▸ **getProps**<P, P2, P3\>(`props`: [P, P2, P3], `final?`: *boolean*): *Pick*<{}, P \| P2 \| P3\>

#### Type parameters:

Name | Type |
:------ | :------ |
`P` | *never* |
`P2` | *never* |
`P3` | *never* |

#### Parameters:

Name | Type |
:------ | :------ |
`props` | [P, P2, P3] |
`final?` | *boolean* |

**Returns:** *Pick*<{}, P \| P2 \| P3\>

Inherited from: Element.getProps

Defined in: [element.d.ts:13](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/element.d.ts#L13)

▸ **getProps**<P, P2, P3, P4\>(`props`: [P, P2, P3, P4], `final?`: *boolean*): *Pick*<{}, P \| P2 \| P3 \| P4\>

#### Type parameters:

Name | Type |
:------ | :------ |
`P` | *never* |
`P2` | *never* |
`P3` | *never* |
`P4` | *never* |

#### Parameters:

Name | Type |
:------ | :------ |
`props` | [P, P2, P3, P4] |
`final?` | *boolean* |

**Returns:** *Pick*<{}, P \| P2 \| P3 \| P4\>

Inherited from: Element.getProps

Defined in: [element.d.ts:17](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/element.d.ts#L17)

▸ **getProps**<P, P2, P3, P4, P5\>(`props`: [P, P2, P3, P4, P5], `final?`: *boolean*): *Pick*<{}, P \| P2 \| P3 \| P4 \| P5\>

#### Type parameters:

Name | Type |
:------ | :------ |
`P` | *never* |
`P2` | *never* |
`P3` | *never* |
`P4` | *never* |
`P5` | *never* |

#### Parameters:

Name | Type |
:------ | :------ |
`props` | [P, P2, P3, P4, P5] |
`final?` | *boolean* |

**Returns:** *Pick*<{}, P \| P2 \| P3 \| P4 \| P5\>

Inherited from: Element.getProps

Defined in: [element.d.ts:21](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/element.d.ts#L21)

▸ **getProps**(`props`: *never*[], `final?`: *boolean*): *object*

#### Parameters:

Name | Type |
:------ | :------ |
`props` | *never*[] |
`final?` | *boolean* |

**Returns:** *object*

Inherited from: Element.getProps

Defined in: [element.d.ts:25](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/element.d.ts#L25)

___

### getTicks

▸ **getTicks**(): [*Tick*](../interfaces/tick.md)[]

**Returns:** [*Tick*](../interfaces/tick.md)[]

Defined in: [index.esm.d.ts:1231](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1231)

___

### getUserBounds

▸ **getUserBounds**(): *object*

**Returns:** *object*

Name | Type |
:------ | :------ |
`max` | *number* |
`maxDefined` | *boolean* |
`min` | *number* |
`minDefined` | *boolean* |

Defined in: [index.esm.d.ts:1229](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1229)

___

### getValueForPixel

▸ **getValueForPixel**(`pixel`: *number*): *number*

Used to get the data value from a given pixel. This is the inverse of getPixelForValue
The coordinate (0, 0) is at the upper-left corner of the canvas

#### Parameters:

Name | Type |
:------ | :------ |
`pixel` | *number* |

**Returns:** *number*

Defined in: [index.esm.d.ts:1217](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1217)

___

### hasValue

▸ **hasValue**(): *boolean*

**Returns:** *boolean*

Inherited from: Element.hasValue

Defined in: [element.d.ts:10](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/element.d.ts#L10)

___

### init

▸ **init**(`options`: O): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`options` | O |

**Returns:** *void*

Defined in: [index.esm.d.ts:1227](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1227)

___

### isFullSize

▸ **isFullSize**(): *boolean*

**Returns:** *boolean*

Defined in: [index.esm.d.ts:1255](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1255)

___

### isHorizontal

▸ **isHorizontal**(): *boolean*

returns true if the layout item is horizontal (ie. top or bottom)

**Returns:** *boolean*

Inherited from: [LayoutItem](../interfaces/layoutitem.md)

Defined in: [layout.d.ts:58](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/layout.d.ts#L58)

___

### parse

▸ **parse**(`raw`: *unknown*, `index`: *number*): *unknown*

#### Parameters:

Name | Type |
:------ | :------ |
`raw` | *unknown* |
`index` | *number* |

**Returns:** *unknown*

Defined in: [index.esm.d.ts:1228](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1228)

___

### setDimensions

▸ **setDimensions**(): *void*

**Returns:** *void*

Defined in: [index.esm.d.ts:1237](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1237)

___

### tooltipPosition

▸ **tooltipPosition**(`useFinalPosition?`: *boolean*): [*Point*](../interfaces/point.md)

#### Parameters:

Name | Type |
:------ | :------ |
`useFinalPosition?` | *boolean* |

**Returns:** [*Point*](../interfaces/point.md)

Inherited from: Element.tooltipPosition

Defined in: [element.d.ts:9](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/element.d.ts#L9)

___

### update

▸ **update**(`width`: *number*, `height`: *number*, `margins?`: [*ChartArea*](../interfaces/chartarea.md)): *void*

Takes two parameters: width and height.

#### Parameters:

Name | Type |
:------ | :------ |
`width` | *number* |
`height` | *number* |
`margins?` | [*ChartArea*](../interfaces/chartarea.md) |

**Returns:** *void*

Inherited from: [LayoutItem](../interfaces/layoutitem.md)

Defined in: [layout.d.ts:64](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/layout.d.ts#L64)
