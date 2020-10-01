**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/util-crypto/src/mnemonic/toLegacySeed"

# Module: "packages/util-crypto/src/mnemonic/toLegacySeed"

## Index

### Functions

* [toLegacy](_packages_util_crypto_src_mnemonic_tolegacyseed_.md#tolegacy)

## Functions

### toLegacy

▸ **toLegacy**(`mnemonic`: string, `password`: string): Uint8Array

*Defined in [packages/util-crypto/src/mnemonic/toLegacySeed.ts:26](https://github.com/polkadot-js/common/blob/dd1220ac/packages/util-crypto/src/mnemonic/toLegacySeed.ts#L26)*

**`name`** toSeed

**`summary`** Creates a valid Ethereum/Bitcoin-compatible seed from a mnemonic input

**`example`** 
<BR>

```javascript
import { mnemonicGenerate, mnemonicToBip39, mnemonicValidate } from '@polkadot/util-crypto';

const mnemonic = mnemonicGenerate(); // => string
const isValidMnemonic = mnemonicValidate(mnemonic); // => boolean

if (isValidMnemonic) {
  console.log(`Seed generated from mnemonic: ${mnemonicToBip39(mnemonic)}`); => u8a
}
```

#### Parameters:

Name | Type | Default value |
------ | ------ | ------ |
`mnemonic` | string | - |
`password` | string | "" |

**Returns:** Uint8Array
