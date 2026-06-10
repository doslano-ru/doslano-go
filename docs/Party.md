# Party

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** |  | [optional] 
**Address** | Pointer to **string** |  | [optional] 
**PartyType** | Pointer to [**PartyType**](PartyType.md) |  | [optional] 
**Inn** | Pointer to **string** |  | [optional] 

## Methods

### NewParty

`func NewParty() *Party`

NewParty instantiates a new Party object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartyWithDefaults

`func NewPartyWithDefaults() *Party`

NewPartyWithDefaults instantiates a new Party object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *Party) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Party) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Party) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *Party) HasName() bool`

HasName returns a boolean if a field has been set.

### GetAddress

`func (o *Party) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *Party) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *Party) SetAddress(v string)`

SetAddress sets Address field to given value.

### HasAddress

`func (o *Party) HasAddress() bool`

HasAddress returns a boolean if a field has been set.

### GetPartyType

`func (o *Party) GetPartyType() PartyType`

GetPartyType returns the PartyType field if non-nil, zero value otherwise.

### GetPartyTypeOk

`func (o *Party) GetPartyTypeOk() (*PartyType, bool)`

GetPartyTypeOk returns a tuple with the PartyType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartyType

`func (o *Party) SetPartyType(v PartyType)`

SetPartyType sets PartyType field to given value.

### HasPartyType

`func (o *Party) HasPartyType() bool`

HasPartyType returns a boolean if a field has been set.

### GetInn

`func (o *Party) GetInn() string`

GetInn returns the Inn field if non-nil, zero value otherwise.

### GetInnOk

`func (o *Party) GetInnOk() (*string, bool)`

GetInnOk returns a tuple with the Inn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInn

`func (o *Party) SetInn(v string)`

SetInn sets Inn field to given value.

### HasInn

`func (o *Party) HasInn() bool`

HasInn returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


