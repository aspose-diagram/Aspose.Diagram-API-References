---
title: "Shape.gluedShapes"
linktitle: "gluedShapes"
articleTitle: "gluedShapes"
second_title: "Aspose.Diagram for Python via Java"
description: "Returns an array that contains the identifiers of the shapes that are glued to a shape."
type: docs
weight: 220
url: /python-java/asposediagram.api/shape/gluedshapes/
---

## gluedShapes(flag, categoryFilter, otherShape) {#gluedshapes}

Returns an array that contains the identifiers of the shapes that are glued to a shape.

| Parameter | Type | Description |
| --- | --- | --- |
| flag | int | A GluedShapesFlags value. The dimensionality and directionality of the connection points of the shapes to return.See Remarks for possible values GluedShapesFlags . |
| categoryFilter | String | Filters the array of returned shape IDs by limiting it to the IDs of shapes that match the specified category java.lang.String . |
| otherShape | Shape | Optional: additional shape to which returned shapes must also be glued, can be Shape or null. |

**Returns:** IDs array long .

**Example:**

```python
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
