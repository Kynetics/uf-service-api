[uf-client-service-api](../../../../index.md) / [com.kynetics.uf.android.api.v1](../../../index.md) / [UFServiceMessageV1](../../index.md) / [State](../index.md) / [Downloading](./index.md)

# Downloading

`data class Downloading : `[`UFServiceMessageV1.State`](../index.md)

Client is downloading artifacts from server

### Types

| Name | Summary |
|---|---|
| [Artifact](-artifact/index.md) | `data class Artifact`<br>This class represent a file to download |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Downloading(artifacts: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`UFServiceMessageV1.State.Downloading.Artifact`](-artifact/index.md)`>)`<br>Client is downloading artifacts from server |

### Properties

| Name | Summary |
|---|---|
| [artifacts](artifacts.md) | `val artifacts: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`UFServiceMessageV1.State.Downloading.Artifact`](-artifact/index.md)`>`<br>list of all artifacts to download |

### Inherited Properties

| Name | Summary |
|---|---|
| [description](../description.md) | `open val description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Message description |
| [name](../name.md) | `open val name: `[`UFServiceMessageV1.MessageName`](../../-message-name/index.md)<br>Message type |

### Functions

| Name | Summary |
|---|---|
| [toJson](to-json.md) | `fun toJson(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
