# NodeResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**NodeId** | **string** |  | 
**Text** | **string** |  | 
**NodeType** | **string** |  | 
**Choices** | [**[]ChoiceResponse**](ChoiceResponse.md) |  | 
**Metadata** | [**NodeMetadata**](NodeMetadata.md) |  | 
**FlagDelta** | Pointer to **map[string]interface{}** |  | [optional] [default to {}]
**FlagSchemaDelta** | Pointer to **map[string]interface{}** |  | [optional] [default to {}]
**EndReason** | Pointer to **NullableString** |  | [optional] 
**ResolvedAnchor** | Pointer to **NullableString** |  | [optional] 
**CharacterDelta** | Pointer to **[]string** |  | [optional] [default to {}]
**LocationDelta** | Pointer to [**map[string]LocationSpecResponse**](LocationSpecResponse.md) |  | [optional] [default to {}]
**ObjectDelta** | Pointer to [**map[string]ObjectSpecResponse**](ObjectSpecResponse.md) |  | [optional] [default to {}]
**HistorySummary** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewNodeResponse

`func NewNodeResponse(nodeId string, text string, nodeType string, choices []ChoiceResponse, metadata NodeMetadata, ) *NodeResponse`

NewNodeResponse instantiates a new NodeResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewNodeResponseWithDefaults

`func NewNodeResponseWithDefaults() *NodeResponse`

NewNodeResponseWithDefaults instantiates a new NodeResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNodeId

`func (o *NodeResponse) GetNodeId() string`

GetNodeId returns the NodeId field if non-nil, zero value otherwise.

### GetNodeIdOk

`func (o *NodeResponse) GetNodeIdOk() (*string, bool)`

GetNodeIdOk returns a tuple with the NodeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNodeId

`func (o *NodeResponse) SetNodeId(v string)`

SetNodeId sets NodeId field to given value.


### GetText

`func (o *NodeResponse) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *NodeResponse) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *NodeResponse) SetText(v string)`

SetText sets Text field to given value.


### GetNodeType

`func (o *NodeResponse) GetNodeType() string`

GetNodeType returns the NodeType field if non-nil, zero value otherwise.

### GetNodeTypeOk

`func (o *NodeResponse) GetNodeTypeOk() (*string, bool)`

GetNodeTypeOk returns a tuple with the NodeType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNodeType

`func (o *NodeResponse) SetNodeType(v string)`

SetNodeType sets NodeType field to given value.


### GetChoices

`func (o *NodeResponse) GetChoices() []ChoiceResponse`

GetChoices returns the Choices field if non-nil, zero value otherwise.

### GetChoicesOk

`func (o *NodeResponse) GetChoicesOk() (*[]ChoiceResponse, bool)`

GetChoicesOk returns a tuple with the Choices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChoices

`func (o *NodeResponse) SetChoices(v []ChoiceResponse)`

SetChoices sets Choices field to given value.


### GetMetadata

