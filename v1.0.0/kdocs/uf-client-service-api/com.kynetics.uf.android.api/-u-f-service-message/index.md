[uf-client-service-api](../../index.md) / [com.kynetics.uf.android.api](../index.md) / [UFServiceMessage](./index.md)

# UFServiceMessage

`class ~~UFServiceMessage~~ : `[`Serializable`](https://developer.android.com/reference/java/io/Serializable.html)
**Deprecated:** As of release 1.0.0 replaced by com.kynetics.uf.android.api.v1.UFServiceMessageV1

This class represents the service's state (api version 0.1)

**See Also**

[ApiCommunicationVersion.V0_1](../-api-communication-version/-v0_1.md)

[com.kynetics.uf.android.api.v1.UFServiceMessageV1](../../com.kynetics.uf.android.api.v1/-u-f-service-message-v1/index.md)

### Types

| Name | Summary |
|---|---|
| [Suspend](-suspend/index.md) | `enum class Suspend` |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `UFServiceMessage(eventName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, oldState: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, currentState: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, suspend: `[`UFServiceMessage.Suspend`](-suspend/index.md)`)`<br>This class represents the service's state (api version 0.1) |

### Properties

| Name | Summary |
|---|---|
| [currentState](current-state.md) | `val currentState: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [dateTime](date-time.md) | `val dateTime: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [eventName](event-name.md) | `val eventName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [oldState](old-state.md) | `val oldState: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [suspend](suspend.md) | `val suspend: `[`UFServiceMessage.Suspend`](-suspend/index.md) |
