[uf-client-service-api](../../../../../index.md) / [com.kynetics.uf.android.api](../../../../index.md) / [Communication](../../../index.md) / [V1](../../index.md) / [In](../index.md) / [UnregisterClient](./index.md)

# UnregisterClient

`class UnregisterClient : `[`Communication.V1.In.WithReplyTo`](../-with-reply-to/index.md)

Class use to build a message to unsubscribe a [Messenger](https://developer.android.com/reference/android/os/Messenger.html) to the service notification
system.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `UnregisterClient(replyTo: `[`Messenger`](https://developer.android.com/reference/android/os/Messenger.html)`)`<br>Class use to build a message to unsubscribe a [Messenger](https://developer.android.com/reference/android/os/Messenger.html) to the service notification system. |

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
