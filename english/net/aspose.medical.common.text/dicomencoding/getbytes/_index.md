---
title: GetBytes
second_title: Aspose.Medical for .NET API Reference
description: Encodes all the characters in the specified string into a Bytes array.
type: docs
weight: 30
url: /net/aspose.medical.common.text/dicomencoding/getbytes/
---

## DicomEncoding.GetBytes method

Encodes all the characters in the specified string into a Byte's array.

```csharp
public virtual byte[] GetBytes(string data, Encoding[] encodings, byte paddingValue, 
    ReadOnlySpan<byte> delimiters)
```

| Parameter | Type | Description |
| --- | --- | --- |
| data | String | The string containing the characters to encode. |
| encodings | Encoding[] | Encodings used to encode the given *data*. |
| paddingValue | Byte | Byte value used to pad result Byte's array to even length. |
| delimiters | ReadOnlySpan`1 | Delimiters in text values that reset the encoding. |

### Return Value

A Byte array containing the results of encoding the specified set of characters.

### See Also

* class [DicomEncoding](../../dicomencoding)
* namespace [Aspose.Medical.Common.Text](../../dicomencoding)
* assembly [Aspose.Medical](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Medical.dll -->
