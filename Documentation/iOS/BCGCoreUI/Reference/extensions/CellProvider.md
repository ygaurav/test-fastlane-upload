**EXTENSION**

# `CellProvider`

## Methods
### `tableView(_:didSelectRowAt:)`

```swift
public func tableView(_ tableView: UITableView, didSelectRowAt indexPath: IndexPath)
```

### `tableView(_:viewForHeaderInSection:)`

```swift
public func tableView(_ tableView: UITableView, viewForHeaderInSection section: Int) -> UIView?
```

### `tableView(_:viewForFooterInSection:)`

```swift
public func tableView(_ tableView: UITableView, viewForFooterInSection section: Int) -> UIView?
```

### `tableView(_:heightForRowAt:)`

```swift
public func tableView(_ tableView: UITableView, heightForRowAt indexPath: IndexPath) -> CGFloat
```

### `tableView(_:estimatedHeightForRowAt:)`

```swift
public func tableView(_ tableView: UITableView, estimatedHeightForRowAt indexPath: IndexPath) -> CGFloat
```

### `tableView(_:heightForHeaderInSection:)`

```swift
public func tableView(_ tableView: UITableView, heightForHeaderInSection section: Int) -> CGFloat
```

### `tableView(_:heightForFooterInSection:)`

```swift
public func tableView(_ tableView: UITableView, heightForFooterInSection section: Int) -> CGFloat
```

### `tableView(_:willDisplay:forRowAt:)`

```swift
public func tableView(_ tableView: UITableView, willDisplay cell: UITableViewCell, forRowAt indexPath: IndexPath)
```

### `tableView(_:willDisplayHeaderView:forSection:)`

```swift
public func tableView(_ tableView: UITableView, willDisplayHeaderView view: UIView, forSection section: Int)
```

### `tableView(_:willDisplayFooterView:forSection:)`

```swift
public func tableView(_ tableView: UITableView, willDisplayFooterView view: UIView, forSection section: Int)
```

### `scrollViewDidScroll(_:)`

```swift
public func scrollViewDidScroll(_ scrollView: UIScrollView)
```

### `numberOfSections(in:)`

```swift
public func numberOfSections(in tableView: UITableView) -> Int
```

### `tableView(_:numberOfRowsInSection:)`

```swift
public func tableView(_ tableView: UITableView, numberOfRowsInSection section: Int) -> Int
```

### `tableView(_:cellForRowAt:)`

```swift
public func tableView(_ tableView: UITableView, cellForRowAt indexPath: IndexPath) -> UITableViewCell
```

### `tableView(_:titleForHeaderInSection:)`

```swift
public func tableView(_ tableView: UITableView, titleForHeaderInSection section: Int) -> String?
```

### `tableView(_:titleForFooterInSection:)`

```swift
public func tableView(_ tableView: UITableView, titleForFooterInSection section: Int) -> String?
```

### `tableView(_:canEditRowAt:)`

```swift
public func tableView(_ tableView: UITableView, canEditRowAt indexPath: IndexPath) -> Bool
```

### `tableView(_:editingStyleForRowAt:)`

```swift
public func tableView(_ tableView: UITableView, editingStyleForRowAt indexPath: IndexPath) -> UITableViewCell.EditingStyle
```

### `tableView(_:commit:forRowAt:)`

```swift
public func tableView(_ tableView: UITableView, commit editingStyle: UITableViewCell.EditingStyle, forRowAt indexPath: IndexPath)
```
