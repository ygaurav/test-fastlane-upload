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

### `setProfileStatus(_:)`

```swift
func setProfileStatus(_: ProfileViewController.ProfileStatus)
```

### `setupBarButtons(_:)`

```swift
func setupBarButtons(_: ProfileBarButtons)
```

### `updateFavoriteStatus(_:)`

```swift
func updateFavoriteStatus(_: Bool)
```

### `showAlert(from:)`

```swift
func showAlert(from: ProfileViewController.AlertBuilder)
```
