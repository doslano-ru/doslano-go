# SenderInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** | ФИО или название отправителя. Не указано — из профиля ЛК. | [optional] 
**Address** | Pointer to **string** | Адрес отправителя (строкой; нормализуется). Не указан — из профиля ЛК. | [optional] 
**Email** | Pointer to **string** | Email отправителя (плательщика) для кассового чека. Не указан — из профиля ЛК. | [optional] 
**PartyType** | Pointer to [**PartyType**](PartyType.md) |  | [optional] 
**Inn** | Pointer to **string** | ИНН (для юр. лиц/ИП). Не указан — из профиля ЛК. | [optional] 

## Methods

### NewSenderInput

`func NewSenderInput() *SenderInput`

NewSenderInput instantiates a new SenderInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSenderInputWithDefaults

`func NewSenderInputWithDefaults() *SenderInput`

NewSenderInputWithDefaults instantiates a new SenderInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *SenderInput) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *SenderInput) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *SenderInput) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *SenderInput) HasName() bool`

HasName returns a boolean if a field has been set.

### GetAddress

`func (o *SenderInput) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *SenderInput) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *SenderInput) SetAddress(v string)`

SetAddress sets Address field to given value.

### HasAddress

`func (o *SenderInput) HasAddress() bool`

HasAddress returns a boolean if a field has been set.

### GetEmail

`func (o *SenderInput) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *SenderInput) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *SenderInput) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *SenderInput) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetPartyType

`func (o *SenderInput) GetPartyType() PartyType`

GetPartyType returns the PartyType field if non-nil, zero value otherwise.

### GetPartyTypeOk

`func (o *SenderInput) GetPartyTypeOk() (*PartyType, bool)`

GetPartyTypeOk returns a tuple with the PartyType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartyType

`func (o *SenderInput) SetPartyType(v PartyType)`

SetPartyType sets PartyType field to given value.

### HasPartyType

`func (o *SenderInput) HasPartyType() bool`

HasPartyType returns a boolean if a field has been set.

### GetInn

`func (o *SenderInput) GetInn() string`

GetInn returns the Inn field if non-nil, zero value otherwise.

### GetInnOk

`func (o *SenderInput) GetInnOk() (*string, bool)`

GetInnOk returns a tuple with the Inn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInn

`func (o *SenderInput) SetInn(v string)`

SetInn sets Inn field to given value.

### HasInn

`func (o *SenderInput) HasInn() bool`

HasInn returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


