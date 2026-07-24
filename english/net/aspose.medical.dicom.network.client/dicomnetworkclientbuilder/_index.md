---
title: DicomNetworkClientBuilder
second_title: Aspose.Medical for .NET API Reference
description: Configures DICOM network clients before they are built.
type: docs
weight: 1360
url: /net/aspose.medical.dicom.network.client/dicomnetworkclientbuilder/
---

## DicomNetworkClientBuilder class

Configures DICOM network clients before they are built.

Configures DICOM network clients before they are built.

Configures DICOM network clients before they are built.

Configures DICOM network clients before they are built.

```csharp
public sealed class DicomNetworkClientBuilder
```

| Parameter | Description |
| --- | --- |
| options | The client options used by clients created by this builder. |

## Constructors

| Name | Description |
| --- | --- |
| [DicomNetworkClientBuilder](dicomnetworkclientbuilder)(DicomNetworkClientOptions) | Configures DICOM network clients before they are built. |

## Methods

| Name | Description |
| --- | --- |
| [AddCCancelHandler](../../aspose.medical.dicom.network.client/dicomnetworkclientbuilder/addccancelhandler)(DicomExchangeHandler&lt;CCancelRequest, NoneDicomNetworkResponse&gt;) | Registers a delegate that observes C-CANCEL exchanges. |
| [AddCCancelHandlerFactory](../../aspose.medical.dicom.network.client/dicomnetworkclientbuilder/addccancelhandlerfactory)(ICCancelExchangeHandlerFactory) | Registers a factory that creates notification handlers for C-CANCEL exchanges. |
| [AddCEchoHandler](../../aspose.medical.dicom.network.client/dicomnetworkclientbuilder/addcechohandler)(DicomExchangeHandler&lt;CEchoRequest, CEchoResponse&gt;) | Registers a delegate that observes C-ECHO exchanges. |
| [AddCEchoHandlerFactory](../../aspose.medical.dicom.network.client/dicomnetworkclientbuilder/addcechohandlerfactory)(ICEchoExchangeHandlerFactory) | Registers a factory that creates notification handlers for C-ECHO exchanges. |
| [AddCFindHandler](../../aspose.medical.dicom.network.client/dicomnetworkclientbuilder/addcfindhandler)(DicomExchangeHandler&lt;CFindRequest, CFindResponse&gt;) | Registers a delegate that observes each C-FIND response together with its originating request. |
| [AddCFindHandlerFactory](../../aspose.medical.dicom.network.client/dicomnetworkclientbuilder/addcfindhandlerfactory)(ICFindExchangeHandlerFactory) | Registers a factory that creates notification handlers for C-FIND exchanges. |
| [AddCGetHandler](../../aspose.medical.dicom.network.client/dicomnetworkclientbuilder/addcgethandler)(DicomExchangeHandler&lt;CGetRequest, CGetResponse&gt;) | Registers a delegate that observes each C-GET response together with its originating request. |
| [AddCGetHandlerFactory](../../aspose.medical.dicom.network.client/dicomnetworkclientbuilder/addcgethandlerfactory)(ICGetExchangeHandlerFactory) | Registers a factory that creates notification handlers for C-GET exchanges. |
| [AddCMoveHandler](../../aspose.medical.dicom.network.client/dicomnetworkclientbuilder/addcmovehandler)(DicomExchangeHandler&lt;CMoveRequest, CMoveResponse&gt;) | Registers a delegate that observes each C-MOVE response together with its originating request. |
| [AddCMoveHandlerFactory](../../aspose.medical.dicom.network.client/dicomnetworkclientbuilder/addcmovehandlerfactory)(ICMoveExchangeHandlerFactory) | Registers a factory that creates notification handlers for C-MOVE exchanges. |
| [AddCStoreHandler](../../aspose.medical.dicom.network.client/dicomnetworkclientbuilder/addcstorehandler)(DicomExchangeHandler&lt;CStoreRequest, CStoreResponse&gt;) | Registers a delegate that observes C-STORE exchanges. |
| [AddCStoreHandlerFactory](../../aspose.medical.dicom.network.client/dicomnetworkclientbuilder/addcstorehandlerfactory)(ICStoreExchangeHandlerFactory) | Registers a factory that creates notification handlers for C-STORE exchanges. |
| [AddNActionHandler](../../aspose.medical.dicom.network.client/dicomnetworkclientbuilder/addnactionhandler)(DicomExchangeHandler&lt;NActionRequest, NActionResponse&gt;) | Registers a delegate that observes N-ACTION exchanges. |
| [AddNActionHandlerFactory](../../aspose.medical.dicom.network.client/dicomnetworkclientbuilder/addnactionhandlerfactory)(INActionExchangeHandlerFactory) | Registers a factory that creates notification handlers for N-ACTION exchanges. |
| [AddNCreateHandler](../../aspose.medical.dicom.network.client/dicomnetworkclientbuilder/addncreatehandler)(DicomExchangeHandler&lt;NCreateRequest, NCreateResponse&gt;) | Registers a delegate that observes N-CREATE exchanges. |
| [AddNCreateHandlerFactory](../../aspose.medical.dicom.network.client/dicomnetworkclientbuilder/addncreatehandlerfactory)(INCreateExchangeHandlerFactory) | Registers a factory that creates notification handlers for N-CREATE exchanges. |
| [AddNDeleteHandler](../../aspose.medical.dicom.network.client/dicomnetworkclientbuilder/addndeletehandler)(DicomExchangeHandler&lt;NDeleteRequest, NDeleteResponse&gt;) | Registers a delegate that observes N-DELETE exchanges. |
| [AddNDeleteHandlerFactory](../../aspose.medical.dicom.network.client/dicomnetworkclientbuilder/addndeletehandlerfactory)(INDeleteExchangeHandlerFactory) | Registers a factory that creates notification handlers for N-DELETE exchanges. |
| [AddNEventReportHandler](../../aspose.medical.dicom.network.client/dicomnetworkclientbuilder/addneventreporthandler)(DicomExchangeHandler&lt;NEventReportRequest, NEventReportResponse&gt;) | Registers a delegate that observes N-EVENT-REPORT exchanges. |
| [AddNEventReportHandlerFactory](../../aspose.medical.dicom.network.client/dicomnetworkclientbuilder/addneventreporthandlerfactory)(INEventReportExchangeHandlerFactory) | Registers a factory that creates notification handlers for N-EVENT-REPORT exchanges. |
| [AddNGetHandler](../../aspose.medical.dicom.network.client/dicomnetworkclientbuilder/addngethandler)(DicomExchangeHandler&lt;NGetRequest, NGetResponse&gt;) | Registers a delegate that observes N-GET exchanges. |
| [AddNGetHandlerFactory](../../aspose.medical.dicom.network.client/dicomnetworkclientbuilder/addngethandlerfactory)(INGetExchangeHandlerFactory) | Registers a factory that creates notification handlers for N-GET exchanges. |
| [AddNotificationHandlerFactory&lt;TNotification&gt;](../../aspose.medical.dicom.network.client/dicomnetworkclientbuilder/addnotificationhandlerfactory)(INotificationHandlerFactory&lt;TNotification&gt;) | Registers a notification handler factory for client notifications. |
| [AddNSetHandler](../../aspose.medical.dicom.network.client/dicomnetworkclientbuilder/addnsethandler)(DicomExchangeHandler&lt;NSetRequest, NSetResponse&gt;) | Registers a delegate that observes N-SET exchanges. |
| [AddNSetHandlerFactory](../../aspose.medical.dicom.network.client/dicomnetworkclientbuilder/addnsethandlerfactory)(INSetExchangeHandlerFactory) | Registers a factory that creates notification handlers for N-SET exchanges. |
| [AddOpenNotificationHandlerFactory](../../aspose.medical.dicom.network.client/dicomnetworkclientbuilder/addopennotificationhandlerfactory)(IOpenNotificationHandlerFactory) | Registers an open notification handler factory for client notifications. |
| [AddSingletonCCancelHandler](../../aspose.medical.dicom.network.client/dicomnetworkclientbuilder/addsingletonccancelhandler)(ICCancelExchangeHandler) | Registers a notification handler for C-CANCEL exchanges. |
| [AddSingletonCEchoHandler](../../aspose.medical.dicom.network.client/dicomnetworkclientbuilder/addsingletoncechohandler)(ICEchoExchangeHandler) | Registers a notification handler for C-ECHO exchanges. |
| [AddSingletonCFindHandler](../../aspose.medical.dicom.network.client/dicomnetworkclientbuilder/addsingletoncfindhandler)(ICFindExchangeHandler) | Registers a notification handler for C-FIND exchanges. |
| [AddSingletonCGetHandler](../../aspose.medical.dicom.network.client/dicomnetworkclientbuilder/addsingletoncgethandler)(ICGetExchangeHandler) | Registers a notification handler for C-GET exchanges. |
| [AddSingletonCMoveHandler](../../aspose.medical.dicom.network.client/dicomnetworkclientbuilder/addsingletoncmovehandler)(ICMoveExchangeHandler) | Registers a notification handler for C-MOVE exchanges. |
| [AddSingletonCStoreHandler](../../aspose.medical.dicom.network.client/dicomnetworkclientbuilder/addsingletoncstorehandler)(ICStoreExchangeHandler) | Registers a notification handler for C-STORE exchanges. |
| [AddSingletonNActionHandler](../../aspose.medical.dicom.network.client/dicomnetworkclientbuilder/addsingletonnactionhandler)(INActionExchangeHandler) | Registers a notification handler for N-ACTION exchanges. |
| [AddSingletonNCreateHandler](../../aspose.medical.dicom.network.client/dicomnetworkclientbuilder/addsingletonncreatehandler)(INCreateExchangeHandler) | Registers a notification handler for N-CREATE exchanges. |
| [AddSingletonNDeleteHandler](../../aspose.medical.dicom.network.client/dicomnetworkclientbuilder/addsingletonndeletehandler)(INDeleteExchangeHandler) | Registers a notification handler for N-DELETE exchanges. |
| [AddSingletonNEventReportHandler](../../aspose.medical.dicom.network.client/dicomnetworkclientbuilder/addsingletonneventreporthandler)(INEventReportExchangeHandler) | Registers a notification handler for N-EVENT-REPORT exchanges. |
| [AddSingletonNGetHandler](../../aspose.medical.dicom.network.client/dicomnetworkclientbuilder/addsingletonngethandler)(INGetExchangeHandler) | Registers a notification handler for N-GET exchanges. |
| [AddSingletonNotificationHandler&lt;TNotification&gt;](../../aspose.medical.dicom.network.client/dicomnetworkclientbuilder/addsingletonnotificationhandler)(INotificationHandler&lt;TNotification&gt;) | Registers a shared notification handler for client notifications. |
| [AddSingletonNSetHandler](../../aspose.medical.dicom.network.client/dicomnetworkclientbuilder/addsingletonnsethandler)(INSetExchangeHandler) | Registers a notification handler for N-SET exchanges. |
| [AddSingletonRequestHandler&lt;TRequest,TResponse&gt;](../../aspose.medical.dicom.network.client/dicomnetworkclientbuilder/addsingletonrequesthandler)(IRequestHandler&lt;TRequest, TResponse&gt;) | Registers a shared unary request handler for client request dispatch. |
| [AddSingletonStreamRequestHandler&lt;TRequest,TResponse&gt;](../../aspose.medical.dicom.network.client/dicomnetworkclientbuilder/addsingletonstreamrequesthandler)(IStreamRequestHandler&lt;TRequest, TResponse&gt;) | Registers a shared stream request handler for client stream request dispatch. |
| [AddStreamRequestHandlerFactory&lt;TRequest,TResponse&gt;](../../aspose.medical.dicom.network.client/dicomnetworkclientbuilder/addstreamrequesthandlerfactory)(IStreamRequestHandlerFactory&lt;TRequest, TResponse&gt;) | Registers a stream request handler factory for client stream request dispatch. |
| [Build](../../aspose.medical.dicom.network.client/dicomnetworkclientbuilder/build)() | Creates a DICOM network client from the current builder configuration. |
| [Use](../../aspose.medical.dicom.network.client/dicomnetworkclientbuilder/use#use)(IOpenRequestBehaviorFactory) | Registers an open unary request behavior factory for client request dispatch. |
| [Use](../../aspose.medical.dicom.network.client/dicomnetworkclientbuilder/use#use_1)(IOpenStreamRequestBehaviorFactory) | Registers an open stream request behavior factory for client stream request dispatch. |
| [Use&lt;TRequest,TResponse&gt;](../../aspose.medical.dicom.network.client/dicomnetworkclientbuilder/use#use_3)(IRequestBehavior&lt;TRequest, TResponse&gt;) | Registers a shared unary request behavior for client request dispatch. |
| [Use&lt;TRequest,TResponse&gt;](../../aspose.medical.dicom.network.client/dicomnetworkclientbuilder/use#use_2)(IRequestBehaviorFactory&lt;TRequest, TResponse&gt;) | Registers a unary request behavior factory for client request dispatch. |
| [Use&lt;TRequest,TResponse&gt;](../../aspose.medical.dicom.network.client/dicomnetworkclientbuilder/use#use_5)(IStreamRequestBehavior&lt;TRequest, TResponse&gt;) | Registers a shared stream request behavior for client stream request dispatch. |
| [Use&lt;TRequest,TResponse&gt;](../../aspose.medical.dicom.network.client/dicomnetworkclientbuilder/use#use_4)(IStreamRequestBehaviorFactory&lt;TRequest, TResponse&gt;) | Registers a stream request behavior factory for client stream request dispatch. |

### Remarks

This builder is mutable. Changes made after [`Build`](./build) affect later client instances only.

### See Also

* namespace [Aspose.Medical.Dicom.Network.Client](../../aspose.medical.dicom.network.client)
* assembly [Aspose.Medical](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Medical.dll -->
