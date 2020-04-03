**ENUM**

# `APIServiceError`

```swift
public enum APIServiceError: ReportableError
```

## Cases
### `network`

```swift
case network
```

### `badRequest`

```swift
case badRequest
```

### `service`

```swift
case service
```

### `forbidden`

```swift
case forbidden
```

### `noDataToParse`

```swift
case noDataToParse
```

### `jsonSerialization`

```swift
case jsonSerialization
```

### `responseSerialization`

```swift
case responseSerialization
```

### `parseKeyNotFound(key:context:)`

```swift
case parseKeyNotFound(key: String, context: [String: Any])
```

### `parseTypeMismatch(key:context:)`

```swift
case parseTypeMismatch(key: String, context: [String: Any])
```

### `parseInvalidDateFormat(key:context:)`

```swift
case parseInvalidDateFormat(key: String, context: [String: Any])
```

### `parseNoItemsFound(key:context:)`

```swift
case parseNoItemsFound(key: String, context: [String: Any])
```

### `parseNoElementsFound(context:)`

```swift
case parseNoElementsFound(context: [[String: Any]])
```

### `noAuth`

```swift
case noAuth
```

### `wrongCredentials`

```swift
case wrongCredentials
```

### `passwordExpired`

```swift
case passwordExpired
```

### `accessDenied`

```swift
case accessDenied
```

### `mfaNotSetup`

```swift
case mfaNotSetup
```

### `unknown(message:)`

```swift
case unknown(message: String?)
```

## Properties
### `errorName`

```swift
public var errorName: String
```

## Methods
### `errorCode()`

```swift
public func errorCode() -> Int
```
