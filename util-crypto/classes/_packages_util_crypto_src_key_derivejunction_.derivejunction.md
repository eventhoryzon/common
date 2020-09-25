**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / ["packages/util-crypto/src/key/DeriveJunction"](../modules/_packages_util_crypto_src_key_derivejunction_.md) / DeriveJunction

# Class: DeriveJunction

## Hierarchy

* **DeriveJunction**

## Index

### Accessors

* [chainCode](_packages_util_crypto_src_key_derivejunction_.derivejunction.md#chaincode)
* [isHard](_packages_util_crypto_src_key_derivejunction_.derivejunction.md#ishard)
* [isSoft](_packages_util_crypto_src_key_derivejunction_.derivejunction.md#issoft)

### Methods

* [hard](_packages_util_crypto_src_key_derivejunction_.derivejunction.md#hard)
* [harden](_packages_util_crypto_src_key_derivejunction_.derivejunction.md#harden)
* [soft](_packages_util_crypto_src_key_derivejunction_.derivejunction.md#soft)
* [soften](_packages_util_crypto_src_key_derivejunction_.derivejunction.md#soften)
* [from](_packages_util_crypto_src_key_derivejunction_.derivejunction.md#from)

## Accessors

### chainCode

• get **chainCode**(): Uint8Array

*Defined in [packages/util-crypto/src/key/DeriveJunction.ts:40](https://github.com/polkadot-js/common/blob/bd1735ca/packages/util-crypto/src/key/DeriveJunction.ts#L40)*

**Returns:** Uint8Array

___

### isHard

• get **isHard**(): boolean

*Defined in [packages/util-crypto/src/key/DeriveJunction.ts:44](https://github.com/polkadot-js/common/blob/bd1735ca/packages/util-crypto/src/key/DeriveJunction.ts#L44)*

**Returns:** boolean

___

### isSoft

• get **isSoft**(): boolean

*Defined in [packages/util-crypto/src/key/DeriveJunction.ts:48](https://github.com/polkadot-js/common/blob/bd1735ca/packages/util-crypto/src/key/DeriveJunction.ts#L48)*

**Returns:** boolean

## Methods

### hard

▸ **hard**(`value`: number \| string \| BigInt \| BN \| Uint8Array): [DeriveJunction](_packages_util_crypto_src_key_derivejunction_.derivejunction.md)

*Defined in [packages/util-crypto/src/key/DeriveJunction.ts:52](https://github.com/polkadot-js/common/blob/bd1735ca/packages/util-crypto/src/key/DeriveJunction.ts#L52)*

#### Parameters:

Name | Type |
------ | ------ |
`value` | number \| string \| BigInt \| BN \| Uint8Array |

**Returns:** [DeriveJunction](_packages_util_crypto_src_key_derivejunction_.derivejunction.md)

___

### harden

▸ **harden**(): [DeriveJunction](_packages_util_crypto_src_key_derivejunction_.derivejunction.md)

*Defined in [packages/util-crypto/src/key/DeriveJunction.ts:56](https://github.com/polkadot-js/common/blob/bd1735ca/packages/util-crypto/src/key/DeriveJunction.ts#L56)*

**Returns:** [DeriveJunction](_packages_util_crypto_src_key_derivejunction_.derivejunction.md)

___

### soft

▸ **soft**(`value`: number \| string \| BigInt \| BN \| Uint8Array): [DeriveJunction](_packages_util_crypto_src_key_derivejunction_.derivejunction.md)

*Defined in [packages/util-crypto/src/key/DeriveJunction.ts:62](https://github.com/polkadot-js/common/blob/bd1735ca/packages/util-crypto/src/key/DeriveJunction.ts#L62)*

#### Parameters:

Name | Type |
------ | ------ |
`value` | number \| string \| BigInt \| BN \| Uint8Array |

**Returns:** [DeriveJunction](_packages_util_crypto_src_key_derivejunction_.derivejunction.md)

___

### soften

▸ **soften**(): [DeriveJunction](_packages_util_crypto_src_key_derivejunction_.derivejunction.md)

*Defined in [packages/util-crypto/src/key/DeriveJunction.ts:81](https://github.com/polkadot-js/common/blob/bd1735ca/packages/util-crypto/src/key/DeriveJunction.ts#L81)*

**Returns:** [DeriveJunction](_packages_util_crypto_src_key_derivejunction_.derivejunction.md)

___

### from

▸ `Static`**from**(`value`: string): [DeriveJunction](_packages_util_crypto_src_key_derivejunction_.derivejunction.md)

*Defined in [packages/util-crypto/src/key/DeriveJunction.ts:23](https://github.com/polkadot-js/common/blob/bd1735ca/packages/util-crypto/src/key/DeriveJunction.ts#L23)*

#### Parameters:

Name | Type |
------ | ------ |
`value` | string |

**Returns:** [DeriveJunction](_packages_util_crypto_src_key_derivejunction_.derivejunction.md)
