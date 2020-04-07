**STRUCT**

# `EmptyTableDescriptor`

```swift
public struct EmptyTableDescriptor: EmptyTableDescriptorType
```

> Initializes a descriptor which is used for showing message in tableview when there nothing to display.
> - Precondition: This will activate when conditions stated below are met.
>     * EmptyTableDescriptor set in CellProvider is not nil
>     * There are zero sections **OR** There is 1 section & it has zero cells
>  ### Parameters ###
>  - **title**: Title of the message shown
>  - **subtitle**: Subtitle of the message shown
>  - **placeholderImage**: Optional image you would like to show to user
>  - **titleAttributes**: Optional attributes for title of the message. Default is standard BCGGreen color & Bold font of 18pt size.
>  - **subtitleAttributes**: Optional attributes for title of the message. Default is standard BCGLightGray color & Regular font of 14pt size.
>  - **shouldAnimate**: Light scale up animation is added to the message. Default is true.

## Properties
### `placeholderImage`

```swift
public var placeholderImage: UIImage?
```

### `title`

```swift
public var title: String
```

### `subtitle`

```swift
public var subtitle: String
```

### `titleAttributes`

```swift
public var titleAttributes: [NSAttributedString.Key: Any]
```

### `subtitleAttributes`

```swift
public var subtitleAttributes: [NSAttributedString.Key: Any]
```

### `shouldAnimate`

```swift
public var shouldAnimate: Bool = false
```

## Methods
### `init(placeholderImage:title:subtitle:titleAttributes:subtitleAttributes:shouldAnimate:)`

```swift
public init(placeholderImage: UIImage? = nil, title: String, subtitle: String, titleAttributes: Attributes = [:], subtitleAttributes: Attributes = [:], shouldAnimate: Bool = true)
```
