**CLASS**

# `ScrollDescriptor`

```swift
public class ScrollDescriptor: ScrollDescriptorType
```

## Properties
### `scrollViewClosure`

```swift
public private(set) var scrollViewClosure: ((UIScrollView) -> Void)?
```

## Methods
### `init()`

```swift
public init()
```

### `didScroll(_:)`

```swift
public func didScroll(_ closure: @escaping ((UIScrollView) -> Void)) -> ScrollDescriptor
```
