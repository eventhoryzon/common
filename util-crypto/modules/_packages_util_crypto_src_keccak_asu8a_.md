**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/util-crypto/src/keccak/asU8a"

# Module: "packages/util-crypto/src/keccak/asU8a"

## Index

### Functions

* [keccakAsU8a](_packages_util_crypto_src_keccak_asu8a_.md#keccakasu8a)

## Functions

### keccakAsU8a

▸ **keccakAsU8a**(`value`: Buffer \| Uint8Array \| string): Uint8Array

*Defined in [packages/util-crypto/src/keccak/asU8a.ts:22](https://github.com/polkadot-js/common/blob/dd1220ac/packages/util-crypto/src/keccak/asU8a.ts#L22)*

**`name`** keccakAsU8a

**`summary`** Creates a keccak Uint8Array from the input.

**`description`** 
From either a `string` or a `Buffer` input, create the keccak and return the result as a `Uint8Array`.

**`example`** 
<BR>

```javascript
import { keccakAsU8a } from '@polkadot/util-crypto';

keccakAsU8a('123'); // => Uint8Array
```

#### Parameters:

Name | Type |
------ | ------ |
`value` | Buffer \| Uint8Array \| string |

**Returns:** Uint8Array
