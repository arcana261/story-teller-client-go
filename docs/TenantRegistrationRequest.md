# TenantRegistrationRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** |  | 
**ContactEmail** | **string** |  | 
**AnthropicApiKey** | **string** |  | 
**BillingCountry** | **string** |  | 
**MaxAgeRating** | Pointer to **string** |  | [optional] [default to "teen"]

## Methods

### NewTenantRegistrationRequest

`func NewTenantRegistrationRequest(name string, contactEmail string, anthropicApiKey string, billingCountry string, ) *TenantRegistrationRequest`

NewTenantRegistrationRequest instantiates a new TenantRegistrationRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTenantRegistrationRequestWithDefaults

`func NewTenantRegistrationRequestWithDefaults() *TenantRegistrationRequest`

NewTenantRegistrationRequestWithDefaults instantiates a new TenantRegistrationRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *TenantRegistrationRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *TenantRegistrationRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *TenantRegistrationRequest) SetName(v string)`

SetName sets Name field to given value.


### GetContactEmail

`func (o *TenantRegistrationRequest) GetContactEmail() string`

GetContactEmail returns the ContactEmail field if non-nil, zero value otherwise.

### GetContactEmailOk

`func (o *TenantRegistrationRequest) GetContactEmailOk() (*string, bool)`

GetContactEmailOk returns a tuple with the ContactEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactEmail

`func (o *TenantRegistrationRequest) SetContactEmail(v string)`

SetContactEmail sets ContactEmail field to given value.


### GetAnthropicApiKey

`func (o *TenantRegistrationRequest) GetAnthropicApiKey() string`

GetAnthropicApiKey returns the AnthropicApiKey field if non-nil, zero value otherwise.

### GetAnthropicApiKeyOk

`func (o *TenantRegistrationRequest) GetAnthropicApiKeyOk() (*string, bool)`

GetAnthropicApiKeyOk returns a tuple with the AnthropicApiKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAnthropicApiKey

`func (o *TenantRegistrationRequest) SetAnthropicApiKey(v string)`

SetAnthropicApiKey sets AnthropicApiKey field to given value.


### GetBillingCountry

`func (o *TenantRegistrationRequest) GetBillingCountry() string`

GetBillingCountry returns the BillingCountry field if non-nil, zero value otherwise.

### GetBillingCountryOk

`func (o *TenantRegistrationRequest) GetBillingCountryOk() (*string, bool)`

GetBillingCountryOk returns a tuple with the BillingCountry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingCountry

`func (o *TenantRegistrationRequest) SetBillingCountry(v string)`

SetBillingCountry sets BillingCountry field to given value.


### GetMaxAgeRating

`func (o *TenantRegistrationRequest) GetMaxAgeRating() string`

GetMaxAgeRating returns the MaxAgeRating field if non-nil, zero value otherwise.

### GetMaxAgeRatingOk

`func (o *TenantRegistrationRequest) GetMaxAgeRatingOk() (*string, bool)`

GetMaxAgeRatingOk returns a tuple with the MaxAgeRating field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxAgeRating

`func (o *TenantRegistrationRequest) SetMaxAgeRating(v string)`

SetMaxAgeRating sets MaxAgeRating field to given value.

### HasMaxAgeRating

`func (o *TenantRegistrationRequest) HasMaxAgeRating() bool`

HasMaxAgeRating returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


