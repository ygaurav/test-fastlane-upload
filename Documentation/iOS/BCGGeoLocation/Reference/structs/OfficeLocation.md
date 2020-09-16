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

### `phone`

```swift
public let phone: String?
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
### `init(id:name:phone:regionId:street:street2:street3:city:state:zipCode:country:imageUrl:location:timezone:weather:configuration:)`

```swift
public init(id: String?, name: String? = nil, phone: String? = nil, regionId: String? = nil, street: String? = nil, street2: String? = nil, street3: String? = nil, city: String? = nil, state: String? = nil, zipCode: String? = nil, country: String? = nil, imageUrl: String? = nil, location: BCGLocationCoordinate? = nil, timezone: String? = nil, weather: Weather? = nil, configuration: Configuration = Configuration())
```
