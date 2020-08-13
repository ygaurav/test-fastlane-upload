**EXTENSION**

# `SMPClient`

## Methods
### `fetch(path:requestFields:completion:)`

```swift
@discardableResult public func fetch<T: ExpressibleByJSONDictionary>(path: String,
                                                            requestFields: String,
                                                               completion: @escaping(Result<T, Error>) -> Void) -> BCGAPICore.Operation?
```

### `events(for:after:completion:)`

```swift
public func events(for locationID: String, after timeInterval: String, completion: @escaping(Result<EventFilterResults, Error>) -> Void) -> BCGAPICore.Operation?
```

### `add(event:completion:)`

```swift
public func add(event: Event, completion: @escaping(Result<CreateEventResult, Error>) -> Void) -> BCGAPICore.Operation?
```

### `requestSeatFor(eventID:attendeeInfo:completion:)`

```swift
public func requestSeatFor(eventID: String,
                           attendeeInfo: AttendeesInfo,
                           completion: @escaping(Result<RequestSeatResult, Error>) -> Void) -> BCGAPICore.Operation?
```

### `removeAttendee(eventID:attendeeInfo:completion:)`

```swift
public func removeAttendee(eventID: String,
                           attendeeInfo: AttendeesInfo,
                           completion: @escaping(Result<DeleteAttendeeResult, Error>) -> Void) -> BCGAPICore.Operation?
```

### `requestEventsReport(forLocation:startTimeInterval:endTimeInterval:completion:)`

```swift
public func requestEventsReport(forLocation locID: String,
                                startTimeInterval: TimeInterval,
                                endTimeInterval: TimeInterval,
                                completion: @escaping (Result<Data, Error>) -> Void) -> BCGAPICore.Operation?
```

### `eventsBetween(startTimeInterval:endTimeInterval:locationID:completion:)`

```swift
public func eventsBetween(startTimeInterval: String,
                          endTimeInterval: String,
                          locationID: String,
                          completion: @escaping(Result<EventFilterResults, Error>) -> Void) -> BCGAPICore.Operation?
```

### `updateAttendeePresence(forEvent:attendeeID:fieldsToUpdate:callback:)`

```swift
public func updateAttendeePresence(forEvent eventID: String,
                                   attendeeID: String,
                                   fieldsToUpdate: String,
                                   callback: @escaping(Result<UpdateAttendeeInfoResult, Error>) -> Void) -> BCGAPICore.Operation?
```

> <#Description#>
> - Parameters:
>   - eventID: <#eventID description#>
>   - attendeeID: <#attendeeID description#>
>   - isAttending: <#isAttending description#>
>   - callback: <#callback description#>
> - Returns: <#description#>

#### Parameters

| Name | Description |
| ---- | ----------- |
| eventID | <#eventID description#> |
| attendeeID | <#attendeeID description#> |
| isAttending | <#isAttending description#> |
| callback | <#callback description#> |

### `event(forUserId:from:completion:)`

```swift
public func event(forUserId userId: String, from: TimeInterval, completion: @escaping(Result<EventResults, Error>) -> Void) -> BCGAPICore.Operation?
```

### `profileImage(for:completion:)`

```swift
@discardableResult public func profileImage(for hrid: String, completion: @escaping(Result<Data, Error>) -> Void) -> BCGAPICore.Operation?
```
