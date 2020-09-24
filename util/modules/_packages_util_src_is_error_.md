**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/util/src/is/error"

# Module: "packages/util/src/is/error"

## Index

### Functions

* [isError](_packages_util_src_is_error_.md#iserror)

## Functions

### isError

▸ **isError**(`value`: unknown): value is Error

*Defined in [packages/util/src/is/error.ts:20](https://github.com/polkadot-js/common/blob/ce964d2f/packages/util/src/is/error.ts#L20)*

**`name`** isError

**`summary`** Tests for a `Error` object instance.

**`description`** 
Checks to see if the input object is an instance of `Error`.

**`example`** 
<BR>

```javascript
import { isError } from '@polkadot/util';

console.log('isError', isError(new Error('message'))); // => true
```

#### Parameters:

Name | Type |
------ | ------ |
`value` | unknown |

**Returns:** value is Error
