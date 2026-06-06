# StoryGenerateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Prompt** | **string** |  | 
**Mode** | Pointer to **string** |  | [optional] [default to "sync"]
**Genre** | Pointer to **NullableString** |  | [optional] 
**Themes** | Pointer to **[]string** |  | [optional] 
**TargetNodeCount** | Pointer to **NullableInt32** |  | [optional] 
**AgeRating** | Pointer to **NullableString** |  | [optional] 
**Complexity** | Pointer to **NullableInt32** |  | [optional] 
**InitialWorldFlags** | Pointer to **map[string]interface{}** |  | [optional] 
**FlagSchema** | Pointer to **map[string]interface{}** |  | [optional] 
**Characters** | Pointer to **map[string]interface{}** |  | [optional] 
**Locations** | Pointer to **map[string]interface{}** |  | [optional] 
**Objects** | Pointer to **map[string]interface{}** |  | [optional] 
**AllowFreeTextContinuation** | Pointer to **bool** |  | [optional] [default to true]
**Unbounded** | Pointer to **bool** |  | [optional] [default to false]
**AllowLlmCharacters** | Pointer to **bool** |  | [optional] [default to true]
**AllowLlmLocations** | Pointer to **bool** |  | [optional] [default to true]
**AllowLlmObjects** | Pointer to **bool** |  | [optional] [default to true]
**OutcomeAnchors** | Pointer to **[]string** |  | [optional] 
**HistorySummaryMaxChars** | Pointer to **NullableInt32** |  | [optional] 
**HistoryContextWindow** | Pointer to **NullableInt32** |  | [optional] 
**WorldSystemPrompt** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewStoryGenerateRequest

`func NewStoryGenerateRequest(prompt string, ) *StoryGenerateRequest`

NewStoryGenerateRequest instantiates a new StoryGenerateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStoryGenerateRequestWithDefaults

`func NewStoryGenerateRequestWithDefaults() *StoryGenerateRequest`

NewStoryGenerateRequestWithDefaults instantiates a new StoryGenerateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPrompt

`func (o *StoryGenerateRequest) GetPrompt() string`

GetPrompt returns the Prompt field if non-nil, zero value otherwise.

### GetPromptOk

`func (o *StoryGenerateRequest) GetPromptOk() (*string, bool)`

GetPromptOk returns a tuple with the Prompt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrompt

`func (o *StoryGenerateRequest) SetPrompt(v string)`

SetPrompt sets Prompt field to given value.


### GetMode

`func (o *StoryGenerateRequest) GetMode() string`

GetMode returns the Mode field if non-nil, zero value otherwise.

### GetModeOk

`func (o *StoryGenerateRequest) GetModeOk() (*string, bool)`

GetModeOk returns a tuple with the Mode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMode

`func (o *StoryGenerateRequest) SetMode(v string)`

SetMode sets Mode field to given value.

### HasMode

`func (o *StoryGenerateRequest) HasMode() bool`

HasMode returns a boolean if a field has been set.

### GetGenre

`func (o *StoryGenerateRequest) GetGenre() string`

GetGenre returns the Genre field if non-nil, zero value otherwise.

### GetGenreOk

`func (o *StoryGenerateRequest) GetGenreOk() (*string, bool)`

GetGenreOk returns a tuple with the Genre field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGenre

`func (o *StoryGenerateRequest) SetGenre(v string)`

SetGenre sets Genre field to given value.

### HasGenre

`func (o *StoryGenerateRequest) HasGenre() bool`

HasGenre returns a boolean if a field has been set.

### SetGenreNil

`func (o *StoryGenerateRequest) SetGenreNil(b bool)`

 SetGenreNil sets the value for Genre to be an explicit nil

### UnsetGenre
`func (o *StoryGenerateRequest) UnsetGenre()`

UnsetGenre ensures that no value is present for Genre, not even an explicit nil
### GetThemes

`func (o *StoryGenerateRequest) GetThemes() []string`

GetThemes returns the Themes field if non-nil, zero value otherwise.

### GetThemesOk

`func (o *StoryGenerateRequest) GetThemesOk() (*[]string, bool)`

GetThemesOk returns a tuple with the Themes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThemes

`func (o *StoryGenerateRequest) SetThemes(v []string)`

SetThemes sets Themes field to given value.

### HasThemes

`func (o *StoryGenerateRequest) HasThemes() bool`

HasThemes returns a boolean if a field has been set.

