# V1AdminStoryStoryIdGet200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AllowFreeTextContinuation** | **bool** |  | 
**Characters** | [**map[string]V1AdminStoryStoryIdGet200ResponseCharactersValue**](V1AdminStoryStoryIdGet200ResponseCharactersValue.md) |  | 
**ContentWarnings** | Pointer to **[]string** |  | [optional] 
**FlagSchema** | **map[string]map[string]interface{}** |  | 
**GenerationContract** | Pointer to **map[string]map[string]interface{}** |  | [optional] 
**Genre** | Pointer to **string** |  | [optional] 
**InitialWorldFlags** | **map[string]map[string]interface{}** |  | 
**Locations** | [**map[string]V1AdminStoryStoryIdGet200ResponseLocationsValue**](V1AdminStoryStoryIdGet200ResponseLocationsValue.md) |  | 
**MaxNodes** | **int32** |  | 
**Objects** | [**map[string]V1AdminStoryStoryIdGet200ResponseObjectsValue**](V1AdminStoryStoryIdGet200ResponseObjectsValue.md) |  | 
**StartNodeId** | **string** |  | 
**StoryId** | **string** |  | 
**Title** | **string** |  | 
**Unbounded** | **bool** |  | 

## Methods

### NewV1AdminStoryStoryIdGet200Response

`func NewV1AdminStoryStoryIdGet200Response(allowFreeTextContinuation bool, characters map[string]V1AdminStoryStoryIdGet200ResponseCharactersValue, flagSchema map[string]map[string]interface{}, initialWorldFlags map[string]map[string]interface{}, locations map[string]V1AdminStoryStoryIdGet200ResponseLocationsValue, maxNodes int32, objects map[string]V1AdminStoryStoryIdGet200ResponseObjectsValue, startNodeId string, storyId string, title string, unbounded bool, ) *V1AdminStoryStoryIdGet200Response`

NewV1AdminStoryStoryIdGet200Response instantiates a new V1AdminStoryStoryIdGet200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1AdminStoryStoryIdGet200ResponseWithDefaults

`func NewV1AdminStoryStoryIdGet200ResponseWithDefaults() *V1AdminStoryStoryIdGet200Response`

NewV1AdminStoryStoryIdGet200ResponseWithDefaults instantiates a new V1AdminStoryStoryIdGet200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAllowFreeTextContinuation

`func (o *V1AdminStoryStoryIdGet200Response) GetAllowFreeTextContinuation() bool`

GetAllowFreeTextContinuation returns the AllowFreeTextContinuation field if non-nil, zero value otherwise.

### GetAllowFreeTextContinuationOk

`func (o *V1AdminStoryStoryIdGet200Response) GetAllowFreeTextContinuationOk() (*bool, bool)`

GetAllowFreeTextContinuationOk returns a tuple with the AllowFreeTextContinuation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowFreeTextContinuation

`func (o *V1AdminStoryStoryIdGet200Response) SetAllowFreeTextContinuation(v bool)`

SetAllowFreeTextContinuation sets AllowFreeTextContinuation field to given value.


### GetCharacters

`func (o *V1AdminStoryStoryIdGet200Response) GetCharacters() map[string]V1AdminStoryStoryIdGet200ResponseCharactersValue`

GetCharacters returns the Characters field if non-nil, zero value otherwise.

### GetCharactersOk

`func (o *V1AdminStoryStoryIdGet200Response) GetCharactersOk() (*map[string]V1AdminStoryStoryIdGet200ResponseCharactersValue, bool)`

GetCharactersOk returns a tuple with the Characters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCharacters

`func (o *V1AdminStoryStoryIdGet200Response) SetCharacters(v map[string]V1AdminStoryStoryIdGet200ResponseCharactersValue)`

SetCharacters sets Characters field to given value.


### GetContentWarnings

`func (o *V1AdminStoryStoryIdGet200Response) GetContentWarnings() []string`

GetContentWarnings returns the ContentWarnings field if non-nil, zero value otherwise.

### GetContentWarningsOk

`func (o *V1AdminStoryStoryIdGet200Response) GetContentWarningsOk() (*[]string, bool)`

GetContentWarningsOk returns a tuple with the ContentWarnings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContentWarnings

`func (o *V1AdminStoryStoryIdGet200Response) SetContentWarnings(v []string)`

SetContentWarnings sets ContentWarnings field to given value.

### HasContentWarnings

`func (o *V1AdminStoryStoryIdGet200Response) HasContentWarnings() bool`

HasContentWarnings returns a boolean if a field has been set.

### GetFlagSchema

`func (o *V1AdminStoryStoryIdGet200Response) GetFlagSchema() map[string]map[string]interface{}`

GetFlagSchema returns the FlagSchema field if non-nil, zero value otherwise.

### GetFlagSchemaOk

`func (o *V1AdminStoryStoryIdGet200Response) GetFlagSchemaOk() (*map[string]map[string]interface{}, bool)`

GetFlagSchemaOk returns a tuple with the FlagSchema field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFlagSchema

`func (o *V1AdminStoryStoryIdGet200Response) SetFlagSchema(v map[string]map[string]interface{})`

SetFlagSchema sets FlagSchema field to given value.


### GetGenerationContract

`func (o *V1AdminStoryStoryIdGet200Response) GetGenerationContract() map[string]map[string]interface{}`

GetGenerationContract returns the GenerationContract field if non-nil, zero value otherwise.

### GetGenerationContractOk

`func (o *V1AdminStoryStoryIdGet200Response) GetGenerationContractOk() (*map[string]map[string]interface{}, bool)`

