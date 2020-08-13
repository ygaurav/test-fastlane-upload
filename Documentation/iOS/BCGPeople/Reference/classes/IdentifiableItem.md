**CLASS**

# `IdentifiableItem`

```swift
open class IdentifiableItem: Hashable, DataSourceIdentifiable
```

## Properties
### `id`

```swift
public let id: String
```

## Methods
### `init(id:)`

```swift
public init(id: String)
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
public static func == (lhs: IdentifiableItem, rhs: IdentifiableItem) -> Bool
```

#### Parameters

| Name | Description |
| ---- | ----------- |
| lhs | A value to compare. |
| rhs | Another value to compare. |