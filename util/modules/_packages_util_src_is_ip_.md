**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/util/src/is/ip"

# Module: "packages/util/src/is/ip"

## Index

### Functions

* [isIp](_packages_util_src_is_ip_.md#isip)

## Functions

### isIp

▸ **isIp**(`value`: string, `type?`: IpTypes): boolean

*Defined in [packages/util/src/is/ip.ts:25](https://github.com/polkadot-js/common/blob/30198d1a/packages/util/src/is/ip.ts#L25)*

**`name`** isIp

**`summary`** Tests if the value is a valid IP address

**`description`** 
Checks to see if the value is a valid IP address. Optionally check for either v4/v6

**`example`** 
<BR>

```javascript
import { isIp } from '@polkadot/util';

isIp('192.168.0.1')); // => true
isIp('1:2:3:4:5:6:7:8'); // => true
isIp('192.168.0.1', 'v6')); // => false
isIp('1:2:3:4:5:6:7:8', 'v4'); // => false
```

#### Parameters:

Name | Type |
------ | ------ |
`value` | string |
`type?` | IpTypes |

**Returns:** boolean
