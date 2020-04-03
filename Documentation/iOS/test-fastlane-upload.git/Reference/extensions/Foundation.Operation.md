**EXTENSION**

# `Foundation.Operation`

## Methods
### `addCompletionBlock(_:)`

```swift
public func addCompletionBlock(_ block: @escaping () -> Void)
```

> Add a completion block to be executed after the `NSOperation` enters the
> "finished" state.

### `addDependencies(_:)`

```swift
public func addDependencies(_ dependencies: [Foundation.Operation])
```

> Add multiple depdendencies to the operation.
