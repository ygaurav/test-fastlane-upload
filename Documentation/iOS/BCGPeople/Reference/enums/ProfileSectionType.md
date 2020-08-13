**ENUM**

# `ProfileSectionType`

```swift
public enum ProfileSectionType: String, CaseIterable
```

> Pre-defined table sections in framework.

## Cases
### `header`

```swift
case header = "employee-profile-details"
```

### `location`

```swift
case location = "employee-profile-location"
```

### `teams`

```swift
case teams = "employee-profile-teams"
```

### `manager`

```swift
case manager = "employee-profile-manager"
```

### `reportingLine`

```swift
case reportingLine = "employee-profile-reporting-line"
```

### `personalContent`

```swift
case personalContent = "employee-profile-personal-blog"
```

### `practiceArea`

```swift
case practiceArea = "employee-profile-practice-area"
```

### `functionArea`

```swift
case functionArea = "employee-profile-function-area"
```

### `professionalExperience`

```swift
case professionalExperience = "employee-profile-professional-experience"
```

### `education`

```swift
case education = "employee-profile-education"
```

### `languages`

```swift
case languages = "employee-profile-languages"
```

## Properties
### `identifier`

```swift
public var identifier: String
```

## Methods
### `hasConflicting(identifier:)`

```swift
public static func hasConflicting(identifier: String) -> Bool
```

> Use this method to check if section identifier already exists when someone tries to add custom section
> - Parameter identifier: Section identifier to check for conflict

#### Parameters

| Name | Description |
| ---- | ----------- |
| identifier | Section identifier to check for conflict |