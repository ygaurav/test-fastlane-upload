**EXTENSION**

# `EventsViewController`

## Methods
### `showError(message:)`

```swift
public func showError(message: String)
```

### `update(with:)`

```swift
public func update(with section: [Section])
```

### `showLoadingSpinner(text:)`

```swift
public func showLoadingSpinner(text: String)
```

### `hideLoadingSpinner()`

```swift
public func hideLoadingSpinner()
```

### `instantiate(configurationData:locationName:services:officeConfiguration:employeeDetailDisplayDelegate:)`

```swift
public static func instantiate(configurationData: EventsConfigurationsData, locationName: String, services: Services, officeConfiguration: OfficeLocation.Configuration, employeeDetailDisplayDelegate : @escaping EmployeeDetailDisplayDelegate) -> Self
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
