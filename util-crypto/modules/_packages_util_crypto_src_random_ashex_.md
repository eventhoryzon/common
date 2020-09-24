[Polkadot JS Common](../README.md) › [Globals](../globals.md) › ["packages/util-crypto/src/random/asHex"](_packages_util_crypto_src_random_ashex_.md)

# Module: "packages/util-crypto/src/random/asHex"

## Index

### Functions

* [randomAsHex](_packages_util_crypto_src_random_ashex_.md#randomashex)

## Functions

###  randomAsHex

▸ **randomAsHex**(`length`: number): *string*

*Defined in [packages/util-crypto/src/random/asHex.ts:22](https://github.com/polkadot-js/common/blob/4111122c/packages/util-crypto/src/random/asHex.ts#L22)*

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

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`length` | number | 32 |

**Returns:** *string*
