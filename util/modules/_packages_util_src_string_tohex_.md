[Polkadot JS Common](../README.md) › [Globals](../globals.md) › ["packages/util/src/string/toHex"](_packages_util_src_string_tohex_.md)

# Module: "packages/util/src/string/toHex"

## Index

### Functions

* [stringToHex](_packages_util_src_string_tohex_.md#stringtohex)

## Functions

###  stringToHex

▸ **stringToHex**(`value?`: undefined | string): *string*

*Defined in [packages/util/src/string/toHex.ts:21](https://github.com/polkadot-js/common/blob/5c886b0f/packages/util/src/string/toHex.ts#L21)*

**`name`** stringToHex

**`summary`** Creates a hex string from a utf-8 string

**`description`** 
String input values return the actual encoded hex value.

**`example`** 
<BR>

```javascript
import { stringToHex } from '@polkadot/util';

stringToU8a('hello'); // 0x68656c6c6f
```

**Parameters:**

Name | Type |
------ | ------ |
`value?` | undefined &#124; string |

**Returns:** *string*
