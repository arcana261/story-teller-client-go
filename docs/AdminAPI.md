# \AdminAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ClearNodeEnrichmentV1AdminStoryStoryIdNodeNodeIdClearEnrichmentPost**](AdminAPI.md#ClearNodeEnrichmentV1AdminStoryStoryIdNodeNodeIdClearEnrichmentPost) | **Post** /v1/admin/story/{story_id}/node/{node_id}/clear-enrichment | Clear Node Enrichment
[**CreateTosVersionV1AdminTermsPost**](AdminAPI.md#CreateTosVersionV1AdminTermsPost) | **Post** /v1/admin/terms | Create Tos Version
[**GetStoryV1AdminStoryStoryIdGet**](AdminAPI.md#GetStoryV1AdminStoryStoryIdGet) | **Get** /v1/admin/story/{story_id} | Get Story
[**GetTenantV1AdminTenantTenantIdGet**](AdminAPI.md#GetTenantV1AdminTenantTenantIdGet) | **Get** /v1/admin/tenant/{tenant_id} | Get Tenant
[**ImportStoryV1AdminStoryImportPost**](AdminAPI.md#ImportStoryV1AdminStoryImportPost) | **Post** /v1/admin/story/import | Import Story
[**ListTenantsV1AdminTenantsGet**](AdminAPI.md#ListTenantsV1AdminTenantsGet) | **Get** /v1/admin/tenants | List Tenants
[**ListTosVersionsV1AdminTermsGet**](AdminAPI.md#ListTosVersionsV1AdminTermsGet) | **Get** /v1/admin/terms | List Tos Versions
[**OffboardTenantV1AdminTenantTenantIdDelete**](AdminAPI.md#OffboardTenantV1AdminTenantTenantIdDelete) | **Delete** /v1/admin/tenant/{tenant_id} | Offboard Tenant
[**RegisterTenantV1AdminTenantRegisterPost**](AdminAPI.md#RegisterTenantV1AdminTenantRegisterPost) | **Post** /v1/admin/tenant/register | Register Tenant
[**RotateAnthropicKeyV1AdminTenantTenantIdAnthropicKeyPatch**](AdminAPI.md#RotateAnthropicKeyV1AdminTenantTenantIdAnthropicKeyPatch) | **Patch** /v1/admin/tenant/{tenant_id}/anthropic-key | Rotate Anthropic Key
[**ScaffoldStoryV1AdminStoryScaffoldPost**](AdminAPI.md#ScaffoldStoryV1AdminStoryScaffoldPost) | **Post** /v1/admin/story/scaffold | Scaffold Story
[**SoftDeleteStoryV1AdminStoryStoryIdDelete**](AdminAPI.md#SoftDeleteStoryV1AdminStoryStoryIdDelete) | **Delete** /v1/admin/story/{story_id} | Soft Delete Story



## ClearNodeEnrichmentV1AdminStoryStoryIdNodeNodeIdClearEnrichmentPost

> NodeClearEnrichmentResponse ClearNodeEnrichmentV1AdminStoryStoryIdNodeNodeIdClearEnrichmentPost(ctx, storyId, nodeId).NodeClearEnrichmentRequest(nodeClearEnrichmentRequest).Execute()

Clear Node Enrichment



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/arcana261/story-teller-client-go"
)

func main() {
	storyId := "storyId_example" // string | 
	nodeId := "nodeId_example" // string | 
	nodeClearEnrichmentRequest := *openapiclient.NewNodeClearEnrichmentRequest("Reason_example", "ActorAdminId_example") // NodeClearEnrichmentRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AdminAPI.ClearNodeEnrichmentV1AdminStoryStoryIdNodeNodeIdClearEnrichmentPost(context.Background(), storyId, nodeId).NodeClearEnrichmentRequest(nodeClearEnrichmentRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AdminAPI.ClearNodeEnrichmentV1AdminStoryStoryIdNodeNodeIdClearEnrichmentPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ClearNodeEnrichmentV1AdminStoryStoryIdNodeNodeIdClearEnrichmentPost`: NodeClearEnrichmentResponse
	fmt.Fprintf(os.Stdout, "Response from `AdminAPI.ClearNodeEnrichmentV1AdminStoryStoryIdNodeNodeIdClearEnrichmentPost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**storyId** | **string** |  | 
**nodeId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiClearNodeEnrichmentV1AdminStoryStoryIdNodeNodeIdClearEnrichmentPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **nodeClearEnrichmentRequest** | [**NodeClearEnrichmentRequest**](NodeClearEnrichmentRequest.md) |  | 

### Return type

[**NodeClearEnrichmentResponse**](NodeClearEnrichmentResponse.md)

### Authorization

[AdminBearer](../README.md#AdminBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateTosVersionV1AdminTermsPost

> ToSVersionResponse CreateTosVersionV1AdminTermsPost(ctx).CreateToSVersionRequest(createToSVersionRequest).Execute()

Create Tos Version

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/arcana261/story-teller-client-go"
)

func main() {
	createToSVersionRequest := *openapiclient.NewCreateToSVersionRequest("VersionNumber_example", "Content_example", "EffectiveDate_example") // CreateToSVersionRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AdminAPI.CreateTosVersionV1AdminTermsPost(context.Background()).CreateToSVersionRequest(createToSVersionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AdminAPI.CreateTosVersionV1AdminTermsPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateTosVersionV1AdminTermsPost`: ToSVersionResponse
	fmt.Fprintf(os.Stdout, "Response from `AdminAPI.CreateTosVersionV1AdminTermsPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateTosVersionV1AdminTermsPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createToSVersionRequest** | [**CreateToSVersionRequest**](CreateToSVersionRequest.md) |  | 

### Return type

[**ToSVersionResponse**](ToSVersionResponse.md)

### Authorization

[AdminBearer](../README.md#AdminBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetStoryV1AdminStoryStoryIdGet

> StoryDetailResponse GetStoryV1AdminStoryStoryIdGet(ctx, storyId).Execute()

Get Story



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/arcana261/story-teller-client-go"
)

func main() {
	storyId := "storyId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AdminAPI.GetStoryV1AdminStoryStoryIdGet(context.Background(), storyId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AdminAPI.GetStoryV1AdminStoryStoryIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetStoryV1AdminStoryStoryIdGet`: StoryDetailResponse
	fmt.Fprintf(os.Stdout, "Response from `AdminAPI.GetStoryV1AdminStoryStoryIdGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**storyId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetStoryV1AdminStoryStoryIdGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**StoryDetailResponse**](StoryDetailResponse.md)

### Authorization

[AdminBearer](../README.md#AdminBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetTenantV1AdminTenantTenantIdGet

> TenantResponse GetTenantV1AdminTenantTenantIdGet(ctx, tenantId).Execute()

Get Tenant

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/arcana261/story-teller-client-go"
)

func main() {
	tenantId := "tenantId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AdminAPI.GetTenantV1AdminTenantTenantIdGet(context.Background(), tenantId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AdminAPI.GetTenantV1AdminTenantTenantIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTenantV1AdminTenantTenantIdGet`: TenantResponse
	fmt.Fprintf(os.Stdout, "Response from `AdminAPI.GetTenantV1AdminTenantTenantIdGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**tenantId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetTenantV1AdminTenantTenantIdGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**TenantResponse**](TenantResponse.md)

### Authorization

[AdminBearer](../README.md#AdminBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ImportStoryV1AdminStoryImportPost

> interface{} ImportStoryV1AdminStoryImportPost(ctx).Execute()

Import Story



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/arcana261/story-teller-client-go"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AdminAPI.ImportStoryV1AdminStoryImportPost(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AdminAPI.ImportStoryV1AdminStoryImportPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ImportStoryV1AdminStoryImportPost`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `AdminAPI.ImportStoryV1AdminStoryImportPost`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiImportStoryV1AdminStoryImportPostRequest struct via the builder pattern


### Return type

**interface{}**

### Authorization

[AdminBearer](../README.md#AdminBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListTenantsV1AdminTenantsGet

> []TenantResponse ListTenantsV1AdminTenantsGet(ctx).Offset(offset).Limit(limit).Execute()

List Tenants

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/arcana261/story-teller-client-go"
)

func main() {
	offset := int32(56) // int32 |  (optional) (default to 0)
	limit := int32(56) // int32 |  (optional) (default to 50)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AdminAPI.ListTenantsV1AdminTenantsGet(context.Background()).Offset(offset).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AdminAPI.ListTenantsV1AdminTenantsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListTenantsV1AdminTenantsGet`: []TenantResponse
	fmt.Fprintf(os.Stdout, "Response from `AdminAPI.ListTenantsV1AdminTenantsGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListTenantsV1AdminTenantsGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **offset** | **int32** |  | [default to 0]
 **limit** | **int32** |  | [default to 50]

### Return type

[**[]TenantResponse**](TenantResponse.md)

### Authorization

[AdminBearer](../README.md#AdminBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListTosVersionsV1AdminTermsGet

> []ToSVersionResponse ListTosVersionsV1AdminTermsGet(ctx).Execute()

List Tos Versions

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/arcana261/story-teller-client-go"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AdminAPI.ListTosVersionsV1AdminTermsGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AdminAPI.ListTosVersionsV1AdminTermsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListTosVersionsV1AdminTermsGet`: []ToSVersionResponse
	fmt.Fprintf(os.Stdout, "Response from `AdminAPI.ListTosVersionsV1AdminTermsGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListTosVersionsV1AdminTermsGetRequest struct via the builder pattern


### Return type

[**[]ToSVersionResponse**](ToSVersionResponse.md)

### Authorization

[AdminBearer](../README.md#AdminBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OffboardTenantV1AdminTenantTenantIdDelete

> OffboardTenantV1AdminTenantTenantIdDelete(ctx, tenantId).Execute()

Offboard Tenant

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/arcana261/story-teller-client-go"
)

func main() {
	tenantId := "tenantId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AdminAPI.OffboardTenantV1AdminTenantTenantIdDelete(context.Background(), tenantId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AdminAPI.OffboardTenantV1AdminTenantTenantIdDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**tenantId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiOffboardTenantV1AdminTenantTenantIdDeleteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[AdminBearer](../README.md#AdminBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RegisterTenantV1AdminTenantRegisterPost

> TenantRegistrationResponse RegisterTenantV1AdminTenantRegisterPost(ctx).TenantRegistrationRequest(tenantRegistrationRequest).Execute()

Register Tenant

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/arcana261/story-teller-client-go"
)

func main() {
	tenantRegistrationRequest := *openapiclient.NewTenantRegistrationRequest("Name_example", "ContactEmail_example", "AnthropicApiKey_example", "BillingCountry_example") // TenantRegistrationRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AdminAPI.RegisterTenantV1AdminTenantRegisterPost(context.Background()).TenantRegistrationRequest(tenantRegistrationRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AdminAPI.RegisterTenantV1AdminTenantRegisterPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RegisterTenantV1AdminTenantRegisterPost`: TenantRegistrationResponse
	fmt.Fprintf(os.Stdout, "Response from `AdminAPI.RegisterTenantV1AdminTenantRegisterPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRegisterTenantV1AdminTenantRegisterPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **tenantRegistrationRequest** | [**TenantRegistrationRequest**](TenantRegistrationRequest.md) |  | 

### Return type

[**TenantRegistrationResponse**](TenantRegistrationResponse.md)

### Authorization

[AdminBearer](../README.md#AdminBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RotateAnthropicKeyV1AdminTenantTenantIdAnthropicKeyPatch

> RotateAnthropicKeyV1AdminTenantTenantIdAnthropicKeyPatch(ctx, tenantId).RotateAnthropicKeyRequest(rotateAnthropicKeyRequest).Execute()

Rotate Anthropic Key

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/arcana261/story-teller-client-go"
)

func main() {
	tenantId := "tenantId_example" // string | 
	rotateAnthropicKeyRequest := *openapiclient.NewRotateAnthropicKeyRequest("AnthropicApiKey_example") // RotateAnthropicKeyRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AdminAPI.RotateAnthropicKeyV1AdminTenantTenantIdAnthropicKeyPatch(context.Background(), tenantId).RotateAnthropicKeyRequest(rotateAnthropicKeyRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AdminAPI.RotateAnthropicKeyV1AdminTenantTenantIdAnthropicKeyPatch``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**tenantId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRotateAnthropicKeyV1AdminTenantTenantIdAnthropicKeyPatchRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **rotateAnthropicKeyRequest** | [**RotateAnthropicKeyRequest**](RotateAnthropicKeyRequest.md) |  | 

### Return type

 (empty response body)

### Authorization

[AdminBearer](../README.md#AdminBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ScaffoldStoryV1AdminStoryScaffoldPost

> ScaffoldStoryV1AdminStoryScaffoldPost(ctx).Execute()

Scaffold Story

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/arcana261/story-teller-client-go"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AdminAPI.ScaffoldStoryV1AdminStoryScaffoldPost(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AdminAPI.ScaffoldStoryV1AdminStoryScaffoldPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiScaffoldStoryV1AdminStoryScaffoldPostRequest struct via the builder pattern


### Return type

 (empty response body)

### Authorization

[AdminBearer](../README.md#AdminBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SoftDeleteStoryV1AdminStoryStoryIdDelete

> SoftDeleteStoryV1AdminStoryStoryIdDelete(ctx, storyId).Execute()

Soft Delete Story



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/arcana261/story-teller-client-go"
)

func main() {
	storyId := "storyId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AdminAPI.SoftDeleteStoryV1AdminStoryStoryIdDelete(context.Background(), storyId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AdminAPI.SoftDeleteStoryV1AdminStoryStoryIdDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**storyId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSoftDeleteStoryV1AdminStoryStoryIdDeleteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[AdminBearer](../README.md#AdminBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

