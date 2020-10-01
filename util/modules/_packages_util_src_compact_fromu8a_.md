**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/util/src/compact/fromU8a"

# Module: "packages/util/src/compact/fromU8a"

## Index

### Functions

* [compactFromU8a](_packages_util_src_compact_fromu8a_.md#compactfromu8a)

## Functions

### compactFromU8a

▸ **compactFromU8a**(`_input`: Uint8Array \| string, `bitLength`: [BitLength](_packages_util_src_compact_types_.md#bitlength)): [number, BN]

*Defined in [packages/util/src/compact/fromU8a.ts:26](https://github.com/polkadot-js/common/blob/dd1220ac/packages/util/src/compact/fromU8a.ts#L26)*

**`name`** compactFromU8a

**`description`** Retrievs the offset and encoded length from a compact-prefixed value

**`example`** 
<BR>

```javascript
import { compactFromU8a } from '@polkadot/util';

const [offset, length] = compactFromU8a(new Uint8Array([254, 255, 3, 0]), 32));

console.log('value offset=', offset, 'length=', length); // 4, 0xffff
```

#### Parameters:

Name | Type | Default value |
------ | ------ | ------ |
`_input` | Uint8Array \| string | - |
`bitLength` | [BitLength](_packages_util_src_compact_types_.md#bitlength) | DEFAULT_BITLENGTH |

**Returns:** [number, BN]
