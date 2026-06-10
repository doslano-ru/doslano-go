# PromoResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Code** | **string** |  | 
**Applied** | **bool** | Применён ли промокод. | 
**DiscountMinor** | Pointer to **int64** | Размер скидки в копейках (если применён). | [optional] 
**Message** | Pointer to **string** | Пояснение, если промокод не применён (письмо при этом отправлено). | [optional] 

## Methods

### NewPromoResult

`func NewPromoResult(code string, applied bool, ) *PromoResult`

NewPromoResult instantiates a new PromoResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPromoResultWithDefaults

`func NewPromoResultWithDefaults() *PromoResult`

NewPromoResultWithDefaults instantiates a new PromoResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCode

`func (o *PromoResult) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *PromoResult) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *PromoResult) SetCode(v string)`

SetCode sets Code field to given value.


### GetApplied

`func (o *PromoResult) GetApplied() bool`

GetApplied returns the Applied field if non-nil, zero value otherwise.

### GetAppliedOk

`func (o *PromoResult) GetAppliedOk() (*bool, bool)`

GetAppliedOk returns a tuple with the Applied field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplied

`func (o *PromoResult) SetApplied(v bool)`

SetApplied sets Applied field to given value.


### GetDiscountMinor

`func (o *PromoResult) GetDiscountMinor() int64`

GetDiscountMinor returns the DiscountMinor field if non-nil, zero value otherwise.

### GetDiscountMinorOk

`func (o *PromoResult) GetDiscountMinorOk() (*int64, bool)`

GetDiscountMinorOk returns a tuple with the DiscountMinor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscountMinor

`func (o *PromoResult) SetDiscountMinor(v int64)`

SetDiscountMinor sets DiscountMinor field to given value.

### HasDiscountMinor

`func (o *PromoResult) HasDiscountMinor() bool`

HasDiscountMinor returns a boolean if a field has been set.

### GetMessage

`func (o *PromoResult) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *PromoResult) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *PromoResult) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *PromoResult) HasMessage() bool`

HasMessage returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


