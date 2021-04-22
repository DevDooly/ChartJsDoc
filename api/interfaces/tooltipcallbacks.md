---
title: "Interface: TooltipCallbacks<TType, Model, Item>"
---

# Interface: TooltipCallbacks<TType, Model, Item\>

## Type parameters

Name | Type | Default |
:------ | :------ | :------ |
`TType` | [*ChartType*](../README.md#charttype) | - |
`Model` | - | [*TooltipModel*](tooltipmodel.md)<TType\> |
`Item` | - | [*TooltipItem*](tooltipitem.md)<TType\> |

## Methods

### afterBody

▸ **afterBody**(`tooltipItems`: Item[]): *string* \| *string*[]

#### Parameters:

Name | Type |
:------ | :------ |
`tooltipItems` | Item[] |

**Returns:** *string* \| *string*[]

Defined in: [index.esm.d.ts:2351](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2351)

___

### afterFooter

▸ **afterFooter**(`tooltipItems`: Item[]): *string* \| *string*[]

#### Parameters:

Name | Type |
:------ | :------ |
`tooltipItems` | Item[] |

**Returns:** *string* \| *string*[]

Defined in: [index.esm.d.ts:2363](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2363)

___

### afterLabel

▸ **afterLabel**(`tooltipItem`: Item): *string* \| *string*[]

#### Parameters:

Name | Type |
:------ | :------ |
`tooltipItem` | Item |

**Returns:** *string* \| *string*[]

Defined in: [index.esm.d.ts:2355](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2355)

___

### afterTitle

▸ **afterTitle**(`tooltipItems`: Item[]): *string* \| *string*[]

#### Parameters:

Name | Type |
:------ | :------ |
`tooltipItems` | Item[] |

**Returns:** *string* \| *string*[]

Defined in: [index.esm.d.ts:2348](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2348)

___

### beforeBody

▸ **beforeBody**(`tooltipItems`: Item[]): *string* \| *string*[]

#### Parameters:

Name | Type |
:------ | :------ |
`tooltipItems` | Item[] |

**Returns:** *string* \| *string*[]

Defined in: [index.esm.d.ts:2350](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2350)

___

### beforeFooter

▸ **beforeFooter**(`tooltipItems`: Item[]): *string* \| *string*[]

#### Parameters:

Name | Type |
:------ | :------ |
`tooltipItems` | Item[] |

**Returns:** *string* \| *string*[]

Defined in: [index.esm.d.ts:2361](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2361)

___

### beforeLabel

▸ **beforeLabel**(`tooltipItem`: Item): *string* \| *string*[]

#### Parameters:

Name | Type |
:------ | :------ |
`tooltipItem` | Item |

**Returns:** *string* \| *string*[]

Defined in: [index.esm.d.ts:2353](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2353)

___

### beforeTitle

▸ **beforeTitle**(`tooltipItems`: Item[]): *string* \| *string*[]

#### Parameters:

Name | Type |
:------ | :------ |
`tooltipItems` | Item[] |

**Returns:** *string* \| *string*[]

Defined in: [index.esm.d.ts:2346](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2346)

___

### footer

▸ **footer**(`tooltipItems`: Item[]): *string* \| *string*[]

#### Parameters:

Name | Type |
:------ | :------ |
`tooltipItems` | Item[] |

**Returns:** *string* \| *string*[]

Defined in: [index.esm.d.ts:2362](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2362)

___

### label

▸ **label**(`tooltipItem`: Item): *string* \| *string*[]

#### Parameters:

Name | Type |
:------ | :------ |
`tooltipItem` | Item |

**Returns:** *string* \| *string*[]

Defined in: [index.esm.d.ts:2354](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2354)

___

### labelColor

▸ **labelColor**(`tooltipItem`: Item): [*TooltipLabelStyle*](tooltiplabelstyle.md)

#### Parameters:

Name | Type |
:------ | :------ |
`tooltipItem` | Item |

**Returns:** [*TooltipLabelStyle*](tooltiplabelstyle.md)

Defined in: [index.esm.d.ts:2357](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2357)

___

### labelPointStyle

▸ **labelPointStyle**(`tooltipItem`: Item): *object*

#### Parameters:

Name | Type |
:------ | :------ |
`tooltipItem` | Item |

**Returns:** *object*

Name | Type |
:------ | :------ |
`pointStyle` | [*PointStyle*](../README.md#pointstyle) |
`rotation` | *number* |

Defined in: [index.esm.d.ts:2359](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2359)

___

### labelTextColor

▸ **labelTextColor**(`tooltipItem`: Item): [*Color*](../README.md#color)

#### Parameters:

Name | Type |
:------ | :------ |
`tooltipItem` | Item |

**Returns:** [*Color*](../README.md#color)

Defined in: [index.esm.d.ts:2358](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2358)

___

### title

▸ **title**(`tooltipItems`: Item[]): *string* \| *string*[]

#### Parameters:

Name | Type |
:------ | :------ |
`tooltipItems` | Item[] |

**Returns:** *string* \| *string*[]

Defined in: [index.esm.d.ts:2347](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L2347)
