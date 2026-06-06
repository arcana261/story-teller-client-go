# SessionResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SessionId** | **string** |  | 
**PlaythroughId** | **string** |  | 
**CurrentNodeId** | **string** |  | 
**WorldFlags** | **map[string]interface{}** |  | 
**DiscoveredLocations** | Pointer to [**map[string]LocationSpecResponse**](LocationSpecResponse.md) |  | [optional] [default to {}]
**DiscoveredObjects** | Pointer to [**map[string]ObjectSpecResponse**](ObjectSpecResponse.md) |  | [optional] [default to {}]
**DiscoveredFlagSchema** | Pointer to **map[string]interface{}** |  | [optional] [default to {}]
**NodesVisited** | **int32** |  | 
**IsCompleted** | **bool** |  | 
**LockToken** | Pointer to **NullableString** |  | [optional] 
**WarningsAcknowledgedAt** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewSessionResponse

`func NewSessionResponse(sessionId string, playthroughId string, currentNodeId string, worldFlags map[string]interface{}, nodesVisited int32, isCompleted bool, ) *SessionResponse`

NewSessionResponse instantiates a new SessionResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSessionResponseWithDefaults

`func NewSessionResponseWithDefaults() *SessionResponse`

NewSessionResponseWithDefaults instantiates a new SessionResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSessionId

`func (o *SessionResponse) GetSessionId() string`

GetSessionId returns the SessionId field if non-nil, zero value otherwise.

### GetSessionIdOk

`func (o *SessionResponse) GetSessionIdOk() (*string, bool)`

GetSessionIdOk returns a tuple with the SessionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSessionId

`func (o *SessionResponse) SetSessionId(v string)`

SetSessionId sets SessionId field to given value.


### GetPlaythroughId

`func (o *SessionResponse) GetPlaythroughId() string`

GetPlaythroughId returns the PlaythroughId field if non-nil, zero value otherwise.

### GetPlaythroughIdOk

`func (o *SessionResponse) GetPlaythroughIdOk() (*string, bool)`

GetPlaythroughIdOk returns a tuple with the PlaythroughId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlaythroughId

`func (o *SessionResponse) SetPlaythroughId(v string)`

SetPlaythroughId sets PlaythroughId field to given value.


### GetCurrentNodeId

`func (o *SessionResponse) GetCurrentNodeId() string`

GetCurrentNodeId returns the CurrentNodeId field if non-nil, zero value otherwise.

### GetCurrentNodeIdOk

`func (o *SessionResponse) GetCurrentNodeIdOk() (*string, bool)`

GetCurrentNodeIdOk returns a tuple with the CurrentNodeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentNodeId

`func (o *SessionResponse) SetCurrentNodeId(v string)`

SetCurrentNodeId sets CurrentNodeId field to given value.


### GetWorldFlags

`func (o *SessionResponse) GetWorldFlags() map[string]interface{}`

GetWorldFlags returns the WorldFlags field if non-nil, zero value otherwise.

### GetWorldFlagsOk

`func (o *SessionResponse) GetWorldFlagsOk() (*map[string]interface{}, bool)`

GetWorldFlagsOk returns a tuple with the WorldFlags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorldFlags

`func (o *SessionResponse) SetWorldFlags(v map[string]interface{})`

SetWorldFlags sets WorldFlags field to given value.


### GetDiscoveredLocations

`func (o *SessionResponse) GetDiscoveredLocations() map[string]LocationSpecResponse`

GetDiscoveredLocations returns the DiscoveredLocations field if non-nil, zero value otherwise.

### GetDiscoveredLocationsOk

`func (o *SessionResponse) GetDiscoveredLocationsOk() (*map[string]LocationSpecResponse, bool)`

GetDiscoveredLocationsOk returns a tuple with the DiscoveredLocations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscoveredLocations

`func (o *SessionResponse) SetDiscoveredLocations(v map[string]LocationSpecResponse)`

SetDiscoveredLocations sets DiscoveredLocations field to given value.

### HasDiscoveredLocations

`func (o *SessionResponse) HasDiscoveredLocations() bool`

HasDiscoveredLocations returns a boolean if a field has been set.

### GetDiscoveredObjects

`func (o *SessionResponse) GetDiscoveredObjects() map[string]ObjectSpecResponse`

GetDiscoveredObjects returns the DiscoveredObjects field if non-nil, zero value otherwise.

### GetDiscoveredObjectsOk

`func (o *SessionResponse) GetDiscoveredObjectsOk() (*map[string]ObjectSpecResponse, bool)`

