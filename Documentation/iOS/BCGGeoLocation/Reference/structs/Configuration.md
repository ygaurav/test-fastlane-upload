**STRUCT**

# `Configuration`

```swift
public struct Configuration: Codable
```

## Properties
### `adminEmail`

```swift
public let adminEmail: String?
```

### `adminTeamName`

```swift
public let adminTeamName: String?
```

### `poolName`

```swift
public let poolName: String?
```

### `officeSpaceGuidelines`

```swift
public let officeSpaceGuidelines: String?
```

### `healthReportingEnabled`

```swift
public let healthReportingEnabled: Bool
```

### `checkinEnabled`

```swift
public let checkinEnabled: Bool
```

### `requestASeatOption`

```swift
public let requestASeatOption: RequestASeatOption
```

### `enableAddPeopleToPending`

```swift
public let enableAddPeopleToPending: Bool
```

## Methods
### `init(adminEmail:adminTeamName:poolName:officeSpaceGuidelines:healthReportingEnabled:checkinEnabled:requestASeatOption:enableAddPeopleToPending:)`

```swift
public init(adminEmail: String? = nil,
            adminTeamName: String? = nil,
            poolName: String? = nil,
            officeSpaceGuidelines: String? = nil,
            healthReportingEnabled: Bool = false,
            checkinEnabled: Bool = true,
            requestASeatOption: RequestASeatOption = .alert,
            enableAddPeopleToPending: Bool = false)
```
