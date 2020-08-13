**PROTOCOL**

# `EventsService`

```swift
public protocol EventsService
```

## Methods
### `events(for:after:completion:)`

```swift
@discardableResult func events(for locationID: String, after timeInterval: String, completion: @escaping(Result<EventFilterResults, Error>) -> Void) -> BCGAPICore.Operation?
```

### `add(event:completion:)`

```swift
@discardableResult func add(event: Event, completion: @escaping(Result<CreateEventResult, Error>) -> Void) -> BCGAPICore.Operation?
```

### `requestSeatFor(eventID:attendeeInfo:completion:)`

```swift
@discardableResult func requestSeatFor(eventID: String,
```

### `removeAttendee(eventID:attendeeInfo:completion:)`

```swift
@discardableResult  func removeAttendee(eventID: String,
```

### `requestEventsReport(forLocation:startTimeInterval:endTimeInterval:completion:)`

```swift
@discardableResult func requestEventsReport(forLocation locID: String,
```

### `eventsBetween(startTimeInterval:endTimeInterval:locationID:completion:)`

```swift
@discardableResult func eventsBetween(startTimeInterval: String,
```

### `updateAttendeePresence(forEvent:attendeeID:isAttending:callback:)`

```swift
@discardableResult func updateAttendeePresence(forEvent eventID: String,
```
