**PROTOCOL**

# `SectionDescriptorType`

```swift
public protocol SectionDescriptorType
```

## Properties
### `identifier`

```swift
var identifier: String
```

### `headerClosure`

```swift
var headerClosure: ((SectionType, Int) -> HeaderFooter)?
```

### `footerClosure`

```swift
var footerClosure: ((SectionType, Int) -> HeaderFooter)?
```

### `headerHeightClosure`

```swift
var headerHeightClosure: ((SectionType, Int) -> SectionHeight)?
```

### `footerHeightClosure`

```swift
var footerHeightClosure: ((SectionType, Int) -> SectionHeight)?
```

### `willDisplayHeaderClosure`

```swift
var willDisplayHeaderClosure: ((SectionType, UIView, Int) -> Void)?
```

### `willDisplayFooterClosure`

```swift
var willDisplayFooterClosure: ((SectionType, UIView, Int) -> Void)?
```
