---
title: "Class: Animations"
---

# Class: Animations

## Constructors

### constructor

\+ **new Animations**(`chart`: [*Chart*](chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](../interfaces/scatterdatapoint.md) \| [*BubbleDataPoint*](../interfaces/bubbledatapoint.md))[], unknown\>, `animations`: *Record*<string, unknown\>): [*Animations*](animations.md)

#### Parameters:

Name | Type |
:------ | :------ |
`chart` | [*Chart*](chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](../interfaces/scatterdatapoint.md) \| [*BubbleDataPoint*](../interfaces/bubbledatapoint.md))[], unknown\> |
`animations` | *Record*<string, unknown\> |

**Returns:** [*Animations*](animations.md)

Defined in: [animation.d.ts:28](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/animation.d.ts#L28)

## Methods

### configure

▸ **configure**(`animations`: *Record*<string, unknown\>): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`animations` | *Record*<string, unknown\> |

**Returns:** *void*

Defined in: [animation.d.ts:30](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/animation.d.ts#L30)

___

### update

▸ **update**(`target`: *Record*<string, unknown\>, `values`: *Record*<string, unknown\>): *boolean*

#### Parameters:

Name | Type |
:------ | :------ |
`target` | *Record*<string, unknown\> |
`values` | *Record*<string, unknown\> |

**Returns:** *boolean*

Defined in: [animation.d.ts:31](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/animation.d.ts#L31)
