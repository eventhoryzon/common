**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/util-crypto/src/address/encodeMulti"

# Module: "packages/util-crypto/src/address/encodeMulti"

## Index

### Functions

* [encodeMultiAddress](_packages_util_crypto_src_address_encodemulti_.md#encodemultiaddress)

## Functions

### encodeMultiAddress

▸ **encodeMultiAddress**(`who`: (Uint8Array \| string)[], `threshold`: BigInt \| BN \| number, `ss58Format?`: [Prefix](_packages_util_crypto_src_address_types_.md#prefix)): string

*Defined in [packages/util-crypto/src/address/encodeMulti.ts:17](https://github.com/polkadot-js/common/blob/ce964d2f/packages/util-crypto/src/address/encodeMulti.ts#L17)*

**`name`** encodeMultiAddress

**`summary`** Creates a multisig address.

**`description`** 
Creates a Substrate multisig address based on the input address and the required threshold.

#### Parameters:

Name | Type |
------ | ------ |
`who` | (Uint8Array \| string)[] |
`threshold` | BigInt \| BN \| number |
`ss58Format?` | [Prefix](_packages_util_crypto_src_address_types_.md#prefix) |

**Returns:** string
