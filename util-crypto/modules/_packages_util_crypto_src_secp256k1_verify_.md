**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/util-crypto/src/secp256k1/verify"

# Module: "packages/util-crypto/src/secp256k1/verify"

## Index

### Functions

* [secp256k1Verify](_packages_util_crypto_src_secp256k1_verify_.md#secp256k1verify)

## Functions

### secp256k1Verify

▸ **secp256k1Verify**(`message`: Uint8Array \| string, `signature`: Uint8Array \| string, `address`: Uint8Array \| string, `hashType`: [HashType](_packages_util_crypto_src_secp256k1_types_.md#hashtype), `isExpanded`: boolean): boolean

*Defined in [packages/util-crypto/src/secp256k1/verify.ts:19](https://github.com/polkadot-js/common/blob/aff78c2e/packages/util-crypto/src/secp256k1/verify.ts#L19)*

**`name`** secp256k1Verify

**`description`** Verifies the signature of `message`, using the supplied pair

#### Parameters:

Name | Type | Default value |
------ | ------ | ------ |
`message` | Uint8Array \| string | - |
`signature` | Uint8Array \| string | - |
`address` | Uint8Array \| string | - |
`hashType` | [HashType](_packages_util_crypto_src_secp256k1_types_.md#hashtype) | "blake2" |
`isExpanded` | boolean | false |

**Returns:** boolean
