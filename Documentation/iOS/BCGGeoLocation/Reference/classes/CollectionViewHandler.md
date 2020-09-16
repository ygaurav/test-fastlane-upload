**CLASS**

# `CollectionViewHandler`

```swift
public final class CollectionViewHandler: NSObject, UICollectionViewDelegate
```

## Methods
### `init(collectionView:headerView:cellDescriptors:)`

```swift
public init(collectionView: UICollectionView, headerView: StretchyCollectionViewHeader? = nil, cellDescriptors: [CellConfigurator])
```

### `sectionIdentifier(atIndex:)`

```swift
public func sectionIdentifier(atIndex index: Int) -> String?
```

### `setSupplementaryViewProvider(_:)`

```swift
public func setSupplementaryViewProvider(_ provider: UICollectionViewDiffableDataSource<IdentifiableSection, IdentifiableItem>.SupplementaryViewProvider?)
```

### `collectionView(_:didSelectItemAt:)`

```swift
public func collectionView(_ collectionView: UICollectionView, didSelectItemAt indexPath: IndexPath)
```

### `scrollViewDidScroll(_:)`

```swift
public func scrollViewDidScroll(_ scrollView: UIScrollView)
```

### `apply(_:withAnimations:)`

```swift
public func apply(_ snapshot: NSDiffableDataSourceSnapshot<IdentifiableSection, IdentifiableItem>, withAnimations: Bool = true)
```
