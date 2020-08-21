**CLASS**

# `Presenter`

```swift
open class Presenter: ProfilePresenter
```

## Properties
### `delegate`

```swift
public weak var delegate: ProfilePresenterDelegate?
```

### `spotlightIndexer`

```swift
public let spotlightIndexer: EmployeeImageIndexer
```

### `router`

```swift
public let router: ProfileRouter
```

### `pictureService`

```swift
public let pictureService: PictureService
```

### `employee`

```swift
public var employee: Employee
```

### `profileConfig`

```swift
public var profileConfig: ProfileConfiguration
```

## Methods
### `init(employee:profileConfig:router:service:pictureService:spotlightIndexer:favoritesDelegate:)`

```swift
public init(employee: Employee, profileConfig: ProfileConfiguration, router: ProfileRouter, service: EmployeeDetailsService, pictureService: PictureService, spotlightIndexer: EmployeeImageIndexer, favoritesDelegate: FavouritesDelegate? = nil)
```

### `fetchProfile()`

```swift
public func fetchProfile()
```

### `generateEmployeeContact()`

```swift
public func generateEmployeeContact() -> URL?
```

### `favoriteTapped()`

```swift
public func favoriteTapped()
```

### `reloadProfileView()`

```swift
public func reloadProfileView()
```

### `supplementaryViewProvider()`

```swift
open func supplementaryViewProvider() -> UICollectionViewDiffableDataSource<IdentifiableSection, IdentifiableItem>.SupplementaryViewProvider?
```

### `updateItems()`

```swift
open func updateItems() -> [IdentifiableSection]
```

### `showAlert(from:)`

```swift
public func showAlert(from builder: AlertBuilder)
```
