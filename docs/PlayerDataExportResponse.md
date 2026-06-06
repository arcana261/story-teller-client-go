# PlayerDataExportResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TenantId** | **string** |  | 
**PlayerId** | **string** |  | 
**GeneratedAt** | **string** |  | 
**Sessions** | Pointer to **[]map[string]interface{}** |  | [optional] [default to {}]
**Exploration** | [**PlayerExplorationDataExport**](PlayerExplorationDataExport.md) |  | 
**EntityProvenance** | Pointer to [**[]EntityProvenanceExportEntryResponse**](EntityProvenanceExportEntryResponse.md) |  | [optional] [default to {}]

## Methods

### NewPlayerDataExportResponse

`func NewPlayerDataExportResponse(tenantId string, playerId string, generatedAt string, exploration PlayerExplorationDataExport, ) *PlayerDataExportResponse`

NewPlayerDataExportResponse instantiates a new PlayerDataExportResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPlayerDataExportResponseWithDefaults

`func NewPlayerDataExportResponseWithDefaults() *PlayerDataExportResponse`

NewPlayerDataExportResponseWithDefaults instantiates a new PlayerDataExportResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTenantId

`func (o *PlayerDataExportResponse) GetTenantId() string`

GetTenantId returns the TenantId field if non-nil, zero value otherwise.

### GetTenantIdOk

`func (o *PlayerDataExportResponse) GetTenantIdOk() (*string, bool)`

GetTenantIdOk returns a tuple with the TenantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantId

`func (o *PlayerDataExportResponse) SetTenantId(v string)`

SetTenantId sets TenantId field to given value.


### GetPlayerId

`func (o *PlayerDataExportResponse) GetPlayerId() string`

GetPlayerId returns the PlayerId field if non-nil, zero value otherwise.

### GetPlayerIdOk

`func (o *PlayerDataExportResponse) GetPlayerIdOk() (*string, bool)`

GetPlayerIdOk returns a tuple with the PlayerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlayerId

`func (o *PlayerDataExportResponse) SetPlayerId(v string)`

SetPlayerId sets PlayerId field to given value.


### GetGeneratedAt

`func (o *PlayerDataExportResponse) GetGeneratedAt() string`

GetGeneratedAt returns the GeneratedAt field if non-nil, zero value otherwise.

### GetGeneratedAtOk

`func (o *PlayerDataExportResponse) GetGeneratedAtOk() (*string, bool)`

GetGeneratedAtOk returns a tuple with the GeneratedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeneratedAt

`func (o *PlayerDataExportResponse) SetGeneratedAt(v string)`

SetGeneratedAt sets GeneratedAt field to given value.


### GetSessions

`func (o *PlayerDataExportResponse) GetSessions() []*map[string]interface{}`

GetSessions returns the Sessions field if non-nil, zero value otherwise.

### GetSessionsOk

`func (o *PlayerDataExportResponse) GetSessionsOk() (*[]*map[string]interface{}, bool)`

GetSessionsOk returns a tuple with the Sessions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSessions

`func (o *PlayerDataExportResponse) SetSessions(v []*map[string]interface{})`

SetSessions sets Sessions field to given value.

### HasSessions

`func (o *PlayerDataExportResponse) HasSessions() bool`

HasSessions returns a boolean if a field has been set.

### GetExploration

`func (o *PlayerDataExportResponse) GetExploration() PlayerExplorationDataExport`

GetExploration returns the Exploration field if non-nil, zero value otherwise.

### GetExplorationOk

`func (o *PlayerDataExportResponse) GetExplorationOk() (*PlayerExplorationDataExport, bool)`

GetExplorationOk returns a tuple with the Exploration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExploration

`func (o *PlayerDataExportResponse) SetExploration(v PlayerExplorationDataExport)`

SetExploration sets Exploration field to given value.


### GetEntityProvenance

`func (o *PlayerDataExportResponse) GetEntityProvenance() []EntityProvenanceExportEntryResponse`

GetEntityProvenance returns the EntityProvenance field if non-nil, zero value otherwise.

### GetEntityProvenanceOk

`func (o *PlayerDataExportResponse) GetEntityProvenanceOk() (*[]EntityProvenanceExportEntryResponse, bool)`

GetEntityProvenanceOk returns a tuple with the EntityProvenance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntityProvenance

`func (o *PlayerDataExportResponse) SetEntityProvenance(v []EntityProvenanceExportEntryResponse)`

SetEntityProvenance sets EntityProvenance field to given value.

### HasEntityProvenance

`func (o *PlayerDataExportResponse) HasEntityProvenance() bool`

HasEntityProvenance returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


