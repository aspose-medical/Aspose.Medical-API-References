---
title: AsyncWalker
second_title: Aspose.Medical for .NET API Reference
description: Represents an extensible asynchronous visitor that traverses a DICOM file or dataset and its nested datasets in depth-first order using Task-based visit operations.
type: docs
weight: 3050
url: /net/aspose.medical.dicom.traversal/asyncwalker/
---

## AsyncWalker class

Represents an extensible asynchronous visitor that traverses a DICOM file or dataset and its nested datasets in depth-first order using Task-based visit operations.

```csharp
public abstract class AsyncWalker
```

## Methods

| Name | Description |
| --- | --- |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/asyncwalker/visitasync#visitasync_2)(AgeString) | Defines the asynchronous visit operation for an [`AgeString`](../../aspose.medical.dicom.elements/agestring) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/asyncwalker/visitasync#visitasync_3)(ApplicationEntity) | Defines the asynchronous visit operation for an [`ApplicationEntity`](../../aspose.medical.dicom.elements/applicationentity) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/asyncwalker/visitasync#visitasync_4)(AttributeTag) | Defines the asynchronous visit operation for an [`AttributeTag`](../../aspose.medical.dicom.elements/attributetag) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/asyncwalker/visitasync#visitasync_5)(CodeString) | Defines the asynchronous visit operation for a [`CodeString`](../../aspose.medical.dicom.elements/codestring) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/asyncwalker/visitasync#visitasync)(Dataset) | Visits each element in the dataset in enumeration order and recursively traverses nested datasets. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/asyncwalker/visitasync#visitasync_6)(Date) | Defines the asynchronous visit operation for a [`Date`](../../aspose.medical.dicom.elements/date) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/asyncwalker/visitasync#visitasync_7)(DateTime) | Defines the asynchronous visit operation for a [`DateTime`](../../aspose.medical.dicom.elements/datetime) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/asyncwalker/visitasync#visitasync_8)(DecimalString) | Defines the asynchronous visit operation for a [`DecimalString`](../../aspose.medical.dicom.elements/decimalstring) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/asyncwalker/visitasync#visitasync_1)(DicomFile) | Visits the file meta information followed by the main dataset. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/asyncwalker/visitasync#visitasync_9)(FloatingPointDouble) | Defines the asynchronous visit operation for a [`FloatingPointDouble`](../../aspose.medical.dicom.elements/floatingpointdouble) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/asyncwalker/visitasync#visitasync_10)(FloatingPointSingle) | Defines the asynchronous visit operation for a [`FloatingPointSingle`](../../aspose.medical.dicom.elements/floatingpointsingle) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/asyncwalker/visitasync#visitasync_11)(IElement) | Dispatches a traversable element to the visit operation corresponding to its runtime type. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/asyncwalker/visitasync#visitasync_12)(IntegerString) | Defines the asynchronous visit operation for an [`IntegerString`](../../aspose.medical.dicom.elements/integerstring) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/asyncwalker/visitasync#visitasync_13)(LongString) | Defines the asynchronous visit operation for a [`LongString`](../../aspose.medical.dicom.elements/longstring) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/asyncwalker/visitasync#visitasync_14)(LongText) | Defines the asynchronous visit operation for a [`LongText`](../../aspose.medical.dicom.elements/longtext) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/asyncwalker/visitasync#visitasync_15)(OtherByte) | Defines the asynchronous visit operation for an [`OtherByte`](../../aspose.medical.dicom.elements/otherbyte) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/asyncwalker/visitasync#visitasync_16)(OtherDouble) | Defines the asynchronous visit operation for an [`OtherDouble`](../../aspose.medical.dicom.elements/otherdouble) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/asyncwalker/visitasync#visitasync_17)(OtherFloat) | Defines the asynchronous visit operation for an [`OtherFloat`](../../aspose.medical.dicom.elements/otherfloat) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/asyncwalker/visitasync#visitasync_18)(OtherLong) | Defines the asynchronous visit operation for an [`OtherLong`](../../aspose.medical.dicom.elements/otherlong) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/asyncwalker/visitasync#visitasync_19)(OtherVeryLong) | Defines the asynchronous visit operation for an [`OtherVeryLong`](../../aspose.medical.dicom.elements/otherverylong) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/asyncwalker/visitasync#visitasync_20)(OtherWord) | Defines the asynchronous visit operation for an [`OtherWord`](../../aspose.medical.dicom.elements/otherword) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/asyncwalker/visitasync#visitasync_21)(PersonName) | Defines the asynchronous visit operation for a [`PersonName`](../../aspose.medical.dicom.elements/personname) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/asyncwalker/visitasync#visitasync_22)(ShortString) | Defines the asynchronous visit operation for a [`ShortString`](../../aspose.medical.dicom.elements/shortstring) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/asyncwalker/visitasync#visitasync_23)(ShortText) | Defines the asynchronous visit operation for a [`ShortText`](../../aspose.medical.dicom.elements/shorttext) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/asyncwalker/visitasync#visitasync_24)(SignedLong) | Defines the asynchronous visit operation for a [`SignedLong`](../../aspose.medical.dicom.elements/signedlong) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/asyncwalker/visitasync#visitasync_25)(SignedShort) | Defines the asynchronous visit operation for a [`SignedShort`](../../aspose.medical.dicom.elements/signedshort) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/asyncwalker/visitasync#visitasync_26)(SignedVeryLong) | Defines the asynchronous visit operation for a [`SignedVeryLong`](../../aspose.medical.dicom.elements/signedverylong) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/asyncwalker/visitasync#visitasync_27)(Time) | Defines the asynchronous visit operation for a [`Time`](../../aspose.medical.dicom.elements/time) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/asyncwalker/visitasync#visitasync_28)(UniqueIdentifier) | Defines the asynchronous visit operation for a [`UniqueIdentifier`](../../aspose.medical.dicom.elements/uniqueidentifier) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/asyncwalker/visitasync#visitasync_29)(UniversalResource) | Defines the asynchronous visit operation for a [`UniversalResource`](../../aspose.medical.dicom.elements/universalresource) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/asyncwalker/visitasync#visitasync_30)(Unknown) | Defines the asynchronous visit operation for an [`Unknown`](../../aspose.medical.dicom.elements/unknown) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/asyncwalker/visitasync#visitasync_31)(UnlimitedCharacters) | Defines the asynchronous visit operation for an [`UnlimitedCharacters`](../../aspose.medical.dicom.elements/unlimitedcharacters) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/asyncwalker/visitasync#visitasync_32)(UnlimitedText) | Defines the asynchronous visit operation for an [`UnlimitedText`](../../aspose.medical.dicom.elements/unlimitedtext) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/asyncwalker/visitasync#visitasync_33)(UnsignedLong) | Defines the asynchronous visit operation for an [`UnsignedLong`](../../aspose.medical.dicom.elements/unsignedlong) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/asyncwalker/visitasync#visitasync_34)(UnsignedShort) | Defines the asynchronous visit operation for an [`UnsignedShort`](../../aspose.medical.dicom.elements/unsignedshort) element. |
| virtual [VisitAsync](../../aspose.medical.dicom.traversal/asyncwalker/visitasync#visitasync_35)(UnsignedVeryLong) | Defines the asynchronous visit operation for an [`UnsignedVeryLong`](../../aspose.medical.dicom.elements/unsignedverylong) element. |
| virtual [VisitBeginFragmentAsync](../../aspose.medical.dicom.traversal/asyncwalker/visitbeginfragmentasync)(FragmentSequence) | Defines the asynchronous operation invoked before any item of the fragment sequence is visited. |
| virtual [VisitBeginSequenceAsync](../../aspose.medical.dicom.traversal/asyncwalker/visitbeginsequenceasync)(Sequence) | Defines the asynchronous operation invoked before any item of the sequence is visited. |
| virtual [VisitBeginSequenceItemAsync](../../aspose.medical.dicom.traversal/asyncwalker/visitbeginsequenceitemasync)(Sequence, Dataset) | Defines the asynchronous operation invoked immediately before a sequence item is visited. |
| virtual [VisitEndFragmentAsync](../../aspose.medical.dicom.traversal/asyncwalker/visitendfragmentasync)(FragmentSequence) | Defines the asynchronous operation invoked after every item of the fragment sequence has been visited. |
| virtual [VisitEndSequenceAsync](../../aspose.medical.dicom.traversal/asyncwalker/visitendsequenceasync)(Sequence) | Defines the asynchronous operation invoked after every item of the sequence has been visited. |
| virtual [VisitEndSequenceItemAsync](../../aspose.medical.dicom.traversal/asyncwalker/visitendsequenceitemasync)(Sequence, Dataset) | Defines the asynchronous operation invoked after a sequence item and its nested elements have been visited. |
| virtual [VisitFragmentItemAsync](../../aspose.medical.dicom.traversal/asyncwalker/visitfragmentitemasync)(FragmentSequence, byte[]) | Defines the asynchronous visit operation for one item of a fragment sequence. |

### Remarks

Traversal is sequential: each visit operation completes before traversal advances to the next element. Type-specific visit operations complete without performing an action unless overridden.

### See Also

* namespace [Aspose.Medical.Dicom.Traversal](../../aspose.medical.dicom.traversal)
* assembly [Aspose.Medical](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Medical.dll -->
