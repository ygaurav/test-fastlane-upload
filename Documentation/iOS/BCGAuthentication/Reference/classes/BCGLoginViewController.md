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

## Methods
### `viewDidLoad()`

```swift
public override func viewDidLoad()
```

### `instantiate(loginConfiguration:uiConfigurator:delegate:)`

```swift
public static func instantiate(loginConfiguration: BCGLoginConfigurations, uiConfigurator: UIConfigurator?, delegate: BCGLoginViewControllerDelegate) -> UIViewController?
```

>  Method to create & return Login Screen object to display
>
> - Precondition: **loginConfiguration** parameter must be non-nil.
> - Important: **session** parameter must be non-nil for login facility to work

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
