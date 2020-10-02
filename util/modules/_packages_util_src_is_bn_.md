**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/util/src/is/bn"

# Module: "packages/util/src/is/bn"

## Index

### Functions

* [isBn](_packages_util_src_is_bn_.md#isbn)

## Functions

### isBn

▸ **isBn**(`value`: unknown): value is BN

*Defined in [packages/util/src/is/bn.ts:21](https://github.com/polkadot-js/common/blob/975103fd/packages/util/src/is/bn.ts#L21)*

**`name`** isBn

**`summary`** Tests for a `BN` object instance.

**`description`** 
Checks to see if the input object is an instance of `BN` (bn.js).

**`example`** 
<BR>

```javascript
import BN from 'bn.js';
import { isBn } from '@polkadot/util';

console.log('isBn', isBn(new BN(1))); // => true
```

#### Parameters:

Name | Type |
------ | ------ |
`value` | unknown |

**Returns:** value is BN
