**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / ["packages/keyring/src/keyring"](../modules/_packages_keyring_src_keyring_.md) / Keyring

# Class: Keyring

# @polkadot/keyring

## Overview

**`name`** Keyring

**`summary`** Keyring management of user accounts

**`description`** Allows generation of keyring pairs from a variety of input combinations, such as
json object containing account address or public key, account metadata, and account encoded using
`addFromJson`, or by providing those values as arguments separately to `addFromAddress`,
or by providing the mnemonic (seed phrase) and account metadata as arguments to `addFromMnemonic`.
Stores the keyring pairs in a keyring pair dictionary. Removal of the keyring pairs from the keyring pair
dictionary is achieved using `removePair`. Retrieval of all the stored pairs via `getPairs` or perform
lookup of a pair for a given account address or public key using `getPair`. JSON metadata associated with
an account may be obtained using `toJson` accompanied by the account passphrase.

## Hierarchy

* **Keyring**

## Implements

* [KeyringInstance](../interfaces/_packages_keyring_src_types_.keyringinstance.md)

## Index

### Constructors

* [constructor](_packages_keyring_src_keyring_.keyring.md#constructor)

### Properties

* [decodeAddress](_packages_keyring_src_keyring_.keyring.md#decodeaddress)

### Accessors

* [pairs](_packages_keyring_src_keyring_.keyring.md#pairs)
* [publicKeys](_packages_keyring_src_keyring_.keyring.md#publickeys)
* [type](_packages_keyring_src_keyring_.keyring.md#type)

### Methods

* [addFromAddress](_packages_keyring_src_keyring_.keyring.md#addfromaddress)
* [addFromJson](_packages_keyring_src_keyring_.keyring.md#addfromjson)
* [addFromMnemonic](_packages_keyring_src_keyring_.keyring.md#addfrommnemonic)
* [addFromSeed](_packages_keyring_src_keyring_.keyring.md#addfromseed)
* [addFromUri](_packages_keyring_src_keyring_.keyring.md#addfromuri)
* [addPair](_packages_keyring_src_keyring_.keyring.md#addpair)
* [createFromJson](_packages_keyring_src_keyring_.keyring.md#createfromjson)
* [createFromUri](_packages_keyring_src_keyring_.keyring.md#createfromuri)
* [encodeAddress](_packages_keyring_src_keyring_.keyring.md#encodeaddress)
* [getPair](_packages_keyring_src_keyring_.keyring.md#getpair)
* [getPairs](_packages_keyring_src_keyring_.keyring.md#getpairs)
* [getPublicKeys](_packages_keyring_src_keyring_.keyring.md#getpublickeys)
* [removePair](_packages_keyring_src_keyring_.keyring.md#removepair)
* [setSS58Format](_packages_keyring_src_keyring_.keyring.md#setss58format)
* [toJson](_packages_keyring_src_keyring_.keyring.md#tojson)

## Constructors

### constructor

\+ **new Keyring**(`options`: [KeyringOptions](../interfaces/_packages_keyring_src_types_.keyringoptions.md)): [Keyring](_packages_keyring_src_keyring_.keyring.md)

*Defined in [packages/keyring/src/keyring.ts:44](https://github.com/polkadot-js/common/blob/975103fd/packages/keyring/src/keyring.ts#L44)*

#### Parameters:

Name | Type | Default value |
------ | ------ | ------ |
`options` | [KeyringOptions](../interfaces/_packages_keyring_src_types_.keyringoptions.md) | {} |

**Returns:** [Keyring](_packages_keyring_src_keyring_.keyring.md)

## Properties

### decodeAddress

•  **decodeAddress**: decode = decodeAddress

*Implementation of [KeyringInstance](../interfaces/_packages_keyring_src_types_.keyringinstance.md).[decodeAddress](../interfaces/_packages_keyring_src_types_.keyringinstance.md#decodeaddress)*

*Defined in [packages/keyring/src/keyring.ts:44](https://github.com/polkadot-js/common/blob/975103fd/packages/keyring/src/keyring.ts#L44)*

## Accessors

### pairs

• get **pairs**(): [KeyringPair](../interfaces/_packages_keyring_src_types_.keyringpair.md)[]

*Defined in [packages/keyring/src/keyring.ts:59](https://github.com/polkadot-js/common/blob/975103fd/packages/keyring/src/keyring.ts#L59)*

**`description`** retrieve the pairs (alias for getPairs)

**Returns:** [KeyringPair](../interfaces/_packages_keyring_src_types_.keyringpair.md)[]

___

### publicKeys

• get **publicKeys**(): Uint8Array[]

*Defined in [packages/keyring/src/keyring.ts:66](https://github.com/polkadot-js/common/blob/975103fd/packages/keyring/src/keyring.ts#L66)*

**`description`** retrieve the publicKeys (alias for getPublicKeys)

**Returns:** Uint8Array[]

___

### type

• get **type**(): KeypairType

*Defined in [packages/keyring/src/keyring.ts:73](https://github.com/polkadot-js/common/blob/975103fd/packages/keyring/src/keyring.ts#L73)*

**`description`** Returns the type of the keyring, ed25519, sr25519 or ecdsa

**Returns:** KeypairType

## Methods

### addFromAddress

▸ **addFromAddress**(`address`: string \| Uint8Array, `meta`: [KeyringPair$Meta](../modules/_packages_keyring_src_types_.md#keyringpair$meta), `encoded`: Uint8Array \| null, `type`: KeypairType, `ignoreChecksum?`: undefined \| false \| true, `encType?`: [KeyringPair$JsonEncodingTypes](../modules/_packages_keyring_src_types_.md#keyringpair$jsonencodingtypes)[]): [KeyringPair](../interfaces/_packages_keyring_src_types_.keyringpair.md)

*Defined in [packages/keyring/src/keyring.ts:93](https://github.com/polkadot-js/common/blob/975103fd/packages/keyring/src/keyring.ts#L93)*

**`name`** addFromAddress

**`summary`** Stores an account, given an account address, as a Key/Value (public key, pair) in Keyring Pair Dictionary

**`description`** Allows user to explicitely provide separate inputs including account address or public key, and optionally
the associated account metadata, and the default encoded value as arguments (that may be obtained from the json file
of an account backup), and then generates a keyring pair from them that it passes to
`addPair` to stores in a keyring pair dictionary the public key of the generated pair as a key and the pair as the associated value.

#### Parameters:

Name | Type | Default value |
------ | ------ | ------ |
`address` | string \| Uint8Array | - |
`meta` | [KeyringPair$Meta](../modules/_packages_keyring_src_types_.md#keyringpair$meta) | {} |
`encoded` | Uint8Array \| null | null |
`type` | KeypairType | this.type |
`ignoreChecksum?` | undefined \| false \| true | - |
`encType?` | [KeyringPair$JsonEncodingTypes](../modules/_packages_keyring_src_types_.md#keyringpair$jsonencodingtypes)[] | - |

**Returns:** [KeyringPair](../interfaces/_packages_keyring_src_types_.keyringpair.md)

___

### addFromJson

▸ **addFromJson**(`json`: [KeyringPair$Json](../interfaces/_packages_keyring_src_types_.keyringpair_json.md), `ignoreChecksum?`: undefined \| false \| true): [KeyringPair](../interfaces/_packages_keyring_src_types_.keyringpair.md)

*Implementation of [KeyringInstance](../interfaces/_packages_keyring_src_types_.keyringinstance.md)*

*Defined in [packages/keyring/src/keyring.ts:106](https://github.com/polkadot-js/common/blob/975103fd/packages/keyring/src/keyring.ts#L106)*

**`name`** addFromJson

**`summary`** Stores an account, given JSON data, as a Key/Value (public key, pair) in Keyring Pair Dictionary

**`description`** Allows user to provide a json object argument that contains account information (that may be obtained from the json file
of an account backup), and then generates a keyring pair from it that it passes to
`addPair` to stores in a keyring pair dictionary the public key of the generated pair as a key and the pair as the associated value.

#### Parameters:

Name | Type |
------ | ------ |
`json` | [KeyringPair$Json](../interfaces/_packages_keyring_src_types_.keyringpair_json.md) |
`ignoreChecksum?` | undefined \| false \| true |

**Returns:** [KeyringPair](../interfaces/_packages_keyring_src_types_.keyringpair.md)

___

### addFromMnemonic

▸ **addFromMnemonic**(`mnemonic`: string, `meta`: [KeyringPair$Meta](../modules/_packages_keyring_src_types_.md#keyringpair$meta), `type`: KeypairType): [KeyringPair](../interfaces/_packages_keyring_src_types_.keyringpair.md)

*Implementation of [KeyringInstance](../interfaces/_packages_keyring_src_types_.keyringinstance.md)*

*Defined in [packages/keyring/src/keyring.ts:118](https://github.com/polkadot-js/common/blob/975103fd/packages/keyring/src/keyring.ts#L118)*

**`name`** addFromMnemonic

**`summary`** Stores an account, given a mnemonic, as a Key/Value (public key, pair) in Keyring Pair Dictionary

**`description`** Allows user to provide a mnemonic (seed phrase that is provided when account is originally created)
argument and a metadata argument that contains account information (that may be obtained from the json file
of an account backup), and then generates a keyring pair from it that it passes to
`addPair` to stores in a keyring pair dictionary the public key of the generated pair as a key and the pair as the associated value.

#### Parameters:

Name | Type | Default value |
------ | ------ | ------ |
`mnemonic` | string | - |
`meta` | [KeyringPair$Meta](../modules/_packages_keyring_src_types_.md#keyringpair$meta) | {} |
`type` | KeypairType | this.type |

**Returns:** [KeyringPair](../interfaces/_packages_keyring_src_types_.keyringpair.md)

___

### addFromSeed

▸ **addFromSeed**(`seed`: Uint8Array, `meta`: [KeyringPair$Meta](../modules/_packages_keyring_src_types_.md#keyringpair$meta), `type`: KeypairType): [KeyringPair](../interfaces/_packages_keyring_src_types_.keyringpair.md)

*Implementation of [KeyringInstance](../interfaces/_packages_keyring_src_types_.keyringinstance.md)*

*Defined in [packages/keyring/src/keyring.ts:129](https://github.com/polkadot-js/common/blob/975103fd/packages/keyring/src/keyring.ts#L129)*

**`name`** addFromSeed

**`summary`** Stores an account, given seed data, as a Key/Value (public key, pair) in Keyring Pair Dictionary

**`description`** Stores in a keyring pair dictionary the public key of the pair as a key and the pair as the associated value.
Allows user to provide the account seed as an argument, and then generates a keyring pair from it that it passes to
`addPair` to store in a keyring pair dictionary the public key of the generated pair as a key and the pair as the associated value.

#### Parameters:

Name | Type | Default value |
------ | ------ | ------ |
`seed` | Uint8Array | - |
`meta` | [KeyringPair$Meta](../modules/_packages_keyring_src_types_.md#keyringpair$meta) | {} |
`type` | KeypairType | this.type |

**Returns:** [KeyringPair](../interfaces/_packages_keyring_src_types_.keyringpair.md)

___

### addFromUri

▸ **addFromUri**(`suri`: string, `meta`: [KeyringPair$Meta](../modules/_packages_keyring_src_types_.md#keyringpair$meta), `type`: KeypairType): [KeyringPair](../interfaces/_packages_keyring_src_types_.keyringpair.md)

*Implementation of [KeyringInstance](../interfaces/_packages_keyring_src_types_.keyringinstance.md)*

*Defined in [packages/keyring/src/keyring.ts:138](https://github.com/polkadot-js/common/blob/975103fd/packages/keyring/src/keyring.ts#L138)*

**`name`** addFromUri

**`summary`** Creates an account via an suri

**`description`** Extracts the phrase, path and password from a SURI format for specifying secret keys `<secret>/<soft-key>//<hard-key>///<password>` (the `///password` may be omitted, and `/<soft-key>` and `//<hard-key>` maybe repeated and mixed). The secret can be a hex string, mnemonic phrase or a string (to be padded)

#### Parameters:

Name | Type | Default value |
------ | ------ | ------ |
`suri` | string | - |
`meta` | [KeyringPair$Meta](../modules/_packages_keyring_src_types_.md#keyringpair$meta) | {} |
`type` | KeypairType | this.type |

**Returns:** [KeyringPair](../interfaces/_packages_keyring_src_types_.keyringpair.md)

___

### addPair

▸ **addPair**(`pair`: [KeyringPair](../interfaces/_packages_keyring_src_types_.keyringpair.md)): [KeyringPair](../interfaces/_packages_keyring_src_types_.keyringpair.md)

*Implementation of [KeyringInstance](../interfaces/_packages_keyring_src_types_.keyringinstance.md)*

*Defined in [packages/keyring/src/keyring.ts:81](https://github.com/polkadot-js/common/blob/975103fd/packages/keyring/src/keyring.ts#L81)*

**`name`** addPair

**`summary`** Stores an account, given a keyring pair, as a Key/Value (public key, pair) in Keyring Pair Dictionary

#### Parameters:

Name | Type |
------ | ------ |
`pair` | [KeyringPair](../interfaces/_packages_keyring_src_types_.keyringpair.md) |

**Returns:** [KeyringPair](../interfaces/_packages_keyring_src_types_.keyringpair.md)

___

### createFromJson

▸ **createFromJson**(`__namedParameters`: { address: string ; encoded: string ; encoding: { content: [\"pkcs8\", KeypairType] ; type: \"none\" \| \"scrypt\" \| \"xsalsa20-poly1305\" \| [KeyringPair$JsonEncodingTypes](../modules/_packages_keyring_src_types_.md#keyringpair$jsonencodingtypes)[] ; version: [KeyringPair$JsonVersion](../modules/_packages_keyring_src_types_.md#keyringpair$jsonversion)  } ; meta: Record\<string, unknown>  }, `ignoreChecksum?`: undefined \| false \| true): [KeyringPair](../interfaces/_packages_keyring_src_types_.keyringpair.md)

*Defined in [packages/keyring/src/keyring.ts:148](https://github.com/polkadot-js/common/blob/975103fd/packages/keyring/src/keyring.ts#L148)*

**`name`** createFromJson

**`description`** Creates a pair from a JSON keyfile

#### Parameters:

Name | Type |
------ | ------ |
`__namedParameters` | { address: string ; encoded: string ; encoding: { content: [\"pkcs8\", KeypairType] ; type: \"none\" \| \"scrypt\" \| \"xsalsa20-poly1305\" \| [KeyringPair$JsonEncodingTypes](../modules/_packages_keyring_src_types_.md#keyringpair$jsonencodingtypes)[] ; version: [KeyringPair$JsonVersion](../modules/_packages_keyring_src_types_.md#keyringpair$jsonversion)  } ; meta: Record\<string, unknown>  } |
`ignoreChecksum?` | undefined \| false \| true |

**Returns:** [KeyringPair](../interfaces/_packages_keyring_src_types_.keyringpair.md)

___

### createFromUri

▸ **createFromUri**(`_suri`: string, `meta`: [KeyringPair$Meta](../modules/_packages_keyring_src_types_.md#keyringpair$meta), `type`: KeypairType): [KeyringPair](../interfaces/_packages_keyring_src_types_.keyringpair.md)

*Implementation of [KeyringInstance](../interfaces/_packages_keyring_src_types_.keyringinstance.md)*

*Defined in [packages/keyring/src/keyring.ts:170](https://github.com/polkadot-js/common/blob/975103fd/packages/keyring/src/keyring.ts#L170)*

**`name`** createFromUri

**`summary`** Creates a Keypair from an suri

**`description`** This creates a pair from the suri, but does not add it to the keyring

#### Parameters:

Name | Type | Default value |
------ | ------ | ------ |
`_suri` | string | - |
`meta` | [KeyringPair$Meta](../modules/_packages_keyring_src_types_.md#keyringpair$meta) | {} |
`type` | KeypairType | this.type |

**Returns:** [KeyringPair](../interfaces/_packages_keyring_src_types_.keyringpair.md)

___

### encodeAddress

▸ **encodeAddress**(`address`: Uint8Array \| string, `ss58Format?`: undefined \| number): string

*Defined in [packages/keyring/src/keyring.ts:205](https://github.com/polkadot-js/common/blob/975103fd/packages/keyring/src/keyring.ts#L205)*

**`name`** encodeAddress

**`description`** Encodes the input into an ss58 representation

#### Parameters:

Name | Type |
------ | ------ |
`address` | Uint8Array \| string |
`ss58Format?` | undefined \| number |

**Returns:** string

___

### getPair

▸ **getPair**(`address`: string \| Uint8Array): [KeyringPair](../interfaces/_packages_keyring_src_types_.keyringpair.md)

*Implementation of [KeyringInstance](../interfaces/_packages_keyring_src_types_.keyringinstance.md)*

*Defined in [packages/keyring/src/keyring.ts:215](https://github.com/polkadot-js/common/blob/975103fd/packages/keyring/src/keyring.ts#L215)*

**`name`** getPair

**`summary`** Retrieves an account keyring pair from the Keyring Pair Dictionary, given an account address

**`description`** Returns a keyring pair value from the keyring pair dictionary by performing
a key lookup using the provided account address or public key (after decoding it).

#### Parameters:

Name | Type |
------ | ------ |
`address` | string \| Uint8Array |

**Returns:** [KeyringPair](../interfaces/_packages_keyring_src_types_.keyringpair.md)

___

### getPairs

▸ **getPairs**(): [KeyringPair](../interfaces/_packages_keyring_src_types_.keyringpair.md)[]

*Implementation of [KeyringInstance](../interfaces/_packages_keyring_src_types_.keyringinstance.md)*

*Defined in [packages/keyring/src/keyring.ts:224](https://github.com/polkadot-js/common/blob/975103fd/packages/keyring/src/keyring.ts#L224)*

**`name`** getPairs

**`summary`** Retrieves all account keyring pairs from the Keyring Pair Dictionary

**`description`** Returns an array list of all the keyring pair values that are stored in the keyring pair dictionary.

**Returns:** [KeyringPair](../interfaces/_packages_keyring_src_types_.keyringpair.md)[]

___

### getPublicKeys

▸ **getPublicKeys**(): Uint8Array[]

*Implementation of [KeyringInstance](../interfaces/_packages_keyring_src_types_.keyringinstance.md)*

*Defined in [packages/keyring/src/keyring.ts:233](https://github.com/polkadot-js/common/blob/975103fd/packages/keyring/src/keyring.ts#L233)*

**`name`** getPublicKeys

**`summary`** Retrieves Public Keys of all Keyring Pairs stored in the Keyring Pair Dictionary

**`description`** Returns an array list of all the public keys associated with each of the keyring pair values that are stored in the keyring pair dictionary.

**Returns:** Uint8Array[]

___

### removePair

▸ **removePair**(`address`: string \| Uint8Array): void

*Implementation of [KeyringInstance](../interfaces/_packages_keyring_src_types_.keyringinstance.md)*

*Defined in [packages/keyring/src/keyring.ts:245](https://github.com/polkadot-js/common/blob/975103fd/packages/keyring/src/keyring.ts#L245)*

**`name`** removePair

**`description`** Deletes the provided input address or public key from the stored Keyring Pair Dictionary.

#### Parameters:

Name | Type |
------ | ------ |
`address` | string \| Uint8Array |

**Returns:** void

___

### setSS58Format

▸ **setSS58Format**(`ss58`: number): void

*Defined in [packages/keyring/src/keyring.ts:253](https://github.com/polkadot-js/common/blob/975103fd/packages/keyring/src/keyring.ts#L253)*

**`name`** setSS58Format;

**`description`** Sets the ss58 format for the keyring

#### Parameters:

Name | Type |
------ | ------ |
`ss58` | number |

**Returns:** void

___

### toJson

▸ **toJson**(`address`: string \| Uint8Array, `passphrase?`: undefined \| string): [KeyringPair$Json](../interfaces/_packages_keyring_src_types_.keyringpair_json.md)

*Implementation of [KeyringInstance](../interfaces/_packages_keyring_src_types_.keyringinstance.md)*

*Defined in [packages/keyring/src/keyring.ts:265](https://github.com/polkadot-js/common/blob/975103fd/packages/keyring/src/keyring.ts#L265)*

**`name`** toJson

**`summary`** Returns a JSON object associated with the input argument that contains metadata assocated with an account

**`description`** Returns a JSON object containing the metadata associated with an account
when valid address or public key and when the account passphrase is provided if the account secret
is not already unlocked and available in memory. Note that in [Polkadot-JS Apps](https://github.com/polkadot-js/apps) the user
may backup their account to a JSON file that contains this information.

#### Parameters:

Name | Type |
------ | ------ |
`address` | string \| Uint8Array |
`passphrase?` | undefined \| string |

**Returns:** [KeyringPair$Json](../interfaces/_packages_keyring_src_types_.keyringpair_json.md)
