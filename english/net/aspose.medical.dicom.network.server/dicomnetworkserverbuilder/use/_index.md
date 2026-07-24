---
title: Use
second_title: Aspose.Medical for .NET API Reference
description: Registers a shared unary request behavior for server request dispatch.
type: docs
weight: 340
url: /net/aspose.medical.dicom.network.server/dicomnetworkserverbuilder/use/
---

## Use&lt;TRequest,TResponse&gt;(IRequestBehavior&lt;TRequest, TResponse&gt;) {#use_3}

Registers a shared unary request behavior for server request dispatch.

```csharp
public DicomNetworkServerBuilder Use<TRequest, TResponse>(
    IRequestBehavior<TRequest, TResponse> behavior)
    where TRequest : IRequest<TResponse>
    where TResponse : IResponse
```

| Parameter | Description |
| --- | --- |
| TRequest | The DICOM request type processed by the behavior. |
| TResponse | The DICOM response type produced by the pipeline. |
| behavior | The behavior instance to register. |

### Return Value

The current builder.

### Remarks

This overload reuses the supplied behavior instance for every matching dispatch. Use it only for stateless or thread-safe behavior instances.

### See Also

* interface [IRequestBehavior&lt;TRequest,TResponse&gt;](../../../aspose.medical.communication.messages/irequestbehavior-2)
* interface [IRequest&lt;TResponse&gt;](../../../aspose.medical.communication/irequest-1)
* interface [IResponse](../../../aspose.medical.communication/iresponse)
* class [DicomNetworkServerBuilder](../../dicomnetworkserverbuilder)
* namespace [Aspose.Medical.Dicom.Network.Server](../../dicomnetworkserverbuilder)
* assembly [Aspose.Medical](../../../)

---

## Use&lt;TRequest,TResponse&gt;(IRequestBehaviorFactory&lt;TRequest, TResponse&gt;) {#use_2}

Registers a unary request behavior factory for server request dispatch.

```csharp
public DicomNetworkServerBuilder Use<TRequest, TResponse>(
    IRequestBehaviorFactory<TRequest, TResponse> factory)
    where TRequest : IRequest<TResponse>
    where TResponse : IResponse
```

| Parameter | Description |
| --- | --- |
| TRequest | The DICOM request type processed by created behaviors. |
| TResponse | The DICOM response type produced by the pipeline. |
| factory | The behavior factory to register. |

### Return Value

The current builder.

### See Also

* interface [IRequestBehaviorFactory&lt;TRequest,TResponse&gt;](../../../aspose.medical.communication.messages/irequestbehaviorfactory-2)
* interface [IRequest&lt;TResponse&gt;](../../../aspose.medical.communication/irequest-1)
* interface [IResponse](../../../aspose.medical.communication/iresponse)
* class [DicomNetworkServerBuilder](../../dicomnetworkserverbuilder)
* namespace [Aspose.Medical.Dicom.Network.Server](../../dicomnetworkserverbuilder)
* assembly [Aspose.Medical](../../../)

---

## Use(IOpenRequestBehaviorFactory) {#use}

Registers an open unary request behavior factory for server request dispatch.

```csharp
public DicomNetworkServerBuilder Use(IOpenRequestBehaviorFactory factory)
```

| Parameter | Type | Description |
| --- | --- | --- |
| factory | IOpenRequestBehaviorFactory | The open behavior factory to register. |

### Return Value

The current builder.

### See Also

* interface [IOpenRequestBehaviorFactory](../../../aspose.medical.communication.messages/iopenrequestbehaviorfactory)
* class [DicomNetworkServerBuilder](../../dicomnetworkserverbuilder)
* namespace [Aspose.Medical.Dicom.Network.Server](../../dicomnetworkserverbuilder)
* assembly [Aspose.Medical](../../../)

---

## Use&lt;TRequest,TResponse&gt;(IStreamRequestBehavior&lt;TRequest, TResponse&gt;) {#use_5}

Registers a shared stream request behavior for server stream request dispatch.

```csharp
public DicomNetworkServerBuilder Use<TRequest, TResponse>(
    IStreamRequestBehavior<TRequest, TResponse> behavior)
    where TRequest : IStreamRequest<TResponse>
    where TResponse : IResponse
```

| Parameter | Description |
| --- | --- |
| TRequest | The DICOM stream request type processed by the behavior. |
| TResponse | The DICOM response type produced by the pipeline. |
| behavior | The behavior instance to register. |

### Return Value

The current builder.

### Remarks

This overload reuses the supplied behavior instance for every matching dispatch. Use it only for stateless or thread-safe behavior instances.

### See Also

* interface [IStreamRequestBehavior&lt;TRequest,TResponse&gt;](../../../aspose.medical.communication.messages/istreamrequestbehavior-2)
* interface [IStreamRequest&lt;TResponse&gt;](../../../aspose.medical.communication/istreamrequest-1)
* interface [IResponse](../../../aspose.medical.communication/iresponse)
* class [DicomNetworkServerBuilder](../../dicomnetworkserverbuilder)
* namespace [Aspose.Medical.Dicom.Network.Server](../../dicomnetworkserverbuilder)
* assembly [Aspose.Medical](../../../)

---

## Use&lt;TRequest,TResponse&gt;(IStreamRequestBehaviorFactory&lt;TRequest, TResponse&gt;) {#use_4}

Registers a stream request behavior factory for server stream request dispatch.

```csharp
public DicomNetworkServerBuilder Use<TRequest, TResponse>(
    IStreamRequestBehaviorFactory<TRequest, TResponse> factory)
    where TRequest : IStreamRequest<TResponse>
    where TResponse : IResponse
```

| Parameter | Description |
| --- | --- |
| TRequest | The DICOM stream request type processed by created behaviors. |
| TResponse | The DICOM response type produced by the pipeline. |
| factory | The behavior factory to register. |

### Return Value

The current builder.

### See Also

* interface [IStreamRequestBehaviorFactory&lt;TRequest,TResponse&gt;](../../../aspose.medical.communication.messages/istreamrequestbehaviorfactory-2)
* interface [IStreamRequest&lt;TResponse&gt;](../../../aspose.medical.communication/istreamrequest-1)
* interface [IResponse](../../../aspose.medical.communication/iresponse)
* class [DicomNetworkServerBuilder](../../dicomnetworkserverbuilder)
* namespace [Aspose.Medical.Dicom.Network.Server](../../dicomnetworkserverbuilder)
* assembly [Aspose.Medical](../../../)

---

## Use(IOpenStreamRequestBehaviorFactory) {#use_1}

Registers an open stream request behavior factory for server stream request dispatch.

```csharp
public DicomNetworkServerBuilder Use(IOpenStreamRequestBehaviorFactory factory)
```

| Parameter | Type | Description |
| --- | --- | --- |
| factory | IOpenStreamRequestBehaviorFactory | The open stream behavior factory to register. |

### Return Value

The current builder.

### See Also

* interface [IOpenStreamRequestBehaviorFactory](../../../aspose.medical.communication.messages/iopenstreamrequestbehaviorfactory)
* class [DicomNetworkServerBuilder](../../dicomnetworkserverbuilder)
* namespace [Aspose.Medical.Dicom.Network.Server](../../dicomnetworkserverbuilder)
* assembly [Aspose.Medical](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Medical.dll -->
