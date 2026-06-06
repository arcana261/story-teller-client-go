# EntityProvenanceEntryResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**EntityType** | **string** |  | 
**EntityId** | **string** |  | 
**IntroducedAtNodeId** | **string** |  | 
**IntroducedAtChoiceId** | **NullableString** |  | 
**LastUpdatedAtNodeId** | **NullableString** |  | 
**LastUpdatedAtChoiceId** | **NullableString** |  | 
**IntroducedAt** | **time.Time** |  | 
**LastUpdatedAt** | **NullableTime** |  | 

## Methods

### NewEntityProvenanceEntryResponse

`func NewEntityProvenanceEntryResponse(entityType string, entityId string, introducedAtNodeId string, introducedAtChoiceId NullableString, lastUpdatedAtNodeId NullableString, lastUpdatedAtChoiceId NullableString, introducedAt time.Time, lastUpdatedAt NullableTime, ) *EntityProvenanceEntryResponse`

NewEntityProvenanceEntryResponse instantiates a new EntityProvenanceEntryResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEntityProvenanceEntryResponseWithDefaults

`func NewEntityProvenanceEntryResponseWithDefaults() *EntityProvenanceEntryResponse`

NewEntityProvenanceEntryResponseWithDefaults instantiates a new EntityProvenanceEntryResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEntityType

`func (o *EntityProvenanceEntryResponse) GetEntityType() string`

GetEntityType returns the EntityType field if non-nil, zero value otherwise.

### GetEntityTypeOk

`func (o *EntityProvenanceEntryResponse) GetEntityTypeOk() (*string, bool)`

GetEntityTypeOk returns a tuple with the EntityType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntityType

`func (o *EntityProvenanceEntryResponse) SetEntityType(v string)`

SetEntityType sets EntityType field to given value.


### GetEntityId

`func (o *EntityProvenanceEntryResponse) GetEntityId() string`

GetEntityId returns the EntityId field if non-nil, zero value otherwise.

### GetEntityIdOk

`func (o *EntityProvenanceEntryResponse) GetEntityIdOk() (*string, bool)`

GetEntityIdOk returns a tuple with the EntityId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntityId

`func (o *EntityProvenanceEntryResponse) SetEntityId(v string)`

SetEntityId sets EntityId field to given value.


### GetIntroducedAtNodeId

`func (o *EntityProvenanceEntryResponse) GetIntroducedAtNodeId() string`

GetIntroducedAtNodeId returns the IntroducedAtNodeId field if non-nil, zero value otherwise.

### GetIntroducedAtNodeIdOk

`func (o *EntityProvenanceEntryResponse) GetIntroducedAtNodeIdOk() (*string, bool)`

GetIntroducedAtNodeIdOk returns a tuple with the IntroducedAtNodeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIntroducedAtNodeId

`func (o *EntityProvenanceEntryResponse) SetIntroducedAtNodeId(v string)`

SetIntroducedAtNodeId sets IntroducedAtNodeId field to given value.


### GetIntroducedAtChoiceId

`func (o *EntityProvenanceEntryResponse) GetIntroducedAtChoiceId() string`

GetIntroducedAtChoiceId returns the IntroducedAtChoiceId field if non-nil, zero value otherwise.

### GetIntroducedAtChoiceIdOk

`func (o *EntityProvenanceEntryResponse) GetIntroducedAtChoiceIdOk() (*string, bool)`

GetIntroducedAtChoiceIdOk returns a tuple with the IntroducedAtChoiceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIntroducedAtChoiceId

`func (o *EntityProvenanceEntryResponse) SetIntroducedAtChoiceId(v string)`

SetIntroducedAtChoiceId sets IntroducedAtChoiceId field to given value.


### SetIntroducedAtChoiceIdNil

`func (o *EntityProvenanceEntryResponse) SetIntroducedAtChoiceIdNil(b bool)`

 SetIntroducedAtChoiceIdNil sets the value for IntroducedAtChoiceId to be an explicit nil

### UnsetIntroducedAtChoiceId
`func (o *EntityProvenanceEntryResponse) UnsetIntroducedAtChoiceId()`

UnsetIntroducedAtChoiceId ensures that no value is present for IntroducedAtChoiceId, not even an explicit nil
### GetLastUpdatedAtNodeId

