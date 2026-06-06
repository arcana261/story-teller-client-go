# FreeTextRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**NodeId** | **string** |  | 
**FreeText** | **string** |  | 
**IdempotencyKey** | **string** |  | 
**LockToken** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewFreeTextRequest

`func NewFreeTextRequest(nodeId string, freeText string, idempotencyKey string, ) *FreeTextRequest`

NewFreeTextRequest instantiates a new FreeTextRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeTextRequestWithDefaults

`func NewFreeTextRequestWithDefaults() *FreeTextRequest`

NewFreeTextRequestWithDefaults instantiates a new FreeTextRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNodeId

`func (o *FreeTextRequest) GetNodeId() string`

GetNodeId returns the NodeId field if non-nil, zero value otherwise.

### GetNodeIdOk

`func (o *FreeTextRequest) GetNodeIdOk() (*string, bool)`

GetNodeIdOk returns a tuple with the NodeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNodeId

`func (o *FreeTextRequest) SetNodeId(v string)`

SetNodeId sets NodeId field to given value.


### GetFreeText

`func (o *FreeTextRequest) GetFreeText() string`

GetFreeText returns the FreeText field if non-nil, zero value otherwise.

### GetFreeTextOk

`func (o *FreeTextRequest) GetFreeTextOk() (*string, bool)`

GetFreeTextOk returns a tuple with the FreeText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFreeText

`func (o *FreeTextRequest) SetFreeText(v string)`

SetFreeText sets FreeText field to given value.


### GetIdempotencyKey

`func (o *FreeTextRequest) GetIdempotencyKey() string`

GetIdempotencyKey returns the IdempotencyKey field if non-nil, zero value otherwise.

### GetIdempotencyKeyOk

`func (o *FreeTextRequest) GetIdempotencyKeyOk() (*string, bool)`

GetIdempotencyKeyOk returns a tuple with the IdempotencyKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdempotencyKey

`func (o *FreeTextRequest) SetIdempotencyKey(v string)`

SetIdempotencyKey sets IdempotencyKey field to given value.


### GetLockToken

`func (o *FreeTextRequest) GetLockToken() string`

GetLockToken returns the LockToken field if non-nil, zero value otherwise.

### GetLockTokenOk

`func (o *FreeTextRequest) GetLockTokenOk() (*string, bool)`

GetLockTokenOk returns a tuple with the LockToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLockToken

`func (o *FreeTextRequest) SetLockToken(v string)`

SetLockToken sets LockToken field to given value.

### HasLockToken

`func (o *FreeTextRequest) HasLockToken() bool`

HasLockToken returns a boolean if a field has been set.

### SetLockTokenNil

`func (o *FreeTextRequest) SetLockTokenNil(b bool)`

 SetLockTokenNil sets the value for LockToken to be an explicit nil

### UnsetLockToken
`func (o *FreeTextRequest) UnsetLockToken()`

UnsetLockToken ensures that no value is present for LockToken, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


