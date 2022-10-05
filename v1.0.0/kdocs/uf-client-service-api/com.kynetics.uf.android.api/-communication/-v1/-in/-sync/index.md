[uf-client-service-api](../../../../../index.md) / [com.kynetics.uf.android.api](../../../../index.md) / [Communication](../../../index.md) / [V1](../../index.md) / [In](../index.md) / [Sync](./index.md)

# Sync

`class Sync : `[`Communication.V1.In.WithReplyTo`](../-with-reply-to/index.md)

Class use to build a sync message.
When the service receive a sync message it responses with two messages,
the first message contains the service's state and the second message contains the
service's configuration

**See Also**

[Communication.V1.Out.ServiceNotification](../../-out/-service-notification/index.md)

[Communication.V1.Out.CurrentServiceConfiguration](../../-out/-current-service-configuration/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Sync(replyTo: `[`Messenger`](https://developer.android.com/reference/android/os/Messenger.html)`)`<br>Class use to build a sync message. When the service receive a sync message it responses with two messages, the first message contains the service's state and the second message contains the service's configuration |

### Inherited Properties

| Name | Summary |
|---|---|
| [replyTo](../-with-reply-to/reply-to.md) | `val replyTo: `[`Messenger`](https://developer.android.com/reference/android/os/Messenger.html)<br>[Messenger](https://developer.android.com/reference/android/os/Messenger.html) where replies to this message is sent |

### Inherited Functions

| Name | Summary |
|---|---|
| [toMessage](../-with-reply-to/to-message.md) | `open fun toMessage(): `[`Message`](https://developer.android.com/reference/android/os/Message.html)<br>Convert the object to the corresponding [android.os.Message](https://developer.android.com/reference/android/os/Message.html) instance. |

### Companion Object Properties

| Name | Summary |
|---|---|
| [ID](-i-d.md) | `const val ID: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
