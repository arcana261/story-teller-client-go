# StorySummaryResponse

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

## Methods

### NewStorySummaryResponse

`func NewStorySummaryResponse(storyId string, title string, startNodeId string, ) *StorySummaryResponse`

NewStorySummaryResponse instantiates a new StorySummaryResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStorySummaryResponseWithDefaults

`func NewStorySummaryResponseWithDefaults() *StorySummaryResponse`

NewStorySummaryResponseWithDefaults instantiates a new StorySummaryResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStoryId

`func (o *StorySummaryResponse) GetStoryId() string`

GetStoryId returns the StoryId field if non-nil, zero value otherwise.

### GetStoryIdOk

`func (o *StorySummaryResponse) GetStoryIdOk() (*string, bool)`

GetStoryIdOk returns a tuple with the StoryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStoryId

`func (o *StorySummaryResponse) SetStoryId(v string)`

SetStoryId sets StoryId field to given value.


### GetTitle

`func (o *StorySummaryResponse) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *StorySummaryResponse) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *StorySummaryResponse) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetStartNodeId

`func (o *StorySummaryResponse) GetStartNodeId() string`

GetStartNodeId returns the StartNodeId field if non-nil, zero value otherwise.

### GetStartNodeIdOk

`func (o *StorySummaryResponse) GetStartNodeIdOk() (*string, bool)`

GetStartNodeIdOk returns a tuple with the StartNodeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartNodeId

`func (o *StorySummaryResponse) SetStartNodeId(v string)`

SetStartNodeId sets StartNodeId field to given value.


### GetGenre

`func (o *StorySummaryResponse) GetGenre() string`

GetGenre returns the Genre field if non-nil, zero value otherwise.

### GetGenreOk

`func (o *StorySummaryResponse) GetGenreOk() (*string, bool)`

GetGenreOk returns a tuple with the Genre field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGenre

`func (o *StorySummaryResponse) SetGenre(v string)`

SetGenre sets Genre field to given value.

### HasGenre

`func (o *StorySummaryResponse) HasGenre() bool`

HasGenre returns a boolean if a field has been set.

### SetGenreNil

`func (o *StorySummaryResponse) SetGenreNil(b bool)`

 SetGenreNil sets the value for Genre to be an explicit nil

### UnsetGenre
`func (o *StorySummaryResponse) UnsetGenre()`

UnsetGenre ensures that no value is present for Genre, not even an explicit nil
### GetContentWarnings

`func (o *StorySummaryResponse) GetContentWarnings() []string`

GetContentWarnings returns the ContentWarnings field if non-nil, zero value otherwise.

### GetContentWarningsOk

`func (o *StorySummaryResponse) GetContentWarningsOk() (*[]string, bool)`

GetContentWarningsOk returns a tuple with the ContentWarnings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContentWarnings

`func (o *StorySummaryResponse) SetContentWarnings(v []string)`

SetContentWarnings sets ContentWarnings field to given value.

### HasContentWarnings

`func (o *StorySummaryResponse) HasContentWarnings() bool`

HasContentWarnings returns a boolean if a field has been set.

### SetContentWarningsNil

`func (o *StorySummaryResponse) SetContentWarningsNil(b bool)`

 SetContentWarningsNil sets the value for ContentWarnings to be an explicit nil

### UnsetContentWarnings
`func (o *StorySummaryResponse) UnsetContentWarnings()`

UnsetContentWarnings ensures that no value is present for ContentWarnings, not even an explicit nil
### GetMaxNodes

`func (o *StorySummaryResponse) GetMaxNodes() int32`

GetMaxNodes returns the MaxNodes field if non-nil, zero value otherwise.

### GetMaxNodesOk

`func (o *StorySummaryResponse) GetMaxNodesOk() (*int32, bool)`

GetMaxNodesOk returns a tuple with the MaxNodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxNodes

`func (o *StorySummaryResponse) SetMaxNodes(v int32)`

SetMaxNodes sets MaxNodes field to given value.

### HasMaxNodes

`func (o *StorySummaryResponse) HasMaxNodes() bool`

HasMaxNodes returns a boolean if a field has been set.

### GetUnbounded

`func (o *StorySummaryResponse) GetUnbounded() bool`

GetUnbounded returns the Unbounded field if non-nil, zero value otherwise.

### GetUnboundedOk

`func (o *StorySummaryResponse) GetUnboundedOk() (*bool, bool)`

GetUnboundedOk returns a tuple with the Unbounded field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnbounded

`func (o *StorySummaryResponse) SetUnbounded(v bool)`

SetUnbounded sets Unbounded field to given value.

### HasUnbounded

`func (o *StorySummaryResponse) HasUnbounded() bool`

HasUnbounded returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


