**PROTOCOL**

# `EmployeeDetailsService`

```swift
public protocol EmployeeDetailsService
```

## Methods
### `details(for:field:dataSet:completion:)`

```swift
@discardableResult func details(for employeeID: String, field: String?, dataSet: String, completion: @escaping(Result<EmployeeDetails, Error>) -> Void) -> BCGAPICore.Operation?
```
