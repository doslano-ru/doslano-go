# Pricing

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TotalMinor** | **int64** | Итоговая списанная сумма, в копейках. | 
**Currency** | **string** |  | 
**Promo** | Pointer to [**PromoResult**](PromoResult.md) |  | [optional] 

## Methods

### NewPricing

`func NewPricing(totalMinor int64, currency string, ) *Pricing`

NewPricing instantiates a new Pricing object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPricingWithDefaults

`func NewPricingWithDefaults() *Pricing`

NewPricingWithDefaults instantiates a new Pricing object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTotalMinor

`func (o *Pricing) GetTotalMinor() int64`

GetTotalMinor returns the TotalMinor field if non-nil, zero value otherwise.

### GetTotalMinorOk

`func (o *Pricing) GetTotalMinorOk() (*int64, bool)`

GetTotalMinorOk returns a tuple with the TotalMinor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalMinor

`func (o *Pricing) SetTotalMinor(v int64)`

SetTotalMinor sets TotalMinor field to given value.


### GetCurrency

`func (o *Pricing) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *Pricing) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *Pricing) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetPromo

`func (o *Pricing) GetPromo() PromoResult`

GetPromo returns the Promo field if non-nil, zero value otherwise.

### GetPromoOk

`func (o *Pricing) GetPromoOk() (*PromoResult, bool)`

GetPromoOk returns a tuple with the Promo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromo

`func (o *Pricing) SetPromo(v PromoResult)`

SetPromo sets Promo field to given value.

### HasPromo

`func (o *Pricing) HasPromo() bool`

HasPromo returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


