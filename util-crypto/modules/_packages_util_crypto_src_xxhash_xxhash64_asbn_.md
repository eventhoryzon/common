**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/util-crypto/src/xxhash/xxhash64/asBn"

# Module: "packages/util-crypto/src/xxhash/xxhash64/asBn"

## Index

### Functions

* [xxhash64AsBn](_packages_util_crypto_src_xxhash_xxhash64_asbn_.md#xxhash64asbn)

## Functions

### xxhash64AsBn

▸ **xxhash64AsBn**(`data`: Buffer \| Uint8Array \| string, `seed`: number): BN

*Defined in [packages/util-crypto/src/xxhash/xxhash64/asBn.ts:22](https://github.com/polkadot-js/common/blob/bd1735ca/packages/util-crypto/src/xxhash/xxhash64/asBn.ts#L22)*

**`name`** xxhash64AsBn

**`summary`** Creates a xxhash BN from the input.

**`description`** 
From either a `string`, `Uint8Array` or a `Buffer` input, create the xxhash and return the result as a BN.

**`example`** 
<BR>

```javascript
import { xxhash64AsNumber } from '@polkadot/util-crypto';

xxhash64AsBn('abcd', 0xabcd)); // => new BN(0xe29f70f8b8c96df7)
```

#### Parameters:

Name | Type |
------ | ------ |
`data` | Buffer \| Uint8Array \| string |
`seed` | number |

**Returns:** BN
