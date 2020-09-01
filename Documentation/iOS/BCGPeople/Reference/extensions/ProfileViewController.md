**EXTENSION**

# `ProfileViewController`

## Methods
### `createCollectionViewLayout()`

```swift
open func createCollectionViewLayout() -> UICollectionViewCompositionalLayout
```

### `setupBarButtons(_:)`

```swift
public func setupBarButtons(_ options: ProfileBarButtons)
```

### `update(snapshot:withAnimations:)`

```swift
public func update(snapshot: NSDiffableDataSourceSnapshot<IdentifiableSection, IdentifiableItem>, withAnimations: Bool = true)
```

### `copiedContactDetail(_:)`

```swift
public func copiedContactDetail(_ message: String)
```

### `setProfileStatus(_:)`

```swift
public func setProfileStatus(_ status: ProfileStatus)
```

### `shareUrl(_:)`

```swift
public func shareUrl(_ contactUrl: URL?)
```

### `showAlert(from:)`

```swift
public func showAlert(from builder: ProfileViewController.AlertBuilder)
```

### `instantiate(presenter:)`

```swift
public static func instantiate(presenter: ProfilePresenter?) -> Self
```
