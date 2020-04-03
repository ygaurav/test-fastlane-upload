**CLASS**

# `Operation`

```swift
open class Operation: Foundation.Operation
```

## Properties
### `isReady`

```swift
override open var isReady: Bool
```

### `isExecuting`

```swift
override open var isExecuting: Bool
```

### `isFinished`

```swift
override open var isFinished: Bool
```

### `isCancelled`

```swift
override open var isCancelled: Bool
```

### `errors`

```swift
open var errors: [Error]
```

## Methods
### `start()`

```swift
override final public func start()
```

### `main()`

```swift
override final public func main()
```

### `execute()`

```swift
open func execute()
```

### `finish(_:)`

```swift
public final func finish(_ errors: [Error] = [])
```

### `cancel()`

```swift
override open func cancel()
```

### `produceOperation(_:)`

```swift
public final func produceOperation(_ operation: Foundation.Operation)
```

### `addObserver(_:)`

```swift
open func addObserver(_ observer: OperationObserver)
```
