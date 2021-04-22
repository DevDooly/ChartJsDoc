---
title: "Interface: DateAdapter"
---

# Interface: DateAdapter

## Properties

### options

• `Readonly` **options**: *any*

Defined in: [adapters.d.ts:6](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/adapters.d.ts#L6)

## Methods

### add

▸ **add**(`timestamp`: *number*, `amount`: *number*, `unit`: [*TimeUnit*](../README.md#timeunit)): *number*

Adds the specified `amount` of `unit` to the given `timestamp`.

#### Parameters:

Name | Type | Description |
:------ | :------ | :------ |
`timestamp` | *number* | the input timestamp   |
`amount` | *number* | the amount to add   |
`unit` | [*TimeUnit*](../README.md#timeunit) | the unit as string   |

**Returns:** *number*

Defined in: [adapters.d.ts:34](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/adapters.d.ts#L34)

___

### diff

▸ **diff**(`a`: *number*, `b`: *number*, `unit`: [*TimeUnit*](../README.md#timeunit)): *number*

Returns the number of `unit` between the given timestamps.

#### Parameters:

Name | Type | Description |
:------ | :------ | :------ |
`a` | *number* | the input timestamp (reference)   |
`b` | *number* | the timestamp to subtract   |
`unit` | [*TimeUnit*](../README.md#timeunit) | the unit as string   |

**Returns:** *number*

Defined in: [adapters.d.ts:42](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/adapters.d.ts#L42)

___

### endOf

▸ **endOf**(`timestamp`: *number*, `unit`: *millisecond* \| *second* \| *minute* \| *hour* \| *day* \| *week* \| *month* \| *quarter* \| *year* \| *isoWeek*): *number*

Returns end of `unit` for the given `timestamp`.

#### Parameters:

Name | Type | Description |
:------ | :------ | :------ |
`timestamp` | *number* | the input timestamp   |
`unit` | *millisecond* \| *second* \| *minute* \| *hour* \| *day* \| *week* \| *month* \| *quarter* \| *year* \| *isoWeek* | the unit as string   |

**Returns:** *number*

Defined in: [adapters.d.ts:58](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/adapters.d.ts#L58)

___

### format

▸ **format**(`timestamp`: *number*, `format`: [*TimeUnit*](../README.md#timeunit)): *string*

Returns the formatted date in the specified `format` for a given `timestamp`.

#### Parameters:

Name | Type | Description |
:------ | :------ | :------ |
`timestamp` | *number* | the timestamp to format   |
`format` | [*TimeUnit*](../README.md#timeunit) | the date/time token   |

**Returns:** *string*

Defined in: [adapters.d.ts:26](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/adapters.d.ts#L26)

___

### formats

▸ **formats**(): *object*

Returns a map of time formats for the supported formatting units defined
in Unit as well as 'datetime' representing a detailed date/time string.

**Returns:** *object*

Defined in: [adapters.d.ts:13](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/adapters.d.ts#L13)

___

### override

▸ **override**(`members`: *Partial*<[*DateAdapter*](dateadapter.md)\>): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`members` | *Partial*<[*DateAdapter*](dateadapter.md)\> |

**Returns:** *void*

Defined in: [adapters.d.ts:5](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/adapters.d.ts#L5)

___

### parse

▸ **parse**(`value`: *any*, `format?`: [*TimeUnit*](../README.md#timeunit)): *number*

Parses the given `value` and return the associated timestamp.

#### Parameters:

Name | Type | Description |
:------ | :------ | :------ |
`value` | *any* | the value to parse (usually comes from the data)   |
`format?` | [*TimeUnit*](../README.md#timeunit) | - |

**Returns:** *number*

Defined in: [adapters.d.ts:19](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/adapters.d.ts#L19)

___

### startOf

▸ **startOf**(`timestamp`: *number*, `unit`: *millisecond* \| *second* \| *minute* \| *hour* \| *day* \| *week* \| *month* \| *quarter* \| *year* \| *isoWeek*, `weekday?`: *number*): *number*

Returns start of `unit` for the given `timestamp`.

#### Parameters:

Name | Type | Description |
:------ | :------ | :------ |
`timestamp` | *number* | the input timestamp   |
`unit` | *millisecond* \| *second* \| *minute* \| *hour* \| *day* \| *week* \| *month* \| *quarter* \| *year* \| *isoWeek* | the unit as string   |
`weekday?` | *number* | - |

**Returns:** *number*

Defined in: [adapters.d.ts:51](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/adapters.d.ts#L51)
