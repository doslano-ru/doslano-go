# PaymentResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Charged** | **bool** | Списаны ли средства с баланса. | 
**Status** | Pointer to **string** | &#x60;awaiting_payment&#x60; — при &#x60;on_insufficient_funds&#x3D;hold&#x60; до пополнения. | [optional] 

## Methods

### NewPaymentResult

`func NewPaymentResult(charged bool, ) *PaymentResult`

NewPaymentResult instantiates a new PaymentResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPaymentResultWithDefaults

`func NewPaymentResultWithDefaults() *PaymentResult`

NewPaymentResultWithDefaults instantiates a new PaymentResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCharged

`func (o *PaymentResult) GetCharged() bool`

GetCharged returns the Charged field if non-nil, zero value otherwise.

### GetChargedOk

`func (o *PaymentResult) GetChargedOk() (*bool, bool)`

GetChargedOk returns a tuple with the Charged field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCharged

`func (o *PaymentResult) SetCharged(v bool)`

SetCharged sets Charged field to given value.


### GetStatus

`func (o *PaymentResult) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PaymentResult) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PaymentResult) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *PaymentResult) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


