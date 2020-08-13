**CLASS**

# `Employee`

```swift
public class Employee: ExpressibleByJSONDictionary, Codable
```

## Properties
### `empId`

```swift
public let empId: String
```

### `name`

```swift
public let name: String
```

### `firstName`

```swift
public var firstName: String
```

### `lastName`

```swift
public var lastName: String
```

### `displayName`

```swift
public let displayName: String
```

### `title`

```swift
public let title: String
```

### `jobFunction`

```swift
public var jobFunction: String
```

### `email`

```swift
public let email: String?
```

### `phone`

```swift
public let phone: String?
```

### `slackId`

```swift
public let slackId: String?
```

### `mobile`

```swift
public let mobile: String?
```

### `location`

```swift
public let location: String
```

### `picture`

```swift
public let picture: String
```

### `lineManager`

```swift
public let lineManager: Employee?
```

### `reportingLine`

```swift
public let reportingLine: [Employee]
```

### `hostOfficeLocation`

```swift
public let hostOfficeLocation: OfficeLocation?
```

### `lastUpdated`

```swift
public let lastUpdated: Date?
```

### `assistants`

```swift
public let assistants: [Assistant]
```

## Methods
### `init(empId:name:firstName:lastName:displayName:title:jobFunction:email:phone:mobile:location:picture:lineManager:reportingLine:hostOfficeLocation:lastUpdated:slackID:assistants:)`

```swift
public init(empId: String, name: String = "", firstName: String = "", lastName: String = "", displayName: String = "", title: String = "", jobFunction: String = "", email: String = "", phone: String = "", mobile: String = "", location: String = "", picture: String = "", lineManager: Employee? = nil, reportingLine: [Employee] = [], hostOfficeLocation: OfficeLocation? = nil, lastUpdated: Date? = nil, slackID: String? = nil, assistants: [Assistant] = [])
```

### `init(json:)`

```swift
public required init(json: [String: Any]) throws
```
