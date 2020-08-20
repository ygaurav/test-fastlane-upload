**PROTOCOL**

# `ProfilePresenterDelegate`

```swift
public protocol ProfilePresenterDelegate: class
```

## Methods
### `copiedContactDetail(_:)`

```swift
func copiedContactDetail(_: String)
```

### `update(snapshot:)`

```swift
func update(snapshot: NSDiffableDataSourceSnapshot<IdentifiableSection, IdentifiableItem>)
```

### `updateSections(_:)`

```swift
func updateSections(_: [IdentifiableSection])
```

### `setupBarButtons(_:)`

```swift
func setupBarButtons(_: ProfileBarButtons)
```

### `updateFavoriteStatus(_:)`

```swift
func updateFavoriteStatus(_: Bool)
```

### `showProfileError()`

```swift
func showProfileError()
```

### `showAlert(from:)`

```swift
func showAlert(from: ProfileViewController.AlertBuilder)
```
