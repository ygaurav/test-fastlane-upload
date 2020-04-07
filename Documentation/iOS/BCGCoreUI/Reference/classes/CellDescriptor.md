**CLASS**

# `CellDescriptor`

```swift
public class CellDescriptor<Item, Cell: UITableViewCell>: CellDescriptorType
```

## Properties
### `rowIdentifier`

```swift
public let rowIdentifier: String
```

### `cellIdentifier`

```swift
public let cellIdentifier: String
```

### `nibName`

```swift
public let nibName: String?
```

### `cellClass`

```swift
public let cellClass: UITableViewCell.Type
```

### `configureClosure`

```swift
public private(set) var configureClosure: ((RowType, UITableViewCell, IndexPath) -> Void)?
```

### `canEditClosure`

```swift
public private(set) var canEditClosure: ((RowType, IndexPath) -> Bool)?
```

### `canMoveClosure`

```swift
public private(set) var canMoveClosure: ((RowType, IndexPath) -> Bool)?
```

### `heightClosure`

```swift
public private(set) var heightClosure: ((RowType, IndexPath) -> CGFloat)?
```

### `estimatedHeightClosure`

```swift
public private(set) var estimatedHeightClosure: ((RowType, IndexPath) -> CGFloat)?
```

### `commitEditingClosure`

```swift
public private(set) var commitEditingClosure: ((RowType, UITableViewCell.EditingStyle, IndexPath) -> Void)?
```

### `moveRowClosure`

```swift
public private(set) var moveRowClosure: ((RowType, (IndexPath, IndexPath)) -> Void)?
```

### `shouldHighlightClosure`

```swift
public private(set) var shouldHighlightClosure: ((RowType, IndexPath) -> Bool)?
```

### `didHighlightClosure`

```swift
public private(set) var didHighlightClosure: ((RowType, IndexPath) -> Void)?
```

### `didUnhighlightClosure`

```swift
public private(set) var didUnhighlightClosure: ((RowType, IndexPath) -> Void)?
```

### `willSelectClosure`

```swift
public private(set) var willSelectClosure: ((RowType, IndexPath) -> IndexPath?)?
```

### `willDeselectClosure`

```swift
public private(set) var willDeselectClosure: ((RowType, IndexPath) -> IndexPath?)?
```

### `didSelectClosure`

```swift
public private(set) var didSelectClosure: ((RowType, IndexPath) -> SelectionResult)?
```

### `didDeselectClosure`

```swift
public private(set) var didDeselectClosure: ((RowType, IndexPath) -> Void)?
```

### `willDisplayClosure`

```swift
public private(set) var willDisplayClosure: ((RowType, UITableViewCell, IndexPath) -> Void)?
```

### `editingStyleClosure`

```swift
public private(set) var editingStyleClosure: ((RowType, IndexPath) -> UITableViewCell.EditingStyle)?
```

### `titleForDeleteConfirmationButtonClosure`

```swift
public private(set) var titleForDeleteConfirmationButtonClosure: ((RowType, IndexPath) -> String?)?
```

### `shouldIndentWhileEditingClosure`

```swift
public private(set) var shouldIndentWhileEditingClosure: ((RowType, IndexPath) -> Bool)?
```

### `willBeginEditingClosure`

```swift
public private(set) var willBeginEditingClosure: ((RowType, IndexPath) -> Void)?
```

### `targetIndexPathForMoveClosure`

```swift
public private(set) var targetIndexPathForMoveClosure: ((RowType, (IndexPath, IndexPath)) -> IndexPath)?
```

### `indentationLevelClosure`

```swift
public private(set) var indentationLevelClosure: ((RowType, IndexPath) -> Int)?
```

### `shouldShowMenuClosure`

```swift
public private(set) var shouldShowMenuClosure: ((RowType, IndexPath) -> Bool)?
```

### `canPerformActionClosure`

```swift
public private(set) var canPerformActionClosure: ((RowType, Selector, Any?, IndexPath) -> Bool)?
```

### `performActionClosure`

```swift
public private(set) var performActionClosure: ((RowType, Selector, Any?, IndexPath) -> Void)?
```

### `canFocusClosure`

```swift
public private(set) var canFocusClosure: ((RowType, IndexPath) -> Bool)?
```

## Methods
### `init(_:cellIdentifier:nibName:)`

```swift
public init(_ rowIdentifier: String? = nil, cellIdentifier: String? = nil, nibName: String? = nil)
```

### `configure(_:)`

```swift
public func configure(_ closure: @escaping (Item, Cell, IndexPath) -> Void) -> CellDescriptor
```

### `canEdit(_:)`

```swift
public func canEdit(_ closure: @escaping (Item, IndexPath) -> Bool) -> CellDescriptor
```

### `canEdit(_:)`

```swift
public func canEdit(_ closure: @escaping () -> Bool) -> CellDescriptor
```

### `canMove(_:)`

```swift
public func canMove(_ closure: @escaping (Item, IndexPath) -> Bool) -> CellDescriptor
```

### `canMove(_:)`

```swift
public func canMove(_ closure: @escaping () -> Bool) -> CellDescriptor
```

### `height(_:)`

```swift
public func height(_ closure: @escaping (Item, IndexPath) -> CGFloat) -> CellDescriptor
```

### `height(_:)`

```swift
public func height(_ closure: @escaping () -> CGFloat) -> CellDescriptor
```

### `estimatedHeight(_:)`

```swift
public func estimatedHeight(_ closure: @escaping (Item, IndexPath) -> CGFloat) -> CellDescriptor
```

### `estimatedHeight(_:)`

```swift
public func estimatedHeight(_ closure: @escaping () -> CGFloat) -> CellDescriptor
```

