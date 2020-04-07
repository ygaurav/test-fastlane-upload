**CLASS**

# `TransitionAnimators`

```swift
public class TransitionAnimators: NSObject
```

## Methods
### `addForPresenting(transition:)`

```swift
public func addForPresenting(transition: ViewControllerTransitioning)
```

### `addForDismissing(transition:)`

```swift
public func addForDismissing(transition: ViewControllerTransitioning)
```

### `animator(for:_:)`

```swift
public func animator(for viewController1: UIViewController, _ viewController2: UIViewController) -> UIViewControllerAnimatedTransitioning?
```

### `animator(for:)`

```swift
public func animator(for dismissed: UIViewController) -> UIViewControllerAnimatedTransitioning?
```
