# ObjectSpecResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** |  | 
**Description** | **string** |  | 
**ObjectType** | Pointer to **string** |  | [optional] [default to ""]
**LocationId** | Pointer to **string** |  | [optional] [default to ""]
**HolderId** | Pointer to **string** |  | [optional] [default to ""]

## Methods

### NewObjectSpecResponse

`func NewObjectSpecResponse(name string, description string, ) *ObjectSpecResponse`

NewObjectSpecResponse instantiates a new ObjectSpecResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewObjectSpecResponseWithDefaults

`func NewObjectSpecResponseWithDefaults() *ObjectSpecResponse`

NewObjectSpecResponseWithDefaults instantiates a new ObjectSpecResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *ObjectSpecResponse) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ObjectSpecResponse) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ObjectSpecResponse) SetName(v string)`

SetName sets Name field to given value.


### GetDescription

`func (o *ObjectSpecResponse) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ObjectSpecResponse) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ObjectSpecResponse) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetObjectType

`func (o *ObjectSpecResponse) GetObjectType() string`

GetObjectType returns the ObjectType field if non-nil, zero value otherwise.

### GetObjectTypeOk

`func (o *ObjectSpecResponse) GetObjectTypeOk() (*string, bool)`

GetObjectTypeOk returns a tuple with the ObjectType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObjectType

`func (o *ObjectSpecResponse) SetObjectType(v string)`

SetObjectType sets ObjectType field to given value.

### HasObjectType

`func (o *ObjectSpecResponse) HasObjectType() bool`

HasObjectType returns a boolean if a field has been set.

### GetLocationId

`func (o *ObjectSpecResponse) GetLocationId() string`

GetLocationId returns the LocationId field if non-nil, zero value otherwise.

### GetLocationIdOk

`func (o *ObjectSpecResponse) GetLocationIdOk() (*string, bool)`

GetLocationIdOk returns a tuple with the LocationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocationId

`func (o *ObjectSpecResponse) SetLocationId(v string)`

SetLocationId sets LocationId field to given value.

### HasLocationId

`func (o *ObjectSpecResponse) HasLocationId() bool`

HasLocationId returns a boolean if a field has been set.

### GetHolderId

`func (o *ObjectSpecResponse) GetHolderId() string`

GetHolderId returns the HolderId field if non-nil, zero value otherwise.

### GetHolderIdOk

`func (o *ObjectSpecResponse) GetHolderIdOk() (*string, bool)`

GetHolderIdOk returns a tuple with the HolderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHolderId

`func (o *ObjectSpecResponse) SetHolderId(v string)`

SetHolderId sets HolderId field to given value.

### HasHolderId

`func (o *ObjectSpecResponse) HasHolderId() bool`

HasHolderId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


