# DryRunResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DryRun** | **bool** | Всегда &#x60;true&#x60; (маркер ответа пробного прогона). | 
**Valid** | **bool** | Всегда &#x60;true&#x60; — невалидные запросы получают 400/422. | 
**RecipientsCount** | **int32** | Количество получателей (&#x3D; отправлений) в запросе. | 
**Pricing** | [**DryRunResultPricing**](DryRunResultPricing.md) |  | 

## Methods

### NewDryRunResult

`func NewDryRunResult(dryRun bool, valid bool, recipientsCount int32, pricing DryRunResultPricing, ) *DryRunResult`

NewDryRunResult instantiates a new DryRunResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDryRunResultWithDefaults

`func NewDryRunResultWithDefaults() *DryRunResult`

NewDryRunResultWithDefaults instantiates a new DryRunResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDryRun

`func (o *DryRunResult) GetDryRun() bool`

GetDryRun returns the DryRun field if non-nil, zero value otherwise.

### GetDryRunOk

`func (o *DryRunResult) GetDryRunOk() (*bool, bool)`

GetDryRunOk returns a tuple with the DryRun field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDryRun

`func (o *DryRunResult) SetDryRun(v bool)`

SetDryRun sets DryRun field to given value.


### GetValid

`func (o *DryRunResult) GetValid() bool`

GetValid returns the Valid field if non-nil, zero value otherwise.

### GetValidOk

`func (o *DryRunResult) GetValidOk() (*bool, bool)`

GetValidOk returns a tuple with the Valid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValid

`func (o *DryRunResult) SetValid(v bool)`

SetValid sets Valid field to given value.


### GetRecipientsCount

`func (o *DryRunResult) GetRecipientsCount() int32`

GetRecipientsCount returns the RecipientsCount field if non-nil, zero value otherwise.

### GetRecipientsCountOk

`func (o *DryRunResult) GetRecipientsCountOk() (*int32, bool)`

GetRecipientsCountOk returns a tuple with the RecipientsCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecipientsCount

`func (o *DryRunResult) SetRecipientsCount(v int32)`

SetRecipientsCount sets RecipientsCount field to given value.


### GetPricing

`func (o *DryRunResult) GetPricing() DryRunResultPricing`

GetPricing returns the Pricing field if non-nil, zero value otherwise.

### GetPricingOk

`func (o *DryRunResult) GetPricingOk() (*DryRunResultPricing, bool)`

GetPricingOk returns a tuple with the Pricing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPricing

`func (o *DryRunResult) SetPricing(v DryRunResultPricing)`

SetPricing sets Pricing field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


