**PROTOCOL**

# `OfficePresenter`

```swift
public protocol OfficePresenter: ActionBannerDelegate, OfficeDetailTypeADelegate, OfficeDetailTypeBDelegate, OfficeAddressCellDelegate, OfficeHeaderDataSource
```

## Methods
### `update()`

```swift
func update()
```

### `reload()`

```swift
func reload()
```

### `supplementaryViewProvider()`

```swift
func supplementaryViewProvider() -> UICollectionViewDiffableDataSource<IdentifiableSection, IdentifiableItem>.SupplementaryViewProvider?
```