`func (o *NodeResponse) GetMetadata() NodeMetadata`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *NodeResponse) GetMetadataOk() (*NodeMetadata, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *NodeResponse) SetMetadata(v NodeMetadata)`

SetMetadata sets Metadata field to given value.


### GetFlagDelta

`func (o *NodeResponse) GetFlagDelta() map[string]interface{}`

GetFlagDelta returns the FlagDelta field if non-nil, zero value otherwise.

### GetFlagDeltaOk

`func (o *NodeResponse) GetFlagDeltaOk() (*map[string]interface{}, bool)`

GetFlagDeltaOk returns a tuple with the FlagDelta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFlagDelta

`func (o *NodeResponse) SetFlagDelta(v map[string]interface{})`

SetFlagDelta sets FlagDelta field to given value.

### HasFlagDelta

`func (o *NodeResponse) HasFlagDelta() bool`

HasFlagDelta returns a boolean if a field has been set.

### GetFlagSchemaDelta

`func (o *NodeResponse) GetFlagSchemaDelta() map[string]interface{}`

GetFlagSchemaDelta returns the FlagSchemaDelta field if non-nil, zero value otherwise.

### GetFlagSchemaDeltaOk

`func (o *NodeResponse) GetFlagSchemaDeltaOk() (*map[string]interface{}, bool)`

GetFlagSchemaDeltaOk returns a tuple with the FlagSchemaDelta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFlagSchemaDelta

`func (o *NodeResponse) SetFlagSchemaDelta(v map[string]interface{})`

SetFlagSchemaDelta sets FlagSchemaDelta field to given value.

### HasFlagSchemaDelta

`func (o *NodeResponse) HasFlagSchemaDelta() bool`

HasFlagSchemaDelta returns a boolean if a field has been set.

### GetEndReason

`func (o *NodeResponse) GetEndReason() string`

GetEndReason returns the EndReason field if non-nil, zero value otherwise.

### GetEndReasonOk

`func (o *NodeResponse) GetEndReasonOk() (*string, bool)`

GetEndReasonOk returns a tuple with the EndReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndReason

`func (o *NodeResponse) SetEndReason(v string)`

SetEndReason sets EndReason field to given value.

### HasEndReason

`func (o *NodeResponse) HasEndReason() bool`

HasEndReason returns a boolean if a field has been set.

### SetEndReasonNil

`func (o *NodeResponse) SetEndReasonNil(b bool)`

 SetEndReasonNil sets the value for EndReason to be an explicit nil

### UnsetEndReason
`func (o *NodeResponse) UnsetEndReason()`

UnsetEndReason ensures that no value is present for EndReason, not even an explicit nil
### GetResolvedAnchor

`func (o *NodeResponse) GetResolvedAnchor() string`

GetResolvedAnchor returns the ResolvedAnchor field if non-nil, zero value otherwise.

### GetResolvedAnchorOk

`func (o *NodeResponse) GetResolvedAnchorOk() (*string, bool)`

GetResolvedAnchorOk returns a tuple with the ResolvedAnchor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResolvedAnchor

`func (o *NodeResponse) SetResolvedAnchor(v string)`

SetResolvedAnchor sets ResolvedAnchor field to given value.

### HasResolvedAnchor

`func (o *NodeResponse) HasResolvedAnchor() bool`

HasResolvedAnchor returns a boolean if a field has been set.

### SetResolvedAnchorNil

`func (o *NodeResponse) SetResolvedAnchorNil(b bool)`

 SetResolvedAnchorNil sets the value for ResolvedAnchor to be an explicit nil

### UnsetResolvedAnchor
`func (o *NodeResponse) UnsetResolvedAnchor()`

UnsetResolvedAnchor ensures that no value is present for ResolvedAnchor, not even an explicit nil
### GetCharacterDelta

`func (o *NodeResponse) GetCharacterDelta() []*string`

GetCharacterDelta returns the CharacterDelta field if non-nil, zero value otherwise.

### GetCharacterDeltaOk

`func (o *NodeResponse) GetCharacterDeltaOk() (*[]*string, bool)`

GetCharacterDeltaOk returns a tuple with the CharacterDelta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCharacterDelta

`func (o *NodeResponse) SetCharacterDelta(v []*string)`

SetCharacterDelta sets CharacterDelta field to given value.

### HasCharacterDelta

`func (o *NodeResponse) HasCharacterDelta() bool`

HasCharacterDelta returns a boolean if a field has been set.

### GetLocationDelta

`func (o *NodeResponse) GetLocationDelta() map[string]LocationSpecResponse`

GetLocationDelta returns the LocationDelta field if non-nil, zero value otherwise.

### GetLocationDeltaOk

`func (o *NodeResponse) GetLocationDeltaOk() (*map[string]LocationSpecResponse, bool)`

GetLocationDeltaOk returns a tuple with the LocationDelta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocationDelta

`func (o *NodeResponse) SetLocationDelta(v map[string]LocationSpecResponse)`

SetLocationDelta sets LocationDelta field to given value.

### HasLocationDelta

`func (o *NodeResponse) HasLocationDelta() bool`

HasLocationDelta returns a boolean if a field has been set.

### GetObjectDelta

`func (o *NodeResponse) GetObjectDelta() map[string]ObjectSpecResponse`

GetObjectDelta returns the ObjectDelta field if non-nil, zero value otherwise.

### GetObjectDeltaOk

`func (o *NodeResponse) GetObjectDeltaOk() (*map[string]ObjectSpecResponse, bool)`

GetObjectDeltaOk returns a tuple with the ObjectDelta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObjectDelta

`func (o *NodeResponse) SetObjectDelta(v map[string]ObjectSpecResponse)`

SetObjectDelta sets ObjectDelta field to given value.

### HasObjectDelta

`func (o *NodeResponse) HasObjectDelta() bool`

HasObjectDelta returns a boolean if a field has been set.

### GetHistorySummary

`func (o *NodeResponse) GetHistorySummary() string`

GetHistorySummary returns the HistorySummary field if non-nil, zero value otherwise.

### GetHistorySummaryOk

`func (o *NodeResponse) GetHistorySummaryOk() (*string, bool)`

GetHistorySummaryOk returns a tuple with the HistorySummary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHistorySummary

`func (o *NodeResponse) SetHistorySummary(v string)`

SetHistorySummary sets HistorySummary field to given value.

### HasHistorySummary

`func (o *NodeResponse) HasHistorySummary() bool`

HasHistorySummary returns a boolean if a field has been set.

### SetHistorySummaryNil

`func (o *NodeResponse) SetHistorySummaryNil(b bool)`

 SetHistorySummaryNil sets the value for HistorySummary to be an explicit nil

### UnsetHistorySummary
`func (o *NodeResponse) UnsetHistorySummary()`

UnsetHistorySummary ensures that no value is present for HistorySummary, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


