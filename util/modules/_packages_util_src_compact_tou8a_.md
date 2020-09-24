**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/util/src/compact/toU8a"

# Module: "packages/util/src/compact/toU8a"

## Index

### Functions

* [compactToU8a](_packages_util_src_compact_tou8a_.md#compacttou8a)

## Functions

### compactToU8a

▸ **compactToU8a**(`_value`: BN \| BigInt \| number): Uint8Array

*Defined in [packages/util/src/compact/toU8a.ts:26](https://github.com/polkadot-js/common/blob/ce964d2f/packages/util/src/compact/toU8a.ts#L26)*

**`name`** compactToU8a

**`description`** Encodes a number into a compact representation

**`example`** 
<BR>

```javascript
import { compactToU8a } from '@polkadot/util';

console.log(compactToU8a(511, 32)); // Uint8Array([0b11111101, 0b00000111])
```

#### Parameters:

Name | Type |
------ | ------ |
`_value` | BN \| BigInt \| number |

**Returns:** Uint8Array