### SetThemesNil

`func (o *StoryGenerateRequest) SetThemesNil(b bool)`

 SetThemesNil sets the value for Themes to be an explicit nil

### UnsetThemes
`func (o *StoryGenerateRequest) UnsetThemes()`

UnsetThemes ensures that no value is present for Themes, not even an explicit nil
### GetTargetNodeCount

`func (o *StoryGenerateRequest) GetTargetNodeCount() int32`

GetTargetNodeCount returns the TargetNodeCount field if non-nil, zero value otherwise.

### GetTargetNodeCountOk

`func (o *StoryGenerateRequest) GetTargetNodeCountOk() (*int32, bool)`

GetTargetNodeCountOk returns a tuple with the TargetNodeCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetNodeCount

`func (o *StoryGenerateRequest) SetTargetNodeCount(v int32)`

SetTargetNodeCount sets TargetNodeCount field to given value.

### HasTargetNodeCount

`func (o *StoryGenerateRequest) HasTargetNodeCount() bool`

HasTargetNodeCount returns a boolean if a field has been set.

### SetTargetNodeCountNil

`func (o *StoryGenerateRequest) SetTargetNodeCountNil(b bool)`

 SetTargetNodeCountNil sets the value for TargetNodeCount to be an explicit nil

### UnsetTargetNodeCount
`func (o *StoryGenerateRequest) UnsetTargetNodeCount()`

UnsetTargetNodeCount ensures that no value is present for TargetNodeCount, not even an explicit nil
### GetAgeRating

`func (o *StoryGenerateRequest) GetAgeRating() string`

GetAgeRating returns the AgeRating field if non-nil, zero value otherwise.

### GetAgeRatingOk

`func (o *StoryGenerateRequest) GetAgeRatingOk() (*string, bool)`

GetAgeRatingOk returns a tuple with the AgeRating field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgeRating

`func (o *StoryGenerateRequest) SetAgeRating(v string)`

SetAgeRating sets AgeRating field to given value.

### HasAgeRating

`func (o *StoryGenerateRequest) HasAgeRating() bool`

HasAgeRating returns a boolean if a field has been set.

### SetAgeRatingNil

`func (o *StoryGenerateRequest) SetAgeRatingNil(b bool)`

 SetAgeRatingNil sets the value for AgeRating to be an explicit nil

### UnsetAgeRating
`func (o *StoryGenerateRequest) UnsetAgeRating()`

UnsetAgeRating ensures that no value is present for AgeRating, not even an explicit nil
### GetComplexity

`func (o *StoryGenerateRequest) GetComplexity() int32`

GetComplexity returns the Complexity field if non-nil, zero value otherwise.

### GetComplexityOk

`func (o *StoryGenerateRequest) GetComplexityOk() (*int32, bool)`

GetComplexityOk returns a tuple with the Complexity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComplexity

`func (o *StoryGenerateRequest) SetComplexity(v int32)`

SetComplexity sets Complexity field to given value.

### HasComplexity

`func (o *StoryGenerateRequest) HasComplexity() bool`

HasComplexity returns a boolean if a field has been set.

### SetComplexityNil

`func (o *StoryGenerateRequest) SetComplexityNil(b bool)`

 SetComplexityNil sets the value for Complexity to be an explicit nil

### UnsetComplexity
`func (o *StoryGenerateRequest) UnsetComplexity()`

UnsetComplexity ensures that no value is present for Complexity, not even an explicit nil
### GetInitialWorldFlags

`func (o *StoryGenerateRequest) GetInitialWorldFlags() map[string]interface{}`

GetInitialWorldFlags returns the InitialWorldFlags field if non-nil, zero value otherwise.

### GetInitialWorldFlagsOk

`func (o *StoryGenerateRequest) GetInitialWorldFlagsOk() (*map[string]interface{}, bool)`

GetInitialWorldFlagsOk returns a tuple with the InitialWorldFlags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInitialWorldFlags

`func (o *StoryGenerateRequest) SetInitialWorldFlags(v map[string]interface{})`

SetInitialWorldFlags sets InitialWorldFlags field to given value.

### HasInitialWorldFlags

`func (o *StoryGenerateRequest) HasInitialWorldFlags() bool`

HasInitialWorldFlags returns a boolean if a field has been set.

### SetInitialWorldFlagsNil

`func (o *StoryGenerateRequest) SetInitialWorldFlagsNil(b bool)`

 SetInitialWorldFlagsNil sets the value for InitialWorldFlags to be an explicit nil

