**STRUCT**

# `OfficeLocation`

```swift
public struct OfficeLocation: Codable
```

## Properties
### `id`

```swift
public let id: String?
```

### `name`

```swift
public let name: String?
```

### `regionId`

```swift
public let regionId: String?
```

### `street`

```swift
public let street: String?
```

### `street2`

```swift
public let street2: String?
```

### `street3`

```swift
public let street3: String?
```

### `city`

```swift
public let city: String?
```

### `state`

```swift
public let state: String?
```

### `zipCode`

```swift
public let zipCode: String?
```

### `country`

```swift
public let country: String?
```

### `imageUrl`

```swift
public let imageUrl: String?
```

### `location`

```swift
public let location: BCGLocationCoordinate?
```

### `timezone`

```swift
public let timezone: String?
```

### `weather`

```swift
public let weather: Weather?
```

### `configuration`

```swift
public let configuration: Configuration
```

### `fullStreet`

```swift
public var fullStreet: String?
```

### `address`

```swift
public var address: CNPostalAddress
```

## Methods
### `init(id:name:regionId:street:street2:street3:city:state:zipCode:country:imageUrl:location:timezone:weather:configuration:)`

```swift
public init(id: String, name: String?, regionId: String?, street: String?, street2: String?, street3: String?, city: String?, state: String?, zipCode: String?, country: String?, imageUrl: String?, location: BCGLocationCoordinate?, timezone: String?, weather: Weather?, configuration: Configuration)
```
