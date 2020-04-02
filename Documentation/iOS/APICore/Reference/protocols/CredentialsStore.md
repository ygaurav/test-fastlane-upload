**PROTOCOL**

# `CredentialsStore`

```swift
public protocol CredentialsStore
```

## Properties
### `credentials`

```swift
var credentials: AuthenticationCredentials?
```

### `isBiometricsSetup`

```swift
var isBiometricsSetup: Bool
```

### `email`

```swift
var email: String?
```

## Methods
### `save(credentials:)`

```swift
@discardableResult func save(credentials: AuthenticationCredentials) -> Bool
```

### `save(email:)`

```swift
@discardableResult func save(email: String) -> Bool
```

### `save(biometrics:)`

```swift
@discardableResult func save(biometrics: Bool) -> Bool
```

### `save(username:)`

```swift
@discardableResult func save(username: String) -> Bool
```

### `save(password:)`

```swift
@discardableResult func save(password: String) -> Bool
```

### `clear()`

```swift
func clear()
```
