# ExplorationStateResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**NodeId** | **string** |  | 
**CurrentNodeId** | **string** |  | 
**PlaythroughId** | **string** |  | 
**EnrichmentDetails** | Pointer to **map[string]interface{}** |  | [optional] [default to {}]
**QuestionCount** | Pointer to **int32** |  | [optional] [default to 0]
**RecentTurns** | Pointer to [**[]ExplorationRecentTurnResponse**](ExplorationRecentTurnResponse.md) |  | [optional] [default to {}]

## Methods

### NewExplorationStateResponse

`func NewExplorationStateResponse(nodeId string, currentNodeId string, playthroughId string, ) *ExplorationStateResponse`

NewExplorationStateResponse instantiates a new ExplorationStateResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewExplorationStateResponseWithDefaults

`func NewExplorationStateResponseWithDefaults() *ExplorationStateResponse`

NewExplorationStateResponseWithDefaults instantiates a new ExplorationStateResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNodeId

`func (o *ExplorationStateResponse) GetNodeId() string`

GetNodeId returns the NodeId field if non-nil, zero value otherwise.

### GetNodeIdOk

`func (o *ExplorationStateResponse) GetNodeIdOk() (*string, bool)`

GetNodeIdOk returns a tuple with the NodeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNodeId

`func (o *ExplorationStateResponse) SetNodeId(v string)`

SetNodeId sets NodeId field to given value.


### GetCurrentNodeId

`func (o *ExplorationStateResponse) GetCurrentNodeId() string`

GetCurrentNodeId returns the CurrentNodeId field if non-nil, zero value otherwise.

### GetCurrentNodeIdOk

`func (o *ExplorationStateResponse) GetCurrentNodeIdOk() (*string, bool)`

GetCurrentNodeIdOk returns a tuple with the CurrentNodeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentNodeId

`func (o *ExplorationStateResponse) SetCurrentNodeId(v string)`

SetCurrentNodeId sets CurrentNodeId field to given value.


### GetPlaythroughId

`func (o *ExplorationStateResponse) GetPlaythroughId() string`

GetPlaythroughId returns the PlaythroughId field if non-nil, zero value otherwise.

### GetPlaythroughIdOk

`func (o *ExplorationStateResponse) GetPlaythroughIdOk() (*string, bool)`

GetPlaythroughIdOk returns a tuple with the PlaythroughId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlaythroughId

`func (o *ExplorationStateResponse) SetPlaythroughId(v string)`

SetPlaythroughId sets PlaythroughId field to given value.


### GetEnrichmentDetails

`func (o *ExplorationStateResponse) GetEnrichmentDetails() map[string]interface{}`

GetEnrichmentDetails returns the EnrichmentDetails field if non-nil, zero value otherwise.

### GetEnrichmentDetailsOk

`func (o *ExplorationStateResponse) GetEnrichmentDetailsOk() (*map[string]interface{}, bool)`

GetEnrichmentDetailsOk returns a tuple with the EnrichmentDetails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnrichmentDetails

`func (o *ExplorationStateResponse) SetEnrichmentDetails(v map[string]interface{})`

SetEnrichmentDetails sets EnrichmentDetails field to given value.

### HasEnrichmentDetails

`func (o *ExplorationStateResponse) HasEnrichmentDetails() bool`

HasEnrichmentDetails returns a boolean if a field has been set.

### GetQuestionCount

`func (o *ExplorationStateResponse) GetQuestionCount() int32`

GetQuestionCount returns the QuestionCount field if non-nil, zero value otherwise.

### GetQuestionCountOk

`func (o *ExplorationStateResponse) GetQuestionCountOk() (*int32, bool)`

GetQuestionCountOk returns a tuple with the QuestionCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuestionCount

`func (o *ExplorationStateResponse) SetQuestionCount(v int32)`

SetQuestionCount sets QuestionCount field to given value.

### HasQuestionCount

`func (o *ExplorationStateResponse) HasQuestionCount() bool`

HasQuestionCount returns a boolean if a field has been set.

### GetRecentTurns

`func (o *ExplorationStateResponse) GetRecentTurns() []ExplorationRecentTurnResponse`

GetRecentTurns returns the RecentTurns field if non-nil, zero value otherwise.

### GetRecentTurnsOk

`func (o *ExplorationStateResponse) GetRecentTurnsOk() (*[]ExplorationRecentTurnResponse, bool)`

GetRecentTurnsOk returns a tuple with the RecentTurns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecentTurns

`func (o *ExplorationStateResponse) SetRecentTurns(v []ExplorationRecentTurnResponse)`

SetRecentTurns sets RecentTurns field to given value.

### HasRecentTurns

`func (o *ExplorationStateResponse) HasRecentTurns() bool`

HasRecentTurns returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


