**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/util/src/hex/toBn"

# Module: "packages/util/src/hex/toBn"

## Index

### Functions

* [hexToBn](_packages_util_src_hex_tobn_.md#hextobn)

## Functions

### hexToBn

▸ **hexToBn**(`value?`: string \| number \| null, `options`: [ToBnOptions](../interfaces/_packages_util_src_types_.tobnoptions.md) \| boolean): BN

*Defined in [packages/util/src/hex/toBn.ts:34](https://github.com/polkadot-js/common/blob/aff78c2e/packages/util/src/hex/toBn.ts#L34)*

**`name`** hexToBn

**`summary`** Creates a BN.js bignumber object from a hex string.

**`description`** 
`null` inputs returns a `BN(0)` result. Hex input values return the actual value converted to a BN. Anything that is not a hex string (including the `0x` prefix) throws an error.

**`example`** 
<BR>

```javascript
import { hexToBn } from '@polkadot/util';

hexToBn('0x123480001f'); // => BN(0x123480001f)
```

#### Parameters:

Name | Type | Default value |
------ | ------ | ------ |
`value?` | string \| number \| null | - |
`options` | [ToBnOptions](../interfaces/_packages_util_src_types_.tobnoptions.md) \| boolean | { isLe: false, isNegative: false } |

**Returns:** BN
