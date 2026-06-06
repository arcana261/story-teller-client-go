# StoryDetailResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**StoryId** | **string** |  | 
**Title** | **string** |  | 
**StartNodeId** | **string** |  | 
**Genre** | Pointer to **NullableString** |  | [optional] 
**ContentWarnings** | Pointer to **[]string** |  | [optional] 
**MaxNodes** | Pointer to **int32** |  | [optional] [default to 10]
**Unbounded** | Pointer to **bool** |  | [optional] [default to false]
**FlagSchema** | Pointer to **map[string]interface{}** |  | [optional] [default to {}]
**InitialWorldFlags** | Pointer to **map[string]interface{}** |  | [optional] [default to {}]
**Characters** | Pointer to [**map[string]CharacterSpecResponse**](CharacterSpecResponse.md) |  | [optional] [default to {}]
**Locations** | Pointer to [**map[string]LocationSpecResponse**](LocationSpecResponse.md) |  | [optional] [default to {}]
**Objects** | Pointer to [**map[string]ObjectSpecResponse**](ObjectSpecResponse.md) |  | [optional] [default to {}]
**GenerationContract** | Pointer to **map[string]interface{}** |  | [optional] 

## Methods

### NewStoryDetailResponse

`func NewStoryDetailResponse(storyId string, title string, startNodeId string, ) *StoryDetailResponse`

NewStoryDetailResponse instantiates a new StoryDetailResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStoryDetailResponseWithDefaults

`func NewStoryDetailResponseWithDefaults() *StoryDetailResponse`

NewStoryDetailResponseWithDefaults instantiates a new StoryDetailResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStoryId

`func (o *StoryDetailResponse) GetStoryId() string`

GetStoryId returns the StoryId field if non-nil, zero value otherwise.

### GetStoryIdOk

`func (o *StoryDetailResponse) GetStoryIdOk() (*string, bool)`

GetStoryIdOk returns a tuple with the StoryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStoryId

`func (o *StoryDetailResponse) SetStoryId(v string)`

SetStoryId sets StoryId field to given value.


### GetTitle

