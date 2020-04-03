**CLASS**

# `APIResponseSerializer`

```swift
open class APIResponseSerializer<ResponseType>
```

## Methods
### `init()`

```swift
public init()
```

### `parse(response:)`

```swift
open func parse(response: APIResponse) -> Result<ResponseType, Error>
```

### `extractError(from:)`

```swift
open func extractError(from response: APIResponse) -> Error?
```

### `parse(responseData:)`

```swift
open func parse(responseData: Data) throws -> ResponseType
```
