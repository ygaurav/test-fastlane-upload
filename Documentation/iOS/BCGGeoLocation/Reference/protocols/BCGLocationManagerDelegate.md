**PROTOCOL**

# `BCGLocationManagerDelegate`

```swift
public protocol BCGLocationManagerDelegate: class
```

## Methods
### `locationManager(_:didUpdateLocations:)`

```swift
func locationManager(_ manager: BCGLocationManager, didUpdateLocations locations: [BCGLocation])
```

### `locationManager(_:didFailWithError:)`

```swift
func locationManager(_ manager: BCGLocationManager, didFailWithError error: Error)
```

### `locationManager(_:didChangeAuthorization:)`

```swift
func locationManager(_ manager: BCGLocationManager, didChangeAuthorization status: CLAuthorizationStatus)
```
