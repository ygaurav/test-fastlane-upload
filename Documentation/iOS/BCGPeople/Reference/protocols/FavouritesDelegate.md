**PROTOCOL**

# `FavouritesDelegate`

```swift
public protocol FavouritesDelegate: class
```

## Methods
### `addEmployeeAsFavourite(employee:)`

```swift
@discardableResult func addEmployeeAsFavourite(employee: EmployeeModel) -> Bool
```

### `deleteEmployeeAsFavourite(employee:)`

```swift
func deleteEmployeeAsFavourite(employee: EmployeeModel)
```

### `getFavouriteStatusFor(employee:)`

```swift
func getFavouriteStatusFor(employee: EmployeeModel) -> Bool
```
