**CLASS**

# `BiometricAuthenticator`

```swift
public class BiometricAuthenticator: NSObject
```

> Object contains method relating to Biometric authentication

## Properties
### `availableBiometricTypeTitle`

```swift
public var availableBiometricTypeTitle: String?
```

> Provides name of the biometric authentication type available on device

### `deviceHasPasscode`

```swift
public var deviceHasPasscode: Bool
```

> Method indicates if device has passcode setup
> You may want to display some message to user to atleast enable setup passcode for authentication.
> This method is used for displaying a message on login screen when user has not setup any passcode

## Methods
### `init(_:)`

```swift
public init(_ context: LAContext = LAContext())
```

> Initializer

### `canAuthenticateDeviceOwner(withPolicy:)`

```swift
public func canAuthenticateDeviceOwner(withPolicy policy: LAPolicy = .deviceOwnerAuthenticationWithBiometrics) -> Result<Void, BiometricError>
```

> Method returns a Result object with corresponding values.
> - parameters:
>     - withPolicy: LAPolicy. Please refer to documentation to understand its functionality. Defaults to `.deviceOwnerAuthenticationWithBiometrics`

#### Parameters

| Name | Description |
| ---- | ----------- |
| withPolicy | LAPolicy. Please refer to documentation to understand its functionality. Defaults to `.deviceOwnerAuthenticationWithBiometrics` |

### `authenticateDeviceOwner(forReason:withPolicy:_:)`

```swift
public func authenticateDeviceOwner(forReason reason: String, withPolicy policy: LAPolicy, _ completion: @escaping (Result<Void, BiometricError>) -> Void)
```

> Method prompts user to authenticate using biometric method.
>
>  This method first checks if authentication with biometrics (with passed policy) can proceed.
>  ```
>  func canAuthenticateDeviceOwner(withPolicy: LAPolicy)
>  ```
>  If that succeeds, method proceeds to evaluate biometric authentication (with passed policy)
>  - parameters:
>      - reason: Localized string of message to be shown when presenting with Biometric Authentication challenge
>      - policy: LAPolicy against which to evaluate & perform authentication. Please refer to Apple documentation for LAPolicy to understand.
>      - completion: Block will be called with ```Result<Void, BiometricError>```

#### Parameters

| Name | Description |
| ---- | ----------- |
| reason | Localized string of message to be shown when presenting with Biometric Authentication challenge |
| policy | LAPolicy against which to evaluate & perform authentication. Please refer to Apple documentation for LAPolicy to understand. |
| completion | Block will be called with `Result<Void, BiometricError>` |