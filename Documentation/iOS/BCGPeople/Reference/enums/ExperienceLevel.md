**ENUM**

# `ExperienceLevel`

```swift
public enum ExperienceLevel: String, Comparable, CaseIterable
```

## Cases
### `any`

```swift
case any = "Any"
```

### `advanced`

```swift
case advanced = "Advanced"
```

### `experienced`

```swift
case experienced = "Experienced"
```

### `basic`

```swift
case basic = "Basic"
```

### `none`

```swift
case none = "None"
```

## Methods
### `<(_:_:)`

```swift
static public func < (lhs: ExperienceLevel, rhs: ExperienceLevel) -> Bool
```

#### Parameters

| Name | Description |
| ---- | ----------- |
| lhs | A value to compare. |
| rhs | Another value to compare. |