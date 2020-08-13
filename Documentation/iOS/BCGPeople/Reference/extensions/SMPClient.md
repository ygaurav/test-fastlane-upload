**EXTENSION**

# `SMPClient`

## Methods
### `details(for:dataSet:completion:)`

```swift
public func details(for employeeID: String, dataSet: String, completion: @escaping(Result<EmployeeDetails, Error>) -> Void) -> BCGAPICore.Operation?
```

### `people(for:param:offset:numberOfRecords:limit:dataSet:completion:)`

```swift
@discardableResult public func people(for   code: String,
                                      param: String,
                                      offset: Int,
                                      numberOfRecords: Int,
                                      limit: Int,
                                      dataSet: String,
                                      completion: @escaping(Result<SearchResults, Error>) -> Void) -> BCGAPICore.Operation?
```

### `allTeams(completion:)`

```swift
@discardableResult public func allTeams(completion: @escaping(Result<AllTeamResult, Error>) -> Void) -> BCGAPICore.Operation?
```

### `teams(forEmployeeId:completion:)`

```swift
@discardableResult public func teams(forEmployeeId employeeID: String, completion: @escaping(Result<ProfileTeamResult, Error>) -> Void) -> BCGAPICore.Operation?
```

### `team(withID:completion:)`

```swift
@discardableResult public func team(withID teamId: String, completion: @escaping(Result<AddTeamResult, Error>) -> Void) -> BCGAPICore.Operation?
```

### `teamMembers(withIDs:completion:)`

```swift
@discardableResult public func teamMembers(withIDs ids: [String], completion: @escaping(Result<TeamsEmployeeDetails, Error>) -> Void) -> BCGAPICore.Operation?
```

### `delete(teamId:completion:)`

```swift
@discardableResult public func delete(teamId: String, completion: @escaping(Result<DeleteTeamResponse, Error>) -> Void) -> BCGAPICore.Operation?
```

### `update(team:completion:)`

```swift
@discardableResult public func update(team: Team, completion: @escaping(Result<UpdateTeamResult, Error>) -> Void) -> BCGAPICore.Operation?
```

### `add(team:completion:)`

```swift
@discardableResult public func add(team: Team, completion: @escaping(Result<AddTeamResult, Error>) -> Void) -> BCGAPICore.Operation?
```

### `search(text:limit:offset:completion:)`

```swift
@discardableResult public func search(text: String, limit: Int, offset: Int, completion: @escaping(Result<TeamSearchResult, Error>) -> Void) -> BCGAPICore.Operation?
```

### `me(for:dataSet:completion:)`

```swift
public func me(for email: String, dataSet: String, completion: @escaping(Result<EmployeeDetails, Error>) -> Void) -> BCGAPICore.Operation?
```

### `picture(for:completion:)`

```swift
@discardableResult public func picture(for hrid: String, completion: @escaping(Result<Data, Error>) -> Void) -> BCGAPICore.Operation?
```

### `search(text:offset:numberOfRecords:limit:dataSet:completion:)`

```swift
@discardableResult public func search(text: String,
                               offset: Int,
                               numberOfRecords: Int,
                               limit: Int,
                               dataSet: String,
                               completion: @escaping (Result<SearchResults, Error>) -> Void) -> BCGAPICore.Operation?
```
