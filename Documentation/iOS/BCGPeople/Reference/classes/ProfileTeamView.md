**CLASS**

# `ProfileTeamView`

```swift
public final class ProfileTeamView: UIView
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

### `init(title:teams:navigationController:service:userServives:configurationData:selectedEmployeeCallBack:)`

```swift
public convenience init(title: String,
                         teams: [Team],
                         navigationController: UINavigationController,
                         service: Services, userServives: UserServices, configurationData: TeamsConfigurationsData,
                         selectedEmployeeCallBack: @escaping EmployeeDetailDisplayDelegate)
```

### `layoutSubviews()`

```swift
public override func layoutSubviews()
```
