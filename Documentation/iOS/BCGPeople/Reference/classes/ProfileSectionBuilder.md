**CLASS**

# `ProfileSectionBuilder`

```swift
public class ProfileSectionBuilder
```

> **ProfileSectionBuilder** is used to build models used to display different sections in Profile card.
>
> This class provides method which adds section based on parameter they are provided.
> It uses builder pattern to build different section models.
> Order of using these methods define the order of sections.
> Caller can use any & every method to build profile UI in any order.

## Properties
### `headerViewDescriptors`

```swift
public var headerViewDescriptors: [SectionDescriptorType]
```

> Array of SectionDescriptorsType which is used to define section & display its header view containing title etc.
> - important: Without a sectionDescriptorType to define a section, they wont be displayed even if model exists in array returned by *buildSections*

## Methods
### `init(config:)`

```swift
public init(config: ProfileConfiguration)
```

> Initializes and returns a newly allocated builder object with the specified ProfileConfiguration.
> - Parameter config: Configuration providing values like *showWeather, showEvents* required for building profile card sections

#### Parameters

| Name | Description |
| ---- | ----------- |
| config | Configuration providing values like  required for building profile card sections |

### `buildSections()`

```swift
public func buildSections() -> [Section]
```

> - Returns: Array of Section models used by cellProvider to display cells

### `withHeader(forEmployee:withLocation:)`

```swift
public func withHeader(forEmployee employee: Employee, withLocation location: OfficeLocation?) -> ProfileSectionBuilder
```

> Use this method to add header section in profile card. If phone number of employee is in correct format then a cell is added with that.
> - Note: Section Descriptor Type for this section is automatically added when this method is used.
> - Parameters:
>   - employee: Employee whose profile details like name, image, title etc to display on card
>   - location: OfficeLocation to display in cell below employee title. Profile configuration provided in initializer is used to show/hide temperature (*showWeather*) as celsius/fahernheit (*temperatureScale*) on this cell.

#### Parameters

| Name | Description |
| ---- | ----------- |
| employee | Employee whose profile details like name, image, title etc to display on card |
| location | OfficeLocation to display in cell below employee title. Profile configuration provided in initializer is used to show/hide temperature () as celsius/fahernheit () on this cell. |

### `withTeams(of:)`

```swift
public func withTeams(of displayable: TeamDisplayable) -> ProfileSectionBuilder
```

> Use this method to add Teams section in profile card.
> - Attention: This section wont be displayed under following conditions
>     - *showTeams* of profile configuration is **false**
>     - Displayable parameter returns zero teams
> - Note: Section Descriptor Type for this section is automatically added when this method is used.
> - Parameter displayable: Object conforming to TeamDisplayable protocol

#### Parameters

| Name | Description |
| ---- | ----------- |
| displayable | Object conforming to TeamDisplayable protocol |

### `withManager(of:)`

```swift
public func withManager(of displayable: ManagerDisplayable) -> ProfileSectionBuilder
```

> Use this method to add Manager section in profile card.
> - Attention: This section wont be displayed under following conditions
>     - *showManager* of profile configuration is **false**
>     - Displayable parameter returns nil manager object
> - Note: Section Descriptor Type for this section is automatically added when this method is used.
> - Parameter displayable: Object conforming to ManagerDisplayable protocol

#### Parameters

| Name | Description |
| ---- | ----------- |
| displayable | Object conforming to ManagerDisplayable protocol |

### `withReportingLine(of:)`

```swift
public func withReportingLine(of displayable: ReportingLineDisplayable) -> ProfileSectionBuilder
```

> Use this method to add Reporting line section in profile card.
> - Attention: This section wont be displayed under following conditions
>     - *showReportingLine* of profile configuration is **false**
>     - Displayable parameter returns empty employee list
> - Note: Section Descriptor Type for this section is automatically added when this method is used.
> - Parameter displayable: Object conforming to TeamDisplayable protocol

#### Parameters

| Name | Description |
| ---- | ----------- |
| displayable | Object conforming to TeamDisplayable protocol |

### `withPersonalContent(of:)`

```swift
public func withPersonalContent(of employee: Employee) -> ProfileSectionBuilder
```

