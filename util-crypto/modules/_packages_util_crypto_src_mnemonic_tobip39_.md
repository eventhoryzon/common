**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/util-crypto/src/mnemonic/toBip39"

# Module: "packages/util-crypto/src/mnemonic/toBip39"

## Index

### Functions

* [toBip39](_packages_util_crypto_src_mnemonic_tobip39_.md#tobip39)

## Functions

### toBip39

▸ **toBip39**(`mnemonic`: string, `password`: string): Uint8Array

*Defined in [packages/util-crypto/src/mnemonic/toBip39.ts:26](https://github.com/polkadot-js/common/blob/bd1735ca/packages/util-crypto/src/mnemonic/toBip39.ts#L26)*

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
