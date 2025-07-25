---
title: TagDataReadingStrategies
second_title: Aspose.Medical for .NET API Reference
description: Provides different strategies for controlling how DICOM tag data is accessed from a dataset.
type: docs
weight: 940
url: /net/aspose.medical.dicom.readers/tagdatareadingstrategies/
---

## TagDataReadingStrategies class

Provides different strategies for controlling how DICOM tag data is accessed from a dataset.

```csharp
public static class TagDataReadingStrategies
```

## Methods

| Name | Description |
| --- | --- |
| static [ReadAll](../../aspose.medical.dicom.readers/tagdatareadingstrategies/readall)() | Returns a reading strategy that immediately loads all DICOM tag data into memory. |
| static [ReadLargeOnDemand](../../aspose.medical.dicom.readers/tagdatareadingstrategies/readlargeondemand)(int) | Creates a reading strategy that defers the loading of large DICOM tags until explicitly accessed. |
| static [SkipLargeTags](../../aspose.medical.dicom.readers/tagdatareadingstrategies/skiplargetags)(int) | Returns a reading strategy that skips loading of large DICOM tags to reduce memory usage. |

### See Also

* namespace [Aspose.Medical.Dicom.Readers](../../aspose.medical.dicom.readers)
* assembly [Aspose.Medical](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Medical.dll -->
