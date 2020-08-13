**CLASS**

# `CollectionViewHandler`

```swift
public final class CollectionViewHandler: NSObject, UICollectionViewDelegate
```

## Methods
### `init(collectionView:enableHeader:headerColor:cellDescriptors:)`

```swift
public init(collectionView: UICollectionView, enableHeader: Bool = false, headerColor: UIColor = UIColor(named: "NavBarColor")!, cellDescriptors: [CellConfigurator])
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

### `apply(_:)`

```swift
public func apply(_ snapshot: NSDiffableDataSourceSnapshot<IdentifiableSection, IdentifiableItem>)
```

### `updateSections(_:)`

```swift
public func updateSections(_ sections: [IdentifiableSection])
```
