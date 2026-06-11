# DryRunResultPricing

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SubtotalMinor** | **int64** | Цена без скидки, в копейках. | 
**TotalMinor** | **int64** | Итог к списанию (после промокода), в копейках. Non-binding — фиксируется при реальной оплате. | 
**Currency** | **string** |  | 
**Promo** | Pointer to [**PromoResult**](PromoResult.md) |  | [optional] 

## Methods

### NewDryRunResultPricing

`func NewDryRunResultPricing(subtotalMinor int64, totalMinor int64, currency string, ) *DryRunResultPricing`

NewDryRunResultPricing instantiates a new DryRunResultPricing object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDryRunResultPricingWithDefaults

`func NewDryRunResultPricingWithDefaults() *DryRunResultPricing`

NewDryRunResultPricingWithDefaults instantiates a new DryRunResultPricing object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSubtotalMinor

`func (o *DryRunResultPricing) GetSubtotalMinor() int64`

GetSubtotalMinor returns the SubtotalMinor field if non-nil, zero value otherwise.

### GetSubtotalMinorOk

`func (o *DryRunResultPricing) GetSubtotalMinorOk() (*int64, bool)`

GetSubtotalMinorOk returns a tuple with the SubtotalMinor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubtotalMinor

`func (o *DryRunResultPricing) SetSubtotalMinor(v int64)`

SetSubtotalMinor sets SubtotalMinor field to given value.


### GetTotalMinor

`func (o *DryRunResultPricing) GetTotalMinor() int64`

GetTotalMinor returns the TotalMinor field if non-nil, zero value otherwise.

### GetTotalMinorOk

`func (o *DryRunResultPricing) GetTotalMinorOk() (*int64, bool)`

GetTotalMinorOk returns a tuple with the TotalMinor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalMinor

`func (o *DryRunResultPricing) SetTotalMinor(v int64)`

SetTotalMinor sets TotalMinor field to given value.


### GetCurrency

`func (o *DryRunResultPricing) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *DryRunResultPricing) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *DryRunResultPricing) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetPromo

`func (o *DryRunResultPricing) GetPromo() PromoResult`

GetPromo returns the Promo field if non-nil, zero value otherwise.

### GetPromoOk

`func (o *DryRunResultPricing) GetPromoOk() (*PromoResult, bool)`

GetPromoOk returns a tuple with the Promo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromo

`func (o *DryRunResultPricing) SetPromo(v PromoResult)`

SetPromo sets Promo field to given value.

### HasPromo

`func (o *DryRunResultPricing) HasPromo() bool`

HasPromo returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


