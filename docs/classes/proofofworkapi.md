[@iota-pico/business](../README.md) > [ProofOfWorkApi](../classes/proofofworkapi.md)



# Class: ProofOfWorkApi


ProofOfWork implementation using API.

## Implements

* `IProofOfWork`

## Index

### Constructors

* [constructor](proofofworkapi.md#constructor)


### Methods

* [initialize](proofofworkapi.md#initialize)
* [pow](proofofworkapi.md#pow)



---
## Constructors
<a id="constructor"></a>


### ⊕ **new ProofOfWorkApi**(apiClient: *`IApiClient`*): [ProofOfWorkApi](proofofworkapi.md)


*Defined in [transactions/proofOfWorkApi.ts:17](https://github.com/iotaeco/iota-pico-business/blob/ab10af2/src/transactions/proofOfWorkApi.ts#L17)*



Create an instance of ProofOfWork.


**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| apiClient | `IApiClient`   |  The API client to send the request through. |





**Returns:** [ProofOfWorkApi](proofofworkapi.md)

---


## Methods
<a id="initialize"></a>

###  initialize

► **initialize**(): `Promise`.<`void`>



*Defined in [transactions/proofOfWorkApi.ts:34](https://github.com/iotaeco/iota-pico-business/blob/ab10af2/src/transactions/proofOfWorkApi.ts#L34)*



Allow the proof of work to perform any initialization. Will throw an exception if the implementation is not supported.




**Returns:** `Promise`.<`void`>





___

<a id="pow"></a>

###  pow

► **pow**(trunkTransaction: *`Hash`*, branchTransaction: *`Hash`*, trytes: *`Trytes`[]*, minWeightMagnitude: *`number`*): `Promise`.<`Trytes`[]>



*Defined in [transactions/proofOfWorkApi.ts:46](https://github.com/iotaeco/iota-pico-business/blob/ab10af2/src/transactions/proofOfWorkApi.ts#L46)*



Perform a proof of work on the data.


**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| trunkTransaction | `Hash`   |  The trunkTransaction to use for the pow. |
| branchTransaction | `Hash`   |  The branchTransaction to use for the pow. |
| trytes | `Trytes`[]   |  The trytes to perform the pow on. |
| minWeightMagnitude | `number`   |  The minimum weight magnitude. |





**Returns:** `Promise`.<`Trytes`[]>
The trytes produced by the proof of work.






___

