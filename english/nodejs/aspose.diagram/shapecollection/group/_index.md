---
title: "ShapeCollection.group"
linktitle: "group"
articleTitle: "group"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Group the shapes."
type: docs
weight: 90
url: /nodejs/aspose.diagram/shapecollection/group/
---

## group(groupItems)

Group the shapes. The shape in the groupItems should not be grouped. The shape must be in this Shapes collection.

| Parameter | Type | Description |
| --- | --- | --- |
| groupItems | Array ofShape | the group items. |

**Returns:** Shape — `Shape` Return the group shape.

**Example:**

```js
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
