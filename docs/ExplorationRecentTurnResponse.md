# ExplorationRecentTurnResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ExplorationTurnId** | **string** |  | 
**QuestionHash** | **string** |  | 
**CacheSource** | **string** |  | 
**CacheHit** | **bool** |  | 
**RequiresAction** | **bool** |  | 
**RedirectReason** | Pointer to **NullableString** |  | [optional] 
**CreatedAt** | Pointer to **string** |  | [optional] [default to ""]

## Methods

### NewExplorationRecentTurnResponse

`func NewExplorationRecentTurnResponse(explorationTurnId string, questionHash string, cacheSource string, cacheHit bool, requiresAction bool, ) *ExplorationRecentTurnResponse`

NewExplorationRecentTurnResponse instantiates a new ExplorationRecentTurnResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewExplorationRecentTurnResponseWithDefaults

`func NewExplorationRecentTurnResponseWithDefaults() *ExplorationRecentTurnResponse`

NewExplorationRecentTurnResponseWithDefaults instantiates a new ExplorationRecentTurnResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetExplorationTurnId

`func (o *ExplorationRecentTurnResponse) GetExplorationTurnId() string`

GetExplorationTurnId returns the ExplorationTurnId field if non-nil, zero value otherwise.

### GetExplorationTurnIdOk

`func (o *ExplorationRecentTurnResponse) GetExplorationTurnIdOk() (*string, bool)`

GetExplorationTurnIdOk returns a tuple with the ExplorationTurnId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExplorationTurnId

`func (o *ExplorationRecentTurnResponse) SetExplorationTurnId(v string)`

SetExplorationTurnId sets ExplorationTurnId field to given value.


### GetQuestionHash

`func (o *ExplorationRecentTurnResponse) GetQuestionHash() string`

GetQuestionHash returns the QuestionHash field if non-nil, zero value otherwise.

### GetQuestionHashOk

`func (o *ExplorationRecentTurnResponse) GetQuestionHashOk() (*string, bool)`

GetQuestionHashOk returns a tuple with the QuestionHash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuestionHash

`func (o *ExplorationRecentTurnResponse) SetQuestionHash(v string)`

SetQuestionHash sets QuestionHash field to given value.


### GetCacheSource

`func (o *ExplorationRecentTurnResponse) GetCacheSource() string`

GetCacheSource returns the CacheSource field if non-nil, zero value otherwise.

### GetCacheSourceOk

`func (o *ExplorationRecentTurnResponse) GetCacheSourceOk() (*string, bool)`

GetCacheSourceOk returns a tuple with the CacheSource field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCacheSource

`func (o *ExplorationRecentTurnResponse) SetCacheSource(v string)`

SetCacheSource sets CacheSource field to given value.


### GetCacheHit

`func (o *ExplorationRecentTurnResponse) GetCacheHit() bool`

GetCacheHit returns the CacheHit field if non-nil, zero value otherwise.

### GetCacheHitOk

`func (o *ExplorationRecentTurnResponse) GetCacheHitOk() (*bool, bool)`

GetCacheHitOk returns a tuple with the CacheHit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCacheHit

`func (o *ExplorationRecentTurnResponse) SetCacheHit(v bool)`

SetCacheHit sets CacheHit field to given value.


### GetRequiresAction

`func (o *ExplorationRecentTurnResponse) GetRequiresAction() bool`

GetRequiresAction returns the RequiresAction field if non-nil, zero value otherwise.

### GetRequiresActionOk

`func (o *ExplorationRecentTurnResponse) GetRequiresActionOk() (*bool, bool)`

GetRequiresActionOk returns a tuple with the RequiresAction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequiresAction

`func (o *ExplorationRecentTurnResponse) SetRequiresAction(v bool)`

SetRequiresAction sets RequiresAction field to given value.


### GetRedirectReason

`func (o *ExplorationRecentTurnResponse) GetRedirectReason() string`

GetRedirectReason returns the RedirectReason field if non-nil, zero value otherwise.

### GetRedirectReasonOk

`func (o *ExplorationRecentTurnResponse) GetRedirectReasonOk() (*string, bool)`

GetRedirectReasonOk returns a tuple with the RedirectReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRedirectReason

`func (o *ExplorationRecentTurnResponse) SetRedirectReason(v string)`

SetRedirectReason sets RedirectReason field to given value.

### HasRedirectReason

`func (o *ExplorationRecentTurnResponse) HasRedirectReason() bool`

HasRedirectReason returns a boolean if a field has been set.

### SetRedirectReasonNil

`func (o *ExplorationRecentTurnResponse) SetRedirectReasonNil(b bool)`

 SetRedirectReasonNil sets the value for RedirectReason to be an explicit nil

### UnsetRedirectReason
`func (o *ExplorationRecentTurnResponse) UnsetRedirectReason()`

UnsetRedirectReason ensures that no value is present for RedirectReason, not even an explicit nil
### GetCreatedAt

`func (o *ExplorationRecentTurnResponse) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ExplorationRecentTurnResponse) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ExplorationRecentTurnResponse) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *ExplorationRecentTurnResponse) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


