[uf-client-service-api](../../../index.md) / [com.kynetics.uf.android.api.v1](../../index.md) / [UFServiceMessageV1](../index.md) / [Event](./index.md)

# Event

`sealed class Event : `[`UFServiceMessageV1`](../index.md)

Class that maps all the events that are notified

### Types

| Name | Summary |
|---|---|
| [AllFilesDownloaded](-all-files-downloaded.md) | `object AllFilesDownloaded : `[`UFServiceMessageV1.Event`](./index.md)<br>All file needed are downloaded |
| [DownloadProgress](-download-progress/index.md) | `data class DownloadProgress : `[`UFServiceMessageV1.Event`](./index.md)<br>Percent of file downloaded |
| [Error](-error/index.md) | `data class Error : `[`UFServiceMessageV1.Event`](./index.md)<br>An error is occurred |
| [FileDownloaded](-file-downloaded/index.md) | `data class FileDownloaded : `[`UFServiceMessageV1.Event`](./index.md)<br>A file is downloaded |
| [Polling](-polling.md) | `object Polling : `[`UFServiceMessageV1.Event`](./index.md)<br>Client is contacting server to retrieve new action to execute |
| [StartDownloadFile](-start-download-file/index.md) | `data class StartDownloadFile : `[`UFServiceMessageV1.Event`](./index.md)<br>A file downloading is started |
| [UpdateAvailable](-update-available/index.md) | `data class UpdateAvailable : `[`UFServiceMessageV1.Event`](./index.md)<br>An update is available on cloud |
| [UpdateFinished](-update-finished/index.md) | `data class UpdateFinished : `[`UFServiceMessageV1.Event`](./index.md)<br>Update process is finish |
| [UpdateProgress](-update-progress/index.md) | `data class UpdateProgress : `[`UFServiceMessageV1.Event`](./index.md)<br>Update phase |

### Properties

| Name | Summary |
|---|---|
| [description](description.md) | `open val description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Message description |
| [name](name.md) | `open val name: `[`UFServiceMessageV1.MessageName`](../-message-name/index.md)<br>Message type |

### Functions

| Name | Summary |
|---|---|
| [toJson](to-json.md) | `open fun toJson(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Inherited Functions

| Name | Summary |
|---|---|
| [toString](../to-string.md) | `open fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Inheritors

| Name | Summary |
|---|---|
| [AllFilesDownloaded](-all-files-downloaded.md) | `object AllFilesDownloaded : `[`UFServiceMessageV1.Event`](./index.md)<br>All file needed are downloaded |
| [DownloadProgress](-download-progress/index.md) | `data class DownloadProgress : `[`UFServiceMessageV1.Event`](./index.md)<br>Percent of file downloaded |
| [Error](-error/index.md) | `data class Error : `[`UFServiceMessageV1.Event`](./index.md)<br>An error is occurred |
| [FileDownloaded](-file-downloaded/index.md) | `data class FileDownloaded : `[`UFServiceMessageV1.Event`](./index.md)<br>A file is downloaded |
| [Polling](-polling.md) | `object Polling : `[`UFServiceMessageV1.Event`](./index.md)<br>Client is contacting server to retrieve new action to execute |
| [StartDownloadFile](-start-download-file/index.md) | `data class StartDownloadFile : `[`UFServiceMessageV1.Event`](./index.md)<br>A file downloading is started |
| [UpdateAvailable](-update-available/index.md) | `data class UpdateAvailable : `[`UFServiceMessageV1.Event`](./index.md)<br>An update is available on cloud |
| [UpdateFinished](-update-finished/index.md) | `data class UpdateFinished : `[`UFServiceMessageV1.Event`](./index.md)<br>Update process is finish |
| [UpdateProgress](-update-progress/index.md) | `data class UpdateProgress : `[`UFServiceMessageV1.Event`](./index.md)<br>Update phase |
