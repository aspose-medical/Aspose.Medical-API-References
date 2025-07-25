---
title: UnlimitedText
second_title: Aspose.Medical for .NET API Reference
description: Encapsulates the Unlimited Text UT VR type. https//dicom.nema.org/medical/dicom/current/output/chtml/part05/sect_6.2.htmltextUT-Unlimited20Text-A20character20string.
type: docs
weight: 560
url: /net/aspose.medical.dicom.elements/unlimitedtext/
---

## UnlimitedText class

Encapsulates the Unlimited Text (UT) VR type. https://dicom.nema.org/medical/dicom/current/output/chtml/part05/sect_6.2.html#:~:text=UT-,Unlimited%20Text,-A%20character%20string.

```csharp
public sealed class UnlimitedText : SingleValueTextElement
```

## Constructors

| Name | Description |
| --- | --- |
| [UnlimitedText](unlimitedtext#constructor)(Tag, string?) |  |
| [UnlimitedText](unlimitedtext#constructor_2)(Tag, string?, Encoding) |  |
| [UnlimitedText](unlimitedtext#constructor_1)(Tag, string?, IEnumerable&lt;Encoding&gt;) |  |

## Properties

| Name | Description |
| --- | --- |
| override [Count](../../aspose.medical.dicom.elements/singlevaluetextelement/count) { get; } |  |
| [Data](../../aspose.medical.dicom.elements/singlevaluetextelement/data) { get; set; } | Text element value. Read/Write String. |
| [SerializationEncodings](../../aspose.medical.dicom.elements/singlevaluetextelement/serializationencodings) { get; set; } | A collection of specific character set used to serialize / deserialize this text element data. Read/Write IReadOnlyCollection of Encoding. |
| [Tag](../../aspose.medical.dicom.elements/textelement/tag) { get; } |  |
| override [ValueRepresentation](../../aspose.medical.dicom.elements/unlimitedtext/valuerepresentation) { get; } |  |

## Methods

| Name | Description |
| --- | --- |
| override [Get&lt;T&gt;](../../aspose.medical.dicom.elements/singlevaluetextelement/get)(Index) |  |
| override [Get&lt;T&gt;](../../aspose.medical.dicom.elements/singlevaluetextelement/get)(int) |  |
| override [GetOrDefault&lt;T&gt;](../../aspose.medical.dicom.elements/singlevaluetextelement/getordefault)(Index) |  |
| override [GetOrDefault&lt;T&gt;](../../aspose.medical.dicom.elements/singlevaluetextelement/getordefault)(int) |  |
| override [GetValues&lt;T&gt;](../../aspose.medical.dicom.elements/singlevaluetextelement/getvalues)() |  |
| override [GetValues&lt;T&gt;](../../aspose.medical.dicom.elements/singlevaluetextelement/getvalues)(Range) |  |
| override [ToString](../../aspose.medical.dicom.elements/singlevaluetextelement/tostring)() |  |
| override [TryGetValue&lt;T&gt;](../../aspose.medical.dicom.elements/singlevaluetextelement/trygetvalue)(Index, out T) |  |
| override [TryGetValue&lt;T&gt;](../../aspose.medical.dicom.elements/singlevaluetextelement/trygetvalue)(int, out T) |  |

### See Also

* class [SingleValueTextElement](../singlevaluetextelement)
* namespace [Aspose.Medical.Dicom.Elements](../../aspose.medical.dicom.elements)
* assembly [Aspose.Medical](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Medical.dll -->
