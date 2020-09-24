**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/util/src/u8a/toString"

# Module: "packages/util/src/u8a/toString"

## Index

### Functions

* [u8aToString](_packages_util_src_u8a_tostring_.md#u8atostring)

## Functions

### u8aToString

▸ **u8aToString**(`value?`: Uint8Array \| null): string

*Defined in [packages/util/src/u8a/toString.ts:22](https://github.com/polkadot-js/common/blob/ce964d2f/packages/util/src/u8a/toString.ts#L22)*

**`name`** u8aToString

**`summary`** Creates a utf-8 string from a Uint8Array object.

**`description`** 
`UInt8Array` input values return the actual decoded utf-8 string. `null` or `undefined` values returns an empty string.

**`example`** 
<BR>

```javascript
import { u8aToString } from '@polkadot/util';

u8aToString(new Uint8Array([0x68, 0x65, 0x6c, 0x6c, 0x6f])); // hello
```

#### Parameters:

Name | Type |
------ | ------ |
`value?` | Uint8Array \| null |

**Returns:** string
