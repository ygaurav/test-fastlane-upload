**CLASS**

# `BCGEventNotificationService`

```swift
public class BCGEventNotificationService: NSObject, NotificationServiceProvider
```

## Methods
### `scheduleAttendeeNotification(forEvent:attendeeID:attendeeName:)`

```swift
public func scheduleAttendeeNotification(forEvent event: Event,
                                         attendeeID id: String,
                                         attendeeName name: String)
```

### `cancelScheduledNotification(forEeventID:)`

```swift
public func cancelScheduledNotification(forEeventID eventID: String)
```

### `removeDelieveredNotifcaion(forEventID:)`

```swift
public func removeDelieveredNotifcaion(forEventID eventID: String)
```
