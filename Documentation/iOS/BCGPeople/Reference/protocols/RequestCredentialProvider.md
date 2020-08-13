**PROTOCOL**

# `RequestCredentialProvider`

```swift
public protocol RequestCredentialProvider: class
```

## Properties
### `headers`

```swift
var headers: [String: String]
```

## Methods
### `createAuthenticatedRequest(url:)`

```swift
func createAuthenticatedRequest(url: URL) -> URLRequest
```
