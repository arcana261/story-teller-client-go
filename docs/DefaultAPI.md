# \DefaultAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**V1AdminStoryImportPost**](DefaultAPI.md#V1AdminStoryImportPost) | **Post** /v1/admin/story/import | Import a full story graph.
[**V1AdminStoryScaffoldPost**](DefaultAPI.md#V1AdminStoryScaffoldPost) | **Post** /v1/admin/story/scaffold | Create a development sample story.
[**V1AdminStoryStoryIdDelete**](DefaultAPI.md#V1AdminStoryStoryIdDelete) | **Delete** /v1/admin/story/{story_id} | Delete a story as an administrator.
[**V1AdminStoryStoryIdGet**](DefaultAPI.md#V1AdminStoryStoryIdGet) | **Get** /v1/admin/story/{story_id} | Read an authored story.
[**V1AdminStoryStoryIdNodeNodeIdClearEnrichmentPost**](DefaultAPI.md#V1AdminStoryStoryIdNodeNodeIdClearEnrichmentPost) | **Post** /v1/admin/story/{story_id}/node/{node_id}/clear-enrichment | Clear generated enrichment metadata from a node.
[**V1AdminTenantRegisterPost**](DefaultAPI.md#V1AdminTenantRegisterPost) | **Post** /v1/admin/tenant/register | Register a tenant and issue its API key.
[**V1AdminTenantTenantIdDelete**](DefaultAPI.md#V1AdminTenantTenantIdDelete) | **Delete** /v1/admin/tenant/{tenant_id} | Delete a tenant.
[**V1AdminTenantTenantIdGet**](DefaultAPI.md#V1AdminTenantTenantIdGet) | **Get** /v1/admin/tenant/{tenant_id} | Read tenant details.
[**V1AdminTenantTenantIdLitellmKeyPatch**](DefaultAPI.md#V1AdminTenantTenantIdLitellmKeyPatch) | **Patch** /v1/admin/tenant/{tenant_id}/litellm-key | Rotate tenant LiteLLM key metadata.
[**V1AdminTenantTenantIdLlmKeyGet**](DefaultAPI.md#V1AdminTenantTenantIdLlmKeyGet) | **Get** /v1/admin/tenant/{tenant_id}/llm-key | Read tenant LiteLLM key status.
[**V1AdminTenantTenantIdReprovisionLlmKeyPost**](DefaultAPI.md#V1AdminTenantTenantIdReprovisionLlmKeyPost) | **Post** /v1/admin/tenant/{tenant_id}/reprovision-llm-key | Reprovision a tenant LiteLLM virtual key.
[**V1AdminTenantsGet**](DefaultAPI.md#V1AdminTenantsGet) | **Get** /v1/admin/tenants | List tenants.
[**V1AdminTermsGet**](DefaultAPI.md#V1AdminTermsGet) | **Get** /v1/admin/terms | List Terms of Service versions.
[**V1AdminTermsPost**](DefaultAPI.md#V1AdminTermsPost) | **Post** /v1/admin/terms | Create a Terms of Service version.
[**V1AuthoringJobsJobIdGet**](DefaultAPI.md#V1AuthoringJobsJobIdGet) | **Get** /v1/authoring/jobs/{job_id} | Read async authoring job status.
[**V1AuthoringJobsJobIdStreamGet**](DefaultAPI.md#V1AuthoringJobsJobIdStreamGet) | **Get** /v1/authoring/jobs/{job_id}/stream | Stream async authoring job status events.
[**V1AuthoringStoriesGet**](DefaultAPI.md#V1AuthoringStoriesGet) | **Get** /v1/authoring/stories | List authored stories.
[**V1AuthoringStoriesPost**](DefaultAPI.md#V1AuthoringStoriesPost) | **Post** /v1/authoring/stories | Create a story synchronously in development or enqueue async generation.
[**V1AuthoringStoriesStoryIdDelete**](DefaultAPI.md#V1AuthoringStoriesStoryIdDelete) | **Delete** /v1/authoring/stories/{story_id} | Delete an authored story.
[**V1AuthoringStoriesStoryIdExplorationNodesGet**](DefaultAPI.md#V1AuthoringStoriesStoryIdExplorationNodesGet) | **Get** /v1/authoring/stories/{story_id}/exploration-nodes | List authored exploration nodes.
[**V1AuthoringStoriesStoryIdExplorationNodesNodeIdGet**](DefaultAPI.md#V1AuthoringStoriesStoryIdExplorationNodesNodeIdGet) | **Get** /v1/authoring/stories/{story_id}/exploration-nodes/{node_id} | Read authored exploration node details.
[**V1AuthoringStoriesStoryIdExplorationNodesNodeIdPatch**](DefaultAPI.md#V1AuthoringStoriesStoryIdExplorationNodesNodeIdPatch) | **Patch** /v1/authoring/stories/{story_id}/exploration-nodes/{node_id} | Update authored exploration-node controls.
[**V1AuthoringStoriesStoryIdGet**](DefaultAPI.md#V1AuthoringStoriesStoryIdGet) | **Get** /v1/authoring/stories/{story_id} | Read authored story details.
[**V1AuthoringStoriesStoryIdGraphGet**](DefaultAPI.md#V1AuthoringStoriesStoryIdGraphGet) | **Get** /v1/authoring/stories/{story_id}/graph | Read authored story graph topology.
[**V1AuthoringStoriesStoryIdPathsGet**](DefaultAPI.md#V1AuthoringStoriesStoryIdPathsGet) | **Get** /v1/authoring/stories/{story_id}/paths | List all authored story paths.
[**V1HealthGet**](DefaultAPI.md#V1HealthGet) | **Get** /v1/health | Check API, Postgres, and Redis health.
[**V1PlayerPlayerIdDataExportGet**](DefaultAPI.md#V1PlayerPlayerIdDataExportGet) | **Get** /v1/player/{player_id}/data-export | Export stored player data.
[**V1PlayerPlayerIdDelete**](DefaultAPI.md#V1PlayerPlayerIdDelete) | **Delete** /v1/player/{player_id} | Erase stored player data.
[**V1PlayerPlayerIdStoryStoryIdWarningsAcknowledgePost**](DefaultAPI.md#V1PlayerPlayerIdStoryStoryIdWarningsAcknowledgePost) | **Post** /v1/player/{player_id}/story/{story_id}/warnings/acknowledge | Acknowledge content warnings for a player story session.
[**V1PlayerPlayerIdTosStatusGet**](DefaultAPI.md#V1PlayerPlayerIdTosStatusGet) | **Get** /v1/player/{player_id}/tos-status | Read player Terms of Service acceptance status.
[**V1StoriesGet**](DefaultAPI.md#V1StoriesGet) | **Get** /v1/stories | List playable stories for the current tenant.
[**V1StoryStoryIdChoicePost**](DefaultAPI.md#V1StoryStoryIdChoicePost) | **Post** /v1/story/{story_id}/choice | Advance the current session by choosing a structured choice.
[**V1StoryStoryIdExplorationNodesGet**](DefaultAPI.md#V1StoryStoryIdExplorationNodesGet) | **Get** /v1/story/{story_id}/exploration-nodes | List exploration nodes available at the current story node.
[**V1StoryStoryIdExplorationNodesNodeIdPickDelete**](DefaultAPI.md#V1StoryStoryIdExplorationNodesNodeIdPickDelete) | **Delete** /v1/story/{story_id}/exploration-nodes/{node_id}/pick | Remove an exploration-node pick from the current session.
[**V1StoryStoryIdExplorationNodesNodeIdPickPost**](DefaultAPI.md#V1StoryStoryIdExplorationNodesNodeIdPickPost) | **Post** /v1/story/{story_id}/exploration-nodes/{node_id}/pick | Pick an exploration node for the current session.
[**V1StoryStoryIdExplorationStateGet**](DefaultAPI.md#V1StoryStoryIdExplorationStateGet) | **Get** /v1/story/{story_id}/exploration-state | Read exploration state for the current session.
[**V1StoryStoryIdExplorePost**](DefaultAPI.md#V1StoryStoryIdExplorePost) | **Post** /v1/story/{story_id}/explore | Ask an exploration question at the current story node.
[**V1StoryStoryIdFreeTextPost**](DefaultAPI.md#V1StoryStoryIdFreeTextPost) | **Post** /v1/story/{story_id}/free-text | Continue the story from free text input using SSE events.
[**V1StoryStoryIdGraphGet**](DefaultAPI.md#V1StoryStoryIdGraphGet) | **Get** /v1/story/{story_id}/graph | Read story graph topology.
[**V1StoryStoryIdNodeNodeIdArcGet**](DefaultAPI.md#V1StoryStoryIdNodeNodeIdArcGet) | **Get** /v1/story/{story_id}/node/{node_id}/arc | Read drama arc analysis for a story node.
[**V1StoryStoryIdNodeNodeIdGet**](DefaultAPI.md#V1StoryStoryIdNodeNodeIdGet) | **Get** /v1/story/{story_id}/node/{node_id} | Read a story node.
[**V1StoryStoryIdPathsGet**](DefaultAPI.md#V1StoryStoryIdPathsGet) | **Get** /v1/story/{story_id}/paths | List all story paths.
[**V1StoryStoryIdSessionEntityIndexGet**](DefaultAPI.md#V1StoryStoryIdSessionEntityIndexGet) | **Get** /v1/story/{story_id}/session/entity-index | List discovered entity index entries for the current session.
[**V1StoryStoryIdSessionGet**](DefaultAPI.md#V1StoryStoryIdSessionGet) | **Get** /v1/story/{story_id}/session | Get or create the current player session.
[**V1StoryStoryIdSessionLockDelete**](DefaultAPI.md#V1StoryStoryIdSessionLockDelete) | **Delete** /v1/story/{story_id}/session/lock | Release a session lock.
[**V1StoryStoryIdSessionResetPost**](DefaultAPI.md#V1StoryStoryIdSessionResetPost) | **Post** /v1/story/{story_id}/session/reset | Reset a completed or forced player session.
[**V1TermsAcceptPost**](DefaultAPI.md#V1TermsAcceptPost) | **Post** /v1/terms/accept | Accept the current Terms of Service for the current player.
[**V1TermsGet**](DefaultAPI.md#V1TermsGet) | **Get** /v1/terms | Read the current Terms of Service version.



## V1AdminStoryImportPost

> V1AdminStoryImportPost201Response V1AdminStoryImportPost(ctx).RequestBody(requestBody).Execute()

Import a full story graph.

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
	requestBody := map[string]map[string]interface{}{"key": map[string]interface{}{"key": interface{}(123)}} // map[string]map[string]interface{} | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.V1AdminStoryImportPost(context.Background()).RequestBody(requestBody).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.V1AdminStoryImportPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1AdminStoryImportPost`: V1AdminStoryImportPost201Response
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.V1AdminStoryImportPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1AdminStoryImportPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **requestBody** | **map[string]map[string]interface{}** |  | 

### Return type

[**V1AdminStoryImportPost201Response**](V1AdminStoryImportPost201Response.md)

### Authorization

[AdminBearer](../README.md#AdminBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1AdminStoryScaffoldPost

> V1AdminStoryScaffoldPost201Response V1AdminStoryScaffoldPost(ctx).Execute()

Create a development sample story.

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
	resp, r, err := apiClient.DefaultAPI.V1AdminStoryScaffoldPost(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.V1AdminStoryScaffoldPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1AdminStoryScaffoldPost`: V1AdminStoryScaffoldPost201Response
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.V1AdminStoryScaffoldPost`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiV1AdminStoryScaffoldPostRequest struct via the builder pattern


### Return type

[**V1AdminStoryScaffoldPost201Response**](V1AdminStoryScaffoldPost201Response.md)

### Authorization

[AdminBearer](../README.md#AdminBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1AdminStoryStoryIdDelete

> V1AdminStoryStoryIdDelete(ctx, storyId).Execute()

Delete a story as an administrator.

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
	r, err := apiClient.DefaultAPI.V1AdminStoryStoryIdDelete(context.Background(), storyId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.V1AdminStoryStoryIdDelete``: %v\n", err)
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

Other parameters are passed through a pointer to a apiV1AdminStoryStoryIdDeleteRequest struct via the builder pattern


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


## V1AdminStoryStoryIdGet

> V1AdminStoryStoryIdGet200Response V1AdminStoryStoryIdGet(ctx, storyId).Execute()

Read an authored story.

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
	resp, r, err := apiClient.DefaultAPI.V1AdminStoryStoryIdGet(context.Background(), storyId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.V1AdminStoryStoryIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1AdminStoryStoryIdGet`: V1AdminStoryStoryIdGet200Response
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.V1AdminStoryStoryIdGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**storyId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1AdminStoryStoryIdGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**V1AdminStoryStoryIdGet200Response**](V1AdminStoryStoryIdGet200Response.md)

### Authorization

[AdminBearer](../README.md#AdminBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1AdminStoryStoryIdNodeNodeIdClearEnrichmentPost

> V1AdminStoryStoryIdNodeNodeIdClearEnrichmentPost200Response V1AdminStoryStoryIdNodeNodeIdClearEnrichmentPost(ctx, storyId, nodeId).Execute()

Clear generated enrichment metadata from a node.

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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.V1AdminStoryStoryIdNodeNodeIdClearEnrichmentPost(context.Background(), storyId, nodeId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.V1AdminStoryStoryIdNodeNodeIdClearEnrichmentPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1AdminStoryStoryIdNodeNodeIdClearEnrichmentPost`: V1AdminStoryStoryIdNodeNodeIdClearEnrichmentPost200Response
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.V1AdminStoryStoryIdNodeNodeIdClearEnrichmentPost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**storyId** | **string** |  | 
**nodeId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1AdminStoryStoryIdNodeNodeIdClearEnrichmentPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**V1AdminStoryStoryIdNodeNodeIdClearEnrichmentPost200Response**](V1AdminStoryStoryIdNodeNodeIdClearEnrichmentPost200Response.md)

### Authorization

[AdminBearer](../README.md#AdminBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1AdminTenantRegisterPost

> V1AdminTenantRegisterPost201Response V1AdminTenantRegisterPost(ctx).V1AdminTenantRegisterPostRequest(v1AdminTenantRegisterPostRequest).Execute()

Register a tenant and issue its API key.

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
	v1AdminTenantRegisterPostRequest := *openapiclient.NewV1AdminTenantRegisterPostRequest("BillingCountry_example", "ContactEmail_example", "MaxAgeRating_example", "Name_example") // V1AdminTenantRegisterPostRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.V1AdminTenantRegisterPost(context.Background()).V1AdminTenantRegisterPostRequest(v1AdminTenantRegisterPostRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.V1AdminTenantRegisterPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1AdminTenantRegisterPost`: V1AdminTenantRegisterPost201Response
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.V1AdminTenantRegisterPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1AdminTenantRegisterPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **v1AdminTenantRegisterPostRequest** | [**V1AdminTenantRegisterPostRequest**](V1AdminTenantRegisterPostRequest.md) |  | 

### Return type

[**V1AdminTenantRegisterPost201Response**](V1AdminTenantRegisterPost201Response.md)

### Authorization

[AdminBearer](../README.md#AdminBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1AdminTenantTenantIdDelete

> V1AdminTenantTenantIdDelete(ctx, tenantId).Execute()

Delete a tenant.

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
	r, err := apiClient.DefaultAPI.V1AdminTenantTenantIdDelete(context.Background(), tenantId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.V1AdminTenantTenantIdDelete``: %v\n", err)
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

Other parameters are passed through a pointer to a apiV1AdminTenantTenantIdDeleteRequest struct via the builder pattern


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


## V1AdminTenantTenantIdGet

> V1AdminTenantTenantIdGet200Response V1AdminTenantTenantIdGet(ctx, tenantId).Execute()

Read tenant details.

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
	resp, r, err := apiClient.DefaultAPI.V1AdminTenantTenantIdGet(context.Background(), tenantId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.V1AdminTenantTenantIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1AdminTenantTenantIdGet`: V1AdminTenantTenantIdGet200Response
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.V1AdminTenantTenantIdGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**tenantId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1AdminTenantTenantIdGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**V1AdminTenantTenantIdGet200Response**](V1AdminTenantTenantIdGet200Response.md)

### Authorization

[AdminBearer](../README.md#AdminBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1AdminTenantTenantIdLitellmKeyPatch

> map[string]string V1AdminTenantTenantIdLitellmKeyPatch(ctx, tenantId).Execute()

Rotate tenant LiteLLM key metadata.

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
	resp, r, err := apiClient.DefaultAPI.V1AdminTenantTenantIdLitellmKeyPatch(context.Background(), tenantId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.V1AdminTenantTenantIdLitellmKeyPatch``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1AdminTenantTenantIdLitellmKeyPatch`: map[string]string
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.V1AdminTenantTenantIdLitellmKeyPatch`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**tenantId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1AdminTenantTenantIdLitellmKeyPatchRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

**map[string]string**

### Authorization

[AdminBearer](../README.md#AdminBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1AdminTenantTenantIdLlmKeyGet

> V1AdminTenantTenantIdLlmKeyGet200Response V1AdminTenantTenantIdLlmKeyGet(ctx, tenantId).Execute()

Read tenant LiteLLM key status.

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
	resp, r, err := apiClient.DefaultAPI.V1AdminTenantTenantIdLlmKeyGet(context.Background(), tenantId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.V1AdminTenantTenantIdLlmKeyGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1AdminTenantTenantIdLlmKeyGet`: V1AdminTenantTenantIdLlmKeyGet200Response
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.V1AdminTenantTenantIdLlmKeyGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**tenantId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1AdminTenantTenantIdLlmKeyGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**V1AdminTenantTenantIdLlmKeyGet200Response**](V1AdminTenantTenantIdLlmKeyGet200Response.md)

### Authorization

[AdminBearer](../README.md#AdminBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1AdminTenantTenantIdReprovisionLlmKeyPost

> V1AdminTenantTenantIdReprovisionLlmKeyPost(ctx, tenantId).Execute()

Reprovision a tenant LiteLLM virtual key.

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
	r, err := apiClient.DefaultAPI.V1AdminTenantTenantIdReprovisionLlmKeyPost(context.Background(), tenantId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.V1AdminTenantTenantIdReprovisionLlmKeyPost``: %v\n", err)
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

Other parameters are passed through a pointer to a apiV1AdminTenantTenantIdReprovisionLlmKeyPostRequest struct via the builder pattern


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


## V1AdminTenantsGet

> []V1AdminTenantTenantIdGet200Response V1AdminTenantsGet(ctx).Execute()

List tenants.

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
	resp, r, err := apiClient.DefaultAPI.V1AdminTenantsGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.V1AdminTenantsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1AdminTenantsGet`: []V1AdminTenantTenantIdGet200Response
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.V1AdminTenantsGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiV1AdminTenantsGetRequest struct via the builder pattern


### Return type

[**[]V1AdminTenantTenantIdGet200Response**](V1AdminTenantTenantIdGet200Response.md)

### Authorization

[AdminBearer](../README.md#AdminBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1AdminTermsGet

> []V1AdminTermsGet200ResponseInner V1AdminTermsGet(ctx).Execute()

List Terms of Service versions.

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
	resp, r, err := apiClient.DefaultAPI.V1AdminTermsGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.V1AdminTermsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1AdminTermsGet`: []V1AdminTermsGet200ResponseInner
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.V1AdminTermsGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiV1AdminTermsGetRequest struct via the builder pattern


### Return type

[**[]V1AdminTermsGet200ResponseInner**](V1AdminTermsGet200ResponseInner.md)

### Authorization

[AdminBearer](../README.md#AdminBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1AdminTermsPost

> V1AdminTermsGet200ResponseInner V1AdminTermsPost(ctx).V1AdminTermsPostRequest(v1AdminTermsPostRequest).Execute()

Create a Terms of Service version.

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
	v1AdminTermsPostRequest := *openapiclient.NewV1AdminTermsPostRequest("Content_example", "EffectiveDate_example", "VersionNumber_example") // V1AdminTermsPostRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.V1AdminTermsPost(context.Background()).V1AdminTermsPostRequest(v1AdminTermsPostRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.V1AdminTermsPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1AdminTermsPost`: V1AdminTermsGet200ResponseInner
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.V1AdminTermsPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1AdminTermsPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **v1AdminTermsPostRequest** | [**V1AdminTermsPostRequest**](V1AdminTermsPostRequest.md) |  | 

### Return type

[**V1AdminTermsGet200ResponseInner**](V1AdminTermsGet200ResponseInner.md)

### Authorization

[AdminBearer](../README.md#AdminBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1AuthoringJobsJobIdGet

> V1AuthoringJobsJobIdGet200Response V1AuthoringJobsJobIdGet(ctx, jobId).Execute()

Read async authoring job status.

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
	jobId := "jobId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.V1AuthoringJobsJobIdGet(context.Background(), jobId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.V1AuthoringJobsJobIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1AuthoringJobsJobIdGet`: V1AuthoringJobsJobIdGet200Response
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.V1AuthoringJobsJobIdGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**jobId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1AuthoringJobsJobIdGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**V1AuthoringJobsJobIdGet200Response**](V1AuthoringJobsJobIdGet200Response.md)

### Authorization

[PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1AuthoringJobsJobIdStreamGet

> V1AuthoringJobsJobIdGet200Response V1AuthoringJobsJobIdStreamGet(ctx, jobId).Execute()

Stream async authoring job status events.

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
	jobId := "jobId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.V1AuthoringJobsJobIdStreamGet(context.Background(), jobId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.V1AuthoringJobsJobIdStreamGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1AuthoringJobsJobIdStreamGet`: V1AuthoringJobsJobIdGet200Response
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.V1AuthoringJobsJobIdStreamGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**jobId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1AuthoringJobsJobIdStreamGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**V1AuthoringJobsJobIdGet200Response**](V1AuthoringJobsJobIdGet200Response.md)

### Authorization

[PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/event-stream, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1AuthoringStoriesGet

> V1AuthoringStoriesGet200Response V1AuthoringStoriesGet(ctx).Execute()

List authored stories.

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
	resp, r, err := apiClient.DefaultAPI.V1AuthoringStoriesGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.V1AuthoringStoriesGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1AuthoringStoriesGet`: V1AuthoringStoriesGet200Response
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.V1AuthoringStoriesGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiV1AuthoringStoriesGetRequest struct via the builder pattern


### Return type

[**V1AuthoringStoriesGet200Response**](V1AuthoringStoriesGet200Response.md)

### Authorization

[PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1AuthoringStoriesPost

> V1AdminStoryScaffoldPost201Response V1AuthoringStoriesPost(ctx).V1AuthoringStoriesPostRequest(v1AuthoringStoriesPostRequest).Execute()

Create a story synchronously in development or enqueue async generation.

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
	v1AuthoringStoriesPostRequest := *openapiclient.NewV1AuthoringStoriesPostRequest() // V1AuthoringStoriesPostRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.V1AuthoringStoriesPost(context.Background()).V1AuthoringStoriesPostRequest(v1AuthoringStoriesPostRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.V1AuthoringStoriesPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1AuthoringStoriesPost`: V1AdminStoryScaffoldPost201Response
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.V1AuthoringStoriesPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1AuthoringStoriesPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **v1AuthoringStoriesPostRequest** | [**V1AuthoringStoriesPostRequest**](V1AuthoringStoriesPostRequest.md) |  | 

### Return type

[**V1AdminStoryScaffoldPost201Response**](V1AdminStoryScaffoldPost201Response.md)

### Authorization

[PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1AuthoringStoriesStoryIdDelete

> V1AuthoringStoriesStoryIdDelete(ctx, storyId).Execute()

Delete an authored story.

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
	r, err := apiClient.DefaultAPI.V1AuthoringStoriesStoryIdDelete(context.Background(), storyId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.V1AuthoringStoriesStoryIdDelete``: %v\n", err)
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

Other parameters are passed through a pointer to a apiV1AuthoringStoriesStoryIdDeleteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1AuthoringStoriesStoryIdExplorationNodesGet

> V1AuthoringStoriesStoryIdExplorationNodesGet200Response V1AuthoringStoriesStoryIdExplorationNodesGet(ctx, storyId).Execute()

List authored exploration nodes.

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
	resp, r, err := apiClient.DefaultAPI.V1AuthoringStoriesStoryIdExplorationNodesGet(context.Background(), storyId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.V1AuthoringStoriesStoryIdExplorationNodesGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1AuthoringStoriesStoryIdExplorationNodesGet`: V1AuthoringStoriesStoryIdExplorationNodesGet200Response
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.V1AuthoringStoriesStoryIdExplorationNodesGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**storyId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1AuthoringStoriesStoryIdExplorationNodesGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**V1AuthoringStoriesStoryIdExplorationNodesGet200Response**](V1AuthoringStoriesStoryIdExplorationNodesGet200Response.md)

### Authorization

[PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1AuthoringStoriesStoryIdExplorationNodesNodeIdGet

> V1AuthoringStoriesStoryIdExplorationNodesGet200ResponseItemsInner V1AuthoringStoriesStoryIdExplorationNodesNodeIdGet(ctx, storyId, nodeId).Execute()

Read authored exploration node details.

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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.V1AuthoringStoriesStoryIdExplorationNodesNodeIdGet(context.Background(), storyId, nodeId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.V1AuthoringStoriesStoryIdExplorationNodesNodeIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1AuthoringStoriesStoryIdExplorationNodesNodeIdGet`: V1AuthoringStoriesStoryIdExplorationNodesGet200ResponseItemsInner
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.V1AuthoringStoriesStoryIdExplorationNodesNodeIdGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**storyId** | **string** |  | 
**nodeId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1AuthoringStoriesStoryIdExplorationNodesNodeIdGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**V1AuthoringStoriesStoryIdExplorationNodesGet200ResponseItemsInner**](V1AuthoringStoriesStoryIdExplorationNodesGet200ResponseItemsInner.md)

### Authorization

[PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1AuthoringStoriesStoryIdExplorationNodesNodeIdPatch

> V1AuthoringStoriesStoryIdExplorationNodesGet200ResponseItemsInner V1AuthoringStoriesStoryIdExplorationNodesNodeIdPatch(ctx, storyId, nodeId).V1AuthoringStoriesStoryIdExplorationNodesNodeIdPatchRequest(v1AuthoringStoriesStoryIdExplorationNodesNodeIdPatchRequest).Execute()

Update authored exploration-node controls.

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
	v1AuthoringStoriesStoryIdExplorationNodesNodeIdPatchRequest := *openapiclient.NewV1AuthoringStoriesStoryIdExplorationNodesNodeIdPatchRequest() // V1AuthoringStoriesStoryIdExplorationNodesNodeIdPatchRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.V1AuthoringStoriesStoryIdExplorationNodesNodeIdPatch(context.Background(), storyId, nodeId).V1AuthoringStoriesStoryIdExplorationNodesNodeIdPatchRequest(v1AuthoringStoriesStoryIdExplorationNodesNodeIdPatchRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.V1AuthoringStoriesStoryIdExplorationNodesNodeIdPatch``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1AuthoringStoriesStoryIdExplorationNodesNodeIdPatch`: V1AuthoringStoriesStoryIdExplorationNodesGet200ResponseItemsInner
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.V1AuthoringStoriesStoryIdExplorationNodesNodeIdPatch`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**storyId** | **string** |  | 
**nodeId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1AuthoringStoriesStoryIdExplorationNodesNodeIdPatchRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **v1AuthoringStoriesStoryIdExplorationNodesNodeIdPatchRequest** | [**V1AuthoringStoriesStoryIdExplorationNodesNodeIdPatchRequest**](V1AuthoringStoriesStoryIdExplorationNodesNodeIdPatchRequest.md) |  | 

### Return type

[**V1AuthoringStoriesStoryIdExplorationNodesGet200ResponseItemsInner**](V1AuthoringStoriesStoryIdExplorationNodesGet200ResponseItemsInner.md)

### Authorization

[PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1AuthoringStoriesStoryIdGet

> V1AdminStoryStoryIdGet200Response V1AuthoringStoriesStoryIdGet(ctx, storyId).Execute()

Read authored story details.

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
	resp, r, err := apiClient.DefaultAPI.V1AuthoringStoriesStoryIdGet(context.Background(), storyId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.V1AuthoringStoriesStoryIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1AuthoringStoriesStoryIdGet`: V1AdminStoryStoryIdGet200Response
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.V1AuthoringStoriesStoryIdGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**storyId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1AuthoringStoriesStoryIdGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**V1AdminStoryStoryIdGet200Response**](V1AdminStoryStoryIdGet200Response.md)

### Authorization

[PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1AuthoringStoriesStoryIdGraphGet

> V1AuthoringStoriesStoryIdGraphGet200Response V1AuthoringStoriesStoryIdGraphGet(ctx, storyId).Execute()

Read authored story graph topology.

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
	resp, r, err := apiClient.DefaultAPI.V1AuthoringStoriesStoryIdGraphGet(context.Background(), storyId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.V1AuthoringStoriesStoryIdGraphGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1AuthoringStoriesStoryIdGraphGet`: V1AuthoringStoriesStoryIdGraphGet200Response
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.V1AuthoringStoriesStoryIdGraphGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**storyId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1AuthoringStoriesStoryIdGraphGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**V1AuthoringStoriesStoryIdGraphGet200Response**](V1AuthoringStoriesStoryIdGraphGet200Response.md)

### Authorization

[PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1AuthoringStoriesStoryIdPathsGet

> V1AuthoringStoriesStoryIdPathsGet200Response V1AuthoringStoriesStoryIdPathsGet(ctx, storyId).Execute()

List all authored story paths.

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
	resp, r, err := apiClient.DefaultAPI.V1AuthoringStoriesStoryIdPathsGet(context.Background(), storyId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.V1AuthoringStoriesStoryIdPathsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1AuthoringStoriesStoryIdPathsGet`: V1AuthoringStoriesStoryIdPathsGet200Response
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.V1AuthoringStoriesStoryIdPathsGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**storyId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1AuthoringStoriesStoryIdPathsGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**V1AuthoringStoriesStoryIdPathsGet200Response**](V1AuthoringStoriesStoryIdPathsGet200Response.md)

### Authorization

[PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1HealthGet

> V1HealthGet200Response V1HealthGet(ctx).Execute()

Check API, Postgres, and Redis health.

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
	resp, r, err := apiClient.DefaultAPI.V1HealthGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.V1HealthGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1HealthGet`: V1HealthGet200Response
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.V1HealthGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiV1HealthGetRequest struct via the builder pattern


### Return type

[**V1HealthGet200Response**](V1HealthGet200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1PlayerPlayerIdDataExportGet

> V1PlayerPlayerIdDataExportGet200Response V1PlayerPlayerIdDataExportGet(ctx, playerId).Execute()

Export stored player data.

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
	playerId := "playerId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.V1PlayerPlayerIdDataExportGet(context.Background(), playerId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.V1PlayerPlayerIdDataExportGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1PlayerPlayerIdDataExportGet`: V1PlayerPlayerIdDataExportGet200Response
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.V1PlayerPlayerIdDataExportGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**playerId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1PlayerPlayerIdDataExportGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**V1PlayerPlayerIdDataExportGet200Response**](V1PlayerPlayerIdDataExportGet200Response.md)

### Authorization

[PlayerId](../README.md#PlayerId), [PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1PlayerPlayerIdDelete

> V1PlayerPlayerIdDelete200Response V1PlayerPlayerIdDelete(ctx, playerId).Execute()

Erase stored player data.

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
	playerId := "playerId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.V1PlayerPlayerIdDelete(context.Background(), playerId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.V1PlayerPlayerIdDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1PlayerPlayerIdDelete`: V1PlayerPlayerIdDelete200Response
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.V1PlayerPlayerIdDelete`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**playerId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1PlayerPlayerIdDeleteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**V1PlayerPlayerIdDelete200Response**](V1PlayerPlayerIdDelete200Response.md)

### Authorization

[PlayerId](../README.md#PlayerId), [PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1PlayerPlayerIdStoryStoryIdWarningsAcknowledgePost

> V1PlayerPlayerIdStoryStoryIdWarningsAcknowledgePost(ctx, playerId, storyId).Execute()

Acknowledge content warnings for a player story session.

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
	playerId := "playerId_example" // string | 
	storyId := "storyId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DefaultAPI.V1PlayerPlayerIdStoryStoryIdWarningsAcknowledgePost(context.Background(), playerId, storyId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.V1PlayerPlayerIdStoryStoryIdWarningsAcknowledgePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**playerId** | **string** |  | 
**storyId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1PlayerPlayerIdStoryStoryIdWarningsAcknowledgePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

 (empty response body)

### Authorization

[PlayerId](../README.md#PlayerId), [PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1PlayerPlayerIdTosStatusGet

> V1PlayerPlayerIdTosStatusGet200Response V1PlayerPlayerIdTosStatusGet(ctx, playerId).Execute()

Read player Terms of Service acceptance status.

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
	playerId := "playerId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.V1PlayerPlayerIdTosStatusGet(context.Background(), playerId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.V1PlayerPlayerIdTosStatusGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1PlayerPlayerIdTosStatusGet`: V1PlayerPlayerIdTosStatusGet200Response
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.V1PlayerPlayerIdTosStatusGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**playerId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1PlayerPlayerIdTosStatusGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**V1PlayerPlayerIdTosStatusGet200Response**](V1PlayerPlayerIdTosStatusGet200Response.md)

### Authorization

[PlayerId](../README.md#PlayerId), [PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1StoriesGet

> V1AuthoringStoriesGet200Response V1StoriesGet(ctx).Execute()

List playable stories for the current tenant.

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
	resp, r, err := apiClient.DefaultAPI.V1StoriesGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.V1StoriesGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1StoriesGet`: V1AuthoringStoriesGet200Response
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.V1StoriesGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiV1StoriesGetRequest struct via the builder pattern


### Return type

[**V1AuthoringStoriesGet200Response**](V1AuthoringStoriesGet200Response.md)

### Authorization

[PlayerId](../README.md#PlayerId), [PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1StoryStoryIdChoicePost

> V1StoryStoryIdChoicePost200Response V1StoryStoryIdChoicePost(ctx, storyId).V1StoryStoryIdChoicePostRequest(v1StoryStoryIdChoicePostRequest).Execute()

Advance the current session by choosing a structured choice.

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
	v1StoryStoryIdChoicePostRequest := *openapiclient.NewV1StoryStoryIdChoicePostRequest("ChoiceId_example", "NodeId_example") // V1StoryStoryIdChoicePostRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.V1StoryStoryIdChoicePost(context.Background(), storyId).V1StoryStoryIdChoicePostRequest(v1StoryStoryIdChoicePostRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.V1StoryStoryIdChoicePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1StoryStoryIdChoicePost`: V1StoryStoryIdChoicePost200Response
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.V1StoryStoryIdChoicePost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**storyId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1StoryStoryIdChoicePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **v1StoryStoryIdChoicePostRequest** | [**V1StoryStoryIdChoicePostRequest**](V1StoryStoryIdChoicePostRequest.md) |  | 

### Return type

[**V1StoryStoryIdChoicePost200Response**](V1StoryStoryIdChoicePost200Response.md)

### Authorization

[PlayerId](../README.md#PlayerId), [PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1StoryStoryIdExplorationNodesGet

> []V1AuthoringStoriesStoryIdExplorationNodesGet200ResponseItemsInner V1StoryStoryIdExplorationNodesGet(ctx, storyId).Execute()

List exploration nodes available at the current story node.

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
	resp, r, err := apiClient.DefaultAPI.V1StoryStoryIdExplorationNodesGet(context.Background(), storyId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.V1StoryStoryIdExplorationNodesGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1StoryStoryIdExplorationNodesGet`: []V1AuthoringStoriesStoryIdExplorationNodesGet200ResponseItemsInner
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.V1StoryStoryIdExplorationNodesGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**storyId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1StoryStoryIdExplorationNodesGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]V1AuthoringStoriesStoryIdExplorationNodesGet200ResponseItemsInner**](V1AuthoringStoriesStoryIdExplorationNodesGet200ResponseItemsInner.md)

### Authorization

[PlayerId](../README.md#PlayerId), [PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1StoryStoryIdExplorationNodesNodeIdPickDelete

> V1StoryStoryIdExplorationNodesNodeIdPickPost200Response V1StoryStoryIdExplorationNodesNodeIdPickDelete(ctx, storyId, nodeId).Execute()

Remove an exploration-node pick from the current session.

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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.V1StoryStoryIdExplorationNodesNodeIdPickDelete(context.Background(), storyId, nodeId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.V1StoryStoryIdExplorationNodesNodeIdPickDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1StoryStoryIdExplorationNodesNodeIdPickDelete`: V1StoryStoryIdExplorationNodesNodeIdPickPost200Response
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.V1StoryStoryIdExplorationNodesNodeIdPickDelete`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**storyId** | **string** |  | 
**nodeId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1StoryStoryIdExplorationNodesNodeIdPickDeleteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**V1StoryStoryIdExplorationNodesNodeIdPickPost200Response**](V1StoryStoryIdExplorationNodesNodeIdPickPost200Response.md)

### Authorization

[PlayerId](../README.md#PlayerId), [PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1StoryStoryIdExplorationNodesNodeIdPickPost

> V1StoryStoryIdExplorationNodesNodeIdPickPost200Response V1StoryStoryIdExplorationNodesNodeIdPickPost(ctx, storyId, nodeId).Execute()

Pick an exploration node for the current session.

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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.V1StoryStoryIdExplorationNodesNodeIdPickPost(context.Background(), storyId, nodeId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.V1StoryStoryIdExplorationNodesNodeIdPickPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1StoryStoryIdExplorationNodesNodeIdPickPost`: V1StoryStoryIdExplorationNodesNodeIdPickPost200Response
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.V1StoryStoryIdExplorationNodesNodeIdPickPost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**storyId** | **string** |  | 
**nodeId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1StoryStoryIdExplorationNodesNodeIdPickPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**V1StoryStoryIdExplorationNodesNodeIdPickPost200Response**](V1StoryStoryIdExplorationNodesNodeIdPickPost200Response.md)

### Authorization

[PlayerId](../README.md#PlayerId), [PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1StoryStoryIdExplorationStateGet

> V1StoryStoryIdExplorationStateGet200Response V1StoryStoryIdExplorationStateGet(ctx, storyId).Execute()

Read exploration state for the current session.

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
	resp, r, err := apiClient.DefaultAPI.V1StoryStoryIdExplorationStateGet(context.Background(), storyId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.V1StoryStoryIdExplorationStateGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1StoryStoryIdExplorationStateGet`: V1StoryStoryIdExplorationStateGet200Response
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.V1StoryStoryIdExplorationStateGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**storyId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1StoryStoryIdExplorationStateGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**V1StoryStoryIdExplorationStateGet200Response**](V1StoryStoryIdExplorationStateGet200Response.md)

### Authorization

[PlayerId](../README.md#PlayerId), [PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1StoryStoryIdExplorePost

> V1StoryStoryIdExplorePost200Response V1StoryStoryIdExplorePost(ctx, storyId).V1StoryStoryIdExplorePostRequest(v1StoryStoryIdExplorePostRequest).Execute()

Ask an exploration question at the current story node.

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
	v1StoryStoryIdExplorePostRequest := *openapiclient.NewV1StoryStoryIdExplorePostRequest("NodeId_example", "Question_example") // V1StoryStoryIdExplorePostRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.V1StoryStoryIdExplorePost(context.Background(), storyId).V1StoryStoryIdExplorePostRequest(v1StoryStoryIdExplorePostRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.V1StoryStoryIdExplorePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1StoryStoryIdExplorePost`: V1StoryStoryIdExplorePost200Response
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.V1StoryStoryIdExplorePost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**storyId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1StoryStoryIdExplorePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **v1StoryStoryIdExplorePostRequest** | [**V1StoryStoryIdExplorePostRequest**](V1StoryStoryIdExplorePostRequest.md) |  | 

### Return type

[**V1StoryStoryIdExplorePost200Response**](V1StoryStoryIdExplorePost200Response.md)

### Authorization

[PlayerId](../README.md#PlayerId), [PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1StoryStoryIdFreeTextPost

> V1StoryStoryIdChoicePost200Response V1StoryStoryIdFreeTextPost(ctx, storyId).V1StoryStoryIdFreeTextPostRequest(v1StoryStoryIdFreeTextPostRequest).Execute()

Continue the story from free text input using SSE events.

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
	v1StoryStoryIdFreeTextPostRequest := *openapiclient.NewV1StoryStoryIdFreeTextPostRequest("FreeText_example", "NodeId_example") // V1StoryStoryIdFreeTextPostRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.V1StoryStoryIdFreeTextPost(context.Background(), storyId).V1StoryStoryIdFreeTextPostRequest(v1StoryStoryIdFreeTextPostRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.V1StoryStoryIdFreeTextPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1StoryStoryIdFreeTextPost`: V1StoryStoryIdChoicePost200Response
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.V1StoryStoryIdFreeTextPost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**storyId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1StoryStoryIdFreeTextPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **v1StoryStoryIdFreeTextPostRequest** | [**V1StoryStoryIdFreeTextPostRequest**](V1StoryStoryIdFreeTextPostRequest.md) |  | 

### Return type

[**V1StoryStoryIdChoicePost200Response**](V1StoryStoryIdChoicePost200Response.md)

### Authorization

[PlayerId](../README.md#PlayerId), [PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: text/event-stream, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1StoryStoryIdGraphGet

> V1AuthoringStoriesStoryIdGraphGet200Response V1StoryStoryIdGraphGet(ctx, storyId).Execute()

Read story graph topology.

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
	resp, r, err := apiClient.DefaultAPI.V1StoryStoryIdGraphGet(context.Background(), storyId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.V1StoryStoryIdGraphGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1StoryStoryIdGraphGet`: V1AuthoringStoriesStoryIdGraphGet200Response
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.V1StoryStoryIdGraphGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**storyId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1StoryStoryIdGraphGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**V1AuthoringStoriesStoryIdGraphGet200Response**](V1AuthoringStoriesStoryIdGraphGet200Response.md)

### Authorization

[PlayerId](../README.md#PlayerId), [PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1StoryStoryIdNodeNodeIdArcGet

> map[string]map[string]interface{} V1StoryStoryIdNodeNodeIdArcGet(ctx, storyId, nodeId).Execute()

Read drama arc analysis for a story node.

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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.V1StoryStoryIdNodeNodeIdArcGet(context.Background(), storyId, nodeId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.V1StoryStoryIdNodeNodeIdArcGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1StoryStoryIdNodeNodeIdArcGet`: map[string]map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.V1StoryStoryIdNodeNodeIdArcGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**storyId** | **string** |  | 
**nodeId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1StoryStoryIdNodeNodeIdArcGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**map[string]map[string]interface{}**](map.md)

### Authorization

[PlayerId](../README.md#PlayerId), [PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1StoryStoryIdNodeNodeIdGet

> V1StoryStoryIdChoicePost200Response V1StoryStoryIdNodeNodeIdGet(ctx, storyId, nodeId).Execute()

Read a story node.

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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.V1StoryStoryIdNodeNodeIdGet(context.Background(), storyId, nodeId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.V1StoryStoryIdNodeNodeIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1StoryStoryIdNodeNodeIdGet`: V1StoryStoryIdChoicePost200Response
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.V1StoryStoryIdNodeNodeIdGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**storyId** | **string** |  | 
**nodeId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1StoryStoryIdNodeNodeIdGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**V1StoryStoryIdChoicePost200Response**](V1StoryStoryIdChoicePost200Response.md)

### Authorization

[PlayerId](../README.md#PlayerId), [PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1StoryStoryIdPathsGet

> V1AuthoringStoriesStoryIdPathsGet200Response V1StoryStoryIdPathsGet(ctx, storyId).Execute()

List all story paths.

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
	resp, r, err := apiClient.DefaultAPI.V1StoryStoryIdPathsGet(context.Background(), storyId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.V1StoryStoryIdPathsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1StoryStoryIdPathsGet`: V1AuthoringStoriesStoryIdPathsGet200Response
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.V1StoryStoryIdPathsGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**storyId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1StoryStoryIdPathsGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**V1AuthoringStoriesStoryIdPathsGet200Response**](V1AuthoringStoriesStoryIdPathsGet200Response.md)

### Authorization

[PlayerId](../README.md#PlayerId), [PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1StoryStoryIdSessionEntityIndexGet

> V1StoryStoryIdSessionEntityIndexGet200Response V1StoryStoryIdSessionEntityIndexGet(ctx, storyId).Execute()

List discovered entity index entries for the current session.

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
	resp, r, err := apiClient.DefaultAPI.V1StoryStoryIdSessionEntityIndexGet(context.Background(), storyId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.V1StoryStoryIdSessionEntityIndexGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1StoryStoryIdSessionEntityIndexGet`: V1StoryStoryIdSessionEntityIndexGet200Response
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.V1StoryStoryIdSessionEntityIndexGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**storyId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1StoryStoryIdSessionEntityIndexGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**V1StoryStoryIdSessionEntityIndexGet200Response**](V1StoryStoryIdSessionEntityIndexGet200Response.md)

### Authorization

[PlayerId](../README.md#PlayerId), [PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1StoryStoryIdSessionGet

> V1StoryStoryIdSessionGet200Response V1StoryStoryIdSessionGet(ctx, storyId).Execute()

Get or create the current player session.

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
	resp, r, err := apiClient.DefaultAPI.V1StoryStoryIdSessionGet(context.Background(), storyId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.V1StoryStoryIdSessionGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1StoryStoryIdSessionGet`: V1StoryStoryIdSessionGet200Response
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.V1StoryStoryIdSessionGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**storyId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1StoryStoryIdSessionGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**V1StoryStoryIdSessionGet200Response**](V1StoryStoryIdSessionGet200Response.md)

### Authorization

[PlayerId](../README.md#PlayerId), [PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1StoryStoryIdSessionLockDelete

> V1StoryStoryIdSessionLockDelete(ctx, storyId).Execute()

Release a session lock.

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
	r, err := apiClient.DefaultAPI.V1StoryStoryIdSessionLockDelete(context.Background(), storyId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.V1StoryStoryIdSessionLockDelete``: %v\n", err)
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

Other parameters are passed through a pointer to a apiV1StoryStoryIdSessionLockDeleteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[PlayerId](../README.md#PlayerId), [PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1StoryStoryIdSessionResetPost

> V1StoryStoryIdSessionGet200Response V1StoryStoryIdSessionResetPost(ctx, storyId).Execute()

Reset a completed or forced player session.

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
	resp, r, err := apiClient.DefaultAPI.V1StoryStoryIdSessionResetPost(context.Background(), storyId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.V1StoryStoryIdSessionResetPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1StoryStoryIdSessionResetPost`: V1StoryStoryIdSessionGet200Response
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.V1StoryStoryIdSessionResetPost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**storyId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiV1StoryStoryIdSessionResetPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**V1StoryStoryIdSessionGet200Response**](V1StoryStoryIdSessionGet200Response.md)

### Authorization

[PlayerId](../README.md#PlayerId), [PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1TermsAcceptPost

> V1TermsAcceptPost200Response V1TermsAcceptPost(ctx).V1TermsAcceptPostRequest(v1TermsAcceptPostRequest).Execute()

Accept the current Terms of Service for the current player.

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
	v1TermsAcceptPostRequest := *openapiclient.NewV1TermsAcceptPostRequest("TosVersionId_example") // V1TermsAcceptPostRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DefaultAPI.V1TermsAcceptPost(context.Background()).V1TermsAcceptPostRequest(v1TermsAcceptPostRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.V1TermsAcceptPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1TermsAcceptPost`: V1TermsAcceptPost200Response
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.V1TermsAcceptPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiV1TermsAcceptPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **v1TermsAcceptPostRequest** | [**V1TermsAcceptPostRequest**](V1TermsAcceptPostRequest.md) |  | 

### Return type

[**V1TermsAcceptPost200Response**](V1TermsAcceptPost200Response.md)

### Authorization

[PlayerId](../README.md#PlayerId), [PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## V1TermsGet

> V1AdminTermsGet200ResponseInner V1TermsGet(ctx).Execute()

Read the current Terms of Service version.

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
	resp, r, err := apiClient.DefaultAPI.V1TermsGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DefaultAPI.V1TermsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `V1TermsGet`: V1AdminTermsGet200ResponseInner
	fmt.Fprintf(os.Stdout, "Response from `DefaultAPI.V1TermsGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiV1TermsGetRequest struct via the builder pattern


### Return type

[**V1AdminTermsGet200ResponseInner**](V1AdminTermsGet200ResponseInner.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

