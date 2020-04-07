**CLASS**

# `SectionDescriptor`

```swift
public class SectionDescriptor<HeaderFooterContent>: SectionDescriptorType
```

## Properties
### `identifier`

```swift
public let identifier: String
```

### `headerClosure`

```swift
public private(set) var headerClosure: ((SectionType, Int) -> HeaderFooter)?
```

### `footerClosure`

```swift
public private(set) var footerClosure: ((SectionType, Int) -> HeaderFooter)?
```

### `headerHeightClosure`

```swift
public private(set) var headerHeightClosure: ((SectionType, Int) -> SectionHeight)?
```

### `footerHeightClosure`

```swift
public private(set) var footerHeightClosure: ((SectionType, Int) -> SectionHeight)?
```

### `willDisplayHeaderClosure`

```swift
public private(set) var willDisplayHeaderClosure: ((SectionType, UIView, Int) -> Void)?
```

### `willDisplayFooterClosure`

```swift
public private(set) var willDisplayFooterClosure: ((SectionType, UIView, Int) -> Void)?
```

### `didEndDisplayingHeaderClosure`

```swift
public private(set) var didEndDisplayingHeaderClosure: ((SectionType, UIView, Int) -> Void)?
```

### `didEndDisplayingFooterClosure`

```swift
public private(set) var didEndDisplayingFooterClosure: ((SectionType, UIView, Int) -> Void)?
```

## Methods
### `init(_:)`

```swift
public init(_ identifier: String? = nil)
```

### `header(_:)`

```swift
public func header(_ closure: @escaping (HeaderFooterContent, Int) -> HeaderFooter) -> SectionDescriptor
```

### `header(_:)`

```swift
public func header(_ closure: @escaping () -> HeaderFooter) -> SectionDescriptor
```

### `footer(_:)`

```swift
public func footer(_ closure: @escaping (HeaderFooterContent, Int) -> HeaderFooter) -> SectionDescriptor
```

### `footer(_:)`

```swift
public func footer(_ closure: @escaping () -> HeaderFooter) -> SectionDescriptor
```

### `headerHeight(_:)`

```swift
public func headerHeight(_ closure: @escaping (HeaderFooterContent, Int) -> SectionHeight) -> SectionDescriptor
```

### `headerHeight(_:)`

```swift
public func headerHeight(_ closure: @escaping () -> SectionHeight) -> SectionDescriptor
```

### `footerHeight(_:)`

```swift
public func footerHeight(_ closure: @escaping (HeaderFooterContent, Int) -> SectionHeight) -> SectionDescriptor
```

### `footerHeight(_:)`

```swift
public func footerHeight(_ closure: @escaping () -> SectionHeight) -> SectionDescriptor
```

### `willDisplayHeader(_:)`

```swift
public func willDisplayHeader(_ closure: @escaping (HeaderFooterContent, UIView, Int) -> Void) -> SectionDescriptorType
```

### `willDisplayHeader(_:)`

```swift
public func willDisplayHeader(_ closure: @escaping () -> Void) -> SectionDescriptor
```

### `willDisplayFooter(_:)`

```swift
public func willDisplayFooter(_ closure: @escaping (HeaderFooterContent, UIView, Int) -> Void) -> SectionDescriptorType
```

### `willDisplayFooter(_:)`

```swift
public func willDisplayFooter(_ closure: @escaping () -> Void) -> SectionDescriptor
```

### `didEndDisplayingHeader(_:)`

```swift
public func didEndDisplayingHeader(_ closure: @escaping (HeaderFooterContent, UIView, Int) -> Void) -> SectionDescriptorType
```

### `didEndDisplayingHeader(_:)`

```swift
public func didEndDisplayingHeader(_ closure: @escaping () -> Void) -> SectionDescriptor
```

### `didEndDisplayingFooter(_:)`

```swift
public func didEndDisplayingFooter(_ closure: @escaping (HeaderFooterContent, UIView, Int) -> Void) -> SectionDescriptorType
```

### `didEndDisplayingFooter(_:)`

```swift
public func didEndDisplayingFooter(_ closure: @escaping () -> Void) -> SectionDescriptor
```
