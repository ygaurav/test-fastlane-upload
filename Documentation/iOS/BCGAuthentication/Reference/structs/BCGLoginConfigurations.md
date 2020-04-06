**STRUCT**

# `BCGLoginConfigurations`

```swift
public struct BCGLoginConfigurations: APIConfiguration, AuthenticationConfiguration
```

> Configuraton settings that need to be passed for perfect authentication

## Properties
### `appVersion`

```swift
public var appVersion: String = "1.0"
```

> String value denoting the version of the app. Default is "1.0"

### `language`

```swift
public var language: String = "en-UK"
```

> String value denoting the language of the app. Default is "en-UK"

### `apiKey`

```swift
public var apiKey: String
```

> Pass the proper string accoring to the environment configured i.e prod, pre-prod etc

### `apiVersion`

```swift
public var apiVersion: String
```

> String value to specify the version of the API

### `baseURL`

```swift
public var baseURL: URL
```

> String value to specify the baseURL for the API

### `pinningConfigurationKeys`

```swift
public var pinningConfigurationKeys: [String]
```

> Array of string to specify the pinning keys use for SSLPinning. This is used to prevent the **MITM** attack.
>
> - note: The authentication will fail if the keys specified does not match to keys that we get for the host during authentication challenge

### `applicationGroupIdentifier`

```swift
public let applicationGroupIdentifier: String = "R4DPX84QP9.BCGKeychainGroup"
```

> application group Identifier

### `keychainAccessGroup`

```swift
public let keychainAccessGroup: String = "group.com.bcg.macoe"
```

> keychain group Identifier

## Methods
### `init(pinKeys:keychainConfiguration:apiKey:baseURL:apiVersion:)`

```swift
public init(pinKeys: [String], keychainConfiguration: KeychainConfiguration, apiKey: String, baseURL: URL, apiVersion: String)
```

> SwifterSwift: Initializes & returns **BCGLoginConfigurations** object
>
> - Parameters:
>   - pinKeys: Pinkeys used for SSLPinning. For more info please refer to: ["SSLPinning with public pinning keys"](https://tools.ietf.org/html/rfc7469 "Title") has a title attribute.
>
>   - keychainConfiguration: keychainConfiguration
>   - apiKeys: apiKey passed as header parameter for the login api
>   - baseURL: baseURL of login api
>   - apiVersion: apiVersion of the login api

#### Parameters

| Name | Description |
| ---- | ----------- |
| pinKeys | Pinkeys used for SSLPinning. For more info please refer to:  has a title attribute. |
| keychainConfiguration | keychainConfiguration |
| apiKeys | apiKey passed as header parameter for the login api |
| baseURL | baseURL of login api |
| apiVersion | apiVersion of the login api |