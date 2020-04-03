**CLASS**

# `UserCredentialsManager`

```swift
public class UserCredentialsManager: AuthenticationCredentialsManager
```

## Properties
### `credentialsStorage`

```swift
public let credentialsStorage: CredentialsStore
```

### `credentialsService`

```swift
public let credentialsService: CredentialsService?
```

### `authentication`

```swift
public var authentication: APIAuthentication?
```

## Methods
### `init(storage:service:)`

```swift
public init(storage: CredentialsStore, service: CredentialsService? = nil)
```

### `credentials(_:)`

```swift
public func credentials(_ completion: @escaping (AuthenticationCredentials?) -> Void)
```

### `save(credentials:)`

```swift
public func save(credentials: AuthenticationCredentials) -> Bool
```

### `clear()`

```swift
public func clear()
```
