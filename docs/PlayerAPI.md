# \PlayerAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AcceptTosV1TermsAcceptPost**](PlayerAPI.md#AcceptTosV1TermsAcceptPost) | **Post** /v1/terms/accept | Accept Tos
[**AcknowledgeWarningsV1PlayerPlayerIdStoryStoryIdWarningsAcknowledgePost**](PlayerAPI.md#AcknowledgeWarningsV1PlayerPlayerIdStoryStoryIdWarningsAcknowledgePost) | **Post** /v1/player/{player_id}/story/{story_id}/warnings/acknowledge | Acknowledge Warnings
[**ErasePlayerDataV1PlayerPlayerIdDelete**](PlayerAPI.md#ErasePlayerDataV1PlayerPlayerIdDelete) | **Delete** /v1/player/{player_id} | Erase Player Data
[**ExploreNodeV1StoryStoryIdExplorePost**](PlayerAPI.md#ExploreNodeV1StoryStoryIdExplorePost) | **Post** /v1/story/{story_id}/explore | Explore Node
[**ExportPlayerDataV1PlayerPlayerIdDataExportGet**](PlayerAPI.md#ExportPlayerDataV1PlayerPlayerIdDataExportGet) | **Get** /v1/player/{player_id}/data-export | Export Player Data
[**GetCurrentTosV1TermsGet**](PlayerAPI.md#GetCurrentTosV1TermsGet) | **Get** /v1/terms | Get Current Tos
[**GetEntityIndexV1StoryStoryIdSessionEntityIndexGet**](PlayerAPI.md#GetEntityIndexV1StoryStoryIdSessionEntityIndexGet) | **Get** /v1/story/{story_id}/session/entity-index | Get Entity Index
[**GetExplorationStateV1StoryStoryIdExplorationStateGet**](PlayerAPI.md#GetExplorationStateV1StoryStoryIdExplorationStateGet) | **Get** /v1/story/{story_id}/exploration-state | Get Exploration State
[**GetGraphTopologyV1StoryStoryIdGraphGet**](PlayerAPI.md#GetGraphTopologyV1StoryStoryIdGraphGet) | **Get** /v1/story/{story_id}/graph | Get Graph Topology
[**GetNodeArcV1StoryStoryIdNodeNodeIdArcGet**](PlayerAPI.md#GetNodeArcV1StoryStoryIdNodeNodeIdArcGet) | **Get** /v1/story/{story_id}/node/{node_id}/arc | Get Node Arc
[**GetNodeV1StoryStoryIdNodeNodeIdGet**](PlayerAPI.md#GetNodeV1StoryStoryIdNodeNodeIdGet) | **Get** /v1/story/{story_id}/node/{node_id} | Get Node
[**GetOrCreateSessionV1StoryStoryIdSessionGet**](PlayerAPI.md#GetOrCreateSessionV1StoryStoryIdSessionGet) | **Get** /v1/story/{story_id}/session | Get Or Create Session
[**GetStoryPathsV1StoryStoryIdPathsGet**](PlayerAPI.md#GetStoryPathsV1StoryStoryIdPathsGet) | **Get** /v1/story/{story_id}/paths | Get Story Paths
[**GetTosStatusV1PlayerPlayerIdTosStatusGet**](PlayerAPI.md#GetTosStatusV1PlayerPlayerIdTosStatusGet) | **Get** /v1/player/{player_id}/tos-status | Get Tos Status
[**HealthV1HealthGet**](PlayerAPI.md#HealthV1HealthGet) | **Get** /v1/health | Health
[**ListPlayerExplorationNodesV1StoryStoryIdExplorationNodesGet**](PlayerAPI.md#ListPlayerExplorationNodesV1StoryStoryIdExplorationNodesGet) | **Get** /v1/story/{story_id}/exploration-nodes | List Player Exploration Nodes
[**ListStoriesV1StoriesGet**](PlayerAPI.md#ListStoriesV1StoriesGet) | **Get** /v1/stories | List Stories
[**PickExplorationNodeV1StoryStoryIdExplorationNodesNodeIdPickPost**](PlayerAPI.md#PickExplorationNodeV1StoryStoryIdExplorationNodesNodeIdPickPost) | **Post** /v1/story/{story_id}/exploration-nodes/{node_id}/pick | Pick Exploration Node
[**ReleaseSessionLockV1StoryStoryIdSessionLockDelete**](PlayerAPI.md#ReleaseSessionLockV1StoryStoryIdSessionLockDelete) | **Delete** /v1/story/{story_id}/session/lock | Release Session Lock
[**ResetSessionV1StoryStoryIdSessionResetPost**](PlayerAPI.md#ResetSessionV1StoryStoryIdSessionResetPost) | **Post** /v1/story/{story_id}/session/reset | Reset Session
[**SubmitChoiceV1StoryStoryIdChoicePost**](PlayerAPI.md#SubmitChoiceV1StoryStoryIdChoicePost) | **Post** /v1/story/{story_id}/choice | Submit Choice
[**SubmitFreeTextV1StoryStoryIdFreeTextPost**](PlayerAPI.md#SubmitFreeTextV1StoryStoryIdFreeTextPost) | **Post** /v1/story/{story_id}/free-text | Submit Free Text
[**UnpickExplorationNodeV1StoryStoryIdExplorationNodesNodeIdPickDelete**](PlayerAPI.md#UnpickExplorationNodeV1StoryStoryIdExplorationNodesNodeIdPickDelete) | **Delete** /v1/story/{story_id}/exploration-nodes/{node_id}/pick | Unpick Exploration Node



## AcceptTosV1TermsAcceptPost

> AcceptTosV1TermsAcceptPost(ctx).AcceptToSRequest(acceptToSRequest).Execute()

Accept Tos



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
	acceptToSRequest := *openapiclient.NewAcceptToSRequest("TosVersionId_example") // AcceptToSRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.PlayerAPI.AcceptTosV1TermsAcceptPost(context.Background()).AcceptToSRequest(acceptToSRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PlayerAPI.AcceptTosV1TermsAcceptPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiAcceptTosV1TermsAcceptPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **acceptToSRequest** | [**AcceptToSRequest**](AcceptToSRequest.md) |  | 

### Return type

 (empty response body)

### Authorization

[PlayerId](../README.md#PlayerId), [PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## AcknowledgeWarningsV1PlayerPlayerIdStoryStoryIdWarningsAcknowledgePost

> AcknowledgeWarningsV1PlayerPlayerIdStoryStoryIdWarningsAcknowledgePost(ctx, playerId, storyId).Execute()

Acknowledge Warnings



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
	r, err := apiClient.PlayerAPI.AcknowledgeWarningsV1PlayerPlayerIdStoryStoryIdWarningsAcknowledgePost(context.Background(), playerId, storyId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PlayerAPI.AcknowledgeWarningsV1PlayerPlayerIdStoryStoryIdWarningsAcknowledgePost``: %v\n", err)
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

Other parameters are passed through a pointer to a apiAcknowledgeWarningsV1PlayerPlayerIdStoryStoryIdWarningsAcknowledgePostRequest struct via the builder pattern


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


## ErasePlayerDataV1PlayerPlayerIdDelete

> PlayerErasureResponse ErasePlayerDataV1PlayerPlayerIdDelete(ctx, playerId).Execute()

Erase Player Data



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
	resp, r, err := apiClient.PlayerAPI.ErasePlayerDataV1PlayerPlayerIdDelete(context.Background(), playerId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PlayerAPI.ErasePlayerDataV1PlayerPlayerIdDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ErasePlayerDataV1PlayerPlayerIdDelete`: PlayerErasureResponse
	fmt.Fprintf(os.Stdout, "Response from `PlayerAPI.ErasePlayerDataV1PlayerPlayerIdDelete`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**playerId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiErasePlayerDataV1PlayerPlayerIdDeleteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**PlayerErasureResponse**](PlayerErasureResponse.md)

### Authorization

[PlayerId](../README.md#PlayerId), [PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ExploreNodeV1StoryStoryIdExplorePost

> interface{} ExploreNodeV1StoryStoryIdExplorePost(ctx, storyId).ExplorationRequest(explorationRequest).Execute()

Explore Node



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
	explorationRequest := *openapiclient.NewExplorationRequest("NodeId_example", "Question_example", "IdempotencyKey_example") // ExplorationRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PlayerAPI.ExploreNodeV1StoryStoryIdExplorePost(context.Background(), storyId).ExplorationRequest(explorationRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PlayerAPI.ExploreNodeV1StoryStoryIdExplorePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ExploreNodeV1StoryStoryIdExplorePost`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `PlayerAPI.ExploreNodeV1StoryStoryIdExplorePost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**storyId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiExploreNodeV1StoryStoryIdExplorePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **explorationRequest** | [**ExplorationRequest**](ExplorationRequest.md) |  | 

### Return type

**interface{}**

### Authorization

[PlayerId](../README.md#PlayerId), [PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ExportPlayerDataV1PlayerPlayerIdDataExportGet

> PlayerDataExportResponse ExportPlayerDataV1PlayerPlayerIdDataExportGet(ctx, playerId).Execute()

Export Player Data



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
	resp, r, err := apiClient.PlayerAPI.ExportPlayerDataV1PlayerPlayerIdDataExportGet(context.Background(), playerId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PlayerAPI.ExportPlayerDataV1PlayerPlayerIdDataExportGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ExportPlayerDataV1PlayerPlayerIdDataExportGet`: PlayerDataExportResponse
	fmt.Fprintf(os.Stdout, "Response from `PlayerAPI.ExportPlayerDataV1PlayerPlayerIdDataExportGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**playerId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiExportPlayerDataV1PlayerPlayerIdDataExportGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**PlayerDataExportResponse**](PlayerDataExportResponse.md)

### Authorization

[PlayerId](../README.md#PlayerId), [PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetCurrentTosV1TermsGet

> ToSVersionResponse GetCurrentTosV1TermsGet(ctx).Execute()

Get Current Tos



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
	resp, r, err := apiClient.PlayerAPI.GetCurrentTosV1TermsGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PlayerAPI.GetCurrentTosV1TermsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCurrentTosV1TermsGet`: ToSVersionResponse
	fmt.Fprintf(os.Stdout, "Response from `PlayerAPI.GetCurrentTosV1TermsGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetCurrentTosV1TermsGetRequest struct via the builder pattern


### Return type

[**ToSVersionResponse**](ToSVersionResponse.md)

### Authorization

[PlayerId](../README.md#PlayerId), [PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetEntityIndexV1StoryStoryIdSessionEntityIndexGet

> EntityIndexResponse GetEntityIndexV1StoryStoryIdSessionEntityIndexGet(ctx, storyId).Execute()

Get Entity Index



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
	resp, r, err := apiClient.PlayerAPI.GetEntityIndexV1StoryStoryIdSessionEntityIndexGet(context.Background(), storyId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PlayerAPI.GetEntityIndexV1StoryStoryIdSessionEntityIndexGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetEntityIndexV1StoryStoryIdSessionEntityIndexGet`: EntityIndexResponse
	fmt.Fprintf(os.Stdout, "Response from `PlayerAPI.GetEntityIndexV1StoryStoryIdSessionEntityIndexGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**storyId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetEntityIndexV1StoryStoryIdSessionEntityIndexGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**EntityIndexResponse**](EntityIndexResponse.md)

### Authorization

[PlayerId](../README.md#PlayerId), [PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetExplorationStateV1StoryStoryIdExplorationStateGet

> ExplorationStateResponse GetExplorationStateV1StoryStoryIdExplorationStateGet(ctx, storyId).NodeId(nodeId).Execute()

Get Exploration State



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
	resp, r, err := apiClient.PlayerAPI.GetExplorationStateV1StoryStoryIdExplorationStateGet(context.Background(), storyId).NodeId(nodeId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PlayerAPI.GetExplorationStateV1StoryStoryIdExplorationStateGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetExplorationStateV1StoryStoryIdExplorationStateGet`: ExplorationStateResponse
	fmt.Fprintf(os.Stdout, "Response from `PlayerAPI.GetExplorationStateV1StoryStoryIdExplorationStateGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**storyId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetExplorationStateV1StoryStoryIdExplorationStateGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **nodeId** | **string** |  | 

### Return type

[**ExplorationStateResponse**](ExplorationStateResponse.md)

### Authorization

[PlayerId](../README.md#PlayerId), [PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetGraphTopologyV1StoryStoryIdGraphGet

> GraphTopologyResponse GetGraphTopologyV1StoryStoryIdGraphGet(ctx, storyId).Execute()

Get Graph Topology



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
	resp, r, err := apiClient.PlayerAPI.GetGraphTopologyV1StoryStoryIdGraphGet(context.Background(), storyId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PlayerAPI.GetGraphTopologyV1StoryStoryIdGraphGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetGraphTopologyV1StoryStoryIdGraphGet`: GraphTopologyResponse
	fmt.Fprintf(os.Stdout, "Response from `PlayerAPI.GetGraphTopologyV1StoryStoryIdGraphGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**storyId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetGraphTopologyV1StoryStoryIdGraphGetRequest struct via the builder pattern


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


## GetNodeArcV1StoryStoryIdNodeNodeIdArcGet

> ArcAnalysis GetNodeArcV1StoryStoryIdNodeNodeIdArcGet(ctx, storyId, nodeId).Execute()

Get Node Arc



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
	resp, r, err := apiClient.PlayerAPI.GetNodeArcV1StoryStoryIdNodeNodeIdArcGet(context.Background(), storyId, nodeId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PlayerAPI.GetNodeArcV1StoryStoryIdNodeNodeIdArcGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetNodeArcV1StoryStoryIdNodeNodeIdArcGet`: ArcAnalysis
	fmt.Fprintf(os.Stdout, "Response from `PlayerAPI.GetNodeArcV1StoryStoryIdNodeNodeIdArcGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**storyId** | **string** |  | 
**nodeId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetNodeArcV1StoryStoryIdNodeNodeIdArcGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**ArcAnalysis**](ArcAnalysis.md)

### Authorization

[PlayerId](../README.md#PlayerId), [PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetNodeV1StoryStoryIdNodeNodeIdGet

> NodeResponse GetNodeV1StoryStoryIdNodeNodeIdGet(ctx, storyId, nodeId).Execute()

Get Node



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
	resp, r, err := apiClient.PlayerAPI.GetNodeV1StoryStoryIdNodeNodeIdGet(context.Background(), storyId, nodeId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PlayerAPI.GetNodeV1StoryStoryIdNodeNodeIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetNodeV1StoryStoryIdNodeNodeIdGet`: NodeResponse
	fmt.Fprintf(os.Stdout, "Response from `PlayerAPI.GetNodeV1StoryStoryIdNodeNodeIdGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**storyId** | **string** |  | 
**nodeId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetNodeV1StoryStoryIdNodeNodeIdGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**NodeResponse**](NodeResponse.md)

### Authorization

[PlayerId](../README.md#PlayerId), [PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetOrCreateSessionV1StoryStoryIdSessionGet

> SessionResponse GetOrCreateSessionV1StoryStoryIdSessionGet(ctx, storyId).Execute()

Get Or Create Session



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
	resp, r, err := apiClient.PlayerAPI.GetOrCreateSessionV1StoryStoryIdSessionGet(context.Background(), storyId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PlayerAPI.GetOrCreateSessionV1StoryStoryIdSessionGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetOrCreateSessionV1StoryStoryIdSessionGet`: SessionResponse
	fmt.Fprintf(os.Stdout, "Response from `PlayerAPI.GetOrCreateSessionV1StoryStoryIdSessionGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**storyId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetOrCreateSessionV1StoryStoryIdSessionGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**SessionResponse**](SessionResponse.md)

### Authorization

[PlayerId](../README.md#PlayerId), [PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetStoryPathsV1StoryStoryIdPathsGet

> PathsResponse GetStoryPathsV1StoryStoryIdPathsGet(ctx, storyId).Execute()

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
	resp, r, err := apiClient.PlayerAPI.GetStoryPathsV1StoryStoryIdPathsGet(context.Background(), storyId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PlayerAPI.GetStoryPathsV1StoryStoryIdPathsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetStoryPathsV1StoryStoryIdPathsGet`: PathsResponse
	fmt.Fprintf(os.Stdout, "Response from `PlayerAPI.GetStoryPathsV1StoryStoryIdPathsGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**storyId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetStoryPathsV1StoryStoryIdPathsGetRequest struct via the builder pattern


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


## GetTosStatusV1PlayerPlayerIdTosStatusGet

> ToSStatusResponse GetTosStatusV1PlayerPlayerIdTosStatusGet(ctx, playerId).Execute()

Get Tos Status



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
	resp, r, err := apiClient.PlayerAPI.GetTosStatusV1PlayerPlayerIdTosStatusGet(context.Background(), playerId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PlayerAPI.GetTosStatusV1PlayerPlayerIdTosStatusGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTosStatusV1PlayerPlayerIdTosStatusGet`: ToSStatusResponse
	fmt.Fprintf(os.Stdout, "Response from `PlayerAPI.GetTosStatusV1PlayerPlayerIdTosStatusGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**playerId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetTosStatusV1PlayerPlayerIdTosStatusGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ToSStatusResponse**](ToSStatusResponse.md)

### Authorization

[PlayerId](../README.md#PlayerId), [PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## HealthV1HealthGet

> HealthResponse HealthV1HealthGet(ctx).Execute()

Health



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
	resp, r, err := apiClient.PlayerAPI.HealthV1HealthGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PlayerAPI.HealthV1HealthGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `HealthV1HealthGet`: HealthResponse
	fmt.Fprintf(os.Stdout, "Response from `PlayerAPI.HealthV1HealthGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiHealthV1HealthGetRequest struct via the builder pattern


### Return type

[**HealthResponse**](HealthResponse.md)

### Authorization

[PlayerId](../README.md#PlayerId), [PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListPlayerExplorationNodesV1StoryStoryIdExplorationNodesGet

> []ExplorationNodeResponse ListPlayerExplorationNodesV1StoryStoryIdExplorationNodesGet(ctx, storyId).ParentNodeId(parentNodeId).Execute()

List Player Exploration Nodes



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
	parentNodeId := "parentNodeId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PlayerAPI.ListPlayerExplorationNodesV1StoryStoryIdExplorationNodesGet(context.Background(), storyId).ParentNodeId(parentNodeId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PlayerAPI.ListPlayerExplorationNodesV1StoryStoryIdExplorationNodesGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListPlayerExplorationNodesV1StoryStoryIdExplorationNodesGet`: []ExplorationNodeResponse
	fmt.Fprintf(os.Stdout, "Response from `PlayerAPI.ListPlayerExplorationNodesV1StoryStoryIdExplorationNodesGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**storyId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiListPlayerExplorationNodesV1StoryStoryIdExplorationNodesGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **parentNodeId** | **string** |  | 

### Return type

[**[]ExplorationNodeResponse**](ExplorationNodeResponse.md)

### Authorization

[PlayerId](../README.md#PlayerId), [PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListStoriesV1StoriesGet

> PaginatedResponseStorySummaryResponse ListStoriesV1StoriesGet(ctx).Cursor(cursor).Limit(limit).Execute()

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
	resp, r, err := apiClient.PlayerAPI.ListStoriesV1StoriesGet(context.Background()).Cursor(cursor).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PlayerAPI.ListStoriesV1StoriesGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListStoriesV1StoriesGet`: PaginatedResponseStorySummaryResponse
	fmt.Fprintf(os.Stdout, "Response from `PlayerAPI.ListStoriesV1StoriesGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListStoriesV1StoriesGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **cursor** | **string** |  | 
 **limit** | **int32** |  | [default to 20]

### Return type

[**PaginatedResponseStorySummaryResponse**](PaginatedResponseStorySummaryResponse.md)

### Authorization

[PlayerId](../README.md#PlayerId), [PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PickExplorationNodeV1StoryStoryIdExplorationNodesNodeIdPickPost

> ExplorationPickResponse PickExplorationNodeV1StoryStoryIdExplorationNodesNodeIdPickPost(ctx, storyId, nodeId).Execute()

Pick Exploration Node



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
	resp, r, err := apiClient.PlayerAPI.PickExplorationNodeV1StoryStoryIdExplorationNodesNodeIdPickPost(context.Background(), storyId, nodeId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PlayerAPI.PickExplorationNodeV1StoryStoryIdExplorationNodesNodeIdPickPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PickExplorationNodeV1StoryStoryIdExplorationNodesNodeIdPickPost`: ExplorationPickResponse
	fmt.Fprintf(os.Stdout, "Response from `PlayerAPI.PickExplorationNodeV1StoryStoryIdExplorationNodesNodeIdPickPost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**storyId** | **string** |  | 
**nodeId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiPickExplorationNodeV1StoryStoryIdExplorationNodesNodeIdPickPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**ExplorationPickResponse**](ExplorationPickResponse.md)

### Authorization

[PlayerId](../README.md#PlayerId), [PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ReleaseSessionLockV1StoryStoryIdSessionLockDelete

> ReleaseSessionLockV1StoryStoryIdSessionLockDelete(ctx, storyId).XSessionLockToken(xSessionLockToken).Execute()

Release Session Lock



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
	xSessionLockToken := "xSessionLockToken_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.PlayerAPI.ReleaseSessionLockV1StoryStoryIdSessionLockDelete(context.Background(), storyId).XSessionLockToken(xSessionLockToken).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PlayerAPI.ReleaseSessionLockV1StoryStoryIdSessionLockDelete``: %v\n", err)
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

Other parameters are passed through a pointer to a apiReleaseSessionLockV1StoryStoryIdSessionLockDeleteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xSessionLockToken** | **string** |  | 

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


## ResetSessionV1StoryStoryIdSessionResetPost

> SessionResponse ResetSessionV1StoryStoryIdSessionResetPost(ctx, storyId).Force(force).Execute()

Reset Session



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
	force := true // bool |  (optional) (default to false)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PlayerAPI.ResetSessionV1StoryStoryIdSessionResetPost(context.Background(), storyId).Force(force).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PlayerAPI.ResetSessionV1StoryStoryIdSessionResetPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ResetSessionV1StoryStoryIdSessionResetPost`: SessionResponse
	fmt.Fprintf(os.Stdout, "Response from `PlayerAPI.ResetSessionV1StoryStoryIdSessionResetPost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**storyId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiResetSessionV1StoryStoryIdSessionResetPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **force** | **bool** |  | [default to false]

### Return type

[**SessionResponse**](SessionResponse.md)

### Authorization

[PlayerId](../README.md#PlayerId), [PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SubmitChoiceV1StoryStoryIdChoicePost

> NodeResponse SubmitChoiceV1StoryStoryIdChoicePost(ctx, storyId).ChoiceRequest(choiceRequest).Execute()

Submit Choice



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
	choiceRequest := *openapiclient.NewChoiceRequest("ChoiceId_example", "NodeId_example", "IdempotencyKey_example") // ChoiceRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PlayerAPI.SubmitChoiceV1StoryStoryIdChoicePost(context.Background(), storyId).ChoiceRequest(choiceRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PlayerAPI.SubmitChoiceV1StoryStoryIdChoicePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SubmitChoiceV1StoryStoryIdChoicePost`: NodeResponse
	fmt.Fprintf(os.Stdout, "Response from `PlayerAPI.SubmitChoiceV1StoryStoryIdChoicePost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**storyId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSubmitChoiceV1StoryStoryIdChoicePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **choiceRequest** | [**ChoiceRequest**](ChoiceRequest.md) |  | 

### Return type

[**NodeResponse**](NodeResponse.md)

### Authorization

[PlayerId](../README.md#PlayerId), [PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json, text/event-stream

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SubmitFreeTextV1StoryStoryIdFreeTextPost

> interface{} SubmitFreeTextV1StoryStoryIdFreeTextPost(ctx, storyId).FreeTextRequest(freeTextRequest).Execute()

Submit Free Text



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
	freeTextRequest := *openapiclient.NewFreeTextRequest("NodeId_example", "FreeText_example", "IdempotencyKey_example") // FreeTextRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PlayerAPI.SubmitFreeTextV1StoryStoryIdFreeTextPost(context.Background(), storyId).FreeTextRequest(freeTextRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PlayerAPI.SubmitFreeTextV1StoryStoryIdFreeTextPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SubmitFreeTextV1StoryStoryIdFreeTextPost`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `PlayerAPI.SubmitFreeTextV1StoryStoryIdFreeTextPost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**storyId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSubmitFreeTextV1StoryStoryIdFreeTextPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **freeTextRequest** | [**FreeTextRequest**](FreeTextRequest.md) |  | 

### Return type

**interface{}**

### Authorization

[PlayerId](../README.md#PlayerId), [PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json, text/event-stream

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UnpickExplorationNodeV1StoryStoryIdExplorationNodesNodeIdPickDelete

> ExplorationPickResponse UnpickExplorationNodeV1StoryStoryIdExplorationNodesNodeIdPickDelete(ctx, storyId, nodeId).Execute()

Unpick Exploration Node



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
	resp, r, err := apiClient.PlayerAPI.UnpickExplorationNodeV1StoryStoryIdExplorationNodesNodeIdPickDelete(context.Background(), storyId, nodeId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PlayerAPI.UnpickExplorationNodeV1StoryStoryIdExplorationNodesNodeIdPickDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UnpickExplorationNodeV1StoryStoryIdExplorationNodesNodeIdPickDelete`: ExplorationPickResponse
	fmt.Fprintf(os.Stdout, "Response from `PlayerAPI.UnpickExplorationNodeV1StoryStoryIdExplorationNodesNodeIdPickDelete`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**storyId** | **string** |  | 
**nodeId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUnpickExplorationNodeV1StoryStoryIdExplorationNodesNodeIdPickDeleteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**ExplorationPickResponse**](ExplorationPickResponse.md)

### Authorization

[PlayerId](../README.md#PlayerId), [PlayerApiKey](../README.md#PlayerApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

