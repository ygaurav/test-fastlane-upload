**EXTENSION**

# `APIClient`

## Methods
### `execute(request:responseSerializer:completion:)`

```swift
public func execute<ResponseType>(request: APIRequest,
                                  responseSerializer: APIResponseSerializer<ResponseType>? = nil,
                                  completion: ((Result<ResponseType, Error>) -> Void)? = nil) -> Operation?
```
