**PROTOCOL**

# `ProfileRouter`

```swift
public protocol ProfileRouter: Router
```

## Methods
### `showProfile(of:)`

```swift
func showProfile(of employeeIdentifiable: EmployeeIdentifiable)
```

### `showOffice(of:)`

```swift
func showOffice(of: OfficeLocationIdentifiable)
```

### `showVendors(_:pictureService:spotlightIndexer:)`

```swift
func showVendors(_: [Employee], pictureService: PictureService, spotlightIndexer: SpotlightContactIndexer)
```
