**CLASS**

# `APIResponseSerializerOperation`

```swift
public class APIResponseSerializerOperation<DataType>: Operation
```

## Properties
### `response`

```swift
public var response: APIResponse?
```

### `result`

```swift
public var result: Result<DataType, Error>?
```

### `plainResult`

```swift
public var plainResult: DataType?
```

## Methods
### `init(serializer:)`

```swift
public init(serializer: APIResponseSerializer<DataType>)
```

### `execute()`

```swift
final public override func execute()
```
