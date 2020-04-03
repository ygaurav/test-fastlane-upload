**CLASS**

# `BCGOperationQueue`

```swift
open class BCGOperationQueue: Foundation.OperationQueue
```

> `OperationQueue` is an `NSOperationQueue` subclass that implements a large
> number of "extra features" related to the `Operation` class:
>
> - Notifying a delegate of all operation completion
> - Extracting generated dependencies from operation conditions
> - Setting up dependencies to enforce mutual exclusivity

## Properties
### `delegate`

```swift
open weak var delegate: OperationQueueDelegate?
```

## Methods
### `addOperation(_:)`

```swift
override open  func addOperation(_ operation: Foundation.Operation)
```

### `addOperations(_:waitUntilFinished:)`

```swift
override open func addOperations(_ ops: [Foundation.Operation], waitUntilFinished wait: Bool)
```
