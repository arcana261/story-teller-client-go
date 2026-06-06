# PaginatedResponseAuthoringStorySummaryResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Items** | [**[]AuthoringStorySummaryResponse**](AuthoringStorySummaryResponse.md) |  | 
**NextCursor** | **NullableString** |  | 
**HasMore** | **bool** |  | 

## Methods

### NewPaginatedResponseAuthoringStorySummaryResponse

`func NewPaginatedResponseAuthoringStorySummaryResponse(items []AuthoringStorySummaryResponse, nextCursor NullableString, hasMore bool, ) *PaginatedResponseAuthoringStorySummaryResponse`

NewPaginatedResponseAuthoringStorySummaryResponse instantiates a new PaginatedResponseAuthoringStorySummaryResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPaginatedResponseAuthoringStorySummaryResponseWithDefaults

`func NewPaginatedResponseAuthoringStorySummaryResponseWithDefaults() *PaginatedResponseAuthoringStorySummaryResponse`

NewPaginatedResponseAuthoringStorySummaryResponseWithDefaults instantiates a new PaginatedResponseAuthoringStorySummaryResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetItems

`func (o *PaginatedResponseAuthoringStorySummaryResponse) GetItems() []AuthoringStorySummaryResponse`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *PaginatedResponseAuthoringStorySummaryResponse) GetItemsOk() (*[]AuthoringStorySummaryResponse, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *PaginatedResponseAuthoringStorySummaryResponse) SetItems(v []AuthoringStorySummaryResponse)`

SetItems sets Items field to given value.


### GetNextCursor

`func (o *PaginatedResponseAuthoringStorySummaryResponse) GetNextCursor() string`

GetNextCursor returns the NextCursor field if non-nil, zero value otherwise.

### GetNextCursorOk

`func (o *PaginatedResponseAuthoringStorySummaryResponse) GetNextCursorOk() (*string, bool)`

GetNextCursorOk returns a tuple with the NextCursor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextCursor

`func (o *PaginatedResponseAuthoringStorySummaryResponse) SetNextCursor(v string)`

SetNextCursor sets NextCursor field to given value.


### SetNextCursorNil

`func (o *PaginatedResponseAuthoringStorySummaryResponse) SetNextCursorNil(b bool)`

 SetNextCursorNil sets the value for NextCursor to be an explicit nil

### UnsetNextCursor
`func (o *PaginatedResponseAuthoringStorySummaryResponse) UnsetNextCursor()`

UnsetNextCursor ensures that no value is present for NextCursor, not even an explicit nil
### GetHasMore

`func (o *PaginatedResponseAuthoringStorySummaryResponse) GetHasMore() bool`

GetHasMore returns the HasMore field if non-nil, zero value otherwise.

### GetHasMoreOk

`func (o *PaginatedResponseAuthoringStorySummaryResponse) GetHasMoreOk() (*bool, bool)`

GetHasMoreOk returns a tuple with the HasMore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasMore

`func (o *PaginatedResponseAuthoringStorySummaryResponse) SetHasMore(v bool)`

SetHasMore sets HasMore field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


