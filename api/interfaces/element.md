---
title: "Interface: Element<T, O>"
---

# Interface: Element<T, O\>

## Type parameters

Name | Default |
:------ | :------ |
`T` | {} |
`O` | {} |

## Properties

### active

• `Readonly` **active**: *boolean*

Defined in: [element.d.ts:6](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/element.d.ts#L6)

___

### options

• `Readonly` **options**: O

Defined in: [element.d.ts:7](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/element.d.ts#L7)

___

### x

• `Readonly` **x**: *number*

Defined in: [element.d.ts:4](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/element.d.ts#L4)

___

### y

• `Readonly` **y**: *number*

Defined in: [element.d.ts:5](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/element.d.ts#L5)

## Methods

### getProps

▸ **getProps**<P\>(`props`: [P], `final?`: *boolean*): *Pick*<T, P\>

#### Type parameters:

Name | Type |
:------ | :------ |
`P` | *string* \| *number* \| *symbol* |

#### Parameters:

Name | Type |
:------ | :------ |
`props` | [P] |
`final?` | *boolean* |

**Returns:** *Pick*<T, P\>

Defined in: [element.d.ts:11](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/element.d.ts#L11)

▸ **getProps**<P, P2\>(`props`: [P, P2], `final?`: *boolean*): *Pick*<T, P \| P2\>

#### Type parameters:

Name | Type |
:------ | :------ |
`P` | *string* \| *number* \| *symbol* |
`P2` | *string* \| *number* \| *symbol* |

#### Parameters:

Name | Type |
:------ | :------ |
`props` | [P, P2] |
`final?` | *boolean* |

**Returns:** *Pick*<T, P \| P2\>

Defined in: [element.d.ts:12](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/element.d.ts#L12)

▸ **getProps**<P, P2, P3\>(`props`: [P, P2, P3], `final?`: *boolean*): *Pick*<T, P \| P2 \| P3\>

#### Type parameters:

Name | Type |
:------ | :------ |
`P` | *string* \| *number* \| *symbol* |
`P2` | *string* \| *number* \| *symbol* |
`P3` | *string* \| *number* \| *symbol* |

#### Parameters:

Name | Type |
:------ | :------ |
`props` | [P, P2, P3] |
`final?` | *boolean* |

**Returns:** *Pick*<T, P \| P2 \| P3\>

Defined in: [element.d.ts:13](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/element.d.ts#L13)

▸ **getProps**<P, P2, P3, P4\>(`props`: [P, P2, P3, P4], `final?`: *boolean*): *Pick*<T, P \| P2 \| P3 \| P4\>

#### Type parameters:

Name | Type |
:------ | :------ |
`P` | *string* \| *number* \| *symbol* |
`P2` | *string* \| *number* \| *symbol* |
`P3` | *string* \| *number* \| *symbol* |
`P4` | *string* \| *number* \| *symbol* |

#### Parameters:

Name | Type |
:------ | :------ |
`props` | [P, P2, P3, P4] |
`final?` | *boolean* |

**Returns:** *Pick*<T, P \| P2 \| P3 \| P4\>

Defined in: [element.d.ts:17](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/element.d.ts#L17)

▸ **getProps**<P, P2, P3, P4, P5\>(`props`: [P, P2, P3, P4, P5], `final?`: *boolean*): *Pick*<T, P \| P2 \| P3 \| P4 \| P5\>

#### Type parameters:

Name | Type |
:------ | :------ |
`P` | *string* \| *number* \| *symbol* |
`P2` | *string* \| *number* \| *symbol* |
`P3` | *string* \| *number* \| *symbol* |
`P4` | *string* \| *number* \| *symbol* |
`P5` | *string* \| *number* \| *symbol* |

#### Parameters:

Name | Type |
:------ | :------ |
`props` | [P, P2, P3, P4, P5] |
`final?` | *boolean* |

**Returns:** *Pick*<T, P \| P2 \| P3 \| P4 \| P5\>

Defined in: [element.d.ts:21](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/element.d.ts#L21)

▸ **getProps**(`props`: keyof T[], `final?`: *boolean*): T

#### Parameters:

Name | Type |
:------ | :------ |
`props` | keyof T[] |
`final?` | *boolean* |

**Returns:** T

Defined in: [element.d.ts:25](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/element.d.ts#L25)

___

### hasValue

▸ **hasValue**(): *boolean*

**Returns:** *boolean*

Defined in: [element.d.ts:10](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/element.d.ts#L10)

___

### tooltipPosition

▸ **tooltipPosition**(`useFinalPosition?`: *boolean*): [*Point*](point.md)

#### Parameters:

Name | Type |
:------ | :------ |
`useFinalPosition?` | *boolean* |

**Returns:** [*Point*](point.md)

Defined in: [element.d.ts:9](https://github.com/chartjs/Chart.js/blob/b319f2cf/types/element.d.ts#L9)
