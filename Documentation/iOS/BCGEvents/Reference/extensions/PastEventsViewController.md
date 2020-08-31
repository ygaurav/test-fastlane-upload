**EXTENSION**

# `PastEventsViewController`

## Methods
### `update(with:)`

```swift
public func update(with section: [Section])
```

### `collectionView(_:numberOfItemsInSection:)`

```swift
public func collectionView(_ collectionView: UICollectionView, numberOfItemsInSection section: Int) -> Int
```

### `collectionView(_:cellForItemAt:)`

```swift
public func collectionView(_ collectionView: UICollectionView, cellForItemAt indexPath: IndexPath) -> UICollectionViewCell
```

### `collectionView(_:didSelectItemAt:)`

```swift
public func collectionView(_ collectionView: UICollectionView, didSelectItemAt indexPath: IndexPath)
```

### `collectionView(_:layout:sizeForItemAt:)`

```swift
public func collectionView(_ collectionView: UICollectionView, layout collectionViewLayout: UICollectionViewLayout, sizeForItemAt indexPath: IndexPath) -> CGSize
```

### `collectionView(_:layout:insetForSectionAt:)`

```swift
public func collectionView(_ collectionView: UICollectionView, layout collectionViewLayout: UICollectionViewLayout, insetForSectionAt section: Int) -> UIEdgeInsets
```
