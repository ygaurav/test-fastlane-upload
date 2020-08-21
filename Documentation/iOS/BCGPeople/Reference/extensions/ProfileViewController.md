**EXTENSION**

# `ProfileViewController`

## Methods
### `createCollectionViewLayout()`

```swift
open func createCollectionViewLayout() -> UICollectionViewCompositionalLayout
```

### `updateFavoriteStatus(_:)`

```swift
public func updateFavoriteStatus(_ status: Bool)
```

### `setupBarButtons(_:)`

```swift
public func setupBarButtons(_ options: ProfileBarButtons)
```

### `update(snapshot:)`

```swift
public func update(snapshot: NSDiffableDataSourceSnapshot<IdentifiableSection, IdentifiableItem>)
```

### `copiedContactDetail(_:)`

```swift
public func copiedContactDetail(_ message: String)
```

### `updateSections(_:)`

```swift
public func updateSections(_ sections: [IdentifiableSection])
```

### `setProfileStatus(_:)`

```swift
public func setProfileStatus(_ status: ProfileStatus)
```

### `showAlert(from:)`

```swift
public func showAlert(from builder: ProfileViewController.AlertBuilder)
```

### `instantiate(presenter:)`

```swift
public static func instantiate(presenter: ProfilePresenter?) -> Self
```
