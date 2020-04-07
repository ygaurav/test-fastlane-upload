**CLASS**

# `RouteTransitionManager`

```swift
public class RouteTransitionManager: NSObject, UIViewControllerTransitioningDelegate
```

## Methods
### `animationController(forPresented:presenting:source:)`

```swift
public func animationController(forPresented presented: UIViewController, presenting: UIViewController, source: UIViewController) -> UIViewControllerAnimatedTransitioning?
```

### `animationController(forDismissed:)`

```swift
public func animationController(forDismissed dismissed: UIViewController) -> UIViewControllerAnimatedTransitioning?
```
