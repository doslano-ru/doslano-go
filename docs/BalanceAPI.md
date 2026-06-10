# \BalanceAPI

All URIs are relative to *https://integration.doslano.ru*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetBalance**](BalanceAPI.md#GetBalance) | **Get** /v1/balance | Баланс аккаунта



## GetBalance

> Balance GetBalance(ctx).Execute()

Баланс аккаунта



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BalanceAPI.GetBalance(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BalanceAPI.GetBalance``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetBalance`: Balance
	fmt.Fprintf(os.Stdout, "Response from `BalanceAPI.GetBalance`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetBalanceRequest struct via the builder pattern


### Return type

[**Balance**](Balance.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/problem+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

