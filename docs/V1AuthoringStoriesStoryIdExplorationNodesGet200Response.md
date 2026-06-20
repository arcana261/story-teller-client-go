# V1AuthoringStoriesStoryIdExplorationNodesGet200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**HasMore** | **bool** |  | 
**Items** | [**[]V1AuthoringStoriesStoryIdExplorationNodesGet200ResponseItemsInner**](V1AuthoringStoriesStoryIdExplorationNodesGet200ResponseItemsInner.md) |  | 
**NextCursor** | Pointer to **string** |  | [optional] 

## Methods

### NewV1AuthoringStoriesStoryIdExplorationNodesGet200Response

`func NewV1AuthoringStoriesStoryIdExplorationNodesGet200Response(hasMore bool, items []V1AuthoringStoriesStoryIdExplorationNodesGet200ResponseItemsInner, ) *V1AuthoringStoriesStoryIdExplorationNodesGet200Response`

NewV1AuthoringStoriesStoryIdExplorationNodesGet200Response instantiates a new V1AuthoringStoriesStoryIdExplorationNodesGet200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1AuthoringStoriesStoryIdExplorationNodesGet200ResponseWithDefaults

`func NewV1AuthoringStoriesStoryIdExplorationNodesGet200ResponseWithDefaults() *V1AuthoringStoriesStoryIdExplorationNodesGet200Response`

NewV1AuthoringStoriesStoryIdExplorationNodesGet200ResponseWithDefaults instantiates a new V1AuthoringStoriesStoryIdExplorationNodesGet200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHasMore

`func (o *V1AuthoringStoriesStoryIdExplorationNodesGet200Response) GetHasMore() bool`

GetHasMore returns the HasMore field if non-nil, zero value otherwise.

### GetHasMoreOk

`func (o *V1AuthoringStoriesStoryIdExplorationNodesGet200Response) GetHasMoreOk() (*bool, bool)`

GetHasMoreOk returns a tuple with the HasMore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasMore

`func (o *V1AuthoringStoriesStoryIdExplorationNodesGet200Response) SetHasMore(v bool)`

SetHasMore sets HasMore field to given value.


### GetItems

`func (o *V1AuthoringStoriesStoryIdExplorationNodesGet200Response) GetItems() []V1AuthoringStoriesStoryIdExplorationNodesGet200ResponseItemsInner`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *V1AuthoringStoriesStoryIdExplorationNodesGet200Response) GetItemsOk() (*[]V1AuthoringStoriesStoryIdExplorationNodesGet200ResponseItemsInner, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *V1AuthoringStoriesStoryIdExplorationNodesGet200Response) SetItems(v []V1AuthoringStoriesStoryIdExplorationNodesGet200ResponseItemsInner)`

SetItems sets Items field to given value.


### GetNextCursor

`func (o *V1AuthoringStoriesStoryIdExplorationNodesGet200Response) GetNextCursor() string`

GetNextCursor returns the NextCursor field if non-nil, zero value otherwise.

### GetNextCursorOk

`func (o *V1AuthoringStoriesStoryIdExplorationNodesGet200Response) GetNextCursorOk() (*string, bool)`

GetNextCursorOk returns a tuple with the NextCursor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextCursor

`func (o *V1AuthoringStoriesStoryIdExplorationNodesGet200Response) SetNextCursor(v string)`

SetNextCursor sets NextCursor field to given value.

### HasNextCursor

`func (o *V1AuthoringStoriesStoryIdExplorationNodesGet200Response) HasNextCursor() bool`

HasNextCursor returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


