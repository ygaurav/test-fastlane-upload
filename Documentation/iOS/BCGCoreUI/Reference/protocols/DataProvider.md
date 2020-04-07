**PROTOCOL**

# `DataProvider`

```swift
public protocol DataProvider
```

## Methods
### `section(at:)`

```swift
func section(at index: Int) -> SectionType
```

### `row(at:)`

```swift
func row(at indexPath: IndexPath) -> RowType
```

### `numberOfSections()`

```swift
func numberOfSections() -> Int
```

### `numberOfRows(in:)`

```swift
func numberOfRows(in section: Int) -> Int
```
