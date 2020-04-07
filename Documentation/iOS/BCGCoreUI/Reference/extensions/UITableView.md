**EXTENSION**

# `UITableView`

## Methods
### `register(cell:)`

```swift
func register<T: UITableViewCell>(cell cellType: T.Type) where T: Reusable
```

### `register(cell:)`

```swift
func register<T: UITableViewCell>(cell cellType: T.Type) where T: Reusable, T: HasNib
```

### `register(headerFooterView:)`

```swift
func register<T: UITableViewHeaderFooterView>(headerFooterView viewType: T.Type) where T: Reusable, T: HasNib
```

### `dequeueCell(for:)`

```swift
func dequeueCell<T: UITableViewCell>(for indexPath: IndexPath) -> T where T: Reusable
```

### `dequeueHeaderFooterView()`

```swift
func dequeueHeaderFooterView<T: UITableViewHeaderFooterView>() -> T where T: Reusable
```

### `addStretchyTableHeaderView(withModel:offset:headerDelegate:)`

```swift
public func addStretchyTableHeaderView(withModel model: StretchyTableHeaderViewModel,
                                         offset: CGFloat,
                                 headerDelegate: StretchyTableHeaderViewDelegate)
```

### `updateHeaderView()`

```swift
public func updateHeaderView()
```
