**PROTOCOL**

# `APIClient`

```swift
public protocol APIClient
```

## Properties
### `operationQueue`

```swift
var operationQueue: OperationQueue
```

### `configuration`

```swift
var configuration: APIServiceConfiguration
```

### `credentialsManager`

```swift
var credentialsManager: AuthenticationCredentialsManager?
```

## Methods
### `execute(request:responseSerializer:completion:)`

```swift
func execute<ResponseType>(request: APIRequest,
```
