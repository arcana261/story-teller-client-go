# V1StoryStoryIdChoicePost200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CharacterDelta** | **[]string** |  | 
**Choices** | [**[]V1StoryStoryIdChoicePost200ResponseChoicesInner**](V1StoryStoryIdChoicePost200ResponseChoicesInner.md) |  | 
**EndReason** | Pointer to **string** |  | [optional] 
**FlagDelta** | **map[string]map[string]interface{}** |  | 
**FlagSchemaDelta** | **map[string]map[string]interface{}** |  | 
**HistorySummary** | Pointer to **string** |  | [optional] 
**LocationDelta** | [**map[string]V1AdminStoryStoryIdGet200ResponseLocationsValue**](V1AdminStoryStoryIdGet200ResponseLocationsValue.md) |  | 
**Metadata** | [**V1StoryStoryIdChoicePost200ResponseMetadata**](V1StoryStoryIdChoicePost200ResponseMetadata.md) |  | 
**NodeId** | **string** |  | 
**NodeType** | **string** |  | 
**ObjectDelta** | [**map[string]V1AdminStoryStoryIdGet200ResponseObjectsValue**](V1AdminStoryStoryIdGet200ResponseObjectsValue.md) |  | 
**ResolvedAnchor** | Pointer to **string** |  | [optional] 
**Text** | **string** |  | 

## Methods

### NewV1StoryStoryIdChoicePost200Response

`func NewV1StoryStoryIdChoicePost200Response(characterDelta []string, choices []V1StoryStoryIdChoicePost200ResponseChoicesInner, flagDelta map[string]map[string]interface{}, flagSchemaDelta map[string]map[string]interface{}, locationDelta map[string]V1AdminStoryStoryIdGet200ResponseLocationsValue, metadata V1StoryStoryIdChoicePost200ResponseMetadata, nodeId string, nodeType string, objectDelta map[string]V1AdminStoryStoryIdGet200ResponseObjectsValue, text string, ) *V1StoryStoryIdChoicePost200Response`

NewV1StoryStoryIdChoicePost200Response instantiates a new V1StoryStoryIdChoicePost200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1StoryStoryIdChoicePost200ResponseWithDefaults

`func NewV1StoryStoryIdChoicePost200ResponseWithDefaults() *V1StoryStoryIdChoicePost200Response`

NewV1StoryStoryIdChoicePost200ResponseWithDefaults instantiates a new V1StoryStoryIdChoicePost200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCharacterDelta

`func (o *V1StoryStoryIdChoicePost200Response) GetCharacterDelta() []string`

GetCharacterDelta returns the CharacterDelta field if non-nil, zero value otherwise.

### GetCharacterDeltaOk

`func (o *V1StoryStoryIdChoicePost200Response) GetCharacterDeltaOk() (*[]string, bool)`

GetCharacterDeltaOk returns a tuple with the CharacterDelta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCharacterDelta

`func (o *V1StoryStoryIdChoicePost200Response) SetCharacterDelta(v []string)`

SetCharacterDelta sets CharacterDelta field to given value.


### GetChoices

`func (o *V1StoryStoryIdChoicePost200Response) GetChoices() []V1StoryStoryIdChoicePost200ResponseChoicesInner`

GetChoices returns the Choices field if non-nil, zero value otherwise.

### GetChoicesOk

`func (o *V1StoryStoryIdChoicePost200Response) GetChoicesOk() (*[]V1StoryStoryIdChoicePost200ResponseChoicesInner, bool)`

GetChoicesOk returns a tuple with the Choices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChoices

`func (o *V1StoryStoryIdChoicePost200Response) SetChoices(v []V1StoryStoryIdChoicePost200ResponseChoicesInner)`

SetChoices sets Choices field to given value.


### GetEndReason

`func (o *V1StoryStoryIdChoicePost200Response) GetEndReason() string`

GetEndReason returns the EndReason field if non-nil, zero value otherwise.

### GetEndReasonOk

`func (o *V1StoryStoryIdChoicePost200Response) GetEndReasonOk() (*string, bool)`

GetEndReasonOk returns a tuple with the EndReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndReason

`func (o *V1StoryStoryIdChoicePost200Response) SetEndReason(v string)`

SetEndReason sets EndReason field to given value.

### HasEndReason

`func (o *V1StoryStoryIdChoicePost200Response) HasEndReason() bool`

HasEndReason returns a boolean if a field has been set.

### GetFlagDelta

`func (o *V1StoryStoryIdChoicePost200Response) GetFlagDelta() map[string]map[string]interface{}`

GetFlagDelta returns the FlagDelta field if non-nil, zero value otherwise.

### GetFlagDeltaOk

`func (o *V1StoryStoryIdChoicePost200Response) GetFlagDeltaOk() (*map[string]map[string]interface{}, bool)`

GetFlagDeltaOk returns a tuple with the FlagDelta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFlagDelta

`func (o *V1StoryStoryIdChoicePost200Response) SetFlagDelta(v map[string]map[string]interface{})`

SetFlagDelta sets FlagDelta field to given value.


### GetFlagSchemaDelta

`func (o *V1StoryStoryIdChoicePost200Response) GetFlagSchemaDelta() map[string]map[string]interface{}`

GetFlagSchemaDelta returns the FlagSchemaDelta field if non-nil, zero value otherwise.

### GetFlagSchemaDeltaOk

