**CLASS**

# `ProfileEventCell`

```swift
public class ProfileEventCell: UICollectionViewCell
```

## Properties
### `titleLabel`

```swift
@IBOutlet public weak var titleLabel: UILabel!
```

### `delegate`

```swift
public weak var delegate: ProfileEventCellDelegate?
```

### `eventService`

```swift
public var eventService: EventsService?
```

### `configuration`

```swift
public var configuration: EventsConfigurationsData?
```

### `hideAddEventButton`

```swift
public var hideAddEventButton: Bool = false
```

## Methods
### `awakeFromNib()`

```swift
public override func awakeFromNib()
```

### `prepareForReuse()`

```swift
public override func prepareForReuse()
```

### `loadEvents(forEmployeeId:userId:inTimeZone:)`

```swift
public func loadEvents(forEmployeeId employeeId: String, userId: String, inTimeZone timeZone: String)
```
