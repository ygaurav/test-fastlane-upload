**CLASS**

# `APIRequestOperation`

```swift
public class APIRequestOperation<ResponseType>: GroupOperation
```

## Methods
### `init(request:configuration:responseSerializer:authentication:credentialsManager:completion:)`

```swift
public init?(request: APIRequest,
      configuration: APIServiceConfiguration,
      responseSerializer: APIResponseSerializer<ResponseType>,
      authentication: APIAuthentication? = nil,
      credentialsManager: AuthenticationCredentialsManager? = nil,
      completion: ((Result<ResponseType, Error>) -> Void)? = nil)
```
