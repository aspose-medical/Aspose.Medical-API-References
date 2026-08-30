---
title: VisitAsync
second_title: Aspose.Medical for .NET API Reference
description: Visits the file meta information followed by the main dataset.
type: docs
weight: 10
url: /net/aspose.medical.dicom.traversal/valuetaskasyncwalker/visitasync/
---

## VisitAsync(DicomFile, CancellationToken) {#visitasync_1}

Visits the file meta information followed by the main dataset.

```csharp
public virtual ValueTask VisitAsync(DicomFile file, CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| file | DicomFile | The DICOM file to traverse. |
| cancellationToken | CancellationToken | A token used to cancel the traversal. |

### Return Value

An operation that completes when both datasets have been visited.

### See Also

* class [DicomFile](../../../aspose.medical.dicom/dicomfile)
* class [ValueTaskAsyncWalker](../../valuetaskasyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../valuetaskasyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(Dataset, CancellationToken) {#visitasync}

Visits each element in the dataset in enumeration order and recursively traverses nested datasets.

```csharp
public virtual ValueTask VisitAsync(Dataset dataset, CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| dataset | Dataset | The DICOM dataset to traverse. |
| cancellationToken | CancellationToken | A token used to cancel the traversal. |

### Return Value

An operation that completes when every element in the dataset has been visited.

### See Also

* class [Dataset](../../../aspose.medical.dicom/dataset)
* class [ValueTaskAsyncWalker](../../valuetaskasyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../valuetaskasyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(IElement, CancellationToken) {#visitasync_11}

Dispatches a traversable element to the visit operation corresponding to its runtime type.

```csharp
public virtual ValueTask VisitAsync(IElement element, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | IElement | The element to dispatch. |
| cancellationToken | CancellationToken | The token supplied for the current traversal. |

### Return Value

An operation that completes when the type-specific visit operation has finished.

### Remarks

The default implementation ignores elements that do not support traversal.

### See Also

* interface [IElement](../../../aspose.medical.dicom.elements/ielement)
* class [ValueTaskAsyncWalker](../../valuetaskasyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../valuetaskasyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(AttributeTag, CancellationToken) {#visitasync_4}

Defines the asynchronous visit operation for an [`AttributeTag`](../../../aspose.medical.dicom.elements/attributetag) element.

```csharp
public virtual ValueTask VisitAsync(AttributeTag element, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | AttributeTag | The element being visited. |
| cancellationToken | CancellationToken | The token supplied for the current traversal. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [AttributeTag](../../../aspose.medical.dicom.elements/attributetag)
* class [ValueTaskAsyncWalker](../../valuetaskasyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../valuetaskasyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(FloatingPointDouble, CancellationToken) {#visitasync_9}

Defines the asynchronous visit operation for a [`FloatingPointDouble`](../../../aspose.medical.dicom.elements/floatingpointdouble) element.

```csharp
public virtual ValueTask VisitAsync(FloatingPointDouble element, 
    CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | FloatingPointDouble | The element being visited. |
| cancellationToken | CancellationToken | The token supplied for the current traversal. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [FloatingPointDouble](../../../aspose.medical.dicom.elements/floatingpointdouble)
* class [ValueTaskAsyncWalker](../../valuetaskasyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../valuetaskasyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(FloatingPointSingle, CancellationToken) {#visitasync_10}

Defines the asynchronous visit operation for a [`FloatingPointSingle`](../../../aspose.medical.dicom.elements/floatingpointsingle) element.

```csharp
public virtual ValueTask VisitAsync(FloatingPointSingle element, 
    CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | FloatingPointSingle | The element being visited. |
| cancellationToken | CancellationToken | The token supplied for the current traversal. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [FloatingPointSingle](../../../aspose.medical.dicom.elements/floatingpointsingle)
* class [ValueTaskAsyncWalker](../../valuetaskasyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../valuetaskasyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(OtherByte, CancellationToken) {#visitasync_15}

Defines the asynchronous visit operation for an [`OtherByte`](../../../aspose.medical.dicom.elements/otherbyte) element.

```csharp
public virtual ValueTask VisitAsync(OtherByte element, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | OtherByte | The element being visited. |
| cancellationToken | CancellationToken | The token supplied for the current traversal. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [OtherByte](../../../aspose.medical.dicom.elements/otherbyte)
* class [ValueTaskAsyncWalker](../../valuetaskasyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../valuetaskasyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(OtherDouble, CancellationToken) {#visitasync_16}

Defines the asynchronous visit operation for an [`OtherDouble`](../../../aspose.medical.dicom.elements/otherdouble) element.

```csharp
public virtual ValueTask VisitAsync(OtherDouble element, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | OtherDouble | The element being visited. |
| cancellationToken | CancellationToken | The token supplied for the current traversal. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [OtherDouble](../../../aspose.medical.dicom.elements/otherdouble)
* class [ValueTaskAsyncWalker](../../valuetaskasyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../valuetaskasyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(OtherFloat, CancellationToken) {#visitasync_17}

Defines the asynchronous visit operation for an [`OtherFloat`](../../../aspose.medical.dicom.elements/otherfloat) element.

```csharp
public virtual ValueTask VisitAsync(OtherFloat element, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | OtherFloat | The element being visited. |
| cancellationToken | CancellationToken | The token supplied for the current traversal. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [OtherFloat](../../../aspose.medical.dicom.elements/otherfloat)
* class [ValueTaskAsyncWalker](../../valuetaskasyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../valuetaskasyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(OtherLong, CancellationToken) {#visitasync_18}

Defines the asynchronous visit operation for an [`OtherLong`](../../../aspose.medical.dicom.elements/otherlong) element.

```csharp
public virtual ValueTask VisitAsync(OtherLong element, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | OtherLong | The element being visited. |
| cancellationToken | CancellationToken | The token supplied for the current traversal. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [OtherLong](../../../aspose.medical.dicom.elements/otherlong)
* class [ValueTaskAsyncWalker](../../valuetaskasyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../valuetaskasyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(OtherVeryLong, CancellationToken) {#visitasync_19}

Defines the asynchronous visit operation for an [`OtherVeryLong`](../../../aspose.medical.dicom.elements/otherverylong) element.

```csharp
public virtual ValueTask VisitAsync(OtherVeryLong element, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | OtherVeryLong | The element being visited. |
| cancellationToken | CancellationToken | The token supplied for the current traversal. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [OtherVeryLong](../../../aspose.medical.dicom.elements/otherverylong)
* class [ValueTaskAsyncWalker](../../valuetaskasyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../valuetaskasyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(OtherWord, CancellationToken) {#visitasync_20}

Defines the asynchronous visit operation for an [`OtherWord`](../../../aspose.medical.dicom.elements/otherword) element.

```csharp
public virtual ValueTask VisitAsync(OtherWord element, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | OtherWord | The element being visited. |
| cancellationToken | CancellationToken | The token supplied for the current traversal. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [OtherWord](../../../aspose.medical.dicom.elements/otherword)
* class [ValueTaskAsyncWalker](../../valuetaskasyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../valuetaskasyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(SignedLong, CancellationToken) {#visitasync_24}

Defines the asynchronous visit operation for a [`SignedLong`](../../../aspose.medical.dicom.elements/signedlong) element.

```csharp
public virtual ValueTask VisitAsync(SignedLong element, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | SignedLong | The element being visited. |
| cancellationToken | CancellationToken | The token supplied for the current traversal. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [SignedLong](../../../aspose.medical.dicom.elements/signedlong)
* class [ValueTaskAsyncWalker](../../valuetaskasyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../valuetaskasyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(SignedShort, CancellationToken) {#visitasync_25}

Defines the asynchronous visit operation for a [`SignedShort`](../../../aspose.medical.dicom.elements/signedshort) element.

```csharp
public virtual ValueTask VisitAsync(SignedShort element, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | SignedShort | The element being visited. |
| cancellationToken | CancellationToken | The token supplied for the current traversal. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [SignedShort](../../../aspose.medical.dicom.elements/signedshort)
* class [ValueTaskAsyncWalker](../../valuetaskasyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../valuetaskasyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(SignedVeryLong, CancellationToken) {#visitasync_26}

Defines the asynchronous visit operation for a [`SignedVeryLong`](../../../aspose.medical.dicom.elements/signedverylong) element.

```csharp
public virtual ValueTask VisitAsync(SignedVeryLong element, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | SignedVeryLong | The element being visited. |
| cancellationToken | CancellationToken | The token supplied for the current traversal. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [SignedVeryLong](../../../aspose.medical.dicom.elements/signedverylong)
* class [ValueTaskAsyncWalker](../../valuetaskasyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../valuetaskasyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(Unknown, CancellationToken) {#visitasync_30}

Defines the asynchronous visit operation for an [`Unknown`](../../../aspose.medical.dicom.elements/unknown) element.

```csharp
public virtual ValueTask VisitAsync(Unknown element, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | Unknown | The element being visited. |
| cancellationToken | CancellationToken | The token supplied for the current traversal. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [Unknown](../../../aspose.medical.dicom.elements/unknown)
* class [ValueTaskAsyncWalker](../../valuetaskasyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../valuetaskasyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(UnsignedLong, CancellationToken) {#visitasync_33}

Defines the asynchronous visit operation for an [`UnsignedLong`](../../../aspose.medical.dicom.elements/unsignedlong) element.

```csharp
public virtual ValueTask VisitAsync(UnsignedLong element, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | UnsignedLong | The element being visited. |
| cancellationToken | CancellationToken | The token supplied for the current traversal. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [UnsignedLong](../../../aspose.medical.dicom.elements/unsignedlong)
* class [ValueTaskAsyncWalker](../../valuetaskasyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../valuetaskasyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(UnsignedShort, CancellationToken) {#visitasync_34}

Defines the asynchronous visit operation for an [`UnsignedShort`](../../../aspose.medical.dicom.elements/unsignedshort) element.

```csharp
public virtual ValueTask VisitAsync(UnsignedShort element, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | UnsignedShort | The element being visited. |
| cancellationToken | CancellationToken | The token supplied for the current traversal. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [UnsignedShort](../../../aspose.medical.dicom.elements/unsignedshort)
* class [ValueTaskAsyncWalker](../../valuetaskasyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../valuetaskasyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(UnsignedVeryLong, CancellationToken) {#visitasync_35}

Defines the asynchronous visit operation for an [`UnsignedVeryLong`](../../../aspose.medical.dicom.elements/unsignedverylong) element.

```csharp
public virtual ValueTask VisitAsync(UnsignedVeryLong element, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | UnsignedVeryLong | The element being visited. |
| cancellationToken | CancellationToken | The token supplied for the current traversal. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [UnsignedVeryLong](../../../aspose.medical.dicom.elements/unsignedverylong)
* class [ValueTaskAsyncWalker](../../valuetaskasyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../valuetaskasyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(Time, CancellationToken) {#visitasync_27}

Defines the asynchronous visit operation for a [`Time`](../../../aspose.medical.dicom.elements/time) element.

```csharp
public virtual ValueTask VisitAsync(Time element, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | Time | The element being visited. |
| cancellationToken | CancellationToken | The token supplied for the current traversal. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [Time](../../../aspose.medical.dicom.elements/time)
* class [ValueTaskAsyncWalker](../../valuetaskasyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../valuetaskasyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(UniqueIdentifier, CancellationToken) {#visitasync_28}

Defines the asynchronous visit operation for a [`UniqueIdentifier`](../../../aspose.medical.dicom.elements/uniqueidentifier) element.

```csharp
public virtual ValueTask VisitAsync(UniqueIdentifier element, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | UniqueIdentifier | The element being visited. |
| cancellationToken | CancellationToken | The token supplied for the current traversal. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [UniqueIdentifier](../../../aspose.medical.dicom.elements/uniqueidentifier)
* class [ValueTaskAsyncWalker](../../valuetaskasyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../valuetaskasyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(UniversalResource, CancellationToken) {#visitasync_29}

Defines the asynchronous visit operation for a [`UniversalResource`](../../../aspose.medical.dicom.elements/universalresource) element.

```csharp
public virtual ValueTask VisitAsync(UniversalResource element, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | UniversalResource | The element being visited. |
| cancellationToken | CancellationToken | The token supplied for the current traversal. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [UniversalResource](../../../aspose.medical.dicom.elements/universalresource)
* class [ValueTaskAsyncWalker](../../valuetaskasyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../valuetaskasyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(UnlimitedCharacters, CancellationToken) {#visitasync_31}

Defines the asynchronous visit operation for an [`UnlimitedCharacters`](../../../aspose.medical.dicom.elements/unlimitedcharacters) element.

```csharp
public virtual ValueTask VisitAsync(UnlimitedCharacters element, 
    CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | UnlimitedCharacters | The element being visited. |
| cancellationToken | CancellationToken | The token supplied for the current traversal. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [UnlimitedCharacters](../../../aspose.medical.dicom.elements/unlimitedcharacters)
* class [ValueTaskAsyncWalker](../../valuetaskasyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../valuetaskasyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(AgeString, CancellationToken) {#visitasync_2}

Defines the asynchronous visit operation for an [`AgeString`](../../../aspose.medical.dicom.elements/agestring) element.

```csharp
public virtual ValueTask VisitAsync(AgeString element, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | AgeString | The element being visited. |
| cancellationToken | CancellationToken | The token supplied for the current traversal. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [AgeString](../../../aspose.medical.dicom.elements/agestring)
* class [ValueTaskAsyncWalker](../../valuetaskasyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../valuetaskasyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(ApplicationEntity, CancellationToken) {#visitasync_3}

Defines the asynchronous visit operation for an [`ApplicationEntity`](../../../aspose.medical.dicom.elements/applicationentity) element.

```csharp
public virtual ValueTask VisitAsync(ApplicationEntity element, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | ApplicationEntity | The element being visited. |
| cancellationToken | CancellationToken | The token supplied for the current traversal. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [ApplicationEntity](../../../aspose.medical.dicom.elements/applicationentity)
* class [ValueTaskAsyncWalker](../../valuetaskasyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../valuetaskasyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(CodeString, CancellationToken) {#visitasync_5}

Defines the asynchronous visit operation for a [`CodeString`](../../../aspose.medical.dicom.elements/codestring) element.

```csharp
public virtual ValueTask VisitAsync(CodeString element, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | CodeString | The element being visited. |
| cancellationToken | CancellationToken | The token supplied for the current traversal. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [CodeString](../../../aspose.medical.dicom.elements/codestring)
* class [ValueTaskAsyncWalker](../../valuetaskasyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../valuetaskasyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(Date, CancellationToken) {#visitasync_6}

Defines the asynchronous visit operation for a [`Date`](../../../aspose.medical.dicom.elements/date) element.

```csharp
public virtual ValueTask VisitAsync(Date element, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | Date | The element being visited. |
| cancellationToken | CancellationToken | The token supplied for the current traversal. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [Date](../../../aspose.medical.dicom.elements/date)
* class [ValueTaskAsyncWalker](../../valuetaskasyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../valuetaskasyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(DateTime, CancellationToken) {#visitasync_7}

Defines the asynchronous visit operation for a [`DateTime`](../../../aspose.medical.dicom.elements/datetime) element.

```csharp
public virtual ValueTask VisitAsync(DateTime element, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | DateTime | The element being visited. |
| cancellationToken | CancellationToken | The token supplied for the current traversal. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [DateTime](../../../aspose.medical.dicom.elements/datetime)
* class [ValueTaskAsyncWalker](../../valuetaskasyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../valuetaskasyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(DecimalString, CancellationToken) {#visitasync_8}

Defines the asynchronous visit operation for a [`DecimalString`](../../../aspose.medical.dicom.elements/decimalstring) element.

```csharp
public virtual ValueTask VisitAsync(DecimalString element, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | DecimalString | The element being visited. |
| cancellationToken | CancellationToken | The token supplied for the current traversal. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [DecimalString](../../../aspose.medical.dicom.elements/decimalstring)
* class [ValueTaskAsyncWalker](../../valuetaskasyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../valuetaskasyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(IntegerString, CancellationToken) {#visitasync_12}

Defines the asynchronous visit operation for an [`IntegerString`](../../../aspose.medical.dicom.elements/integerstring) element.

```csharp
public virtual ValueTask VisitAsync(IntegerString element, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | IntegerString | The element being visited. |
| cancellationToken | CancellationToken | The token supplied for the current traversal. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [IntegerString](../../../aspose.medical.dicom.elements/integerstring)
* class [ValueTaskAsyncWalker](../../valuetaskasyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../valuetaskasyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(LongString, CancellationToken) {#visitasync_13}

Defines the asynchronous visit operation for a [`LongString`](../../../aspose.medical.dicom.elements/longstring) element.

```csharp
public virtual ValueTask VisitAsync(LongString element, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | LongString | The element being visited. |
| cancellationToken | CancellationToken | The token supplied for the current traversal. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [LongString](../../../aspose.medical.dicom.elements/longstring)
* class [ValueTaskAsyncWalker](../../valuetaskasyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../valuetaskasyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(LongText, CancellationToken) {#visitasync_14}

Defines the asynchronous visit operation for a [`LongText`](../../../aspose.medical.dicom.elements/longtext) element.

```csharp
public virtual ValueTask VisitAsync(LongText element, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | LongText | The element being visited. |
| cancellationToken | CancellationToken | The token supplied for the current traversal. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [LongText](../../../aspose.medical.dicom.elements/longtext)
* class [ValueTaskAsyncWalker](../../valuetaskasyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../valuetaskasyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(PersonName, CancellationToken) {#visitasync_21}

Defines the asynchronous visit operation for a [`PersonName`](../../../aspose.medical.dicom.elements/personname) element.

```csharp
public virtual ValueTask VisitAsync(PersonName element, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | PersonName | The element being visited. |
| cancellationToken | CancellationToken | The token supplied for the current traversal. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [PersonName](../../../aspose.medical.dicom.elements/personname)
* class [ValueTaskAsyncWalker](../../valuetaskasyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../valuetaskasyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(ShortString, CancellationToken) {#visitasync_22}

Defines the asynchronous visit operation for a [`ShortString`](../../../aspose.medical.dicom.elements/shortstring) element.

```csharp
public virtual ValueTask VisitAsync(ShortString element, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | ShortString | The element being visited. |
| cancellationToken | CancellationToken | The token supplied for the current traversal. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [ShortString](../../../aspose.medical.dicom.elements/shortstring)
* class [ValueTaskAsyncWalker](../../valuetaskasyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../valuetaskasyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(ShortText, CancellationToken) {#visitasync_23}

Defines the asynchronous visit operation for a [`ShortText`](../../../aspose.medical.dicom.elements/shorttext) element.

```csharp
public virtual ValueTask VisitAsync(ShortText element, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | ShortText | The element being visited. |
| cancellationToken | CancellationToken | The token supplied for the current traversal. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [ShortText](../../../aspose.medical.dicom.elements/shorttext)
* class [ValueTaskAsyncWalker](../../valuetaskasyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../valuetaskasyncwalker)
* assembly [Aspose.Medical](../../../)

---

## VisitAsync(UnlimitedText, CancellationToken) {#visitasync_32}

Defines the asynchronous visit operation for an [`UnlimitedText`](../../../aspose.medical.dicom.elements/unlimitedtext) element.

```csharp
public virtual ValueTask VisitAsync(UnlimitedText element, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| element | UnlimitedText | The element being visited. |
| cancellationToken | CancellationToken | The token supplied for the current traversal. |

### Return Value

An operation that completes when the element visit has finished.

### See Also

* class [UnlimitedText](../../../aspose.medical.dicom.elements/unlimitedtext)
* class [ValueTaskAsyncWalker](../../valuetaskasyncwalker)
* namespace [Aspose.Medical.Dicom.Traversal](../../valuetaskasyncwalker)
* assembly [Aspose.Medical](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Medical.dll -->
