**PROTOCOL**

# `EmployeeModel`

```swift
public protocol EmployeeModel: PhoneConnected, MobileConnected, EmailConnected, WebExConnected, SlackConnected, ZoomConnected, EmployeeIdentifiable
```

## Properties
### `empId`

```swift
var empId: String
```

### `name`

```swift
var name: String
```

### `firstName`

```swift
var firstName: String
```

### `lastName`

```swift
var lastName: String
```

### `displayName`

```swift
var displayName: String
```

### `title`

```swift
var title: String
```

### `picture`

```swift
var picture: String
```

### `location`

```swift
var location: String
```

### `blogURL`

```swift
var blogURL: URL?
```

### `locationCity`

```swift
var locationCity: String?
```

### `locationCountry`

```swift
var locationCountry: String?
```
