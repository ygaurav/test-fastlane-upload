**PROTOCOL**

# `CellConfigurator`

```swift
public protocol CellConfigurator
```

## Properties
### `configuratorId`

```swift
var configuratorId: String
```

### `reuseIdentifier`

```swift
var reuseIdentifier: String
```

### `viewType`

```swift
var viewType: ConfigurableCell.Type
```

## Methods
### `configure(item:view:)`

```swift
func configure(item: DataSourceIdentifiable, view: ConfigurableCell)
```

### `didSelect(item:)`

```swift
func didSelect(item: DataSourceIdentifiable)
```
