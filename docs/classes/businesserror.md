[@iota-pico/business](../README.md) > [BusinessError](../classes/businesserror.md)

# Class: BusinessError

A business implementation of an error.

## Hierarchy

 `CoreError`

**↳ BusinessError**

## Index

### Constructors

* [constructor](businesserror.md#constructor)

### Properties

* [additional](businesserror.md#additional)
* [domain](businesserror.md#domain)
* [innerError](businesserror.md#innererror)
* [message](businesserror.md#message)
* [name](businesserror.md#name)
* [stack](businesserror.md#stack)

### Methods

* [format](businesserror.md#format)
* [isError](businesserror.md#iserror)

---

## Constructors

<a id="constructor"></a>

###  constructor

⊕ **new BusinessError**(message: *`string`*, additional?: *`object`*, innerError?: *`Error`*): [BusinessError](businesserror.md)

*Overrides CoreError.__constructor*

*Defined in [error/businessError.ts:6](https://github.com/iota-pico/business/tree/master/src/error/businessError.ts#L6*

Create an instance of BusinessError.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| message | `string` |  The message for the error. |
| `Optional` additional | `object` |  Additional details about the error. |
| `Optional` innerError | `Error` |  Add information from inner error if there was one. |

**Returns:** [BusinessError](businesserror.md)

___

## Properties

<a id="additional"></a>

### `<Optional>` additional

**● additional**: *`object`*

*Inherited from CoreError.additional*

*Defined in D:/Workarea/iota.eco/iota-pico/business/node_modules/@iota-pico/core/dist/error/coreError.d.ts:12*

Additional details about the error.

#### Type declaration

[id: `string`]: `any`

___
<a id="domain"></a>

###  domain

**● domain**: *`string`*

*Inherited from CoreError.domain*

*Defined in D:/Workarea/iota.eco/iota-pico/business/node_modules/@iota-pico/core/dist/error/coreError.d.ts:8*

The domain of the error.

___
<a id="innererror"></a>

### `<Optional>` innerError

**● innerError**: *`Error`*

*Inherited from CoreError.innerError*

*Defined in D:/Workarea/iota.eco/iota-pico/business/node_modules/@iota-pico/core/dist/error/coreError.d.ts:18*

The inner error if there was one.

___
<a id="message"></a>

###  message

**● message**: *`string`*

*Inherited from Error.message*

*Defined in D:/Workarea/iota.eco/iota-pico/business/node_modules/typedoc/node_modules/typescript/lib/lib.es5.d.ts:964*

___
<a id="name"></a>

###  name

**● name**: *`string`*

*Inherited from Error.name*

*Defined in D:/Workarea/iota.eco/iota-pico/business/node_modules/typedoc/node_modules/typescript/lib/lib.es5.d.ts:963*

___
<a id="stack"></a>

### `<Optional>` stack

**● stack**: *`string`*

*Inherited from Error.stack*

*Defined in D:/Workarea/iota.eco/iota-pico/business/node_modules/typedoc/node_modules/typescript/lib/lib.es5.d.ts:965*

___

## Methods

<a id="format"></a>

###  format

▸ **format**(): `string`

*Inherited from CoreError.format*

*Defined in D:/Workarea/iota.eco/iota-pico/business/node_modules/@iota-pico/core/dist/error/coreError.d.ts:38*

Format the error to a readable version.

**Returns:** `string`
Formatted version of the error.

___
<a id="iserror"></a>

### `<Static>` isError

▸ **isError**(obj: *`any`*): `boolean`

*Inherited from CoreError.isError*

*Defined in D:/Workarea/iota.eco/iota-pico/business/node_modules/@iota-pico/core/dist/error/coreError.d.ts:33*

Check if an object could be a CoreError.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| obj | `any` |  The object to check if it is a CoreError. |

**Returns:** `boolean`
true If the tested object is a CoreError.

___

