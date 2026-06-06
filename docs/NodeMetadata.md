# NodeMetadata

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AgeRating** | **string** |  | 
**Mood** | **string** |  | 
**Genre** | **string** |  | 
**Themes** | **[]string** |  | 
**Complexity** | **int32** |  | 
**DramaScore** | Pointer to **NullableFloat32** |  | [optional] 

## Methods

### NewNodeMetadata

`func NewNodeMetadata(ageRating string, mood string, genre string, themes []string, complexity int32, ) *NodeMetadata`

NewNodeMetadata instantiates a new NodeMetadata object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewNodeMetadataWithDefaults

`func NewNodeMetadataWithDefaults() *NodeMetadata`

NewNodeMetadataWithDefaults instantiates a new NodeMetadata object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAgeRating

`func (o *NodeMetadata) GetAgeRating() string`

GetAgeRating returns the AgeRating field if non-nil, zero value otherwise.

### GetAgeRatingOk

`func (o *NodeMetadata) GetAgeRatingOk() (*string, bool)`

GetAgeRatingOk returns a tuple with the AgeRating field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgeRating

`func (o *NodeMetadata) SetAgeRating(v string)`

SetAgeRating sets AgeRating field to given value.


### GetMood

`func (o *NodeMetadata) GetMood() string`

GetMood returns the Mood field if non-nil, zero value otherwise.

### GetMoodOk

`func (o *NodeMetadata) GetMoodOk() (*string, bool)`

GetMoodOk returns a tuple with the Mood field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMood

`func (o *NodeMetadata) SetMood(v string)`

SetMood sets Mood field to given value.


### GetGenre

`func (o *NodeMetadata) GetGenre() string`

GetGenre returns the Genre field if non-nil, zero value otherwise.

### GetGenreOk

`func (o *NodeMetadata) GetGenreOk() (*string, bool)`

GetGenreOk returns a tuple with the Genre field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGenre

`func (o *NodeMetadata) SetGenre(v string)`

SetGenre sets Genre field to given value.


### GetThemes

`func (o *NodeMetadata) GetThemes() []string`

GetThemes returns the Themes field if non-nil, zero value otherwise.

### GetThemesOk

`func (o *NodeMetadata) GetThemesOk() (*[]string, bool)`

GetThemesOk returns a tuple with the Themes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThemes

`func (o *NodeMetadata) SetThemes(v []string)`

SetThemes sets Themes field to given value.


### GetComplexity

`func (o *NodeMetadata) GetComplexity() int32`

GetComplexity returns the Complexity field if non-nil, zero value otherwise.

### GetComplexityOk

`func (o *NodeMetadata) GetComplexityOk() (*int32, bool)`

GetComplexityOk returns a tuple with the Complexity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComplexity

`func (o *NodeMetadata) SetComplexity(v int32)`

SetComplexity sets Complexity field to given value.


### GetDramaScore

`func (o *NodeMetadata) GetDramaScore() float32`

GetDramaScore returns the DramaScore field if non-nil, zero value otherwise.

### GetDramaScoreOk

`func (o *NodeMetadata) GetDramaScoreOk() (*float32, bool)`

GetDramaScoreOk returns a tuple with the DramaScore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDramaScore

`func (o *NodeMetadata) SetDramaScore(v float32)`

SetDramaScore sets DramaScore field to given value.

### HasDramaScore

`func (o *NodeMetadata) HasDramaScore() bool`

HasDramaScore returns a boolean if a field has been set.

### SetDramaScoreNil

`func (o *NodeMetadata) SetDramaScoreNil(b bool)`

 SetDramaScoreNil sets the value for DramaScore to be an explicit nil

### UnsetDramaScore
`func (o *NodeMetadata) UnsetDramaScore()`

UnsetDramaScore ensures that no value is present for DramaScore, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


