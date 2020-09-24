**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/util/src/string/toU8a"

# Module: "packages/util/src/string/toU8a"

## Index

### Functions

* [stringToU8a](_packages_util_src_string_tou8a_.md#stringtou8a)

## Functions

### stringToU8a

▸ **stringToU8a**(`value?`: undefined \| string): Uint8Array

*Defined in [packages/util/src/string/toU8a.ts:22](https://github.com/polkadot-js/common/blob/aff78c2e/packages/util/src/string/toU8a.ts#L22)*

**`name`** stringToU8a

**`summary`** Creates a Uint8Array object from a utf-8 string.

**`description`** 
String input values return the actual encoded `UInt8Array`. `null` or `undefined` values returns an empty encoded array.

**`example`** 
<BR>

```javascript
import { stringToU8a } from '@polkadot/util';

stringToU8a('hello'); // [0x68, 0x65, 0x6c, 0x6c, 0x6f]
```

#### Parameters:

Name | Type |
------ | ------ |
`value?` | undefined \| string |

**Returns:** Uint8Array
