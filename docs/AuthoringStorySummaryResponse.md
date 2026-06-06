# AuthoringStorySummaryResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**StoryId** | **string** |  | 
**Title** | **string** |  | 
**StartNodeId** | **string** |  | 
**MaxNodes** | **int32** |  | 
**Unbounded** | Pointer to **bool** |  | [optional] [default to false]
**Genre** | Pointer to **NullableString** |  | [optional] 
**FlagSchema** | Pointer to **map[string]interface{}** |  | [optional] [default to {}]
**Characters** | Pointer to [**map[string]CharacterSpecResponse**](CharacterSpecResponse.md) |  | [optional] [default to {}]
**Locations** | Pointer to [**map[string]LocationSpecResponse**](LocationSpecResponse.md) |  | [optional] [default to {}]
**Objects** | Pointer to [**map[string]ObjectSpecResponse**](ObjectSpecResponse.md) |  | [optional] [default to {}]
**GenerationContract** | Pointer to **map[string]interface{}** |  | [optional] 

## Methods

### NewAuthoringStorySummaryResponse

`func NewAuthoringStorySummaryResponse(storyId string, title string, startNodeId string, maxNodes int32, ) *AuthoringStorySummaryResponse`

NewAuthoringStorySummaryResponse instantiates a new AuthoringStorySummaryResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAuthoringStorySummaryResponseWithDefaults

`func NewAuthoringStorySummaryResponseWithDefaults() *AuthoringStorySummaryResponse`

NewAuthoringStorySummaryResponseWithDefaults instantiates a new AuthoringStorySummaryResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStoryId

`func (o *AuthoringStorySummaryResponse) GetStoryId() string`

GetStoryId returns the StoryId field if non-nil, zero value otherwise.

### GetStoryIdOk

`func (o *AuthoringStorySummaryResponse) GetStoryIdOk() (*string, bool)`

GetStoryIdOk returns a tuple with the StoryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStoryId

`func (o *AuthoringStorySummaryResponse) SetStoryId(v string)`

SetStoryId sets StoryId field to given value.


### GetTitle

