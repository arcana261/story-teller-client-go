# GraphTopologyResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**StoryId** | **string** |  | 
**StartNodeId** | **string** |  | 
**Nodes** | **[]map[string]string** |  | 
**Edges** | [**[]GraphEdge**](GraphEdge.md) |  | 
**FlagSchema** | Pointer to **map[string]interface{}** |  | [optional] [default to {}]
**Characters** | Pointer to **map[string]interface{}** |  | [optional] [default to {}]
**Locations** | Pointer to **map[string]interface{}** |  | [optional] [default to {}]
**Objects** | Pointer to **map[string]interface{}** |  | [optional] [default to {}]
**AllowFreeTextContinuation** | Pointer to **bool** |  | [optional] [default to true]
**ExplorationNodes** | Pointer to **[]map[string]interface{}** |  | [optional] [default to {}]

## Methods

### NewGraphTopologyResponse

`func NewGraphTopologyResponse(storyId string, startNodeId string, nodes []map[string]string, edges []GraphEdge, ) *GraphTopologyResponse`

NewGraphTopologyResponse instantiates a new GraphTopologyResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGraphTopologyResponseWithDefaults

`func NewGraphTopologyResponseWithDefaults() *GraphTopologyResponse`

NewGraphTopologyResponseWithDefaults instantiates a new GraphTopologyResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStoryId

`func (o *GraphTopologyResponse) GetStoryId() string`

GetStoryId returns the StoryId field if non-nil, zero value otherwise.

### GetStoryIdOk

`func (o *GraphTopologyResponse) GetStoryIdOk() (*string, bool)`

GetStoryIdOk returns a tuple with the StoryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStoryId

`func (o *GraphTopologyResponse) SetStoryId(v string)`

SetStoryId sets StoryId field to given value.


### GetStartNodeId

`func (o *GraphTopologyResponse) GetStartNodeId() string`

GetStartNodeId returns the StartNodeId field if non-nil, zero value otherwise.

### GetStartNodeIdOk

`func (o *GraphTopologyResponse) GetStartNodeIdOk() (*string, bool)`

GetStartNodeIdOk returns a tuple with the StartNodeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartNodeId

`func (o *GraphTopologyResponse) SetStartNodeId(v string)`

SetStartNodeId sets StartNodeId field to given value.


### GetNodes

`func (o *GraphTopologyResponse) GetNodes() []map[string]string`

GetNodes returns the Nodes field if non-nil, zero value otherwise.

### GetNodesOk

`func (o *GraphTopologyResponse) GetNodesOk() (*[]map[string]string, bool)`

GetNodesOk returns a tuple with the Nodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNodes

`func (o *GraphTopologyResponse) SetNodes(v []map[string]string)`

SetNodes sets Nodes field to given value.


### GetEdges

`func (o *GraphTopologyResponse) GetEdges() []GraphEdge`

GetEdges returns the Edges field if non-nil, zero value otherwise.

### GetEdgesOk

`func (o *GraphTopologyResponse) GetEdgesOk() (*[]GraphEdge, bool)`

GetEdgesOk returns a tuple with the Edges field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEdges

`func (o *GraphTopologyResponse) SetEdges(v []GraphEdge)`

SetEdges sets Edges field to given value.


### GetFlagSchema

`func (o *GraphTopologyResponse) GetFlagSchema() map[string]interface{}`

GetFlagSchema returns the FlagSchema field if non-nil, zero value otherwise.

### GetFlagSchemaOk

`func (o *GraphTopologyResponse) GetFlagSchemaOk() (*map[string]interface{}, bool)`

GetFlagSchemaOk returns a tuple with the FlagSchema field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFlagSchema

`func (o *GraphTopologyResponse) SetFlagSchema(v map[string]interface{})`

SetFlagSchema sets FlagSchema field to given value.

### HasFlagSchema

`func (o *GraphTopologyResponse) HasFlagSchema() bool`

HasFlagSchema returns a boolean if a field has been set.

### GetCharacters

`func (o *GraphTopologyResponse) GetCharacters() map[string]interface{}`

GetCharacters returns the Characters field if non-nil, zero value otherwise.

### GetCharactersOk

`func (o *GraphTopologyResponse) GetCharactersOk() (*map[string]interface{}, bool)`

GetCharactersOk returns a tuple with the Characters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCharacters

`func (o *GraphTopologyResponse) SetCharacters(v map[string]interface{})`

SetCharacters sets Characters field to given value.

### HasCharacters

`func (o *GraphTopologyResponse) HasCharacters() bool`

HasCharacters returns a boolean if a field has been set.

### GetLocations

`func (o *GraphTopologyResponse) GetLocations() map[string]interface{}`

GetLocations returns the Locations field if non-nil, zero value otherwise.

### GetLocationsOk

`func (o *GraphTopologyResponse) GetLocationsOk() (*map[string]interface{}, bool)`

GetLocationsOk returns a tuple with the Locations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocations

`func (o *GraphTopologyResponse) SetLocations(v map[string]interface{})`

SetLocations sets Locations field to given value.

### HasLocations

`func (o *GraphTopologyResponse) HasLocations() bool`

HasLocations returns a boolean if a field has been set.

### GetObjects

`func (o *GraphTopologyResponse) GetObjects() map[string]interface{}`

GetObjects returns the Objects field if non-nil, zero value otherwise.

### GetObjectsOk

`func (o *GraphTopologyResponse) GetObjectsOk() (*map[string]interface{}, bool)`

GetObjectsOk returns a tuple with the Objects field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObjects

`func (o *GraphTopologyResponse) SetObjects(v map[string]interface{})`

SetObjects sets Objects field to given value.

### HasObjects

`func (o *GraphTopologyResponse) HasObjects() bool`

HasObjects returns a boolean if a field has been set.

### GetAllowFreeTextContinuation

`func (o *GraphTopologyResponse) GetAllowFreeTextContinuation() bool`

GetAllowFreeTextContinuation returns the AllowFreeTextContinuation field if non-nil, zero value otherwise.

### GetAllowFreeTextContinuationOk

`func (o *GraphTopologyResponse) GetAllowFreeTextContinuationOk() (*bool, bool)`

GetAllowFreeTextContinuationOk returns a tuple with the AllowFreeTextContinuation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowFreeTextContinuation

`func (o *GraphTopologyResponse) SetAllowFreeTextContinuation(v bool)`

SetAllowFreeTextContinuation sets AllowFreeTextContinuation field to given value.

### HasAllowFreeTextContinuation

`func (o *GraphTopologyResponse) HasAllowFreeTextContinuation() bool`

HasAllowFreeTextContinuation returns a boolean if a field has been set.

### GetExplorationNodes

`func (o *GraphTopologyResponse) GetExplorationNodes() []*map[string]interface{}`

GetExplorationNodes returns the ExplorationNodes field if non-nil, zero value otherwise.

### GetExplorationNodesOk

`func (o *GraphTopologyResponse) GetExplorationNodesOk() (*[]*map[string]interface{}, bool)`

GetExplorationNodesOk returns a tuple with the ExplorationNodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExplorationNodes

`func (o *GraphTopologyResponse) SetExplorationNodes(v []*map[string]interface{})`

SetExplorationNodes sets ExplorationNodes field to given value.

### HasExplorationNodes

`func (o *GraphTopologyResponse) HasExplorationNodes() bool`

HasExplorationNodes returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