> Use this method to add Personal content section in profile card.
> ### This includes
> * Blog url  (if url is not nil)
> * Egnyte link (if *showEgnyte* in profile configuration is true)
>
> - Attention: This section wont be displayed if there is neither blog nor egnyte link.
> - Note: Section Descriptor Type for this section is automatically added when this method is used.
> - Parameter employee: Employee object

#### Parameters

| Name | Description |
| ---- | ----------- |
| employee | Employee object |

### `withPracticeAreas(of:)`

```swift
public func withPracticeAreas(of displayable: PracticeAreaDisplayable) -> ProfileSectionBuilder
```

> Use this method to add Practice Area section in profile card.
> - Remark: Practice area is set experience level which is highest amongst its subtopic. Subtpocis are sorted by **name, experience level**.
> - Attention: This section wont be displayed if there isn't any practice area model.
> - Note: Section Descriptor Type for this section is automatically added when this method is used.
> - Parameter displayable: Object conforming to PracticeAreaDisplayable protocol

#### Parameters

| Name | Description |
| ---- | ----------- |
| displayable | Object conforming to PracticeAreaDisplayable protocol |

### `withFunctions(of:)`

```swift
public func withFunctions(of displayable: FunctionalExpertiseDisplayable) -> ProfileSectionBuilder
```

> Use this method to add Function Expertise section in profile card.
> - Remark: Functional expertises are sorted by **experience level**.
> - Attention: This section wont be displayed if there isn't any practice area model.
> - Note: Section Descriptor Type for this section is automatically added when this method is used.
> - Parameter displayable: Object conforming to FunctionalExpertiseDisplayable protocol

#### Parameters

| Name | Description |
| ---- | ----------- |
| displayable | Object conforming to FunctionalExpertiseDisplayable protocol |

### `withProfessionalExperience(of:)`

```swift
public func withProfessionalExperience(of displayable: ProfessionalBackgroundDisplayable) -> ProfileSectionBuilder
```

> Use this method to add Professional Experience section in profile card.
> - Attention: This section wont be displayed if there isn't any professional background model.
> - Note: Section Descriptor Type for this section is automatically added when this method is used.
> - Parameter displayable: Object conforming to ProfessionalBackgroundDisplayable protocol

#### Parameters

| Name | Description |
| ---- | ----------- |
| displayable | Object conforming to ProfessionalBackgroundDisplayable protocol |

### `withEducation(of:)`

```swift
public func withEducation(of displayable: EducationDisplayable) -> ProfileSectionBuilder
```

> Use this method to add Education section in profile card.
> - Attention: This section wont be displayed if there isn't any Education model.
> - Note: Section Descriptor Type for this section is automatically added when this method is used.
> - Parameter displayable: Object conforming to EducationDisplayable protocol

#### Parameters

| Name | Description |
| ---- | ----------- |
| displayable | Object conforming to EducationDisplayable protocol |

### `withLanguages(of:)`

```swift
public func withLanguages(of displayable: LanguageDisplayable) -> ProfileSectionBuilder
```

> Use this method to add Languages section in profile card.
> - Attention: This section wont be displayed if there isn't any Language model.
> - Note: Section Descriptor Type for this section is automatically added when this method is used.
> - Parameter displayable: Object conforming to LanguageDisplayable protocol

#### Parameters

| Name | Description |
| ---- | ----------- |
| displayable | Object conforming to LanguageDisplayable protocol |

### `addCustomSection(withItems:andIdentifier:withSectionHeader:)`

```swift
public func addCustomSection(withItems items: [Any], andIdentifier identifier: String, withSectionHeader sectionHeader: SectionDescriptorType) throws -> ProfileSectionBuilder
```

> Use this method to add Custom section in profile card not predefined in framework.
> - Attention: This section wont be displayed if items list provided is empty.
> - Throws: If section identifier provided conflicts with pre defined identifiers.
> - Parameters:
>   - items: Array of items to be displayed in section cells
>   - identifier: Unique Identifier of section
>   - sectionHeader: SectionDescriptorType which defines the section

#### Parameters

| Name | Description |
| ---- | ----------- |
| items | Array of items to be displayed in section cells |
| identifier | Unique Identifier of section |
| sectionHeader | SectionDescriptorType which defines the section |