---
title: DicomJsonSerializer
second_title: Aspose.Medical for .NET API Reference
description: Serializes DICOM datasets and files to JSON and deserializes their JSON representations.
type: docs
weight: 2910
url: /net/aspose.medical.dicom.serialization/dicomjsonserializer/
---

## DicomJsonSerializer class

Serializes DICOM datasets and files to JSON and deserializes their JSON representations.

```csharp
public static class DicomJsonSerializer
```

## Methods

| Name | Description |
| --- | --- |
| static [Deserialize](../../aspose.medical.dicom.serialization/dicomjsonserializer/deserialize#deserialize_1)(ReadOnlySpan&lt;char&gt;, DicomJsonSerializerOptions) | Deserializes a DICOM dataset from JSON text. |
| static [Deserialize](../../aspose.medical.dicom.serialization/dicomjsonserializer/deserialize#deserialize)(Stream, DicomJsonSerializerOptions) | Reads a DICOM dataset from a UTF-8 JSON stream. |
| static [DeserializeAsync](../../aspose.medical.dicom.serialization/dicomjsonserializer/deserializeasync#deserializeasync)(PipeReader, DicomJsonSerializerOptions?, CancellationToken) | Asynchronously reads a DICOM dataset from a UTF-8 JSON pipe. |
| static [DeserializeAsync](../../aspose.medical.dicom.serialization/dicomjsonserializer/deserializeasync#deserializeasync_1)(Stream, DicomJsonSerializerOptions?, CancellationToken) | Asynchronously reads a DICOM dataset from a UTF-8 JSON stream. |
| static [DeserializeAsyncEnumerable](../../aspose.medical.dicom.serialization/dicomjsonserializer/deserializeasyncenumerable#deserializeasyncenumerable)(PipeReader, DicomJsonSerializerOptions?, CancellationToken) | Asynchronously reads datasets from a DICOM JSON array in a pipe. |
| static [DeserializeAsyncEnumerable](../../aspose.medical.dicom.serialization/dicomjsonserializer/deserializeasyncenumerable#deserializeasyncenumerable_1)(Stream, DicomJsonSerializerOptions?, CancellationToken) | Asynchronously reads datasets from a DICOM JSON array in a UTF-8 stream. |
| static [DeserializeFile](../../aspose.medical.dicom.serialization/dicomjsonserializer/deserializefile#deserializefile_1)(ReadOnlySpan&lt;char&gt;, DicomJsonSerializerOptions) | Deserializes a DICOM file from JSON text. |
| static [DeserializeFile](../../aspose.medical.dicom.serialization/dicomjsonserializer/deserializefile#deserializefile)(Stream, DicomJsonSerializerOptions) | Reads a DICOM file from a UTF-8 JSON stream. |
| static [DeserializeFileAsync](../../aspose.medical.dicom.serialization/dicomjsonserializer/deserializefileasync#deserializefileasync)(PipeReader, DicomJsonSerializerOptions?, CancellationToken) | Asynchronously reads a DICOM file from a UTF-8 JSON pipe. |
| static [DeserializeFileAsync](../../aspose.medical.dicom.serialization/dicomjsonserializer/deserializefileasync#deserializefileasync_1)(Stream, DicomJsonSerializerOptions?, CancellationToken) | Asynchronously reads a DICOM file from a UTF-8 JSON stream. |
| static [DeserializeList](../../aspose.medical.dicom.serialization/dicomjsonserializer/deserializelist#deserializelist_1)(ReadOnlySpan&lt;char&gt;, DicomJsonSerializerOptions?) | Deserializes a DICOM JSON array into datasets. |
| static [DeserializeList](../../aspose.medical.dicom.serialization/dicomjsonserializer/deserializelist#deserializelist)(Stream, DicomJsonSerializerOptions?) | Reads a DICOM JSON array from a UTF-8 stream. |
| static [DeserializeListAsync](../../aspose.medical.dicom.serialization/dicomjsonserializer/deserializelistasync#deserializelistasync)(PipeReader, DicomJsonSerializerOptions?, CancellationToken) | Asynchronously reads a DICOM JSON array from a pipe. |
| static [DeserializeListAsync](../../aspose.medical.dicom.serialization/dicomjsonserializer/deserializelistasync#deserializelistasync_1)(Stream, DicomJsonSerializerOptions?, CancellationToken) | Asynchronously reads a DICOM JSON array from a UTF-8 stream. |
| static [Serialize](../../aspose.medical.dicom.serialization/dicomjsonserializer/serialize#serialize)(Dataset, DicomJsonSerializerOptions?, bool) | Serializes a DICOM dataset to JSON text. |
| static [Serialize](../../aspose.medical.dicom.serialization/dicomjsonserializer/serialize#serialize_1)(Dataset[], DicomJsonSerializerOptions?, bool) | Serializes an array of DICOM datasets to JSON text. |
| static [Serialize](../../aspose.medical.dicom.serialization/dicomjsonserializer/serialize#serialize_2)(DicomFile, DicomJsonSerializerOptions?, bool) | Serializes a DICOM file to JSON text. |
| static [Serialize](../../aspose.medical.dicom.serialization/dicomjsonserializer/serialize#serialize_3)(Stream, Dataset, DicomJsonSerializerOptions?, bool) | Writes a DICOM dataset as UTF-8 JSON to a stream. |
| static [Serialize](../../aspose.medical.dicom.serialization/dicomjsonserializer/serialize#serialize_4)(Stream, Dataset[], DicomJsonSerializerOptions?, bool) | Writes an array of DICOM datasets as UTF-8 JSON to a stream. |
| static [Serialize](../../aspose.medical.dicom.serialization/dicomjsonserializer/serialize#serialize_5)(Stream, DicomFile, DicomJsonSerializerOptions?, bool) | Writes a DICOM file as UTF-8 JSON to a stream. |
| static [SerializeAsync](../../aspose.medical.dicom.serialization/dicomjsonserializer/serializeasync#serializeasync_4)(PipeWriter, Dataset, DicomJsonSerializerOptions?, bool, CancellationToken) | Asynchronously writes a DICOM dataset as UTF-8 JSON to a pipe. |
| static [SerializeAsync](../../aspose.medical.dicom.serialization/dicomjsonserializer/serializeasync#serializeasync_5)(PipeWriter, Dataset[], DicomJsonSerializerOptions?, bool, CancellationToken) | Asynchronously writes an array of DICOM datasets as UTF-8 JSON to a pipe. |
| static [SerializeAsync](../../aspose.medical.dicom.serialization/dicomjsonserializer/serializeasync#serializeasync_6)(PipeWriter, DicomFile, DicomJsonSerializerOptions?, bool, CancellationToken) | Asynchronously writes a DICOM file as UTF-8 JSON to a pipe. |
| static [SerializeAsync](../../aspose.medical.dicom.serialization/dicomjsonserializer/serializeasync#serializeasync_7)(PipeWriter, IAsyncEnumerable&lt;Dataset?&gt;, DicomJsonSerializerOptions?, bool, CancellationToken) | Asynchronously writes a sequence of DICOM datasets as one UTF-8 JSON array to a pipe. |
| static [SerializeAsync](../../aspose.medical.dicom.serialization/dicomjsonserializer/serializeasync#serializeasync)(Stream, Dataset, DicomJsonSerializerOptions?, bool, CancellationToken) | Asynchronously writes a DICOM dataset as UTF-8 JSON to a stream. |
| static [SerializeAsync](../../aspose.medical.dicom.serialization/dicomjsonserializer/serializeasync#serializeasync_1)(Stream, Dataset[], DicomJsonSerializerOptions?, bool, CancellationToken) | Asynchronously writes an array of DICOM datasets as UTF-8 JSON to a stream. |
| static [SerializeAsync](../../aspose.medical.dicom.serialization/dicomjsonserializer/serializeasync#serializeasync_2)(Stream, DicomFile, DicomJsonSerializerOptions?, bool, CancellationToken) | Asynchronously writes a DICOM file as UTF-8 JSON to a stream. |
| static [SerializeAsync](../../aspose.medical.dicom.serialization/dicomjsonserializer/serializeasync#serializeasync_3)(Stream, IAsyncEnumerable&lt;Dataset?&gt;, DicomJsonSerializerOptions?, bool, CancellationToken) | Asynchronously writes a sequence of DICOM datasets as one UTF-8 JSON array to a stream. |

### See Also

* namespace [Aspose.Medical.Dicom.Serialization](../../aspose.medical.dicom.serialization)
* assembly [Aspose.Medical](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Medical.dll -->
