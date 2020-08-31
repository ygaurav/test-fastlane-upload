**STRUCT**

# `AuthenticationCredentials`

```swift
public struct AuthenticationCredentials: Codable
```

## Properties
### `status`

```swift
public let status: AuthenticationResponseStatus
```

### `accessToken`

```swift
public let accessToken: String?
```

### `refreshToken`

```swift
public let refreshToken: String?
```

### `psID`

```swift
public let psID: String?
```

### `pollUri`

```swift
public let pollUri: String?
```

### `creationDate`

```swift
public let creationDate: Date
```

### `expirationDate`

```swift
public let expirationDate: Date
```

### `idToken`

```swift
public let idToken: String?
```

## Methods
### `init(accessToken:refreshToken:psID:pollUri:idToken:)`

```swift
public init(accessToken: String? = nil, refreshToken: String? = nil, psID: String? = nil, pollUri: String? = nil, idToken: String? = nil)
```