### `commitEditing(_:)`

```swift
public func commitEditing(_ closure: @escaping (Item, UITableViewCell.EditingStyle, IndexPath) -> Void) -> CellDescriptor
```

### `moveRow(_:)`

```swift
public func moveRow(_ closure: @escaping (Item, (IndexPath, IndexPath)) -> Void) -> CellDescriptor
```

### `shouldHighlight(_:)`

```swift
public func shouldHighlight(_ closure: @escaping (Item, IndexPath) -> Bool) -> CellDescriptor
```

### `shouldHighlight(_:)`

```swift
public func shouldHighlight(_ closure: @escaping () -> Bool) -> CellDescriptor
```

### `didHighlight(_:)`

```swift
public func didHighlight(_ closure: @escaping (Item, IndexPath) -> Void) -> CellDescriptor
```

### `didHighlight(_:)`

```swift
public func didHighlight(_ closure: @escaping () -> Void) -> CellDescriptor
```

### `didUnhighlight(_:)`

```swift
public func didUnhighlight(_ closure: @escaping (Item, IndexPath) -> Void) -> CellDescriptor
```

### `didUnhighlight(_:)`

```swift
public func didUnhighlight(_ closure: @escaping () -> Void) -> CellDescriptor
```

### `willSelect(_:)`

```swift
public func willSelect(_ closure: @escaping (Item, IndexPath) -> IndexPath?) -> CellDescriptor
```

### `willSelect(_:)`

```swift
public func willSelect(_ closure: @escaping () -> IndexPath?) -> CellDescriptor
```

### `willDeselect(_:)`

```swift
public func willDeselect(_ closure: @escaping (Item, IndexPath) -> IndexPath?) -> CellDescriptor
```

### `willDeselect(_:)`

```swift
public func willDeselect(_ closure: @escaping () -> IndexPath?) -> CellDescriptor
```

### `didSelect(_:)`

```swift
public func didSelect(_ closure: @escaping (Item, IndexPath) -> SelectionResult) -> CellDescriptor
```

### `didSelect(_:)`

```swift
public func didSelect(_ closure: @escaping () -> SelectionResult) -> CellDescriptor
```

### `didDeselect(_:)`

```swift
public func didDeselect(_ closure: @escaping (Item, IndexPath) -> Void) -> CellDescriptor
```

### `didDeselect(_:)`

```swift
public func didDeselect(_ closure: @escaping () -> Void) -> CellDescriptor
```

### `willDisplay(_:)`

```swift
public func willDisplay(_ closure: @escaping (Item, Cell, IndexPath) -> Void) -> CellDescriptor
```

### `editingStyle(_:)`

```swift
public func editingStyle(_ closure: @escaping (Item, IndexPath) -> UITableViewCell.EditingStyle) -> CellDescriptor
```

### `editingStyle(_:)`

```swift
public func editingStyle(_ closure: @escaping () -> UITableViewCell.EditingStyle) -> CellDescriptor
```

### `titleForDeleteConfirmationButton(_:)`

```swift
public func titleForDeleteConfirmationButton(_ closure: @escaping (Item, IndexPath) -> String?) -> CellDescriptor
```

### `titleForDeleteConfirmationButton(_:)`

```swift
public func titleForDeleteConfirmationButton(_ closure: @escaping () -> String?) -> CellDescriptor
```

### `shouldIndentWhileEditing(_:)`

```swift
public func shouldIndentWhileEditing(_ closure: @escaping (Item, IndexPath) -> Bool) -> CellDescriptor
```

### `shouldIndentWhileEditing(_:)`

```swift
public func shouldIndentWhileEditing(_ closure: @escaping () -> Bool) -> CellDescriptor
```

### `willBeginEditing(_:)`

```swift
public func willBeginEditing(_ closure: @escaping (Item, IndexPath) -> Void) -> CellDescriptor
```

### `willBeginEditing(_:)`

```swift
public func willBeginEditing(_ closure: @escaping () -> Void) -> CellDescriptor
```

### `targetIndexPathForMove(_:)`

```swift
public func targetIndexPathForMove(_ closure: @escaping (Item, (IndexPath, IndexPath)) -> IndexPath) -> CellDescriptor
```

### `indentationLevel(_:)`

```swift
public func indentationLevel(_ closure: @escaping (Item, IndexPath) -> Int) -> CellDescriptor
```

### `indentationLevel(_:)`

```swift
public func indentationLevel(_ closure: @escaping () -> Int) -> CellDescriptor
```

### `shouldShowMenu(_:)`

```swift
public func shouldShowMenu(_ closure: @escaping (Item, IndexPath) -> Bool) -> CellDescriptor
```

### `shouldShowMenu(_:)`

```swift
public func shouldShowMenu(_ closure: @escaping () -> Bool) -> CellDescriptor
```

### `canPerformAction(_:)`

```swift
public func canPerformAction(_ closure: @escaping (Item, Selector, Any?, IndexPath) -> Bool) -> CellDescriptor
```

### `canPerformAction(_:)`

```swift
public func canPerformAction(_ closure: @escaping (Selector, Any?) -> Bool) -> CellDescriptor
```

### `performAction(_:)`

```swift
public func performAction(_ closure: @escaping (Item, Selector, Any?, IndexPath) -> Void) -> CellDescriptor
```

### `performAction(_:)`

```swift
public func performAction(_ closure: @escaping (Selector, Any?) -> Void) -> CellDescriptor
```

### `canFocus(_:)`

```swift
public func canFocus(_ closure: @escaping (Item, IndexPath) -> Bool) -> CellDescriptor
```

### `canFocus(_:)`

```swift
public func canFocus(_ closure: @escaping () -> Bool) -> CellDescriptor
```
