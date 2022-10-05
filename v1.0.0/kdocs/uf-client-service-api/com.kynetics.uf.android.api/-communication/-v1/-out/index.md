[uf-client-service-api](../../../../index.md) / [com.kynetics.uf.android.api](../../../index.md) / [Communication](../../index.md) / [V1](../index.md) / [Out](./index.md)

# Out

`sealed class Out : `[`Communication.V1`](../index.md)

Class that maps all messages that the [com.kynetics.uf.android.UpdateFactoryService](#)
sends to the clients

### Types

| Name | Summary |
|---|---|
| [AuthorizationRequest](-authorization-request/index.md) | `class AuthorizationRequest : `[`Communication.V1.Out`](./index.md)<br>This class represents a message that the [com.kynetics.uf.android.UpdateFactoryService](#) sends to clients when it is waiting for an user authorization |
| [CurrentServiceConfiguration](-current-service-configuration/index.md) | `class CurrentServiceConfiguration : `[`Communication.V1.Out`](./index.md)<br>This class represents a message that the [com.kynetics.uf.android.UpdateFactoryService](#) sends to the client as response of a [Communication.V1.In.Sync](../-in/-sync/index.md) message. |
| [ServiceNotification](-service-notification/index.md) | `class ServiceNotification : `[`Communication.V1.Out`](./index.md)<br>This class represents a message that the [com.kynetics.uf.android.UpdateFactoryService](#) sends to clients with the information about its state. This message is sent after each polling request or as response of a [Communication.V1.In.Sync](../-in/-sync/index.md) message. |

### Inheritors

| Name | Summary |
|---|---|
| [AuthorizationRequest](-authorization-request/index.md) | `class AuthorizationRequest : `[`Communication.V1.Out`](./index.md)<br>This class represents a message that the [com.kynetics.uf.android.UpdateFactoryService](#) sends to clients when it is waiting for an user authorization |
| [CurrentServiceConfiguration](-current-service-configuration/index.md) | `class CurrentServiceConfiguration : `[`Communication.V1.Out`](./index.md)<br>This class represents a message that the [com.kynetics.uf.android.UpdateFactoryService](#) sends to the client as response of a [Communication.V1.In.Sync](../-in/-sync/index.md) message. |
| [ServiceNotification](-service-notification/index.md) | `class ServiceNotification : `[`Communication.V1.Out`](./index.md)<br>This class represents a message that the [com.kynetics.uf.android.UpdateFactoryService](#) sends to clients with the information about its state. This message is sent after each polling request or as response of a [Communication.V1.In.Sync](../-in/-sync/index.md) message. |
