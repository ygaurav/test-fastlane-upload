**PROTOCOL**

# `EmployeeDetailsService`

```swift
public protocol EmployeeDetailsService
```

## Methods
### `details(for:dataSet:completion:)`

```swift
@discardableResult func details(for employeeID: String, dataSet: String, completion: @escaping(Result<EmployeeDetails, Error>) -> Void) -> BCGAPICore.Operation?
```
