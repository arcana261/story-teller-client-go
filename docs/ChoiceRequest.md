# ChoiceRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ChoiceId** | **string** |  | 
**NodeId** | **string** |  | 
**IdempotencyKey** | **string** |  | 
**LockToken** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewChoiceRequest

`func NewChoiceRequest(choiceId string, nodeId string, idempotencyKey string, ) *ChoiceRequest`

NewChoiceRequest instantiates a new ChoiceRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChoiceRequestWithDefaults

`func NewChoiceRequestWithDefaults() *ChoiceRequest`

NewChoiceRequestWithDefaults instantiates a new ChoiceRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetChoiceId

`func (o *ChoiceRequest) GetChoiceId() string`

GetChoiceId returns the ChoiceId field if non-nil, zero value otherwise.

### GetChoiceIdOk

`func (o *ChoiceRequest) GetChoiceIdOk() (*string, bool)`

GetChoiceIdOk returns a tuple with the ChoiceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChoiceId

`func (o *ChoiceRequest) SetChoiceId(v string)`

SetChoiceId sets ChoiceId field to given value.


### GetNodeId

`func (o *ChoiceRequest) GetNodeId() string`

GetNodeId returns the NodeId field if non-nil, zero value otherwise.

### GetNodeIdOk

`func (o *ChoiceRequest) GetNodeIdOk() (*string, bool)`

GetNodeIdOk returns a tuple with the NodeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNodeId

`func (o *ChoiceRequest) SetNodeId(v string)`

SetNodeId sets NodeId field to given value.


### GetIdempotencyKey

`func (o *ChoiceRequest) GetIdempotencyKey() string`

GetIdempotencyKey returns the IdempotencyKey field if non-nil, zero value otherwise.

### GetIdempotencyKeyOk

`func (o *ChoiceRequest) GetIdempotencyKeyOk() (*string, bool)`

GetIdempotencyKeyOk returns a tuple with the IdempotencyKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdempotencyKey

`func (o *ChoiceRequest) SetIdempotencyKey(v string)`

SetIdempotencyKey sets IdempotencyKey field to given value.


### GetLockToken

`func (o *ChoiceRequest) GetLockToken() string`

GetLockToken returns the LockToken field if non-nil, zero value otherwise.

### GetLockTokenOk

`func (o *ChoiceRequest) GetLockTokenOk() (*string, bool)`

GetLockTokenOk returns a tuple with the LockToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLockToken

`func (o *ChoiceRequest) SetLockToken(v string)`

SetLockToken sets LockToken field to given value.

### HasLockToken

`func (o *ChoiceRequest) HasLockToken() bool`

HasLockToken returns a boolean if a field has been set.

### SetLockTokenNil

`func (o *ChoiceRequest) SetLockTokenNil(b bool)`

 SetLockTokenNil sets the value for LockToken to be an explicit nil

### UnsetLockToken
`func (o *ChoiceRequest) UnsetLockToken()`

UnsetLockToken ensures that no value is present for LockToken, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


