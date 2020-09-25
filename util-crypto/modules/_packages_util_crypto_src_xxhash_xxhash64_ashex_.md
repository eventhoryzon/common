**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/util-crypto/src/xxhash/xxhash64/asHex"

# Module: "packages/util-crypto/src/xxhash/xxhash64/asHex"

## Index

### Functions

* [xxhash64AsHex](_packages_util_crypto_src_xxhash_xxhash64_ashex_.md#xxhash64ashex)

## Functions

### xxhash64AsHex

▸ **xxhash64AsHex**(`data`: Buffer \| Uint8Array \| string, `seed`: number): string

*Defined in [packages/util-crypto/src/xxhash/xxhash64/asHex.ts:22](https://github.com/polkadot-js/common/blob/bd1735ca/packages/util-crypto/src/xxhash/xxhash64/asHex.ts#L22)*

**`name`** xxhash64AsHex

**`summary`** Creates a xxhash hex from the input.

**`description`** 
From either a `string`, `Uint8Array` or a `Buffer` input, create the xxhash and return the result as a hex string.

**`example`** 
<BR>

```javascript
import { xxhash64AsHex } from '@polkadot/util-crypto';

xxhash64AsHex('abcd', 0xabcd)); // => 0xe29f70f8b8c96df7
```

#### Parameters:

Name | Type |
------ | ------ |
`data` | Buffer \| Uint8Array \| string |
`seed` | number |

**Returns:** string
