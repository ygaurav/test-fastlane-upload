**STRUCT**

# `Route`

```swift
public struct Route
```

## Properties
### `previewViewController`

```swift
public var previewViewController: UIViewController
```

## Methods
### `new(style:build:)`

```swift
public static func new<Destination: UIViewController>(style: PresentationStyle, build: @escaping () -> Destination) -> Route
```

### `unwind(to:predicate:configure:)`

```swift
public static func unwind<Destination: UIViewController>(to destination: Destination.Type, predicate: ((Destination) -> Bool)? = nil, configure: ((Destination) -> Void)? = nil) -> Route
```

### `navigate(from:)`

```swift
public func navigate(from source: UIViewController)
```
