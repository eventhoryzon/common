**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/util-crypto/src/base58/validate"

# Module: "packages/util-crypto/src/base58/validate"

## Index

### Functions

* [base58Validate](_packages_util_crypto_src_base58_validate_.md#base58validate)
* [validateChars](_packages_util_crypto_src_base58_validate_.md#validatechars)

## Functions

### base58Validate

▸ **base58Validate**(`value?`: string \| null, `ipfsCompat`: boolean): true

*Defined in [packages/util-crypto/src/base58/validate.ts:25](https://github.com/polkadot-js/common/blob/c366e637/packages/util-crypto/src/base58/validate.ts#L25)*

**`name`** base58Validate

**`summary`** Validates a base58 value.

**`description`** 
Validates the the supplied value is valid base58

#### Parameters:

Name | Type | Default value |
------ | ------ | ------ |
`value?` | string \| null | - |
`ipfsCompat` | boolean | false |

**Returns:** true

___

### validateChars

▸ **validateChars**(`type`: string, `alphabet`: string, `value?`: string \| null, `startChar?`: undefined \| string): true

*Defined in [packages/util-crypto/src/base58/validate.ts:8](https://github.com/polkadot-js/common/blob/c366e637/packages/util-crypto/src/base58/validate.ts#L8)*

#### Parameters:

Name | Type |
------ | ------ |
`type` | string |
`alphabet` | string |
`value?` | string \| null |
`startChar?` | undefined \| string |

**Returns:** true
