# ArcAnalysis

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DramaScore** | **float32** |  | 
**TensionLabel** | **string** |  | 
**Depth** | **int32** |  | 
**MaxNodes** | **int32** |  | 
**Progress** | **float32** |  | 
**Phase** | **string** |  | 
**IdealTension** | **float32** |  | 
**Deviation** | **float32** |  | 
**OnTrack** | **bool** |  | 
**ChoicesReordered** | **bool** |  | 
**Unbounded** | Pointer to **bool** |  | [optional] [default to false]

## Methods

### NewArcAnalysis

`func NewArcAnalysis(dramaScore float32, tensionLabel string, depth int32, maxNodes int32, progress float32, phase string, idealTension float32, deviation float32, onTrack bool, choicesReordered bool, ) *ArcAnalysis`

NewArcAnalysis instantiates a new ArcAnalysis object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewArcAnalysisWithDefaults

`func NewArcAnalysisWithDefaults() *ArcAnalysis`

NewArcAnalysisWithDefaults instantiates a new ArcAnalysis object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDramaScore

`func (o *ArcAnalysis) GetDramaScore() float32`

GetDramaScore returns the DramaScore field if non-nil, zero value otherwise.

### GetDramaScoreOk

`func (o *ArcAnalysis) GetDramaScoreOk() (*float32, bool)`

GetDramaScoreOk returns a tuple with the DramaScore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDramaScore

`func (o *ArcAnalysis) SetDramaScore(v float32)`

SetDramaScore sets DramaScore field to given value.


### GetTensionLabel

`func (o *ArcAnalysis) GetTensionLabel() string`

GetTensionLabel returns the TensionLabel field if non-nil, zero value otherwise.

### GetTensionLabelOk

`func (o *ArcAnalysis) GetTensionLabelOk() (*string, bool)`

GetTensionLabelOk returns a tuple with the TensionLabel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTensionLabel

`func (o *ArcAnalysis) SetTensionLabel(v string)`

SetTensionLabel sets TensionLabel field to given value.


### GetDepth

`func (o *ArcAnalysis) GetDepth() int32`

GetDepth returns the Depth field if non-nil, zero value otherwise.

### GetDepthOk

`func (o *ArcAnalysis) GetDepthOk() (*int32, bool)`

GetDepthOk returns a tuple with the Depth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDepth

`func (o *ArcAnalysis) SetDepth(v int32)`

SetDepth sets Depth field to given value.


### GetMaxNodes

`func (o *ArcAnalysis) GetMaxNodes() int32`

GetMaxNodes returns the MaxNodes field if non-nil, zero value otherwise.

### GetMaxNodesOk

`func (o *ArcAnalysis) GetMaxNodesOk() (*int32, bool)`

GetMaxNodesOk returns a tuple with the MaxNodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxNodes

`func (o *ArcAnalysis) SetMaxNodes(v int32)`

SetMaxNodes sets MaxNodes field to given value.


### GetProgress

`func (o *ArcAnalysis) GetProgress() float32`

GetProgress returns the Progress field if non-nil, zero value otherwise.

### GetProgressOk

`func (o *ArcAnalysis) GetProgressOk() (*float32, bool)`

GetProgressOk returns a tuple with the Progress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProgress

`func (o *ArcAnalysis) SetProgress(v float32)`

SetProgress sets Progress field to given value.


### GetPhase

`func (o *ArcAnalysis) GetPhase() string`

GetPhase returns the Phase field if non-nil, zero value otherwise.

### GetPhaseOk

`func (o *ArcAnalysis) GetPhaseOk() (*string, bool)`

GetPhaseOk returns a tuple with the Phase field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhase

`func (o *ArcAnalysis) SetPhase(v string)`

SetPhase sets Phase field to given value.


### GetIdealTension

`func (o *ArcAnalysis) GetIdealTension() float32`

GetIdealTension returns the IdealTension field if non-nil, zero value otherwise.

### GetIdealTensionOk

`func (o *ArcAnalysis) GetIdealTensionOk() (*float32, bool)`

GetIdealTensionOk returns a tuple with the IdealTension field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdealTension

`func (o *ArcAnalysis) SetIdealTension(v float32)`

SetIdealTension sets IdealTension field to given value.


### GetDeviation

`func (o *ArcAnalysis) GetDeviation() float32`

GetDeviation returns the Deviation field if non-nil, zero value otherwise.

### GetDeviationOk

`func (o *ArcAnalysis) GetDeviationOk() (*float32, bool)`

GetDeviationOk returns a tuple with the Deviation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviation

`func (o *ArcAnalysis) SetDeviation(v float32)`

SetDeviation sets Deviation field to given value.


### GetOnTrack

`func (o *ArcAnalysis) GetOnTrack() bool`

GetOnTrack returns the OnTrack field if non-nil, zero value otherwise.

### GetOnTrackOk

`func (o *ArcAnalysis) GetOnTrackOk() (*bool, bool)`

GetOnTrackOk returns a tuple with the OnTrack field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOnTrack

`func (o *ArcAnalysis) SetOnTrack(v bool)`

SetOnTrack sets OnTrack field to given value.


### GetChoicesReordered

`func (o *ArcAnalysis) GetChoicesReordered() bool`

GetChoicesReordered returns the ChoicesReordered field if non-nil, zero value otherwise.

### GetChoicesReorderedOk

`func (o *ArcAnalysis) GetChoicesReorderedOk() (*bool, bool)`

GetChoicesReorderedOk returns a tuple with the ChoicesReordered field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChoicesReordered

`func (o *ArcAnalysis) SetChoicesReordered(v bool)`

SetChoicesReordered sets ChoicesReordered field to given value.


### GetUnbounded

`func (o *ArcAnalysis) GetUnbounded() bool`

GetUnbounded returns the Unbounded field if non-nil, zero value otherwise.

### GetUnboundedOk

`func (o *ArcAnalysis) GetUnboundedOk() (*bool, bool)`

GetUnboundedOk returns a tuple with the Unbounded field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnbounded

`func (o *ArcAnalysis) SetUnbounded(v bool)`

SetUnbounded sets Unbounded field to given value.

### HasUnbounded

`func (o *ArcAnalysis) HasUnbounded() bool`

HasUnbounded returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


