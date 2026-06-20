# V1AdminStoryImportPostDefaultResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Details** | Pointer to **map[string]map[string]interface{}** |  | [optional] 
**ErrorCode** | **string** |  | 
**Message** | **string** |  | 

## Methods

### NewV1AdminStoryImportPostDefaultResponse

`func NewV1AdminStoryImportPostDefaultResponse(errorCode string, message string, ) *V1AdminStoryImportPostDefaultResponse`

NewV1AdminStoryImportPostDefaultResponse instantiates a new V1AdminStoryImportPostDefaultResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1AdminStoryImportPostDefaultResponseWithDefaults

`func NewV1AdminStoryImportPostDefaultResponseWithDefaults() *V1AdminStoryImportPostDefaultResponse`

NewV1AdminStoryImportPostDefaultResponseWithDefaults instantiates a new V1AdminStoryImportPostDefaultResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDetails

`func (o *V1AdminStoryImportPostDefaultResponse) GetDetails() map[string]map[string]interface{}`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *V1AdminStoryImportPostDefaultResponse) GetDetailsOk() (*map[string]map[string]interface{}, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *V1AdminStoryImportPostDefaultResponse) SetDetails(v map[string]map[string]interface{})`

SetDetails sets Details field to given value.

### HasDetails

`func (o *V1AdminStoryImportPostDefaultResponse) HasDetails() bool`

HasDetails returns a boolean if a field has been set.

### GetErrorCode

`func (o *V1AdminStoryImportPostDefaultResponse) GetErrorCode() string`

GetErrorCode returns the ErrorCode field if non-nil, zero value otherwise.

### GetErrorCodeOk

`func (o *V1AdminStoryImportPostDefaultResponse) GetErrorCodeOk() (*string, bool)`

GetErrorCodeOk returns a tuple with the ErrorCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorCode

`func (o *V1AdminStoryImportPostDefaultResponse) SetErrorCode(v string)`

SetErrorCode sets ErrorCode field to given value.


### GetMessage

`func (o *V1AdminStoryImportPostDefaultResponse) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *V1AdminStoryImportPostDefaultResponse) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *V1AdminStoryImportPostDefaultResponse) SetMessage(v string)`

SetMessage sets Message field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


