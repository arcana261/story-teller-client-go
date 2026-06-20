# V1AuthoringStoriesPostRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AgeRating** | Pointer to **string** |  | [optional] 
**AllowFreeTextContinuation** | Pointer to **bool** |  | [optional] 
**AllowLlmCharacters** | Pointer to **bool** |  | [optional] 
**AllowLlmLocations** | Pointer to **bool** |  | [optional] 
**AllowLlmObjects** | Pointer to **bool** |  | [optional] 
**Characters** | Pointer to [**map[string]V1AdminStoryStoryIdGet200ResponseCharactersValue**](V1AdminStoryStoryIdGet200ResponseCharactersValue.md) |  | [optional] 
**Complexity** | Pointer to **int32** |  | [optional] 
**FlagSchema** | Pointer to **map[string]map[string]interface{}** |  | [optional] 
**Genre** | Pointer to **string** |  | [optional] 
**HistoryContextWindow** | Pointer to **int32** |  | [optional] 
**HistorySummaryMaxChars** | Pointer to **int32** |  | [optional] 
**InitialWorldFlags** | Pointer to **map[string]map[string]interface{}** |  | [optional] 
**Locations** | Pointer to [**map[string]V1AdminStoryStoryIdGet200ResponseLocationsValue**](V1AdminStoryStoryIdGet200ResponseLocationsValue.md) |  | [optional] 
**Mode** | Pointer to **string** |  | [optional] 
**Objects** | Pointer to [**map[string]V1AdminStoryStoryIdGet200ResponseObjectsValue**](V1AdminStoryStoryIdGet200ResponseObjectsValue.md) |  | [optional] 
**OutcomeAnchors** | Pointer to **[]string** |  | [optional] 
**Prompt** | Pointer to **string** |  | [optional] 
**TargetNodeCount** | Pointer to **int32** |  | [optional] 
**Themes** | Pointer to **[]string** |  | [optional] 
**Title** | Pointer to **string** |  | [optional] 
**Unbounded** | Pointer to **bool** |  | [optional] 
**WorldSystemPrompt** | Pointer to **string** |  | [optional] 

## Methods

### NewV1AuthoringStoriesPostRequest

`func NewV1AuthoringStoriesPostRequest() *V1AuthoringStoriesPostRequest`

NewV1AuthoringStoriesPostRequest instantiates a new V1AuthoringStoriesPostRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1AuthoringStoriesPostRequestWithDefaults

`func NewV1AuthoringStoriesPostRequestWithDefaults() *V1AuthoringStoriesPostRequest`

NewV1AuthoringStoriesPostRequestWithDefaults instantiates a new V1AuthoringStoriesPostRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAgeRating

`func (o *V1AuthoringStoriesPostRequest) GetAgeRating() string`

GetAgeRating returns the AgeRating field if non-nil, zero value otherwise.

### GetAgeRatingOk

`func (o *V1AuthoringStoriesPostRequest) GetAgeRatingOk() (*string, bool)`

GetAgeRatingOk returns a tuple with the AgeRating field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgeRating

`func (o *V1AuthoringStoriesPostRequest) SetAgeRating(v string)`

SetAgeRating sets AgeRating field to given value.

### HasAgeRating

`func (o *V1AuthoringStoriesPostRequest) HasAgeRating() bool`

HasAgeRating returns a boolean if a field has been set.

### GetAllowFreeTextContinuation

`func (o *V1AuthoringStoriesPostRequest) GetAllowFreeTextContinuation() bool`

GetAllowFreeTextContinuation returns the AllowFreeTextContinuation field if non-nil, zero value otherwise.

### GetAllowFreeTextContinuationOk

`func (o *V1AuthoringStoriesPostRequest) GetAllowFreeTextContinuationOk() (*bool, bool)`

GetAllowFreeTextContinuationOk returns a tuple with the AllowFreeTextContinuation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowFreeTextContinuation

`func (o *V1AuthoringStoriesPostRequest) SetAllowFreeTextContinuation(v bool)`

SetAllowFreeTextContinuation sets AllowFreeTextContinuation field to given value.

### HasAllowFreeTextContinuation

`func (o *V1AuthoringStoriesPostRequest) HasAllowFreeTextContinuation() bool`

HasAllowFreeTextContinuation returns a boolean if a field has been set.

### GetAllowLlmCharacters

`func (o *V1AuthoringStoriesPostRequest) GetAllowLlmCharacters() bool`

GetAllowLlmCharacters returns the AllowLlmCharacters field if non-nil, zero value otherwise.

### GetAllowLlmCharactersOk

`func (o *V1AuthoringStoriesPostRequest) GetAllowLlmCharactersOk() (*bool, bool)`

GetAllowLlmCharactersOk returns a tuple with the AllowLlmCharacters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowLlmCharacters

`func (o *V1AuthoringStoriesPostRequest) SetAllowLlmCharacters(v bool)`

SetAllowLlmCharacters sets AllowLlmCharacters field to given value.

### HasAllowLlmCharacters

`func (o *V1AuthoringStoriesPostRequest) HasAllowLlmCharacters() bool`

HasAllowLlmCharacters returns a boolean if a field has been set.

### GetAllowLlmLocations

`func (o *V1AuthoringStoriesPostRequest) GetAllowLlmLocations() bool`

GetAllowLlmLocations returns the AllowLlmLocations field if non-nil, zero value otherwise.

### GetAllowLlmLocationsOk

`func (o *V1AuthoringStoriesPostRequest) GetAllowLlmLocationsOk() (*bool, bool)`

GetAllowLlmLocationsOk returns a tuple with the AllowLlmLocations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowLlmLocations

`func (o *V1AuthoringStoriesPostRequest) SetAllowLlmLocations(v bool)`

SetAllowLlmLocations sets AllowLlmLocations field to given value.

### HasAllowLlmLocations

`func (o *V1AuthoringStoriesPostRequest) HasAllowLlmLocations() bool`

HasAllowLlmLocations returns a boolean if a field has been set.

### GetAllowLlmObjects

`func (o *V1AuthoringStoriesPostRequest) GetAllowLlmObjects() bool`

GetAllowLlmObjects returns the AllowLlmObjects field if non-nil, zero value otherwise.

### GetAllowLlmObjectsOk

`func (o *V1AuthoringStoriesPostRequest) GetAllowLlmObjectsOk() (*bool, bool)`

GetAllowLlmObjectsOk returns a tuple with the AllowLlmObjects field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowLlmObjects

`func (o *V1AuthoringStoriesPostRequest) SetAllowLlmObjects(v bool)`

SetAllowLlmObjects sets AllowLlmObjects field to given value.

### HasAllowLlmObjects

`func (o *V1AuthoringStoriesPostRequest) HasAllowLlmObjects() bool`

HasAllowLlmObjects returns a boolean if a field has been set.

### GetCharacters

`func (o *V1AuthoringStoriesPostRequest) GetCharacters() map[string]V1AdminStoryStoryIdGet200ResponseCharactersValue`

GetCharacters returns the Characters field if non-nil, zero value otherwise.

### GetCharactersOk

`func (o *V1AuthoringStoriesPostRequest) GetCharactersOk() (*map[string]V1AdminStoryStoryIdGet200ResponseCharactersValue, bool)`

GetCharactersOk returns a tuple with the Characters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCharacters

`func (o *V1AuthoringStoriesPostRequest) SetCharacters(v map[string]V1AdminStoryStoryIdGet200ResponseCharactersValue)`

SetCharacters sets Characters field to given value.

### HasCharacters

`func (o *V1AuthoringStoriesPostRequest) HasCharacters() bool`

HasCharacters returns a boolean if a field has been set.

### GetComplexity

`func (o *V1AuthoringStoriesPostRequest) GetComplexity() int32`

