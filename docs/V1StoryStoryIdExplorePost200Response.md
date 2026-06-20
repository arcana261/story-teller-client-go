# V1StoryStoryIdExplorePost200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Answer** | **string** |  | 
**CacheHit** | **bool** |  | 
**CacheSource** | Pointer to **string** |  | [optional] 
**CanonicalDetailVersion** | Pointer to **int32** |  | [optional] 
**Confidence** | **string** |  | 
**CurrentNodeIdAfter** | Pointer to **string** |  | [optional] 
**CurrentNodeIdBefore** | Pointer to **string** |  | [optional] 
**DetailDelta** | **map[string]map[string]interface{}** |  | 
**ExplorationNodeId** | Pointer to **string** |  | [optional] 
**ExplorationTurnId** | Pointer to **string** |  | [optional] 
**FormalizedText** | Pointer to **string** |  | [optional] 
**HiddenInfoRequested** | **bool** |  | 
**IdempotencyReplay** | **bool** |  | 
**NodeId** | Pointer to **string** |  | [optional] 
**OverlayVersion** | Pointer to **int32** |  | [optional] 
**RedirectReason** | Pointer to **string** |  | [optional] 
**RequiresAction** | **bool** |  | 

## Methods

### NewV1StoryStoryIdExplorePost200Response

`func NewV1StoryStoryIdExplorePost200Response(answer string, cacheHit bool, confidence string, detailDelta map[string]map[string]interface{}, hiddenInfoRequested bool, idempotencyReplay bool, requiresAction bool, ) *V1StoryStoryIdExplorePost200Response`

NewV1StoryStoryIdExplorePost200Response instantiates a new V1StoryStoryIdExplorePost200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1StoryStoryIdExplorePost200ResponseWithDefaults

`func NewV1StoryStoryIdExplorePost200ResponseWithDefaults() *V1StoryStoryIdExplorePost200Response`

NewV1StoryStoryIdExplorePost200ResponseWithDefaults instantiates a new V1StoryStoryIdExplorePost200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAnswer

`func (o *V1StoryStoryIdExplorePost200Response) GetAnswer() string`

GetAnswer returns the Answer field if non-nil, zero value otherwise.

### GetAnswerOk

`func (o *V1StoryStoryIdExplorePost200Response) GetAnswerOk() (*string, bool)`

GetAnswerOk returns a tuple with the Answer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAnswer

`func (o *V1StoryStoryIdExplorePost200Response) SetAnswer(v string)`

SetAnswer sets Answer field to given value.


### GetCacheHit

`func (o *V1StoryStoryIdExplorePost200Response) GetCacheHit() bool`

GetCacheHit returns the CacheHit field if non-nil, zero value otherwise.

### GetCacheHitOk

`func (o *V1StoryStoryIdExplorePost200Response) GetCacheHitOk() (*bool, bool)`

GetCacheHitOk returns a tuple with the CacheHit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCacheHit

`func (o *V1StoryStoryIdExplorePost200Response) SetCacheHit(v bool)`

SetCacheHit sets CacheHit field to given value.


### GetCacheSource

`func (o *V1StoryStoryIdExplorePost200Response) GetCacheSource() string`

GetCacheSource returns the CacheSource field if non-nil, zero value otherwise.

### GetCacheSourceOk

`func (o *V1StoryStoryIdExplorePost200Response) GetCacheSourceOk() (*string, bool)`

GetCacheSourceOk returns a tuple with the CacheSource field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCacheSource

`func (o *V1StoryStoryIdExplorePost200Response) SetCacheSource(v string)`

SetCacheSource sets CacheSource field to given value.

### HasCacheSource

`func (o *V1StoryStoryIdExplorePost200Response) HasCacheSource() bool`

HasCacheSource returns a boolean if a field has been set.

### GetCanonicalDetailVersion

`func (o *V1StoryStoryIdExplorePost200Response) GetCanonicalDetailVersion() int32`

GetCanonicalDetailVersion returns the CanonicalDetailVersion field if non-nil, zero value otherwise.

### GetCanonicalDetailVersionOk

`func (o *V1StoryStoryIdExplorePost200Response) GetCanonicalDetailVersionOk() (*int32, bool)`

GetCanonicalDetailVersionOk returns a tuple with the CanonicalDetailVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCanonicalDetailVersion

`func (o *V1StoryStoryIdExplorePost200Response) SetCanonicalDetailVersion(v int32)`

SetCanonicalDetailVersion sets CanonicalDetailVersion field to given value.

### HasCanonicalDetailVersion

`func (o *V1StoryStoryIdExplorePost200Response) HasCanonicalDetailVersion() bool`

HasCanonicalDetailVersion returns a boolean if a field has been set.

### GetConfidence

`func (o *V1StoryStoryIdExplorePost200Response) GetConfidence() string`

