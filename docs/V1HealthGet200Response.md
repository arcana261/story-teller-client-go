# V1HealthGet200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Postgres** | **string** |  | 
**Redis** | **string** |  | 
**Status** | **string** |  | 
**Version** | **string** |  | 

## Methods

### NewV1HealthGet200Response

`func NewV1HealthGet200Response(postgres string, redis string, status string, version string, ) *V1HealthGet200Response`

NewV1HealthGet200Response instantiates a new V1HealthGet200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1HealthGet200ResponseWithDefaults

`func NewV1HealthGet200ResponseWithDefaults() *V1HealthGet200Response`

NewV1HealthGet200ResponseWithDefaults instantiates a new V1HealthGet200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPostgres

`func (o *V1HealthGet200Response) GetPostgres() string`

GetPostgres returns the Postgres field if non-nil, zero value otherwise.

### GetPostgresOk

`func (o *V1HealthGet200Response) GetPostgresOk() (*string, bool)`

GetPostgresOk returns a tuple with the Postgres field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostgres

`func (o *V1HealthGet200Response) SetPostgres(v string)`

SetPostgres sets Postgres field to given value.


### GetRedis

`func (o *V1HealthGet200Response) GetRedis() string`

GetRedis returns the Redis field if non-nil, zero value otherwise.

### GetRedisOk

`func (o *V1HealthGet200Response) GetRedisOk() (*string, bool)`

GetRedisOk returns a tuple with the Redis field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRedis

`func (o *V1HealthGet200Response) SetRedis(v string)`

SetRedis sets Redis field to given value.


### GetStatus

`func (o *V1HealthGet200Response) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *V1HealthGet200Response) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *V1HealthGet200Response) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetVersion

`func (o *V1HealthGet200Response) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *V1HealthGet200Response) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *V1HealthGet200Response) SetVersion(v string)`

SetVersion sets Version field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


