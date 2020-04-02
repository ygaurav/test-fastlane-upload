**STRUCT**

# `APIResponse`

```swift
public struct APIResponse
```

## Properties
### `data`

```swift
public var data: Data?
```

### `error`

```swift
public var error: Error?
```

### `status`

```swift
public var status: Int = 0
```

### `headers`

```swift
public var headers: HTTPHeaders = HTTPHeaders()
```

## Methods
### `init(responseData:response:responseError:)`

```swift
public init(responseData: Data?, response: HTTPURLResponse?, responseError: Error?)
```
