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

### `showProfileError(_:)`

```swift
public func showProfileError(_ message: String)
```

### `showError(withTitle:message:)`

```swift
public func showError(withTitle title: String?, message: String)
```

### `instantiate(presenter:)`

```swift
public static func instantiate(presenter: ProfilePresenter?) -> Self
```
