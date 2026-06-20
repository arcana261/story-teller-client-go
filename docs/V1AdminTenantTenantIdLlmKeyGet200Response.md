# V1AdminTenantTenantIdLlmKeyGet200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BudgetRemaining** | Pointer to **float32** |  | [optional] 
**KeyAlias** | Pointer to **string** |  | [optional] 
**KeyStatus** | Pointer to **string** |  | [optional] 
**MaxBudget** | Pointer to **float32** |  | [optional] 
**Models** | **[]string** |  | 
**NotProvisioned** | **bool** |  | 
**PolicyDrift** | **bool** |  | 
**RevocationPending** | **bool** |  | 
**Spend** | Pointer to **float32** |  | [optional] 
**TenantId** | **string** |  | 
**UpdatedAt** | Pointer to **string** |  | [optional] 

## Methods

### NewV1AdminTenantTenantIdLlmKeyGet200Response

`func NewV1AdminTenantTenantIdLlmKeyGet200Response(models []string, notProvisioned bool, policyDrift bool, revocationPending bool, tenantId string, ) *V1AdminTenantTenantIdLlmKeyGet200Response`

NewV1AdminTenantTenantIdLlmKeyGet200Response instantiates a new V1AdminTenantTenantIdLlmKeyGet200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1AdminTenantTenantIdLlmKeyGet200ResponseWithDefaults

`func NewV1AdminTenantTenantIdLlmKeyGet200ResponseWithDefaults() *V1AdminTenantTenantIdLlmKeyGet200Response`

NewV1AdminTenantTenantIdLlmKeyGet200ResponseWithDefaults instantiates a new V1AdminTenantTenantIdLlmKeyGet200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBudgetRemaining

`func (o *V1AdminTenantTenantIdLlmKeyGet200Response) GetBudgetRemaining() float32`

GetBudgetRemaining returns the BudgetRemaining field if non-nil, zero value otherwise.

### GetBudgetRemainingOk

`func (o *V1AdminTenantTenantIdLlmKeyGet200Response) GetBudgetRemainingOk() (*float32, bool)`

GetBudgetRemainingOk returns a tuple with the BudgetRemaining field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBudgetRemaining

`func (o *V1AdminTenantTenantIdLlmKeyGet200Response) SetBudgetRemaining(v float32)`

SetBudgetRemaining sets BudgetRemaining field to given value.

### HasBudgetRemaining

`func (o *V1AdminTenantTenantIdLlmKeyGet200Response) HasBudgetRemaining() bool`

HasBudgetRemaining returns a boolean if a field has been set.

### GetKeyAlias

`func (o *V1AdminTenantTenantIdLlmKeyGet200Response) GetKeyAlias() string`

GetKeyAlias returns the KeyAlias field if non-nil, zero value otherwise.

### GetKeyAliasOk

`func (o *V1AdminTenantTenantIdLlmKeyGet200Response) GetKeyAliasOk() (*string, bool)`

GetKeyAliasOk returns a tuple with the KeyAlias field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeyAlias

`func (o *V1AdminTenantTenantIdLlmKeyGet200Response) SetKeyAlias(v string)`

SetKeyAlias sets KeyAlias field to given value.

### HasKeyAlias

`func (o *V1AdminTenantTenantIdLlmKeyGet200Response) HasKeyAlias() bool`

HasKeyAlias returns a boolean if a field has been set.

### GetKeyStatus

`func (o *V1AdminTenantTenantIdLlmKeyGet200Response) GetKeyStatus() string`

GetKeyStatus returns the KeyStatus field if non-nil, zero value otherwise.

### GetKeyStatusOk

`func (o *V1AdminTenantTenantIdLlmKeyGet200Response) GetKeyStatusOk() (*string, bool)`

GetKeyStatusOk returns a tuple with the KeyStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeyStatus

`func (o *V1AdminTenantTenantIdLlmKeyGet200Response) SetKeyStatus(v string)`

SetKeyStatus sets KeyStatus field to given value.

### HasKeyStatus

`func (o *V1AdminTenantTenantIdLlmKeyGet200Response) HasKeyStatus() bool`

HasKeyStatus returns a boolean if a field has been set.

### GetMaxBudget

`func (o *V1AdminTenantTenantIdLlmKeyGet200Response) GetMaxBudget() float32`

GetMaxBudget returns the MaxBudget field if non-nil, zero value otherwise.

### GetMaxBudgetOk

`func (o *V1AdminTenantTenantIdLlmKeyGet200Response) GetMaxBudgetOk() (*float32, bool)`

