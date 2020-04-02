**PROTOCOL**

# `CredentialsService`

```swift
public protocol CredentialsService
```

## Methods
### `renew(refreshToken:completion:)`

```swift
@discardableResult func renew(refreshToken: String?, completion: @escaping(Result<AuthenticationCredentials, Error>) -> Void) -> Operation?
```

### `revoke(refreshToken:)`

```swift
func revoke(refreshToken: String?)
```
