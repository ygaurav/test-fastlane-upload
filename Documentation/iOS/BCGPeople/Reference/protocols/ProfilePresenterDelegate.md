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

### `update(snapshot:withAnimations:)`

```swift
func update(snapshot: NSDiffableDataSourceSnapshot<IdentifiableSection, IdentifiableItem>, withAnimations: Bool)
```

### `setProfileStatus(_:)`

```swift
func setProfileStatus(_: ProfileViewController.ProfileStatus)
```

### `setupBarButtons(_:)`

```swift
func setupBarButtons(_: ProfileBarButtons)
```

### `showAlert(from:)`

```swift
func showAlert(from: ProfileViewController.AlertBuilder)
```

### `shareUrl(_:)`

```swift
func shareUrl(_: URL?)
```
