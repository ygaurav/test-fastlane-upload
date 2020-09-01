**CLASS**

# `ProfileViewController`

```swift
public class ProfileViewController: UIViewController
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

### `viewDidAppear(_:)`

```swift
public override func viewDidAppear(_ animated: Bool)
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
