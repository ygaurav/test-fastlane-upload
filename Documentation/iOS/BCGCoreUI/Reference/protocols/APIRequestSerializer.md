**PROTOCOL**

# `APIRequestSerializer`

```swift
public protocol APIRequestSerializer
```

## Methods
### `url(for:using:)`

```swift
func url(for request: APIRequest, using configuration: APIServiceConfiguration) throws -> URL
```

### `requestHttpBody(request:)`

```swift
func requestHttpBody(request: APIRequest) throws -> Data?
```

### `requestHeaders()`

```swift
func requestHeaders() -> [String: String]
```
