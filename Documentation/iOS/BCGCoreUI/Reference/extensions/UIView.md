**EXTENSION**

# `UIView`

## Methods
### `addConstraintsWithFormat(_:views:)`

```swift
public func addConstraintsWithFormat(_ format: String, views: UIView...)
```

### `fillSuperview()`

```swift
public func fillSuperview()
```

### `anchor(_:left:bottom:right:topConstant:leftConstant:bottomConstant:rightConstant:widthConstant:heightConstant:)`

```swift
public func anchor(_ top: NSLayoutYAxisAnchor? = nil, left: NSLayoutXAxisAnchor? = nil, bottom: NSLayoutYAxisAnchor? = nil, right: NSLayoutXAxisAnchor? = nil, topConstant: CGFloat = 0, leftConstant: CGFloat = 0, bottomConstant: CGFloat = 0, rightConstant: CGFloat = 0, widthConstant: CGFloat = 0, heightConstant: CGFloat = 0)
```

### `anchorWithReturnAnchors(_:left:bottom:right:topConstant:leftConstant:bottomConstant:rightConstant:widthConstant:heightConstant:)`

```swift
public func anchorWithReturnAnchors(_ top: NSLayoutYAxisAnchor? = nil, left: NSLayoutXAxisAnchor? = nil, bottom: NSLayoutYAxisAnchor? = nil, right: NSLayoutXAxisAnchor? = nil, topConstant: CGFloat = 0, leftConstant: CGFloat = 0, bottomConstant: CGFloat = 0, rightConstant: CGFloat = 0, widthConstant: CGFloat = 0, heightConstant: CGFloat = 0) -> [NSLayoutConstraint]
```

### `anchorCenterXToSuperview(constant:)`

```swift
public func anchorCenterXToSuperview(constant: CGFloat = 0)
```

### `anchorCenterYToSuperview(constant:)`

```swift
public func anchorCenterYToSuperview(constant: CGFloat = 0)
```

### `anchorCenterSuperview()`

```swift
public func anchorCenterSuperview()
```
