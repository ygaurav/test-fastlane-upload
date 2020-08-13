**CLASS**

# `CustomImageView`

```swift
public class CustomImageView: UIImageView, PictureImage
```

## Methods
### `loadImageWith(employee:pictureService:completed:)`

```swift
public func loadImageWith(employee: EmployeeIdentifiable, pictureService: PictureService, completed: ((_ image: UIImage?) -> Void)? = nil)
```

### `getImage(for:imgData:completed:)`

```swift
public func getImage(for employeeId: String, imgData: Data?, completed: @escaping ((_ image: UIImage?) -> Void))
```
