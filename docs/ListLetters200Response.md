# ListLetters200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**[]Letter**](Letter.md) |  | 
**HasMore** | **bool** |  | 

## Methods

### NewListLetters200Response

`func NewListLetters200Response(data []Letter, hasMore bool, ) *ListLetters200Response`

NewListLetters200Response instantiates a new ListLetters200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListLetters200ResponseWithDefaults

`func NewListLetters200ResponseWithDefaults() *ListLetters200Response`

NewListLetters200ResponseWithDefaults instantiates a new ListLetters200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *ListLetters200Response) GetData() []Letter`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ListLetters200Response) GetDataOk() (*[]Letter, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ListLetters200Response) SetData(v []Letter)`

SetData sets Data field to given value.


### GetHasMore

`func (o *ListLetters200Response) GetHasMore() bool`

GetHasMore returns the HasMore field if non-nil, zero value otherwise.

### GetHasMoreOk

`func (o *ListLetters200Response) GetHasMoreOk() (*bool, bool)`

GetHasMoreOk returns a tuple with the HasMore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasMore

`func (o *ListLetters200Response) SetHasMore(v bool)`

SetHasMore sets HasMore field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


