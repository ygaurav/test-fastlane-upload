**PROTOCOL**

# `BCGLoginViewControllerDelegate`

```swift
public protocol BCGLoginViewControllerDelegate: class
```

> Objects conforming to this protocol receives callbacks from login screen.
> Login screen requires object conforming to this protocol

## Methods
### `didTapTroubleLoginIn()`

```swift
func didTapTroubleLoginIn()
```

### `loginSuccess(user:)`

```swift
func loginSuccess(user: UserObject)
```

### `loginWillBegin(adhocUserCredentials:)`

```swift
func loginWillBegin(adhocUserCredentials: (username: String, password: String)?)
```

### `loginFailed(message:)`

```swift
func loginFailed(message: String)
```
