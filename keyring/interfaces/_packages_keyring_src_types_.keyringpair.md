**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / ["packages/keyring/src/types"](../modules/_packages_keyring_src_types_.md) / KeyringPair

# Interface: KeyringPair

## Hierarchy

* **KeyringPair**

## Index

### Properties

* [address](_packages_keyring_src_types_.keyringpair.md#address)
* [addressRaw](_packages_keyring_src_types_.keyringpair.md#addressraw)
* [decodePkcs8](_packages_keyring_src_types_.keyringpair.md#decodepkcs8)
* [derive](_packages_keyring_src_types_.keyringpair.md#derive)
* [encodePkcs8](_packages_keyring_src_types_.keyringpair.md#encodepkcs8)
* [isLocked](_packages_keyring_src_types_.keyringpair.md#islocked)
* [lock](_packages_keyring_src_types_.keyringpair.md#lock)
* [meta](_packages_keyring_src_types_.keyringpair.md#meta)
* [publicKey](_packages_keyring_src_types_.keyringpair.md#publickey)
* [setMeta](_packages_keyring_src_types_.keyringpair.md#setmeta)
* [type](_packages_keyring_src_types_.keyringpair.md#type)

### Methods

* [sign](_packages_keyring_src_types_.keyringpair.md#sign)
* [toJson](_packages_keyring_src_types_.keyringpair.md#tojson)
* [verify](_packages_keyring_src_types_.keyringpair.md#verify)

## Properties

### address

• `Readonly` **address**: string

*Defined in [packages/keyring/src/types.ts:36](https://github.com/polkadot-js/common/blob/dd1220ac/packages/keyring/src/types.ts#L36)*

___

### addressRaw

• `Readonly` **addressRaw**: Uint8Array

*Defined in [packages/keyring/src/types.ts:37](https://github.com/polkadot-js/common/blob/dd1220ac/packages/keyring/src/types.ts#L37)*

___

### decodePkcs8

•  **decodePkcs8**: (passphrase?: undefined \| string,encoded?: Uint8Array) => void

*Defined in [packages/keyring/src/types.ts:43](https://github.com/polkadot-js/common/blob/dd1220ac/packages/keyring/src/types.ts#L43)*

___

### derive

•  **derive**: (suri: string,meta?: [KeyringPair$Meta](../modules/_packages_keyring_src_types_.md#keyringpair$meta)) => [KeyringPair](_packages_keyring_src_types_.keyringpair.md)

*Defined in [packages/keyring/src/types.ts:44](https://github.com/polkadot-js/common/blob/dd1220ac/packages/keyring/src/types.ts#L44)*

___

### encodePkcs8

•  **encodePkcs8**: (passphrase?: undefined \| string) => Uint8Array

*Defined in [packages/keyring/src/types.ts:45](https://github.com/polkadot-js/common/blob/dd1220ac/packages/keyring/src/types.ts#L45)*

___

### isLocked

• `Readonly` **isLocked**: boolean

*Defined in [packages/keyring/src/types.ts:39](https://github.com/polkadot-js/common/blob/dd1220ac/packages/keyring/src/types.ts#L39)*

___

### lock

•  **lock**: () => void

*Defined in [packages/keyring/src/types.ts:46](https://github.com/polkadot-js/common/blob/dd1220ac/packages/keyring/src/types.ts#L46)*

___

### meta

• `Readonly` **meta**: [KeyringPair$Meta](../modules/_packages_keyring_src_types_.md#keyringpair$meta)

*Defined in [packages/keyring/src/types.ts:38](https://github.com/polkadot-js/common/blob/dd1220ac/packages/keyring/src/types.ts#L38)*

___

### publicKey

• `Readonly` **publicKey**: Uint8Array

*Defined in [packages/keyring/src/types.ts:40](https://github.com/polkadot-js/common/blob/dd1220ac/packages/keyring/src/types.ts#L40)*

___

### setMeta

•  **setMeta**: (meta: [KeyringPair$Meta](../modules/_packages_keyring_src_types_.md#keyringpair$meta)) => void

*Defined in [packages/keyring/src/types.ts:47](https://github.com/polkadot-js/common/blob/dd1220ac/packages/keyring/src/types.ts#L47)*

___

### type

• `Readonly` **type**: KeypairType

*Defined in [packages/keyring/src/types.ts:41](https://github.com/polkadot-js/common/blob/dd1220ac/packages/keyring/src/types.ts#L41)*

## Methods

### sign

▸ **sign**(`message`: Uint8Array, `options?`: [SignOptions](_packages_keyring_src_types_.signoptions.md)): Uint8Array

*Defined in [packages/keyring/src/types.ts:48](https://github.com/polkadot-js/common/blob/dd1220ac/packages/keyring/src/types.ts#L48)*

#### Parameters:

Name | Type |
------ | ------ |
`message` | Uint8Array |
`options?` | [SignOptions](_packages_keyring_src_types_.signoptions.md) |

**Returns:** Uint8Array

___

### toJson

▸ **toJson**(`passphrase?`: undefined \| string): [KeyringPair$Json](_packages_keyring_src_types_.keyringpair_json.md)

*Defined in [packages/keyring/src/types.ts:49](https://github.com/polkadot-js/common/blob/dd1220ac/packages/keyring/src/types.ts#L49)*

#### Parameters:

Name | Type |
------ | ------ |
`passphrase?` | undefined \| string |

**Returns:** [KeyringPair$Json](_packages_keyring_src_types_.keyringpair_json.md)

___

### verify

▸ **verify**(`message`: Uint8Array, `signature`: Uint8Array): boolean

*Defined in [packages/keyring/src/types.ts:50](https://github.com/polkadot-js/common/blob/dd1220ac/packages/keyring/src/types.ts#L50)*

#### Parameters:

Name | Type |
------ | ------ |
`message` | Uint8Array |
`signature` | Uint8Array |

**Returns:** boolean
