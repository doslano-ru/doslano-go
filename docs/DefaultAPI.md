# \DefaultAPI

All URIs are relative to *https://integration.doslano.ru*

Method | HTTP request | Description
------------- | ------------- | -------------
[**OnLetterStatusChanged**](DefaultAPI.md#OnLetterStatusChanged) | **Post** /letterStatusChanged | Колбек на финальный статус



## OnLetterStatusChanged

> OnLetterStatusChanged(ctx).WebhookEvent(webhookEvent).Execute()

Колбек на финальный статус



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/doslano-ru/doslano-go"
)

func main() {
	webhookEvent :=  // WebhookEvent | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DefaultAPI.OnLetterStatusChanged(context.Background()).WebhookEvent(webhookEvent).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.OnLetterStatusChanged``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOnLetterStatusChangedRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **webhookEvent** | [**WebhookEvent**](WebhookEvent.md) |  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

