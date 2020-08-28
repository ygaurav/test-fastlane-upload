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

### `fetchEvents(locationID:startDate:handler:)`

```swift
public func fetchEvents(locationID: String, startDate: Date, handler: @escaping ([Event], String?) -> Void)
```
