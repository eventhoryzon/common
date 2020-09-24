**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/util/src/hex/addPrefix"

# Module: "packages/util/src/hex/addPrefix"

## Index

### Functions

* [hexAddPrefix](_packages_util_src_hex_addprefix_.md#hexaddprefix)

## Functions

### hexAddPrefix

▸ **hexAddPrefix**(`value?`: string \| null): string

*Defined in [packages/util/src/hex/addPrefix.ts:20](https://github.com/polkadot-js/common/blob/ce964d2f/packages/util/src/hex/addPrefix.ts#L20)*

**`name`** hexAddPrefix

**`summary`** Adds the `0x` prefix to string values.

**`description`** 
Returns a `0x` prefixed string from the input value. If the input is already prefixed, it is returned unchanged.

**`example`** 
<BR>

```javascript
import { hexAddPrefix } from '@polkadot/util';

console.log('With prefix', hexAddPrefix('0a0b12')); // => 0x0a0b12
```

#### Parameters:

Name | Type |
------ | ------ |
`value?` | string \| null |

**Returns:** string
