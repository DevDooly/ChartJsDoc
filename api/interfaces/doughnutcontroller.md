---
title: "Interface: DoughnutController"
---

# Interface: DoughnutController

## Hierarchy

* [*DatasetController*](../classes/datasetcontroller.md)

  ↳ **DoughnutController**

## Properties

### \_cachedMeta

• `Readonly` **\_cachedMeta**: [*ChartMeta*](chartmeta.md)<[*Element*](../README.md#element)<{}, {}\>, [*Element*](../README.md#element)<{}, {}\>\>

Inherited from: [DatasetController](../classes/datasetcontroller.md).[_cachedMeta](../classes/datasetcontroller.md#_cachedmeta)

Defined in: [index.esm.d.ts:537](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L537)

___

### chart

• `Readonly` **chart**: [*Chart*](../classes/chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[], unknown\>

Inherited from: [DatasetController](../classes/datasetcontroller.md).[chart](../classes/datasetcontroller.md#chart)

Defined in: [index.esm.d.ts:535](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L535)

___

### enableOptionSharing

• **enableOptionSharing**: *boolean*

Inherited from: [DatasetController](../classes/datasetcontroller.md).[enableOptionSharing](../classes/datasetcontroller.md#enableoptionsharing)

Defined in: [index.esm.d.ts:538](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L538)

___

### index

• `Readonly` **index**: *number*

Inherited from: [DatasetController](../classes/datasetcontroller.md).[index](../classes/datasetcontroller.md#index)

Defined in: [index.esm.d.ts:536](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L536)

___

### innerRadius

• `Readonly` **innerRadius**: *number*

Defined in: [index.esm.d.ts:303](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L303)

___

### offsetX

• `Readonly` **offsetX**: *number*

Defined in: [index.esm.d.ts:305](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L305)

___

### offsetY

• `Readonly` **offsetY**: *number*

Defined in: [index.esm.d.ts:306](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L306)

___

### outerRadius

• `Readonly` **outerRadius**: *number*

Defined in: [index.esm.d.ts:304](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L304)

## Methods

### addElements

▸ **addElements**(): *void*

**Returns:** *void*

Inherited from: [DatasetController](../classes/datasetcontroller.md)

Defined in: [index.esm.d.ts:554](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L554)

___

### applyStack

▸ `Protected`**applyStack**(`scale`: [*Scale*](../classes/scale.md)<[*CoreScaleOptions*](corescaleoptions.md)\>, `parsed`: *unknown*[]): *number*

#### Parameters:

Name | Type |
:------ | :------ |
`scale` | [*Scale*](../classes/scale.md)<[*CoreScaleOptions*](corescaleoptions.md)\> |
`parsed` | *unknown*[] |

**Returns:** *number*

Inherited from: [DatasetController](../classes/datasetcontroller.md)

Defined in: [index.esm.d.ts:590](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L590)

___

### buildOrUpdateElements

▸ **buildOrUpdateElements**(`resetNewElements?`: *boolean*): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`resetNewElements?` | *boolean* |

**Returns:** *void*

Inherited from: [DatasetController](../classes/datasetcontroller.md)

Defined in: [index.esm.d.ts:555](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L555)

___

### calculateCircumference

▸ **calculateCircumference**(`value`: *number*): *number*

#### Parameters:

Name | Type |
:------ | :------ |
`value` | *number* |

**Returns:** *number*

Defined in: [index.esm.d.ts:309](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L309)

___

### calculateTotal

▸ **calculateTotal**(): *number*

**Returns:** *number*

Defined in: [index.esm.d.ts:308](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L308)

___

### configure

▸ **configure**(): *void*

**Returns:** *void*

Inherited from: [DatasetController](../classes/datasetcontroller.md)

Defined in: [index.esm.d.ts:552](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L552)

___

### draw

▸ **draw**(): *void*

**Returns:** *void*

Inherited from: [DatasetController](../classes/datasetcontroller.md)

Defined in: [index.esm.d.ts:547](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L547)

___

### getAllParsedValues

▸ **getAllParsedValues**(`scale`: [*Scale*](../classes/scale.md)<[*CoreScaleOptions*](corescaleoptions.md)\>): *number*[]

#### Parameters:

Name | Type |
:------ | :------ |
`scale` | [*Scale*](../classes/scale.md)<[*CoreScaleOptions*](corescaleoptions.md)\> |

**Returns:** *number*[]

Inherited from: [DatasetController](../classes/datasetcontroller.md)

Defined in: [index.esm.d.ts:541](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L541)

___

### getDataset

▸ **getDataset**(): [*ChartDataset*](../README.md#chartdataset)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[]\>

**Returns:** [*ChartDataset*](../README.md#chartdataset)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](scatterdatapoint.md) \| [*BubbleDataPoint*](bubbledatapoint.md))[]\>

Inherited from: [DatasetController](../classes/datasetcontroller.md)

Defined in: [index.esm.d.ts:549](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L549)

___

### getLabelAndValue

▸ `Protected`**getLabelAndValue**(`index`: *number*): *object*

#### Parameters:

Name | Type |
:------ | :------ |
`index` | *number* |

**Returns:** *object*

Name | Type |
:------ | :------ |
`label` | *string* |
`value` | *string* |

Inherited from: [DatasetController](../classes/datasetcontroller.md)

Defined in: [index.esm.d.ts:542](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L542)

___

### getMaxOverflow

▸ `Protected`**getMaxOverflow**(): *number* \| *boolean*

**Returns:** *number* \| *boolean*

Inherited from: [DatasetController](../classes/datasetcontroller.md)

Defined in: [index.esm.d.ts:546](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L546)

___

### getMeta

▸ **getMeta**(): [*ChartMeta*](chartmeta.md)<[*Element*](../README.md#element)<{}, {}\>, [*Element*](../README.md#element)<{}, {}\>\>

**Returns:** [*ChartMeta*](chartmeta.md)<[*Element*](../README.md#element)<{}, {}\>, [*Element*](../README.md#element)<{}, {}\>\>

Inherited from: [DatasetController](../classes/datasetcontroller.md)

Defined in: [index.esm.d.ts:550](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L550)

___

### getMinMax

▸ `Protected`**getMinMax**(`scale`: [*Scale*](../classes/scale.md)<[*CoreScaleOptions*](corescaleoptions.md)\>, `canStack?`: *boolean*): *object*

#### Parameters:

Name | Type |
:------ | :------ |
`scale` | [*Scale*](../classes/scale.md)<[*CoreScaleOptions*](corescaleoptions.md)\> |
`canStack?` | *boolean* |

**Returns:** *object*

Name | Type |
:------ | :------ |
`max` | *number* |
`min` | *number* |

Inherited from: [DatasetController](../classes/datasetcontroller.md)

Defined in: [index.esm.d.ts:597](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L597)

___

### getParsed

▸ `Protected`**getParsed**(`index`: *number*): *number* \| BarParsedData \| CartesianParsedData \| BubbleParsedData \| RadialParsedData

#### Parameters:

Name | Type |
:------ | :------ |
`index` | *number* |

**Returns:** *number* \| BarParsedData \| CartesianParsedData \| BubbleParsedData \| RadialParsedData

Inherited from: [DatasetController](../classes/datasetcontroller.md)

Defined in: [index.esm.d.ts:589](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L589)

___

### getScaleForId

▸ **getScaleForId**(`scaleID`: *string*): [*Scale*](../classes/scale.md)<[*CoreScaleOptions*](corescaleoptions.md)\>

#### Parameters:

Name | Type |
:------ | :------ |
`scaleID` | *string* |

**Returns:** [*Scale*](../classes/scale.md)<[*CoreScaleOptions*](corescaleoptions.md)\>

Inherited from: [DatasetController](../classes/datasetcontroller.md)

Defined in: [index.esm.d.ts:551](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L551)

___

### getSharedOptions

▸ `Protected`**getSharedOptions**(`options`: *Record*<string, unknown\>): *Record*<string, unknown\>

Utility for checking if the options are shared and should be animated separately.

#### Parameters:

Name | Type |
:------ | :------ |
`options` | *Record*<string, unknown\> |

**Returns:** *Record*<string, unknown\>

Inherited from: [DatasetController](../classes/datasetcontroller.md)

Defined in: [index.esm.d.ts:564](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L564)

___

### getStyle

▸ **getStyle**(`index`: *number*, `active`: *boolean*): *Record*<string, unknown\>

#### Parameters:

Name | Type |
:------ | :------ |
`index` | *number* |
`active` | *boolean* |

**Returns:** *Record*<string, unknown\>

Inherited from: [DatasetController](../classes/datasetcontroller.md)

Defined in: [index.esm.d.ts:557](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L557)

___

### includeOptions

▸ `Protected`**includeOptions**(`mode`: *resize* \| *reset* \| *none* \| *hide* \| *show* \| *normal* \| *active*, `sharedOptions`: *Record*<string, unknown\>): *boolean*

Utility for determining if `options` should be included in the updated properties

#### Parameters:

Name | Type |
:------ | :------ |
`mode` | *resize* \| *reset* \| *none* \| *hide* \| *show* \| *normal* \| *active* |
`sharedOptions` | *Record*<string, unknown\> |

**Returns:** *boolean*

Inherited from: [DatasetController](../classes/datasetcontroller.md)

Defined in: [index.esm.d.ts:569](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L569)

___

### initialize

▸ **initialize**(): *void*

**Returns:** *void*

Inherited from: [DatasetController](../classes/datasetcontroller.md)

Defined in: [index.esm.d.ts:553](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L553)

___

### linkScales

▸ **linkScales**(): *void*

**Returns:** *void*

Inherited from: [DatasetController](../classes/datasetcontroller.md)

Defined in: [index.esm.d.ts:540](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L540)

___

### parse

▸ **parse**(`start`: *number*, `count`: *number*): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`start` | *number* |
`count` | *number* |

**Returns:** *void*

Inherited from: [DatasetController](../classes/datasetcontroller.md)

Defined in: [index.esm.d.ts:585](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L585)

___

### parseArrayData

▸ `Protected`**parseArrayData**(`meta`: [*ChartMeta*](chartmeta.md)<[*Element*](../README.md#element)<{}, {}\>, [*Element*](../README.md#element)<{}, {}\>\>, `data`: *Record*<string, unknown\>[], `start`: *number*, `count`: *number*): *Record*<string, unknown\>[]

#### Parameters:

Name | Type |
:------ | :------ |
`meta` | [*ChartMeta*](chartmeta.md)<[*Element*](../README.md#element)<{}, {}\>, [*Element*](../README.md#element)<{}, {}\>\> |
`data` | *Record*<string, unknown\>[] |
`start` | *number* |
`count` | *number* |

**Returns:** *Record*<string, unknown\>[]

Inherited from: [DatasetController](../classes/datasetcontroller.md)

Defined in: [index.esm.d.ts:587](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L587)

___

### parseObjectData

▸ `Protected`**parseObjectData**(`meta`: [*ChartMeta*](chartmeta.md)<[*Element*](../README.md#element)<{}, {}\>, [*Element*](../README.md#element)<{}, {}\>\>, `data`: *Record*<string, unknown\>[], `start`: *number*, `count`: *number*): *Record*<string, unknown\>[]

#### Parameters:

Name | Type |
:------ | :------ |
`meta` | [*ChartMeta*](chartmeta.md)<[*Element*](../README.md#element)<{}, {}\>, [*Element*](../README.md#element)<{}, {}\>\> |
`data` | *Record*<string, unknown\>[] |
`start` | *number* |
`count` | *number* |

**Returns:** *Record*<string, unknown\>[]

Inherited from: [DatasetController](../classes/datasetcontroller.md)

Defined in: [index.esm.d.ts:588](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L588)

___

### parsePrimitiveData

▸ `Protected`**parsePrimitiveData**(`meta`: [*ChartMeta*](chartmeta.md)<[*Element*](../README.md#element)<{}, {}\>, [*Element*](../README.md#element)<{}, {}\>\>, `data`: *Record*<string, unknown\>[], `start`: *number*, `count`: *number*): *Record*<string, unknown\>[]

#### Parameters:

Name | Type |
:------ | :------ |
`meta` | [*ChartMeta*](chartmeta.md)<[*Element*](../README.md#element)<{}, {}\>, [*Element*](../README.md#element)<{}, {}\>\> |
`data` | *Record*<string, unknown\>[] |
`start` | *number* |
`count` | *number* |

**Returns:** *Record*<string, unknown\>[]

Inherited from: [DatasetController](../classes/datasetcontroller.md)

Defined in: [index.esm.d.ts:586](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L586)

___

### removeHoverStyle

▸ **removeHoverStyle**(`element`: [*Element*](../README.md#element)<{}, {}\>, `datasetIndex`: *number*, `index`: *number*): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`element` | [*Element*](../README.md#element)<{}, {}\> |
`datasetIndex` | *number* |
`index` | *number* |

**Returns:** *void*

Inherited from: [DatasetController](../classes/datasetcontroller.md)

Defined in: [index.esm.d.ts:582](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L582)

___

### reset

▸ **reset**(): *void*

**Returns:** *void*

Inherited from: [DatasetController](../classes/datasetcontroller.md)

Defined in: [index.esm.d.ts:548](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L548)

___

### resolveDataElementOptions

▸ `Protected`**resolveDataElementOptions**(`index`: *number*, `mode`: *resize* \| *reset* \| *none* \| *hide* \| *show* \| *normal* \| *active*): *Record*<string, unknown\>

#### Parameters:

Name | Type |
:------ | :------ |
`index` | *number* |
`mode` | *resize* \| *reset* \| *none* \| *hide* \| *show* \| *normal* \| *active* |

**Returns:** *Record*<string, unknown\>

Inherited from: [DatasetController](../classes/datasetcontroller.md)

Defined in: [index.esm.d.ts:559](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L559)

___

### resolveDatasetElementOptions

▸ `Protected`**resolveDatasetElementOptions**(`mode`: *resize* \| *reset* \| *none* \| *hide* \| *show* \| *normal* \| *active*): *Record*<string, unknown\>

#### Parameters:

Name | Type |
:------ | :------ |
`mode` | *resize* \| *reset* \| *none* \| *hide* \| *show* \| *normal* \| *active* |

**Returns:** *Record*<string, unknown\>

Inherited from: [DatasetController](../classes/datasetcontroller.md)

Defined in: [index.esm.d.ts:558](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L558)

___

### setHoverStyle

▸ **setHoverStyle**(`element`: [*Element*](../README.md#element)<{}, {}\>, `datasetIndex`: *number*, `index`: *number*): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`element` | [*Element*](../README.md#element)<{}, {}\> |
`datasetIndex` | *number* |
`index` | *number* |

**Returns:** *void*

Inherited from: [DatasetController](../classes/datasetcontroller.md)

Defined in: [index.esm.d.ts:583](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L583)

___

### update

▸ **update**(`mode`: *resize* \| *reset* \| *none* \| *hide* \| *show* \| *normal* \| *active*): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`mode` | *resize* \| *reset* \| *none* \| *hide* \| *show* \| *normal* \| *active* |

**Returns:** *void*

Inherited from: [DatasetController](../classes/datasetcontroller.md)

Defined in: [index.esm.d.ts:544](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L544)

___

### updateElement

▸ `Protected`**updateElement**(`element`: [*Element*](../README.md#element)<{}, {}\>, `index`: *number*, `properties`: *Record*<string, unknown\>, `mode`: *resize* \| *reset* \| *none* \| *hide* \| *show* \| *normal* \| *active*): *void*

Utility for updating an element with new properties, using animations when appropriate.

#### Parameters:

Name | Type |
:------ | :------ |
`element` | [*Element*](../README.md#element)<{}, {}\> |
`index` | *number* |
`properties` | *Record*<string, unknown\> |
`mode` | *resize* \| *reset* \| *none* \| *hide* \| *show* \| *normal* \| *active* |

**Returns:** *void*

Inherited from: [DatasetController](../classes/datasetcontroller.md)

Defined in: [index.esm.d.ts:575](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L575)

___

### updateElements

▸ **updateElements**(`elements`: [*Element*](../README.md#element)<{}, {}\>[], `start`: *number*, `count`: *number*, `mode`: *resize* \| *reset* \| *none* \| *hide* \| *show* \| *normal* \| *active*): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`elements` | [*Element*](../README.md#element)<{}, {}\>[] |
`start` | *number* |
`count` | *number* |
`mode` | *resize* \| *reset* \| *none* \| *hide* \| *show* \| *normal* \| *active* |

**Returns:** *void*

Inherited from: [DatasetController](../classes/datasetcontroller.md)

Defined in: [index.esm.d.ts:543](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L543)

___

### updateIndex

▸ **updateIndex**(`datasetIndex`: *number*): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`datasetIndex` | *number* |

**Returns:** *void*

Inherited from: [DatasetController](../classes/datasetcontroller.md)

Defined in: [index.esm.d.ts:545](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L545)

___

### updateRangeFromParsed

▸ `Protected`**updateRangeFromParsed**(`range`: { `max`: *number* ; `min`: *number*  }, `scale`: [*Scale*](../classes/scale.md)<[*CoreScaleOptions*](corescaleoptions.md)\>, `parsed`: *unknown*[], `stack`: *string* \| *boolean*): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`range` | *object* |
`range.max` | *number* |
`range.min` | *number* |
`scale` | [*Scale*](../classes/scale.md)<[*CoreScaleOptions*](corescaleoptions.md)\> |
`parsed` | *unknown*[] |
`stack` | *string* \| *boolean* |

**Returns:** *void*

Inherited from: [DatasetController](../classes/datasetcontroller.md)

Defined in: [index.esm.d.ts:591](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L591)

___

### updateSharedOptions

▸ `Protected`**updateSharedOptions**(`sharedOptions`: *Record*<string, unknown\>, `mode`: *resize* \| *reset* \| *none* \| *hide* \| *show* \| *normal* \| *active*, `newOptions`: *Record*<string, unknown\>): *void*

Utility to animate the shared options, that are potentially affecting multiple elements.

#### Parameters:

Name | Type |
:------ | :------ |
`sharedOptions` | *Record*<string, unknown\> |
`mode` | *resize* \| *reset* \| *none* \| *hide* \| *show* \| *normal* \| *active* |
`newOptions` | *Record*<string, unknown\> |

**Returns:** *void*

Inherited from: [DatasetController](../classes/datasetcontroller.md)

Defined in: [index.esm.d.ts:581](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L581)
