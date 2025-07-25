---
title: ModalityRescaleLookUpTable
second_title: Aspose.Medical for .NET API Reference
description: Represents Modality Rescale LUT Modality LUT Module when Rescale Slope or Rescale Intercept are used at least one of them. The output ranges from minimum pixel valueRescale SlopeRescale Intercept to maximum pixel valueRescale SlopeRescale Intercept where the minimum and maximum pixel values are determined by Bits Stored and Pixel Representation. See https//dicom.nema.org/medical/dicom/current/output/chtml/part03/sect_C.11.html
type: docs
weight: 800
url: /net/aspose.medical.dicom.lookuptables/modalityrescalelookuptable/
---

## ModalityRescaleLookUpTable class

Represents 'Modality Rescale LUT', 'Modality LUT Module' when 'Rescale Slope' or 'Rescale Intercept' are used (at least one of them). The output ranges: from (minimum pixel value*Rescale Slope+Rescale Intercept) to (maximum pixel value*Rescale Slope+Rescale Intercept), where the minimum and maximum pixel values are determined by Bits Stored and Pixel Representation. See https://dicom.nema.org/medical/dicom/current/output/chtml/part03/sect_C.11.html

```csharp
public sealed class ModalityRescaleLookUpTable : IModalityLookUpTable
```

## Constructors

| Name | Description |
| --- | --- |
| [ModalityRescaleLookUpTable](modalityrescalelookuptable)(GrayscaleRenderOptions) | Initialize new instance of [`ModalityRescaleLookUpTable`](../modalityrescalelookuptable) using the specified slope and intercept parameters |

## Properties

| Name | Description |
| --- | --- |
| [IsValid](../../aspose.medical.dicom.lookuptables/modalityrescalelookuptable/isvalid) { get; } |  |
| [Item](../../aspose.medical.dicom.lookuptables/modalityrescalelookuptable/item) { get; } |  |
| [Maximum](../../aspose.medical.dicom.lookuptables/modalityrescalelookuptable/maximum) { get; } |  |
| [Minimum](../../aspose.medical.dicom.lookuptables/modalityrescalelookuptable/minimum) { get; } |  |
| [RescaleIntercept](../../aspose.medical.dicom.lookuptables/modalityrescalelookuptable/rescaleintercept) { get; } | The modality rescale intercept. Read-only Double. |
| [RescaleSlope](../../aspose.medical.dicom.lookuptables/modalityrescalelookuptable/rescaleslope) { get; } | The modality rescale slope. Read-only Double. |

## Methods

| Name | Description |
| --- | --- |
| [Recalculate](../../aspose.medical.dicom.lookuptables/modalityrescalelookuptable/recalculate)() |  |

### See Also

* interface [IModalityLookUpTable](../imodalitylookuptable)
* namespace [Aspose.Medical.Dicom.LookUpTables](../../aspose.medical.dicom.lookuptables)
* assembly [Aspose.Medical](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Medical.dll -->
