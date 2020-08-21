**PROTOCOL**

# `ProfilePresenter`

```swift
public protocol ProfilePresenter: ProfileContactCellDelegate, AssistantCellDelegate, BasicEmployeeCellDelegate, ProfileLocationCellDelegate, ProfileStandardCellDelegate
```

## Properties
### `pictureService`

```swift
var pictureService: PictureService
```

### `spotlightIndexer`

```swift
var spotlightIndexer: EmployeeImageIndexer
```

## Methods
### `fetchProfile()`

```swift
func fetchProfile()
```

### `favoriteTapped()`

```swift
func favoriteTapped()
```

### `generateEmployeeContact()`

```swift
func generateEmployeeContact() -> URL?
```

### `supplementaryViewProvider()`

```swift
func supplementaryViewProvider() -> UICollectionViewDiffableDataSource<IdentifiableSection, IdentifiableItem>.SupplementaryViewProvider?
```