`func (o *V1StoryStoryIdChoicePost200Response) GetFlagSchemaDeltaOk() (*map[string]map[string]interface{}, bool)`

GetFlagSchemaDeltaOk returns a tuple with the FlagSchemaDelta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFlagSchemaDelta

`func (o *V1StoryStoryIdChoicePost200Response) SetFlagSchemaDelta(v map[string]map[string]interface{})`

SetFlagSchemaDelta sets FlagSchemaDelta field to given value.


### GetHistorySummary

`func (o *V1StoryStoryIdChoicePost200Response) GetHistorySummary() string`

GetHistorySummary returns the HistorySummary field if non-nil, zero value otherwise.

### GetHistorySummaryOk

`func (o *V1StoryStoryIdChoicePost200Response) GetHistorySummaryOk() (*string, bool)`

GetHistorySummaryOk returns a tuple with the HistorySummary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHistorySummary

`func (o *V1StoryStoryIdChoicePost200Response) SetHistorySummary(v string)`

SetHistorySummary sets HistorySummary field to given value.

### HasHistorySummary

`func (o *V1StoryStoryIdChoicePost200Response) HasHistorySummary() bool`

HasHistorySummary returns a boolean if a field has been set.

### GetLocationDelta

`func (o *V1StoryStoryIdChoicePost200Response) GetLocationDelta() map[string]V1AdminStoryStoryIdGet200ResponseLocationsValue`

GetLocationDelta returns the LocationDelta field if non-nil, zero value otherwise.

### GetLocationDeltaOk

`func (o *V1StoryStoryIdChoicePost200Response) GetLocationDeltaOk() (*map[string]V1AdminStoryStoryIdGet200ResponseLocationsValue, bool)`

GetLocationDeltaOk returns a tuple with the LocationDelta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocationDelta

`func (o *V1StoryStoryIdChoicePost200Response) SetLocationDelta(v map[string]V1AdminStoryStoryIdGet200ResponseLocationsValue)`

SetLocationDelta sets LocationDelta field to given value.


### GetMetadata

`func (o *V1StoryStoryIdChoicePost200Response) GetMetadata() V1StoryStoryIdChoicePost200ResponseMetadata`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *V1StoryStoryIdChoicePost200Response) GetMetadataOk() (*V1StoryStoryIdChoicePost200ResponseMetadata, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *V1StoryStoryIdChoicePost200Response) SetMetadata(v V1StoryStoryIdChoicePost200ResponseMetadata)`

SetMetadata sets Metadata field to given value.


### GetNodeId

`func (o *V1StoryStoryIdChoicePost200Response) GetNodeId() string`

GetNodeId returns the NodeId field if non-nil, zero value otherwise.

### GetNodeIdOk

`func (o *V1StoryStoryIdChoicePost200Response) GetNodeIdOk() (*string, bool)`

GetNodeIdOk returns a tuple with the NodeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNodeId

`func (o *V1StoryStoryIdChoicePost200Response) SetNodeId(v string)`

SetNodeId sets NodeId field to given value.


### GetNodeType

`func (o *V1StoryStoryIdChoicePost200Response) GetNodeType() string`

GetNodeType returns the NodeType field if non-nil, zero value otherwise.

### GetNodeTypeOk

`func (o *V1StoryStoryIdChoicePost200Response) GetNodeTypeOk() (*string, bool)`

GetNodeTypeOk returns a tuple with the NodeType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNodeType

`func (o *V1StoryStoryIdChoicePost200Response) SetNodeType(v string)`

SetNodeType sets NodeType field to given value.


### GetObjectDelta

`func (o *V1StoryStoryIdChoicePost200Response) GetObjectDelta() map[string]V1AdminStoryStoryIdGet200ResponseObjectsValue`

GetObjectDelta returns the ObjectDelta field if non-nil, zero value otherwise.

### GetObjectDeltaOk

`func (o *V1StoryStoryIdChoicePost200Response) GetObjectDeltaOk() (*map[string]V1AdminStoryStoryIdGet200ResponseObjectsValue, bool)`

GetObjectDeltaOk returns a tuple with the ObjectDelta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObjectDelta

`func (o *V1StoryStoryIdChoicePost200Response) SetObjectDelta(v map[string]V1AdminStoryStoryIdGet200ResponseObjectsValue)`

SetObjectDelta sets ObjectDelta field to given value.


### GetResolvedAnchor

`func (o *V1StoryStoryIdChoicePost200Response) GetResolvedAnchor() string`

GetResolvedAnchor returns the ResolvedAnchor field if non-nil, zero value otherwise.

### GetResolvedAnchorOk

`func (o *V1StoryStoryIdChoicePost200Response) GetResolvedAnchorOk() (*string, bool)`

GetResolvedAnchorOk returns a tuple with the ResolvedAnchor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResolvedAnchor

`func (o *V1StoryStoryIdChoicePost200Response) SetResolvedAnchor(v string)`

SetResolvedAnchor sets ResolvedAnchor field to given value.

### HasResolvedAnchor

`func (o *V1StoryStoryIdChoicePost200Response) HasResolvedAnchor() bool`

HasResolvedAnchor returns a boolean if a field has been set.

### GetText

`func (o *V1StoryStoryIdChoicePost200Response) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *V1StoryStoryIdChoicePost200Response) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *V1StoryStoryIdChoicePost200Response) SetText(v string)`

SetText sets Text field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


