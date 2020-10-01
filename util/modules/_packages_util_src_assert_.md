**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/util/src/assert"

# Module: "packages/util/src/assert"

## Index

### Functions

* [assert](_packages_util_src_assert_.md#assert)

## Functions

### assert

▸ **assert**(`condition`: unknown, `message`: string \| MessageFn): asserts condition

*Defined in [packages/util/src/assert.ts:24](https://github.com/polkadot-js/common/blob/dd1220ac/packages/util/src/assert.ts#L24)*

**`name`** assert

**`summary`** Checks for a valid test, if not Error is thrown.

**`description`** 
Checks that `test` is a truthy value. If value is falsy (`null`, `undefined`, `false`, ...), it throws an Error with the supplied `message`. When `test` passes, `true` is returned.

**`example`** 
<BR>

```javascript
const { assert } from '@polkadot/util';

assert(true, 'True should be true'); // passes
assert(false, 'False should not be true'); // Error thrown
assert(false, () => 'message'); // Error with 'message'
```

#### Parameters:

Name | Type |
------ | ------ |
`condition` | unknown |
`message` | string \| MessageFn |

**Returns:** asserts condition
