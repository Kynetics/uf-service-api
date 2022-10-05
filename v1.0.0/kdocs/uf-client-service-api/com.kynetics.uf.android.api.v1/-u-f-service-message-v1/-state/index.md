[uf-client-service-api](../../../index.md) / [com.kynetics.uf.android.api.v1](../../index.md) / [UFServiceMessageV1](../index.md) / [State](./index.md)

# State

`sealed class State : `[`UFServiceMessageV1`](../index.md)

Class that maps all the possible actions that the service is doing

### Types

| Name | Summary |
|---|---|
| [CancellingUpdate](-cancelling-update.md) | `object CancellingUpdate : `[`UFServiceMessageV1.State`](./index.md)<br>Client is cancelling the last update request |
| [ConfigurationError](-configuration-error/index.md) | `data class ConfigurationError : `[`UFServiceMessageV1.State`](./index.md)<br>Bad service configuration |
| [Downloading](-downloading/index.md) | `data class Downloading : `[`UFServiceMessageV1.State`](./index.md)<br>Client is downloading artifacts from server |
| [Idle](-idle.md) | `object Idle : `[`UFServiceMessageV1.State`](./index.md)<br>Client is waiting for new requests from server |
| [Updating](-updating.md) | `object Updating : `[`UFServiceMessageV1.State`](./index.md)<br>Client has started the update process. Any request to cancel an update will be rejected |
| [WaitingDownloadAuthorization](-waiting-download-authorization.md) | `object WaitingDownloadAuthorization : `[`UFServiceMessageV1.State`](./index.md)<br>Client is waiting for an authorization to start the artifacts downloading |
| [WaitingUpdateAuthorization](-waiting-update-authorization.md) | `object WaitingUpdateAuthorization : `[`UFServiceMessageV1.State`](./index.md)<br>Client is waiting for an authorization to start the update |

### Properties

| Name | Summary |
|---|---|
| [description](description.md) | `open val description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Message description |
| [name](name.md) | `open val name: `[`UFServiceMessageV1.MessageName`](../-message-name/index.md)<br>Message type |

### Functions

| Name | Summary |
|---|---|
| [toJson](to-json.md) | `open fun toJson(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Inherited Functions

| Name | Summary |
|---|---|
| [toString](../to-string.md) | `open fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Inheritors

| Name | Summary |
|---|---|
| [CancellingUpdate](-cancelling-update.md) | `object CancellingUpdate : `[`UFServiceMessageV1.State`](./index.md)<br>Client is cancelling the last update request |
| [ConfigurationError](-configuration-error/index.md) | `data class ConfigurationError : `[`UFServiceMessageV1.State`](./index.md)<br>Bad service configuration |
| [Downloading](-downloading/index.md) | `data class Downloading : `[`UFServiceMessageV1.State`](./index.md)<br>Client is downloading artifacts from server |
| [Idle](-idle.md) | `object Idle : `[`UFServiceMessageV1.State`](./index.md)<br>Client is waiting for new requests from server |
| [Updating](-updating.md) | `object Updating : `[`UFServiceMessageV1.State`](./index.md)<br>Client has started the update process. Any request to cancel an update will be rejected |
| [WaitingDownloadAuthorization](-waiting-download-authorization.md) | `object WaitingDownloadAuthorization : `[`UFServiceMessageV1.State`](./index.md)<br>Client is waiting for an authorization to start the artifacts downloading |
| [WaitingUpdateAuthorization](-waiting-update-authorization.md) | `object WaitingUpdateAuthorization : `[`UFServiceMessageV1.State`](./index.md)<br>Client is waiting for an authorization to start the update |
