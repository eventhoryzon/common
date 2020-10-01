**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/util/src/u8a/concat"

# Module: "packages/util/src/u8a/concat"

## Index

### Functions

* [u8aConcat](_packages_util_src_u8a_concat_.md#u8aconcat)

## Functions

### u8aConcat

▸ **u8aConcat**(...`list`: (Uint8Array \| string)[]): Uint8Array

*Defined in [packages/util/src/u8a/concat.ts:23](https://github.com/polkadot-js/common/blob/13ae8665/packages/util/src/u8a/concat.ts#L23)*

**`name`** u8aConcat

**`summary`** Creates a concatenated Uint8Array from the inputs.

**`description`** 
Concatenates the input arrays into a single `UInt8Array`.

**`example`** 
<BR>

```javascript
import { u8aConcat } from '@polkadot/util';

u8aConcat(
  new Uint8Array([1, 2, 3]),
  new Uint8Array([4, 5, 6])
); // [1, 2, 3, 4, 5, 6]
```

#### Parameters:

Name | Type |
------ | ------ |
`...list` | (Uint8Array \| string)[] |

**Returns:** Uint8Array
