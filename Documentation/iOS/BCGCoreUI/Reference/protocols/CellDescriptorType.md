**PROTOCOL**

# `CellDescriptorType`

```swift
public protocol CellDescriptorType
```

## Properties
### `rowIdentifier`

```swift
var rowIdentifier: String
```

### `cellIdentifier`

```swift
var cellIdentifier: String
```

### `nibName`

```swift
var nibName: String?
```

### `cellClass`

```swift
var cellClass: UITableViewCell.Type
```

### `configureClosure`

```swift
var configureClosure: ((RowType, UITableViewCell, IndexPath) -> Void)?
```

### `canEditClosure`

```swift
var canEditClosure: ((RowType, IndexPath) -> Bool)?
```

### `canMoveClosure`

```swift
var canMoveClosure: ((RowType, IndexPath) -> Bool)?
```

### `commitEditingClosure`

```swift
var commitEditingClosure: ((RowType, UITableViewCell.EditingStyle, IndexPath) -> Void)?
```

### `moveRowClosure`

```swift
var moveRowClosure: ((RowType, (IndexPath, IndexPath)) -> Void)?
```

### `heightClosure`

```swift
var heightClosure: ((RowType, IndexPath) -> CGFloat)?
```

### `estimatedHeightClosure`

```swift
var estimatedHeightClosure: ((RowType, IndexPath) -> CGFloat)?
```

### `shouldHighlightClosure`

```swift
var shouldHighlightClosure: ((RowType, IndexPath) -> Bool)?
```

### `didHighlightClosure`

```swift
var didHighlightClosure: ((RowType, IndexPath) -> Void)?
```

### `didUnhighlightClosure`

```swift
var didUnhighlightClosure: ((RowType, IndexPath) -> Void)?
```

### `willSelectClosure`

```swift
var willSelectClosure: ((RowType, IndexPath) -> IndexPath?)?
```

### `willDeselectClosure`

```swift
var willDeselectClosure: ((RowType, IndexPath) -> IndexPath?)?
```

### `didSelectClosure`

```swift
var didSelectClosure: ((RowType, IndexPath) -> SelectionResult)?
```

### `didDeselectClosure`

```swift
var didDeselectClosure: ((RowType, IndexPath) -> Void)?
```

### `willDisplayClosure`

```swift
var willDisplayClosure: ((RowType, UITableViewCell, IndexPath) -> Void)?
```

### `editingStyleClosure`

```swift
var editingStyleClosure: ((RowType, IndexPath) -> UITableViewCell.EditingStyle)?
```

### `titleForDeleteConfirmationButtonClosure`

```swift
var titleForDeleteConfirmationButtonClosure: ((RowType, IndexPath) -> String?)?
```

### `shouldIndentWhileEditingClosure`

```swift
var shouldIndentWhileEditingClosure: ((RowType, IndexPath) -> Bool)?
```

### `willBeginEditingClosure`

```swift
var willBeginEditingClosure: ((RowType, IndexPath) -> Void)?
```

### `targetIndexPathForMoveClosure`

```swift
var targetIndexPathForMoveClosure: ((RowType, (IndexPath, IndexPath)) -> IndexPath)?
```

### `indentationLevelClosure`

```swift
var indentationLevelClosure: ((RowType, IndexPath) -> Int)?
```

### `shouldShowMenuClosure`

```swift
var shouldShowMenuClosure: ((RowType, IndexPath) -> Bool)?
```

### `canPerformActionClosure`

```swift
var canPerformActionClosure: ((RowType, Selector, Any?, IndexPath) -> Bool)?
```

### `performActionClosure`

```swift
var performActionClosure: ((RowType, Selector, Any?, IndexPath) -> Void)?
```

### `canFocusClosure`

```swift
var canFocusClosure: ((RowType, IndexPath) -> Bool)?
```
