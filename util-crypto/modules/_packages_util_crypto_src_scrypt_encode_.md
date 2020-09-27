**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/util-crypto/src/scrypt/encode"

# Module: "packages/util-crypto/src/scrypt/encode"

## Index

### Functions

* [scryptEncode](_packages_util_crypto_src_scrypt_encode_.md#scryptencode)

## Functions

### scryptEncode

▸ **scryptEncode**(`passphrase?`: Uint8Array \| string, `salt`: Uint8Array, `params`: { N: number = 1 \<\< 15; p: number = 1; r: number = 8 }): Result

*Defined in [packages/util-crypto/src/scrypt/encode.ts:19](https://github.com/polkadot-js/common/blob/c366e637/packages/util-crypto/src/scrypt/encode.ts#L19)*

#### Parameters:

Name | Type | Default value |
------ | ------ | ------ |
`passphrase?` | Uint8Array \| string | - |
`salt` | Uint8Array | randomAsU8a() |
`params` | { N: number = 1 \<\< 15; p: number = 1; r: number = 8 } | DEFAULT_PARAMS |

**Returns:** Result
