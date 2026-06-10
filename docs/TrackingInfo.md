# TrackingInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RecipientId** | **string** |  | 
**ShipmentNumber** | Pointer to **string** |  | [optional] 
**TrackingNumber** | Pointer to **string** |  | [optional] 
**Events** | [**[]TrackingInfoEventsInner**](TrackingInfoEventsInner.md) |  | 

## Methods

### NewTrackingInfo

`func NewTrackingInfo(recipientId string, events []TrackingInfoEventsInner, ) *TrackingInfo`

NewTrackingInfo instantiates a new TrackingInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTrackingInfoWithDefaults

`func NewTrackingInfoWithDefaults() *TrackingInfo`

NewTrackingInfoWithDefaults instantiates a new TrackingInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRecipientId

`func (o *TrackingInfo) GetRecipientId() string`

GetRecipientId returns the RecipientId field if non-nil, zero value otherwise.

### GetRecipientIdOk

`func (o *TrackingInfo) GetRecipientIdOk() (*string, bool)`

GetRecipientIdOk returns a tuple with the RecipientId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecipientId

`func (o *TrackingInfo) SetRecipientId(v string)`

SetRecipientId sets RecipientId field to given value.


### GetShipmentNumber

`func (o *TrackingInfo) GetShipmentNumber() string`

GetShipmentNumber returns the ShipmentNumber field if non-nil, zero value otherwise.

### GetShipmentNumberOk

`func (o *TrackingInfo) GetShipmentNumberOk() (*string, bool)`

GetShipmentNumberOk returns a tuple with the ShipmentNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShipmentNumber

`func (o *TrackingInfo) SetShipmentNumber(v string)`

SetShipmentNumber sets ShipmentNumber field to given value.

### HasShipmentNumber

`func (o *TrackingInfo) HasShipmentNumber() bool`

HasShipmentNumber returns a boolean if a field has been set.

### GetTrackingNumber

`func (o *TrackingInfo) GetTrackingNumber() string`

GetTrackingNumber returns the TrackingNumber field if non-nil, zero value otherwise.

### GetTrackingNumberOk

`func (o *TrackingInfo) GetTrackingNumberOk() (*string, bool)`

GetTrackingNumberOk returns a tuple with the TrackingNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrackingNumber

`func (o *TrackingInfo) SetTrackingNumber(v string)`

SetTrackingNumber sets TrackingNumber field to given value.

### HasTrackingNumber

`func (o *TrackingInfo) HasTrackingNumber() bool`

HasTrackingNumber returns a boolean if a field has been set.

### GetEvents

`func (o *TrackingInfo) GetEvents() []TrackingInfoEventsInner`

GetEvents returns the Events field if non-nil, zero value otherwise.

### GetEventsOk

`func (o *TrackingInfo) GetEventsOk() (*[]TrackingInfoEventsInner, bool)`

GetEventsOk returns a tuple with the Events field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvents

`func (o *TrackingInfo) SetEvents(v []TrackingInfoEventsInner)`

SetEvents sets Events field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


