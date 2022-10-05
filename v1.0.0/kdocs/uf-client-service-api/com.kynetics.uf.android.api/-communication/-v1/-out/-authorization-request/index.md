[uf-client-service-api](../../../../../index.md) / [com.kynetics.uf.android.api](../../../../index.md) / [Communication](../../../index.md) / [V1](../../index.md) / [Out](../index.md) / [AuthorizationRequest](./index.md)

# AuthorizationRequest

`class AuthorizationRequest : `[`Communication.V1.Out`](../index.md)

This class represents a message that the [com.kynetics.uf.android.UpdateFactoryService](#)
sends to clients when it is waiting for an user authorization

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `AuthorizationRequest(authName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`)`<br>This class represents a message that the [com.kynetics.uf.android.UpdateFactoryService](#) sends to clients when it is waiting for an user authorization |

### Properties

| Name | Summary |
|---|---|
| [authName](auth-name.md) | `val authName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>is the kind of authorization, it is one between *DOWNLOAD* and *UPDATE* |
