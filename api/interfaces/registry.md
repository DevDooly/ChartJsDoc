---
title: "Interface: Registry"
---

# Interface: Registry

Please use the module's default export which provides a singleton instance
Note: class is exported for typedoc

## Properties

### controllers

• `Readonly` **controllers**: [*TypedRegistry*](typedregistry.md)<[*DatasetController*](../classes/datasetcontroller.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, [*Element*](../README.md#element)<{}, {}\>, [*Element*](../README.md#element)<{}, {}\>, number \| BarParsedData \| CartesianParsedData \| BubbleParsedData \| RadialParsedData\>\>

Defined in: [index.esm.d.ts:1041](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1041)

___

### elements

• `Readonly` **elements**: [*TypedRegistry*](typedregistry.md)<[*Element*](../README.md#element)<{}, {}\>\>

Defined in: [index.esm.d.ts:1042](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1042)

___

### plugins

• `Readonly` **plugins**: [*TypedRegistry*](typedregistry.md)<[*Plugin*](plugin.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, Record<string, unknown\>\>\>

Defined in: [index.esm.d.ts:1043](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1043)

___

### scales

• `Readonly` **scales**: [*TypedRegistry*](typedregistry.md)<[*Scale*](../classes/scale.md)<[*CoreScaleOptions*](corescaleoptions.md)\>\>

Defined in: [index.esm.d.ts:1044](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1044)

## Methods

### add

▸ **add**(...`args`: [*ChartComponentLike*](../README.md#chartcomponentlike)[]): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`...args` | [*ChartComponentLike*](../README.md#chartcomponentlike)[] |

**Returns:** *void*

Defined in: [index.esm.d.ts:1046](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1046)

___

### addControllers

▸ **addControllers**(...`args`: [*ChartComponentLike*](../README.md#chartcomponentlike)[]): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`...args` | [*ChartComponentLike*](../README.md#chartcomponentlike)[] |

**Returns:** *void*

Defined in: [index.esm.d.ts:1049](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1049)

___

### addElements

▸ **addElements**(...`args`: [*ChartComponentLike*](../README.md#chartcomponentlike)[]): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`...args` | [*ChartComponentLike*](../README.md#chartcomponentlike)[] |

**Returns:** *void*

Defined in: [index.esm.d.ts:1050](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1050)

___

### addPlugins

▸ **addPlugins**(...`args`: [*ChartComponentLike*](../README.md#chartcomponentlike)[]): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`...args` | [*ChartComponentLike*](../README.md#chartcomponentlike)[] |

**Returns:** *void*

Defined in: [index.esm.d.ts:1051](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1051)

___

### addScales

▸ **addScales**(...`args`: [*ChartComponentLike*](../README.md#chartcomponentlike)[]): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`...args` | [*ChartComponentLike*](../README.md#chartcomponentlike)[] |

**Returns:** *void*

Defined in: [index.esm.d.ts:1052](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1052)

___

### getController

▸ **getController**(`id`: *string*): [*DatasetController*](../classes/datasetcontroller.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, [*Element*](../README.md#element)<{}, {}\>, [*Element*](../README.md#element)<{}, {}\>, number \| BarParsedData \| CartesianParsedData \| BubbleParsedData \| RadialParsedData\>

#### Parameters:

Name | Type |
:------ | :------ |
`id` | *string* |

**Returns:** [*DatasetController*](../classes/datasetcontroller.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, [*Element*](../README.md#element)<{}, {}\>, [*Element*](../README.md#element)<{}, {}\>, number \| BarParsedData \| CartesianParsedData \| BubbleParsedData \| RadialParsedData\>

Defined in: [index.esm.d.ts:1054](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1054)

___

### getElement

▸ **getElement**(`id`: *string*): [*Element*](../README.md#element)<{}, {}\>

#### Parameters:

Name | Type |
:------ | :------ |
`id` | *string* |

**Returns:** [*Element*](../README.md#element)<{}, {}\>

Defined in: [index.esm.d.ts:1055](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1055)

___

### getPlugin

▸ **getPlugin**(`id`: *string*): [*Plugin*](plugin.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, Record<string, unknown\>\>

#### Parameters:

Name | Type |
:------ | :------ |
`id` | *string* |

**Returns:** [*Plugin*](plugin.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, Record<string, unknown\>\>

Defined in: [index.esm.d.ts:1056](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1056)

___

### getScale

▸ **getScale**(`id`: *string*): [*Scale*](../classes/scale.md)<[*CoreScaleOptions*](corescaleoptions.md)\>

#### Parameters:

Name | Type |
:------ | :------ |
`id` | *string* |

**Returns:** [*Scale*](../classes/scale.md)<[*CoreScaleOptions*](corescaleoptions.md)\>

Defined in: [index.esm.d.ts:1057](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1057)

___

### remove

▸ **remove**(...`args`: [*ChartComponentLike*](../README.md#chartcomponentlike)[]): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`...args` | [*ChartComponentLike*](../README.md#chartcomponentlike)[] |

**Returns:** *void*

Defined in: [index.esm.d.ts:1047](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1047)
