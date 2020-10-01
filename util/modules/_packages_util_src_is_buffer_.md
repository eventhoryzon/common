**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/util/src/is/buffer"

# Module: "packages/util/src/is/buffer"

## Index

### Functions

* [isBuffer](_packages_util_src_is_buffer_.md#isbuffer)

## Functions

### isBuffer

▸ **isBuffer**(`value`: unknown): value is Buffer

*Defined in [packages/util/src/is/buffer.ts:20](https://github.com/polkadot-js/common/blob/dd1220ac/packages/util/src/is/buffer.ts#L20)*

**`name`** isBuffer

**`summary`** Tests for a `Buffer` object instance.

**`description`** 
Checks to see if the input object is an instance of `Buffer`.

**`example`** 
<BR>

```javascript
import { isBuffer } from '@polkadot/util';

console.log('isBuffer', isBuffer(Buffer.from([]))); // => true
```

#### Parameters:

Name | Type |
------ | ------ |
`value` | unknown |

**Returns:** value is Buffer
