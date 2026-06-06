# JobStatusResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**JobId** | **string** |  | 
**Status** | **string** |  | 
**StoryId** | Pointer to **NullableString** |  | [optional] 
**Error** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewJobStatusResponse

`func NewJobStatusResponse(jobId string, status string, ) *JobStatusResponse`

NewJobStatusResponse instantiates a new JobStatusResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewJobStatusResponseWithDefaults

`func NewJobStatusResponseWithDefaults() *JobStatusResponse`

NewJobStatusResponseWithDefaults instantiates a new JobStatusResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetJobId

`func (o *JobStatusResponse) GetJobId() string`

GetJobId returns the JobId field if non-nil, zero value otherwise.

### GetJobIdOk

`func (o *JobStatusResponse) GetJobIdOk() (*string, bool)`

GetJobIdOk returns a tuple with the JobId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobId

`func (o *JobStatusResponse) SetJobId(v string)`

SetJobId sets JobId field to given value.


### GetStatus

`func (o *JobStatusResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *JobStatusResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *JobStatusResponse) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetStoryId

`func (o *JobStatusResponse) GetStoryId() string`

GetStoryId returns the StoryId field if non-nil, zero value otherwise.

### GetStoryIdOk

`func (o *JobStatusResponse) GetStoryIdOk() (*string, bool)`

GetStoryIdOk returns a tuple with the StoryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStoryId

`func (o *JobStatusResponse) SetStoryId(v string)`

SetStoryId sets StoryId field to given value.

### HasStoryId

`func (o *JobStatusResponse) HasStoryId() bool`

HasStoryId returns a boolean if a field has been set.

### SetStoryIdNil

`func (o *JobStatusResponse) SetStoryIdNil(b bool)`

 SetStoryIdNil sets the value for StoryId to be an explicit nil

### UnsetStoryId
`func (o *JobStatusResponse) UnsetStoryId()`

UnsetStoryId ensures that no value is present for StoryId, not even an explicit nil
### GetError

`func (o *JobStatusResponse) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *JobStatusResponse) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *JobStatusResponse) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *JobStatusResponse) HasError() bool`

HasError returns a boolean if a field has been set.

### SetErrorNil

`func (o *JobStatusResponse) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *JobStatusResponse) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


