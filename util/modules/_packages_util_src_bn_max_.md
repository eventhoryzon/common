**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/util/src/bn/max"

# Module: "packages/util/src/bn/max"

## Index

### Functions

* [max](_packages_util_src_bn_max_.md#max)

## Functions

### max

▸ **max**(...`items`: BN[]): BN

*Defined in [packages/util/src/bn/max.ts:21](https://github.com/polkadot-js/common/blob/bd1735ca/packages/util/src/bn/max.ts#L21)*

**`name`** bnMax

**`summary`** Finds and returns the highest value in an array of BNs.

**`example`** 
<BR>

```javascript
import BN from 'bn.js';
import { bnMax } from '@polkadot/util';

bnMax([new BN(1), new BN(3), new BN(2)]).toString(); // => '3'
```

#### Parameters:

Name | Type |
------ | ------ |
`...items` | BN[] |

**Returns:** BN
