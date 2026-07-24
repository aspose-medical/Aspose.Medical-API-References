---
title: Aspose.Medical.Dicom.Network.Messages
second_title: Aspose.Medical for .NET API Reference
description: 
type: docs
weight: 220
url: /net/aspose.medical.dicom.network.messages/
---



## Classes

| Class | Description |
| --- | --- |
| [CCancelRequest](./ccancelrequest) | Represents a C-CANCEL request, which is used to cancel an ongoing C-FIND, C-GET, or C-MOVE operation. |
| [CEchoRequest](./cechorequest) | Represents a C-ECHO request, which is used to verify communication between DICOM Application Entities. |
| [CEchoResponse](./cechoresponse) | Represents a C-ECHO response, which is used to verify communication between DICOM Application Entities. |
| [CFindRequest](./cfindrequest) | Represents a C-FIND request used to query a remote SCP for matching DICOM objects. |
| [CFindResponse](./cfindresponse) | Represents a C-FIND response containing matching results from a remote SCP. |
| [CGetRequest](./cgetrequest) | Represents a C-GET request used to retrieve DICOM objects from a remote SCP over the same association. |
| [CGetResponse](./cgetresponse) | Represents a C-GET response reporting retrieval progress and status. |
| [CMoveRequest](./cmoverequest) | Represents a C-MOVE request used to instruct a remote SCP to transfer DICOM objects to a specified destination. |
| [CMoveResponse](./cmoveresponse) | Represents a C-MOVE response reporting transfer progress and status. |
| [CServiceRequest](./cservicerequest) | Base class for DIMSE C-Service requests (C-ECHO, C-FIND, C-GET, C-MOVE, C-STORE). |
| [CStoreRequest](./cstorerequest) | Represents a C-STORE request used to store a DICOM dataset on a remote SCP. |
| [CStoreResponse](./cstoreresponse) | Represents a C-STORE response indicating the outcome of a storage operation. |
| [NActionRequest](./nactionrequest) | Represents an N-ACTION request used to invoke an action on a SOP Instance managed by a remote SCP. |
| [NActionResponse](./nactionresponse) | Represents an N-ACTION response indicating the outcome of the requested action. |
| [NCreateRequest](./ncreaterequest) | Represents an N-CREATE request used to create a new SOP Instance on a remote SCP. |
| [NCreateResponse](./ncreateresponse) | Represents an N-CREATE response indicating the outcome of the SOP Instance creation. |
| [NDeleteRequest](./ndeleterequest) | Represents an N-DELETE request used to delete a SOP Instance on a remote SCP. |
| [NDeleteResponse](./ndeleteresponse) | Represents an N-DELETE response indicating the outcome of the deletion operation. |
| [NEventReportRequest](./neventreportrequest) | Represents an N-EVENT-REPORT request used to report an event that occurred on a SOP Instance. |
| [NEventReportResponse](./neventreportresponse) | Represents an N-EVENT-REPORT response acknowledging the event notification. |
| [NGetRequest](./ngetrequest) | Represents an N-GET request used to retrieve attribute values from a SOP Instance on a remote SCP. |
| [NGetResponse](./ngetresponse) | Represents an N-GET response containing the requested attribute values. |
| [NLifecycleRequest&lt;TResponse&gt;](./nlifecyclerequest-1) | Base class for N-Service requests that manage SOP Instance lifecycle (N-CREATE, N-DELETE, N-EVENT-REPORT). |
| [NoneDicomNetworkResponse](./nonedicomnetworkresponse) | Represents absence of a DICOM network response (Null Object pattern). |
| [NSetRequest](./nsetrequest) | Represents an N-SET request used to modify attribute values on a SOP Instance managed by a remote SCP. |
| [NSetResponse](./nsetresponse) | Represents an N-SET response indicating the outcome of the attribute modification. |
| [NTargetedRequest&lt;TResponse&gt;](./ntargetedrequest-1) | Base class for N-Service requests that target an existing SOP Instance (N-ACTION, N-GET, N-SET). |
| [RequestTimedOutNotification](./requesttimedoutnotification) | Notifies that a locally invoked DIMSE request exceeded its response timeout while awaiting a response. |
## Interfaces

| Interface | Description |
| --- | --- |
| [IDicomMessage](./idicommessage) | Base interface for all DIMSE messages exchanged over a DICOM association. |
| [IDicomRequest](./idicomrequest) | Represents a DIMSE request message sent by an SCU. Extends [`IRequest`](../aspose.medical.communication/irequest) to allow type-erased dispatch through the messaging infrastructure. |
| [IDicomRequest&lt;TResponse&gt;](./idicomrequest-1) | Represents a DIMSE request message that expects a specific response type. |
| [IDicomRequestContext](./idicomrequestcontext) | Provides request-scoped access to association-bound DIMSE operations. |
| [IDicomResponse](./idicomresponse) | Represents a DIMSE response message returned by an SCP. |
| [IDicomStreamRequest&lt;TResponse&gt;](./idicomstreamrequest-1) | Represents a DIMSE request that can produce pending responses before its terminal response. |
## Enumeration

| Enumeration | Description |
| --- | --- |
| [CFindOptions](./cfindoptions) | Specifies the C-FIND extended negotiation options supported by an Application Entity (AE). These flags indicate additional query capabilities negotiated during association setup. |
| [CGetOptions](./cgetoptions) | Defines the extended negotiation options for the C-GET SOP Class, used to communicate additional retrieval capabilities supported by an Application Entity (AE). |
| [CMoveOptions](./cmoveoptions) | Defines the C-MOVE extended negotiation options supported by an Application Entity (AE). These flags indicate additional retrieval capabilities negotiated during association setup. |
| [DigitalSignatureSupportLevels](./digitalsignaturesupportlevels) | Indicates whether the SCP supports DICOM digital signatures. |
| [DimsePriority](./dimsepriority) | Specifies the DIMSE command priority for a request. |
| [DimseQueryRetrieveLevel](./dimsequeryretrievelevel) | Specifies the DICOM Query/Retrieve level for C-FIND, C-GET, and C-MOVE operations. |
| [ElementCoercion](./elementcoercion) | Whether the SCP may modify certain attributes (e.g., patient name) during storage. |
| [SupportLevels](./supportlevels) | Describes how the SCP handles different SOP Classes. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Medical.dll -->
