---
title: "Shape.isConnected"
linktitle: "isConnected"
articleTitle: "isConnected"
second_title: "Aspose.Diagram for Python via Java"
description: "Indicates whether this two shapes are connected."
type: docs
weight: 180
url: /python-java/asposediagram.api/shape/isconnected/
---

## isConnected(shape) {#isconnected}

Indicates whether this two shapes are connected.

| Parameter | Type | Description |
| --- | --- | --- |
| shape | Shape | shape |

**Example:**

```python
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
