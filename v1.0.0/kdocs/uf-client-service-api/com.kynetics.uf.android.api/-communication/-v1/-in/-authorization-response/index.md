[uf-client-service-api](../../../../../index.md) / [com.kynetics.uf.android.api](../../../../index.md) / [Communication](../../../index.md) / [V1](../../index.md) / [In](../index.md) / [AuthorizationResponse](./index.md)

# AuthorizationResponse

`class AuthorizationResponse : `[`Communication.V1.In`](../index.md)

Class use to build a message to grant / denied  an authorization

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `AuthorizationResponse(granted: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`)`<br>Class use to build a message to grant / denied  an authorization |

### Properties

| Name | Summary |
|---|---|
| [granted](granted.md) | `val granted: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

### Inherited Functions

| Name | Summary |
|---|---|
| [toMessage](../to-message.md) | `open fun toMessage(): `[`Message`](https://developer.android.com/reference/android/os/Message.html)<br>Convert the object to the corresponding [android.os.Message](https://developer.android.com/reference/android/os/Message.html) instance. |

### Companion Object Properties

| Name | Summary |
|---|---|
| [ID](-i-d.md) | `const val ID: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
