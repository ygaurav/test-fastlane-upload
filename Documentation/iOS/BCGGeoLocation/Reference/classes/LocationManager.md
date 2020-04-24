**CLASS**

# `LocationManager`

```swift
public class LocationManager: NSObject, GeoCodingService
```

## Properties
### `clLocationManager`

```swift
public var clLocationManager: CLLocationManager?
```

## Methods
### `init(locationManager:)`

```swift
public required init(locationManager: CLLocationManager)
```

### `deinit`

```swift
deinit
```

### `getLocation(completionHandler:)`

```swift
public func getLocation(completionHandler:@escaping LocationClosure)
```

> Get current location
>
> - Parameter completionHandler: will return CLLocation object which is the current location of the user and NSError in case of error

#### Parameters

| Name | Description |
| ---- | ----------- |
| completionHandler | will return CLLocation object which is the current location of the user and NSError in case of error |

### `getReverseGeoCoded(with:completionHandler:)`

```swift
public func getReverseGeoCoded(with location: BCGLocation, completionHandler: @escaping ReverseGeoLocationClosure )
```

> Get Reverse Geocoded Placemark address by passing CLLocation
>
> - Parameters:
>   - location: location Passed which is a CLLocation object
>   - completionHandler: will return CLLocation object and CLPlacemark of the CLLocation and NSError in case of error

#### Parameters

| Name | Description |
| ---- | ----------- |
| location | location Passed which is a CLLocation object |
| completionHandler | will return CLLocation object and CLPlacemark of the CLLocation and NSError in case of error |

### `getReverseGeoCoded(with:completionHandler:)`

```swift
public func getReverseGeoCoded(with address: String, completionHandler:@escaping ReverseGeoLocationClosure)
```

> Get Latitude and Longitude of the address as CLLocation object
>
> - Parameters:
>   - address: address given by the user in String
>   - completionHandler: will return CLLocation object and CLPlacemark of the address entered and NSError in case of error

#### Parameters

| Name | Description |
| ---- | ----------- |
| address | address given by the user in String |
| completionHandler | will return CLLocation object and CLPlacemark of the address entered and NSError in case of error |