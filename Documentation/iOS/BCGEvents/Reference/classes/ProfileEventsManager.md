**CLASS**

# `ProfileEventsManager`

```swift
public class ProfileEventsManager: ProfileEventHandler
```

## Methods
### `init(service:)`

```swift
public init(service: GenericService)
```

### `fetchEmployeeEvents(for:loggedInUserId:timeZoneID:callBackHandler:)`

```swift
public func fetchEmployeeEvents(for id: String,
                                loggedInUserId: String,
                                timeZoneID: String,
                                callBackHandler: @escaping ([Event], String?) -> Void)
```

### `fetchEvents(locationID:startDate:handler:)`

```swift
public func fetchEvents(locationID: String,
                        startDate: Date,
                        handler: @escaping ([Event], String?) -> Void)
```