### UnsetInitialWorldFlags
`func (o *StoryGenerateRequest) UnsetInitialWorldFlags()`

UnsetInitialWorldFlags ensures that no value is present for InitialWorldFlags, not even an explicit nil
### GetFlagSchema

`func (o *StoryGenerateRequest) GetFlagSchema() map[string]interface{}`

GetFlagSchema returns the FlagSchema field if non-nil, zero value otherwise.

### GetFlagSchemaOk

`func (o *StoryGenerateRequest) GetFlagSchemaOk() (*map[string]interface{}, bool)`

GetFlagSchemaOk returns a tuple with the FlagSchema field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFlagSchema

`func (o *StoryGenerateRequest) SetFlagSchema(v map[string]interface{})`

SetFlagSchema sets FlagSchema field to given value.

### HasFlagSchema

`func (o *StoryGenerateRequest) HasFlagSchema() bool`

HasFlagSchema returns a boolean if a field has been set.

### SetFlagSchemaNil

`func (o *StoryGenerateRequest) SetFlagSchemaNil(b bool)`

 SetFlagSchemaNil sets the value for FlagSchema to be an explicit nil

### UnsetFlagSchema
`func (o *StoryGenerateRequest) UnsetFlagSchema()`

UnsetFlagSchema ensures that no value is present for FlagSchema, not even an explicit nil
### GetCharacters

`func (o *StoryGenerateRequest) GetCharacters() map[string]interface{}`

GetCharacters returns the Characters field if non-nil, zero value otherwise.

### GetCharactersOk

`func (o *StoryGenerateRequest) GetCharactersOk() (*map[string]interface{}, bool)`

GetCharactersOk returns a tuple with the Characters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCharacters

`func (o *StoryGenerateRequest) SetCharacters(v map[string]interface{})`

SetCharacters sets Characters field to given value.

### HasCharacters

`func (o *StoryGenerateRequest) HasCharacters() bool`

HasCharacters returns a boolean if a field has been set.

### SetCharactersNil

`func (o *StoryGenerateRequest) SetCharactersNil(b bool)`

 SetCharactersNil sets the value for Characters to be an explicit nil

### UnsetCharacters
`func (o *StoryGenerateRequest) UnsetCharacters()`

UnsetCharacters ensures that no value is present for Characters, not even an explicit nil
### GetLocations

`func (o *StoryGenerateRequest) GetLocations() map[string]interface{}`

GetLocations returns the Locations field if non-nil, zero value otherwise.

### GetLocationsOk

`func (o *StoryGenerateRequest) GetLocationsOk() (*map[string]interface{}, bool)`

GetLocationsOk returns a tuple with the Locations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocations

`func (o *StoryGenerateRequest) SetLocations(v map[string]interface{})`

SetLocations sets Locations field to given value.

### HasLocations

`func (o *StoryGenerateRequest) HasLocations() bool`

HasLocations returns a boolean if a field has been set.

### SetLocationsNil

`func (o *StoryGenerateRequest) SetLocationsNil(b bool)`

 SetLocationsNil sets the value for Locations to be an explicit nil

### UnsetLocations
`func (o *StoryGenerateRequest) UnsetLocations()`

UnsetLocations ensures that no value is present for Locations, not even an explicit nil
### GetObjects

`func (o *StoryGenerateRequest) GetObjects() map[string]interface{}`

GetObjects returns the Objects field if non-nil, zero value otherwise.

### GetObjectsOk

`func (o *StoryGenerateRequest) GetObjectsOk() (*map[string]interface{}, bool)`

GetObjectsOk returns a tuple with the Objects field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObjects

`func (o *StoryGenerateRequest) SetObjects(v map[string]interface{})`

SetObjects sets Objects field to given value.

### HasObjects

`func (o *StoryGenerateRequest) HasObjects() bool`

HasObjects returns a boolean if a field has been set.

### SetObjectsNil

`func (o *StoryGenerateRequest) SetObjectsNil(b bool)`

 SetObjectsNil sets the value for Objects to be an explicit nil

### UnsetObjects
`func (o *StoryGenerateRequest) UnsetObjects()`

UnsetObjects ensures that no value is present for Objects, not even an explicit nil
### GetAllowFreeTextContinuation

`func (o *StoryGenerateRequest) GetAllowFreeTextContinuation() bool`

GetAllowFreeTextContinuation returns the AllowFreeTextContinuation field if non-nil, zero value otherwise.

