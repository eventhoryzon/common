**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/util-crypto/src/random/asHex"

# Module: "packages/util-crypto/src/random/asHex"

## Index

### Functions

* [randomAsHex](_packages_util_crypto_src_random_ashex_.md#randomashex)

## Functions

### randomAsHex

▸ **randomAsHex**(`length`: number): string

*Defined in [packages/util-crypto/src/random/asHex.ts:22](https://github.com/polkadot-js/common/blob/c366e637/packages/util-crypto/src/random/asHex.ts#L22)*

**`name`** randomAsHex

**`summary`** Creates a hex string filled with random bytes.

**`description`** 
Returns a hex string with the specified (optional) length filled with random bytes.

**`example`** 
<BR>

```javascript
import { randomAsHex } from '@polkadot/util-crypto';

randomAsHex(); // => 0x...
```

#### Parameters:

Name | Type | Default value |
------ | ------ | ------ |
`length` | number | 32 |

**Returns:** string
