# V1StoryStoryIdSessionGet200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CurrentNodeId** | **string** |  | 
**DiscoveredCharacters** | [**map[string]V1AdminStoryStoryIdGet200ResponseCharactersValue**](V1AdminStoryStoryIdGet200ResponseCharactersValue.md) |  | 
**DiscoveredFlagSchema** | **map[string]map[string]interface{}** |  | 
**DiscoveredLocations** | [**map[string]V1AdminStoryStoryIdGet200ResponseLocationsValue**](V1AdminStoryStoryIdGet200ResponseLocationsValue.md) |  | 
**DiscoveredObjects** | [**map[string]V1AdminStoryStoryIdGet200ResponseObjectsValue**](V1AdminStoryStoryIdGet200ResponseObjectsValue.md) |  | 
**IsCompleted** | **bool** |  | 
**LockToken** | Pointer to **string** |  | [optional] 
**NodesVisited** | **int32** |  | 
**PlaythroughId** | **string** |  | 
**SessionId** | **string** |  | 
**WarningsAcknowledgedAt** | Pointer to **string** |  | [optional] 
**WorldFlags** | **map[string]map[string]interface{}** |  | 

## Methods

### NewV1StoryStoryIdSessionGet200Response

`func NewV1StoryStoryIdSessionGet200Response(currentNodeId string, discoveredCharacters map[string]V1AdminStoryStoryIdGet200ResponseCharactersValue, discoveredFlagSchema map[string]map[string]interface{}, discoveredLocations map[string]V1AdminStoryStoryIdGet200ResponseLocationsValue, discoveredObjects map[string]V1AdminStoryStoryIdGet200ResponseObjectsValue, isCompleted bool, nodesVisited int32, playthroughId string, sessionId string, worldFlags map[string]map[string]interface{}, ) *V1StoryStoryIdSessionGet200Response`

NewV1StoryStoryIdSessionGet200Response instantiates a new V1StoryStoryIdSessionGet200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1StoryStoryIdSessionGet200ResponseWithDefaults

`func NewV1StoryStoryIdSessionGet200ResponseWithDefaults() *V1StoryStoryIdSessionGet200Response`

NewV1StoryStoryIdSessionGet200ResponseWithDefaults instantiates a new V1StoryStoryIdSessionGet200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCurrentNodeId

`func (o *V1StoryStoryIdSessionGet200Response) GetCurrentNodeId() string`

GetCurrentNodeId returns the CurrentNodeId field if non-nil, zero value otherwise.

### GetCurrentNodeIdOk

`func (o *V1StoryStoryIdSessionGet200Response) GetCurrentNodeIdOk() (*string, bool)`

GetCurrentNodeIdOk returns a tuple with the CurrentNodeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentNodeId

`func (o *V1StoryStoryIdSessionGet200Response) SetCurrentNodeId(v string)`

SetCurrentNodeId sets CurrentNodeId field to given value.


### GetDiscoveredCharacters

`func (o *V1StoryStoryIdSessionGet200Response) GetDiscoveredCharacters() map[string]V1AdminStoryStoryIdGet200ResponseCharactersValue`

GetDiscoveredCharacters returns the DiscoveredCharacters field if non-nil, zero value otherwise.

### GetDiscoveredCharactersOk

`func (o *V1StoryStoryIdSessionGet200Response) GetDiscoveredCharactersOk() (*map[string]V1AdminStoryStoryIdGet200ResponseCharactersValue, bool)`

GetDiscoveredCharactersOk returns a tuple with the DiscoveredCharacters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscoveredCharacters

`func (o *V1StoryStoryIdSessionGet200Response) SetDiscoveredCharacters(v map[string]V1AdminStoryStoryIdGet200ResponseCharactersValue)`

SetDiscoveredCharacters sets DiscoveredCharacters field to given value.


### GetDiscoveredFlagSchema

`func (o *V1StoryStoryIdSessionGet200Response) GetDiscoveredFlagSchema() map[string]map[string]interface{}`

GetDiscoveredFlagSchema returns the DiscoveredFlagSchema field if non-nil, zero value otherwise.

### GetDiscoveredFlagSchemaOk

`func (o *V1StoryStoryIdSessionGet200Response) GetDiscoveredFlagSchemaOk() (*map[string]map[string]interface{}, bool)`

GetDiscoveredFlagSchemaOk returns a tuple with the DiscoveredFlagSchema field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscoveredFlagSchema

`func (o *V1StoryStoryIdSessionGet200Response) SetDiscoveredFlagSchema(v map[string]map[string]interface{})`

SetDiscoveredFlagSchema sets DiscoveredFlagSchema field to given value.


### GetDiscoveredLocations

`func (o *V1StoryStoryIdSessionGet200Response) GetDiscoveredLocations() map[string]V1AdminStoryStoryIdGet200ResponseLocationsValue`

GetDiscoveredLocations returns the DiscoveredLocations field if non-nil, zero value otherwise.

### GetDiscoveredLocationsOk

`func (o *V1StoryStoryIdSessionGet200Response) GetDiscoveredLocationsOk() (*map[string]V1AdminStoryStoryIdGet200ResponseLocationsValue, bool)`

GetDiscoveredLocationsOk returns a tuple with the DiscoveredLocations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscoveredLocations

`func (o *V1StoryStoryIdSessionGet200Response) SetDiscoveredLocations(v map[string]V1AdminStoryStoryIdGet200ResponseLocationsValue)`

SetDiscoveredLocations sets DiscoveredLocations field to given value.


