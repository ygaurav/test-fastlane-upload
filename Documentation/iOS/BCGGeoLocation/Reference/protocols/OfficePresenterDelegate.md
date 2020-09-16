**PROTOCOL**

# `OfficePresenterDelegate`

```swift
public protocol OfficePresenterDelegate: class
```

## Properties
### `loadingStatus`

```swift
var loadingStatus: OfficeViewController.LoadingStatus
```

## Methods
### `update(snapshot:configuration:withAnimations:)`

```swift
func update(snapshot: NSDiffableDataSourceSnapshot<IdentifiableSection, IdentifiableItem>, configuration: LocationConfiguration.Full, withAnimations: Bool)
```
