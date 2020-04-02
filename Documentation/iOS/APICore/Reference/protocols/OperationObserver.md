**PROTOCOL**

# `OperationObserver`

```swift
public protocol OperationObserver
```

> The protocol that types may implement if they wish to be notified of significant
> operation lifecycle events.

## Methods
### `operationDidStart(_:)`

```swift
func operationDidStart(_ operation: Operation)
```

> Invoked immediately prior to the `Operation`'s `execute()` method.

### `operationDidCancel(_:)`

```swift
func operationDidCancel(_ operation: Operation)
```

> Invoked immediately after the first time the `Operation`'s `cancel()` method is called

### `operation(_:didProduceOperation:)`

```swift
func operation(_ operation: Operation, didProduceOperation newOperation: Foundation.Operation)
```

> Invoked when `Operation.produceOperation(_:)` is executed.

### `operationDidFinish(_:errors:)`

```swift
func operationDidFinish(_ operation: Operation, errors: [Error])
```

> Invoked as an `Operation` finishes, along with any errors produced during
> execution (or readiness evaluation).
