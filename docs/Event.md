# Event

## Properties
Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ID** | **string** | MongoDB ObjectID as string (bson _id field) | [optional] 
**UniqueID** | **string** | Unique identifier as ObjectID string | [optional] 
**Lock** | [**EventTarget**](EventTarget.md) |  | [optional] 
**StartTime** | [**time.Time**](time.Time.md) | Event start time | [optional] 
**EndTime** | [**time.Time**](time.Time.md) | Event end time (optional) | [optional] 
**ExpireAt** | [**time.Time**](time.Time.md) | When the event expires and can be removed (optional) | [optional] 
**Target** | [**EventTarget**](EventTarget.md) |  | [optional] 
**ExtraTargets** | [**[]EventExtraTarget**](EventExtraTarget.md) | Additional targets for this event | [optional] 
**Kind** | [**EventKind**](EventKind.md) |  | [optional] 
**Owner** | [**EventOwner**](EventOwner.md) |  | [optional] 
**SourceIP** | **string** | IP address from which the event was triggered | [optional] 
**LockUpdateTime** | [**time.Time**](time.Time.md) | Last time the lock was updated | [optional] 
**Error** | **string** | Error message if the event failed | [optional] 
**Log** | **string** | Event log (plain text, optional) | [optional] 
**StructuredLog** | [**[]EventLogEntry**](EventLogEntry.md) | Structured log entries | [optional] 
**CancelInfo** | [**EventCancelInfo**](EventCancelInfo.md) |  | [optional] 
**Cancelable** | **bool** | Whether this event can be canceled | [optional] 
**Running** | **bool** | Whether this event is currently running | [optional] 
**Allowed** | [**EventAllowedPermission**](EventAllowedPermission.md) |  | [optional] 
**AllowedCancel** | [**EventAllowedPermission**](EventAllowedPermission.md) |  | [optional] 
**Instance** | [**EventTrackedInstance**](EventTrackedInstance.md) |  | [optional] 
**StartCustomData** | [**EventStartCustomData**](EventStartCustomData.md) |  | [optional] 
**EndCustomData** | [**EventStartCustomData**](EventStartCustomData.md) |  | [optional] 
**OtherCustomData** | [**EventStartCustomData**](EventStartCustomData.md) |  | [optional] 
**CustomData** | [**EventCustomData**](EventCustomData.md) |  | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


