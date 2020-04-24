**PROTOCOL**

# `GeoCodingService`

```swift
public protocol GeoCodingService
```

## Properties
### `clLocationManager`

```swift
var clLocationManager: CLLocationManager?
```

## Methods
### `init(locationManager:)`

```swift
init(locationManager: CLLocationManager)
```

### `getLocation(completionHandler:)`

```swift
func getLocation(completionHandler:@escaping LocationClosure)
```

### `getReverseGeoCoded(with:completionHandler:)`

```swift
func getReverseGeoCoded(with location: CLLocation, completionHandler: @escaping ReverseGeoLocationClosure)
```

### `getReverseGeoCoded(with:completionHandler:)`

```swift
func getReverseGeoCoded(with address: String, completionHandler:@escaping ReverseGeoLocationClosure)
```