### GetDiscoveredObjects

`func (o *V1StoryStoryIdSessionGet200Response) GetDiscoveredObjects() map[string]V1AdminStoryStoryIdGet200ResponseObjectsValue`

GetDiscoveredObjects returns the DiscoveredObjects field if non-nil, zero value otherwise.

### GetDiscoveredObjectsOk

`func (o *V1StoryStoryIdSessionGet200Response) GetDiscoveredObjectsOk() (*map[string]V1AdminStoryStoryIdGet200ResponseObjectsValue, bool)`

GetDiscoveredObjectsOk returns a tuple with the DiscoveredObjects field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscoveredObjects

`func (o *V1StoryStoryIdSessionGet200Response) SetDiscoveredObjects(v map[string]V1AdminStoryStoryIdGet200ResponseObjectsValue)`

SetDiscoveredObjects sets DiscoveredObjects field to given value.


### GetIsCompleted

`func (o *V1StoryStoryIdSessionGet200Response) GetIsCompleted() bool`

GetIsCompleted returns the IsCompleted field if non-nil, zero value otherwise.

### GetIsCompletedOk

`func (o *V1StoryStoryIdSessionGet200Response) GetIsCompletedOk() (*bool, bool)`

GetIsCompletedOk returns a tuple with the IsCompleted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsCompleted

`func (o *V1StoryStoryIdSessionGet200Response) SetIsCompleted(v bool)`

SetIsCompleted sets IsCompleted field to given value.


### GetLockToken

`func (o *V1StoryStoryIdSessionGet200Response) GetLockToken() string`

GetLockToken returns the LockToken field if non-nil, zero value otherwise.

### GetLockTokenOk

`func (o *V1StoryStoryIdSessionGet200Response) GetLockTokenOk() (*string, bool)`

GetLockTokenOk returns a tuple with the LockToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLockToken

`func (o *V1StoryStoryIdSessionGet200Response) SetLockToken(v string)`

SetLockToken sets LockToken field to given value.

### HasLockToken

`func (o *V1StoryStoryIdSessionGet200Response) HasLockToken() bool`

HasLockToken returns a boolean if a field has been set.

### GetNodesVisited

`func (o *V1StoryStoryIdSessionGet200Response) GetNodesVisited() int32`

GetNodesVisited returns the NodesVisited field if non-nil, zero value otherwise.

### GetNodesVisitedOk

`func (o *V1StoryStoryIdSessionGet200Response) GetNodesVisitedOk() (*int32, bool)`

GetNodesVisitedOk returns a tuple with the NodesVisited field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNodesVisited

`func (o *V1StoryStoryIdSessionGet200Response) SetNodesVisited(v int32)`

SetNodesVisited sets NodesVisited field to given value.


### GetPlaythroughId

`func (o *V1StoryStoryIdSessionGet200Response) GetPlaythroughId() string`

GetPlaythroughId returns the PlaythroughId field if non-nil, zero value otherwise.

### GetPlaythroughIdOk

`func (o *V1StoryStoryIdSessionGet200Response) GetPlaythroughIdOk() (*string, bool)`

GetPlaythroughIdOk returns a tuple with the PlaythroughId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlaythroughId

`func (o *V1StoryStoryIdSessionGet200Response) SetPlaythroughId(v string)`

SetPlaythroughId sets PlaythroughId field to given value.


### GetSessionId

`func (o *V1StoryStoryIdSessionGet200Response) GetSessionId() string`

GetSessionId returns the SessionId field if non-nil, zero value otherwise.

### GetSessionIdOk

`func (o *V1StoryStoryIdSessionGet200Response) GetSessionIdOk() (*string, bool)`

GetSessionIdOk returns a tuple with the SessionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSessionId

`func (o *V1StoryStoryIdSessionGet200Response) SetSessionId(v string)`

SetSessionId sets SessionId field to given value.


### GetWarningsAcknowledgedAt

`func (o *V1StoryStoryIdSessionGet200Response) GetWarningsAcknowledgedAt() string`

GetWarningsAcknowledgedAt returns the WarningsAcknowledgedAt field if non-nil, zero value otherwise.

### GetWarningsAcknowledgedAtOk

`func (o *V1StoryStoryIdSessionGet200Response) GetWarningsAcknowledgedAtOk() (*string, bool)`

GetWarningsAcknowledgedAtOk returns a tuple with the WarningsAcknowledgedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarningsAcknowledgedAt

`func (o *V1StoryStoryIdSessionGet200Response) SetWarningsAcknowledgedAt(v string)`

SetWarningsAcknowledgedAt sets WarningsAcknowledgedAt field to given value.

### HasWarningsAcknowledgedAt

`func (o *V1StoryStoryIdSessionGet200Response) HasWarningsAcknowledgedAt() bool`

HasWarningsAcknowledgedAt returns a boolean if a field has been set.

### GetWorldFlags

`func (o *V1StoryStoryIdSessionGet200Response) GetWorldFlags() map[string]map[string]interface{}`

GetWorldFlags returns the WorldFlags field if non-nil, zero value otherwise.

### GetWorldFlagsOk

`func (o *V1StoryStoryIdSessionGet200Response) GetWorldFlagsOk() (*map[string]map[string]interface{}, bool)`

GetWorldFlagsOk returns a tuple with the WorldFlags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorldFlags

`func (o *V1StoryStoryIdSessionGet200Response) SetWorldFlags(v map[string]map[string]interface{})`

SetWorldFlags sets WorldFlags field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


