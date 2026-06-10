# LetterContent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**MainFile** | [**FileSource**](FileSource.md) |  | 
**Attachments** | Pointer to [**[]FileSource**](FileSource.md) |  | [optional] 

## Methods

### NewLetterContent

`func NewLetterContent(mainFile FileSource, ) *LetterContent`

NewLetterContent instantiates a new LetterContent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLetterContentWithDefaults

`func NewLetterContentWithDefaults() *LetterContent`

NewLetterContentWithDefaults instantiates a new LetterContent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMainFile

`func (o *LetterContent) GetMainFile() FileSource`

GetMainFile returns the MainFile field if non-nil, zero value otherwise.

### GetMainFileOk

`func (o *LetterContent) GetMainFileOk() (*FileSource, bool)`

GetMainFileOk returns a tuple with the MainFile field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMainFile

`func (o *LetterContent) SetMainFile(v FileSource)`

SetMainFile sets MainFile field to given value.


### GetAttachments

`func (o *LetterContent) GetAttachments() []FileSource`

GetAttachments returns the Attachments field if non-nil, zero value otherwise.

### GetAttachmentsOk

`func (o *LetterContent) GetAttachmentsOk() (*[]FileSource, bool)`

GetAttachmentsOk returns a tuple with the Attachments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachments

`func (o *LetterContent) SetAttachments(v []FileSource)`

SetAttachments sets Attachments field to given value.

### HasAttachments

`func (o *LetterContent) HasAttachments() bool`

HasAttachments returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


