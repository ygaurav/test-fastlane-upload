**CLASS**

# `OfficeActionBannerModel`

```swift
public class OfficeActionBannerModel: IdentifiableItem
```

## Properties
### `identifier`

```swift
public let identifier: String
```

### `icon`

```swift
public let icon: UIImage?
```

### `header`

```swift
public let header: NSAttributedString?
```

### `title`

```swift
public let title: NSAttributedString?
```

## Methods
### `init(identifier:icon:header:title:)`

```swift
public init(identifier: String, icon: UIImage? = nil, header: NSAttributedString? = nil, title: NSAttributedString? = nil)
```

### `init(type:icon:header:title:)`

```swift
public init(type: ActionType, icon: UIImage? = nil, header: NSAttributedString? = nil, title: NSAttributedString? = nil)
```