GetDiscoveredObjectsOk returns a tuple with the DiscoveredObjects field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscoveredObjects

`func (o *SessionResponse) SetDiscoveredObjects(v map[string]ObjectSpecResponse)`

SetDiscoveredObjects sets DiscoveredObjects field to given value.

### HasDiscoveredObjects

`func (o *SessionResponse) HasDiscoveredObjects() bool`

HasDiscoveredObjects returns a boolean if a field has been set.

### GetDiscoveredFlagSchema

`func (o *SessionResponse) GetDiscoveredFlagSchema() map[string]interface{}`

GetDiscoveredFlagSchema returns the DiscoveredFlagSchema field if non-nil, zero value otherwise.

### GetDiscoveredFlagSchemaOk

`func (o *SessionResponse) GetDiscoveredFlagSchemaOk() (*map[string]interface{}, bool)`

GetDiscoveredFlagSchemaOk returns a tuple with the DiscoveredFlagSchema field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscoveredFlagSchema

`func (o *SessionResponse) SetDiscoveredFlagSchema(v map[string]interface{})`

SetDiscoveredFlagSchema sets DiscoveredFlagSchema field to given value.

### HasDiscoveredFlagSchema

`func (o *SessionResponse) HasDiscoveredFlagSchema() bool`

HasDiscoveredFlagSchema returns a boolean if a field has been set.

### GetNodesVisited

`func (o *SessionResponse) GetNodesVisited() int32`

GetNodesVisited returns the NodesVisited field if non-nil, zero value otherwise.

### GetNodesVisitedOk

`func (o *SessionResponse) GetNodesVisitedOk() (*int32, bool)`

GetNodesVisitedOk returns a tuple with the NodesVisited field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNodesVisited

`func (o *SessionResponse) SetNodesVisited(v int32)`

SetNodesVisited sets NodesVisited field to given value.


### GetIsCompleted

`func (o *SessionResponse) GetIsCompleted() bool`

GetIsCompleted returns the IsCompleted field if non-nil, zero value otherwise.

### GetIsCompletedOk

`func (o *SessionResponse) GetIsCompletedOk() (*bool, bool)`

GetIsCompletedOk returns a tuple with the IsCompleted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsCompleted

`func (o *SessionResponse) SetIsCompleted(v bool)`

SetIsCompleted sets IsCompleted field to given value.


### GetLockToken

`func (o *SessionResponse) GetLockToken() string`

GetLockToken returns the LockToken field if non-nil, zero value otherwise.

### GetLockTokenOk

`func (o *SessionResponse) GetLockTokenOk() (*string, bool)`

GetLockTokenOk returns a tuple with the LockToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLockToken

`func (o *SessionResponse) SetLockToken(v string)`

SetLockToken sets LockToken field to given value.

### HasLockToken

`func (o *SessionResponse) HasLockToken() bool`

HasLockToken returns a boolean if a field has been set.

### SetLockTokenNil

`func (o *SessionResponse) SetLockTokenNil(b bool)`

 SetLockTokenNil sets the value for LockToken to be an explicit nil

### UnsetLockToken
`func (o *SessionResponse) UnsetLockToken()`

UnsetLockToken ensures that no value is present for LockToken, not even an explicit nil
### GetWarningsAcknowledgedAt

`func (o *SessionResponse) GetWarningsAcknowledgedAt() string`

GetWarningsAcknowledgedAt returns the WarningsAcknowledgedAt field if non-nil, zero value otherwise.

### GetWarningsAcknowledgedAtOk

`func (o *SessionResponse) GetWarningsAcknowledgedAtOk() (*string, bool)`

GetWarningsAcknowledgedAtOk returns a tuple with the WarningsAcknowledgedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarningsAcknowledgedAt

`func (o *SessionResponse) SetWarningsAcknowledgedAt(v string)`

SetWarningsAcknowledgedAt sets WarningsAcknowledgedAt field to given value.

### HasWarningsAcknowledgedAt

`func (o *SessionResponse) HasWarningsAcknowledgedAt() bool`

HasWarningsAcknowledgedAt returns a boolean if a field has been set.

### SetWarningsAcknowledgedAtNil

`func (o *SessionResponse) SetWarningsAcknowledgedAtNil(b bool)`

 SetWarningsAcknowledgedAtNil sets the value for WarningsAcknowledgedAt to be an explicit nil

### UnsetWarningsAcknowledgedAt
`func (o *SessionResponse) UnsetWarningsAcknowledgedAt()`

UnsetWarningsAcknowledgedAt ensures that no value is present for WarningsAcknowledgedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


