**CLASS**

# `URLSessionDataTaskOperation`

```swift
open class URLSessionDataTaskOperation: Operation, FetchOperation
```

## Methods
### `init(with:authentication:sslPinningConfiguration:)`

```swift
public required init(with request: URLRequest,
                     authentication: APIAuthentication?,
                     sslPinningConfiguration: PinningConfiguration?)
```

### `update(credentials:)`

```swift
public func update(credentials: APIAuthentication?)
```

### `execute()`

```swift
open override func execute()
```
