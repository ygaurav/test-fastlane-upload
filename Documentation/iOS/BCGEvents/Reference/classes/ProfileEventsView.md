**CLASS**

# `ProfileEventsView`

```swift
public final class ProfileEventsView: UIView
```

## Methods
### `init(frame:)`

```swift
public override init(frame: CGRect)
```

### `init(coder:)`

```swift
public required init?(coder aDecoder: NSCoder)
```

### `init(title:events:navigationController:service:configurationData:selectedEmployeeCallBack:)`

```swift
public convenience init(title: String,
                        events: [Event],
                        navigationController: UINavigationController,
                        service: Services,
                        configurationData: EventsConfigurationsData,
                        selectedEmployeeCallBack: @escaping EmployeeDetailDisplayDelegate)
```

### `init(title:events:navigationController:service:configurationData:userEmail:userName:selectedEmployeeCallBack:)`

```swift
public convenience init(title: String,
                        events: [Event],
                        navigationController: UINavigationController,
                        service: Services,
                        configurationData: EventsConfigurationsData,
                        userEmail: String,
                        userName: String,
                        selectedEmployeeCallBack: @escaping EmployeeDetailDisplayDelegate)
```

### `layoutSubviews()`

```swift
public override func layoutSubviews()
```

### `addNewEvent()`

```swift
public func addNewEvent()
```