GetConfidence returns the Confidence field if non-nil, zero value otherwise.

### GetConfidenceOk

`func (o *V1StoryStoryIdExplorePost200Response) GetConfidenceOk() (*string, bool)`

GetConfidenceOk returns a tuple with the Confidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfidence

`func (o *V1StoryStoryIdExplorePost200Response) SetConfidence(v string)`

SetConfidence sets Confidence field to given value.


### GetCurrentNodeIdAfter

`func (o *V1StoryStoryIdExplorePost200Response) GetCurrentNodeIdAfter() string`

GetCurrentNodeIdAfter returns the CurrentNodeIdAfter field if non-nil, zero value otherwise.

### GetCurrentNodeIdAfterOk

`func (o *V1StoryStoryIdExplorePost200Response) GetCurrentNodeIdAfterOk() (*string, bool)`

GetCurrentNodeIdAfterOk returns a tuple with the CurrentNodeIdAfter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentNodeIdAfter

`func (o *V1StoryStoryIdExplorePost200Response) SetCurrentNodeIdAfter(v string)`

SetCurrentNodeIdAfter sets CurrentNodeIdAfter field to given value.

### HasCurrentNodeIdAfter

`func (o *V1StoryStoryIdExplorePost200Response) HasCurrentNodeIdAfter() bool`

HasCurrentNodeIdAfter returns a boolean if a field has been set.

### GetCurrentNodeIdBefore

`func (o *V1StoryStoryIdExplorePost200Response) GetCurrentNodeIdBefore() string`

GetCurrentNodeIdBefore returns the CurrentNodeIdBefore field if non-nil, zero value otherwise.

### GetCurrentNodeIdBeforeOk

`func (o *V1StoryStoryIdExplorePost200Response) GetCurrentNodeIdBeforeOk() (*string, bool)`

GetCurrentNodeIdBeforeOk returns a tuple with the CurrentNodeIdBefore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentNodeIdBefore

`func (o *V1StoryStoryIdExplorePost200Response) SetCurrentNodeIdBefore(v string)`

SetCurrentNodeIdBefore sets CurrentNodeIdBefore field to given value.

### HasCurrentNodeIdBefore

`func (o *V1StoryStoryIdExplorePost200Response) HasCurrentNodeIdBefore() bool`

HasCurrentNodeIdBefore returns a boolean if a field has been set.

### GetDetailDelta

`func (o *V1StoryStoryIdExplorePost200Response) GetDetailDelta() map[string]map[string]interface{}`

GetDetailDelta returns the DetailDelta field if non-nil, zero value otherwise.

### GetDetailDeltaOk

`func (o *V1StoryStoryIdExplorePost200Response) GetDetailDeltaOk() (*map[string]map[string]interface{}, bool)`

GetDetailDeltaOk returns a tuple with the DetailDelta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetailDelta

`func (o *V1StoryStoryIdExplorePost200Response) SetDetailDelta(v map[string]map[string]interface{})`

SetDetailDelta sets DetailDelta field to given value.


### GetExplorationNodeId

`func (o *V1StoryStoryIdExplorePost200Response) GetExplorationNodeId() string`

GetExplorationNodeId returns the ExplorationNodeId field if non-nil, zero value otherwise.

### GetExplorationNodeIdOk

`func (o *V1StoryStoryIdExplorePost200Response) GetExplorationNodeIdOk() (*string, bool)`

GetExplorationNodeIdOk returns a tuple with the ExplorationNodeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExplorationNodeId

`func (o *V1StoryStoryIdExplorePost200Response) SetExplorationNodeId(v string)`

SetExplorationNodeId sets ExplorationNodeId field to given value.

### HasExplorationNodeId

`func (o *V1StoryStoryIdExplorePost200Response) HasExplorationNodeId() bool`

HasExplorationNodeId returns a boolean if a field has been set.

### GetExplorationTurnId

`func (o *V1StoryStoryIdExplorePost200Response) GetExplorationTurnId() string`

GetExplorationTurnId returns the ExplorationTurnId field if non-nil, zero value otherwise.

### GetExplorationTurnIdOk

`func (o *V1StoryStoryIdExplorePost200Response) GetExplorationTurnIdOk() (*string, bool)`

GetExplorationTurnIdOk returns a tuple with the ExplorationTurnId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExplorationTurnId

`func (o *V1StoryStoryIdExplorePost200Response) SetExplorationTurnId(v string)`

SetExplorationTurnId sets ExplorationTurnId field to given value.

### HasExplorationTurnId

`func (o *V1StoryStoryIdExplorePost200Response) HasExplorationTurnId() bool`

HasExplorationTurnId returns a boolean if a field has been set.

### GetFormalizedText

`func (o *V1StoryStoryIdExplorePost200Response) GetFormalizedText() string`

