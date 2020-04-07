**CLASS**

# `CellProvider`

```swift
public class CellProvider: NSObject, DataProvider
```

## Properties
### `sections`

```swift
public var sections: [SectionType] = []
```

## Methods
### `init(with:cellDescriptors:sectionDescriptors:emptyTableDescriptor:scrollDescriptor:)`

```swift
public init(with tableView: UITableView, cellDescriptors: [CellDescriptorType], sectionDescriptors: [SectionDescriptorType] = [], emptyTableDescriptor: EmptyTableDescriptorType? = nil, scrollDescriptor: ScrollDescriptorType? = nil)
```

### `section(at:)`

```swift
public func section(at index: Int) -> SectionType
```

### `row(at:)`

```swift
public func row(at indexPath: IndexPath) -> RowType
```

### `numberOfSections()`

```swift
public func numberOfSections() -> Int
```

### `numberOfRows(in:)`

```swift
public func numberOfRows(in section: Int) -> Int
```

### `sectionDescriptor(at:)`

```swift
public func sectionDescriptor(at index: Int) -> SectionDescriptorType?
```

### `cellDescriptor(at:)`

```swift
public func cellDescriptor(at indexPath: IndexPath) -> CellDescriptorType
```

### `reloadData()`

```swift
public func reloadData()
```
