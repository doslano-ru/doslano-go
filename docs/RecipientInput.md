# RecipientInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | ФИО или название получателя. | 
**Address** | **string** | Адрес получателя (строкой; нормализуется на нашей стороне). | 
**PartyType** | Pointer to [**PartyType**](PartyType.md) |  | [optional] 
**Inn** | Pointer to **string** |  | [optional] 

## Methods

### NewRecipientInput

`func NewRecipientInput(name string, address string, ) *RecipientInput`

NewRecipientInput instantiates a new RecipientInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRecipientInputWithDefaults

`func NewRecipientInputWithDefaults() *RecipientInput`

NewRecipientInputWithDefaults instantiates a new RecipientInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *RecipientInput) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *RecipientInput) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *RecipientInput) SetName(v string)`

SetName sets Name field to given value.


### GetAddress

`func (o *RecipientInput) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *RecipientInput) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *RecipientInput) SetAddress(v string)`

SetAddress sets Address field to given value.


### GetPartyType

`func (o *RecipientInput) GetPartyType() PartyType`

GetPartyType returns the PartyType field if non-nil, zero value otherwise.

### GetPartyTypeOk

`func (o *RecipientInput) GetPartyTypeOk() (*PartyType, bool)`

GetPartyTypeOk returns a tuple with the PartyType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartyType

`func (o *RecipientInput) SetPartyType(v PartyType)`

SetPartyType sets PartyType field to given value.

### HasPartyType

`func (o *RecipientInput) HasPartyType() bool`

HasPartyType returns a boolean if a field has been set.

### GetInn

`func (o *RecipientInput) GetInn() string`

GetInn returns the Inn field if non-nil, zero value otherwise.

### GetInnOk

`func (o *RecipientInput) GetInnOk() (*string, bool)`

GetInnOk returns a tuple with the Inn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInn

`func (o *RecipientInput) SetInn(v string)`

SetInn sets Inn field to given value.

### HasInn

`func (o *RecipientInput) HasInn() bool`

HasInn returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