`func (o *EntityProvenanceEntryResponse) GetLastUpdatedAtNodeId() string`

GetLastUpdatedAtNodeId returns the LastUpdatedAtNodeId field if non-nil, zero value otherwise.

### GetLastUpdatedAtNodeIdOk

`func (o *EntityProvenanceEntryResponse) GetLastUpdatedAtNodeIdOk() (*string, bool)`

GetLastUpdatedAtNodeIdOk returns a tuple with the LastUpdatedAtNodeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastUpdatedAtNodeId

`func (o *EntityProvenanceEntryResponse) SetLastUpdatedAtNodeId(v string)`

SetLastUpdatedAtNodeId sets LastUpdatedAtNodeId field to given value.


### SetLastUpdatedAtNodeIdNil

`func (o *EntityProvenanceEntryResponse) SetLastUpdatedAtNodeIdNil(b bool)`

 SetLastUpdatedAtNodeIdNil sets the value for LastUpdatedAtNodeId to be an explicit nil

### UnsetLastUpdatedAtNodeId
`func (o *EntityProvenanceEntryResponse) UnsetLastUpdatedAtNodeId()`

UnsetLastUpdatedAtNodeId ensures that no value is present for LastUpdatedAtNodeId, not even an explicit nil
### GetLastUpdatedAtChoiceId

`func (o *EntityProvenanceEntryResponse) GetLastUpdatedAtChoiceId() string`

GetLastUpdatedAtChoiceId returns the LastUpdatedAtChoiceId field if non-nil, zero value otherwise.

### GetLastUpdatedAtChoiceIdOk

`func (o *EntityProvenanceEntryResponse) GetLastUpdatedAtChoiceIdOk() (*string, bool)`

GetLastUpdatedAtChoiceIdOk returns a tuple with the LastUpdatedAtChoiceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastUpdatedAtChoiceId

`func (o *EntityProvenanceEntryResponse) SetLastUpdatedAtChoiceId(v string)`

SetLastUpdatedAtChoiceId sets LastUpdatedAtChoiceId field to given value.


### SetLastUpdatedAtChoiceIdNil

`func (o *EntityProvenanceEntryResponse) SetLastUpdatedAtChoiceIdNil(b bool)`

 SetLastUpdatedAtChoiceIdNil sets the value for LastUpdatedAtChoiceId to be an explicit nil

### UnsetLastUpdatedAtChoiceId
`func (o *EntityProvenanceEntryResponse) UnsetLastUpdatedAtChoiceId()`

UnsetLastUpdatedAtChoiceId ensures that no value is present for LastUpdatedAtChoiceId, not even an explicit nil
### GetIntroducedAt

`func (o *EntityProvenanceEntryResponse) GetIntroducedAt() time.Time`

GetIntroducedAt returns the IntroducedAt field if non-nil, zero value otherwise.

### GetIntroducedAtOk

`func (o *EntityProvenanceEntryResponse) GetIntroducedAtOk() (*time.Time, bool)`

GetIntroducedAtOk returns a tuple with the IntroducedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIntroducedAt

`func (o *EntityProvenanceEntryResponse) SetIntroducedAt(v time.Time)`

SetIntroducedAt sets IntroducedAt field to given value.


### GetLastUpdatedAt

`func (o *EntityProvenanceEntryResponse) GetLastUpdatedAt() time.Time`

GetLastUpdatedAt returns the LastUpdatedAt field if non-nil, zero value otherwise.

### GetLastUpdatedAtOk

`func (o *EntityProvenanceEntryResponse) GetLastUpdatedAtOk() (*time.Time, bool)`

GetLastUpdatedAtOk returns a tuple with the LastUpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastUpdatedAt

`func (o *EntityProvenanceEntryResponse) SetLastUpdatedAt(v time.Time)`

SetLastUpdatedAt sets LastUpdatedAt field to given value.


### SetLastUpdatedAtNil

`func (o *EntityProvenanceEntryResponse) SetLastUpdatedAtNil(b bool)`

 SetLastUpdatedAtNil sets the value for LastUpdatedAt to be an explicit nil

### UnsetLastUpdatedAt
`func (o *EntityProvenanceEntryResponse) UnsetLastUpdatedAt()`

UnsetLastUpdatedAt ensures that no value is present for LastUpdatedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


