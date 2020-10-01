**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/util/src/bn/toBn"

# Module: "packages/util/src/bn/toBn"

## Index

### Functions

* [bnToBn](_packages_util_src_bn_tobn_.md#bntobn)

## Functions

### bnToBn

▸ **bnToBn**\<ExtToBn>(`value?`: ExtToBn \| BN \| BigInt \| string \| number \| null): BN

*Defined in [packages/util/src/bn/toBn.ts:29](https://github.com/polkadot-js/common/blob/dd1220ac/packages/util/src/bn/toBn.ts#L29)*

**`name`** bnToBn

**`summary`** Creates a BN value from a BN, BigInt, string (base 10 or hex) or number input.

**`description`** 
`null` inputs returns a `0x0` result, BN values returns the value, numbers returns a BN representation.

**`example`** 
<BR>

```javascript
import BN from 'bn.js';
import { bnToBn } from '@polkadot/util';

bnToBn(0x1234); // => BN(0x1234)
bnToBn(new BN(0x1234)); // => BN(0x1234)
```

#### Type parameters:

Name | Type |
------ | ------ |
`ExtToBn` | [ToBn](../interfaces/_packages_util_src_types_.tobn.md) |

#### Parameters:

Name | Type |
------ | ------ |
`value?` | ExtToBn \| BN \| BigInt \| string \| number \| null |

**Returns:** BN
