<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@firebase/remote-config](./remote-config.md) &gt; [RemoteConfig](./remote-config.remoteconfig.md)

## RemoteConfig interface

The Firebase Remote Config service interface.

<b>Signature:</b>

```typescript
export interface RemoteConfig 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [defaultConfig](./remote-config.remoteconfig.defaultconfig.md) | { \[key: string\]: string \| number \| boolean; } | Object containing default values for conigs. |
|  [fetchTimeMillis](./remote-config.remoteconfig.fetchtimemillis.md) | number | The Unix timestamp in milliseconds of the last <i>successful</i> fetch, or negative one if the [RemoteConfig](./remote-config.remoteconfig.md) instance either hasn't fetched or initialization is incomplete. |
|  [lastFetchStatus](./remote-config.remoteconfig.lastfetchstatus.md) | [FetchStatus](./remote-config.fetchstatus.md) | The status of the last fetch <i>attempt</i>. |
|  [settings](./remote-config.remoteconfig.settings.md) | [Settings](./remote-config.settings.md) | Defines configuration for the Remote Config SDK. |
