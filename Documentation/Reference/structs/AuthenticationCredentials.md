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

## Methods
### `init(accessToken:refreshToken:psID:pollUri:)`

```swift
public init(accessToken: String? = nil, refreshToken: String? = nil, psID: String? = nil, pollUri: String? = nil)
```
