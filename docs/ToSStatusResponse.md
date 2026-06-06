# ToSStatusResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Accepted** | **bool** |  | 
**Version** | **NullableString** |  | 

## Methods

### NewToSStatusResponse

`func NewToSStatusResponse(accepted bool, version NullableString, ) *ToSStatusResponse`

NewToSStatusResponse instantiates a new ToSStatusResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewToSStatusResponseWithDefaults

`func NewToSStatusResponseWithDefaults() *ToSStatusResponse`

NewToSStatusResponseWithDefaults instantiates a new ToSStatusResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccepted

`func (o *ToSStatusResponse) GetAccepted() bool`

GetAccepted returns the Accepted field if non-nil, zero value otherwise.

### GetAcceptedOk

`func (o *ToSStatusResponse) GetAcceptedOk() (*bool, bool)`

GetAcceptedOk returns a tuple with the Accepted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccepted

`func (o *ToSStatusResponse) SetAccepted(v bool)`

SetAccepted sets Accepted field to given value.


### GetVersion

`func (o *ToSStatusResponse) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *ToSStatusResponse) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *ToSStatusResponse) SetVersion(v string)`

SetVersion sets Version field to given value.


### SetVersionNil

`func (o *ToSStatusResponse) SetVersionNil(b bool)`

 SetVersionNil sets the value for Version to be an explicit nil

### UnsetVersion
`func (o *ToSStatusResponse) UnsetVersion()`

UnsetVersion ensures that no value is present for Version, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


