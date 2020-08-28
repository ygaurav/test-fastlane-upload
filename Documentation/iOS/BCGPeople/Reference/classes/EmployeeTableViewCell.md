**CLASS**

# `EmployeeTableViewCell`

```swift
public class EmployeeTableViewCell: UITableViewCell
```

## Methods
### `awakeFromNib()`

```swift
public override func awakeFromNib()
```

### `setUp(employee:pictureService:imageIndexer:)`

```swift
public func setUp(employee: EmployeeModel, pictureService: PictureService, imageIndexer: SpotlightContactIndexer)
```

### `getCell(inTableView:for:)`

```swift
public static func getCell<T>(inTableView tableView: UITableView, for indexPath: IndexPath) -> T?
```

### `register(tableView:)`

```swift
public static func register(tableView: UITableView)
```
