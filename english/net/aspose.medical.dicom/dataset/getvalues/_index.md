---
title: GetValues
second_title: Aspose.Medical for .NET API Reference
description: Gets the element values of the specified tag.
type: docs
weight: 160
url: /net/aspose.medical.dicom/dataset/getvalues/
---

## GetValues&lt;T&gt;(Tag) {#getvalues}

Gets the element values of the specified *tag*.

```csharp
public Span<T> GetValues<T>(Tag tag)
```

| Parameter | Description |
| --- | --- |
| T | Type of the return value (collections aren't allowed). |
| tag | The requested DICOM tag. |

### Return Value

The *T* element values corresponding to *tag*.

### Exceptions

| exception | condition |
| --- | --- |
| [MedicalApiException](../../../aspose.medical.errors/medicalapiexception) | The dataset does not contain *tag* or element's value can't be converted to the specified type. |

### See Also

* class [Tag](../../../aspose.medical.dicom.tags/tag)
* class [Dataset](../../dataset)
* namespace [Aspose.Medical.Dicom](../../dataset)
* assembly [Aspose.Medical](../../../)

---

## GetValues&lt;T&gt;(Tag, Range) {#getvalues_1}

Gets the element values of the specified *tag*.

```csharp
public Span<T> GetValues<T>(Tag tag, Range range)
```

| Parameter | Description |
| --- | --- |
| T | Type of the return value (collections aren't allowed). |
| tag | The requested DICOM tag. |
| range | The range of the element values to retrieve. |

### Return Value

The *T* element values corresponding to *tag*.

### Exceptions

| exception | condition |
| --- | --- |
| [MedicalApiException](../../../aspose.medical.errors/medicalapiexception) | The dataset does not contain *tag* or element's value can't be converted to the specified type. |

### See Also

* class [Tag](../../../aspose.medical.dicom.tags/tag)
* class [Dataset](../../dataset)
* namespace [Aspose.Medical.Dicom](../../dataset)
* assembly [Aspose.Medical](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Medical.dll -->
