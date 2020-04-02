**STRUCT**

# `APIServiceConfiguration`

```swift
public struct APIServiceConfiguration: APIConfiguration
```

## Properties
### `baseURL`

```swift
public var baseURL: URL
```

### `appVersion`

```swift
public var appVersion: String
```

### `language`

```swift
public var language: String
```

### `apiKey`

```swift
public var apiKey: String
```

### `pinningConfigurationKeys`

```swift
public var pinningConfigurationKeys: [String]
```

### `sslPinningConfiguration`

```swift
public var sslPinningConfiguration: SSLPinningConfiguration?
```

### `apiVersion`

```swift
public var apiVersion: String = "1.0"
```

## Methods
### `init(configuration:)`

```swift
public init(configuration: APIConfiguration)
```

### `defaultHeaders()`

```swift
public func defaultHeaders() -> [String: String]
```

### `endpoint()`

```swift
public func endpoint() -> URL
```

### `endpoint(with:)`

```swift
public func endpoint(with path: String) -> URL
```
