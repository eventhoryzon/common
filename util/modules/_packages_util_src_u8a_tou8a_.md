**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/util/src/u8a/toU8a"

# Module: "packages/util/src/u8a/toU8a"

## Index

### Functions

* [u8aToU8a](_packages_util_src_u8a_tou8a_.md#u8atou8a)

## Functions

### u8aToU8a

▸ **u8aToU8a**(`value?`: number[] \| Buffer \| Uint8Array \| string \| null): Uint8Array

*Defined in [packages/util/src/u8a/toU8a.ts:26](https://github.com/polkadot-js/common/blob/13ae8665/packages/util/src/u8a/toU8a.ts#L26)*

**`name`** u8aToU8a

**`summary`** Creates a Uint8Array value from a Uint8Array, Buffer, string or hex input.

**`description`** 
`null` or `undefined` inputs returns a `[]` result, Uint8Array values returns the value, hex strings returns a Uint8Array representation.

**`example`** 
<BR>

```javascript
import { u8aToU8a } from '@polkadot/util';

u8aToU8a(new Uint8Array([0x12, 0x34]); // => Uint8Array([0x12, 0x34])
u8aToU8a(0x1234); // => Uint8Array([0x12, 0x34])
```

#### Parameters:

Name | Type |
------ | ------ |
`value?` | number[] \| Buffer \| Uint8Array \| string \| null |

**Returns:** Uint8Array
