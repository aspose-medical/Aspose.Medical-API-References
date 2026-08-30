---
title: SerializeAsync
second_title: Aspose.Medical for .NET API Reference
description: Asynchronously writes a DICOM dataset as UTF-8 JSON to a stream.
type: docs
weight: 90
url: /net/aspose.medical.dicom.serialization/dicomjsonserializer/serializeasync/
---

## SerializeAsync(Stream, Dataset, DicomJsonSerializerOptions?, bool, CancellationToken) {#serializeasync}

Asynchronously writes a DICOM dataset as UTF-8 JSON to a stream.

```csharp
public static Task SerializeAsync(Stream utf8Json, Dataset dataset, 
    DicomJsonSerializerOptions? dicomJsonOptions = null, bool writeIndented = false, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| utf8Json | Stream | The stream that receives the UTF-8 JSON data. |
| dataset | Dataset | The dataset to serialize. |
| dicomJsonOptions | DicomJsonSerializerOptions | Options controlling the DICOM JSON representation. |
| writeIndented | Boolean | `true` to indent the JSON; otherwise, `false`. |
| cancellationToken | CancellationToken | A token used to cancel serialization or writing. |

### Return Value

An operation that completes after the dataset has been written.

### See Also

* class [Dataset](../../../aspose.medical.dicom/dataset)
* record [DicomJsonSerializerOptions](../../dicomjsonserializeroptions)
* class [DicomJsonSerializer](../../dicomjsonserializer)
* namespace [Aspose.Medical.Dicom.Serialization](../../dicomjsonserializer)
* assembly [Aspose.Medical](../../../)

---

## SerializeAsync(PipeWriter, Dataset, DicomJsonSerializerOptions?, bool, CancellationToken) {#serializeasync_4}

Asynchronously writes a DICOM dataset as UTF-8 JSON to a pipe.

```csharp
public static ValueTask SerializeAsync(PipeWriter utf8Json, Dataset dataset, 
    DicomJsonSerializerOptions? dicomJsonOptions = null, bool writeIndented = false, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| utf8Json | PipeWriter | The pipe that receives the UTF-8 JSON data. |
| dataset | Dataset | The dataset to serialize. |
| dicomJsonOptions | DicomJsonSerializerOptions | Options controlling the DICOM JSON representation. |
| writeIndented | Boolean | `true` to indent the JSON; otherwise, `false`. |
| cancellationToken | CancellationToken | A token used to cancel serialization or pipe flushing. |

### Return Value

An operation that completes after all serialized data has been flushed to the pipe.

### Remarks

This method flushes but does not complete *utf8Json*.

### See Also

* class [Dataset](../../../aspose.medical.dicom/dataset)
* record [DicomJsonSerializerOptions](../../dicomjsonserializeroptions)
* class [DicomJsonSerializer](../../dicomjsonserializer)
* namespace [Aspose.Medical.Dicom.Serialization](../../dicomjsonserializer)
* assembly [Aspose.Medical](../../../)

---

## SerializeAsync(Stream, DicomFile, DicomJsonSerializerOptions?, bool, CancellationToken) {#serializeasync_2}

Asynchronously writes a DICOM file as UTF-8 JSON to a stream.

```csharp
public static Task SerializeAsync(Stream utf8Json, DicomFile dicomFile, 
    DicomJsonSerializerOptions? dicomJsonOptions = null, bool writeIndented = false, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| utf8Json | Stream | The stream that receives the UTF-8 JSON data. |
| dicomFile | DicomFile | The DICOM file to serialize. |
| dicomJsonOptions | DicomJsonSerializerOptions | Options controlling the DICOM JSON representation. |
| writeIndented | Boolean | `true` to indent the JSON; otherwise, `false`. |
| cancellationToken | CancellationToken | A token used to cancel serialization or writing. |

### Return Value

An operation that completes after the DICOM file has been written.

### See Also

* class [DicomFile](../../../aspose.medical.dicom/dicomfile)
* record [DicomJsonSerializerOptions](../../dicomjsonserializeroptions)
* class [DicomJsonSerializer](../../dicomjsonserializer)
* namespace [Aspose.Medical.Dicom.Serialization](../../dicomjsonserializer)
* assembly [Aspose.Medical](../../../)

---

## SerializeAsync(PipeWriter, DicomFile, DicomJsonSerializerOptions?, bool, CancellationToken) {#serializeasync_6}

Asynchronously writes a DICOM file as UTF-8 JSON to a pipe.

```csharp
public static ValueTask SerializeAsync(PipeWriter utf8Json, DicomFile dicomFile, 
    DicomJsonSerializerOptions? dicomJsonOptions = null, bool writeIndented = false, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| utf8Json | PipeWriter | The pipe that receives the UTF-8 JSON data. |
| dicomFile | DicomFile | The DICOM file to serialize. |
| dicomJsonOptions | DicomJsonSerializerOptions | Options controlling the DICOM JSON representation. |
| writeIndented | Boolean | `true` to indent the JSON; otherwise, `false`. |
| cancellationToken | CancellationToken | A token used to cancel serialization or pipe flushing. |

### Return Value

An operation that completes after all serialized data has been flushed to the pipe.

### Remarks

This method flushes but does not complete *utf8Json*.

### See Also

* class [DicomFile](../../../aspose.medical.dicom/dicomfile)
* record [DicomJsonSerializerOptions](../../dicomjsonserializeroptions)
* class [DicomJsonSerializer](../../dicomjsonserializer)
* namespace [Aspose.Medical.Dicom.Serialization](../../dicomjsonserializer)
* assembly [Aspose.Medical](../../../)

---

## SerializeAsync(Stream, Dataset[], DicomJsonSerializerOptions?, bool, CancellationToken) {#serializeasync_1}

Asynchronously writes an array of DICOM datasets as UTF-8 JSON to a stream.

```csharp
public static Task SerializeAsync(Stream utf8Json, Dataset[] datasets, 
    DicomJsonSerializerOptions? dicomJsonOptions = null, bool writeIndented = false, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| utf8Json | Stream | The stream that receives the UTF-8 JSON data. |
| datasets | Dataset[] | The datasets to serialize as one JSON array. |
| dicomJsonOptions | DicomJsonSerializerOptions | Options controlling the DICOM JSON representation. |
| writeIndented | Boolean | `true` to indent the JSON; otherwise, `false`. |
| cancellationToken | CancellationToken | A token used to cancel serialization or writing. |

### Return Value

An operation that completes after the JSON array has been written.

### See Also

* class [Dataset](../../../aspose.medical.dicom/dataset)
* record [DicomJsonSerializerOptions](../../dicomjsonserializeroptions)
* class [DicomJsonSerializer](../../dicomjsonserializer)
* namespace [Aspose.Medical.Dicom.Serialization](../../dicomjsonserializer)
* assembly [Aspose.Medical](../../../)

---

## SerializeAsync(PipeWriter, Dataset[], DicomJsonSerializerOptions?, bool, CancellationToken) {#serializeasync_5}

Asynchronously writes an array of DICOM datasets as UTF-8 JSON to a pipe.

```csharp
public static ValueTask SerializeAsync(PipeWriter utf8Json, Dataset[] datasets, 
    DicomJsonSerializerOptions? dicomJsonOptions = null, bool writeIndented = false, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| utf8Json | PipeWriter | The pipe that receives the UTF-8 JSON data. |
| datasets | Dataset[] | The datasets to serialize as one JSON array. |
| dicomJsonOptions | DicomJsonSerializerOptions | Options controlling the DICOM JSON representation. |
| writeIndented | Boolean | `true` to indent the JSON; otherwise, `false`. |
| cancellationToken | CancellationToken | A token used to cancel serialization or pipe flushing. |

### Return Value

An operation that completes after all serialized data has been flushed to the pipe.

### Remarks

This method flushes but does not complete *utf8Json*.

### See Also

* class [Dataset](../../../aspose.medical.dicom/dataset)
* record [DicomJsonSerializerOptions](../../dicomjsonserializeroptions)
* class [DicomJsonSerializer](../../dicomjsonserializer)
* namespace [Aspose.Medical.Dicom.Serialization](../../dicomjsonserializer)
* assembly [Aspose.Medical](../../../)

---

## SerializeAsync(Stream, IAsyncEnumerable&lt;Dataset?&gt;, DicomJsonSerializerOptions?, bool, CancellationToken) {#serializeasync_3}

Asynchronously writes a sequence of DICOM datasets as one UTF-8 JSON array to a stream.

```csharp
public static Task SerializeAsync(Stream utf8Json, IAsyncEnumerable<Dataset?> datasets, 
    DicomJsonSerializerOptions? dicomJsonOptions = null, bool writeIndented = false, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| utf8Json | Stream | The stream that receives the UTF-8 JSON data. |
| datasets | IAsyncEnumerable`1 | The asynchronous sequence of datasets to serialize. |
| dicomJsonOptions | DicomJsonSerializerOptions | Options controlling the DICOM JSON representation. |
| writeIndented | Boolean | `true` to indent the JSON; otherwise, `false`. |
| cancellationToken | CancellationToken | A token used to cancel enumeration, serialization, or writing. |

### Return Value

An operation that completes after the JSON array has been written.

### Exceptions

| exception | condition |
| --- | --- |
| [MedicalApiException](../../../aspose.medical.errors/medicalapiexception) | *datasets* produces a `null` item. |

### See Also

* class [Dataset](../../../aspose.medical.dicom/dataset)
* record [DicomJsonSerializerOptions](../../dicomjsonserializeroptions)
* class [DicomJsonSerializer](../../dicomjsonserializer)
* namespace [Aspose.Medical.Dicom.Serialization](../../dicomjsonserializer)
* assembly [Aspose.Medical](../../../)

---

## SerializeAsync(PipeWriter, IAsyncEnumerable&lt;Dataset?&gt;, DicomJsonSerializerOptions?, bool, CancellationToken) {#serializeasync_7}

Asynchronously writes a sequence of DICOM datasets as one UTF-8 JSON array to a pipe.

```csharp
public static ValueTask SerializeAsync(PipeWriter utf8Json, IAsyncEnumerable<Dataset?> datasets, 
    DicomJsonSerializerOptions? dicomJsonOptions = null, bool writeIndented = false, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| utf8Json | PipeWriter | The pipe that receives the UTF-8 JSON data. |
| datasets | IAsyncEnumerable`1 | The asynchronous sequence of datasets to serialize. |
| dicomJsonOptions | DicomJsonSerializerOptions | Options controlling the DICOM JSON representation. |
| writeIndented | Boolean | `true` to indent the JSON; otherwise, `false`. |
| cancellationToken | CancellationToken | A token used to cancel enumeration, serialization, or writing. |

### Return Value

An operation that completes after the JSON array has been written.

### Exceptions

| exception | condition |
| --- | --- |
| [MedicalApiException](../../../aspose.medical.errors/medicalapiexception) | *datasets* produces a `null` item. |

### Remarks

This method does not complete *utf8Json*.

### See Also

* class [Dataset](../../../aspose.medical.dicom/dataset)
* record [DicomJsonSerializerOptions](../../dicomjsonserializeroptions)
* class [DicomJsonSerializer](../../dicomjsonserializer)
* namespace [Aspose.Medical.Dicom.Serialization](../../dicomjsonserializer)
* assembly [Aspose.Medical](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Medical.dll -->
