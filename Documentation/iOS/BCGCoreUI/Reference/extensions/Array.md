**EXTENSION**

# `Array`

## Properties
### `overlappingPairs`

```swift
public var overlappingPairs: [(first: Element, second: Element)]
```

> Returns an array of overlapping pairs of elements.
> For example, given the array: [1, 2, 3, 4], it will return: [(1, 2), (2, 3), (3, 4)].

## Methods
### `toDictionary(keySelector:)`

```swift
public func toDictionary<TKey: Hashable>(keySelector: (Element) -> TKey ) -> [TKey: [Element]]
```

### `groupBy(keySelector:)`

```swift
public func groupBy<TKey: Hashable>(keySelector: (Element) -> TKey ) -> [Grouping<TKey, Element>]
```

### `groupBy(keySelector:isOrderedBefore:)`

```swift
public func groupBy<TKey: Hashable>(keySelector: (Element) -> TKey, isOrderedBefore sorter: (TKey, TKey) -> (Bool) ) -> [Grouping<TKey, Element>]
```

### `filterAndMap(map:)`

```swift
public func filterAndMap<Result>(map: (Element) -> Result?  ) -> [Result]
```

### `unique(keySelector:)`

```swift
public func unique<E: Hashable>(keySelector: (Element) -> E  ) -> [Element]
```

### `unique()`

```swift
public func unique() -> [Element]
```

### `group(by:)`

```swift
public func group<Key>(by computedKey: (Element) -> Key) -> [Key: [Element]]
```

### `removeFirst(where:)`

```swift
public mutating func removeFirst(where predicate: (Element) -> Bool)
```
