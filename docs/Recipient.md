# Recipient

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Name** | **string** |  | 
**Address** | Pointer to **string** |  | [optional] 
**Status** | [**RecipientStatus**](RecipientStatus.md) |  | 
**ShipmentNumber** | Pointer to **string** | Наш трек-номер (РПО), присваивается сразу при создании. | [optional] 
**TrackingNumber** | Pointer to **string** | Трек-номер Почты России (ШПИ). Появляется после регистрации отправления. | [optional] 
**PriceMinor** | Pointer to **int64** | Стоимость отправления этому получателю, в копейках. | [optional] 
**Error** | Pointer to **string** | Причина ошибки (для &#x60;failed&#x60;). | [optional] 

## Methods

### NewRecipient

`func NewRecipient(id string, name string, status RecipientStatus, ) *Recipient`

NewRecipient instantiates a new Recipient object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRecipientWithDefaults

`func NewRecipientWithDefaults() *Recipient`

NewRecipientWithDefaults instantiates a new Recipient object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Recipient) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Recipient) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Recipient) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *Recipient) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Recipient) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Recipient) SetName(v string)`

SetName sets Name field to given value.


### GetAddress

`func (o *Recipient) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *Recipient) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *Recipient) SetAddress(v string)`

SetAddress sets Address field to given value.

### HasAddress

`func (o *Recipient) HasAddress() bool`

HasAddress returns a boolean if a field has been set.

### GetStatus

`func (o *Recipient) GetStatus() RecipientStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Recipient) GetStatusOk() (*RecipientStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Recipient) SetStatus(v RecipientStatus)`

SetStatus sets Status field to given value.


### GetShipmentNumber

`func (o *Recipient) GetShipmentNumber() string`

GetShipmentNumber returns the ShipmentNumber field if non-nil, zero value otherwise.

### GetShipmentNumberOk

`func (o *Recipient) GetShipmentNumberOk() (*string, bool)`

GetShipmentNumberOk returns a tuple with the ShipmentNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipmentNumber

`func (o *Recipient) SetShipmentNumber(v string)`

SetShipmentNumber sets ShipmentNumber field to given value.

### HasShipmentNumber

`func (o *Recipient) HasShipmentNumber() bool`

HasShipmentNumber returns a boolean if a field has been set.

### GetTrackingNumber

`func (o *Recipient) GetTrackingNumber() string`

GetTrackingNumber returns the TrackingNumber field if non-nil, zero value otherwise.

### GetTrackingNumberOk

`func (o *Recipient) GetTrackingNumberOk() (*string, bool)`

GetTrackingNumberOk returns a tuple with the TrackingNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackingNumber

`func (o *Recipient) SetTrackingNumber(v string)`

SetTrackingNumber sets TrackingNumber field to given value.

### HasTrackingNumber

`func (o *Recipient) HasTrackingNumber() bool`

HasTrackingNumber returns a boolean if a field has been set.

### GetPriceMinor

`func (o *Recipient) GetPriceMinor() int64`

GetPriceMinor returns the PriceMinor field if non-nil, zero value otherwise.

### GetPriceMinorOk

`func (o *Recipient) GetPriceMinorOk() (*int64, bool)`

GetPriceMinorOk returns a tuple with the PriceMinor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriceMinor

`func (o *Recipient) SetPriceMinor(v int64)`

SetPriceMinor sets PriceMinor field to given value.

### HasPriceMinor

`func (o *Recipient) HasPriceMinor() bool`

HasPriceMinor returns a boolean if a field has been set.

### GetError

`func (o *Recipient) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *Recipient) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *Recipient) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *Recipient) HasError() bool`

HasError returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


