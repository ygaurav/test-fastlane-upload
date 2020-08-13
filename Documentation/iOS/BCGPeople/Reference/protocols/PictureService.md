**PROTOCOL**

# `PictureService`

```swift
public protocol PictureService
```

## Methods
### `picture(for:completion:)`

```swift
@discardableResult func picture(for hrid: String, completion: @escaping(Result<Data, Error>) -> Void) -> BCGAPICore.Operation?
```
