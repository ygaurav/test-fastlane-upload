**CLASS**

# `Section`

```swift
open class Section: SectionType
```

## Properties
### `identifier`

```swift
public let identifier: String
```

### `content`

```swift
public let content: Any?
```

### `rows`

```swift
public internal(set) var rows: [RowType] = []
```

### `numberOfRows`

```swift
public var numberOfRows: Int
```

## Methods
### `init(_:rows:identifier:)`

```swift
public init(_ content: Any? = nil, rows: [RowType], identifier: String? = nil)
```

### `init(_:items:rowIdentifier:sectionIdentifier:)`

```swift
public convenience init(_ content: Any? = nil, items: [Any], rowIdentifier: String? = nil, sectionIdentifier: String? = nil)
```

### `with(identifier:)`

```swift
public func with(identifier: String) -> Section
```

### `row(at:)`

```swift
public func row(at index: Int) -> RowType
```

### `update(rows:)`

```swift
public func update(rows: [RowType])
```
