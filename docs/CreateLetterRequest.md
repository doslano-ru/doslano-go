# CreateLetterRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Sender** | Pointer to [**SenderInput**](SenderInput.md) | Отправитель. Если не указан — берётся отправитель по умолчанию из профиля аккаунта. | [optional] 
**Recipients** | [**[]RecipientInput**](RecipientInput.md) |  | 
**Content** | [**LetterContent**](LetterContent.md) |  | 
**LetterClass** | Pointer to [**LetterClass**](LetterClass.md) |  | [optional] [default to LETTERCLASS_REGISTERED]
**PromoCode** | Pointer to **string** | Промокод (опционально). | [optional] 
**OnPromoInvalid** | Pointer to **string** | Что делать, если промокод не применился: &#x60;ignore&#x60; — отправить без скидки и вернуть пометку в &#x60;pricing.promo&#x60;; &#x60;reject&#x60; — отклонить (422).  | [optional] [default to "ignore"]
**OnInsufficientFunds** | Pointer to **string** | Что делать при нехватке средств: &#x60;reject&#x60; — отклонить (402), письмо не создаётся; &#x60;hold&#x60; — создать письмо в статусе &#x60;awaiting_payment&#x60;, оно оплатится автоматически при пополнении баланса.  | [optional] [default to "reject"]
**CallbackUrl** | Pointer to **string** | HTTPS-URL для колбеков по этому письму. Если не указан — используйте поллинг. | [optional] 

## Methods

### NewCreateLetterRequest

`func NewCreateLetterRequest(recipients []RecipientInput, content LetterContent, ) *CreateLetterRequest`

NewCreateLetterRequest instantiates a new CreateLetterRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateLetterRequestWithDefaults

`func NewCreateLetterRequestWithDefaults() *CreateLetterRequest`

NewCreateLetterRequestWithDefaults instantiates a new CreateLetterRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSender

`func (o *CreateLetterRequest) GetSender() SenderInput`

GetSender returns the Sender field if non-nil, zero value otherwise.

### GetSenderOk

`func (o *CreateLetterRequest) GetSenderOk() (*SenderInput, bool)`

GetSenderOk returns a tuple with the Sender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSender

`func (o *CreateLetterRequest) SetSender(v SenderInput)`

SetSender sets Sender field to given value.

### HasSender

`func (o *CreateLetterRequest) HasSender() bool`

HasSender returns a boolean if a field has been set.

### GetRecipients

`func (o *CreateLetterRequest) GetRecipients() []RecipientInput`

GetRecipients returns the Recipients field if non-nil, zero value otherwise.

### GetRecipientsOk

`func (o *CreateLetterRequest) GetRecipientsOk() (*[]RecipientInput, bool)`

GetRecipientsOk returns a tuple with the Recipients field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecipients

`func (o *CreateLetterRequest) SetRecipients(v []RecipientInput)`

SetRecipients sets Recipients field to given value.


### GetContent

`func (o *CreateLetterRequest) GetContent() LetterContent`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *CreateLetterRequest) GetContentOk() (*LetterContent, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *CreateLetterRequest) SetContent(v LetterContent)`

SetContent sets Content field to given value.


### GetLetterClass

`func (o *CreateLetterRequest) GetLetterClass() LetterClass`

GetLetterClass returns the LetterClass field if non-nil, zero value otherwise.

### GetLetterClassOk

`func (o *CreateLetterRequest) GetLetterClassOk() (*LetterClass, bool)`

GetLetterClassOk returns a tuple with the LetterClass field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLetterClass

`func (o *CreateLetterRequest) SetLetterClass(v LetterClass)`

SetLetterClass sets LetterClass field to given value.

### HasLetterClass

`func (o *CreateLetterRequest) HasLetterClass() bool`

HasLetterClass returns a boolean if a field has been set.

### GetPromoCode

`func (o *CreateLetterRequest) GetPromoCode() string`

GetPromoCode returns the PromoCode field if non-nil, zero value otherwise.

### GetPromoCodeOk

`func (o *CreateLetterRequest) GetPromoCodeOk() (*string, bool)`

GetPromoCodeOk returns a tuple with the PromoCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromoCode

`func (o *CreateLetterRequest) SetPromoCode(v string)`

SetPromoCode sets PromoCode field to given value.

### HasPromoCode

`func (o *CreateLetterRequest) HasPromoCode() bool`

HasPromoCode returns a boolean if a field has been set.

### GetOnPromoInvalid

`func (o *CreateLetterRequest) GetOnPromoInvalid() string`

GetOnPromoInvalid returns the OnPromoInvalid field if non-nil, zero value otherwise.

### GetOnPromoInvalidOk

`func (o *CreateLetterRequest) GetOnPromoInvalidOk() (*string, bool)`

GetOnPromoInvalidOk returns a tuple with the OnPromoInvalid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOnPromoInvalid

`func (o *CreateLetterRequest) SetOnPromoInvalid(v string)`

SetOnPromoInvalid sets OnPromoInvalid field to given value.

### HasOnPromoInvalid

`func (o *CreateLetterRequest) HasOnPromoInvalid() bool`

HasOnPromoInvalid returns a boolean if a field has been set.

### GetOnInsufficientFunds

`func (o *CreateLetterRequest) GetOnInsufficientFunds() string`

GetOnInsufficientFunds returns the OnInsufficientFunds field if non-nil, zero value otherwise.

### GetOnInsufficientFundsOk

`func (o *CreateLetterRequest) GetOnInsufficientFundsOk() (*string, bool)`

GetOnInsufficientFundsOk returns a tuple with the OnInsufficientFunds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOnInsufficientFunds

`func (o *CreateLetterRequest) SetOnInsufficientFunds(v string)`

SetOnInsufficientFunds sets OnInsufficientFunds field to given value.

### HasOnInsufficientFunds

`func (o *CreateLetterRequest) HasOnInsufficientFunds() bool`

HasOnInsufficientFunds returns a boolean if a field has been set.

### GetCallbackUrl

`func (o *CreateLetterRequest) GetCallbackUrl() string`

GetCallbackUrl returns the CallbackUrl field if non-nil, zero value otherwise.

### GetCallbackUrlOk

`func (o *CreateLetterRequest) GetCallbackUrlOk() (*string, bool)`

GetCallbackUrlOk returns a tuple with the CallbackUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCallbackUrl

`func (o *CreateLetterRequest) SetCallbackUrl(v string)`

SetCallbackUrl sets CallbackUrl field to given value.

### HasCallbackUrl

`func (o *CreateLetterRequest) HasCallbackUrl() bool`

HasCallbackUrl returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


