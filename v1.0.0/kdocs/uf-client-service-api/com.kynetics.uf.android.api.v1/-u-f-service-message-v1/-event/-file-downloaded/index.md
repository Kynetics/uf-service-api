[uf-client-service-api](../../../../index.md) / [com.kynetics.uf.android.api.v1](../../../index.md) / [UFServiceMessageV1](../../index.md) / [Event](../index.md) / [FileDownloaded](./index.md)

# FileDownloaded

`data class FileDownloaded : `[`UFServiceMessageV1.Event`](../index.md)

A file is downloaded

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `FileDownloaded(fileDownloaded: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`)`<br>A file is downloaded |

### Properties

| Name | Summary |
|---|---|
| [fileDownloaded](file-downloaded.md) | `val fileDownloaded: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>name of file downloaded |

### Inherited Properties

| Name | Summary |
|---|---|
| [description](../description.md) | `open val description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Message description |
| [name](../name.md) | `open val name: `[`UFServiceMessageV1.MessageName`](../../-message-name/index.md)<br>Message type |

### Functions

| Name | Summary |
|---|---|
| [toJson](to-json.md) | `fun toJson(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
