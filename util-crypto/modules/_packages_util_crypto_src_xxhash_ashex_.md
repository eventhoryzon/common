**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/util-crypto/src/xxhash/asHex"

# Module: "packages/util-crypto/src/xxhash/asHex"

## Index

### Functions

* [xxhashAsHex](_packages_util_crypto_src_xxhash_ashex_.md#xxhashashex)

## Functions

### xxhashAsHex

▸ **xxhashAsHex**(`data`: Buffer \| Uint8Array \| string, `bitLength`: number): string

*Defined in [packages/util-crypto/src/xxhash/asHex.ts:22](https://github.com/polkadot-js/common/blob/ce964d2f/packages/util-crypto/src/xxhash/asHex.ts#L22)*

**`name`** xxhashAsHex

**`summary`** Creates a xxhash64 hex from the input.

**`description`** 
From either a `string`, `Uint8Array` or a `Buffer` input, create the xxhash64 and return the result as a hex string with the specified `bitLength`.

**`example`** 
<BR>

```javascript
import { xxhashAsHex } from '@polkadot/util-crypto';

xxhashAsHex('abc'); // => 0x44bc2cf5ad770999
```

#### Parameters:

Name | Type | Default value |
------ | ------ | ------ |
`data` | Buffer \| Uint8Array \| string | - |
`bitLength` | number | 64 |

**Returns:** string
