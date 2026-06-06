# PathsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**StoryId** | **string** |  | 
**Paths** | **[][]string** |  | 

## Methods

### NewPathsResponse

`func NewPathsResponse(storyId string, paths [][]string, ) *PathsResponse`

NewPathsResponse instantiates a new PathsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPathsResponseWithDefaults

`func NewPathsResponseWithDefaults() *PathsResponse`

NewPathsResponseWithDefaults instantiates a new PathsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStoryId

`func (o *PathsResponse) GetStoryId() string`

GetStoryId returns the StoryId field if non-nil, zero value otherwise.

### GetStoryIdOk

`func (o *PathsResponse) GetStoryIdOk() (*string, bool)`

GetStoryIdOk returns a tuple with the StoryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStoryId

`func (o *PathsResponse) SetStoryId(v string)`

SetStoryId sets StoryId field to given value.


### GetPaths

`func (o *PathsResponse) GetPaths() [][]string`

GetPaths returns the Paths field if non-nil, zero value otherwise.

### GetPathsOk

`func (o *PathsResponse) GetPathsOk() (*[][]string, bool)`

GetPathsOk returns a tuple with the Paths field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaths

`func (o *PathsResponse) SetPaths(v [][]string)`

SetPaths sets Paths field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