### GetAllowFreeTextContinuationOk

`func (o *StoryGenerateRequest) GetAllowFreeTextContinuationOk() (*bool, bool)`

GetAllowFreeTextContinuationOk returns a tuple with the AllowFreeTextContinuation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowFreeTextContinuation

`func (o *StoryGenerateRequest) SetAllowFreeTextContinuation(v bool)`

SetAllowFreeTextContinuation sets AllowFreeTextContinuation field to given value.

### HasAllowFreeTextContinuation

`func (o *StoryGenerateRequest) HasAllowFreeTextContinuation() bool`

HasAllowFreeTextContinuation returns a boolean if a field has been set.

### GetUnbounded

`func (o *StoryGenerateRequest) GetUnbounded() bool`

GetUnbounded returns the Unbounded field if non-nil, zero value otherwise.

### GetUnboundedOk

`func (o *StoryGenerateRequest) GetUnboundedOk() (*bool, bool)`

GetUnboundedOk returns a tuple with the Unbounded field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnbounded

`func (o *StoryGenerateRequest) SetUnbounded(v bool)`

SetUnbounded sets Unbounded field to given value.

### HasUnbounded

`func (o *StoryGenerateRequest) HasUnbounded() bool`

HasUnbounded returns a boolean if a field has been set.

### GetAllowLlmCharacters

`func (o *StoryGenerateRequest) GetAllowLlmCharacters() bool`

GetAllowLlmCharacters returns the AllowLlmCharacters field if non-nil, zero value otherwise.

### GetAllowLlmCharactersOk

`func (o *StoryGenerateRequest) GetAllowLlmCharactersOk() (*bool, bool)`

GetAllowLlmCharactersOk returns a tuple with the AllowLlmCharacters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowLlmCharacters

`func (o *StoryGenerateRequest) SetAllowLlmCharacters(v bool)`

SetAllowLlmCharacters sets AllowLlmCharacters field to given value.

### HasAllowLlmCharacters

`func (o *StoryGenerateRequest) HasAllowLlmCharacters() bool`

HasAllowLlmCharacters returns a boolean if a field has been set.

### GetAllowLlmLocations

`func (o *StoryGenerateRequest) GetAllowLlmLocations() bool`

GetAllowLlmLocations returns the AllowLlmLocations field if non-nil, zero value otherwise.

### GetAllowLlmLocationsOk

`func (o *StoryGenerateRequest) GetAllowLlmLocationsOk() (*bool, bool)`

GetAllowLlmLocationsOk returns a tuple with the AllowLlmLocations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowLlmLocations

`func (o *StoryGenerateRequest) SetAllowLlmLocations(v bool)`

SetAllowLlmLocations sets AllowLlmLocations field to given value.

### HasAllowLlmLocations

`func (o *StoryGenerateRequest) HasAllowLlmLocations() bool`

HasAllowLlmLocations returns a boolean if a field has been set.

### GetAllowLlmObjects

`func (o *StoryGenerateRequest) GetAllowLlmObjects() bool`

GetAllowLlmObjects returns the AllowLlmObjects field if non-nil, zero value otherwise.

### GetAllowLlmObjectsOk

`func (o *StoryGenerateRequest) GetAllowLlmObjectsOk() (*bool, bool)`

GetAllowLlmObjectsOk returns a tuple with the AllowLlmObjects field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowLlmObjects

`func (o *StoryGenerateRequest) SetAllowLlmObjects(v bool)`

SetAllowLlmObjects sets AllowLlmObjects field to given value.

### HasAllowLlmObjects

`func (o *StoryGenerateRequest) HasAllowLlmObjects() bool`

HasAllowLlmObjects returns a boolean if a field has been set.

### GetOutcomeAnchors

`func (o *StoryGenerateRequest) GetOutcomeAnchors() []string`

GetOutcomeAnchors returns the OutcomeAnchors field if non-nil, zero value otherwise.

### GetOutcomeAnchorsOk

`func (o *StoryGenerateRequest) GetOutcomeAnchorsOk() (*[]string, bool)`

GetOutcomeAnchorsOk returns a tuple with the OutcomeAnchors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutcomeAnchors

`func (o *StoryGenerateRequest) SetOutcomeAnchors(v []string)`

SetOutcomeAnchors sets OutcomeAnchors field to given value.

### HasOutcomeAnchors

`func (o *StoryGenerateRequest) HasOutcomeAnchors() bool`

