# \AuthoringAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**DeleteStoryV1AuthoringStoriesStoryIdDelete**](AuthoringAPI.md#DeleteStoryV1AuthoringStoriesStoryIdDelete) | **Delete** /v1/authoring/stories/{story_id} | Delete Story
[**GenerateStoryV1AuthoringStoriesPost**](AuthoringAPI.md#GenerateStoryV1AuthoringStoriesPost) | **Post** /v1/authoring/stories | Generate Story
[**GetAuthoringExplorationNodeV1AuthoringStoriesStoryIdExplorationNodesNodeIdGet**](AuthoringAPI.md#GetAuthoringExplorationNodeV1AuthoringStoriesStoryIdExplorationNodesNodeIdGet) | **Get** /v1/authoring/stories/{story_id}/exploration-nodes/{node_id} | Get Authoring Exploration Node
[**GetJobStatusV1AuthoringJobsJobIdGet**](AuthoringAPI.md#GetJobStatusV1AuthoringJobsJobIdGet) | **Get** /v1/authoring/jobs/{job_id} | Get Job Status
[**GetStoryGraphV1AuthoringStoriesStoryIdGraphGet**](AuthoringAPI.md#GetStoryGraphV1AuthoringStoriesStoryIdGraphGet) | **Get** /v1/authoring/stories/{story_id}/graph | Get Story Graph
[**GetStoryPathsV1AuthoringStoriesStoryIdPathsGet**](AuthoringAPI.md#GetStoryPathsV1AuthoringStoriesStoryIdPathsGet) | **Get** /v1/authoring/stories/{story_id}/paths | Get Story Paths
[**GetStoryV1AuthoringStoriesStoryIdGet**](AuthoringAPI.md#GetStoryV1AuthoringStoriesStoryIdGet) | **Get** /v1/authoring/stories/{story_id} | Get Story
[**ListAuthoringExplorationNodesV1AuthoringStoriesStoryIdExplorationNodesGet**](AuthoringAPI.md#ListAuthoringExplorationNodesV1AuthoringStoriesStoryIdExplorationNodesGet) | **Get** /v1/authoring/stories/{story_id}/exploration-nodes | List Authoring Exploration Nodes
[**ListStoriesV1AuthoringStoriesGet**](AuthoringAPI.md#ListStoriesV1AuthoringStoriesGet) | **Get** /v1/authoring/stories | List Stories
[**PatchAuthoringExplorationNodeV1AuthoringStoriesStoryIdExplorationNodesNodeIdPatch**](AuthoringAPI.md#PatchAuthoringExplorationNodeV1AuthoringStoriesStoryIdExplorationNodesNodeIdPatch) | **Patch** /v1/authoring/stories/{story_id}/exploration-nodes/{node_id} | Patch Authoring Exploration Node
[**StreamJobStatusV1AuthoringJobsJobIdStreamGet**](AuthoringAPI.md#StreamJobStatusV1AuthoringJobsJobIdStreamGet) | **Get** /v1/authoring/jobs/{job_id}/stream | Stream Job Status



## DeleteStoryV1AuthoringStoriesStoryIdDelete

> DeleteStoryV1AuthoringStoriesStoryIdDelete(ctx, storyId).Execute()

Delete Story



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
	r, err := apiClient.AuthoringAPI.DeleteStoryV1AuthoringStoriesStoryIdDelete(context.Background(), storyId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthoringAPI.DeleteStoryV1AuthoringStoriesStoryIdDelete``: %v\n", err)
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

Other parameters are passed through a pointer to a apiDeleteStoryV1AuthoringStoriesStoryIdDeleteRequest struct via the builder pattern


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


## GenerateStoryV1AuthoringStoriesPost

> StoryGenerateResponse GenerateStoryV1AuthoringStoriesPost(ctx).StoryGenerateRequest(storyGenerateRequest).Execute()

Generate Story



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
	storyGenerateRequest := *openapiclient.NewStoryGenerateRequest("Prompt_example") // StoryGenerateRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AuthoringAPI.GenerateStoryV1AuthoringStoriesPost(context.Background()).StoryGenerateRequest(storyGenerateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthoringAPI.GenerateStoryV1AuthoringStoriesPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GenerateStoryV1AuthoringStoriesPost`: StoryGenerateResponse
	fmt.Fprintf(os.Stdout, "Response from `AuthoringAPI.GenerateStoryV1AuthoringStoriesPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGenerateStoryV1AuthoringStoriesPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **storyGenerateRequest** | [**StoryGenerateRequest**](StoryGenerateRequest.md) |  | 

### Return type

[**StoryGenerateResponse**](StoryGenerateResponse.md)

### Authorization

[PlayerId](../README.md#PlayerId), [PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAuthoringExplorationNodeV1AuthoringStoriesStoryIdExplorationNodesNodeIdGet

> ExplorationNodeResponse GetAuthoringExplorationNodeV1AuthoringStoriesStoryIdExplorationNodesNodeIdGet(ctx, storyId, nodeId).Execute()

Get Authoring Exploration Node



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
	resp, r, err := apiClient.AuthoringAPI.GetAuthoringExplorationNodeV1AuthoringStoriesStoryIdExplorationNodesNodeIdGet(context.Background(), storyId, nodeId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthoringAPI.GetAuthoringExplorationNodeV1AuthoringStoriesStoryIdExplorationNodesNodeIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAuthoringExplorationNodeV1AuthoringStoriesStoryIdExplorationNodesNodeIdGet`: ExplorationNodeResponse
	fmt.Fprintf(os.Stdout, "Response from `AuthoringAPI.GetAuthoringExplorationNodeV1AuthoringStoriesStoryIdExplorationNodesNodeIdGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**storyId** | **string** |  | 
**nodeId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetAuthoringExplorationNodeV1AuthoringStoriesStoryIdExplorationNodesNodeIdGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**ExplorationNodeResponse**](ExplorationNodeResponse.md)

### Authorization

[PlayerId](../README.md#PlayerId), [PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetJobStatusV1AuthoringJobsJobIdGet

> JobStatusResponse GetJobStatusV1AuthoringJobsJobIdGet(ctx, jobId).Execute()

Get Job Status



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
	resp, r, err := apiClient.AuthoringAPI.GetJobStatusV1AuthoringJobsJobIdGet(context.Background(), jobId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthoringAPI.GetJobStatusV1AuthoringJobsJobIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetJobStatusV1AuthoringJobsJobIdGet`: JobStatusResponse
	fmt.Fprintf(os.Stdout, "Response from `AuthoringAPI.GetJobStatusV1AuthoringJobsJobIdGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**jobId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetJobStatusV1AuthoringJobsJobIdGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**JobStatusResponse**](JobStatusResponse.md)

### Authorization

[PlayerId](../README.md#PlayerId), [PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetStoryGraphV1AuthoringStoriesStoryIdGraphGet

> GraphTopologyResponse GetStoryGraphV1AuthoringStoriesStoryIdGraphGet(ctx, storyId).Execute()

Get Story Graph



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
	resp, r, err := apiClient.AuthoringAPI.GetStoryGraphV1AuthoringStoriesStoryIdGraphGet(context.Background(), storyId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthoringAPI.GetStoryGraphV1AuthoringStoriesStoryIdGraphGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetStoryGraphV1AuthoringStoriesStoryIdGraphGet`: GraphTopologyResponse
	fmt.Fprintf(os.Stdout, "Response from `AuthoringAPI.GetStoryGraphV1AuthoringStoriesStoryIdGraphGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**storyId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetStoryGraphV1AuthoringStoriesStoryIdGraphGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**GraphTopologyResponse**](GraphTopologyResponse.md)

### Authorization

[PlayerId](../README.md#PlayerId), [PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetStoryPathsV1AuthoringStoriesStoryIdPathsGet

> PathsResponse GetStoryPathsV1AuthoringStoriesStoryIdPathsGet(ctx, storyId).Execute()

Get Story Paths



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
	resp, r, err := apiClient.AuthoringAPI.GetStoryPathsV1AuthoringStoriesStoryIdPathsGet(context.Background(), storyId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthoringAPI.GetStoryPathsV1AuthoringStoriesStoryIdPathsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetStoryPathsV1AuthoringStoriesStoryIdPathsGet`: PathsResponse
	fmt.Fprintf(os.Stdout, "Response from `AuthoringAPI.GetStoryPathsV1AuthoringStoriesStoryIdPathsGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**storyId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetStoryPathsV1AuthoringStoriesStoryIdPathsGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**PathsResponse**](PathsResponse.md)

### Authorization

[PlayerId](../README.md#PlayerId), [PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetStoryV1AuthoringStoriesStoryIdGet

> StoryDetailResponse GetStoryV1AuthoringStoriesStoryIdGet(ctx, storyId).Execute()

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
	resp, r, err := apiClient.AuthoringAPI.GetStoryV1AuthoringStoriesStoryIdGet(context.Background(), storyId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthoringAPI.GetStoryV1AuthoringStoriesStoryIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetStoryV1AuthoringStoriesStoryIdGet`: StoryDetailResponse
	fmt.Fprintf(os.Stdout, "Response from `AuthoringAPI.GetStoryV1AuthoringStoriesStoryIdGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**storyId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetStoryV1AuthoringStoriesStoryIdGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**StoryDetailResponse**](StoryDetailResponse.md)

### Authorization

[PlayerId](../README.md#PlayerId), [PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListAuthoringExplorationNodesV1AuthoringStoriesStoryIdExplorationNodesGet

> PaginatedResponseExplorationNodeResponse ListAuthoringExplorationNodesV1AuthoringStoriesStoryIdExplorationNodesGet(ctx, storyId).ParentNodeId(parentNodeId).Essential(essential).Cursor(cursor).Limit(limit).Execute()

List Authoring Exploration Nodes



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
	parentNodeId := "parentNodeId_example" // string |  (optional)
	essential := true // bool |  (optional)
	cursor := "cursor_example" // string |  (optional)
	limit := int32(56) // int32 |  (optional) (default to 50)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AuthoringAPI.ListAuthoringExplorationNodesV1AuthoringStoriesStoryIdExplorationNodesGet(context.Background(), storyId).ParentNodeId(parentNodeId).Essential(essential).Cursor(cursor).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthoringAPI.ListAuthoringExplorationNodesV1AuthoringStoriesStoryIdExplorationNodesGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListAuthoringExplorationNodesV1AuthoringStoriesStoryIdExplorationNodesGet`: PaginatedResponseExplorationNodeResponse
	fmt.Fprintf(os.Stdout, "Response from `AuthoringAPI.ListAuthoringExplorationNodesV1AuthoringStoriesStoryIdExplorationNodesGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**storyId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiListAuthoringExplorationNodesV1AuthoringStoriesStoryIdExplorationNodesGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **parentNodeId** | **string** |  | 
 **essential** | **bool** |  | 
 **cursor** | **string** |  | 
 **limit** | **int32** |  | [default to 50]

### Return type

[**PaginatedResponseExplorationNodeResponse**](PaginatedResponseExplorationNodeResponse.md)

### Authorization

[PlayerId](../README.md#PlayerId), [PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListStoriesV1AuthoringStoriesGet

> PaginatedResponseAuthoringStorySummaryResponse ListStoriesV1AuthoringStoriesGet(ctx).Cursor(cursor).Limit(limit).Execute()

List Stories



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
	cursor := "cursor_example" // string |  (optional)
	limit := int32(56) // int32 |  (optional) (default to 20)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AuthoringAPI.ListStoriesV1AuthoringStoriesGet(context.Background()).Cursor(cursor).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthoringAPI.ListStoriesV1AuthoringStoriesGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListStoriesV1AuthoringStoriesGet`: PaginatedResponseAuthoringStorySummaryResponse
	fmt.Fprintf(os.Stdout, "Response from `AuthoringAPI.ListStoriesV1AuthoringStoriesGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListStoriesV1AuthoringStoriesGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **cursor** | **string** |  | 
 **limit** | **int32** |  | [default to 20]

### Return type

[**PaginatedResponseAuthoringStorySummaryResponse**](PaginatedResponseAuthoringStorySummaryResponse.md)

### Authorization

[PlayerId](../README.md#PlayerId), [PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PatchAuthoringExplorationNodeV1AuthoringStoriesStoryIdExplorationNodesNodeIdPatch

> ExplorationNodeResponse PatchAuthoringExplorationNodeV1AuthoringStoriesStoryIdExplorationNodesNodeIdPatch(ctx, storyId, nodeId).PatchExplorationNodeRequest(patchExplorationNodeRequest).Execute()

Patch Authoring Exploration Node



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
	patchExplorationNodeRequest := *openapiclient.NewPatchExplorationNodeRequest() // PatchExplorationNodeRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AuthoringAPI.PatchAuthoringExplorationNodeV1AuthoringStoriesStoryIdExplorationNodesNodeIdPatch(context.Background(), storyId, nodeId).PatchExplorationNodeRequest(patchExplorationNodeRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthoringAPI.PatchAuthoringExplorationNodeV1AuthoringStoriesStoryIdExplorationNodesNodeIdPatch``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PatchAuthoringExplorationNodeV1AuthoringStoriesStoryIdExplorationNodesNodeIdPatch`: ExplorationNodeResponse
	fmt.Fprintf(os.Stdout, "Response from `AuthoringAPI.PatchAuthoringExplorationNodeV1AuthoringStoriesStoryIdExplorationNodesNodeIdPatch`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**storyId** | **string** |  | 
**nodeId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiPatchAuthoringExplorationNodeV1AuthoringStoriesStoryIdExplorationNodesNodeIdPatchRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **patchExplorationNodeRequest** | [**PatchExplorationNodeRequest**](PatchExplorationNodeRequest.md) |  | 

### Return type

[**ExplorationNodeResponse**](ExplorationNodeResponse.md)

### Authorization

[PlayerId](../README.md#PlayerId), [PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## StreamJobStatusV1AuthoringJobsJobIdStreamGet

> interface{} StreamJobStatusV1AuthoringJobsJobIdStreamGet(ctx, jobId).Execute()

Stream Job Status



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
	resp, r, err := apiClient.AuthoringAPI.StreamJobStatusV1AuthoringJobsJobIdStreamGet(context.Background(), jobId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthoringAPI.StreamJobStatusV1AuthoringJobsJobIdStreamGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `StreamJobStatusV1AuthoringJobsJobIdStreamGet`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `AuthoringAPI.StreamJobStatusV1AuthoringJobsJobIdStreamGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**jobId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiStreamJobStatusV1AuthoringJobsJobIdStreamGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

**interface{}**

### Authorization

[PlayerId](../README.md#PlayerId), [PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

