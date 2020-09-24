**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/util-crypto/src/address/encodeDerived"

# Module: "packages/util-crypto/src/address/encodeDerived"

## Index

### Functions

* [encodeDerivedAddress](_packages_util_crypto_src_address_encodederived_.md#encodederivedaddress)

## Functions

### encodeDerivedAddress

▸ **encodeDerivedAddress**(`who`: Uint8Array \| string, `index`: BigInt \| BN \| number, `ss58Format?`: [Prefix](_packages_util_crypto_src_address_types_.md#prefix)): string

*Defined in [packages/util-crypto/src/address/encodeDerived.ts:18](https://github.com/polkadot-js/common/blob/aff78c2e/packages/util-crypto/src/address/encodeDerived.ts#L18)*

**`name`** encodeDerivedAddress

**`summary`** Creates a derived address as used in Substrate utility.

**`description`** 
Creates a Substrate derived address based on the input address/publicKey and the index supplied.

#### Parameters:

Name | Type |
------ | ------ |
`who` | Uint8Array \| string |
`index` | BigInt \| BN \| number |
`ss58Format?` | [Prefix](_packages_util_crypto_src_address_types_.md#prefix) |

**Returns:** string
