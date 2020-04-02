**STRUCT**

# `BlockObserver`

```swift
public struct BlockObserver: OperationObserver
```

> The `BlockObserver` is a way to attach arbitrary blocks to significant events
> in an `Operation`'s lifecycle.

## Methods
### `init(startHandler:cancelHandler:produceHandler:finishHandler:)`

```swift
public init(startHandler: ((Operation) -> Void)? = nil, cancelHandler: ((Operation) -> Void)? = nil, produceHandler: ((Operation, Foundation.Operation) -> Void)? = nil, finishHandler: ((Operation, [Error]) -> Void)? = nil)
```

### `operationDidStart(_:)`

```swift
public func operationDidStart(_ operation: Operation)
```

### `operationDidCancel(_:)`

```swift
public func operationDidCancel(_ operation: Operation)
```

### `operation(_:didProduceOperation:)`

```swift
public func operation(_ operation: Operation, didProduceOperation newOperation: Foundation.Operation)
```

### `operationDidFinish(_:errors:)`

```swift
public func operationDidFinish(_ operation: Operation, errors: [Error])
```
