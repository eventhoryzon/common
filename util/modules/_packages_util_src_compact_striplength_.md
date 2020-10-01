**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/util/src/compact/stripLength"

# Module: "packages/util/src/compact/stripLength"

## Index

### Functions

* [compactStripLength](_packages_util_src_compact_striplength_.md#compactstriplength)

## Functions

### compactStripLength

▸ **compactStripLength**(`input`: Uint8Array, `bitLength`: [BitLength](_packages_util_src_compact_types_.md#bitlength)): [number, Uint8Array]

*Defined in [packages/util/src/compact/stripLength.ts:21](https://github.com/polkadot-js/common/blob/dd1220ac/packages/util/src/compact/stripLength.ts#L21)*

**`name`** compactStripLength

**`description`** Removes the length prefix, returning both the total length (including the value + compact encoding) and the decoded value with the correct length

**`example`** 
<BR>

```javascript
import { compactStripLength } from '@polkadot/util';

console.log(compactStripLength(new Uint8Array([2 << 2, 0xde, 0xad]))); // [2, Uint8Array[0xde, 0xad]]
```

#### Parameters:

Name | Type | Default value |
------ | ------ | ------ |
`input` | Uint8Array | - |
`bitLength` | [BitLength](_packages_util_src_compact_types_.md#bitlength) | DEFAULT_BITLENGTH |

**Returns:** [number, Uint8Array]
