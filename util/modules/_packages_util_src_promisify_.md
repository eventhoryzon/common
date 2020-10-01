**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/util/src/promisify"

# Module: "packages/util/src/promisify"

## Index

### Functions

* [promisify](_packages_util_src_promisify_.md#promisify)

## Functions

### promisify

▸ **promisify**\<R>(`self`: unknown, `fn`: (...params: any) => any, ...`params`: any[]): Promise\<R>

*Defined in [packages/util/src/promisify.ts:20](https://github.com/polkadot-js/common/blob/13ae8665/packages/util/src/promisify.ts#L20)*

**`name`** promisify

**`summary`** Wraps an async callback into a `Promise`

**`description`** 
Wraps the supplied async function `fn` that has a standard JS callback `(error: Error, result: any)` into a `Promise`, passing the supplied parameters. When `error` is set, the Promise is rejected, else the Promise resolves with the `result` value.

**`example`** 
<BR>

```javascript
const { promisify } from '@polkadot/util';

await promisify(null, ((a, cb) => cb(null, a), true); // resolves with `true`
await promisify(null, (cb) => cb(new Error('error!'))); // rejects with `error!`
```

#### Type parameters:

Name | Default |
------ | ------ |
`R` | any |

#### Parameters:

Name | Type |
------ | ------ |
`self` | unknown |
`fn` | (...params: any) => any |
`...params` | any[] |

**Returns:** Promise\<R>
