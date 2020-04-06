**CLASS**

# `UserSession`

```swift
public class UserSession
```

> UserSession object is a handle for certain session related properties & methods

## Properties
### `shouldValidateUserOnLaunch`

```swift
public var shouldValidateUserOnLaunch: Bool
```

### `isBiometricsOn`

```swift
public var isBiometricsOn: Bool
```

### `authenticationCredentials`

```swift
public var authenticationCredentials: AuthenticationCredentials?
```

## Methods
### `init(with:)`

```swift
public convenience init(with configuration: AuthenticationConfiguration)
```

> Initialize using configuration
> Hold a reference to his object to check state of user session
> - Parameters:
>     - configuration: Object used to configure session object. All values in it will be used to fetch keychain items & make service calls

#### Parameters

| Name | Description |
| ---- | ----------- |
| configuration | Object used to configure session object. All values in it will be used to fetch keychain items & make service calls |

### `refreshAccessToken(completion:)`

```swift
@discardableResult public func refreshAccessToken(completion: @escaping (AuthResult<AuthenticationCredentials?>) -> Void) -> BCGAPICore.Operation?
```
