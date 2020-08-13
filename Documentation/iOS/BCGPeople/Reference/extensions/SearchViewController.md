**EXTENSION**

# `SearchViewController`

## Methods
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

### `tableView(_:didSelectRowAt:)`

```swift
public func tableView(_ tableView: UITableView, didSelectRowAt indexPath: IndexPath)
```

### `scrollViewDidScroll(_:)`

```swift
public func scrollViewDidScroll(_ scrollView: UIScrollView)
```

### `tableView(_:heightForRowAt:)`

```swift
public func tableView(_ tableView: UITableView, heightForRowAt indexPath: IndexPath) -> CGFloat
```

### `tableView(_:estimatedHeightForRowAt:)`

```swift
public func tableView(_ tableView: UITableView, estimatedHeightForRowAt indexPath: IndexPath) -> CGFloat
```

### `searchBarCancelButtonClicked(_:)`

```swift
public func searchBarCancelButtonClicked(_ searchBar: UISearchBar)
```

### `searchBar(_:shouldChangeTextIn:replacementText:)`

```swift
public func searchBar(_ searchBar: UISearchBar, shouldChangeTextIn range: NSRange, replacementText text: String) -> Bool
```

### `searchBarSearchButtonClicked(_:)`

```swift
public func searchBarSearchButtonClicked(_ searchBar: UISearchBar)
```

### `searchBarShouldBeginEditing(_:)`

```swift
public func searchBarShouldBeginEditing(_ searchBar: UISearchBar) -> Bool
```

### `searchBar(_:textDidChange:)`

```swift
public func searchBar(_ searchBar: UISearchBar, textDidChange searchText: String)
```

### `present(_:for:)`

```swift
public func present(_ addVoiceShortcutViewController: INUIAddVoiceShortcutViewController, for addVoiceShortcutButton: INUIAddVoiceShortcutButton)
```

### `present(_:for:)`

```swift
public func present(_ editVoiceShortcutViewController: INUIEditVoiceShortcutViewController, for addVoiceShortcutButton: INUIAddVoiceShortcutButton)
```

### `addVoiceShortcutViewController(_:didFinishWith:error:)`

```swift
public func addVoiceShortcutViewController(_ controller: INUIAddVoiceShortcutViewController, didFinishWith voiceShortcut: INVoiceShortcut?, error: Error?)
```

### `addVoiceShortcutViewControllerDidCancel(_:)`

```swift
public func addVoiceShortcutViewControllerDidCancel(_ controller: INUIAddVoiceShortcutViewController)
```

### `editVoiceShortcutViewController(_:didUpdate:error:)`

```swift
public func editVoiceShortcutViewController(_ controller: INUIEditVoiceShortcutViewController, didUpdate voiceShortcut: INVoiceShortcut?, error: Error?)
```

### `editVoiceShortcutViewController(_:didDeleteVoiceShortcutWithIdentifier:)`

```swift
public func editVoiceShortcutViewController(_ controller: INUIEditVoiceShortcutViewController, didDeleteVoiceShortcutWithIdentifier deletedVoiceShortcutIdentifier: UUID)
```

### `editVoiceShortcutViewControllerDidCancel(_:)`

```swift
public func editVoiceShortcutViewControllerDidCancel(_ controller: INUIEditVoiceShortcutViewController)
```
