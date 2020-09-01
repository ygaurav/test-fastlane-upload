**ENUM**

# `BiometricError`

```swift
public enum BiometricError: LocalizedError, Equatable
```

## Cases
### `biometricAuthUnavailable(_:_:)`

```swift
case biometricAuthUnavailable(LAError.Code, String)
```

### `authenticationFailed(_:_:)`

```swift
case authenticationFailed(LAError.Code, String)
```

### `canceled(_:_:)`

```swift
case canceled(LAError.Code, String)
```

### `other(_:_:)`

```swift
case other(LAError.Code, String)
```

### `unknown(_:)`

```swift
case unknown(String)
```

## Properties
### `localizedDescription`

```swift
public var localizedDescription: String
```

### `errorDescription`

```swift
public var errorDescription: String?
```

### `title`

```swift
public var title: String
```

### `message`

```swift
public var message: String
```

### `code`

```swift
public var code: LAError.Code
```
