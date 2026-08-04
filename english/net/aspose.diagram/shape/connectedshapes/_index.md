---
title: Shape.ConnectedShapes
second_title: Aspose.Diagram for .NET API Reference
description: Shape method. Returns an array that contains the identifiers IDs of the shapes that are connected to the shape
type: docs
url: /net/aspose.diagram/shape/connectedshapes/
---
## Shape.ConnectedShapes method

Returns an array that contains the identifiers (IDs) of the shapes that are connected to the shape.

```csharp
public long[] ConnectedShapes(ConnectedShapesFlags flag, string categoryFilter)
```

| Parameter | Type | Description |
| --- | --- | --- |
| flag | ConnectedShapesFlags | Filters the array of returned shape IDs by the directionality of the connectors. See Remarks for possible values[`ConnectedShapesFlags`](../../connectedshapesflags/). |
| categoryFilter | String | Filters the array of returned shape IDs by limiting it to the IDs of shapes that match the specified categoryString. |

### Return Value

IDs arrayInt64.

### See Also

* enum [ConnectedShapesFlags](../../connectedshapesflags/)
* class [Shape](../)
* namespace [Aspose.Diagram](../../shape/)
* assembly [Aspose.Diagram](../../../)


