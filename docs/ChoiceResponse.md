# ChoiceResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Label** | **string** |  | 
**TargetNodeId** | **NullableString** |  | 
**FlagDelta** | Pointer to **map[string]interface{}** |  | [optional] [default to {}]
**FlagSchemaDelta** | Pointer to **map[string]interface{}** |  | [optional] [default to {}]

## Methods

### NewChoiceResponse

`func NewChoiceResponse(id string, label string, targetNodeId NullableString, ) *ChoiceResponse`

NewChoiceResponse instantiates a new ChoiceResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChoiceResponseWithDefaults

`func NewChoiceResponseWithDefaults() *ChoiceResponse`

NewChoiceResponseWithDefaults instantiates a new ChoiceResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ChoiceResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ChoiceResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ChoiceResponse) SetId(v string)`

SetId sets Id field to given value.


### GetLabel

`func (o *ChoiceResponse) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *ChoiceResponse) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *ChoiceResponse) SetLabel(v string)`

SetLabel sets Label field to given value.


### GetTargetNodeId

`func (o *ChoiceResponse) GetTargetNodeId() string`

GetTargetNodeId returns the TargetNodeId field if non-nil, zero value otherwise.

### GetTargetNodeIdOk

`func (o *ChoiceResponse) GetTargetNodeIdOk() (*string, bool)`

GetTargetNodeIdOk returns a tuple with the TargetNodeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetNodeId

`func (o *ChoiceResponse) SetTargetNodeId(v string)`

SetTargetNodeId sets TargetNodeId field to given value.


### SetTargetNodeIdNil

`func (o *ChoiceResponse) SetTargetNodeIdNil(b bool)`

 SetTargetNodeIdNil sets the value for TargetNodeId to be an explicit nil

### UnsetTargetNodeId
`func (o *ChoiceResponse) UnsetTargetNodeId()`

UnsetTargetNodeId ensures that no value is present for TargetNodeId, not even an explicit nil
### GetFlagDelta

`func (o *ChoiceResponse) GetFlagDelta() map[string]interface{}`

GetFlagDelta returns the FlagDelta field if non-nil, zero value otherwise.

### GetFlagDeltaOk

`func (o *ChoiceResponse) GetFlagDeltaOk() (*map[string]interface{}, bool)`

GetFlagDeltaOk returns a tuple with the FlagDelta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFlagDelta

`func (o *ChoiceResponse) SetFlagDelta(v map[string]interface{})`

SetFlagDelta sets FlagDelta field to given value.

### HasFlagDelta

`func (o *ChoiceResponse) HasFlagDelta() bool`

HasFlagDelta returns a boolean if a field has been set.

### GetFlagSchemaDelta

`func (o *ChoiceResponse) GetFlagSchemaDelta() map[string]interface{}`

GetFlagSchemaDelta returns the FlagSchemaDelta field if non-nil, zero value otherwise.

### GetFlagSchemaDeltaOk

`func (o *ChoiceResponse) GetFlagSchemaDeltaOk() (*map[string]interface{}, bool)`

GetFlagSchemaDeltaOk returns a tuple with the FlagSchemaDelta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFlagSchemaDelta

`func (o *ChoiceResponse) SetFlagSchemaDelta(v map[string]interface{})`

SetFlagSchemaDelta sets FlagSchemaDelta field to given value.

### HasFlagSchemaDelta

`func (o *ChoiceResponse) HasFlagSchemaDelta() bool`

HasFlagSchemaDelta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


