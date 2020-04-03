**CLASS**

# `APIJSONResponseSerializer`

```swift
open class APIJSONResponseSerializer<ResponseType: ExpressibleByJSONObject>: APIResponseSerializer<ResponseType>
```

## Methods
### `parse(responseData:)`

```swift
override open func parse(responseData: Data) throws -> ResponseType
```
