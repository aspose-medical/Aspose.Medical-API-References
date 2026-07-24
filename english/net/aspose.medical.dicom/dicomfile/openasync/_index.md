---
title: OpenAsync
second_title: Aspose.Medical for .NET API Reference
description: Asynchronously reads a DICOM file from a Pipe and returns the DicomFileaspose.medical.dicom/dicomfile.
type: docs
weight: 100
url: /net/aspose.medical.dicom/dicomfile/openasync/
---

## OpenAsync(Pipe, ReadDicomPipeOptions, ITagDataReadingStrategy, CancellationToken) {#openasync}

Asynchronously reads a DICOM file from a Pipe and returns the [`DicomFile`](../../dicomfile).

```csharp
public static ValueTask<DicomFile> OpenAsync(Pipe pipe, ReadDicomPipeOptions? options = null, 
    ITagDataReadingStrategy? strategy = null, CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pipe | Pipe | The pipe supplying DICOM bytes (its Reader is used). |
| options | ReadDicomPipeOptions | Pipe-read options (e.g., fallback encoding). |
| strategy | ITagDataReadingStrategy | Tag data access strategy (e.g., immediate, deferred, or selective large-value handling). |
| cancellationToken | CancellationToken | A token to cancel the asynchronous operation. The default value is None. |

### Return Value

A Task that represents the asynchronous operation. The task result contains the parsed [`DicomFile`](../../dicomfile).

### Exceptions

| exception | condition |
| --- | --- |
| OperationCanceledException | The operation was canceled via *cancellationToken*. |

### See Also

* record [ReadDicomPipeOptions](../../../aspose.medical.dicom.readers/readdicompipeoptions)
* interface [ITagDataReadingStrategy](../../../aspose.medical.dicom.readers/itagdatareadingstrategy)
* class [DicomFile](../../dicomfile)
* namespace [Aspose.Medical.Dicom](../../dicomfile)
* assembly [Aspose.Medical](../../../)

---

## OpenAsync(PipeReader, ReadDicomPipeOptions, ITagDataReadingStrategy, CancellationToken) {#openasync_1}

Asynchronously reads a DICOM file from a PipeReader and returns the [`DicomFile`](../../dicomfile).

```csharp
public static ValueTask<DicomFile> OpenAsync(PipeReader pipeReader, 
    ReadDicomPipeOptions? options = null, ITagDataReadingStrategy? strategy = null, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pipeReader | PipeReader | The pipe reader supplying DICOM bytes. |
| options | ReadDicomPipeOptions | Pipe-read options (e.g., fallback encoding). |
| strategy | ITagDataReadingStrategy | Tag data access strategy (e.g., immediate, deferred, or selective large-value handling). |
| cancellationToken | CancellationToken | A token to cancel the asynchronous operation. The default value is None. |

### Return Value

A ValueTask that represents the asynchronous operation. The task result contains the parsed [`DicomFile`](../../dicomfile).

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Thrown when ReadLargeTagOnDemandStrategy is used (unsupported for pipe input). |
| OperationCanceledException | The operation was canceled via *cancellationToken*. |

### See Also

* record [ReadDicomPipeOptions](../../../aspose.medical.dicom.readers/readdicompipeoptions)
* interface [ITagDataReadingStrategy](../../../aspose.medical.dicom.readers/itagdatareadingstrategy)
* class [DicomFile](../../dicomfile)
* namespace [Aspose.Medical.Dicom](../../dicomfile)
* assembly [Aspose.Medical](../../../)

---

## OpenAsync(Stream, ReadDicomStreamOptions, ITagDataReadingStrategy, CancellationToken) {#openasync_2}

Asynchronously reads a DICOM file from a Stream and returns the [`DicomFile`](../../dicomfile).

```csharp
public static ValueTask<DicomFile> OpenAsync(Stream stream, ReadDicomStreamOptions? options = null, 
    ITagDataReadingStrategy? strategy = null, CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream containing DICOM data. |
| options | ReadDicomStreamOptions | Stream-read options (fallback encoding, buffer tuning, etc.). |
| strategy | ITagDataReadingStrategy | Tag data access strategy (e.g., immediate, deferred, or selective large-value handling). |
| cancellationToken | CancellationToken | A token to cancel the asynchronous operation. The default value is None. |

### Return Value

A ValueTask that represents the asynchronous operation. The task result contains the parsed [`DicomFile`](../../dicomfile).

### Exceptions

| exception | condition |
| --- | --- |
| [BadDicomFileException](../../../aspose.medical.dicom.errors/baddicomfileexception) | *stream* does not contain a valid DICOM file. |
| OperationCanceledException | The operation was canceled via *cancellationToken*. |

### See Also

* record [ReadDicomStreamOptions](../../../aspose.medical.dicom.readers/readdicomstreamoptions)
* interface [ITagDataReadingStrategy](../../../aspose.medical.dicom.readers/itagdatareadingstrategy)
* class [DicomFile](../../dicomfile)
* namespace [Aspose.Medical.Dicom](../../dicomfile)
* assembly [Aspose.Medical](../../../)

---

## OpenAsync(string, ReadDicomFileOptions, ITagDataReadingStrategy, CancellationToken) {#openasync_3}

Asynchronously reads a DICOM file from a file path and returns the [`DicomFile`](../../dicomfile).

```csharp
public static ValueTask<DicomFile> OpenAsync(string file, ReadDicomFileOptions? options = null, 
    ITagDataReadingStrategy? strategy = null, CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| file | String | The path to the DICOM file. |
| options | ReadDicomFileOptions | File-read options (fallback encoding, buffer tuning, etc.). |
| strategy | ITagDataReadingStrategy | Tag data access strategy (e.g., immediate, deferred, or selective large-value handling). |
| cancellationToken | CancellationToken | A token to cancel the asynchronous operation. The default value is None. |

### Return Value

A ValueTask that represents the asynchronous operation. The task result contains the parsed [`DicomFile`](../../dicomfile).

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *file* is `null` or whitespace. |
| FileNotFoundException | The file specified by *file* was not found. |
| [BadDicomFileException](../../../aspose.medical.dicom.errors/baddicomfileexception) | *file* is not a valid DICOM file. |
| OperationCanceledException | The operation was canceled via *cancellationToken*. |

### See Also

* record [ReadDicomFileOptions](../../../aspose.medical.dicom.readers/readdicomfileoptions)
* interface [ITagDataReadingStrategy](../../../aspose.medical.dicom.readers/itagdatareadingstrategy)
* class [DicomFile](../../dicomfile)
* namespace [Aspose.Medical.Dicom](../../dicomfile)
* assembly [Aspose.Medical](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Medical.dll -->
