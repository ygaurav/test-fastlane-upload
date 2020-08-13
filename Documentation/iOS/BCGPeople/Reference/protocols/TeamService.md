**PROTOCOL**

# `TeamService`

```swift
public protocol TeamService
```

## Methods
### `allTeams(completion:)`

```swift
@discardableResult func allTeams(completion: @escaping(Result<AllTeamResult, Error>) -> Void) -> BCGAPICore.Operation?
```

### `teams(forEmployeeId:completion:)`

```swift
@discardableResult func teams(forEmployeeId: String, completion: @escaping(Result<ProfileTeamResult, Error>) -> Void) -> BCGAPICore.Operation?
```

### `team(withID:completion:)`

```swift
@discardableResult func team(withID: String, completion: @escaping(Result<AddTeamResult, Error>) -> Void) -> BCGAPICore.Operation?
```

### `teamMembers(withIDs:completion:)`

```swift
@discardableResult func teamMembers(withIDs: [String], completion: @escaping(Result<TeamsEmployeeDetails, Error>) -> Void) -> BCGAPICore.Operation?
```

### `delete(teamId:completion:)`

```swift
@discardableResult func delete(teamId: String, completion: @escaping(Result<DeleteTeamResponse, Error>) -> Void) -> BCGAPICore.Operation?
```

### `update(team:completion:)`

```swift
@discardableResult func update(team: Team, completion: @escaping(Result<UpdateTeamResult, Error>) -> Void) -> BCGAPICore.Operation?
```

### `add(team:completion:)`

```swift
@discardableResult func add(team: Team, completion: @escaping(Result<AddTeamResult, Error>) -> Void) -> BCGAPICore.Operation?
```
