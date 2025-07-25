---
title: DicomEncoding
second_title: Aspose.Medical for .NET API Reference
description: Handles alternate character sets for DICOM character strings.
type: docs
weight: 10
url: /net/aspose.medical.common.text/dicomencoding/
---

## DicomEncoding class

Handles alternate character sets for DICOM character strings.

```csharp
public class DicomEncoding : IDicomEncoding
```

## Properties

| Name | Description |
| --- | --- |
| static [Current](../../aspose.medical.common.text/dicomencoding/current) { get; } | The current instance of the [`DicomEncoding`](../dicomencoding). Read-only, [`DicomEncoding`](../dicomencoding). |

## Methods

| Name | Description |
| --- | --- |
| virtual [Decode](../../aspose.medical.common.text/dicomencoding/decode)(Span&lt;byte&gt;, Encoding[], ReadOnlySpan&lt;byte&gt;) | Decodes all the byte fragments in the specified Byte array into a String using a set of the given *encodings*. |
| virtual [GetByteCount](../../aspose.medical.common.text/dicomencoding/getbytecount)(string, Encoding[], ReadOnlySpan&lt;byte&gt;) |  |
| virtual [GetBytes](../../aspose.medical.common.text/dicomencoding/getbytes)(string, Encoding[], byte, ReadOnlySpan&lt;byte&gt;) | Encodes all the characters in the specified string into a Byte's array. |
| virtual [GetCharset](../../aspose.medical.common.text/dicomencoding/getcharset)(Encoding, bool) | Get DICOM character set from .NET Encoding. |
| [GetEncoding](../../aspose.medical.common.text/dicomencoding/getencoding)(string) | Returns the Encoding corresponding to *charset* (DICOM Specific Character Set). |
| [GetEncodings](../../aspose.medical.common.text/dicomencoding/getencodings)(string[]) | Returns a collection of Encoding corresponding to the given *charsets*, where every *charsets* item is a name of the DICOM Specific Character Set. |
| [RegisterEncoding](../../aspose.medical.common.text/dicomencoding/registerencoding)(string, string) | Registers an encoding for a specific character set value. |
| [RegisterProvider](../../aspose.medical.common.text/dicomencoding/registerprovider)(EncodingProvider) | Registers an encoding provider. |

## Fields

| Name | Description |
| --- | --- |
| static readonly [Default](../../aspose.medical.common.text/dicomencoding/default) | Default encoding used in DICOM. |
| static readonly [Defaults](../../aspose.medical.common.text/dicomencoding/defaults) | Default encodings used in DICOM. |

### See Also

* interface [IDicomEncoding](../idicomencoding)
* namespace [Aspose.Medical.Common.Text](../../aspose.medical.common.text)
* assembly [Aspose.Medical](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Medical.dll -->
