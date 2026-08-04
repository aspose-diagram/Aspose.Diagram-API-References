---
title: "Shape.gluedShapes"
linktitle: "gluedShapes"
articleTitle: "gluedShapes"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Returns an array that contains the identifiers of the shapes that are glued to a shape."
type: docs
weight: 1010
url: /nodejs/aspose.diagram/shape/gluedshapes/
---

## gluedShapes(flag, categoryFilter, otherShape)

Returns an array that contains the identifiers of the shapes that are glued to a shape.

| Parameter | Type | Description |
| --- | --- | --- |
| flag | Number | GluedShapesFlags |
| categoryFilter | String | Filters the array of returned shape IDs by limiting it to the IDs of shapes that match the specified category |
| otherShape | Shape | Optional: additional shape to which returned shapes must also be glued, can be |

**Returns:** Array of long — `Array of long` IDs arraylong.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("RetrieveShapeInfo.vsd");
// get shape by an ID
shape = diagram.getPages().getPage("Page-2").getShapes().getShape(1);
// get all glued 1D shapes
gluedShapeIds = shape.gluedShapes(aspose.diagram.GluedShapesFlags.GLUED_SHAPES_ALL_1_D, null, null);
// display shape ID and name
for (let i = 0; i < gluedShapeIds.length; i++) {
shape = diagram.getPages().get(0).getShapes().getShape(gluedShapeIds[i]);
console.log("ID: " + shape.getID() + "\t\t Name: " + shape.getName());
}
```
