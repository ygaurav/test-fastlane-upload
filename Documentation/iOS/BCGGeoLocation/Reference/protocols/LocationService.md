**PROTOCOL**

# `LocationService`

```swift
public protocol LocationService
```

## Methods
### `allLocations(completion:)`

```swift
@discardableResult func allLocations(completion: @escaping(Result<AllLocations, Error>) -> Void) -> BCGAPICore.Operation?
```

### `location(with:completion:)`

```swift
@discardableResult func location(with code: String, completion: @escaping(Result<OfficeLocationDetails, Error>) -> Void) -> BCGAPICore.Operation?
```
