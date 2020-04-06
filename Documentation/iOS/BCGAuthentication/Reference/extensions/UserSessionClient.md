**EXTENSION**

# `UserSessionClient`

## Methods
### `renew(refreshToken:completion:)`

```swift
public func renew(refreshToken: String?, completion: @escaping (Result<AuthenticationCredentials, Error>) -> Void) -> BCGAPICore.Operation?
```

### `revoke(refreshToken:)`

```swift
public func revoke(refreshToken: String?)
```
