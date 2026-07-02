# RecipientInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | ФИО или название получателя. При resolve_address_by_inn&#x3D;true ПЕРЕЗАПИСЫВАЕТСЯ наименованием из ЕГРЮЛ. | 
**Address** | Pointer to **string** | Адрес получателя (строкой; нормализуется на нашей стороне). Можно опустить при resolve_address_by_inn&#x3D;true. | [optional] 
**PartyType** | Pointer to [**PartyType**](PartyType.md) |  | [optional] 
**Inn** | Pointer to **string** | ИНН (10 цифр). | [optional] 
**Email** | Pointer to **string** | Email получателя для уведомления-копии (опционально). После отправки письма получателю на этот адрес приходит письмо со ссылкой на электронную версию (страница /receive). Пустой/опущен — уведомление не шлётся; адрес указывает отправитель и отвечает за корректность. | [optional] 
**ResolveAddressByInn** | Pointer to **bool** | Авто-резолв адреса по ИНН из ЕГРЮЛ. Работает только для party_type&#x3D;organization с заданным inn: адрес и наименование берутся из реестра (DaData findById/party, головная организация), address можно не передавать. Если резолв не удался и address не передан — 422 recipient_address_unresolved; флаг без inn или не для organization — 422 recipient_resolve_requires_inn. Если передан и address — он fallback при неудаче резолва. | [optional] [default to false]
**AllowAddressTruncation** | Pointer to **bool** | Согласие на усечение адреса до номера дома, если полный адрес не проходит в Почте России (ЕПС валидирует адреса по ГАР, где помещение/офис/комната часто не зарегистрированы). Усечённая форма готовится автоматически (только когда дом распознан ФИАС). Триггеры: провал валидации адреса Почтой — проверка не блокирует письмо, пока есть варианты (административная форма → муниципальная → усечённая до дома), — и ошибка сохранения отправления SHIPMENT_ERROR — варианты перебираются сразу, без повторных попыток отправки. (Ошибка регистрации EPS_61_INVALID_ADDRESS обрабатывается независимо существующим механизмом муниципального fallback-адреса, без усечения.) Письмо, ушедшее на усечённый адрес, помечается &#x60;address_truncation_applied: true&#x60; у получателя. Если не помог ни один вариант — стандартная ошибка (422 при создании либо &#x60;failed&#x60; + возврат средств). | [optional] [default to false]

## Methods

### NewRecipientInput

`func NewRecipientInput(name string, ) *RecipientInput`

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

### HasAddress

`func (o *RecipientInput) HasAddress() bool`

HasAddress returns a boolean if a field has been set.

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

### GetEmail

`func (o *RecipientInput) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *RecipientInput) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *RecipientInput) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *RecipientInput) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetResolveAddressByInn

`func (o *RecipientInput) GetResolveAddressByInn() bool`

GetResolveAddressByInn returns the ResolveAddressByInn field if non-nil, zero value otherwise.

### GetResolveAddressByInnOk

`func (o *RecipientInput) GetResolveAddressByInnOk() (*bool, bool)`

GetResolveAddressByInnOk returns a tuple with the ResolveAddressByInn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResolveAddressByInn

`func (o *RecipientInput) SetResolveAddressByInn(v bool)`

SetResolveAddressByInn sets ResolveAddressByInn field to given value.

### HasResolveAddressByInn

`func (o *RecipientInput) HasResolveAddressByInn() bool`

HasResolveAddressByInn returns a boolean if a field has been set.

### GetAllowAddressTruncation

`func (o *RecipientInput) GetAllowAddressTruncation() bool`

GetAllowAddressTruncation returns the AllowAddressTruncation field if non-nil, zero value otherwise.

### GetAllowAddressTruncationOk

`func (o *RecipientInput) GetAllowAddressTruncationOk() (*bool, bool)`

GetAllowAddressTruncationOk returns a tuple with the AllowAddressTruncation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowAddressTruncation

`func (o *RecipientInput) SetAllowAddressTruncation(v bool)`

SetAllowAddressTruncation sets AllowAddressTruncation field to given value.

### HasAllowAddressTruncation

`func (o *RecipientInput) HasAllowAddressTruncation() bool`

HasAllowAddressTruncation returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


