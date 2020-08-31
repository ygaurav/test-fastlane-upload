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
public func events(for locationID: [String], after date: Date, completion: @escaping (Result<EventFilterResponse, Error>) -> ()) -> BCGAPICore.Operation?
```

### `add(event:completion:)`

```swift
public func add(event: Event, completion: @escaping(Result<CreateEventResult, Error>) -> Void) -> BCGAPICore.Operation?
```

### `requestSeatFor(eventID:attendeeInfo:completion:)`

```swift
public func requestSeatFor(eventID: String,
                           attendeeInfo: ReservationRequest,
                           completion: @escaping(Result<RequestSeatResult, Error>) -> Void) -> BCGAPICore.Operation?
```

### `removeAttendee(eventID:attendeeInfo:completion:)`

```swift
public func removeAttendee(eventID: String,
                           attendeeInfo: ReservationRequest,
                           completion: @escaping(Result<DeleteAttendeeResult, Error>) -> Void) -> BCGAPICore.Operation?
```

### `requestEventsReport(forLocation:start:end:completion:)`

```swift
public func requestEventsReport(forLocation locID: String, start: Date, end: Date, completion: @escaping (Result<Data, Error>) -> ()) -> BCGAPICore.Operation?
```

### `eventsBetween(start:end:locationID:completion:)`

```swift
@discardableResult public func eventsBetween(start: Date, end: Date, locationID: [String], completion: @escaping (Result<EventFilterResponse, Error>) -> ()) -> BCGAPICore.Operation?
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
public func event(forUserId userId: String, from: Date, completion: @escaping (Result<EventResults, Error>) -> ()) -> BCGAPICore.Operation?
```

### `update(_:completion:)`

```swift
public func update(_ event: Event, completion: @escaping (Result<UpdateEventResult, Error>) -> Void) -> BCGAPICore.Operation?
```

### `update(eventID:title:state:completion:)`

```swift
public func update(eventID: String, title: String, state: Event.State, completion: @escaping (Result<UpdateEventResult, Error>) -> Void) -> BCGAPICore.Operation?
```

### `categories(completion:)`

```swift
public func categories(completion: @escaping (Result<EventCategoryResult, Error>) -> Void) -> BCGAPICore.Operation?
```

### `userGroups(completion:)`

```swift
public func userGroups(completion: @escaping (Result<EventGroupsResult, Error>) -> Void) -> BCGAPICore.Operation?
```

### `approve(request:forEventID:withAttendees:completion:)`

```swift
public func approve(request: ReservationRequest, forEventID eventID: String, withAttendees: Bool, completion: @escaping (Result<ApproveAttendeeResult, Error>) -> Void) -> BCGAPICore.Operation?
```

### `delete(eventID:completion:)`

```swift
public func delete(eventID: String, completion: @escaping (Result<DeleteEventResponse, Error>) -> Void) -> BCGAPICore.Operation?
```

### `event(withId:withAttendees:completion:)`

```swift
public func event(withId id: String, withAttendees: Bool, completion: @escaping (Result<FetchEventResults, Error>) -> Void) -> BCGAPICore.Operation?
```

### `fetchAllPoolOffices(for:completion:)`

```swift
public func fetchAllPoolOffices(for pool: String, completion: @escaping(Result<PoolOfficeModel, Error>) -> Void ) -> BCGAPICore.Operation?
```

### `profileImage(for:completion:)`

```swift
@discardableResult public func profileImage(for hrid: String, completion: @escaping(Result<Data, Error>) -> Void) -> BCGAPICore.Operation?
```
