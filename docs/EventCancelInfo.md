# EventCancelInfo

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Owner** | **string** | Who requested the cancellation | [optional] 
**StartTime** | [**time.Time**](time.Time.md) | When cancellation was requested | [optional] 
**AckTime** | [**time.Time**](time.Time.md) | When cancellation was acknowledged | [optional] 
**Reason** | **string** | Reason for cancellation | [optional] 
**Asked** | **bool** | Whether cancellation was requested | [optional] 
**Canceled** | **bool** | Whether the event was actually canceled | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