GetFormalizedText returns the FormalizedText field if non-nil, zero value otherwise.

### GetFormalizedTextOk

`func (o *V1StoryStoryIdExplorePost200Response) GetFormalizedTextOk() (*string, bool)`

GetFormalizedTextOk returns a tuple with the FormalizedText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormalizedText

`func (o *V1StoryStoryIdExplorePost200Response) SetFormalizedText(v string)`

SetFormalizedText sets FormalizedText field to given value.

### HasFormalizedText

`func (o *V1StoryStoryIdExplorePost200Response) HasFormalizedText() bool`

HasFormalizedText returns a boolean if a field has been set.

### GetHiddenInfoRequested

`func (o *V1StoryStoryIdExplorePost200Response) GetHiddenInfoRequested() bool`

GetHiddenInfoRequested returns the HiddenInfoRequested field if non-nil, zero value otherwise.

### GetHiddenInfoRequestedOk

`func (o *V1StoryStoryIdExplorePost200Response) GetHiddenInfoRequestedOk() (*bool, bool)`

GetHiddenInfoRequestedOk returns a tuple with the HiddenInfoRequested field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHiddenInfoRequested

`func (o *V1StoryStoryIdExplorePost200Response) SetHiddenInfoRequested(v bool)`

SetHiddenInfoRequested sets HiddenInfoRequested field to given value.


### GetIdempotencyReplay

`func (o *V1StoryStoryIdExplorePost200Response) GetIdempotencyReplay() bool`

GetIdempotencyReplay returns the IdempotencyReplay field if non-nil, zero value otherwise.

### GetIdempotencyReplayOk

`func (o *V1StoryStoryIdExplorePost200Response) GetIdempotencyReplayOk() (*bool, bool)`

GetIdempotencyReplayOk returns a tuple with the IdempotencyReplay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdempotencyReplay

`func (o *V1StoryStoryIdExplorePost200Response) SetIdempotencyReplay(v bool)`

SetIdempotencyReplay sets IdempotencyReplay field to given value.


### GetNodeId

`func (o *V1StoryStoryIdExplorePost200Response) GetNodeId() string`

GetNodeId returns the NodeId field if non-nil, zero value otherwise.

### GetNodeIdOk

`func (o *V1StoryStoryIdExplorePost200Response) GetNodeIdOk() (*string, bool)`

GetNodeIdOk returns a tuple with the NodeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNodeId

`func (o *V1StoryStoryIdExplorePost200Response) SetNodeId(v string)`

SetNodeId sets NodeId field to given value.

### HasNodeId

`func (o *V1StoryStoryIdExplorePost200Response) HasNodeId() bool`

HasNodeId returns a boolean if a field has been set.

### GetOverlayVersion

`func (o *V1StoryStoryIdExplorePost200Response) GetOverlayVersion() int32`

GetOverlayVersion returns the OverlayVersion field if non-nil, zero value otherwise.

### GetOverlayVersionOk

`func (o *V1StoryStoryIdExplorePost200Response) GetOverlayVersionOk() (*int32, bool)`

GetOverlayVersionOk returns a tuple with the OverlayVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOverlayVersion

`func (o *V1StoryStoryIdExplorePost200Response) SetOverlayVersion(v int32)`

SetOverlayVersion sets OverlayVersion field to given value.

### HasOverlayVersion

`func (o *V1StoryStoryIdExplorePost200Response) HasOverlayVersion() bool`

HasOverlayVersion returns a boolean if a field has been set.

### GetRedirectReason

`func (o *V1StoryStoryIdExplorePost200Response) GetRedirectReason() string`

GetRedirectReason returns the RedirectReason field if non-nil, zero value otherwise.

### GetRedirectReasonOk

`func (o *V1StoryStoryIdExplorePost200Response) GetRedirectReasonOk() (*string, bool)`

GetRedirectReasonOk returns a tuple with the RedirectReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRedirectReason

`func (o *V1StoryStoryIdExplorePost200Response) SetRedirectReason(v string)`

SetRedirectReason sets RedirectReason field to given value.

### HasRedirectReason

`func (o *V1StoryStoryIdExplorePost200Response) HasRedirectReason() bool`

HasRedirectReason returns a boolean if a field has been set.

### GetRequiresAction

`func (o *V1StoryStoryIdExplorePost200Response) GetRequiresAction() bool`

GetRequiresAction returns the RequiresAction field if non-nil, zero value otherwise.

### GetRequiresActionOk

`func (o *V1StoryStoryIdExplorePost200Response) GetRequiresActionOk() (*bool, bool)`

GetRequiresActionOk returns a tuple with the RequiresAction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequiresAction

`func (o *V1StoryStoryIdExplorePost200Response) SetRequiresAction(v bool)`

SetRequiresAction sets RequiresAction field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