GetGenerationContractOk returns a tuple with the GenerationContract field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGenerationContract

`func (o *V1AdminStoryStoryIdGet200Response) SetGenerationContract(v map[string]map[string]interface{})`

SetGenerationContract sets GenerationContract field to given value.

### HasGenerationContract

`func (o *V1AdminStoryStoryIdGet200Response) HasGenerationContract() bool`

HasGenerationContract returns a boolean if a field has been set.

### GetGenre

`func (o *V1AdminStoryStoryIdGet200Response) GetGenre() string`

GetGenre returns the Genre field if non-nil, zero value otherwise.

### GetGenreOk

`func (o *V1AdminStoryStoryIdGet200Response) GetGenreOk() (*string, bool)`

GetGenreOk returns a tuple with the Genre field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGenre

`func (o *V1AdminStoryStoryIdGet200Response) SetGenre(v string)`

SetGenre sets Genre field to given value.

### HasGenre

`func (o *V1AdminStoryStoryIdGet200Response) HasGenre() bool`

HasGenre returns a boolean if a field has been set.

### GetInitialWorldFlags

`func (o *V1AdminStoryStoryIdGet200Response) GetInitialWorldFlags() map[string]map[string]interface{}`

GetInitialWorldFlags returns the InitialWorldFlags field if non-nil, zero value otherwise.

### GetInitialWorldFlagsOk

`func (o *V1AdminStoryStoryIdGet200Response) GetInitialWorldFlagsOk() (*map[string]map[string]interface{}, bool)`

GetInitialWorldFlagsOk returns a tuple with the InitialWorldFlags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInitialWorldFlags

`func (o *V1AdminStoryStoryIdGet200Response) SetInitialWorldFlags(v map[string]map[string]interface{})`

SetInitialWorldFlags sets InitialWorldFlags field to given value.


### GetLocations

`func (o *V1AdminStoryStoryIdGet200Response) GetLocations() map[string]V1AdminStoryStoryIdGet200ResponseLocationsValue`

GetLocations returns the Locations field if non-nil, zero value otherwise.

### GetLocationsOk

`func (o *V1AdminStoryStoryIdGet200Response) GetLocationsOk() (*map[string]V1AdminStoryStoryIdGet200ResponseLocationsValue, bool)`

GetLocationsOk returns a tuple with the Locations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocations

`func (o *V1AdminStoryStoryIdGet200Response) SetLocations(v map[string]V1AdminStoryStoryIdGet200ResponseLocationsValue)`

SetLocations sets Locations field to given value.


### GetMaxNodes

`func (o *V1AdminStoryStoryIdGet200Response) GetMaxNodes() int32`

GetMaxNodes returns the MaxNodes field if non-nil, zero value otherwise.

### GetMaxNodesOk

`func (o *V1AdminStoryStoryIdGet200Response) GetMaxNodesOk() (*int32, bool)`

GetMaxNodesOk returns a tuple with the MaxNodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxNodes

`func (o *V1AdminStoryStoryIdGet200Response) SetMaxNodes(v int32)`

SetMaxNodes sets MaxNodes field to given value.


### GetObjects

`func (o *V1AdminStoryStoryIdGet200Response) GetObjects() map[string]V1AdminStoryStoryIdGet200ResponseObjectsValue`

GetObjects returns the Objects field if non-nil, zero value otherwise.

### GetObjectsOk

`func (o *V1AdminStoryStoryIdGet200Response) GetObjectsOk() (*map[string]V1AdminStoryStoryIdGet200ResponseObjectsValue, bool)`

GetObjectsOk returns a tuple with the Objects field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObjects

`func (o *V1AdminStoryStoryIdGet200Response) SetObjects(v map[string]V1AdminStoryStoryIdGet200ResponseObjectsValue)`

SetObjects sets Objects field to given value.


### GetStartNodeId

`func (o *V1AdminStoryStoryIdGet200Response) GetStartNodeId() string`

GetStartNodeId returns the StartNodeId field if non-nil, zero value otherwise.

### GetStartNodeIdOk

`func (o *V1AdminStoryStoryIdGet200Response) GetStartNodeIdOk() (*string, bool)`

GetStartNodeIdOk returns a tuple with the StartNodeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartNodeId

`func (o *V1AdminStoryStoryIdGet200Response) SetStartNodeId(v string)`

SetStartNodeId sets StartNodeId field to given value.


### GetStoryId

`func (o *V1AdminStoryStoryIdGet200Response) GetStoryId() string`

GetStoryId returns the StoryId field if non-nil, zero value otherwise.

### GetStoryIdOk

`func (o *V1AdminStoryStoryIdGet200Response) GetStoryIdOk() (*string, bool)`

GetStoryIdOk returns a tuple with the StoryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStoryId

`func (o *V1AdminStoryStoryIdGet200Response) SetStoryId(v string)`

SetStoryId sets StoryId field to given value.


### GetTitle

`func (o *V1AdminStoryStoryIdGet200Response) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *V1AdminStoryStoryIdGet200Response) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *V1AdminStoryStoryIdGet200Response) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetUnbounded

`func (o *V1AdminStoryStoryIdGet200Response) GetUnbounded() bool`

GetUnbounded returns the Unbounded field if non-nil, zero value otherwise.

### GetUnboundedOk

`func (o *V1AdminStoryStoryIdGet200Response) GetUnboundedOk() (*bool, bool)`

GetUnboundedOk returns a tuple with the Unbounded field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnbounded

`func (o *V1AdminStoryStoryIdGet200Response) SetUnbounded(v bool)`

SetUnbounded sets Unbounded field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


