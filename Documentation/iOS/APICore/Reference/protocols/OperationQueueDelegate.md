**PROTOCOL**

# `OperationQueueDelegate`

```swift
public protocol OperationQueueDelegate: class
```

> The delegate of an `OperationQueue` can respond to `Operation` lifecycle
> events by implementing these methods.
>
> In general, implementing `OperationQueueDelegate` is not necessary; you would
> want to use an `OperationObserver` instead. However, there are a couple of
> situations where using `OperationQueueDelegate` can lead to simpler code.
> For example, `GroupOperation` is the delegate of its own internal
> `OperationQueue` and uses it to manage dependencies.

## Methods
### `operationQueue(_:willAddOperation:)`

```swift
func operationQueue(_ operationQueue: BCGOperationQueue, willAddOperation operation: Foundation.Operation)
```

### `operationQueue(_:operationDidFinish:withErrors:)`

```swift
func operationQueue(_ operationQueue: BCGOperationQueue, operationDidFinish operation: Foundation.Operation, withErrors errors: [Error])
```
