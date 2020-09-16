**CLASS**

# `Presenter`

```swift
open class Presenter: OfficePresenter
```

## Properties
### `office`

```swift
public var office: OfficeLocation
```

### `configuration`

```swift
public var configuration: LocationConfiguration.Full
```

### `delegate`

```swift
public weak var delegate: OfficePresenterDelegate?
```

## Methods
### `init(office:configuration:router:service:gotoAvailability:)`

```swift
public init(office: OfficeLocation, configuration: LocationConfiguration.Full, router: OfficeRouter, service: LocationService, gotoAvailability: Bool = false)
```

### `update()`

```swift
open func update()
```

### `updateSnapshot(withSections:withAnimations:)`

```swift
public func updateSnapshot(withSections sections: [IdentifiableSection], withAnimations: Bool = true)
```

### `reload()`

```swift
open func reload()
```

### `updateItems()`

```swift
open func updateItems() -> [IdentifiableSection]
```

### `supplementaryViewProvider()`

```swift
open func supplementaryViewProvider() -> UICollectionViewDiffableDataSource<IdentifiableSection, IdentifiableItem>.SupplementaryViewProvider?
```

### `onTap(banner:)`

```swift
open func onTap(banner: OfficeActionBannerModel)
```

### `onCheckAvailability()`

```swift
public func onCheckAvailability()
```

### `showDetail(_:)`

```swift
public func showDetail(_ detail: OfficeDetailTypeAModel)
```

### `showDetail(_:)`

```swift
public func showDetail(_ detail: OfficeDetailTypeBModel)
```

### `showAddress()`

```swift
public func showAddress()
```
