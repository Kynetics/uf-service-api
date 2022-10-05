[uf-client-service-api](../../index.md) / [com.kynetics.uf.android.api.v1](../index.md) / [UFServiceMessageV1](index.md) / [fromJson](./from-json.md)

# fromJson

`fun fromJson(jsonContent: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`UFServiceMessageV1`](index.md)

Deserialize a [jsonContent](from-json.md#com.kynetics.uf.android.api.v1.UFServiceMessageV1.Companion$fromJson(kotlin.String)/jsonContent) element into a corresponding object of type [UFServiceMessageV1](index.md).

### Exceptions

`JsonException` - in case of malformed json

`SerializationException` - if given input can not be deserialized

`IllegalArgumentException` - if given input isn't a UFServiceMessageV1 json serialization