# V1AuthoringStoriesGet200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**HasMore** | **bool** |  | 
**Items** | [**[]V1AuthoringStoriesGet200ResponseItemsInner**](V1AuthoringStoriesGet200ResponseItemsInner.md) |  | 
**NextCursor** | Pointer to **string** |  | [optional] 

## Methods

### NewV1AuthoringStoriesGet200Response

`func NewV1AuthoringStoriesGet200Response(hasMore bool, items []V1AuthoringStoriesGet200ResponseItemsInner, ) *V1AuthoringStoriesGet200Response`

NewV1AuthoringStoriesGet200Response instantiates a new V1AuthoringStoriesGet200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1AuthoringStoriesGet200ResponseWithDefaults

`func NewV1AuthoringStoriesGet200ResponseWithDefaults() *V1AuthoringStoriesGet200Response`

NewV1AuthoringStoriesGet200ResponseWithDefaults instantiates a new V1AuthoringStoriesGet200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHasMore

`func (o *V1AuthoringStoriesGet200Response) GetHasMore() bool`

GetHasMore returns the HasMore field if non-nil, zero value otherwise.

### GetHasMoreOk

`func (o *V1AuthoringStoriesGet200Response) GetHasMoreOk() (*bool, bool)`

GetHasMoreOk returns a tuple with the HasMore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasMore

`func (o *V1AuthoringStoriesGet200Response) SetHasMore(v bool)`

SetHasMore sets HasMore field to given value.


### GetItems

`func (o *V1AuthoringStoriesGet200Response) GetItems() []V1AuthoringStoriesGet200ResponseItemsInner`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *V1AuthoringStoriesGet200Response) GetItemsOk() (*[]V1AuthoringStoriesGet200ResponseItemsInner, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *V1AuthoringStoriesGet200Response) SetItems(v []V1AuthoringStoriesGet200ResponseItemsInner)`

SetItems sets Items field to given value.


### GetNextCursor

`func (o *V1AuthoringStoriesGet200Response) GetNextCursor() string`

GetNextCursor returns the NextCursor field if non-nil, zero value otherwise.

### GetNextCursorOk

`func (o *V1AuthoringStoriesGet200Response) GetNextCursorOk() (*string, bool)`

GetNextCursorOk returns a tuple with the NextCursor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextCursor

`func (o *V1AuthoringStoriesGet200Response) SetNextCursor(v string)`

SetNextCursor sets NextCursor field to given value.

### HasNextCursor

`func (o *V1AuthoringStoriesGet200Response) HasNextCursor() bool`

HasNextCursor returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


