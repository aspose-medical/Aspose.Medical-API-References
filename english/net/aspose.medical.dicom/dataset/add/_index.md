---
title: Add
second_title: Aspose.Medical for .NET API Reference
description: Adds the given element to the dataset if the element with the Tagaspose.medical.dicom.elements/ielement/tag is not presented in the dataset or updates element value with the same tag.
type: docs
weight: 20
url: /net/aspose.medical.dicom/dataset/add/
---

## Dataset.Add method

Adds the given element to the dataset if the element with the [`Tag`](../../../aspose.medical.dicom.elements/ielement/tag) is not presented in the dataset or updates element value with the same tag.

```csharp
public void Add(IElement element)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | IElement | A DICOM element to be added. |

### Exceptions

| exception | condition |
| --- | --- |
| [MedicalApiException](../../../aspose.medical.errors/medicalapiexception) | The element with the given tag already exists int this Dataset. |

### See Also

* interface [IElement](../../../aspose.medical.dicom.elements/ielement)
* class [Dataset](../../dataset)
* namespace [Aspose.Medical.Dicom](../../dataset)
* assembly [Aspose.Medical](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Medical.dll -->
