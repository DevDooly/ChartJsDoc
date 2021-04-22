---
title: "Class: BasePlatform"
---

# Class: BasePlatform

## Hierarchy

* **BasePlatform**

  ↳ [*BasicPlatform*](basicplatform.md)

  ↳ [*DomPlatform*](domplatform.md)

## Constructors

### constructor

\+ **new BasePlatform**(): [*BasePlatform*](baseplatform.md)

**Returns:** [*BasePlatform*](baseplatform.md)

## Methods

### acquireContext

▸ **acquireContext**(`canvas`: HTMLCanvasElement, `options?`: CanvasRenderingContext2DSettings): CanvasRenderingContext2D

Called at chart construction time, returns a context2d instance implementing
the [W3C Canvas 2D Context API standard](https://www.w3.org/TR/2dcontext/).

#### Parameters:

Name | Type | Description |
:------ | :------ | :------ |
`canvas` | HTMLCanvasElement | The canvas from which to acquire context (platform specific)   |
`options?` | CanvasRenderingContext2DSettings | The chart options    |

**Returns:** CanvasRenderingContext2D

Defined in: [index.esm.d.ts:1907](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1907)

___

### addEventListener

▸ **addEventListener**(`chart`: [*Chart*](chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](../interfaces/scatterdatapoint.md) \| [*BubbleDataPoint*](../interfaces/bubbledatapoint.md))[], unknown\>, `type`: *string*, `listener`: (`e`: [*ChartEvent*](../interfaces/chartevent.md)) => *void*): *void*

Registers the specified listener on the given chart.

#### Parameters:

Name | Type | Description |
:------ | :------ | :------ |
`chart` | [*Chart*](chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](../interfaces/scatterdatapoint.md) \| [*BubbleDataPoint*](../interfaces/bubbledatapoint.md))[], unknown\> | Chart from which to listen for event   |
`type` | *string* | The ([ChartEvent](../interfaces/chartevent.md)) type to listen for   |
`listener` | (`e`: [*ChartEvent*](../interfaces/chartevent.md)) => *void* | Receives a notification (an object that implements the [ChartEvent](../interfaces/chartevent.md) interface) when an event of the specified type occurs.    |

**Returns:** *void*

Defined in: [index.esm.d.ts:1925](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1925)

___

### getDevicePixelRatio

▸ **getDevicePixelRatio**(): *number*

**Returns:** *number*

the current devicePixelRatio of the device this platform is connected to.

Defined in: [index.esm.d.ts:1936](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1936)

___

### getMaximumSize

▸ **getMaximumSize**(`canvas`: HTMLCanvasElement, `width?`: *number*, `height?`: *number*, `aspectRatio?`: *number*): *object*

#### Parameters:

Name | Type | Description |
:------ | :------ | :------ |
`canvas` | HTMLCanvasElement | The canvas for which to calculate the maximum size   |
`width?` | *number* | - |
`height?` | *number* | - |
`aspectRatio?` | *number* | - |

**Returns:** *object*

Name | Type |
:------ | :------ |
`height` | *number* |
`width` | *number* |

the maximum size available.

Defined in: [index.esm.d.ts:1944](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1944)

___

### isAttached

▸ **isAttached**(`canvas`: HTMLCanvasElement): *boolean*

#### Parameters:

Name | Type |
:------ | :------ |
`canvas` | HTMLCanvasElement |

**Returns:** *boolean*

true if the canvas is attached to the platform, false if not.

Defined in: [index.esm.d.ts:1949](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1949)

___

### releaseContext

▸ **releaseContext**(`context`: CanvasRenderingContext2D): *boolean*

Called at chart destruction time, releases any resources associated to the context
previously returned by the acquireContext() method.

#### Parameters:

Name | Type | Description |
:------ | :------ | :------ |
`context` | CanvasRenderingContext2D | The context2d instance   |

**Returns:** *boolean*

true if the method succeeded, else false

Defined in: [index.esm.d.ts:1917](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1917)

___

### removeEventListener

▸ **removeEventListener**(`chart`: [*Chart*](chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](../interfaces/scatterdatapoint.md) \| [*BubbleDataPoint*](../interfaces/bubbledatapoint.md))[], unknown\>, `type`: *string*, `listener`: (`e`: [*ChartEvent*](../interfaces/chartevent.md)) => *void*): *void*

Removes the specified listener previously registered with addEventListener.

#### Parameters:

Name | Type | Description |
:------ | :------ | :------ |
`chart` | [*Chart*](chart.md)<*bar* \| *line* \| *scatter* \| *bubble* \| *pie* \| *doughnut* \| *polarArea* \| *radar*, (number \| [*ScatterDataPoint*](../interfaces/scatterdatapoint.md) \| [*BubbleDataPoint*](../interfaces/bubbledatapoint.md))[], unknown\> | Chart from which to remove the listener   |
`type` | *string* | The ([ChartEvent](../interfaces/chartevent.md)) type to remove   |
`listener` | (`e`: [*ChartEvent*](../interfaces/chartevent.md)) => *void* | The listener function to remove from the event target.    |

**Returns:** *void*

Defined in: [index.esm.d.ts:1932](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L1932)
