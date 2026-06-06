# EntityIndexResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SessionId** | **string** |  | 
**PlaythroughId** | **string** |  | 
**Entries** | [**[]EntityProvenanceEntryResponse**](EntityProvenanceEntryResponse.md) |  | 

## Methods

### NewEntityIndexResponse

`func NewEntityIndexResponse(sessionId string, playthroughId string, entries []EntityProvenanceEntryResponse, ) *EntityIndexResponse`

NewEntityIndexResponse instantiates a new EntityIndexResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEntityIndexResponseWithDefaults

`func NewEntityIndexResponseWithDefaults() *EntityIndexResponse`

NewEntityIndexResponseWithDefaults instantiates a new EntityIndexResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSessionId

`func (o *EntityIndexResponse) GetSessionId() string`

GetSessionId returns the SessionId field if non-nil, zero value otherwise.

### GetSessionIdOk

`func (o *EntityIndexResponse) GetSessionIdOk() (*string, bool)`

GetSessionIdOk returns a tuple with the SessionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSessionId

`func (o *EntityIndexResponse) SetSessionId(v string)`

SetSessionId sets SessionId field to given value.


### GetPlaythroughId

`func (o *EntityIndexResponse) GetPlaythroughId() string`

GetPlaythroughId returns the PlaythroughId field if non-nil, zero value otherwise.

### GetPlaythroughIdOk

`func (o *EntityIndexResponse) GetPlaythroughIdOk() (*string, bool)`

GetPlaythroughIdOk returns a tuple with the PlaythroughId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlaythroughId

`func (o *EntityIndexResponse) SetPlaythroughId(v string)`

SetPlaythroughId sets PlaythroughId field to given value.


### GetEntries

`func (o *EntityIndexResponse) GetEntries() []EntityProvenanceEntryResponse`

GetEntries returns the Entries field if non-nil, zero value otherwise.

### GetEntriesOk

`func (o *EntityIndexResponse) GetEntriesOk() (*[]EntityProvenanceEntryResponse, bool)`

GetEntriesOk returns a tuple with the Entries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntries

`func (o *EntityIndexResponse) SetEntries(v []EntityProvenanceEntryResponse)`

SetEntries sets Entries field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


