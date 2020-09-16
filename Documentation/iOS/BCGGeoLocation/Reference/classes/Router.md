**CLASS**

# `Router`

```swift
open class Router: OfficeRouter
```

## Properties
### `source`

```swift
weak public var source: UIViewController?
```

### `availabilityDisplayDelegate`

```swift
open var availabilityDisplayDelegate: ((OfficeLocation) -> UIViewController)?
```

### `associatesDisplayDelegate`

```swift
open var associatesDisplayDelegate: ((OfficeLocation) -> UIViewController)?
```

### `locationDisplayDelegate`

```swift
open var locationDisplayDelegate: ((OfficeLocation) -> UIViewController)?
```

## Methods
### `init()`

```swift
public init()
```

### `showDetail()`

```swift
public func showDetail()
```

### `showAvailbility(for:)`

```swift
public func showAvailbility(for location: OfficeLocation)
```

### `showAssociates(for:)`

```swift
public func showAssociates(for office: OfficeLocation)
```

### `showLocationOnMap(for:)`

```swift
public func showLocationOnMap(for office: OfficeLocation)
```
