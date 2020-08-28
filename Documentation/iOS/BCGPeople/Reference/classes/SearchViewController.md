**CLASS**

# `SearchViewController`

```swift
public class SearchViewController: UIViewController, AppDefaultTheme, ApplyDefaultSearchBar, ScreenRefreshable
```

## Properties
### `dataSet`

```swift
public var dataSet: String = ""
```

### `searchIntent`

```swift
public var searchIntent: INIntent?
```

## Methods
### `instantiateViewController(enableSiri:searchService:imageIndexer:contactCacheManager:imageService:employeeDetailDelegate:)`

```swift
public static func instantiateViewController(enableSiri: Bool = false, searchService: SearchService, imageIndexer: SpotlightContactIndexer, contactCacheManager: ContactCacheManager, imageService: PictureService, employeeDetailDelegate: @escaping EmployeeDetailDelegate) -> SearchViewController
```

### `init(nibName:bundle:)`

```swift
public override init(nibName nibNameOrNil: String?, bundle nibBundleOrNil: Bundle?)
```

### `init(coder:)`

```swift
public required init?(coder: NSCoder)
```

### `viewDidLoad()`

```swift
override public func viewDidLoad()
```

### `viewWillLayoutSubviews()`

```swift
override public func viewWillLayoutSubviews()
```

### `viewWillAppear(_:)`

```swift
override public func viewWillAppear(_ animated: Bool)
```

### `viewWillDisappear(_:)`

```swift
override public func viewWillDisappear(_ animated: Bool)
```

### `reloadData(dataSet:)`

```swift
public func reloadData(dataSet : String)
```
