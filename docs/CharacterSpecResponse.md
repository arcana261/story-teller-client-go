# CharacterSpecResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** |  | 
**Role** | **string** |  | 
**Traits** | **[]string** |  | 
**Motive** | **string** |  | 
**Backstory** | Pointer to **string** |  | [optional] [default to ""]
**Voice** | Pointer to **string** |  | [optional] [default to ""]

## Methods

### NewCharacterSpecResponse

`func NewCharacterSpecResponse(name string, role string, traits []string, motive string, ) *CharacterSpecResponse`

NewCharacterSpecResponse instantiates a new CharacterSpecResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCharacterSpecResponseWithDefaults

`func NewCharacterSpecResponseWithDefaults() *CharacterSpecResponse`

NewCharacterSpecResponseWithDefaults instantiates a new CharacterSpecResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *CharacterSpecResponse) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CharacterSpecResponse) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CharacterSpecResponse) SetName(v string)`

SetName sets Name field to given value.


### GetRole

`func (o *CharacterSpecResponse) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *CharacterSpecResponse) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *CharacterSpecResponse) SetRole(v string)`

SetRole sets Role field to given value.


### GetTraits

`func (o *CharacterSpecResponse) GetTraits() []string`

GetTraits returns the Traits field if non-nil, zero value otherwise.

### GetTraitsOk

`func (o *CharacterSpecResponse) GetTraitsOk() (*[]string, bool)`

GetTraitsOk returns a tuple with the Traits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTraits

`func (o *CharacterSpecResponse) SetTraits(v []string)`

SetTraits sets Traits field to given value.


### GetMotive

`func (o *CharacterSpecResponse) GetMotive() string`

GetMotive returns the Motive field if non-nil, zero value otherwise.

### GetMotiveOk

`func (o *CharacterSpecResponse) GetMotiveOk() (*string, bool)`

GetMotiveOk returns a tuple with the Motive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMotive

`func (o *CharacterSpecResponse) SetMotive(v string)`

SetMotive sets Motive field to given value.


### GetBackstory

`func (o *CharacterSpecResponse) GetBackstory() string`

GetBackstory returns the Backstory field if non-nil, zero value otherwise.

### GetBackstoryOk

`func (o *CharacterSpecResponse) GetBackstoryOk() (*string, bool)`

GetBackstoryOk returns a tuple with the Backstory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBackstory

`func (o *CharacterSpecResponse) SetBackstory(v string)`

SetBackstory sets Backstory field to given value.

### HasBackstory

`func (o *CharacterSpecResponse) HasBackstory() bool`

HasBackstory returns a boolean if a field has been set.

### GetVoice

`func (o *CharacterSpecResponse) GetVoice() string`

GetVoice returns the Voice field if non-nil, zero value otherwise.

### GetVoiceOk

`func (o *CharacterSpecResponse) GetVoiceOk() (*string, bool)`

GetVoiceOk returns a tuple with the Voice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoice

`func (o *CharacterSpecResponse) SetVoice(v string)`

SetVoice sets Voice field to given value.

### HasVoice

`func (o *CharacterSpecResponse) HasVoice() bool`

HasVoice returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


