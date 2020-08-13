**PROTOCOL**

# `ProfileConfiguration`

```swift
public protocol ProfileConfiguration
```

>  **ProfileSectionBuilder** are initialized by objects conforming to this protocol.
>
>  They provide values for following properties which are used by ProfileSectionBuilder to configure UI of Profile Card
>  - **showWeather** : Used to show/hide weather on the profile card
>  - **temperatureScale** : Used to show celsius if true, fahrenheit if false
>  - **showAffiliations** : Used to show/hide affiliations
>  - **showTeams** : Used to show/hide teams associated with profile
>  - **showManager** : Used to show/hide manager associated with profile
>  - **showReportingLine** : Used to show/hide reporting line associated with profile
>  - **showEgnyte** : Used to show/hide egnyte link associated with profile
>  - **showEvents** : Used to show/hide events associated with profile
>  ### Example
>  ````
> struct TestConfiguration: ProfileConfiguration {
>     var showWeather: Bool = true
>     var temperatureScale: Bool = false
>     var showAffiliations: Bool = false
>     var showTeams: Bool = false
>     var showManager: Bool = true
>     var showReportingLine: Bool = true
>     var showEgnyte: Bool = false
>     var showEvents: Bool = true
> }
> ````

## Properties
### `showWeather`

```swift
var showWeather: Bool
```

### `temperatureScale`

```swift
var temperatureScale: Bool
```

### `showAffiliations`

```swift
var showAffiliations: Bool
```

### `showTeams`

```swift
var showTeams: Bool
```

### `showManager`

```swift
var showManager: Bool
```

### `showReportingLine`

```swift
var showReportingLine: Bool
```

### `showEgnyte`

```swift
var showEgnyte: Bool
```

### `showEvents`

```swift
var showEvents: Bool
```

### `userId`

```swift
var userId: String
```

### `dataSet`

```swift
var dataSet: EmployeeDataSet
```

### `barButtonOptions`

```swift
var barButtonOptions: ProfileBarButtons
```

### `displayContactOptions`

```swift
var displayContactOptions: ContactOptions
```

### `disableContactOptionsOverride`

```swift
var disableContactOptionsOverride: ContactOptions
```
