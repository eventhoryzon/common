**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/util/src/is/object"

# Module: "packages/util/src/is/object"

## Index

### Functions

* [isObject](_packages_util_src_is_object_.md#isobject)

## Functions

### isObject

▸ **isObject**(`value`: unknown): value is ObjectIndexed

*Defined in [packages/util/src/is/object.ts:24](https://github.com/polkadot-js/common/blob/30198d1a/packages/util/src/is/object.ts#L24)*

**`name`** isObject

**`summary`** Tests for an `object`.

**`description`** 
Checks to see if the input value is a JavaScript object.

**`example`** 
<BR>

```javascript
import { isObject } from '@polkadot/util';

isObject({}); // => true
isObject('something'); // => false
```

#### Parameters:

Name | Type |
------ | ------ |
`value` | unknown |

**Returns:** value is ObjectIndexed
