---
title: "Shape.getLayerMem"
linktitle: "getLayerMem"
articleTitle: "getLayerMem"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Contains the LayerMember element, which specifies each layer to which the shape is assigned."
type: docs
weight: 660
url: /nodejs/aspose.diagram/shape/getlayermem/
---

## getLayerMem()

Contains the LayerMember element, which specifies each layer to which the shape is assigned.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("Layers.vsdx");
shapes = diagram.getPages().getPage("Page-1").getShapes();
// iterate through the shapes
for (var it = shapes.iterator(); it.hasNext();) {
shape = it.next();
if (shape.getName().toLowerCase() == "shape1") {
// Add shape1 in first two layers. Here "0;1" are indexes of the
// layers
layer = shape.getLayerMem();
layer.getLayerMember().setValue("0;1");
} else if (shape.getName().toLowerCase() == "shape2") {
// Remove shape2 from all the layers
layer = shape.getLayerMem();
layer.getLayerMember().setValue("");
} else if (shape.getName().toLowerCase() == "shape3") {
// Add shape3 in first layer. Here "0" is index of the first
// layer
layer = shape.getLayerMem();
layer.getLayerMember().setValue("0");
}
}
// save diagram
diagram.save("out-ConfigureShapeLayers.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```
