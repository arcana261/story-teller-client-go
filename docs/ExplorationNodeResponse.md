# ExplorationNodeResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**ParentNodeId** | **string** |  | 
**Question** | **string** |  | 
**Answer** | **string** |  | 
**FormalizedText** | **string** |  | 
**Essential** | **bool** |  | 
**Picked** | **bool** |  | 
**DetailDelta** | Pointer to **map[string]interface{}** |  | [optional] [default to {}]

## Methods

### NewExplorationNodeResponse

`func NewExplorationNodeResponse(id string, parentNodeId string, question string, answer string, formalizedText string, essential bool, picked bool, ) *ExplorationNodeResponse`

NewExplorationNodeResponse instantiates a new ExplorationNodeResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewExplorationNodeResponseWithDefaults

`func NewExplorationNodeResponseWithDefaults() *ExplorationNodeResponse`

NewExplorationNodeResponseWithDefaults instantiates a new ExplorationNodeResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ExplorationNodeResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ExplorationNodeResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ExplorationNodeResponse) SetId(v string)`

SetId sets Id field to given value.


### GetParentNodeId

`func (o *ExplorationNodeResponse) GetParentNodeId() string`

GetParentNodeId returns the ParentNodeId field if non-nil, zero value otherwise.

### GetParentNodeIdOk

`func (o *ExplorationNodeResponse) GetParentNodeIdOk() (*string, bool)`

GetParentNodeIdOk returns a tuple with the ParentNodeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentNodeId

`func (o *ExplorationNodeResponse) SetParentNodeId(v string)`

SetParentNodeId sets ParentNodeId field to given value.


### GetQuestion

`func (o *ExplorationNodeResponse) GetQuestion() string`

GetQuestion returns the Question field if non-nil, zero value otherwise.

### GetQuestionOk

`func (o *ExplorationNodeResponse) GetQuestionOk() (*string, bool)`

GetQuestionOk returns a tuple with the Question field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuestion

`func (o *ExplorationNodeResponse) SetQuestion(v string)`

SetQuestion sets Question field to given value.


### GetAnswer

`func (o *ExplorationNodeResponse) GetAnswer() string`

GetAnswer returns the Answer field if non-nil, zero value otherwise.

### GetAnswerOk

`func (o *ExplorationNodeResponse) GetAnswerOk() (*string, bool)`

GetAnswerOk returns a tuple with the Answer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAnswer

`func (o *ExplorationNodeResponse) SetAnswer(v string)`

SetAnswer sets Answer field to given value.


### GetFormalizedText

`func (o *ExplorationNodeResponse) GetFormalizedText() string`

GetFormalizedText returns the FormalizedText field if non-nil, zero value otherwise.

### GetFormalizedTextOk

`func (o *ExplorationNodeResponse) GetFormalizedTextOk() (*string, bool)`

GetFormalizedTextOk returns a tuple with the FormalizedText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormalizedText

`func (o *ExplorationNodeResponse) SetFormalizedText(v string)`

SetFormalizedText sets FormalizedText field to given value.


### GetEssential

`func (o *ExplorationNodeResponse) GetEssential() bool`

GetEssential returns the Essential field if non-nil, zero value otherwise.

### GetEssentialOk

`func (o *ExplorationNodeResponse) GetEssentialOk() (*bool, bool)`

GetEssentialOk returns a tuple with the Essential field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEssential

`func (o *ExplorationNodeResponse) SetEssential(v bool)`

SetEssential sets Essential field to given value.


### GetPicked

`func (o *ExplorationNodeResponse) GetPicked() bool`

GetPicked returns the Picked field if non-nil, zero value otherwise.

### GetPickedOk

`func (o *ExplorationNodeResponse) GetPickedOk() (*bool, bool)`

GetPickedOk returns a tuple with the Picked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPicked

`func (o *ExplorationNodeResponse) SetPicked(v bool)`

SetPicked sets Picked field to given value.


### GetDetailDelta

`func (o *ExplorationNodeResponse) GetDetailDelta() map[string]interface{}`

GetDetailDelta returns the DetailDelta field if non-nil, zero value otherwise.

### GetDetailDeltaOk

`func (o *ExplorationNodeResponse) GetDetailDeltaOk() (*map[string]interface{}, bool)`

GetDetailDeltaOk returns a tuple with the DetailDelta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetailDelta

`func (o *ExplorationNodeResponse) SetDetailDelta(v map[string]interface{})`

SetDetailDelta sets DetailDelta field to given value.

### HasDetailDelta

`func (o *ExplorationNodeResponse) HasDetailDelta() bool`

HasDetailDelta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


