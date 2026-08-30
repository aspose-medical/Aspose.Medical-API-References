---
title: ValueTaskAsyncWalker
second_title: Aspose.Medical for .NET API Reference
description: Represents an extensible asynchronous visitor that traverses a DICOM file or dataset and its nested datasets in depth-first order using ValueTask-based visit operations.
type: docs
weight: 3060
url: /net/aspose.medical.dicom.traversal/valuetaskasyncwalker/
---

## ValueTaskAsyncWalker class

Represents an extensible asynchronous visitor that traverses a DICOM file or dataset and its nested datasets in depth-first order using ValueTask-based visit operations.

```csharp
public abstract class ValueTaskAsyncWalker
```

## Methods

| Name | Description |
| --- | --- |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/valuetaskasyncwalker/visitasync#visitasync_2)(AgeString, CancellationToken) | Defines the asynchronous visit operation for an [`AgeString`](../../aspose.medical.dicom.elements/agestring) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/valuetaskasyncwalker/visitasync#visitasync_3)(ApplicationEntity, CancellationToken) | Defines the asynchronous visit operation for an [`ApplicationEntity`](../../aspose.medical.dicom.elements/applicationentity) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/valuetaskasyncwalker/visitasync#visitasync_4)(AttributeTag, CancellationToken) | Defines the asynchronous visit operation for an [`AttributeTag`](../../aspose.medical.dicom.elements/attributetag) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/valuetaskasyncwalker/visitasync#visitasync_5)(CodeString, CancellationToken) | Defines the asynchronous visit operation for a [`CodeString`](../../aspose.medical.dicom.elements/codestring) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/valuetaskasyncwalker/visitasync#visitasync)(Dataset, CancellationToken) | Visits each element in the dataset in enumeration order and recursively traverses nested datasets. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/valuetaskasyncwalker/visitasync#visitasync_6)(Date, CancellationToken) | Defines the asynchronous visit operation for a [`Date`](../../aspose.medical.dicom.elements/date) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/valuetaskasyncwalker/visitasync#visitasync_7)(DateTime, CancellationToken) | Defines the asynchronous visit operation for a [`DateTime`](../../aspose.medical.dicom.elements/datetime) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/valuetaskasyncwalker/visitasync#visitasync_8)(DecimalString, CancellationToken) | Defines the asynchronous visit operation for a [`DecimalString`](../../aspose.medical.dicom.elements/decimalstring) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/valuetaskasyncwalker/visitasync#visitasync_1)(DicomFile, CancellationToken) | Visits the file meta information followed by the main dataset. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/valuetaskasyncwalker/visitasync#visitasync_9)(FloatingPointDouble, CancellationToken) | Defines the asynchronous visit operation for a [`FloatingPointDouble`](../../aspose.medical.dicom.elements/floatingpointdouble) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/valuetaskasyncwalker/visitasync#visitasync_10)(FloatingPointSingle, CancellationToken) | Defines the asynchronous visit operation for a [`FloatingPointSingle`](../../aspose.medical.dicom.elements/floatingpointsingle) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/valuetaskasyncwalker/visitasync#visitasync_11)(IElement, CancellationToken) | Dispatches a traversable element to the visit operation corresponding to its runtime type. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/valuetaskasyncwalker/visitasync#visitasync_12)(IntegerString, CancellationToken) | Defines the asynchronous visit operation for an [`IntegerString`](../../aspose.medical.dicom.elements/integerstring) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/valuetaskasyncwalker/visitasync#visitasync_13)(LongString, CancellationToken) | Defines the asynchronous visit operation for a [`LongString`](../../aspose.medical.dicom.elements/longstring) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/valuetaskasyncwalker/visitasync#visitasync_14)(LongText, CancellationToken) | Defines the asynchronous visit operation for a [`LongText`](../../aspose.medical.dicom.elements/longtext) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/valuetaskasyncwalker/visitasync#visitasync_15)(OtherByte, CancellationToken) | Defines the asynchronous visit operation for an [`OtherByte`](../../aspose.medical.dicom.elements/otherbyte) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/valuetaskasyncwalker/visitasync#visitasync_16)(OtherDouble, CancellationToken) | Defines the asynchronous visit operation for an [`OtherDouble`](../../aspose.medical.dicom.elements/otherdouble) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/valuetaskasyncwalker/visitasync#visitasync_17)(OtherFloat, CancellationToken) | Defines the asynchronous visit operation for an [`OtherFloat`](../../aspose.medical.dicom.elements/otherfloat) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/valuetaskasyncwalker/visitasync#visitasync_18)(OtherLong, CancellationToken) | Defines the asynchronous visit operation for an [`OtherLong`](../../aspose.medical.dicom.elements/otherlong) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/valuetaskasyncwalker/visitasync#visitasync_19)(OtherVeryLong, CancellationToken) | Defines the asynchronous visit operation for an [`OtherVeryLong`](../../aspose.medical.dicom.elements/otherverylong) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/valuetaskasyncwalker/visitasync#visitasync_20)(OtherWord, CancellationToken) | Defines the asynchronous visit operation for an [`OtherWord`](../../aspose.medical.dicom.elements/otherword) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/valuetaskasyncwalker/visitasync#visitasync_21)(PersonName, CancellationToken) | Defines the asynchronous visit operation for a [`PersonName`](../../aspose.medical.dicom.elements/personname) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/valuetaskasyncwalker/visitasync#visitasync_22)(ShortString, CancellationToken) | Defines the asynchronous visit operation for a [`ShortString`](../../aspose.medical.dicom.elements/shortstring) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/valuetaskasyncwalker/visitasync#visitasync_23)(ShortText, CancellationToken) | Defines the asynchronous visit operation for a [`ShortText`](../../aspose.medical.dicom.elements/shorttext) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/valuetaskasyncwalker/visitasync#visitasync_24)(SignedLong, CancellationToken) | Defines the asynchronous visit operation for a [`SignedLong`](../../aspose.medical.dicom.elements/signedlong) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/valuetaskasyncwalker/visitasync#visitasync_25)(SignedShort, CancellationToken) | Defines the asynchronous visit operation for a [`SignedShort`](../../aspose.medical.dicom.elements/signedshort) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/valuetaskasyncwalker/visitasync#visitasync_26)(SignedVeryLong, CancellationToken) | Defines the asynchronous visit operation for a [`SignedVeryLong`](../../aspose.medical.dicom.elements/signedverylong) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/valuetaskasyncwalker/visitasync#visitasync_27)(Time, CancellationToken) | Defines the asynchronous visit operation for a [`Time`](../../aspose.medical.dicom.elements/time) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/valuetaskasyncwalker/visitasync#visitasync_28)(UniqueIdentifier, CancellationToken) | Defines the asynchronous visit operation for a [`UniqueIdentifier`](../../aspose.medical.dicom.elements/uniqueidentifier) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/valuetaskasyncwalker/visitasync#visitasync_29)(UniversalResource, CancellationToken) | Defines the asynchronous visit operation for a [`UniversalResource`](../../aspose.medical.dicom.elements/universalresource) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/valuetaskasyncwalker/visitasync#visitasync_30)(Unknown, CancellationToken) | Defines the asynchronous visit operation for an [`Unknown`](../../aspose.medical.dicom.elements/unknown) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/valuetaskasyncwalker/visitasync#visitasync_31)(UnlimitedCharacters, CancellationToken) | Defines the asynchronous visit operation for an [`UnlimitedCharacters`](../../aspose.medical.dicom.elements/unlimitedcharacters) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/valuetaskasyncwalker/visitasync#visitasync_32)(UnlimitedText, CancellationToken) | Defines the asynchronous visit operation for an [`UnlimitedText`](../../aspose.medical.dicom.elements/unlimitedtext) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/valuetaskasyncwalker/visitasync#visitasync_33)(UnsignedLong, CancellationToken) | Defines the asynchronous visit operation for an [`UnsignedLong`](../../aspose.medical.dicom.elements/unsignedlong) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/valuetaskasyncwalker/visitasync#visitasync_34)(UnsignedShort, CancellationToken) | Defines the asynchronous visit operation for an [`UnsignedShort`](../../aspose.medical.dicom.elements/unsignedshort) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/valuetaskasyncwalker/visitasync#visitasync_35)(UnsignedVeryLong, CancellationToken) | Defines the asynchronous visit operation for an [`UnsignedVeryLong`](../../aspose.medical.dicom.elements/unsignedverylong) element. |
| virtual [VisitBeginFragmentAsync](../../aspose.medical.dicom.traversal/valuetaskasyncwalker/visitbeginfragmentasync)(FragmentSequence, CancellationToken) | Defines the asynchronous operation invoked before any item of the fragment sequence is visited. |
| virtual [VisitBeginSequenceAsync](../../aspose.medical.dicom.traversal/valuetaskasyncwalker/visitbeginsequenceasync)(Sequence, CancellationToken) | Defines the asynchronous operation invoked before any item of the sequence is visited. |
| virtual [VisitBeginSequenceItemAsync](../../aspose.medical.dicom.traversal/valuetaskasyncwalker/visitbeginsequenceitemasync)(Sequence, Dataset, CancellationToken) | Defines the asynchronous operation invoked immediately before a sequence item is visited. |
| virtual [VisitEndFragmentAsync](../../aspose.medical.dicom.traversal/valuetaskasyncwalker/visitendfragmentasync)(FragmentSequence, CancellationToken) | Defines the asynchronous operation invoked after every item of the fragment sequence has been visited. |
| virtual [VisitEndSequenceAsync](../../aspose.medical.dicom.traversal/valuetaskasyncwalker/visitendsequenceasync)(Sequence, CancellationToken) | Defines the asynchronous operation invoked after every item of the sequence has been visited. |
| virtual [VisitEndSequenceItemAsync](../../aspose.medical.dicom.traversal/valuetaskasyncwalker/visitendsequenceitemasync)(Sequence, Dataset, CancellationToken) | Defines the asynchronous operation invoked after a sequence item and its nested elements have been visited. |
| virtual [VisitFragmentItemAsync](../../aspose.medical.dicom.traversal/valuetaskasyncwalker/visitfragmentitemasync)(FragmentSequence, byte[], CancellationToken) | Defines the asynchronous visit operation for one item of a fragment sequence. |

### Remarks

Traversal is sequential: each visit operation completes before traversal advances to the next element. The supplied cancellation token is forwarded to nested and type-specific visit operations. Type-specific visit operations complete without performing an action unless overridden.

### See Also

* namespace [Aspose.Medical.Dicom.Traversal](../../aspose.medical.dicom.traversal)
* assembly [Aspose.Medical](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Medical.dll -->
