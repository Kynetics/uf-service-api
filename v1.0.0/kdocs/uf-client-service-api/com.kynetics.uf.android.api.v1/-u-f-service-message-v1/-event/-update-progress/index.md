[uf-client-service-api](../../../../index.md) / [com.kynetics.uf.android.api.v1](../../../index.md) / [UFServiceMessageV1](../../index.md) / [Event](../index.md) / [UpdateProgress](./index.md)

# UpdateProgress

`data class UpdateProgress : `[`UFServiceMessageV1.Event`](../index.md)

Update phase

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `UpdateProgress(phaseName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, phaseDescription: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = "", percentage: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)` = 0.0)`<br>Update phase |

### Properties

| Name | Summary |
|---|---|
| [percentage](percentage.md) | `val percentage: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>percentage of update phase |
| [phaseDescription](phase-description.md) | `val phaseDescription: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>description of the update phase |
| [phaseName](phase-name.md) | `val phaseName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>name of the update phase |

### Inherited Properties

| Name | Summary |
|---|---|
| [description](../description.md) | `open val description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Message description |
| [name](../name.md) | `open val name: `[`UFServiceMessageV1.MessageName`](../../-message-name/index.md)<br>Message type |

### Functions

| Name | Summary |
|---|---|
| [toJson](to-json.md) | `fun toJson(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