GetComplexity returns the Complexity field if non-nil, zero value otherwise.

### GetComplexityOk

`func (o *V1AuthoringStoriesPostRequest) GetComplexityOk() (*int32, bool)`

GetComplexityOk returns a tuple with the Complexity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComplexity

`func (o *V1AuthoringStoriesPostRequest) SetComplexity(v int32)`

SetComplexity sets Complexity field to given value.

### HasComplexity

`func (o *V1AuthoringStoriesPostRequest) HasComplexity() bool`

HasComplexity returns a boolean if a field has been set.

### GetFlagSchema

`func (o *V1AuthoringStoriesPostRequest) GetFlagSchema() map[string]map[string]interface{}`

GetFlagSchema returns the FlagSchema field if non-nil, zero value otherwise.

### GetFlagSchemaOk

`func (o *V1AuthoringStoriesPostRequest) GetFlagSchemaOk() (*map[string]map[string]interface{}, bool)`

GetFlagSchemaOk returns a tuple with the FlagSchema field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFlagSchema

`func (o *V1AuthoringStoriesPostRequest) SetFlagSchema(v map[string]map[string]interface{})`

SetFlagSchema sets FlagSchema field to given value.

### HasFlagSchema

`func (o *V1AuthoringStoriesPostRequest) HasFlagSchema() bool`

HasFlagSchema returns a boolean if a field has been set.

### GetGenre

`func (o *V1AuthoringStoriesPostRequest) GetGenre() string`

GetGenre returns the Genre field if non-nil, zero value otherwise.

### GetGenreOk

`func (o *V1AuthoringStoriesPostRequest) GetGenreOk() (*string, bool)`

GetGenreOk returns a tuple with the Genre field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGenre

`func (o *V1AuthoringStoriesPostRequest) SetGenre(v string)`

SetGenre sets Genre field to given value.

### HasGenre

`func (o *V1AuthoringStoriesPostRequest) HasGenre() bool`

HasGenre returns a boolean if a field has been set.

### GetHistoryContextWindow

`func (o *V1AuthoringStoriesPostRequest) GetHistoryContextWindow() int32`

GetHistoryContextWindow returns the HistoryContextWindow field if non-nil, zero value otherwise.

### GetHistoryContextWindowOk

`func (o *V1AuthoringStoriesPostRequest) GetHistoryContextWindowOk() (*int32, bool)`

GetHistoryContextWindowOk returns a tuple with the HistoryContextWindow field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHistoryContextWindow

`func (o *V1AuthoringStoriesPostRequest) SetHistoryContextWindow(v int32)`

SetHistoryContextWindow sets HistoryContextWindow field to given value.

### HasHistoryContextWindow

`func (o *V1AuthoringStoriesPostRequest) HasHistoryContextWindow() bool`

HasHistoryContextWindow returns a boolean if a field has been set.

### GetHistorySummaryMaxChars

`func (o *V1AuthoringStoriesPostRequest) GetHistorySummaryMaxChars() int32`

GetHistorySummaryMaxChars returns the HistorySummaryMaxChars field if non-nil, zero value otherwise.

### GetHistorySummaryMaxCharsOk

`func (o *V1AuthoringStoriesPostRequest) GetHistorySummaryMaxCharsOk() (*int32, bool)`

GetHistorySummaryMaxCharsOk returns a tuple with the HistorySummaryMaxChars field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHistorySummaryMaxChars

`func (o *V1AuthoringStoriesPostRequest) SetHistorySummaryMaxChars(v int32)`

SetHistorySummaryMaxChars sets HistorySummaryMaxChars field to given value.

### HasHistorySummaryMaxChars

`func (o *V1AuthoringStoriesPostRequest) HasHistorySummaryMaxChars() bool`

HasHistorySummaryMaxChars returns a boolean if a field has been set.

### GetInitialWorldFlags

