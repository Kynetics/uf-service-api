[uf-client-service-api](../../index.md) / [com.kynetics.uf.android.api.v1](../index.md) / [UFServiceMessageV1](./index.md)

# UFServiceMessageV1

`sealed class UFServiceMessageV1`

This class maps all possible messages sent by UpdateFactoryService to the clients that are
subscribed to its notification system.

**See Also**

[Communication.V1.Out.ServiceNotification](../../com.kynetics.uf.android.api/-communication/-v1/-out/-service-notification/index.md)

### Types

| Name | Summary |
|---|---|
| [Event](-event/index.md) | `sealed class Event : `[`UFServiceMessageV1`](./index.md)<br>Class that maps all the events that are notified |
| [MessageName](-message-name/index.md) | `enum class MessageName`<br>Enum of all the possible messages type |
| [State](-state/index.md) | `sealed class State : `[`UFServiceMessageV1`](./index.md)<br>Class that maps all the possible actions that the service is doing |

### Properties

| Name | Summary |
|---|---|
| [description](description.md) | `abstract val description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Message description |
| [name](name.md) | `abstract val name: `[`UFServiceMessageV1.MessageName`](-message-name/index.md)<br>Message type |

### Functions

| Name | Summary |
|---|---|
| [toJson](to-json.md) | `abstract fun toJson(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [toString](to-string.md) | `open fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [fromJson](from-json.md) | `fun fromJson(jsonContent: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`UFServiceMessageV1`](./index.md)<br>Deserialize a [jsonContent](from-json.md#com.kynetics.uf.android.api.v1.UFServiceMessageV1.Companion$fromJson(kotlin.String)/jsonContent) element into a corresponding object of type [UFServiceMessageV1](./index.md). |

### Inheritors

| Name | Summary |
|---|---|
| [Event](-event/index.md) | `sealed class Event : `[`UFServiceMessageV1`](./index.md)<br>Class that maps all the events that are notified |
| [State](-state/index.md) | `sealed class State : `[`UFServiceMessageV1`](./index.md)<br>Class that maps all the possible actions that the service is doing |
