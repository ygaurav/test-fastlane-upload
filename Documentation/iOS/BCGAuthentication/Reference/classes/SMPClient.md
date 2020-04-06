**CLASS**

# `SMPClient`

```swift
public class SMPClient: APIClient
```

## Properties
### `operationQueue`

```swift
public private(set) var operationQueue: OperationQueue = APIOperationQueue()
```

### `configuration`

```swift
public private(set) var configuration: APIServiceConfiguration
```

### `credentialsManager`

```swift
public private(set) var credentialsManager: AuthenticationCredentialsManager?
```

## Methods
### `client(for:)`

```swift
public static func client(for configuration: AuthenticationConfiguration) -> SMPClient
```

### `init(configuration:credentialsManager:)`

```swift
public required init(configuration: APIConfiguration, credentialsManager: AuthenticationCredentialsManager?)
```
