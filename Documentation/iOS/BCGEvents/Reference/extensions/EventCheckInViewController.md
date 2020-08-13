**EXTENSION**

# `EventCheckInViewController`

## Methods
### `getEventsAttendanceScreen(service:eventID:attendeeID:callbackOnAttending:callbackOnSkipping:)`

```swift
public static func getEventsAttendanceScreen(service: EventsService,
                                             eventID: String,
                                             attendeeID: String,
                                             callbackOnAttending onAttending: (() -> Void)! = nil,
                                             callbackOnSkipping onSkipping:(() -> Void)! = nil
) -> UIViewController
```
