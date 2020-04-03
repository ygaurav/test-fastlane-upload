**PROTOCOL**

# `AuthenticationCredentialsManager`

```swift
public protocol AuthenticationCredentialsManager
```

## Properties
### `authentication`

```swift
var authentication: APIAuthentication?
```

## Methods
### `credentials(_:)`

```swift
func credentials(_ completion: @escaping (AuthenticationCredentials?) -> Void)
```

### `save(credentials:)`

```swift
func save(credentials: AuthenticationCredentials) -> Bool
```

### `clear()`

```swift
func clear()
```
