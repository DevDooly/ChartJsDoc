---
title: "Class: Animator"
---

# Class: Animator

## Constructors

### constructor

\+ **new Animator**(): [*Animator*](animator.md)

**Returns:** [*Animator*](animator.md)

## Methods

### add

▸ **add**(`chart`: [*Chart*](chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](../interfaces/scatterdatapoint.md) \| [*BubbleDataPoint*](../interfaces/bubbledatapoint.md))[], unknown\>, `items`: readonly [*Animation*](animation.md)[]): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`chart` | [*Chart*](chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](../interfaces/scatterdatapoint.md) \| [*BubbleDataPoint*](../interfaces/bubbledatapoint.md))[], unknown\> |
`items` | readonly [*Animation*](animation.md)[] |

**Returns:** *void*

Defined in: [animation.d.ts:20](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/animation.d.ts#L20)

___

### has

▸ **has**(`chart`: [*Chart*](chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](../interfaces/scatterdatapoint.md) \| [*BubbleDataPoint*](../interfaces/bubbledatapoint.md))[], unknown\>): *boolean*

#### Parameters:

Name | Type |
:------ | :------ |
`chart` | [*Chart*](chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](../interfaces/scatterdatapoint.md) \| [*BubbleDataPoint*](../interfaces/bubbledatapoint.md))[], unknown\> |

**Returns:** *boolean*

Defined in: [animation.d.ts:21](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/animation.d.ts#L21)

___

### listen

▸ **listen**(`chart`: [*Chart*](chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](../interfaces/scatterdatapoint.md) \| [*BubbleDataPoint*](../interfaces/bubbledatapoint.md))[], unknown\>, `event`: *complete* \| *progress*, `cb`: (`event`: [*AnimationEvent*](../interfaces/animationevent.md)) => *void*): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`chart` | [*Chart*](chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](../interfaces/scatterdatapoint.md) \| [*BubbleDataPoint*](../interfaces/bubbledatapoint.md))[], unknown\> |
`event` | *complete* \| *progress* |
`cb` | (`event`: [*AnimationEvent*](../interfaces/animationevent.md)) => *void* |

**Returns:** *void*

Defined in: [animation.d.ts:19](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/animation.d.ts#L19)

___

### remove

▸ **remove**(`chart`: [*Chart*](chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](../interfaces/scatterdatapoint.md) \| [*BubbleDataPoint*](../interfaces/bubbledatapoint.md))[], unknown\>): *boolean*

#### Parameters:

Name | Type |
:------ | :------ |
`chart` | [*Chart*](chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](../interfaces/scatterdatapoint.md) \| [*BubbleDataPoint*](../interfaces/bubbledatapoint.md))[], unknown\> |

**Returns:** *boolean*

Defined in: [animation.d.ts:25](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/animation.d.ts#L25)

___

### running

▸ **running**(`chart`: [*Chart*](chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](../interfaces/scatterdatapoint.md) \| [*BubbleDataPoint*](../interfaces/bubbledatapoint.md))[], unknown\>): *boolean*

#### Parameters:

Name | Type |
:------ | :------ |
`chart` | [*Chart*](chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](../interfaces/scatterdatapoint.md) \| [*BubbleDataPoint*](../interfaces/bubbledatapoint.md))[], unknown\> |

**Returns:** *boolean*

Defined in: [animation.d.ts:23](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/animation.d.ts#L23)

___

### start

▸ **start**(`chart`: [*Chart*](chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](../interfaces/scatterdatapoint.md) \| [*BubbleDataPoint*](../interfaces/bubbledatapoint.md))[], unknown\>): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`chart` | [*Chart*](chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](../interfaces/scatterdatapoint.md) \| [*BubbleDataPoint*](../interfaces/bubbledatapoint.md))[], unknown\> |

**Returns:** *void*

Defined in: [animation.d.ts:22](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/animation.d.ts#L22)

___

### stop

▸ **stop**(`chart`: [*Chart*](chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](../interfaces/scatterdatapoint.md) \| [*BubbleDataPoint*](../interfaces/bubbledatapoint.md))[], unknown\>): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`chart` | [*Chart*](chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](../interfaces/scatterdatapoint.md) \| [*BubbleDataPoint*](../interfaces/bubbledatapoint.md))[], unknown\> |

**Returns:** *void*

Defined in: [animation.d.ts:24](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/animation.d.ts#L24)
