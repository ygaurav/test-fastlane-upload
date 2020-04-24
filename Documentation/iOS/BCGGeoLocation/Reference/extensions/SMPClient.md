**EXTENSION**

# `SMPClient`

## Methods
### `allLocations(completion:)`

```swift
@discardableResult public func allLocations(completion: @escaping(Result<AllLocations, Error>) -> Void) -> BCGAPICore.Operation?
```

### `location(with:completion:)`

```swift
@discardableResult public func location(with code: String, completion: @escaping(Result<OfficeLocationDetails, Error>) -> Void) -> BCGAPICore.Operation?
```
