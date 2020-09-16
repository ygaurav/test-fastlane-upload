**CLASS**

# `OfficeViewController`

```swift
public class OfficeViewController: UIViewController, StretchyHeaderViewDelegate
```

## Properties
### `layout`

```swift
public var layout: UICollectionViewCompositionalLayout?
```

## Methods
### `viewDidLoad()`

```swift
public override func viewDidLoad()
```

### `viewWillAppear(_:)`

```swift
public override func viewWillAppear(_ animated: Bool)
```

### `viewWillDisappear(_:)`

```swift
public override func viewWillDisappear(_ animated: Bool)
```

### `backPressed()`

```swift
public func backPressed()
```

### `add(supplementaryViews:)`

```swift
public func add(supplementaryViews: [ConfigurableSupplementaryView.Type])
```

### `setLayout(_:)`

```swift
public func setLayout(_ layout: UICollectionViewCompositionalLayout)
```

### `sectionIdentifier(atIndex:)`

```swift
public func sectionIdentifier(atIndex index: Int) -> String?
```

### `add(cellDescriptors:)`

```swift
public func add(cellDescriptors: [CellConfigurator])
```
