---
title: VisitAsync
second_title: Aspose.Medical for .NET API Reference
description: Visits the file meta information followed by the main dataset.
type: docs
weight: 10
url: /net/aspose.medical.dicom.traversal/asyncwalker/visitasync/
---

## VisitAsync(DicomFile) {#visitasync_1}

Visits the file meta information followed by the main dataset.

```csharp
public virtual Task VisitAsync(DicomFile file)
```

| Parameter | Type | Description |
| --- | --- | --- |
| file | DicomFile | The DICOM file to traverse. |

### Return Value

An operation that completes when both datasets have been visited.

### See Also

* class [DicomFile](../../../aspose.medical.dicom/dicomfile)
* class [AsyncWalker](../../asyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../asyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(Dataset) {#visitasync}

Visits each element in the dataset in enumeration order and recursively traverses nested datasets.

```csharp
public virtual Task VisitAsync(Dataset dataset)
```

| Parameter | Type | Description |
| --- | --- | --- |
| dataset | Dataset | The DICOM dataset to traverse. |

### Return Value

An operation that completes when every element in the dataset has been visited.

### See Also

* class [Dataset](../../../aspose.medical.dicom/dataset)
* class [AsyncWalker](../../asyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../asyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(IElement) {#visitasync_11}

Dispatches a traversable element to the visit operation corresponding to its runtime type.

```csharp
public virtual Task VisitAsync(IElement element)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | IElement | The element to dispatch. |

### Return Value

An operation that completes when the type-specific visit operation has finished.

### Remarks

The default implementation ignores elements that do not support traversal.

### See Also

* interface [IElement](../../../aspose.medical.dicom.elements/ielement)
* class [AsyncWalker](../../asyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../asyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(AttributeTag) {#visitasync_4}

Defines the asynchronous visit operation for an [`AttributeTag`](../../../aspose.medical.dicom.elements/attributetag) element.

```csharp
public virtual Task VisitAsync(AttributeTag element)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | AttributeTag | The element being visited. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [AttributeTag](../../../aspose.medical.dicom.elements/attributetag)
* class [AsyncWalker](../../asyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../asyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(FloatingPointDouble) {#visitasync_9}

Defines the asynchronous visit operation for a [`FloatingPointDouble`](../../../aspose.medical.dicom.elements/floatingpointdouble) element.

```csharp
public virtual Task VisitAsync(FloatingPointDouble element)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | FloatingPointDouble | The element being visited. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [FloatingPointDouble](../../../aspose.medical.dicom.elements/floatingpointdouble)
* class [AsyncWalker](../../asyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../asyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(FloatingPointSingle) {#visitasync_10}

Defines the asynchronous visit operation for a [`FloatingPointSingle`](../../../aspose.medical.dicom.elements/floatingpointsingle) element.

```csharp
public virtual Task VisitAsync(FloatingPointSingle element)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | FloatingPointSingle | The element being visited. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [FloatingPointSingle](../../../aspose.medical.dicom.elements/floatingpointsingle)
* class [AsyncWalker](../../asyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../asyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(OtherByte) {#visitasync_15}

Defines the asynchronous visit operation for an [`OtherByte`](../../../aspose.medical.dicom.elements/otherbyte) element.

```csharp
public virtual Task VisitAsync(OtherByte element)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | OtherByte | The element being visited. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [OtherByte](../../../aspose.medical.dicom.elements/otherbyte)
* class [AsyncWalker](../../asyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../asyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(OtherDouble) {#visitasync_16}

Defines the asynchronous visit operation for an [`OtherDouble`](../../../aspose.medical.dicom.elements/otherdouble) element.

```csharp
public virtual Task VisitAsync(OtherDouble element)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | OtherDouble | The element being visited. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [OtherDouble](../../../aspose.medical.dicom.elements/otherdouble)
* class [AsyncWalker](../../asyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../asyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(OtherFloat) {#visitasync_17}

Defines the asynchronous visit operation for an [`OtherFloat`](../../../aspose.medical.dicom.elements/otherfloat) element.

```csharp
public virtual Task VisitAsync(OtherFloat element)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | OtherFloat | The element being visited. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [OtherFloat](../../../aspose.medical.dicom.elements/otherfloat)
* class [AsyncWalker](../../asyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../asyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(OtherLong) {#visitasync_18}

Defines the asynchronous visit operation for an [`OtherLong`](../../../aspose.medical.dicom.elements/otherlong) element.

```csharp
public virtual Task VisitAsync(OtherLong element)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | OtherLong | The element being visited. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [OtherLong](../../../aspose.medical.dicom.elements/otherlong)
* class [AsyncWalker](../../asyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../asyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(OtherVeryLong) {#visitasync_19}

Defines the asynchronous visit operation for an [`OtherVeryLong`](../../../aspose.medical.dicom.elements/otherverylong) element.

```csharp
public virtual Task VisitAsync(OtherVeryLong element)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | OtherVeryLong | The element being visited. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [OtherVeryLong](../../../aspose.medical.dicom.elements/otherverylong)
* class [AsyncWalker](../../asyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../asyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(OtherWord) {#visitasync_20}

Defines the asynchronous visit operation for an [`OtherWord`](../../../aspose.medical.dicom.elements/otherword) element.

```csharp
public virtual Task VisitAsync(OtherWord element)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | OtherWord | The element being visited. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [OtherWord](../../../aspose.medical.dicom.elements/otherword)
* class [AsyncWalker](../../asyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../asyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(SignedLong) {#visitasync_24}

Defines the asynchronous visit operation for a [`SignedLong`](../../../aspose.medical.dicom.elements/signedlong) element.

```csharp
public virtual Task VisitAsync(SignedLong element)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | SignedLong | The element being visited. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [SignedLong](../../../aspose.medical.dicom.elements/signedlong)
* class [AsyncWalker](../../asyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../asyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(SignedShort) {#visitasync_25}

Defines the asynchronous visit operation for a [`SignedShort`](../../../aspose.medical.dicom.elements/signedshort) element.

```csharp
public virtual Task VisitAsync(SignedShort element)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | SignedShort | The element being visited. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [SignedShort](../../../aspose.medical.dicom.elements/signedshort)
* class [AsyncWalker](../../asyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../asyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(SignedVeryLong) {#visitasync_26}

Defines the asynchronous visit operation for a [`SignedVeryLong`](../../../aspose.medical.dicom.elements/signedverylong) element.

```csharp
public virtual Task VisitAsync(SignedVeryLong element)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | SignedVeryLong | The element being visited. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [SignedVeryLong](../../../aspose.medical.dicom.elements/signedverylong)
* class [AsyncWalker](../../asyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../asyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(Unknown) {#visitasync_30}

Defines the asynchronous visit operation for an [`Unknown`](../../../aspose.medical.dicom.elements/unknown) element.

```csharp
public virtual Task VisitAsync(Unknown element)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | Unknown | The element being visited. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [Unknown](../../../aspose.medical.dicom.elements/unknown)
* class [AsyncWalker](../../asyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../asyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(UnsignedLong) {#visitasync_33}

Defines the asynchronous visit operation for an [`UnsignedLong`](../../../aspose.medical.dicom.elements/unsignedlong) element.

```csharp
public virtual Task VisitAsync(UnsignedLong element)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | UnsignedLong | The element being visited. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [UnsignedLong](../../../aspose.medical.dicom.elements/unsignedlong)
* class [AsyncWalker](../../asyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../asyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(UnsignedShort) {#visitasync_34}

Defines the asynchronous visit operation for an [`UnsignedShort`](../../../aspose.medical.dicom.elements/unsignedshort) element.

```csharp
public virtual Task VisitAsync(UnsignedShort element)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | UnsignedShort | The element being visited. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [UnsignedShort](../../../aspose.medical.dicom.elements/unsignedshort)
* class [AsyncWalker](../../asyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../asyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(UnsignedVeryLong) {#visitasync_35}

Defines the asynchronous visit operation for an [`UnsignedVeryLong`](../../../aspose.medical.dicom.elements/unsignedverylong) element.

```csharp
public virtual Task VisitAsync(UnsignedVeryLong element)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | UnsignedVeryLong | The element being visited. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [UnsignedVeryLong](../../../aspose.medical.dicom.elements/unsignedverylong)
* class [AsyncWalker](../../asyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../asyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(Time) {#visitasync_27}

Defines the asynchronous visit operation for a [`Time`](../../../aspose.medical.dicom.elements/time) element.

```csharp
public virtual Task VisitAsync(Time element)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | Time | The element being visited. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [Time](../../../aspose.medical.dicom.elements/time)
* class [AsyncWalker](../../asyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../asyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(UniqueIdentifier) {#visitasync_28}

Defines the asynchronous visit operation for a [`UniqueIdentifier`](../../../aspose.medical.dicom.elements/uniqueidentifier) element.

```csharp
public virtual Task VisitAsync(UniqueIdentifier element)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | UniqueIdentifier | The element being visited. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [UniqueIdentifier](../../../aspose.medical.dicom.elements/uniqueidentifier)
* class [AsyncWalker](../../asyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../asyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(UniversalResource) {#visitasync_29}

Defines the asynchronous visit operation for a [`UniversalResource`](../../../aspose.medical.dicom.elements/universalresource) element.

```csharp
public virtual Task VisitAsync(UniversalResource element)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | UniversalResource | The element being visited. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [UniversalResource](../../../aspose.medical.dicom.elements/universalresource)
* class [AsyncWalker](../../asyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../asyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(UnlimitedCharacters) {#visitasync_31}

Defines the asynchronous visit operation for an [`UnlimitedCharacters`](../../../aspose.medical.dicom.elements/unlimitedcharacters) element.

```csharp
public virtual Task VisitAsync(UnlimitedCharacters element)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | UnlimitedCharacters | The element being visited. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [UnlimitedCharacters](../../../aspose.medical.dicom.elements/unlimitedcharacters)
* class [AsyncWalker](../../asyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../asyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(AgeString) {#visitasync_2}

Defines the asynchronous visit operation for an [`AgeString`](../../../aspose.medical.dicom.elements/agestring) element.

```csharp
public virtual Task VisitAsync(AgeString element)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | AgeString | The element being visited. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [AgeString](../../../aspose.medical.dicom.elements/agestring)
* class [AsyncWalker](../../asyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../asyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(ApplicationEntity) {#visitasync_3}

Defines the asynchronous visit operation for an [`ApplicationEntity`](../../../aspose.medical.dicom.elements/applicationentity) element.

```csharp
public virtual Task VisitAsync(ApplicationEntity element)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | ApplicationEntity | The element being visited. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [ApplicationEntity](../../../aspose.medical.dicom.elements/applicationentity)
* class [AsyncWalker](../../asyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../asyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(CodeString) {#visitasync_5}

Defines the asynchronous visit operation for a [`CodeString`](../../../aspose.medical.dicom.elements/codestring) element.

```csharp
public virtual Task VisitAsync(CodeString element)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | CodeString | The element being visited. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [CodeString](../../../aspose.medical.dicom.elements/codestring)
* class [AsyncWalker](../../asyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../asyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(Date) {#visitasync_6}

Defines the asynchronous visit operation for a [`Date`](../../../aspose.medical.dicom.elements/date) element.

```csharp
public virtual Task VisitAsync(Date element)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | Date | The element being visited. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [Date](../../../aspose.medical.dicom.elements/date)
* class [AsyncWalker](../../asyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../asyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(DateTime) {#visitasync_7}

Defines the asynchronous visit operation for a [`DateTime`](../../../aspose.medical.dicom.elements/datetime) element.

```csharp
public virtual Task VisitAsync(DateTime element)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | DateTime | The element being visited. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [DateTime](../../../aspose.medical.dicom.elements/datetime)
* class [AsyncWalker](../../asyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../asyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(DecimalString) {#visitasync_8}

Defines the asynchronous visit operation for a [`DecimalString`](../../../aspose.medical.dicom.elements/decimalstring) element.

```csharp
public virtual Task VisitAsync(DecimalString element)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | DecimalString | The element being visited. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [DecimalString](../../../aspose.medical.dicom.elements/decimalstring)
* class [AsyncWalker](../../asyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../asyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(IntegerString) {#visitasync_12}

Defines the asynchronous visit operation for an [`IntegerString`](../../../aspose.medical.dicom.elements/integerstring) element.

```csharp
public virtual Task VisitAsync(IntegerString element)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | IntegerString | The element being visited. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [IntegerString](../../../aspose.medical.dicom.elements/integerstring)
* class [AsyncWalker](../../asyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../asyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(LongString) {#visitasync_13}

Defines the asynchronous visit operation for a [`LongString`](../../../aspose.medical.dicom.elements/longstring) element.

```csharp
public virtual Task VisitAsync(LongString element)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | LongString | The element being visited. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [LongString](../../../aspose.medical.dicom.elements/longstring)
* class [AsyncWalker](../../asyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../asyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(LongText) {#visitasync_14}

Defines the asynchronous visit operation for a [`LongText`](../../../aspose.medical.dicom.elements/longtext) element.

```csharp
public virtual Task VisitAsync(LongText element)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | LongText | The element being visited. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [LongText](../../../aspose.medical.dicom.elements/longtext)
* class [AsyncWalker](../../asyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../asyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(PersonName) {#visitasync_21}

Defines the asynchronous visit operation for a [`PersonName`](../../../aspose.medical.dicom.elements/personname) element.

```csharp
public virtual Task VisitAsync(PersonName element)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | PersonName | The element being visited. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [PersonName](../../../aspose.medical.dicom.elements/personname)
* class [AsyncWalker](../../asyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../asyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(ShortString) {#visitasync_22}

Defines the asynchronous visit operation for a [`ShortString`](../../../aspose.medical.dicom.elements/shortstring) element.

```csharp
public virtual Task VisitAsync(ShortString element)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | ShortString | The element being visited. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [ShortString](../../../aspose.medical.dicom.elements/shortstring)
* class [AsyncWalker](../../asyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../asyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(ShortText) {#visitasync_23}

Defines the asynchronous visit operation for a [`ShortText`](../../../aspose.medical.dicom.elements/shorttext) element.

```csharp
public virtual Task VisitAsync(ShortText element)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | ShortText | The element being visited. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [ShortText](../../../aspose.medical.dicom.elements/shorttext)
* class [AsyncWalker](../../asyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../asyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(UnlimitedText) {#visitasync_32}

Defines the asynchronous visit operation for an [`UnlimitedText`](../../../aspose.medical.dicom.elements/unlimitedtext) element.

```csharp
public virtual Task VisitAsync(UnlimitedText element)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | UnlimitedText | The element being visited. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [UnlimitedText](../../../aspose.medical.dicom.elements/unlimitedtext)
* class [AsyncWalker](../../asyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../asyncwalker)
* assembly [Aspose.Medical](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Medical.dll -->
