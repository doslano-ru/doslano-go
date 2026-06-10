# FileSource

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Base64** | Pointer to **string** | PDF в base64. | [optional] 
**Url** | Pointer to **string** | HTTPS-ссылка на PDF (скачиваем потоково). | [optional] 
**Filename** | Pointer to **string** | Имя файла (опционально, для отображения). | [optional] 

## Methods

### NewFileSource

`func NewFileSource() *FileSource`

NewFileSource instantiates a new FileSource object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFileSourceWithDefaults

`func NewFileSourceWithDefaults() *FileSource`

NewFileSourceWithDefaults instantiates a new FileSource object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBase64

`func (o *FileSource) GetBase64() string`

GetBase64 returns the Base64 field if non-nil, zero value otherwise.

### GetBase64Ok

`func (o *FileSource) GetBase64Ok() (*string, bool)`

GetBase64Ok returns a tuple with the Base64 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBase64

`func (o *FileSource) SetBase64(v string)`

SetBase64 sets Base64 field to given value.

### HasBase64

`func (o *FileSource) HasBase64() bool`

HasBase64 returns a boolean if a field has been set.

### GetUrl

`func (o *FileSource) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *FileSource) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *FileSource) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *FileSource) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### GetFilename

`func (o *FileSource) GetFilename() string`

GetFilename returns the Filename field if non-nil, zero value otherwise.

### GetFilenameOk

`func (o *FileSource) GetFilenameOk() (*string, bool)`

GetFilenameOk returns a tuple with the Filename field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilename

`func (o *FileSource) SetFilename(v string)`

SetFilename sets Filename field to given value.

### HasFilename

`func (o *FileSource) HasFilename() bool`

HasFilename returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


