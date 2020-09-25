**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/util-crypto/src/keccak/asHex"

# Module: "packages/util-crypto/src/keccak/asHex"

## Index

### Functions

* [keccakAsHex](_packages_util_crypto_src_keccak_ashex_.md#keccakashex)

## Functions

### keccakAsHex

▸ **keccakAsHex**(`value`: Buffer \| Uint8Array \| string): string

*Defined in [packages/util-crypto/src/keccak/asHex.ts:22](https://github.com/polkadot-js/common/blob/bd1735ca/packages/util-crypto/src/keccak/asHex.ts#L22)*

**`name`** keccakAsHex

**`summary`** Creates a keccak hex string from the input.

**`description`** 
From either a `string` or a `Buffer` input, create the keccak and return the result as a `0x` prefixed hex string.

**`example`** 
<BR>

```javascript
import { keccakAsHex } from '@polkadot/util-crypto';

keccakAsHex('123'); // => 0x...
```

#### Parameters:

Name | Type |
------ | ------ |
`value` | Buffer \| Uint8Array \| string |

**Returns:** string
