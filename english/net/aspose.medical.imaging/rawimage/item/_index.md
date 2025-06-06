---
title: Item
second_title: Aspose.Medical for .NET API Reference
description: Gets or sets the pixel at the specified position.
type: docs
weight: 30
url: /net/aspose.medical.imaging/rawimage/item/
---

## RawImage indexer

Gets or sets the pixel at the specified position.

```csharp
public Bgra32 this[int x, int y] { get; }
```

| Parameter | Description |
| --- | --- |
| x | The x-coordinate of the pixel. Must be greater than or equal to zero and less than the width of the image. |
| y | The y-coordinate of the pixel. Must be greater than or equal to zero and less than the height of the image. |

### Return Value

The  at the specified position.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | Thrown when the provided (x,y) coordinates are outside the image boundary. |

### See Also

* struct [Bgra32](../../../aspose.medical.imaging.pixelformats/bgra32)
* class [RawImage](../../rawimage)
* namespace [Aspose.Medical.Imaging](../../rawimage)
* assembly [Aspose.Medical](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Medical.dll -->
