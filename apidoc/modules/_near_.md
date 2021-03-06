[near-runtime-ts](../README.md) > ["near"](../modules/_near_.md)

# External module: "near"

## Index

### Modules

* [near](_near_.near.md)

### Classes

* [ContractContext](../classes/_near_.contractcontext.md)
* [GlobalStorage](../classes/_near_.globalstorage.md)

### Type aliases

* [BufferTypeIndex](_near_.md#buffertypeindex)

### Variables

* [BUFFER_TYPE_CURRENT_ACCOUNT_ID](_near_.md#buffer_type_current_account_id)
* [BUFFER_TYPE_ORIGINATOR_ACCOUNT_ID](_near_.md#buffer_type_originator_account_id)
* [contractContext](_near_.md#contractcontext-1)
* [globalStorage](_near_.md#globalstorage-1)

### Functions

* [input_read_into](_near_.md#input_read_into)
* [input_read_len](_near_.md#input_read_len)
* [read_into](_near_.md#read_into)
* [read_len](_near_.md#read_len)
* [return_value](_near_.md#return_value)
* [storage_iter](_near_.md#storage_iter)
* [storage_iter_next](_near_.md#storage_iter_next)
* [storage_iter_peek_into](_near_.md#storage_iter_peek_into)
* [storage_iter_peek_len](_near_.md#storage_iter_peek_len)
* [storage_read_into](_near_.md#storage_read_into)
* [storage_read_len](_near_.md#storage_read_len)
* [storage_write](_near_.md#storage_write)

---

## Type aliases

<a id="buffertypeindex"></a>

###  BufferTypeIndex

**Ƭ BufferTypeIndex**: *`u32`*

*Defined in [near.ts:1](https://github.com/nearprotocol/near-runtime-ts/blob/a6cbaa1/near.ts#L1)*

___

## Variables

<a id="buffer_type_current_account_id"></a>

### `<Const>` BUFFER_TYPE_CURRENT_ACCOUNT_ID

**● BUFFER_TYPE_CURRENT_ACCOUNT_ID**: *[BufferTypeIndex](_near_.md#buffertypeindex)* = 2

*Defined in [near.ts:4](https://github.com/nearprotocol/near-runtime-ts/blob/a6cbaa1/near.ts#L4)*

___
<a id="buffer_type_originator_account_id"></a>

### `<Const>` BUFFER_TYPE_ORIGINATOR_ACCOUNT_ID

**● BUFFER_TYPE_ORIGINATOR_ACCOUNT_ID**: *[BufferTypeIndex](_near_.md#buffertypeindex)* = 1

*Defined in [near.ts:3](https://github.com/nearprotocol/near-runtime-ts/blob/a6cbaa1/near.ts#L3)*

___
<a id="contractcontext-1"></a>

### `<Let>` contractContext

**● contractContext**: *[ContractContext](../classes/_near_.contractcontext.md)* =  new ContractContext()

*Defined in [near.ts:147](https://github.com/nearprotocol/near-runtime-ts/blob/a6cbaa1/near.ts#L147)*

___
<a id="globalstorage-1"></a>

### `<Let>` globalStorage

**● globalStorage**: *[GlobalStorage](../classes/_near_.globalstorage.md)* =  new GlobalStorage()

*Defined in [near.ts:146](https://github.com/nearprotocol/near-runtime-ts/blob/a6cbaa1/near.ts#L146)*

___

## Functions

<a id="input_read_into"></a>

###  input_read_into

▸ **input_read_into**(ptr: *`usize`*): `void`

*Defined in [near.ts:299](https://github.com/nearprotocol/near-runtime-ts/blob/a6cbaa1/near.ts#L299)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| ptr | `usize` |

**Returns:** `void`

___
<a id="input_read_len"></a>

###  input_read_len

▸ **input_read_len**(): `usize`

*Defined in [near.ts:297](https://github.com/nearprotocol/near-runtime-ts/blob/a6cbaa1/near.ts#L297)*

**Returns:** `usize`

___
<a id="read_into"></a>

###  read_into

▸ **read_into**(type_index: *`u32`*, key: *`usize`*, value: *`usize`*): `void`

*Defined in [near.ts:307](https://github.com/nearprotocol/near-runtime-ts/blob/a6cbaa1/near.ts#L307)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| type_index | `u32` |
| key | `usize` |
| value | `usize` |

**Returns:** `void`

___
<a id="read_len"></a>

###  read_len

▸ **read_len**(type_index: *`u32`*, key: *`usize`*): `u32`

*Defined in [near.ts:305](https://github.com/nearprotocol/near-runtime-ts/blob/a6cbaa1/near.ts#L305)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| type_index | `u32` |
| key | `usize` |

**Returns:** `u32`

___
<a id="return_value"></a>

###  return_value

▸ **return_value**(value_ptr: *`usize`*): `void`

*Defined in [near.ts:302](https://github.com/nearprotocol/near-runtime-ts/blob/a6cbaa1/near.ts#L302)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| value_ptr | `usize` |

**Returns:** `void`

___
<a id="storage_iter"></a>

###  storage_iter

▸ **storage_iter**(prefix: *`usize`*): `u32`

*Defined in [near.ts:288](https://github.com/nearprotocol/near-runtime-ts/blob/a6cbaa1/near.ts#L288)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| prefix | `usize` |

**Returns:** `u32`

___
<a id="storage_iter_next"></a>

###  storage_iter_next

▸ **storage_iter_next**(id: *`u32`*): `u32`

*Defined in [near.ts:290](https://github.com/nearprotocol/near-runtime-ts/blob/a6cbaa1/near.ts#L290)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| id | `u32` |

**Returns:** `u32`

___
<a id="storage_iter_peek_into"></a>

###  storage_iter_peek_into

▸ **storage_iter_peek_into**(id: *`u32`*, value: *`usize`*): `void`

*Defined in [near.ts:294](https://github.com/nearprotocol/near-runtime-ts/blob/a6cbaa1/near.ts#L294)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| id | `u32` |
| value | `usize` |

**Returns:** `void`

___
<a id="storage_iter_peek_len"></a>

###  storage_iter_peek_len

▸ **storage_iter_peek_len**(id: *`u32`*): `usize`

*Defined in [near.ts:292](https://github.com/nearprotocol/near-runtime-ts/blob/a6cbaa1/near.ts#L292)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| id | `u32` |

**Returns:** `usize`

___
<a id="storage_read_into"></a>

###  storage_read_into

▸ **storage_read_into**(key: *`usize`*, value: *`usize`*): `void`

*Defined in [near.ts:286](https://github.com/nearprotocol/near-runtime-ts/blob/a6cbaa1/near.ts#L286)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| key | `usize` |
| value | `usize` |

**Returns:** `void`

___
<a id="storage_read_len"></a>

###  storage_read_len

▸ **storage_read_len**(key: *`usize`*): `usize`

*Defined in [near.ts:284](https://github.com/nearprotocol/near-runtime-ts/blob/a6cbaa1/near.ts#L284)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| key | `usize` |

**Returns:** `usize`

___
<a id="storage_write"></a>

###  storage_write

▸ **storage_write**(key: *`usize`*, value: *`usize`*): `void`

*Defined in [near.ts:282](https://github.com/nearprotocol/near-runtime-ts/blob/a6cbaa1/near.ts#L282)*

**Parameters:**

| Name | Type |
| ------ | ------ |
| key | `usize` |
| value | `usize` |

**Returns:** `void`

___