`func (o *V1AuthoringStoriesPostRequest) GetInitialWorldFlags() map[string]map[string]interface{}`

GetInitialWorldFlags returns the InitialWorldFlags field if non-nil, zero value otherwise.

### GetInitialWorldFlagsOk

`func (o *V1AuthoringStoriesPostRequest) GetInitialWorldFlagsOk() (*map[string]map[string]interface{}, bool)`

GetInitialWorldFlagsOk returns a tuple with the InitialWorldFlags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInitialWorldFlags

`func (o *V1AuthoringStoriesPostRequest) SetInitialWorldFlags(v map[string]map[string]interface{})`

SetInitialWorldFlags sets InitialWorldFlags field to given value.

### HasInitialWorldFlags

`func (o *V1AuthoringStoriesPostRequest) HasInitialWorldFlags() bool`

HasInitialWorldFlags returns a boolean if a field has been set.

### GetLocations

`func (o *V1AuthoringStoriesPostRequest) GetLocations() map[string]V1AdminStoryStoryIdGet200ResponseLocationsValue`

GetLocations returns the Locations field if non-nil, zero value otherwise.

### GetLocationsOk

`func (o *V1AuthoringStoriesPostRequest) GetLocationsOk() (*map[string]V1AdminStoryStoryIdGet200ResponseLocationsValue, bool)`

GetLocationsOk returns a tuple with the Locations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocations

`func (o *V1AuthoringStoriesPostRequest) SetLocations(v map[string]V1AdminStoryStoryIdGet200ResponseLocationsValue)`

SetLocations sets Locations field to given value.

### HasLocations

`func (o *V1AuthoringStoriesPostRequest) HasLocations() bool`

HasLocations returns a boolean if a field has been set.

### GetMode

`func (o *V1AuthoringStoriesPostRequest) GetMode() string`

GetMode returns the Mode field if non-nil, zero value otherwise.

### GetModeOk

`func (o *V1AuthoringStoriesPostRequest) GetModeOk() (*string, bool)`

GetModeOk returns a tuple with the Mode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMode

`func (o *V1AuthoringStoriesPostRequest) SetMode(v string)`

SetMode sets Mode field to given value.

### HasMode

`func (o *V1AuthoringStoriesPostRequest) HasMode() bool`

HasMode returns a boolean if a field has been set.

### GetObjects

`func (o *V1AuthoringStoriesPostRequest) GetObjects() map[string]V1AdminStoryStoryIdGet200ResponseObjectsValue`

GetObjects returns the Objects field if non-nil, zero value otherwise.

### GetObjectsOk

`func (o *V1AuthoringStoriesPostRequest) GetObjectsOk() (*map[string]V1AdminStoryStoryIdGet200ResponseObjectsValue, bool)`

GetObjectsOk returns a tuple with the Objects field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObjects

`func (o *V1AuthoringStoriesPostRequest) SetObjects(v map[string]V1AdminStoryStoryIdGet200ResponseObjectsValue)`

SetObjects sets Objects field to given value.

### HasObjects

`func (o *V1AuthoringStoriesPostRequest) HasObjects() bool`

HasObjects returns a boolean if a field has been set.

### GetOutcomeAnchors

`func (o *V1AuthoringStoriesPostRequest) GetOutcomeAnchors() []string`

GetOutcomeAnchors returns the OutcomeAnchors field if non-nil, zero value otherwise.

### GetOutcomeAnchorsOk

`func (o *V1AuthoringStoriesPostRequest) GetOutcomeAnchorsOk() (*[]string, bool)`

GetOutcomeAnchorsOk returns a tuple with the OutcomeAnchors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutcomeAnchors

`func (o *V1AuthoringStoriesPostRequest) SetOutcomeAnchors(v []string)`

SetOutcomeAnchors sets OutcomeAnchors field to given value.

### HasOutcomeAnchors

`func (o *V1AuthoringStoriesPostRequest) HasOutcomeAnchors() bool`

