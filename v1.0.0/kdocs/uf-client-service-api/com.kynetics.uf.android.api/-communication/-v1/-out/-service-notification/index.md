[uf-client-service-api](../../../../../index.md) / [com.kynetics.uf.android.api](../../../../index.md) / [Communication](../../../index.md) / [V1](../../index.md) / [Out](../index.md) / [ServiceNotification](./index.md)

# ServiceNotification

`class ServiceNotification : `[`Communication.V1.Out`](../index.md)

This class represents a message that the [com.kynetics.uf.android.UpdateFactoryService](#)
sends to clients with the information about its state. This message is sent after each
polling request or as response of a [Communication.V1.In.Sync](../../-in/-sync/index.md) message.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ServiceNotification(content: `[`UFServiceMessageV1`](../../../../../com.kynetics.uf.android.api.v1/-u-f-service-message-v1/index.md)`)`<br>This class represents a message that the [com.kynetics.uf.android.UpdateFactoryService](#) sends to clients with the information about its state. This message is sent after each polling request or as response of a [Communication.V1.In.Sync](../../-in/-sync/index.md) message. |

### Properties

| Name | Summary |
|---|---|
| [content](content.md) | `val content: `[`UFServiceMessageV1`](../../../../../com.kynetics.uf.android.api.v1/-u-f-service-message-v1/index.md)<br>is the representation of the current service's state |
