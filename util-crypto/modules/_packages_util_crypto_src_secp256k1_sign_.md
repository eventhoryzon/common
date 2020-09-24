**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/util-crypto/src/secp256k1/sign"

# Module: "packages/util-crypto/src/secp256k1/sign"

## Index

### Functions

* [secp256k1Sign](_packages_util_crypto_src_secp256k1_sign_.md#secp256k1sign)

## Functions

### secp256k1Sign

▸ **secp256k1Sign**(`message`: Uint8Array \| string, `__namedParameters`: { secretKey: undefined \| Uint8Array  }, `hashType`: [HashType](_packages_util_crypto_src_secp256k1_types_.md#hashtype)): Uint8Array

*Defined in [packages/util-crypto/src/secp256k1/sign.ts:19](https://github.com/polkadot-js/common/blob/ce964d2f/packages/util-crypto/src/secp256k1/sign.ts#L19)*

**`name`** secp256k1Sign

**`description`** Returns message signature of `message`, using the supplied pair

#### Parameters:

Name | Type | Default value |
------ | ------ | ------ |
`message` | Uint8Array \| string | - |
`__namedParameters` | { secretKey: undefined \| Uint8Array  } | - |
`hashType` | [HashType](_packages_util_crypto_src_secp256k1_types_.md#hashtype) | "blake2" |

**Returns:** Uint8Array
