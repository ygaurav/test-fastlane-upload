**EXTENSION**

# `SMPClient`

## Methods
### `allLocations(isCustom:completion:)`

```swift
@discardableResult public func allLocations(isCustom: Bool, completion: @escaping(Result<AllLocations, Error>) -> Void) -> BCGAPICore.Operation?
```

### `location(with:completion:)`

```swift
@discardableResult public func location(with code: String, completion: @escaping(Result<OfficeLocationDetails, Error>) -> Void) -> BCGAPICore.Operation?
```
