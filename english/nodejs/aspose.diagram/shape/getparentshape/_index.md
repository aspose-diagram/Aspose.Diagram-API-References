---
title: "Shape.getParentShape"
linktitle: "getParentShape"
articleTitle: "getParentShape"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Shape's parent."
type: docs
weight: 780
url: /nodejs/aspose.diagram/shape/getparentshape/
---

## getParentShape()

Shape's parent.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("AddingNewShape.vsdx");
// get a sub-shape by page name, group shape ID, and then sub-shape ID
shape = diagram.getPages().getPage("Page-3").getShapes().getShape(13).getShapes().getShape(2);
parentShape = shape.getParentShape();
console.log("Parent Shape's Properties:");
console.log("Shape ID: " + parentShape.getID());
console.log("Shape Name: " + parentShape.getName());
console.log("Shape Type: " + parentShape.getType());
```
