[uf-client-service-api](../../../../index.md) / [com.kynetics.uf.android.api.v1](../../../index.md) / [UFServiceMessageV1](../../index.md) / [Event](../index.md) / [StartDownloadFile](./index.md)

# StartDownloadFile

`data class StartDownloadFile : `[`UFServiceMessageV1.Event`](../index.md)

A file downloading is started

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `StartDownloadFile(fileName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`)`<br>A file downloading is started |

### Properties

| Name | Summary |
|---|---|
| [fileName](file-name.md) | `val fileName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>file's name |

### Inherited Properties

| Name | Summary |
|---|---|
| [description](../description.md) | `open val description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Message description |
| [name](../name.md) | `open val name: `[`UFServiceMessageV1.MessageName`](../../-message-name/index.md)<br>Message type |

### Functions

| Name | Summary |
|---|---|
| [toJson](to-json.md) | `fun toJson(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
