**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/util-crypto/src/nacl/keypair/fromSecret"

# Module: "packages/util-crypto/src/nacl/keypair/fromSecret"

## Index

### Functions

* [naclKeypairFromSecret](_packages_util_crypto_src_nacl_keypair_fromsecret_.md#naclkeypairfromsecret)

## Functions

### naclKeypairFromSecret

▸ **naclKeypairFromSecret**(`secret`: Uint8Array): [Keypair](../interfaces/_packages_util_crypto_src_types_.keypair.md)

*Defined in [packages/util-crypto/src/nacl/keypair/fromSecret.ts:22](https://github.com/polkadot-js/common/blob/c366e637/packages/util-crypto/src/nacl/keypair/fromSecret.ts#L22)*

**`name`** naclKeypairFromSecret

**`summary`** Creates a new public/secret keypair from a secret.

**`description`** 
Returns a object containing a `publicKey` & `secretKey` generated from the supplied secret.

**`example`** 
<BR>

```javascript
import { naclKeypairFromSecret } from '@polkadot/util-crypto';

naclKeypairFromSecret(...); // => { secretKey: [...], publicKey: [...] }
```

#### Parameters:

Name | Type |
------ | ------ |
`secret` | Uint8Array |

**Returns:** [Keypair](../interfaces/_packages_util_crypto_src_types_.keypair.md)
