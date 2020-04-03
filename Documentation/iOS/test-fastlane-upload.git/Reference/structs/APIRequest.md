**STRUCT**

# `APIRequest`

```swift
public struct APIRequest
```

## Properties
### `method`

```swift
public var method: Method = .get
```

### `path`

```swift
public var path: String
```

### `type`

```swift
public var type: RequestType = .json
```

### `timeout`

```swift
public var timeout: TimeInterval = 60
```

### `authentication`

```swift
public var authentication: Bool = false
```

### `headers`

```swift
public var headers: [String: String] = [String: String]()
```

### `bodyParameters`

```swift
public var bodyParameters: [String: Any] = [String: Any]()
```

### `queryStringParameters`

```swift
public var queryStringParameters: [String: String] = [String: String]()
```

### `formDataParameters`

```swift
public var formDataParameters: [[String: Any]] = [[String: Any]]()
```

### `formDataContentType`

```swift
public var formDataContentType: String = "image/jpeg"
```

### `formDataFileType`

```swift
public var formDataFileType: String = "jpeg"
```

### `formDataFileName`

```swift
public var formDataFileName: String?
```

## Methods
### `init(path:)`

```swift
public init(path: String)
```
