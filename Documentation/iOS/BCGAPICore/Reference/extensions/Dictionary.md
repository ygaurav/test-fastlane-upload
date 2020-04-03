**EXTENSION**

# `Dictionary`

## Methods
### `parse(_:throwIfEmpty:discardInvalidItems:file:line:)`

```swift
public func parse<T: ExpressibleByJSONDictionary>(_ key: String, throwIfEmpty: Bool = false, discardInvalidItems: Bool = true, file: StaticString = #file, line: UInt = #line) throws -> [T]
```

### `parse(_:)`

```swift
public func parse<T: ExpressibleByJSONDictionary>(_ key: String) throws -> T
```

### `parse(_:)`

```swift
public func parse<T: ExpressibleByJSONDictionary>(_ key: String) throws -> T?
```

### `parse(_:throwIfEmpty:discardInvalidItems:file:line:)`

```swift
public func parse<T: ExpressibleByString>(_ key: String, throwIfEmpty: Bool = false, discardInvalidItems: Bool = true, file: StaticString = #file, line: UInt = #line) throws -> [T]
```

### `parse(_:)`

```swift
public func parse<T: ExpressibleByString>(_ key: String) throws -> T
```

### `parse(_:)`

```swift
public func parse<T: ExpressibleByString>(_ key: String) throws -> T?
```

### `parse(_:)`

```swift
public func parse(_ key: String) throws -> Any
```

### `parse(_:)`

```swift
public func parse(_ key: String) -> Any?
```

### `parse(_:)`

```swift
public func parse(_ key: String) throws -> String
```

### `parse(_:)`

```swift
public func parse(_ key: String) throws -> String?
```

### `parse(_:)`

```swift
public func parse(_ key: String) throws -> NSNumber
```

### `parse(_:)`

```swift
public func parse(_ key: String) throws -> NSNumber?
```

### `parse(_:)`

```swift
public func parse(_ key: String) throws -> Decimal
```

### `parse(_:)`

```swift
public func parse(_ key: String) throws -> Decimal?
```

### `parse(_:)`

```swift
public func parse(_ key: String) throws -> Bool
```

### `parse(_:defaultValue:)`

```swift
public func parse(_ key: String, defaultValue: Bool) -> Bool
```

### `parse(_:)`

```swift
public func parse(_ key: String) throws -> Int
```

### `parse(_:)`

```swift
public func parse(_ key: String) throws -> Int?
```

### `parse(_:)`

```swift
public func parse(_ key: String) throws -> TimeInterval
```

### `parse(_:)`

```swift
public func parse(_ key: String) throws -> TimeInterval?
```

### `parse(_:formatter:)`

```swift
public func parse(_ key: String, formatter: DateFormatter) throws -> Date
```

### `parse(_:formatter:)`

```swift
public func parse(_ key: String, formatter: DateFormatter) throws -> Date?
```

### `parse(_:)`

```swift
public func parse(_ key: String) throws -> [String: Any]
```

### `parse(_:)`

```swift
public func parse(_ key: String) throws -> [String: Any]?
```

### `parse(_:throwIfEmpty:)`

```swift
public func parse(_ key: String, throwIfEmpty: Bool = false) throws -> [String]
```

### `parse(_:throwIfEmpty:)`

```swift
public func parse(_ key: String, throwIfEmpty: Bool = false) throws -> [[String: Any]]
```

### `parse(_:throwIfEmpty:)`

```swift
public func parse(_ key: String, throwIfEmpty: Bool = false) throws -> [[String: Any]]?
```
