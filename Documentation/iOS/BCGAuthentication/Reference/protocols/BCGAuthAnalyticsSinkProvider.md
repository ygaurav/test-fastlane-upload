**PROTOCOL**

# `BCGAuthAnalyticsSinkProvider`

```swift
public protocol BCGAuthAnalyticsSinkProvider
```

## Methods
### `logEvent(_:parameters:description:)`

```swift
func logEvent(_ : String, parameters: [String: Any], description: String)
```

### `logEvent(named:parameters:description:)`

```swift
func logEvent(named: String, parameters: [String: Any], description: String)
```

> This method is invoked to sink all the analytics event originating from within auth framework to the sink
> - Parameters:
>   - event: Event to log
>   - parameters: Any parameters related to event
>   - description: Any detailed description not to be captured as params of the event.

#### Parameters

| Name | Description |
| ---- | ----------- |
| event | Event to log |
| parameters | Any parameters related to event |
| description | Any detailed description not to be captured as params of the event. |