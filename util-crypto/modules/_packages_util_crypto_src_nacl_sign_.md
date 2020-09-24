**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/util-crypto/src/nacl/sign"

# Module: "packages/util-crypto/src/nacl/sign"

## Index

### Functions

* [naclSign](_packages_util_crypto_src_nacl_sign_.md#naclsign)

## Functions

### naclSign

▸ **naclSign**(`message`: Uint8Array \| string, `__namedParameters`: { publicKey: undefined \| Uint8Array ; secretKey: undefined \| Uint8Array  }): Uint8Array

*Defined in [packages/util-crypto/src/nacl/sign.ts:24](https://github.com/polkadot-js/common/blob/ce964d2f/packages/util-crypto/src/nacl/sign.ts#L24)*

**`name`** naclSign

**`summary`** Signs a message using the supplied secretKey

**`description`** 
Returns message signature of `message`, using the `secretKey`.

**`example`** 
<BR>

```javascript
import { naclSign } from '@polkadot/util-crypto';

naclSign([...], [...]); // => [...]
```

#### Parameters:

Name | Type |
------ | ------ |
`message` | Uint8Array \| string |
`__namedParameters` | { publicKey: undefined \| Uint8Array ; secretKey: undefined \| Uint8Array  } |

**Returns:** Uint8Array
