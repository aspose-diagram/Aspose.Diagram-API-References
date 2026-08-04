---
title: "ShapeCollection.group"
linktitle: "group"
articleTitle: "group"
second_title: "Aspose.Diagram for Python via Java"
description: "Group the shapes."
type: docs
weight: 50
url: /python-java/asposediagram.api/shapecollection/group/
---

## group(groupItems) {#group}

Group the shapes.

The shape in the groupItems should not be grouped. The shape must be in this Shapes collection.

| Parameter | Type | Description |
| --- | --- | --- |
| groupItems | Shape[] | the group items. |

**Returns:** Return the group shape.

**Example:**

```python
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
var java = require("java");

diagram = new aspose.diagram.Diagram("GroupShapes.vsdx");

// get page by name
page = diagram.getPages().getPage("Page-3");

ss = new Array(3);
// extract and assign shapes to the array
ss[0] = page.getShapes().getShape(15);
ss[1] = page.getShapes().getShape(16);
ss[2] = page.getShapes().getShape(17);

// Initialize an array of shapes
jss = java.newArray('com.aspose.diagram.Shape', ss);
// mark array shapes as group
page.getShapes().group(jss);

diagram.save("out-GroupShapes.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```
