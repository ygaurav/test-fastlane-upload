**PROTOCOL**

# `NotificationServiceProvider`

```swift
public protocol NotificationServiceProvider: class
```

## Methods
### `scheduleAttendeeNotification(forEvent:attendeeID:attendeeName:)`

```swift
func scheduleAttendeeNotification(forEvent event: Event,
```

### `cancelScheduledNotification(forEeventID:)`

```swift
func cancelScheduledNotification(forEeventID eventID: String)
```

### `removeDelieveredNotifcaion(forEventID:)`

```swift
func removeDelieveredNotifcaion(forEventID eventID: String)
```
