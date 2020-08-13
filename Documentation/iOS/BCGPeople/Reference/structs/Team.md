**STRUCT**

# `Team`

```swift
public struct Team: ExpressibleByJSONDictionary
```

## Methods
### `init(name:id:summary:slackUrl:egnyteUrl:imageName:members:contentLinks:)`

```swift
public init(name: String,
     id: String,
     summary: String? = nil,
     slackUrl: String? = nil,
     egnyteUrl: String? = nil,
     imageName: String? = nil,
     members: [String] = [], contentLinks: [ContentLinks] = [])
```

### `init(json:)`

```swift
public init(json: [String: Any]) throws
```