HasOutcomeAnchors returns a boolean if a field has been set.

### SetOutcomeAnchorsNil

`func (o *StoryGenerateRequest) SetOutcomeAnchorsNil(b bool)`

 SetOutcomeAnchorsNil sets the value for OutcomeAnchors to be an explicit nil

### UnsetOutcomeAnchors
`func (o *StoryGenerateRequest) UnsetOutcomeAnchors()`

UnsetOutcomeAnchors ensures that no value is present for OutcomeAnchors, not even an explicit nil
### GetHistorySummaryMaxChars

`func (o *StoryGenerateRequest) GetHistorySummaryMaxChars() int32`

GetHistorySummaryMaxChars returns the HistorySummaryMaxChars field if non-nil, zero value otherwise.

### GetHistorySummaryMaxCharsOk

`func (o *StoryGenerateRequest) GetHistorySummaryMaxCharsOk() (*int32, bool)`

GetHistorySummaryMaxCharsOk returns a tuple with the HistorySummaryMaxChars field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHistorySummaryMaxChars

`func (o *StoryGenerateRequest) SetHistorySummaryMaxChars(v int32)`

SetHistorySummaryMaxChars sets HistorySummaryMaxChars field to given value.

### HasHistorySummaryMaxChars

`func (o *StoryGenerateRequest) HasHistorySummaryMaxChars() bool`

HasHistorySummaryMaxChars returns a boolean if a field has been set.

### SetHistorySummaryMaxCharsNil

`func (o *StoryGenerateRequest) SetHistorySummaryMaxCharsNil(b bool)`

 SetHistorySummaryMaxCharsNil sets the value for HistorySummaryMaxChars to be an explicit nil

### UnsetHistorySummaryMaxChars
`func (o *StoryGenerateRequest) UnsetHistorySummaryMaxChars()`

UnsetHistorySummaryMaxChars ensures that no value is present for HistorySummaryMaxChars, not even an explicit nil
### GetHistoryContextWindow

`func (o *StoryGenerateRequest) GetHistoryContextWindow() int32`

GetHistoryContextWindow returns the HistoryContextWindow field if non-nil, zero value otherwise.

### GetHistoryContextWindowOk

`func (o *StoryGenerateRequest) GetHistoryContextWindowOk() (*int32, bool)`

GetHistoryContextWindowOk returns a tuple with the HistoryContextWindow field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHistoryContextWindow

`func (o *StoryGenerateRequest) SetHistoryContextWindow(v int32)`

SetHistoryContextWindow sets HistoryContextWindow field to given value.

### HasHistoryContextWindow

`func (o *StoryGenerateRequest) HasHistoryContextWindow() bool`

HasHistoryContextWindow returns a boolean if a field has been set.

### SetHistoryContextWindowNil

`func (o *StoryGenerateRequest) SetHistoryContextWindowNil(b bool)`

 SetHistoryContextWindowNil sets the value for HistoryContextWindow to be an explicit nil

### UnsetHistoryContextWindow
`func (o *StoryGenerateRequest) UnsetHistoryContextWindow()`

UnsetHistoryContextWindow ensures that no value is present for HistoryContextWindow, not even an explicit nil
### GetWorldSystemPrompt

`func (o *StoryGenerateRequest) GetWorldSystemPrompt() string`

GetWorldSystemPrompt returns the WorldSystemPrompt field if non-nil, zero value otherwise.

### GetWorldSystemPromptOk

`func (o *StoryGenerateRequest) GetWorldSystemPromptOk() (*string, bool)`

GetWorldSystemPromptOk returns a tuple with the WorldSystemPrompt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorldSystemPrompt

`func (o *StoryGenerateRequest) SetWorldSystemPrompt(v string)`

SetWorldSystemPrompt sets WorldSystemPrompt field to given value.

### HasWorldSystemPrompt

`func (o *StoryGenerateRequest) HasWorldSystemPrompt() bool`

HasWorldSystemPrompt returns a boolean if a field has been set.

### SetWorldSystemPromptNil

`func (o *StoryGenerateRequest) SetWorldSystemPromptNil(b bool)`

 SetWorldSystemPromptNil sets the value for WorldSystemPrompt to be an explicit nil

### UnsetWorldSystemPrompt
`func (o *StoryGenerateRequest) UnsetWorldSystemPrompt()`

UnsetWorldSystemPrompt ensures that no value is present for WorldSystemPrompt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