HasOutcomeAnchors returns a boolean if a field has been set.

### GetPrompt

`func (o *V1AuthoringStoriesPostRequest) GetPrompt() string`

GetPrompt returns the Prompt field if non-nil, zero value otherwise.

### GetPromptOk

`func (o *V1AuthoringStoriesPostRequest) GetPromptOk() (*string, bool)`

GetPromptOk returns a tuple with the Prompt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrompt

`func (o *V1AuthoringStoriesPostRequest) SetPrompt(v string)`

SetPrompt sets Prompt field to given value.

### HasPrompt

`func (o *V1AuthoringStoriesPostRequest) HasPrompt() bool`

HasPrompt returns a boolean if a field has been set.

### GetTargetNodeCount

`func (o *V1AuthoringStoriesPostRequest) GetTargetNodeCount() int32`

GetTargetNodeCount returns the TargetNodeCount field if non-nil, zero value otherwise.

### GetTargetNodeCountOk

`func (o *V1AuthoringStoriesPostRequest) GetTargetNodeCountOk() (*int32, bool)`

GetTargetNodeCountOk returns a tuple with the TargetNodeCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetNodeCount

`func (o *V1AuthoringStoriesPostRequest) SetTargetNodeCount(v int32)`

SetTargetNodeCount sets TargetNodeCount field to given value.

### HasTargetNodeCount

`func (o *V1AuthoringStoriesPostRequest) HasTargetNodeCount() bool`

HasTargetNodeCount returns a boolean if a field has been set.

### GetThemes

`func (o *V1AuthoringStoriesPostRequest) GetThemes() []string`

GetThemes returns the Themes field if non-nil, zero value otherwise.

### GetThemesOk

`func (o *V1AuthoringStoriesPostRequest) GetThemesOk() (*[]string, bool)`

GetThemesOk returns a tuple with the Themes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThemes

`func (o *V1AuthoringStoriesPostRequest) SetThemes(v []string)`

SetThemes sets Themes field to given value.

### HasThemes

`func (o *V1AuthoringStoriesPostRequest) HasThemes() bool`

HasThemes returns a boolean if a field has been set.

### GetTitle

`func (o *V1AuthoringStoriesPostRequest) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *V1AuthoringStoriesPostRequest) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *V1AuthoringStoriesPostRequest) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *V1AuthoringStoriesPostRequest) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### GetUnbounded

`func (o *V1AuthoringStoriesPostRequest) GetUnbounded() bool`

GetUnbounded returns the Unbounded field if non-nil, zero value otherwise.

### GetUnboundedOk

`func (o *V1AuthoringStoriesPostRequest) GetUnboundedOk() (*bool, bool)`

GetUnboundedOk returns a tuple with the Unbounded field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnbounded

`func (o *V1AuthoringStoriesPostRequest) SetUnbounded(v bool)`

SetUnbounded sets Unbounded field to given value.

### HasUnbounded

`func (o *V1AuthoringStoriesPostRequest) HasUnbounded() bool`

HasUnbounded returns a boolean if a field has been set.

### GetWorldSystemPrompt

`func (o *V1AuthoringStoriesPostRequest) GetWorldSystemPrompt() string`

GetWorldSystemPrompt returns the WorldSystemPrompt field if non-nil, zero value otherwise.

### GetWorldSystemPromptOk

`func (o *V1AuthoringStoriesPostRequest) GetWorldSystemPromptOk() (*string, bool)`

GetWorldSystemPromptOk returns a tuple with the WorldSystemPrompt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorldSystemPrompt

`func (o *V1AuthoringStoriesPostRequest) SetWorldSystemPrompt(v string)`

SetWorldSystemPrompt sets WorldSystemPrompt field to given value.

### HasWorldSystemPrompt

`func (o *V1AuthoringStoriesPostRequest) HasWorldSystemPrompt() bool`

HasWorldSystemPrompt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


