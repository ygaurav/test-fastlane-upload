**EXTENSION**

# `UserSession`

## Properties
### `headers`

```swift
var headers: [String: String]
```

### `isLoggedIn`

```swift
var isLoggedIn: Bool
```

> Is true if user is logged in, false otherwise

### `email`

```swift
var email: String?
```

> User email if provided

### `hrID`

```swift
var hrID: String?
```

## Methods
### `logout(onSuccess:)`

```swift
func logout(onSuccess: (Bool) -> Void)
```

> Logs out user by clearing credentials.

### `stringValue(forKeychainKey:)`

```swift
func stringValue(forKeychainKey key: String) -> String?
```

> Fetch value stored in keychain for particular key

### `removeCredentials(forConfig:)`

```swift
func removeCredentials(forConfig config: BCGLoginConfigurations) -> Bool
```
