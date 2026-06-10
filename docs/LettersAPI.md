# \LettersAPI

All URIs are relative to *https://integration.doslano.ru*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateLetter**](LettersAPI.md#CreateLetter) | **Post** /v1/letters | Отправить письмо
[**GetLetter**](LettersAPI.md#GetLetter) | **Get** /v1/letters/{id} | Статус письма
[**GetRecipientTracking**](LettersAPI.md#GetRecipientTracking) | **Get** /v1/letters/{id}/recipients/{recipient_id}/tracking | Трек-события получателя
[**ListLetters**](LettersAPI.md#ListLetters) | **Get** /v1/letters | Список писем



## CreateLetter

> Letter CreateLetter(ctx).CreateLetterRequest(createLetterRequest).IdempotencyKey(idempotencyKey).Execute()

Отправить письмо



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	createLetterRequest := *openapiclient.NewCreateLetterRequest([]openapiclient.RecipientInput{*openapiclient.NewRecipientInput("Name_example", "Address_example")}, *openapiclient.NewLetterContent(*openapiclient.NewFileSource())) // CreateLetterRequest | 
	idempotencyKey := "idempotencyKey_example" // string | Ключ идемпотентности. Повтор с тем же ключом в течение TTL вернёт исходный результат, не создавая письмо повторно. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LettersAPI.CreateLetter(context.Background()).CreateLetterRequest(createLetterRequest).IdempotencyKey(idempotencyKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LettersAPI.CreateLetter``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateLetter`: Letter
	fmt.Fprintf(os.Stdout, "Response from `LettersAPI.CreateLetter`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateLetterRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createLetterRequest** | [**CreateLetterRequest**](CreateLetterRequest.md) |  | 
 **idempotencyKey** | **string** | Ключ идемпотентности. Повтор с тем же ключом в течение TTL вернёт исходный результат, не создавая письмо повторно. | 

### Return type

[**Letter**](Letter.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetLetter

> Letter GetLetter(ctx, id).Execute()

Статус письма



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | Идентификатор письма.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LettersAPI.GetLetter(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LettersAPI.GetLetter``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetLetter`: Letter
	fmt.Fprintf(os.Stdout, "Response from `LettersAPI.GetLetter`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Идентификатор письма. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetLetterRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Letter**](Letter.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetRecipientTracking

> TrackingInfo GetRecipientTracking(ctx, id, recipientId).Execute()

Трек-события получателя



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	id := "id_example" // string | Идентификатор письма.
	recipientId := "recipientId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LettersAPI.GetRecipientTracking(context.Background(), id, recipientId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LettersAPI.GetRecipientTracking``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetRecipientTracking`: TrackingInfo
	fmt.Fprintf(os.Stdout, "Response from `LettersAPI.GetRecipientTracking`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Идентификатор письма. | 
**recipientId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetRecipientTrackingRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**TrackingInfo**](TrackingInfo.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListLetters

> ListLetters200Response ListLetters(ctx).Limit(limit).Offset(offset).Status(status).CreatedFrom(createdFrom).CreatedTo(createdTo).Execute()

Список писем



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	limit := int32(56) // int32 |  (optional) (default to 20)
	offset := int32(56) // int32 |  (optional) (default to 0)
	status := openapiclient.LetterStatus("forming") // LetterStatus |  (optional)
	createdFrom := time.Now() // time.Time |  (optional)
	createdTo := time.Now() // time.Time |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LettersAPI.ListLetters(context.Background()).Limit(limit).Offset(offset).Status(status).CreatedFrom(createdFrom).CreatedTo(createdTo).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LettersAPI.ListLetters``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListLetters`: ListLetters200Response
	fmt.Fprintf(os.Stdout, "Response from `LettersAPI.ListLetters`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListLettersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **int32** |  | [default to 20]
 **offset** | **int32** |  | [default to 0]
 **status** | [**LetterStatus**](LetterStatus.md) |  | 
 **createdFrom** | **time.Time** |  | 
 **createdTo** | **time.Time** |  | 

### Return type

[**ListLetters200Response**](ListLetters200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

