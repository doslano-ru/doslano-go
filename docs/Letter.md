# Letter

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Channel** | **string** | Канал создания письма — &#x60;api&#x60; (этот API) или &#x60;web&#x60; (личный кабинет). | 
**Status** | [**LetterStatus**](LetterStatus.md) |  | 
**CreatedAt** | **time.Time** |  | 
**Sender** | Pointer to [**Party**](Party.md) |  | [optional] 
**Recipients** | [**[]Recipient**](Recipient.md) |  | 
**Pricing** | [**Pricing**](Pricing.md) |  | 
**Payment** | Pointer to [**PaymentResult**](PaymentResult.md) |  | [optional] 
**CallbackUrl** | Pointer to **string** |  | [optional] 

## Methods

### NewLetter

`func NewLetter(id string, channel string, status LetterStatus, createdAt time.Time, recipients []Recipient, pricing Pricing, ) *Letter`

NewLetter instantiates a new Letter object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLetterWithDefaults

`func NewLetterWithDefaults() *Letter`

NewLetterWithDefaults instantiates a new Letter object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Letter) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Letter) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Letter) SetId(v string)`

SetId sets Id field to given value.


### GetChannel

`func (o *Letter) GetChannel() string`

GetChannel returns the Channel field if non-nil, zero value otherwise.

### GetChannelOk

`func (o *Letter) GetChannelOk() (*string, bool)`

GetChannelOk returns a tuple with the Channel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChannel

`func (o *Letter) SetChannel(v string)`

SetChannel sets Channel field to given value.


### GetStatus

`func (o *Letter) GetStatus() LetterStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Letter) GetStatusOk() (*LetterStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Letter) SetStatus(v LetterStatus)`

SetStatus sets Status field to given value.


### GetCreatedAt

`func (o *Letter) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Letter) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Letter) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetSender

`func (o *Letter) GetSender() Party`

GetSender returns the Sender field if non-nil, zero value otherwise.

### GetSenderOk

`func (o *Letter) GetSenderOk() (*Party, bool)`

GetSenderOk returns a tuple with the Sender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSender

`func (o *Letter) SetSender(v Party)`

SetSender sets Sender field to given value.

### HasSender

`func (o *Letter) HasSender() bool`

HasSender returns a boolean if a field has been set.

### GetRecipients

`func (o *Letter) GetRecipients() []Recipient`

GetRecipients returns the Recipients field if non-nil, zero value otherwise.

### GetRecipientsOk

`func (o *Letter) GetRecipientsOk() (*[]Recipient, bool)`

GetRecipientsOk returns a tuple with the Recipients field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecipients

`func (o *Letter) SetRecipients(v []Recipient)`

SetRecipients sets Recipients field to given value.


### GetPricing

`func (o *Letter) GetPricing() Pricing`

GetPricing returns the Pricing field if non-nil, zero value otherwise.

### GetPricingOk

`func (o *Letter) GetPricingOk() (*Pricing, bool)`

GetPricingOk returns a tuple with the Pricing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPricing

`func (o *Letter) SetPricing(v Pricing)`

SetPricing sets Pricing field to given value.


### GetPayment

`func (o *Letter) GetPayment() PaymentResult`

GetPayment returns the Payment field if non-nil, zero value otherwise.

### GetPaymentOk

`func (o *Letter) GetPaymentOk() (*PaymentResult, bool)`

GetPaymentOk returns a tuple with the Payment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPayment

`func (o *Letter) SetPayment(v PaymentResult)`

SetPayment sets Payment field to given value.

### HasPayment

`func (o *Letter) HasPayment() bool`

HasPayment returns a boolean if a field has been set.

### GetCallbackUrl

`func (o *Letter) GetCallbackUrl() string`

GetCallbackUrl returns the CallbackUrl field if non-nil, zero value otherwise.

### GetCallbackUrlOk

`func (o *Letter) GetCallbackUrlOk() (*string, bool)`

GetCallbackUrlOk returns a tuple with the CallbackUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCallbackUrl

`func (o *Letter) SetCallbackUrl(v string)`

SetCallbackUrl sets CallbackUrl field to given value.

### HasCallbackUrl

`func (o *Letter) HasCallbackUrl() bool`

HasCallbackUrl returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


