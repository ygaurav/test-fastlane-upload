**CLASS**

# `APIFormDataRequestSerializer`

```swift
open class APIFormDataRequestSerializer: APIRequestSerializer
```

## Methods
### `requestHttpBody(request:)`

```swift
open func requestHttpBody(request: APIRequest) throws -> Data?
```

### `generateBoundary()`

```swift
public func generateBoundary() -> String
```

### `requestHeaders()`

```swift
open func requestHeaders() -> [String: String]
```
