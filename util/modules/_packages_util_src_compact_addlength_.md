**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/util/src/compact/addLength"

# Module: "packages/util/src/compact/addLength"

## Index

### Functions

* [compactAddLength](_packages_util_src_compact_addlength_.md#compactaddlength)

## Functions

### compactAddLength

▸ **compactAddLength**(`input`: Uint8Array): Uint8Array

*Defined in [packages/util/src/compact/addLength.ts:19](https://github.com/polkadot-js/common/blob/13ae8665/packages/util/src/compact/addLength.ts#L19)*

**`name`** compactAddLength

**`description`** Adds a length prefix to the input value

**`example`** 
<BR>

```javascript
import { compactAddLength } from '@polkadot/util';

console.log(compactAddLength(new Uint8Array([0xde, 0xad, 0xbe, 0xef]))); // Uint8Array([4 << 2, 0xde, 0xad, 0xbe, 0xef])
```

#### Parameters:

Name | Type |
------ | ------ |
`input` | Uint8Array |

**Returns:** Uint8Array
