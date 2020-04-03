**CLASS**

# `GroupOperation`

```swift
open class GroupOperation: Operation
```

## Methods
### `init(operations:)`

```swift
public convenience init(operations: Foundation.Operation...)
```

### `init(operations:)`

```swift
public init(operations: [Foundation.Operation])
```

### `cancel()`

```swift
override open func cancel()
```

### `execute()`

```swift
override open func execute()
```

### `addOperation(_:)`

```swift
open func addOperation(_ operation: Foundation.Operation)
```

### `aggregateError(_:)`

```swift
public final func aggregateError(_ error: Error)
```

> Note that some part of execution has produced an error.
> Errors aggregated through this method will be included in the final array
> of errors reported to observers and to the `finished(_:)` method.

### `operationDidFinish(_:withErrors:)`

```swift
open func operationDidFinish(_ operation: Foundation.Operation, withErrors errors: [Error])
```
