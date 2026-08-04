---
title: "Shape.isInGroup"
linktitle: "isInGroup"
articleTitle: "isInGroup"
second_title: "Aspose.Diagram for Python via Java"
description: "Indicates whether this shape is in a group shape."
type: docs
weight: 150
url: /python-java/asposediagram.api/shape/isingroup/
---

## isInGroup() {#isingroup}

Indicates whether this shape is in a group shape.

**Example:**

```python
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");

diagram = new aspose.diagram.Diagram("AddingNewShape.vsdx");

// get a sub-shape by page name, group shape ID, and then sub-shape ID
shape = diagram.getPages().getPage("Page-3").getShapes().getShape(13).getShapes().getShape(2);
console.log("Is it in a Group: " + shape.isInGroup());
```
