**STRUCT**

# `IdentifiableSection`

```swift
public struct IdentifiableSection: Hashable
```

## Properties
### `identifier`

```swift
public let identifier: String
```

### `title`

```swift
public let title: String
```

### `items`

```swift
private(set) public var items: [IdentifiableItem]
```

## Methods
### `init(identifier:title:items:)`

```swift
public init(identifier: String, title: String, items: [IdentifiableItem])
```

### `updateItems(_:)`

```swift
public mutating func updateItems(_ items: [IdentifiableItem])
```

### `hash(into:)`

```swift
public func hash(into hasher: inout Hasher)
```

#### Parameters

| Name | Description |
| ---- | ----------- |
| hasher | The hasher to use when combining the components of this instance. |

### `==(_:_:)`

```swift
public static func == (lhs: IdentifiableSection, rhs: IdentifiableSection) -> Bool
```

#### Parameters

| Name | Description |
| ---- | ----------- |
| lhs | A value to compare. |
| rhs | Another value to compare. |