`func (o *StoryDetailResponse) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *StoryDetailResponse) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *StoryDetailResponse) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetStartNodeId

`func (o *StoryDetailResponse) GetStartNodeId() string`

GetStartNodeId returns the StartNodeId field if non-nil, zero value otherwise.

### GetStartNodeIdOk

`func (o *StoryDetailResponse) GetStartNodeIdOk() (*string, bool)`

GetStartNodeIdOk returns a tuple with the StartNodeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartNodeId

`func (o *StoryDetailResponse) SetStartNodeId(v string)`

SetStartNodeId sets StartNodeId field to given value.


### GetGenre

`func (o *StoryDetailResponse) GetGenre() string`

GetGenre returns the Genre field if non-nil, zero value otherwise.

### GetGenreOk

`func (o *StoryDetailResponse) GetGenreOk() (*string, bool)`

GetGenreOk returns a tuple with the Genre field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGenre

`func (o *StoryDetailResponse) SetGenre(v string)`

SetGenre sets Genre field to given value.

### HasGenre

`func (o *StoryDetailResponse) HasGenre() bool`

HasGenre returns a boolean if a field has been set.

### SetGenreNil

`func (o *StoryDetailResponse) SetGenreNil(b bool)`

 SetGenreNil sets the value for Genre to be an explicit nil

### UnsetGenre
`func (o *StoryDetailResponse) UnsetGenre()`

UnsetGenre ensures that no value is present for Genre, not even an explicit nil
### GetContentWarnings

`func (o *StoryDetailResponse) GetContentWarnings() []string`

GetContentWarnings returns the ContentWarnings field if non-nil, zero value otherwise.

### GetContentWarningsOk

`func (o *StoryDetailResponse) GetContentWarningsOk() (*[]string, bool)`

GetContentWarningsOk returns a tuple with the ContentWarnings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContentWarnings

`func (o *StoryDetailResponse) SetContentWarnings(v []string)`

SetContentWarnings sets ContentWarnings field to given value.

### HasContentWarnings

`func (o *StoryDetailResponse) HasContentWarnings() bool`

HasContentWarnings returns a boolean if a field has been set.

### SetContentWarningsNil

`func (o *StoryDetailResponse) SetContentWarningsNil(b bool)`

 SetContentWarningsNil sets the value for ContentWarnings to be an explicit nil

### UnsetContentWarnings
`func (o *StoryDetailResponse) UnsetContentWarnings()`

UnsetContentWarnings ensures that no value is present for ContentWarnings, not even an explicit nil
### GetMaxNodes

`func (o *StoryDetailResponse) GetMaxNodes() int32`

GetMaxNodes returns the MaxNodes field if non-nil, zero value otherwise.

### GetMaxNodesOk

`func (o *StoryDetailResponse) GetMaxNodesOk() (*int32, bool)`

GetMaxNodesOk returns a tuple with the MaxNodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxNodes

`func (o *StoryDetailResponse) SetMaxNodes(v int32)`

SetMaxNodes sets MaxNodes field to given value.

### HasMaxNodes

`func (o *StoryDetailResponse) HasMaxNodes() bool`

HasMaxNodes returns a boolean if a field has been set.

### GetUnbounded

`func (o *StoryDetailResponse) GetUnbounded() bool`

GetUnbounded returns the Unbounded field if non-nil, zero value otherwise.

### GetUnboundedOk

`func (o *StoryDetailResponse) GetUnboundedOk() (*bool, bool)`

GetUnboundedOk returns a tuple with the Unbounded field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnbounded

`func (o *StoryDetailResponse) SetUnbounded(v bool)`

SetUnbounded sets Unbounded field to given value.

### HasUnbounded

`func (o *StoryDetailResponse) HasUnbounded() bool`

HasUnbounded returns a boolean if a field has been set.

### GetFlagSchema

`func (o *StoryDetailResponse) GetFlagSchema() map[string]interface{}`

GetFlagSchema returns the FlagSchema field if non-nil, zero value otherwise.

### GetFlagSchemaOk

`func (o *StoryDetailResponse) GetFlagSchemaOk() (*map[string]interface{}, bool)`

GetFlagSchemaOk returns a tuple with the FlagSchema field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFlagSchema

`func (o *StoryDetailResponse) SetFlagSchema(v map[string]interface{})`

SetFlagSchema sets FlagSchema field to given value.

### HasFlagSchema

`func (o *StoryDetailResponse) HasFlagSchema() bool`

HasFlagSchema returns a boolean if a field has been set.

### GetInitialWorldFlags

`func (o *StoryDetailResponse) GetInitialWorldFlags() map[string]interface{}`

GetInitialWorldFlags returns the InitialWorldFlags field if non-nil, zero value otherwise.

### GetInitialWorldFlagsOk

`func (o *StoryDetailResponse) GetInitialWorldFlagsOk() (*map[string]interface{}, bool)`

GetInitialWorldFlagsOk returns a tuple with the InitialWorldFlags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInitialWorldFlags

`func (o *StoryDetailResponse) SetInitialWorldFlags(v map[string]interface{})`

SetInitialWorldFlags sets InitialWorldFlags field to given value.

### HasInitialWorldFlags

`func (o *StoryDetailResponse) HasInitialWorldFlags() bool`

HasInitialWorldFlags returns a boolean if a field has been set.

### GetCharacters

`func (o *StoryDetailResponse) GetCharacters() map[string]CharacterSpecResponse`

GetCharacters returns the Characters field if non-nil, zero value otherwise.

### GetCharactersOk

`func (o *StoryDetailResponse) GetCharactersOk() (*map[string]CharacterSpecResponse, bool)`

GetCharactersOk returns a tuple with the Characters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCharacters

`func (o *StoryDetailResponse) SetCharacters(v map[string]CharacterSpecResponse)`

SetCharacters sets Characters field to given value.

### HasCharacters

`func (o *StoryDetailResponse) HasCharacters() bool`

HasCharacters returns a boolean if a field has been set.

### GetLocations

`func (o *StoryDetailResponse) GetLocations() map[string]LocationSpecResponse`

GetLocations returns the Locations field if non-nil, zero value otherwise.

### GetLocationsOk

`func (o *StoryDetailResponse) GetLocationsOk() (*map[string]LocationSpecResponse, bool)`

GetLocationsOk returns a tuple with the Locations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocations

`func (o *StoryDetailResponse) SetLocations(v map[string]LocationSpecResponse)`

SetLocations sets Locations field to given value.

### HasLocations

`func (o *StoryDetailResponse) HasLocations() bool`

HasLocations returns a boolean if a field has been set.

### GetObjects

`func (o *StoryDetailResponse) GetObjects() map[string]ObjectSpecResponse`

GetObjects returns the Objects field if non-nil, zero value otherwise.

### GetObjectsOk

`func (o *StoryDetailResponse) GetObjectsOk() (*map[string]ObjectSpecResponse, bool)`

GetObjectsOk returns a tuple with the Objects field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObjects

`func (o *StoryDetailResponse) SetObjects(v map[string]ObjectSpecResponse)`

SetObjects sets Objects field to given value.

### HasObjects

`func (o *StoryDetailResponse) HasObjects() bool`

HasObjects returns a boolean if a field has been set.

### GetGenerationContract

`func (o *StoryDetailResponse) GetGenerationContract() map[string]interface{}`

GetGenerationContract returns the GenerationContract field if non-nil, zero value otherwise.

### GetGenerationContractOk

`func (o *StoryDetailResponse) GetGenerationContractOk() (*map[string]interface{}, bool)`

GetGenerationContractOk returns a tuple with the GenerationContract field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGenerationContract

`func (o *StoryDetailResponse) SetGenerationContract(v map[string]interface{})`

SetGenerationContract sets GenerationContract field to given value.

### HasGenerationContract

`func (o *StoryDetailResponse) HasGenerationContract() bool`

HasGenerationContract returns a boolean if a field has been set.

### SetGenerationContractNil

`func (o *StoryDetailResponse) SetGenerationContractNil(b bool)`

 SetGenerationContractNil sets the value for GenerationContract to be an explicit nil

### UnsetGenerationContract
`func (o *StoryDetailResponse) UnsetGenerationContract()`

UnsetGenerationContract ensures that no value is present for GenerationContract, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


