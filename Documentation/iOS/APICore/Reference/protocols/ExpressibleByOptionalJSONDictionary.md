**PROTOCOL**

# `ExpressibleByOptionalJSONDictionary`

```swift
public protocol ExpressibleByOptionalJSONDictionary: ExpressibleByJSONDictionary
```

## Methods
### `parse(json:defaultValue:)`

```swift
static func parse(json: [String: Any]?, defaultValue: Self) throws -> Self
```

### `init(_:)`

```swift
init(_ other: Self)
```