GetMaxBudgetOk returns a tuple with the MaxBudget field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxBudget

`func (o *V1AdminTenantTenantIdLlmKeyGet200Response) SetMaxBudget(v float32)`

SetMaxBudget sets MaxBudget field to given value.

### HasMaxBudget

`func (o *V1AdminTenantTenantIdLlmKeyGet200Response) HasMaxBudget() bool`

HasMaxBudget returns a boolean if a field has been set.

### GetModels

`func (o *V1AdminTenantTenantIdLlmKeyGet200Response) GetModels() []string`

GetModels returns the Models field if non-nil, zero value otherwise.

### GetModelsOk

`func (o *V1AdminTenantTenantIdLlmKeyGet200Response) GetModelsOk() (*[]string, bool)`

GetModelsOk returns a tuple with the Models field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModels

`func (o *V1AdminTenantTenantIdLlmKeyGet200Response) SetModels(v []string)`

SetModels sets Models field to given value.


### GetNotProvisioned

`func (o *V1AdminTenantTenantIdLlmKeyGet200Response) GetNotProvisioned() bool`

GetNotProvisioned returns the NotProvisioned field if non-nil, zero value otherwise.

### GetNotProvisionedOk

`func (o *V1AdminTenantTenantIdLlmKeyGet200Response) GetNotProvisionedOk() (*bool, bool)`

GetNotProvisionedOk returns a tuple with the NotProvisioned field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotProvisioned

`func (o *V1AdminTenantTenantIdLlmKeyGet200Response) SetNotProvisioned(v bool)`

SetNotProvisioned sets NotProvisioned field to given value.


### GetPolicyDrift

`func (o *V1AdminTenantTenantIdLlmKeyGet200Response) GetPolicyDrift() bool`

GetPolicyDrift returns the PolicyDrift field if non-nil, zero value otherwise.

### GetPolicyDriftOk

`func (o *V1AdminTenantTenantIdLlmKeyGet200Response) GetPolicyDriftOk() (*bool, bool)`

GetPolicyDriftOk returns a tuple with the PolicyDrift field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPolicyDrift

`func (o *V1AdminTenantTenantIdLlmKeyGet200Response) SetPolicyDrift(v bool)`

SetPolicyDrift sets PolicyDrift field to given value.


### GetRevocationPending

`func (o *V1AdminTenantTenantIdLlmKeyGet200Response) GetRevocationPending() bool`

GetRevocationPending returns the RevocationPending field if non-nil, zero value otherwise.

### GetRevocationPendingOk

`func (o *V1AdminTenantTenantIdLlmKeyGet200Response) GetRevocationPendingOk() (*bool, bool)`

GetRevocationPendingOk returns a tuple with the RevocationPending field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevocationPending

`func (o *V1AdminTenantTenantIdLlmKeyGet200Response) SetRevocationPending(v bool)`

SetRevocationPending sets RevocationPending field to given value.


### GetSpend

`func (o *V1AdminTenantTenantIdLlmKeyGet200Response) GetSpend() float32`

GetSpend returns the Spend field if non-nil, zero value otherwise.

### GetSpendOk

`func (o *V1AdminTenantTenantIdLlmKeyGet200Response) GetSpendOk() (*float32, bool)`

GetSpendOk returns a tuple with the Spend field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpend

`func (o *V1AdminTenantTenantIdLlmKeyGet200Response) SetSpend(v float32)`

SetSpend sets Spend field to given value.

### HasSpend

`func (o *V1AdminTenantTenantIdLlmKeyGet200Response) HasSpend() bool`

HasSpend returns a boolean if a field has been set.

### GetTenantId

`func (o *V1AdminTenantTenantIdLlmKeyGet200Response) GetTenantId() string`

GetTenantId returns the TenantId field if non-nil, zero value otherwise.

### GetTenantIdOk

`func (o *V1AdminTenantTenantIdLlmKeyGet200Response) GetTenantIdOk() (*string, bool)`

GetTenantIdOk returns a tuple with the TenantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantId

`func (o *V1AdminTenantTenantIdLlmKeyGet200Response) SetTenantId(v string)`

SetTenantId sets TenantId field to given value.


### GetUpdatedAt

`func (o *V1AdminTenantTenantIdLlmKeyGet200Response) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *V1AdminTenantTenantIdLlmKeyGet200Response) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *V1AdminTenantTenantIdLlmKeyGet200Response) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *V1AdminTenantTenantIdLlmKeyGet200Response) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


