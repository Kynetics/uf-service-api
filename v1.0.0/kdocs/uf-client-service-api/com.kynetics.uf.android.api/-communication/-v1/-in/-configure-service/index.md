[uf-client-service-api](../../../../../index.md) / [com.kynetics.uf.android.api](../../../../index.md) / [Communication](../../../index.md) / [V1](../../index.md) / [In](../index.md) / [ConfigureService](./index.md)

# ConfigureService

`class ConfigureService : `[`Communication.V1.In`](../index.md)

Class use to build a message to configure the service

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ConfigureService(conf: `[`UFServiceConfiguration`](../../../../-u-f-service-configuration/index.md)`)`<br>Class use to build a message to configure the service |

### Properties

| Name | Summary |
|---|---|
| [conf](conf.md) | `val conf: `[`UFServiceConfiguration`](../../../../-u-f-service-configuration/index.md)<br>the service configuration |

### Inherited Functions

| Name | Summary |
|---|---|
| [toMessage](../to-message.md) | `open fun toMessage(): `[`Message`](https://developer.android.com/reference/android/os/Message.html)<br>Convert the object to the corresponding [android.os.Message](https://developer.android.com/reference/android/os/Message.html) instance. |

### Companion Object Properties

| Name | Summary |
|---|---|
| [ID](-i-d.md) | `const val ID: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
