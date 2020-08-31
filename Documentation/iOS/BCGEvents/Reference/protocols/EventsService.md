**PROTOCOL**

# `EventsService`

```swift
public protocol EventsService
```

## Methods
### `events(for:after:completion:)`

```swift
@discardableResult func events(for locationID: [String], after date: Date, completion: @escaping (Result<EventFilterResponse, Error>) -> ()) -> BCGAPICore.Operation?
```

### `fetchAllPoolOffices(for:completion:)`

```swift
@discardableResult func fetchAllPoolOffices(for pool: String, completion: @escaping(Result<PoolOfficeModel, Error>) -> Void ) -> BCGAPICore.Operation?
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

### `requestEventsReport(forLocation:start:end:completion:)`

```swift
@discardableResult func requestEventsReport(forLocation locID: String, start: Date, end: Date, completion: @escaping (Result<Data, Error>) -> ()) -> BCGAPICore.Operation?
```

### `eventsBetween(start:end:locationID:completion:)`

```swift
@discardableResult func eventsBetween(start: Date, end: Date, locationID: [String], completion: @escaping (Result<EventFilterResponse, Error>) -> ()) -> BCGAPICore.Operation?
```

### `updateAttendeePresence(forEvent:attendeeID:fieldsToUpdate:callback:)`

```swift
@discardableResult func updateAttendeePresence(forEvent eventID: String,
```

### `event(forUserId:from:completion:)`

```swift
@discardableResult func event(forUserId: String, from: Date, completion: @escaping (Result<EventResults, Error>) -> ()) -> BCGAPICore.Operation?
```

### `update(_:completion:)`

```swift
@discardableResult func update(_: Event, completion: @escaping (Result<UpdateEventResult, Error>) -> Void) -> BCGAPICore.Operation?
```

### `update(eventID:title:state:completion:)`

```swift
@discardableResult func update(eventID: String, title: String, state: Event.State, completion: @escaping (Result<UpdateEventResult, Error>) -> Void) -> BCGAPICore.Operation?
```

### `categories(completion:)`

```swift
@discardableResult func categories(completion: @escaping (Result<EventCategoryResult, Error>) -> Void) -> BCGAPICore.Operation?
```

### `userGroups(completion:)`

```swift
@discardableResult func userGroups(completion: @escaping (Result<EventGroupsResult, Error>) -> Void) -> BCGAPICore.Operation?
```

### `approve(request:forEventID:withAttendees:completion:)`

```swift
@discardableResult func approve(request: ReservationRequest, forEventID: String, withAttendees: Bool, completion: @escaping (Result<ApproveAttendeeResult, Error>) -> Void) -> BCGAPICore.Operation?
```

### `delete(eventID:completion:)`

```swift
@discardableResult func delete(eventID: String, completion: @escaping (Result<DeleteEventResponse, Error>) -> Void) -> BCGAPICore.Operation?
```

### `event(withId:withAttendees:completion:)`

```swift
@discardableResult func event(withId: String, withAttendees: Bool, completion: @escaping (Result<FetchEventResults, Error>) -> Void) -> BCGAPICore.Operation?
```
