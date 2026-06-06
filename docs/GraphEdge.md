# GraphEdge

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FromNodeId** | **string** |  | 
**ChoiceId** | **string** |  | 
**ToNodeId** | **string** |  | 
**Label** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewGraphEdge

`func NewGraphEdge(fromNodeId string, choiceId string, toNodeId string, ) *GraphEdge`

NewGraphEdge instantiates a new GraphEdge object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGraphEdgeWithDefaults

`func NewGraphEdgeWithDefaults() *GraphEdge`

NewGraphEdgeWithDefaults instantiates a new GraphEdge object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFromNodeId

`func (o *GraphEdge) GetFromNodeId() string`

GetFromNodeId returns the FromNodeId field if non-nil, zero value otherwise.

### GetFromNodeIdOk

`func (o *GraphEdge) GetFromNodeIdOk() (*string, bool)`

GetFromNodeIdOk returns a tuple with the FromNodeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFromNodeId

`func (o *GraphEdge) SetFromNodeId(v string)`

SetFromNodeId sets FromNodeId field to given value.


### GetChoiceId

`func (o *GraphEdge) GetChoiceId() string`

GetChoiceId returns the ChoiceId field if non-nil, zero value otherwise.

### GetChoiceIdOk

`func (o *GraphEdge) GetChoiceIdOk() (*string, bool)`

GetChoiceIdOk returns a tuple with the ChoiceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChoiceId

`func (o *GraphEdge) SetChoiceId(v string)`

SetChoiceId sets ChoiceId field to given value.


### GetToNodeId

`func (o *GraphEdge) GetToNodeId() string`

GetToNodeId returns the ToNodeId field if non-nil, zero value otherwise.

### GetToNodeIdOk

`func (o *GraphEdge) GetToNodeIdOk() (*string, bool)`

GetToNodeIdOk returns a tuple with the ToNodeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToNodeId

`func (o *GraphEdge) SetToNodeId(v string)`

SetToNodeId sets ToNodeId field to given value.


### GetLabel

`func (o *GraphEdge) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *GraphEdge) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *GraphEdge) SetLabel(v string)`

SetLabel sets Label field to given value.

### HasLabel

`func (o *GraphEdge) HasLabel() bool`

HasLabel returns a boolean if a field has been set.

### SetLabelNil

`func (o *GraphEdge) SetLabelNil(b bool)`

 SetLabelNil sets the value for Label to be an explicit nil

### UnsetLabel
`func (o *GraphEdge) UnsetLabel()`

UnsetLabel ensures that no value is present for Label, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


