**EXTENSION**

# `Date`

## Properties
### `startOfDay`

```swift
public var startOfDay: Date
```

### `endOfDay`

```swift
public var endOfDay: Date
```

## Methods
### `shortSymbolMonth(timeZone:)`

```swift
public func shortSymbolMonth(timeZone identifier: String) -> String
```

### `dayOfMonth(timeZone:)`

```swift
public func dayOfMonth(timeZone identifier: String) -> Int
```

### `monthForDate(timeZone:)`

```swift
public func monthForDate(timeZone identifier: String) -> Int
```

### `startOfDayTimeInterval(timeZoneID:)`

```swift
public func startOfDayTimeInterval(timeZoneID: String) -> TimeInterval
```

### `setTime(hour:minute:seconds:timeZoneIdentifier:)`

```swift
public func setTime(hour: Int, minute: Int, seconds: Int = 0, timeZoneIdentifier: String? = nil) -> Date?
```

### `hours(timeZone:)`

```swift
public func hours(timeZone: String) -> Int
```

### `minutes(timeZone:)`

```swift
public func minutes(timeZone: String) -> Int
```

### `days(from:timeZoneID:)`

```swift
public func days(from date: Date, timeZoneID: String) -> Int
```

> Returns the number of days between 2 dates

### `startOfDayDate(withTimeZone:mode:)`

```swift
public func startOfDayDate(withTimeZone: String,
                           mode: UIDatePicker.Mode = .date) -> Date?
```

### `endOfDayDate(withTimeZone:mode:)`

```swift
public func endOfDayDate(withTimeZone: String, mode: UIDatePicker.Mode = .date) -> Date?
```
