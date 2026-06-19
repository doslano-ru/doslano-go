# WebhookEventData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**LetterId** | **string** |  | 
**RecipientId** | Pointer to **string** |  | [optional] 
**Status** | **string** |  | 
**ShipmentNumber** | Pointer to **string** |  | [optional] 
**TrackingNumber** | Pointer to **string** |  | [optional] 
**Error** | Pointer to **string** |  | [optional] 
**AmountMinor** | Pointer to **int32** | Фактически списанная стоимость отправления ЭТОМУ получателю, в копейках (доля дисконтированного тотала письма с учётом промокода). Присутствует только в &#x60;recipient.sent&#x60; — отправление реально ушло и оплачено. В &#x60;recipient.failed&#x60; отсутствует: при провале сумма возвращается на баланс. | [optional] 

## Methods

### NewWebhookEventData

`func NewWebhookEventData(letterId string, status string, ) *WebhookEventData`

NewWebhookEventData instantiates a new WebhookEventData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWebhookEventDataWithDefaults

`func NewWebhookEventDataWithDefaults() *WebhookEventData`

NewWebhookEventDataWithDefaults instantiates a new WebhookEventData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLetterId

`func (o *WebhookEventData) GetLetterId() string`

GetLetterId returns the LetterId field if non-nil, zero value otherwise.

### GetLetterIdOk

`func (o *WebhookEventData) GetLetterIdOk() (*string, bool)`

GetLetterIdOk returns a tuple with the LetterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLetterId

`func (o *WebhookEventData) SetLetterId(v string)`

SetLetterId sets LetterId field to given value.


### GetRecipientId

`func (o *WebhookEventData) GetRecipientId() string`

GetRecipientId returns the RecipientId field if non-nil, zero value otherwise.

### GetRecipientIdOk

`func (o *WebhookEventData) GetRecipientIdOk() (*string, bool)`

GetRecipientIdOk returns a tuple with the RecipientId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecipientId

`func (o *WebhookEventData) SetRecipientId(v string)`

SetRecipientId sets RecipientId field to given value.

### HasRecipientId

`func (o *WebhookEventData) HasRecipientId() bool`

HasRecipientId returns a boolean if a field has been set.

### GetStatus

`func (o *WebhookEventData) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *WebhookEventData) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *WebhookEventData) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetShipmentNumber

`func (o *WebhookEventData) GetShipmentNumber() string`

GetShipmentNumber returns the ShipmentNumber field if non-nil, zero value otherwise.

### GetShipmentNumberOk

`func (o *WebhookEventData) GetShipmentNumberOk() (*string, bool)`

GetShipmentNumberOk returns a tuple with the ShipmentNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipmentNumber

`func (o *WebhookEventData) SetShipmentNumber(v string)`

SetShipmentNumber sets ShipmentNumber field to given value.

### HasShipmentNumber

`func (o *WebhookEventData) HasShipmentNumber() bool`

HasShipmentNumber returns a boolean if a field has been set.

### GetTrackingNumber

`func (o *WebhookEventData) GetTrackingNumber() string`

GetTrackingNumber returns the TrackingNumber field if non-nil, zero value otherwise.

### GetTrackingNumberOk

`func (o *WebhookEventData) GetTrackingNumberOk() (*string, bool)`

GetTrackingNumberOk returns a tuple with the TrackingNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackingNumber

`func (o *WebhookEventData) SetTrackingNumber(v string)`

SetTrackingNumber sets TrackingNumber field to given value.

### HasTrackingNumber

`func (o *WebhookEventData) HasTrackingNumber() bool`

HasTrackingNumber returns a boolean if a field has been set.

### GetError

`func (o *WebhookEventData) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *WebhookEventData) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *WebhookEventData) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *WebhookEventData) HasError() bool`

HasError returns a boolean if a field has been set.

### GetAmountMinor

`func (o *WebhookEventData) GetAmountMinor() int32`

GetAmountMinor returns the AmountMinor field if non-nil, zero value otherwise.

### GetAmountMinorOk

`func (o *WebhookEventData) GetAmountMinorOk() (*int32, bool)`

GetAmountMinorOk returns a tuple with the AmountMinor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmountMinor

`func (o *WebhookEventData) SetAmountMinor(v int32)`

SetAmountMinor sets AmountMinor field to given value.

### HasAmountMinor

`func (o *WebhookEventData) HasAmountMinor() bool`

HasAmountMinor returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


