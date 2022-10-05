[uf-client-service-api](../../../../../index.md) / [com.kynetics.uf.android.api](../../../../index.md) / [Communication](../../../index.md) / [V1](../../index.md) / [In](../index.md) / [WithReplyTo](./index.md)

# WithReplyTo

`abstract class WithReplyTo : `[`Communication.V1.In`](../index.md)

Class that maps all messages that are sent to [com.kynetics.uf.android.UpdateFactoryService](#)
that must receive a response.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `WithReplyTo(replyTo: `[`Messenger`](https://developer.android.com/reference/android/os/Messenger.html)`, id: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`)`<br>Class that maps all messages that are sent to [com.kynetics.uf.android.UpdateFactoryService](#) that must receive a response. |

### Properties

| Name | Summary |
|---|---|
| [replyTo](reply-to.md) | `val replyTo: `[`Messenger`](https://developer.android.com/reference/android/os/Messenger.html)<br>[Messenger](https://developer.android.com/reference/android/os/Messenger.html) where replies to this message is sent |

### Functions

| Name | Summary |
|---|---|
| [toMessage](to-message.md) | `open fun toMessage(): `[`Message`](https://developer.android.com/reference/android/os/Message.html)<br>Convert the object to the corresponding [android.os.Message](https://developer.android.com/reference/android/os/Message.html) instance. |

### Inheritors

| Name | Summary |
|---|---|
| [RegisterClient](../-register-client/index.md) | `class RegisterClient : `[`Communication.V1.In.WithReplyTo`](./index.md)<br>Class use to build a message to subscribe a [Messenger](https://developer.android.com/reference/android/os/Messenger.html) to the service notification system. |
| [Sync](../-sync/index.md) | `class Sync : `[`Communication.V1.In.WithReplyTo`](./index.md)<br>Class use to build a sync message. When the service receive a sync message it responses with two messages, the first message contains the service's state and the second message contains the service's configuration |
| [UnregisterClient](../-unregister-client/index.md) | `class UnregisterClient : `[`Communication.V1.In.WithReplyTo`](./index.md)<br>Class use to build a message to unsubscribe a [Messenger](https://developer.android.com/reference/android/os/Messenger.html) to the service notification system. |
