**CLASS**

# `BCGLoginViewController`

```swift
public class BCGLoginViewController: UIViewController, LoadingIndicator
```

> View controller used to display a BCG login screen.
> It has username & password field.
>
> Create an instance of this ViewController using
> ````
> static func instantiate(session: UserSession, loginConfiguration: BCGLoginConfigurations, delegate: BCGLoginViewControllerDelegate)
> ````

## Properties
### `preferredStatusBarStyle`

```swift
public override var preferredStatusBarStyle: UIStatusBarStyle
```

## Methods
### `viewDidLoad()`

```swift
public override func viewDidLoad()
```

### `instantiate(loginConfiguration:biometricConfiguration:uiConfigurator:delegate:)`

```swift
public static func instantiate(loginConfiguration: BCGLoginConfigurations, biometricConfiguration: BiometricConfiguration, uiConfigurator: UIConfigurator?, delegate: BCGLoginViewControllerDelegate) -> UIViewController?
```

>  Method to create & return Login Screen object to display
>
> - Precondition: **loginConfiguration** parameter must be non-nil.
>  - parameters:
>      - loginConfiguration: Configuration which sets the API Endpoint & related keys to communicate with
>      - biometricConfiguration: Configuration containing properties which customises biometric authentication performed on Login screen
>      - uiConfigurator: Configuration for customising UI of login screen. Please check the options provided in UIConfiguration.
>      - delegate: Delegate which conforms to `BCGLoginViewControllerDelegate` which will receive various login screen callback events.

#### Parameters

| Name | Description |
| ---- | ----------- |
| loginConfiguration | Configuration which sets the API Endpoint & related keys to communicate with |
| biometricConfiguration | Configuration containing properties which customises biometric authentication performed on Login screen |
| uiConfigurator | Configuration for customising UI of login screen. Please check the options provided in UIConfiguration. |
| delegate | Delegate which conforms to `BCGLoginViewControllerDelegate` which will receive various login screen callback events. |

### `traitCollectionDidChange(_:)`

```swift
public override func traitCollectionDidChange(_ previousTraitCollection: UITraitCollection?)
```

### `viewWillAppear(_:)`

```swift
public override func viewWillAppear(_ animated: Bool)
```

### `viewWillDisappear(_:)`

```swift
public override func viewWillDisappear(_ animated: Bool)
```

### `viewDidAppear(_:)`

```swift
public override func viewDidAppear(_ animated: Bool)
```

### `viewDidDisappear(_:)`

```swift
public override func viewDidDisappear(_ animated: Bool)
```
