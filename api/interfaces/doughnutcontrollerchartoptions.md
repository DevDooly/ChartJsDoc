---
title: "Interface: DoughnutControllerChartOptions"
---

# Interface: DoughnutControllerChartOptions

## Properties

### animation

• **animation**: [*DoughnutAnimationOptions*](doughnutanimationoptions.md)

Defined in: [index.esm.d.ts:297](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L297)

___

### circumference

• **circumference**: *number*

Sweep to allow arcs to cover.

**`default`** 360

Defined in: [index.esm.d.ts:276](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L276)

___

### cutout

• **cutout**: [*Scriptable*](../README.md#scriptable)<string \| number, [*ScriptableContext*](scriptablecontext.md)<*doughnut*\>\>

The portion of the chart that is cut out of the middle. ('50%' - for doughnut, 0 - for pie)
String ending with '%' means percentage, number means pixels.

**`default`** 50

Defined in: [index.esm.d.ts:283](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L283)

___

### radius

• **radius**: [*Scriptable*](../README.md#scriptable)<string \| number, [*ScriptableContext*](scriptablecontext.md)<*doughnut*\>\>

The outer radius of the chart. String ending with '%' means percentage of maximum radius, number means pixels.

**`default`** '100%'

Defined in: [index.esm.d.ts:289](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L289)

___

### rotation

• **rotation**: *number*

Starting angle to draw arcs from.

**`default`** 0

Defined in: [index.esm.d.ts:295](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/index.esm.d.ts#L295)
