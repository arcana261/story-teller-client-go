# LocationSpecResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** |  | 
**Description** | **string** |  | 
**Region** | Pointer to **string** |  | [optional] [default to ""]
**Atmosphere** | Pointer to **string** |  | [optional] [default to ""]
**ConnectedTo** | Pointer to **[]string** |  | [optional] [default to {}]

## Methods

### NewLocationSpecResponse

`func NewLocationSpecResponse(name string, description string, ) *LocationSpecResponse`

NewLocationSpecResponse instantiates a new LocationSpecResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLocationSpecResponseWithDefaults

`func NewLocationSpecResponseWithDefaults() *LocationSpecResponse`

NewLocationSpecResponseWithDefaults instantiates a new LocationSpecResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *LocationSpecResponse) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *LocationSpecResponse) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *LocationSpecResponse) SetName(v string)`

SetName sets Name field to given value.


### GetDescription

`func (o *LocationSpecResponse) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *LocationSpecResponse) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *LocationSpecResponse) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetRegion

`func (o *LocationSpecResponse) GetRegion() string`

GetRegion returns the Region field if non-nil, zero value otherwise.

### GetRegionOk

`func (o *LocationSpecResponse) GetRegionOk() (*string, bool)`

GetRegionOk returns a tuple with the Region field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegion

`func (o *LocationSpecResponse) SetRegion(v string)`

SetRegion sets Region field to given value.

### HasRegion

`func (o *LocationSpecResponse) HasRegion() bool`

HasRegion returns a boolean if a field has been set.

### GetAtmosphere

`func (o *LocationSpecResponse) GetAtmosphere() string`

GetAtmosphere returns the Atmosphere field if non-nil, zero value otherwise.

### GetAtmosphereOk

`func (o *LocationSpecResponse) GetAtmosphereOk() (*string, bool)`

GetAtmosphereOk returns a tuple with the Atmosphere field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAtmosphere

`func (o *LocationSpecResponse) SetAtmosphere(v string)`

SetAtmosphere sets Atmosphere field to given value.

### HasAtmosphere

`func (o *LocationSpecResponse) HasAtmosphere() bool`

HasAtmosphere returns a boolean if a field has been set.

### GetConnectedTo

`func (o *LocationSpecResponse) GetConnectedTo() []string`

GetConnectedTo returns the ConnectedTo field if non-nil, zero value otherwise.

### GetConnectedToOk

`func (o *LocationSpecResponse) GetConnectedToOk() (*[]string, bool)`

GetConnectedToOk returns a tuple with the ConnectedTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectedTo

`func (o *LocationSpecResponse) SetConnectedTo(v []string)`

SetConnectedTo sets ConnectedTo field to given value.

### HasConnectedTo

`func (o *LocationSpecResponse) HasConnectedTo() bool`

HasConnectedTo returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


