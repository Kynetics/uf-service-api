[uf-client-service-api](../../../../index.md) / [com.kynetics.uf.android.api.v1](../../../index.md) / [UFServiceMessageV1](../../index.md) / [Event](../index.md) / [UpdateAvailable](./index.md)

# UpdateAvailable

`data class UpdateAvailable : `[`UFServiceMessageV1.Event`](../index.md)

An update is available on cloud

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `UpdateAvailable(id: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`)`<br>An update is available on cloud |

### Properties

| Name | Summary |
|---|---|
| [id](id.md) | `val id: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>update's id |

### Inherited Properties

| Name | Summary |
|---|---|
| [description](../description.md) | `open val description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Message description |
| [name](../name.md) | `open val name: `[`UFServiceMessageV1.MessageName`](../../-message-name/index.md)<br>Message type |

### Functions

| Name | Summary |
|---|---|
| [toJson](to-json.md) | `fun toJson(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
