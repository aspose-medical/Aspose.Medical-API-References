---
title: Get
second_title: Aspose.Medical for .NET API Reference
description: Returns the T of the specified tag or default if the tag is not in the dataset.
type: docs
weight: 80
url: /net/aspose.medical.dicom/dataset/get/
---

## Dataset.Get&lt;T&gt; method

Returns the *T* of the specified tag or `default` if the tag is not in the dataset.

```csharp
public T Get<T>(Tag tag)
    where T : class, IElement
```

| Parameter | Type | Description |
| --- | --- | --- |
| tag | Tag | A requested DICOM tag. |

### Return Value

The *T* of the given tag or `default` if the tag is not in the dataset.

### Exceptions

| exception | condition |
| --- | --- |
| [MedicalApiException](../../../aspose.medical.errors/medicalapiexception) | The requested tag is missing in this Dataset. |

### See Also

* class [Tag](../../../aspose.medical.dicom.tags/tag)
* interface [IElement](../../../aspose.medical.dicom.elements/ielement)
* class [Dataset](../../dataset)
* namespace [Aspose.Medical.Dicom](../../dataset)
* assembly [Aspose.Medical](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Medical.dll -->
