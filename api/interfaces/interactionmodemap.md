---
title: "Interface: InteractionModeMap"
---

# Interface: InteractionModeMap

## Properties

### dataset

• **dataset**: [*InteractionModeFunction*](../README.md#interactionmodefunction)

Returns items in the same dataset. If the options.intersect parameter is true, we only return items if we intersect something
If the options.intersect is false, we find the nearest item and return the items in that dataset

Defined in: [index.esm.d.ts:681](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L681)

___

### index

• **index**: [*InteractionModeFunction*](../README.md#interactionmodefunction)

Returns items at the same index. If the options.intersect parameter is true, we only return items if we intersect something
If the options.intersect mode is false, we find the nearest item and return the items at the same index as that item

Defined in: [index.esm.d.ts:675](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L675)

___

### nearest

• **nearest**: [*InteractionModeFunction*](../README.md#interactionmodefunction)

nearest mode returns the element closest to the point

Defined in: [index.esm.d.ts:690](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L690)

___

### point

• **point**: [*InteractionModeFunction*](../README.md#interactionmodefunction)

Point mode returns all elements that hit test based on the event position
of the event

Defined in: [index.esm.d.ts:686](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L686)

___

### x

• **x**: [*InteractionModeFunction*](../README.md#interactionmodefunction)

x mode returns the elements that hit-test at the current x coordinate

Defined in: [index.esm.d.ts:694](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L694)

___

### y

• **y**: [*InteractionModeFunction*](../README.md#interactionmodefunction)

y mode returns the elements that hit-test at the current y coordinate

Defined in: [index.esm.d.ts:698](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L698)
