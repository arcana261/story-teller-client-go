# HealthResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Status** | **string** |  | 
**Postgres** | **string** |  | 
**Redis** | **string** |  | 
**Version** | **string** |  | 

## Methods

### NewHealthResponse

`func NewHealthResponse(status string, postgres string, redis string, version string, ) *HealthResponse`

NewHealthResponse instantiates a new HealthResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewHealthResponseWithDefaults

`func NewHealthResponseWithDefaults() *HealthResponse`

NewHealthResponseWithDefaults instantiates a new HealthResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatus

`func (o *HealthResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *HealthResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *HealthResponse) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetPostgres

`func (o *HealthResponse) GetPostgres() string`

GetPostgres returns the Postgres field if non-nil, zero value otherwise.

### GetPostgresOk

`func (o *HealthResponse) GetPostgresOk() (*string, bool)`

GetPostgresOk returns a tuple with the Postgres field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostgres

`func (o *HealthResponse) SetPostgres(v string)`

SetPostgres sets Postgres field to given value.


### GetRedis

`func (o *HealthResponse) GetRedis() string`

GetRedis returns the Redis field if non-nil, zero value otherwise.

### GetRedisOk

`func (o *HealthResponse) GetRedisOk() (*string, bool)`

GetRedisOk returns a tuple with the Redis field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRedis

`func (o *HealthResponse) SetRedis(v string)`

SetRedis sets Redis field to given value.


### GetVersion

`func (o *HealthResponse) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *HealthResponse) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *HealthResponse) SetVersion(v string)`

SetVersion sets Version field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


