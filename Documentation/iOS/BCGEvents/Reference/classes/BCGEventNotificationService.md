**CLASS**

# `BCGEventNotificationService`

```swift
public class BCGEventNotificationService: NSObject, NotificationServiceProvider
```

## Methods
### `scheduleAttendeeNotifications(forEvent:attendeeID:attendeeName:recurringFrequency:)`

```swift
public func scheduleAttendeeNotifications(forEvent event: Event,
                                          attendeeID id: String,
                                          attendeeName name: String,
                                          recurringFrequency: NotificationRecurrenceFrequency = .default)
```

### `removeNotifications(forEevent:eventID:)`

```swift
public func removeNotifications(forEevent event: Event! = nil, eventID id: String! = nil)
```

> This implementation might change if removing notifications for past events (on a day after event day)
> To achieve same, we might consider adding event start date in userInfo which can then be used to
