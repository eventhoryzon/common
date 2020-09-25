**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/util/src/buffer/toU8a"

# Module: "packages/util/src/buffer/toU8a"

## Index

### Functions

* [bufferToU8a](_packages_util_src_buffer_tou8a_.md#buffertou8a)

## Functions

### bufferToU8a

▸ **bufferToU8a**(`buffer?`: Buffer \| number[] \| null): Uint8Array

*Defined in [packages/util/src/buffer/toU8a.ts:18](https://github.com/polkadot-js/common/blob/bd1735ca/packages/util/src/buffer/toU8a.ts#L18)*

**`name`** bufferToU8a

**`summary`** Creates a Uint8Array value from a Buffer object.

**`description`** 
`null` inputs returns an empty result, `Buffer` values return the actual value as a `Uint8Array`. Anything that is not a `Buffer` object throws an error.

**`example`** 
<BR>

```javascript
import { bufferToU8a } from '@polkadot/util';

bufferToU8a(Buffer.from([1, 2, 3]));
```

#### Parameters:

Name | Type |
------ | ------ |
`buffer?` | Buffer \| number[] \| null |

**Returns:** Uint8Array
