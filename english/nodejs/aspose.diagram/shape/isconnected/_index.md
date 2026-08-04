---
title: "Shape.isConnected"
linktitle: "isConnected"
articleTitle: "isConnected"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Indicates whether this two shapes are connected."
type: docs
weight: 1030
url: /nodejs/aspose.diagram/shape/isconnected/
---

## isConnected(shape)

Indicates whether this two shapes are connected.

| Parameter | Type | Description |
| --- | --- | --- |
| shape | Shape | shape |

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("RetrieveShapeInfo.vsd");
// get Visio page by name
page = diagram.getPages().getPage("Page-2");
// get Visio shapes by ids
ShapedOne = page.getShapes().getShape(1);
ShapedTwo = page.getShapes().getShape(2);
// determine whether shapes are connected
connected = ShapedOne.isConnected(ShapedTwo);
console.log("Shapes are connected: " + connected);
// determine whether shapes are glued
glued = ShapedOne.isGlued(ShapedTwo);
console.log("Shapes are Glued: " + glued);
```
