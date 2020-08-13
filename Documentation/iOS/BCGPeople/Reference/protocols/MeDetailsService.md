**PROTOCOL**

# `MeDetailsService`

```swift
public protocol MeDetailsService
```

## Methods
### `me(for:dataSet:completion:)`

```swift
@discardableResult func me(for email: String, dataSet: String, completion: @escaping(Result<EmployeeDetails, Error>) -> Void) -> BCGAPICore.Operation?
```
