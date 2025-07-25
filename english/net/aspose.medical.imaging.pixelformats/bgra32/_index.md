---
title: Bgra32
second_title: Aspose.Medical for .NET API Reference
description: Packed pixel contains four 8-bit unsigned normalized values 0..255. The components are stored in Blue Green Red and Alpha order least significant to most significant byte. NOTE the structure is mutable.
type: docs
weight: 1210
url: /net/aspose.medical.imaging.pixelformats/bgra32/
---

## Bgra32 structure

Packed pixel: contains four 8-bit unsigned normalized values [0..255]. The components are stored in Blue, Green, Red, and Alpha order (least significant to most significant byte). NOTE: the structure is mutable.

```csharp
public struct Bgra32 : IPixel<Bgra32>
```

## Constructors

| Name | Description |
| --- | --- |
| [Bgra32](bgra32#constructor)(byte, byte, byte) | Initializes a new instance of the [`Bgra32`](../bgra32) struct. |
| [Bgra32](bgra32#constructor_1)(byte, byte, byte, byte) | Initializes a new instance of the [`Bgra32`](../bgra32) struct. |

## Methods

| Name | Description |
| --- | --- |
| static [FromRgba32](../../aspose.medical.imaging.pixelformats/bgra32/fromrgba32)(Rgba32) |  |
| static [FromScaledVector4](../../aspose.medical.imaging.pixelformats/bgra32/fromscaledvector4)(Vector4) |  |
| static [FromUnscaledVector4](../../aspose.medical.imaging.pixelformats/bgra32/fromunscaledvector4)(Vector4) |  |
| [Equals](../../aspose.medical.imaging.pixelformats/bgra32/equals#equals)(Bgra32) |  |
| override [Equals](../../aspose.medical.imaging.pixelformats/bgra32/equals#equals_1)(object) |  |
| override [GetHashCode](../../aspose.medical.imaging.pixelformats/bgra32/gethashcode)() |  |
| [Pack&lt;T&gt;](../../aspose.medical.imaging.pixelformats/bgra32/pack)(T) | Packs the given numeric pixel value into [`Bgra32`](../bgra32) pixel. |
| [ToScaledVector4](../../aspose.medical.imaging.pixelformats/bgra32/toscaledvector4)() |  |
| override [ToString](../../aspose.medical.imaging.pixelformats/bgra32/tostring)() |  |
| [ToUnscaledVector4](../../aspose.medical.imaging.pixelformats/bgra32/tounscaledvector4)() |  |
| [operator ==](../../aspose.medical.imaging.pixelformats/bgra32/op_equality) | Compares two [`Bgra32`](../bgra32) objects for equality. |
| [operator !=](../../aspose.medical.imaging.pixelformats/bgra32/op_inequality) | Compares two [`Bgra32`](../bgra32) objects for equality. |

## Fields

| Name | Description |
| --- | --- |
| static readonly [Black](../../aspose.medical.imaging.pixelformats/bgra32/black) | Black (0, 0, 0, 255) pixel. |
| static readonly [White](../../aspose.medical.imaging.pixelformats/bgra32/white) | White (255, 255, 255, 255) pixel. |
| [A](../../aspose.medical.imaging.pixelformats/bgra32/a) | The alpha component. |
| [B](../../aspose.medical.imaging.pixelformats/bgra32/b) | The blue component. |
| [G](../../aspose.medical.imaging.pixelformats/bgra32/g) | The green component. |
| [R](../../aspose.medical.imaging.pixelformats/bgra32/r) | The red component. |

### See Also

* interface [IPixel&lt;TSelf&gt;](../ipixel-1)
* namespace [Aspose.Medical.Imaging.PixelFormats](../../aspose.medical.imaging.pixelformats)
* assembly [Aspose.Medical](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Medical.dll -->
