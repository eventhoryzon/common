**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/keyring/src/pair/defaults"

# Module: "packages/keyring/src/pair/defaults"

## Index

### Variables

* [ENCODING](_packages_keyring_src_pair_defaults_.md#encoding)
* [NONCE\_LENGTH](_packages_keyring_src_pair_defaults_.md#nonce_length)
* [PKCS8\_DIVIDER](_packages_keyring_src_pair_defaults_.md#pkcs8_divider)
* [PKCS8\_HEADER](_packages_keyring_src_pair_defaults_.md#pkcs8_header)
* [PUB\_LENGTH](_packages_keyring_src_pair_defaults_.md#pub_length)
* [SALT\_LENGTH](_packages_keyring_src_pair_defaults_.md#salt_length)
* [SCRYPT\_LENGTH](_packages_keyring_src_pair_defaults_.md#scrypt_length)
* [SEC\_LENGTH](_packages_keyring_src_pair_defaults_.md#sec_length)
* [SEED\_LENGTH](_packages_keyring_src_pair_defaults_.md#seed_length)

## Variables

### ENCODING

• `Const` **ENCODING**: [KeyringPair$JsonEncodingTypes](_packages_keyring_src_types_.md#keyringpair$jsonencodingtypes)[] = ['scrypt', 'xsalsa20-poly1305']

*Defined in [packages/keyring/src/pair/defaults.ts:6](https://github.com/polkadot-js/common/blob/c366e637/packages/keyring/src/pair/defaults.ts#L6)*

___

### NONCE\_LENGTH

• `Const` **NONCE\_LENGTH**: 24 = 24

*Defined in [packages/keyring/src/pair/defaults.ts:7](https://github.com/polkadot-js/common/blob/c366e637/packages/keyring/src/pair/defaults.ts#L7)*

___

### PKCS8\_DIVIDER

• `Const` **PKCS8\_DIVIDER**: Uint8Array = new Uint8Array([161, 35, 3, 33, 0])

*Defined in [packages/keyring/src/pair/defaults.ts:8](https://github.com/polkadot-js/common/blob/c366e637/packages/keyring/src/pair/defaults.ts#L8)*

___

### PKCS8\_HEADER

• `Const` **PKCS8\_HEADER**: Uint8Array = new Uint8Array([48, 83, 2, 1, 1, 48, 5, 6, 3, 43, 101, 112, 4, 34, 4, 32])

*Defined in [packages/keyring/src/pair/defaults.ts:9](https://github.com/polkadot-js/common/blob/c366e637/packages/keyring/src/pair/defaults.ts#L9)*

___

### PUB\_LENGTH

• `Const` **PUB\_LENGTH**: 32 = 32

*Defined in [packages/keyring/src/pair/defaults.ts:10](https://github.com/polkadot-js/common/blob/c366e637/packages/keyring/src/pair/defaults.ts#L10)*

___

### SALT\_LENGTH

• `Const` **SALT\_LENGTH**: 32 = 32

*Defined in [packages/keyring/src/pair/defaults.ts:11](https://github.com/polkadot-js/common/blob/c366e637/packages/keyring/src/pair/defaults.ts#L11)*

___

### SCRYPT\_LENGTH

• `Const` **SCRYPT\_LENGTH**: number = SALT\_LENGTH + (3 * 4)

*Defined in [packages/keyring/src/pair/defaults.ts:14](https://github.com/polkadot-js/common/blob/c366e637/packages/keyring/src/pair/defaults.ts#L14)*

___

### SEC\_LENGTH

• `Const` **SEC\_LENGTH**: 64 = 64

*Defined in [packages/keyring/src/pair/defaults.ts:12](https://github.com/polkadot-js/common/blob/c366e637/packages/keyring/src/pair/defaults.ts#L12)*

___

### SEED\_LENGTH

• `Const` **SEED\_LENGTH**: 32 = 32

*Defined in [packages/keyring/src/pair/defaults.ts:13](https://github.com/polkadot-js/common/blob/c366e637/packages/keyring/src/pair/defaults.ts#L13)*
