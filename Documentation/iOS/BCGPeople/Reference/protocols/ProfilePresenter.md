**PROTOCOL**

# `ProfilePresenter`

```swift
public protocol ProfilePresenter: ProfileContactCellDelegate, AssistantCellDelegate, BasicEmployeeCellDelegate, ProfileLocationCellDelegate, ProfileStandardCellDelegate, ProfileHeaderCellDelegate
```

## Properties
### `pictureService`

```swift
var pictureService: PictureService
```

### `spotlightIndexer`

```swift
var spotlightIndexer: SpotlightContactIndexer
```

## Methods
### `fetchProfile()`

```swift
func fetchProfile()
```

### `supplementaryViewProvider()`

```swift
func supplementaryViewProvider() -> UICollectionViewDiffableDataSource<IdentifiableSection, IdentifiableItem>.SupplementaryViewProvider?
```
