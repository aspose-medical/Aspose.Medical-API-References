---
title: DicomNetworkServerBuilder
second_title: Aspose.Medical for .NET API Reference
description: Configures DICOM network servers before they are built.
type: docs
weight: 2490
url: /net/aspose.medical.dicom.network.server/dicomnetworkserverbuilder/
---

## DicomNetworkServerBuilder class

Configures DICOM network servers before they are built.

Configures DICOM network servers before they are built.

Configures DICOM network servers before they are built.

```csharp
public sealed class DicomNetworkServerBuilder
```

| Parameter | Description |
| --- | --- |
| options | The server options used by servers created by this builder. |

## Constructors

| Name | Description |
| --- | --- |
| [DicomNetworkServerBuilder](dicomnetworkserverbuilder)(DicomNetworkServerOptions) | Configures DICOM network servers before they are built. |

## Methods

| Name | Description |
| --- | --- |
| [AddCCancelHandlerFactory](../../aspose.medical.dicom.network.server/dicomnetworkserverbuilder/addccancelhandlerfactory)(ICCancelRequestHandlerFactory) | Registers a factory that creates request handlers for inbound C-CANCEL requests. |
| [AddCEchoHandlerFactory](../../aspose.medical.dicom.network.server/dicomnetworkserverbuilder/addcechohandlerfactory)(ICEchoRequestHandlerFactory) | Registers a factory that creates request handlers for inbound C-ECHO requests. |
| [AddCFindHandlerFactory](../../aspose.medical.dicom.network.server/dicomnetworkserverbuilder/addcfindhandlerfactory)(ICFindRequestHandlerFactory) | Registers a factory that creates request handlers for inbound C-FIND requests. |
| [AddCGetHandlerFactory](../../aspose.medical.dicom.network.server/dicomnetworkserverbuilder/addcgethandlerfactory)(ICGetRequestHandlerFactory) | Registers a factory that creates request handlers for inbound C-GET requests. |
| [AddCMoveHandlerFactory](../../aspose.medical.dicom.network.server/dicomnetworkserverbuilder/addcmovehandlerfactory)(ICMoveRequestHandlerFactory) | Registers a factory that creates request handlers for inbound C-MOVE requests. |
| [AddCStoreHandlerFactory](../../aspose.medical.dicom.network.server/dicomnetworkserverbuilder/addcstorehandlerfactory)(ICStoreRequestHandlerFactory) | Registers a factory that creates request handlers for inbound C-STORE requests. |
| [AddNActionHandlerFactory](../../aspose.medical.dicom.network.server/dicomnetworkserverbuilder/addnactionhandlerfactory)(INActionRequestHandlerFactory) | Registers a factory that creates request handlers for inbound N-ACTION requests. |
| [AddNCreateHandlerFactory](../../aspose.medical.dicom.network.server/dicomnetworkserverbuilder/addncreatehandlerfactory)(INCreateRequestHandlerFactory) | Registers a factory that creates request handlers for inbound N-CREATE requests. |
| [AddNDeleteHandlerFactory](../../aspose.medical.dicom.network.server/dicomnetworkserverbuilder/addndeletehandlerfactory)(INDeleteRequestHandlerFactory) | Registers a factory that creates request handlers for inbound N-DELETE requests. |
| [AddNEventReportHandlerFactory](../../aspose.medical.dicom.network.server/dicomnetworkserverbuilder/addneventreporthandlerfactory)(INEventReportRequestHandlerFactory) | Registers a factory that creates request handlers for inbound N-EVENT-REPORT requests. |
| [AddNGetHandlerFactory](../../aspose.medical.dicom.network.server/dicomnetworkserverbuilder/addngethandlerfactory)(INGetRequestHandlerFactory) | Registers a factory that creates request handlers for inbound N-GET requests. |
| [AddNotificationHandlerFactory&lt;TNotification&gt;](../../aspose.medical.dicom.network.server/dicomnetworkserverbuilder/addnotificationhandlerfactory)(INotificationHandlerFactory&lt;TNotification&gt;) | Registers a notification handler factory for server notifications. |
| [AddNSetHandlerFactory](../../aspose.medical.dicom.network.server/dicomnetworkserverbuilder/addnsethandlerfactory)(INSetRequestHandlerFactory) | Registers a factory that creates request handlers for inbound N-SET requests. |
| [AddOpenNotificationHandlerFactory](../../aspose.medical.dicom.network.server/dicomnetworkserverbuilder/addopennotificationhandlerfactory)(IOpenNotificationHandlerFactory) | Registers an open notification handler factory for server notifications. |
| [AddRequestHandlerFactory&lt;TRequest,TResponse&gt;](../../aspose.medical.dicom.network.server/dicomnetworkserverbuilder/addrequesthandlerfactory)(IRequestHandlerFactory&lt;TRequest, TResponse&gt;) | Registers a unary request handler factory for server request dispatch. |
| [AddSingletonCCancelHandler](../../aspose.medical.dicom.network.server/dicomnetworkserverbuilder/addsingletonccancelhandler)(ICCancelRequestHandler) | Registers the request handler for inbound C-CANCEL requests. |
| [AddSingletonCEchoHandler](../../aspose.medical.dicom.network.server/dicomnetworkserverbuilder/addsingletoncechohandler)(ICEchoRequestHandler) | Registers the request handler for inbound C-ECHO requests. |
| [AddSingletonCFindHandler](../../aspose.medical.dicom.network.server/dicomnetworkserverbuilder/addsingletoncfindhandler)(ICFindRequestHandler) | Registers the request handler for inbound C-FIND requests. |
| [AddSingletonCGetHandler](../../aspose.medical.dicom.network.server/dicomnetworkserverbuilder/addsingletoncgethandler)(ICGetRequestHandler) | Registers the request handler for inbound C-GET requests. |
| [AddSingletonCMoveHandler](../../aspose.medical.dicom.network.server/dicomnetworkserverbuilder/addsingletoncmovehandler)(ICMoveRequestHandler) | Registers the request handler for inbound C-MOVE requests. |
| [AddSingletonCStoreHandler](../../aspose.medical.dicom.network.server/dicomnetworkserverbuilder/addsingletoncstorehandler)(ICStoreRequestHandler) | Registers the request handler for inbound C-STORE requests. |
| [AddSingletonNActionHandler](../../aspose.medical.dicom.network.server/dicomnetworkserverbuilder/addsingletonnactionhandler)(INActionRequestHandler) | Registers the request handler for inbound N-ACTION requests. |
| [AddSingletonNCreateHandler](../../aspose.medical.dicom.network.server/dicomnetworkserverbuilder/addsingletonncreatehandler)(INCreateRequestHandler) | Registers the request handler for inbound N-CREATE requests. |
| [AddSingletonNDeleteHandler](../../aspose.medical.dicom.network.server/dicomnetworkserverbuilder/addsingletonndeletehandler)(INDeleteRequestHandler) | Registers the request handler for inbound N-DELETE requests. |
| [AddSingletonNEventReportHandler](../../aspose.medical.dicom.network.server/dicomnetworkserverbuilder/addsingletonneventreporthandler)(INEventReportRequestHandler) | Registers the request handler for inbound N-EVENT-REPORT requests. |
| [AddSingletonNGetHandler](../../aspose.medical.dicom.network.server/dicomnetworkserverbuilder/addsingletonngethandler)(INGetRequestHandler) | Registers the request handler for inbound N-GET requests. |
| [AddSingletonNotificationHandler&lt;TNotification&gt;](../../aspose.medical.dicom.network.server/dicomnetworkserverbuilder/addsingletonnotificationhandler)(INotificationHandler&lt;TNotification&gt;) | Registers a shared notification handler for server notifications. |
| [AddSingletonNSetHandler](../../aspose.medical.dicom.network.server/dicomnetworkserverbuilder/addsingletonnsethandler)(INSetRequestHandler) | Registers the request handler for inbound N-SET requests. |
| [AddSingletonRequestHandler&lt;TRequest,TResponse&gt;](../../aspose.medical.dicom.network.server/dicomnetworkserverbuilder/addsingletonrequesthandler)(IRequestHandler&lt;TRequest, TResponse&gt;) | Registers a shared unary request handler for server request dispatch. |
| [AddSingletonStreamRequestHandler&lt;TRequest,TResponse&gt;](../../aspose.medical.dicom.network.server/dicomnetworkserverbuilder/addsingletonstreamrequesthandler)(IStreamRequestHandler&lt;TRequest, TResponse&gt;) | Registers a shared stream request handler for server stream request dispatch. |
| [AddStreamRequestHandlerFactory&lt;TRequest,TResponse&gt;](../../aspose.medical.dicom.network.server/dicomnetworkserverbuilder/addstreamrequesthandlerfactory)(IStreamRequestHandlerFactory&lt;TRequest, TResponse&gt;) | Registers a stream request handler factory for server stream request dispatch. |
| [Build](../../aspose.medical.dicom.network.server/dicomnetworkserverbuilder/build)() | Creates a DICOM network server from the current builder configuration. |
| [Use](../../aspose.medical.dicom.network.server/dicomnetworkserverbuilder/use#use)(IOpenRequestBehaviorFactory) | Registers an open unary request behavior factory for server request dispatch. |
| [Use](../../aspose.medical.dicom.network.server/dicomnetworkserverbuilder/use#use_1)(IOpenStreamRequestBehaviorFactory) | Registers an open stream request behavior factory for server stream request dispatch. |
| [Use&lt;TRequest,TResponse&gt;](../../aspose.medical.dicom.network.server/dicomnetworkserverbuilder/use#use_3)(IRequestBehavior&lt;TRequest, TResponse&gt;) | Registers a shared unary request behavior for server request dispatch. |
| [Use&lt;TRequest,TResponse&gt;](../../aspose.medical.dicom.network.server/dicomnetworkserverbuilder/use#use_2)(IRequestBehaviorFactory&lt;TRequest, TResponse&gt;) | Registers a unary request behavior factory for server request dispatch. |
| [Use&lt;TRequest,TResponse&gt;](../../aspose.medical.dicom.network.server/dicomnetworkserverbuilder/use#use_5)(IStreamRequestBehavior&lt;TRequest, TResponse&gt;) | Registers a shared stream request behavior for server stream request dispatch. |
| [Use&lt;TRequest,TResponse&gt;](../../aspose.medical.dicom.network.server/dicomnetworkserverbuilder/use#use_4)(IStreamRequestBehaviorFactory&lt;TRequest, TResponse&gt;) | Registers a stream request behavior factory for server stream request dispatch. |

### Remarks

This builder is mutable. Changes made after [`Build`](./build) affect later server instances only.

### See Also

* namespace [Aspose.Medical.Dicom.Network.Server](../../aspose.medical.dicom.network.server)
* assembly [Aspose.Medical](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Medical.dll -->
