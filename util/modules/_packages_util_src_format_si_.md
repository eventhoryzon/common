**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/util/src/format/si"

# Module: "packages/util/src/format/si"

## Index

### Variables

* [SI](_packages_util_src_format_si_.md#si)
* [SI\_MID](_packages_util_src_format_si_.md#si_mid)

### Functions

* [calcSi](_packages_util_src_format_si_.md#calcsi)
* [findSi](_packages_util_src_format_si_.md#findsi)

## Variables

### SI

• `Const` **SI**: [SiDef](../interfaces/_packages_util_src_types_.sidef.md)[] = [ { power: -24, text: 'yocto', value: 'y' }, { power: -21, text: 'zepto', value: 'z' }, { power: -18, text: 'atto', value: 'a' }, { power: -15, text: 'femto', value: 'f' }, { power: -12, text: 'pico', value: 'p' }, { power: -9, text: 'nano', value: 'n' }, { power: -6, text: 'micro', value: 'µ' }, { power: -3, text: 'milli', value: 'm' }, { power: 0, text: 'Unit', value: '-' }, // position 8 { power: 3, text: 'Kilo', value: 'k' }, { power: 6, text: 'Mega', value: 'M' }, { power: 9, text: 'Giga', value: 'G' }, { power: 12, text: 'Tera', value: 'T' }, { power: 15, text: 'Peta', value: 'P' }, { power: 18, text: 'Exa', value: 'E' }, { power: 21, text: 'Zeta', value: 'Z' }, { power: 24, text: 'Yotta', value: 'Y' }]

*Defined in [packages/util/src/format/si.ts:8](https://github.com/polkadot-js/common/blob/13ae8665/packages/util/src/format/si.ts#L8)*

___

### SI\_MID

• `Const` **SI\_MID**: 8 = 8

*Defined in [packages/util/src/format/si.ts:6](https://github.com/polkadot-js/common/blob/13ae8665/packages/util/src/format/si.ts#L6)*

## Functions

### calcSi

▸ **calcSi**(`text`: string, `decimals`: number, `forceUnit?`: undefined \| string): [SiDef](../interfaces/_packages_util_src_types_.sidef.md)

*Defined in [packages/util/src/format/si.ts:40](https://github.com/polkadot-js/common/blob/13ae8665/packages/util/src/format/si.ts#L40)*

#### Parameters:

Name | Type |
------ | ------ |
`text` | string |
`decimals` | number |
`forceUnit?` | undefined \| string |

**Returns:** [SiDef](../interfaces/_packages_util_src_types_.sidef.md)

___

### findSi

▸ **findSi**(`type`: string): [SiDef](../interfaces/_packages_util_src_types_.sidef.md)

*Defined in [packages/util/src/format/si.ts:29](https://github.com/polkadot-js/common/blob/13ae8665/packages/util/src/format/si.ts#L29)*

#### Parameters:

Name | Type |
------ | ------ |
`type` | string |

**Returns:** [SiDef](../interfaces/_packages_util_src_types_.sidef.md)
