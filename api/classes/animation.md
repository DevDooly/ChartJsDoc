---
title: "Class: Animation"
---

# Class: Animation

## Constructors

### constructor

\+ **new Animation**(`cfg`: *Record*<string, unknown\>, `target`: *Record*<string, unknown\>, `prop`: *string*, `to?`: *unknown*): [*Animation*](animation.md)

#### Parameters:

Name | Type |
:------ | :------ |
`cfg` | *Record*<string, unknown\> |
`target` | *Record*<string, unknown\> |
`prop` | *string* |
`to?` | *unknown* |

**Returns:** [*Animation*](animation.md)

Defined in: [animation.d.ts:4](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/animation.d.ts#L4)

## Methods

### active

▸ **active**(): *boolean*

**Returns:** *boolean*

Defined in: [animation.d.ts:6](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/animation.d.ts#L6)

___

### cancel

▸ **cancel**(): *void*

**Returns:** *void*

Defined in: [animation.d.ts:8](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/animation.d.ts#L8)

___

### tick

▸ **tick**(`date`: *number*): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`date` | *number* |

**Returns:** *void*

Defined in: [animation.d.ts:9](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/animation.d.ts#L9)

___

### update

▸ **update**(`cfg`: *Record*<string, unknown\>, `to`: *unknown*, `date`: *number*): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`cfg` | *Record*<string, unknown\> |
`to` | *unknown* |
`date` | *number* |

**Returns:** *void*

Defined in: [animation.d.ts:7](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/animation.d.ts#L7)
