[uf-client-service-api](../../../../index.md) / [com.kynetics.uf.android.api.v1](../../../index.md) / [UFServiceMessageV1](../../index.md) / [Event](../index.md) / [UpdateFinished](./index.md)

# UpdateFinished

`data class UpdateFinished : `[`UFServiceMessageV1.Event`](../index.md)

Update process is finish

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `UpdateFinished(successApply: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`, details: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`> = emptyList())`<br>Update process is finish |

### Properties

| Name | Summary |
|---|---|
| [details](details.md) | `val details: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>`<br>optional additional details |
| [successApply](success-apply.md) | `val successApply: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>true if the system is successfully updated, false otherwise |

### Inherited Properties

| Name | Summary |
|---|---|
| [description](../description.md) | `open val description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Message description |
| [name](../name.md) | `open val name: `[`UFServiceMessageV1.MessageName`](../../-message-name/index.md)<br>Message type |

### Functions

| Name | Summary |
|---|---|
| [toJson](to-json.md) | `fun toJson(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