`func (o *AuthoringStorySummaryResponse) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *AuthoringStorySummaryResponse) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *AuthoringStorySummaryResponse) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetStartNodeId

`func (o *AuthoringStorySummaryResponse) GetStartNodeId() string`

GetStartNodeId returns the StartNodeId field if non-nil, zero value otherwise.

### GetStartNodeIdOk

`func (o *AuthoringStorySummaryResponse) GetStartNodeIdOk() (*string, bool)`

GetStartNodeIdOk returns a tuple with the StartNodeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartNodeId

`func (o *AuthoringStorySummaryResponse) SetStartNodeId(v string)`

SetStartNodeId sets StartNodeId field to given value.


### GetMaxNodes

`func (o *AuthoringStorySummaryResponse) GetMaxNodes() int32`

GetMaxNodes returns the MaxNodes field if non-nil, zero value otherwise.

### GetMaxNodesOk

`func (o *AuthoringStorySummaryResponse) GetMaxNodesOk() (*int32, bool)`

GetMaxNodesOk returns a tuple with the MaxNodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxNodes

`func (o *AuthoringStorySummaryResponse) SetMaxNodes(v int32)`

SetMaxNodes sets MaxNodes field to given value.


### GetUnbounded

`func (o *AuthoringStorySummaryResponse) GetUnbounded() bool`

GetUnbounded returns the Unbounded field if non-nil, zero value otherwise.

### GetUnboundedOk

`func (o *AuthoringStorySummaryResponse) GetUnboundedOk() (*bool, bool)`

GetUnboundedOk returns a tuple with the Unbounded field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnbounded

`func (o *AuthoringStorySummaryResponse) SetUnbounded(v bool)`

SetUnbounded sets Unbounded field to given value.

### HasUnbounded

`func (o *AuthoringStorySummaryResponse) HasUnbounded() bool`

HasUnbounded returns a boolean if a field has been set.

### GetGenre

`func (o *AuthoringStorySummaryResponse) GetGenre() string`

GetGenre returns the Genre field if non-nil, zero value otherwise.

### GetGenreOk

`func (o *AuthoringStorySummaryResponse) GetGenreOk() (*string, bool)`

GetGenreOk returns a tuple with the Genre field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGenre

`func (o *AuthoringStorySummaryResponse) SetGenre(v string)`

SetGenre sets Genre field to given value.

### HasGenre

`func (o *AuthoringStorySummaryResponse) HasGenre() bool`

HasGenre returns a boolean if a field has been set.

### SetGenreNil

`func (o *AuthoringStorySummaryResponse) SetGenreNil(b bool)`

 SetGenreNil sets the value for Genre to be an explicit nil

### UnsetGenre
`func (o *AuthoringStorySummaryResponse) UnsetGenre()`

UnsetGenre ensures that no value is present for Genre, not even an explicit nil
### GetFlagSchema

`func (o *AuthoringStorySummaryResponse) GetFlagSchema() map[string]interface{}`

GetFlagSchema returns the FlagSchema field if non-nil, zero value otherwise.

### GetFlagSchemaOk

`func (o *AuthoringStorySummaryResponse) GetFlagSchemaOk() (*map[string]interface{}, bool)`

GetFlagSchemaOk returns a tuple with the FlagSchema field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFlagSchema

`func (o *AuthoringStorySummaryResponse) SetFlagSchema(v map[string]interface{})`

SetFlagSchema sets FlagSchema field to given value.

### HasFlagSchema

`func (o *AuthoringStorySummaryResponse) HasFlagSchema() bool`

HasFlagSchema returns a boolean if a field has been set.

### GetCharacters

`func (o *AuthoringStorySummaryResponse) GetCharacters() map[string]CharacterSpecResponse`

GetCharacters returns the Characters field if non-nil, zero value otherwise.

### GetCharactersOk

`func (o *AuthoringStorySummaryResponse) GetCharactersOk() (*map[string]CharacterSpecResponse, bool)`

GetCharactersOk returns a tuple with the Characters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCharacters

`func (o *AuthoringStorySummaryResponse) SetCharacters(v map[string]CharacterSpecResponse)`

SetCharacters sets Characters field to given value.

### HasCharacters

`func (o *AuthoringStorySummaryResponse) HasCharacters() bool`

HasCharacters returns a boolean if a field has been set.

### GetLocations

`func (o *AuthoringStorySummaryResponse) GetLocations() map[string]LocationSpecResponse`

GetLocations returns the Locations field if non-nil, zero value otherwise.

### GetLocationsOk

`func (o *AuthoringStorySummaryResponse) GetLocationsOk() (*map[string]LocationSpecResponse, bool)`

GetLocationsOk returns a tuple with the Locations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocations

`func (o *AuthoringStorySummaryResponse) SetLocations(v map[string]LocationSpecResponse)`

SetLocations sets Locations field to given value.

### HasLocations

`func (o *AuthoringStorySummaryResponse) HasLocations() bool`

HasLocations returns a boolean if a field has been set.

### GetObjects

`func (o *AuthoringStorySummaryResponse) GetObjects() map[string]ObjectSpecResponse`

GetObjects returns the Objects field if non-nil, zero value otherwise.

### GetObjectsOk

`func (o *AuthoringStorySummaryResponse) GetObjectsOk() (*map[string]ObjectSpecResponse, bool)`

GetObjectsOk returns a tuple with the Objects field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObjects

`func (o *AuthoringStorySummaryResponse) SetObjects(v map[string]ObjectSpecResponse)`

SetObjects sets Objects field to given value.

### HasObjects

`func (o *AuthoringStorySummaryResponse) HasObjects() bool`

HasObjects returns a boolean if a field has been set.

### GetGenerationContract

`func (o *AuthoringStorySummaryResponse) GetGenerationContract() map[string]interface{}`

GetGenerationContract returns the GenerationContract field if non-nil, zero value otherwise.

### GetGenerationContractOk

`func (o *AuthoringStorySummaryResponse) GetGenerationContractOk() (*map[string]interface{}, bool)`

GetGenerationContractOk returns a tuple with the GenerationContract field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGenerationContract

`func (o *AuthoringStorySummaryResponse) SetGenerationContract(v map[string]interface{})`

SetGenerationContract sets GenerationContract field to given value.

### HasGenerationContract

`func (o *AuthoringStorySummaryResponse) HasGenerationContract() bool`

HasGenerationContract returns a boolean if a field has been set.

### SetGenerationContractNil

`func (o *AuthoringStorySummaryResponse) SetGenerationContractNil(b bool)`

 SetGenerationContractNil sets the value for GenerationContract to be an explicit nil

### UnsetGenerationContract
`func (o *AuthoringStorySummaryResponse) UnsetGenerationContract()`

UnsetGenerationContract ensures that no value is present for GenerationContract, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


