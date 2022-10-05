[uf-client-service-api](../../../../index.md) / [com.kynetics.uf.android.api](../../../index.md) / [Communication](../../index.md) / [V1](../index.md) / [In](./index.md)

# In

`sealed class In : `[`Communication.V1`](../index.md)

Class that maps all the messages that are sent to com.kynetics.uf.android.UpdateFactoryService

### Types

| Name | Summary |
|---|---|
| [AuthorizationResponse](-authorization-response/index.md) | `class AuthorizationResponse : `[`Communication.V1.In`](./index.md)<br>Class use to build a message to grant / denied  an authorization |
| [ConfigureService](-configure-service/index.md) | `class ConfigureService : `[`Communication.V1.In`](./index.md)<br>Class use to build a message to configure the service |
| [ForcePing](-force-ping.md) | `object ForcePing : `[`Communication.V1.In`](./index.md)<br>Class use to build ForcePing message. When the service receive a force ping message it pings the service |
| [RegisterClient](-register-client/index.md) | `class RegisterClient : `[`Communication.V1.In.WithReplyTo`](-with-reply-to/index.md)<br>Class use to build a message to subscribe a [Messenger](https://developer.android.com/reference/android/os/Messenger.html) to the service notification system. |
| [Sync](-sync/index.md) | `class Sync : `[`Communication.V1.In.WithReplyTo`](-with-reply-to/index.md)<br>Class use to build a sync message. When the service receive a sync message it responses with two messages, the first message contains the service's state and the second message contains the service's configuration |
| [UnregisterClient](-unregister-client/index.md) | `class UnregisterClient : `[`Communication.V1.In.WithReplyTo`](-with-reply-to/index.md)<br>Class use to build a message to unsubscribe a [Messenger](https://developer.android.com/reference/android/os/Messenger.html) to the service notification system. |
| [WithReplyTo](-with-reply-to/index.md) | `abstract class WithReplyTo : `[`Communication.V1.In`](./index.md)<br>Class that maps all messages that are sent to [com.kynetics.uf.android.UpdateFactoryService](#) that must receive a response. |

### Functions

| Name | Summary |
|---|---|
| [toMessage](to-message.md) | `open fun toMessage(): `[`Message`](https://developer.android.com/reference/android/os/Message.html)<br>Convert the object to the corresponding [android.os.Message](https://developer.android.com/reference/android/os/Message.html) instance. |

### Inheritors

| Name | Summary |
|---|---|
| [AuthorizationResponse](-authorization-response/index.md) | `class AuthorizationResponse : `[`Communication.V1.In`](./index.md)<br>Class use to build a message to grant / denied  an authorization |
| [ConfigureService](-configure-service/index.md) | `class ConfigureService : `[`Communication.V1.In`](./index.md)<br>Class use to build a message to configure the service |
| [ForcePing](-force-ping.md) | `object ForcePing : `[`Communication.V1.In`](./index.md)<br>Class use to build ForcePing message. When the service receive a force ping message it pings the service |
| [WithReplyTo](-with-reply-to/index.md) | `abstract class WithReplyTo : `[`Communication.V1.In`](./index.md)<br>Class that maps all messages that are sent to [com.kynetics.uf.android.UpdateFactoryService](#) that must receive a response. |
