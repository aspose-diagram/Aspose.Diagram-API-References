---
title: "Shape.connectedShapes"
linktitle: "connectedShapes"
articleTitle: "connectedShapes"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Returns an array that contains the identifiers (IDs) of the shapes that are connected to the shape."
type: docs
weight: 70
url: /nodejs/aspose.diagram/shape/connectedshapes/
---

## connectedShapes(flag, categoryFilter)

Returns an array that contains the identifiers (IDs) of the shapes that are connected to the shape.

| Parameter | Type | Description |
| --- | --- | --- |
| flag | Number | ConnectedShapesFlags |
| categoryFilter | String | Filters the array of returned shape IDs by limiting it to the IDs of shapes that match the specified category |

**Returns:** Array of long — `Array of long` IDs arraylong.

**Example:**

```js
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
