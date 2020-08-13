**PROTOCOL**

# `EmployeeService`

```swift
public protocol EmployeeService
```

## Methods
### `search(text:limit:offset:completion:)`

```swift
@discardableResult func search(text: String, limit: Int, offset: Int, completion: @escaping(Result<TeamSearchResult, Error>) -> Void) -> BCGAPICore.Operation?
```
