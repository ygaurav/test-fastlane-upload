**PROTOCOL**

# `EmployeePhotoService`

```swift
public protocol EmployeePhotoService
```

## Methods
### `profileImage(for:completion:)`

```swift
@discardableResult func profileImage(for hrid: String, completion: @escaping(Result<Data, Error>) -> Void) -> BCGAPICore.Operation?
```
