[uf-client-service-api](../../index.md) / [com.kynetics.uf.android.api](../index.md) / [UFServiceConfiguration](./index.md)

# UFServiceConfiguration

`data class UFServiceConfiguration : `[`Serializable`](https://developer.android.com/reference/java/io/Serializable.html)

This class represent the [com.kynetics.uf.android.UpdateFactoryService](#)'s configuration

### Types

| Name | Summary |
|---|---|
| [Builder](-builder/index.md) | `class Builder`<br>[UFServiceConfiguration](./index.md)'s builder class |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `UFServiceConfiguration(tenant: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, controllerId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, retryDelay: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, url: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, targetToken: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, gatewayToken: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, isApiMode: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`, isEnable: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`, isUpdateFactoryServe: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`, targetAttributes: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>)`<br>This class represent the [com.kynetics.uf.android.UpdateFactoryService](#)'s configuration |

### Properties

| Name | Summary |
|---|---|
| [controllerId](controller-id.md) | `val controllerId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [gatewayToken](gateway-token.md) | `val gatewayToken: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [isApiMode](is-api-mode.md) | `val isApiMode: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isEnable](is-enable.md) | `val isEnable: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isUpdateFactoryServe](is-update-factory-serve.md) | `val isUpdateFactoryServe: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [retryDelay](retry-delay.md) | `val ~~retryDelay~~: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [targetAttributes](target-attributes.md) | `val targetAttributes: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [targetToken](target-token.md) | `val targetToken: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [tenant](tenant.md) | `val tenant: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [url](url.md) | `val url: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [getArgs](get-args.md) | `fun ~~getArgs~~(): `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>`<br>get target's tags |
| [toJson](to-json.md) | `fun toJson(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Json serialization |

### Companion Object Functions

| Name | Summary |
|---|---|
| [builder](builder.md) | `fun builder(): `[`UFServiceConfiguration.Builder`](-builder/index.md)<br>Instantiate a builder |
| [fromJson](from-json.md) | `fun fromJson(data: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`UFServiceConfiguration`](./index.md)<br>Deserializes given json [data](from-json.md#com.kynetics.uf.android.api.UFServiceConfiguration.Companion$fromJson(kotlin.String)/data) into a corresponding object of type [UFServiceConfiguration](./index.md). |
