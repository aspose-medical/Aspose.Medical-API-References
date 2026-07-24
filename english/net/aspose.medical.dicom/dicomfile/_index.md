---
title: DicomFile
second_title: Aspose.Medical for .NET API Reference
description: Encapsulates basic DICOM functionality.
type: docs
weight: 400
url: /net/aspose.medical.dicom/dicomfile/
---

## DicomFile class

Encapsulates basic DICOM functionality.

```csharp
public sealed class DicomFile
```

## Constructors

| Name | Description |
| --- | --- |
| [DicomFile](dicomfile#constructor)() | Initializes a new instance of the [`DicomFile`](../dicomfile) class. |
| [DicomFile](dicomfile#constructor_1)(Dataset) | Initializes a new instance of the [`DicomFile`](../dicomfile) class with the given *dataset*. |
| [DicomFile](dicomfile#constructor_2)(DicomFile) | Initializes a new instance of the [`DicomFile`](../dicomfile) class using the data from the given *file*. |
| [DicomFile](dicomfile#constructor_3)(MetaInformation, Dataset) | Initializes a new instance of the [`DicomFile`](../dicomfile) class with the given *dataset*. |

## Properties

| Name | Description |
| --- | --- |
| [Dataset](../../aspose.medical.dicom/dicomfile/dataset) { get; } | DICOM File Dataset. Read-only [`Dataset`](./dataset). |
| [MetaInfo](../../aspose.medical.dicom/dicomfile/metainfo) { get; } | DICOM File Meta Information. Read-only [`MetaInformation`](../metainformation). |
| [NumberOfFrames](../../aspose.medical.dicom/dicomfile/numberofframes) { get; } | The number of frames in the DICOM file. Read-only, Int32. |

## Methods

| Name | Description |
| --- | --- |
| static [Open](../../aspose.medical.dicom/dicomfile/open#open)(Pipe, ReadDicomPipeOptions?, ITagDataReadingStrategy?) | Reads a DICOM file from a Pipe and returns the [`DicomFile`](../dicomfile). |
| static [Open](../../aspose.medical.dicom/dicomfile/open#open_1)(PipeReader, ReadDicomPipeOptions?, ITagDataReadingStrategy?) | Reads a DICOM file from a PipeReader and returns the [`DicomFile`](../dicomfile). |
| static [Open](../../aspose.medical.dicom/dicomfile/open#open_2)(Stream, ReadDicomStreamOptions?, ITagDataReadingStrategy?) | Reads a DICOM file from a Stream and returns the [`DicomFile`](../dicomfile). |
| static [Open](../../aspose.medical.dicom/dicomfile/open#open_3)(string, ReadDicomFileOptions?, ITagDataReadingStrategy?) | Reads a DICOM file from a file path and returns the [`DicomFile`](../dicomfile). |
| [RenderImage](../../aspose.medical.dicom/dicomfile/renderimage#renderimage_1)(int) | Renders a frame from the DICOM `Pixel Data` element as a BGRA pixel image. |
| [RenderImage](../../aspose.medical.dicom/dicomfile/renderimage#renderimage)(RenderOptions, int) | Renders a frame from the DICOM `Pixel Data` element as a BGRA 32 pixel image. |
| [Save](../../aspose.medical.dicom/dicomfile/save#save)(Stream, SaveDicomToStreamOptions?) | Saves DICOM file into the given stream. |
| [Save](../../aspose.medical.dicom/dicomfile/save#save_1)(string, SaveDicomToFileOptions?) | Saves DICOM file into the given file. |
| [SaveAsync](../../aspose.medical.dicom/dicomfile/saveasync#saveasync_2)(Stream, SaveDicomToStreamOptions?, CancellationToken) | Asynchronously saves DICOM file into the given stream. |
| [SaveAsync](../../aspose.medical.dicom/dicomfile/saveasync#saveasync_3)(string, SaveDicomToFileOptions?, CancellationToken) | Asynchronously saves DICOM file into the given file. |
| [SaveAsync](../../aspose.medical.dicom/dicomfile/saveasync#saveasync)(Pipe, bool, SaveDicomToPipeOptions?, CancellationToken) | Asynchronously saves this DICOM file to a Pipe using the specified save options. |
| [SaveAsync](../../aspose.medical.dicom/dicomfile/saveasync#saveasync_1)(PipeWriter, bool, SaveDicomToPipeOptions?, CancellationToken) | Asynchronously saves this DICOM file to a PipeWriter using the specified save options. |
| [Transcode](../../aspose.medical.dicom/dicomfile/transcode)(TransferSyntax) | Transcodes this [`DicomFile`](../dicomfile) from [`MetaInfo`](./metainfo).[`TransferSyntax`](../metainformation/transfersyntax) to the given *syntax*. |
| static [OpenAsync](../../aspose.medical.dicom/dicomfile/openasync#openasync)(Pipe, ReadDicomPipeOptions, ITagDataReadingStrategy, CancellationToken) | Asynchronously reads a DICOM file from a Pipe and returns the [`DicomFile`](../dicomfile). |
| static [OpenAsync](../../aspose.medical.dicom/dicomfile/openasync#openasync_1)(PipeReader, ReadDicomPipeOptions, ITagDataReadingStrategy, CancellationToken) | Asynchronously reads a DICOM file from a PipeReader and returns the [`DicomFile`](../dicomfile). |
| static [OpenAsync](../../aspose.medical.dicom/dicomfile/openasync#openasync_2)(Stream, ReadDicomStreamOptions, ITagDataReadingStrategy, CancellationToken) | Asynchronously reads a DICOM file from a Stream and returns the [`DicomFile`](../dicomfile). |
| static [OpenAsync](../../aspose.medical.dicom/dicomfile/openasync#openasync_3)(string, ReadDicomFileOptions, ITagDataReadingStrategy, CancellationToken) | Asynchronously reads a DICOM file from a file path and returns the [`DicomFile`](../dicomfile). |

### See Also

* namespace [Aspose.Medical.Dicom](../../aspose.medical.dicom)
* assembly [Aspose.Medical](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Medical.dll -->
