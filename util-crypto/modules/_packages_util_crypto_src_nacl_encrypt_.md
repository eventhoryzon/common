**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/util-crypto/src/nacl/encrypt"

# Module: "packages/util-crypto/src/nacl/encrypt"

## Index

### Functions

* [naclEncrypt](_packages_util_crypto_src_nacl_encrypt_.md#naclencrypt)

## Functions

### naclEncrypt

▸ **naclEncrypt**(`message`: Uint8Array, `secret`: Uint8Array, `nonce`: Uint8Array): Encrypted

*Defined in [packages/util-crypto/src/nacl/encrypt.ts:27](https://github.com/polkadot-js/common/blob/ce964d2f/packages/util-crypto/src/nacl/encrypt.ts#L27)*

**`name`** naclEncrypt

**`summary`** Encrypts a message using the supplied secretKey and nonce

**`description`** 
Returns an encrypted message, using the `secretKey` and `nonce`. If the `nonce` was not supplied, a random value is generated.

**`example`** 
<BR>

```javascript
import { naclEncrypt } from '@polkadot/util-crypto';

naclEncrypt([...], [...]); // => [...]
```

#### Parameters:

Name | Type | Default value |
------ | ------ | ------ |
`message` | Uint8Array | - |
`secret` | Uint8Array | - |
`nonce` | Uint8Array | randomAsU8a(24) |

**Returns:** Encrypted
