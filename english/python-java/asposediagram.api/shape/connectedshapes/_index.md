---
title: "Shape.connectedShapes"
linktitle: "connectedShapes"
articleTitle: "connectedShapes"
second_title: "Aspose.Diagram for Python via Java"
description: "Returns an array that contains the identifiers (IDs) of the shapes that are connected to the shape."
type: docs
weight: 140
url: /python-java/asposediagram.api/shape/connectedshapes/
---

## connectedShapes(flag, categoryFilter) {#connectedshapes}

Returns an array that contains the identifiers (IDs) of the shapes that are connected to the shape.

| Parameter | Type | Description |
| --- | --- | --- |
| flag | int | A ConnectedShapesFlags value. Filters the array of returned shape IDs by the directionality of the connectors. See Remarks for possible values ConnectedShapesFlags . |
| categoryFilter | String | Filters the array of returned shape IDs by limiting it to the IDs of shapes that match the specified category java.lang.String . |

**Returns:** IDs array long .

**Example:**

```python
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");

diagram = new aspose.diagram.Diagram("AddingNewShape.vsdx");

// get shape by id
shape = diagram.getPages().getPage("Page-3").getShapes().getShape(16);
// get connected shapes
connectedShapeIds = shape.connectedShapes(aspose.diagram.ConnectedShapesFlags.CONNECTED_SHAPES_ALL_NODES, null);

for (let i = 0; i < connectedShapeIds.length; i++) {
    shape = diagram.getPages().getPage("Page-3").getShapes().getShape(connectedShapeIds[i]);
    console.log("ID: " + shape.getID() + "\t\t Name: " + shape.getName());
}
```
