**CLASS**

# `Router`

```swift
open class Router: ProfileRouter
```

## Properties
### `locationDisplayDelegate`

```swift
public var locationDisplayDelegate: ((OfficeLocationIdentifiable) -> UIViewController)?
```

### `profileDisplayDelegate`

```swift
public var profileDisplayDelegate: ((EmployeeIdentifiable) -> UIViewController)?
```

### `source`

```swift
public weak var source: UIViewController?
```

## Methods
### `init()`

```swift
public init()
```

### `showProfile(of:)`

```swift
open func showProfile(of employeeIdentifiable: EmployeeIdentifiable)
```

### `showOffice(of:)`

```swift
open func showOffice(of identifiableLocation: OfficeLocationIdentifiable)
```
