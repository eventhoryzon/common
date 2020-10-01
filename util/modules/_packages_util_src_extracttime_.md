**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/util/src/extractTime"

# Module: "packages/util/src/extractTime"

## Index

### Functions

* [extractTime](_packages_util_src_extracttime_.md#extracttime)

## Functions

### extractTime

▸ **extractTime**(`milliseconds?`: undefined \| number): [Time](../interfaces/_packages_util_src_types_.time.md)

*Defined in [packages/util/src/extractTime.ts:38](https://github.com/polkadot-js/common/blob/dd1220ac/packages/util/src/extractTime.ts#L38)*

**`name`** extractTime

**`summary`** Convert a quantity of seconds to Time array representing accumulated {days, minutes, hours, seconds, milliseconds}

**`example`** 
<BR>

```javascript
import { extractTime } from '@polkadot/util';

const { days, minutes, hours, seconds, milliseconds } = extractTime(6000); // 0, 0, 10, 0, 0
```

#### Parameters:

Name | Type |
------ | ------ |
`milliseconds?` | undefined \| number |

**Returns:** [Time](../interfaces/_packages_util_src_types_.time.md)
