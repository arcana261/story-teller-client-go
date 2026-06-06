# PlayerErasureResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TenantId** | **string** |  | 
**PlayerId** | **string** |  | 
**Deleted** | **map[string]int32** |  | 

## Methods

### NewPlayerErasureResponse

`func NewPlayerErasureResponse(tenantId string, playerId string, deleted map[string]int32, ) *PlayerErasureResponse`

NewPlayerErasureResponse instantiates a new PlayerErasureResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPlayerErasureResponseWithDefaults

`func NewPlayerErasureResponseWithDefaults() *PlayerErasureResponse`

NewPlayerErasureResponseWithDefaults instantiates a new PlayerErasureResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTenantId

`func (o *PlayerErasureResponse) GetTenantId() string`

GetTenantId returns the TenantId field if non-nil, zero value otherwise.

### GetTenantIdOk

`func (o *PlayerErasureResponse) GetTenantIdOk() (*string, bool)`

GetTenantIdOk returns a tuple with the TenantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantId

`func (o *PlayerErasureResponse) SetTenantId(v string)`

SetTenantId sets TenantId field to given value.


### GetPlayerId

`func (o *PlayerErasureResponse) GetPlayerId() string`

GetPlayerId returns the PlayerId field if non-nil, zero value otherwise.

### GetPlayerIdOk

`func (o *PlayerErasureResponse) GetPlayerIdOk() (*string, bool)`

GetPlayerIdOk returns a tuple with the PlayerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlayerId

`func (o *PlayerErasureResponse) SetPlayerId(v string)`

SetPlayerId sets PlayerId field to given value.


### GetDeleted

`func (o *PlayerErasureResponse) GetDeleted() map[string]int32`

GetDeleted returns the Deleted field if non-nil, zero value otherwise.

### GetDeletedOk

`func (o *PlayerErasureResponse) GetDeletedOk() (*map[string]int32, bool)`

GetDeletedOk returns a tuple with the Deleted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeleted

`func (o *PlayerErasureResponse) SetDeleted(v map[string]int32)`

SetDeleted sets Deleted field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


