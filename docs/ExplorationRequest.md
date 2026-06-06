# ExplorationRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**NodeId** | **string** |  | 
**Question** | **string** |  | 
**IdempotencyKey** | **string** |  | 
**LockToken** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewExplorationRequest

`func NewExplorationRequest(nodeId string, question string, idempotencyKey string, ) *ExplorationRequest`

NewExplorationRequest instantiates a new ExplorationRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewExplorationRequestWithDefaults

`func NewExplorationRequestWithDefaults() *ExplorationRequest`

NewExplorationRequestWithDefaults instantiates a new ExplorationRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNodeId

`func (o *ExplorationRequest) GetNodeId() string`

GetNodeId returns the NodeId field if non-nil, zero value otherwise.

### GetNodeIdOk

`func (o *ExplorationRequest) GetNodeIdOk() (*string, bool)`

GetNodeIdOk returns a tuple with the NodeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNodeId

`func (o *ExplorationRequest) SetNodeId(v string)`

SetNodeId sets NodeId field to given value.


### GetQuestion

`func (o *ExplorationRequest) GetQuestion() string`

GetQuestion returns the Question field if non-nil, zero value otherwise.

### GetQuestionOk

`func (o *ExplorationRequest) GetQuestionOk() (*string, bool)`

GetQuestionOk returns a tuple with the Question field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuestion

`func (o *ExplorationRequest) SetQuestion(v string)`

SetQuestion sets Question field to given value.


### GetIdempotencyKey

`func (o *ExplorationRequest) GetIdempotencyKey() string`

GetIdempotencyKey returns the IdempotencyKey field if non-nil, zero value otherwise.

### GetIdempotencyKeyOk

`func (o *ExplorationRequest) GetIdempotencyKeyOk() (*string, bool)`

GetIdempotencyKeyOk returns a tuple with the IdempotencyKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdempotencyKey

`func (o *ExplorationRequest) SetIdempotencyKey(v string)`

SetIdempotencyKey sets IdempotencyKey field to given value.


### GetLockToken

`func (o *ExplorationRequest) GetLockToken() string`

GetLockToken returns the LockToken field if non-nil, zero value otherwise.

### GetLockTokenOk

`func (o *ExplorationRequest) GetLockTokenOk() (*string, bool)`

GetLockTokenOk returns a tuple with the LockToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLockToken

`func (o *ExplorationRequest) SetLockToken(v string)`

SetLockToken sets LockToken field to given value.

### HasLockToken

`func (o *ExplorationRequest) HasLockToken() bool`

HasLockToken returns a boolean if a field has been set.

### SetLockTokenNil

`func (o *ExplorationRequest) SetLockTokenNil(b bool)`

 SetLockTokenNil sets the value for LockToken to be an explicit nil

### UnsetLockToken
`func (o *ExplorationRequest) UnsetLockToken()`

UnsetLockToken ensures that no value is present for LockToken, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


