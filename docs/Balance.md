# Balance

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BalanceMinor** | **int64** | Баланс в копейках. | 
**Currency** | **string** |  | 

## Methods

### NewBalance

`func NewBalance(balanceMinor int64, currency string, ) *Balance`

NewBalance instantiates a new Balance object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBalanceWithDefaults

`func NewBalanceWithDefaults() *Balance`

NewBalanceWithDefaults instantiates a new Balance object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBalanceMinor

`func (o *Balance) GetBalanceMinor() int64`

GetBalanceMinor returns the BalanceMinor field if non-nil, zero value otherwise.

### GetBalanceMinorOk

`func (o *Balance) GetBalanceMinorOk() (*int64, bool)`

GetBalanceMinorOk returns a tuple with the BalanceMinor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBalanceMinor

`func (o *Balance) SetBalanceMinor(v int64)`

SetBalanceMinor sets BalanceMinor field to given value.


### GetCurrency

`func (o *Balance) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *Balance) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *Balance) SetCurrency(v string)`

SetCurrency sets Currency field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


