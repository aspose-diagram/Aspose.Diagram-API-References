---
title: "Page.glueShapes"
linktitle: "glueShapes"
articleTitle: "glueShapes"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Glue shapes"
type: docs
weight: 500
url: /nodejs/aspose.diagram/page/glueshapes-1/
---

## glueShapes(shapeFromId, placeTo, shapeToId)

Glue shapes

| Parameter | Type | Description |
| --- | --- | --- |
| shapeFromId | long | The ID of shape which is glue from |
| placeTo | Number | ConnectionPointPlace |
| shapeToId | long | The ID of shape where to glue to |

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("GlueVisioShapes.vsdx");
// Get a particular page
page = diagram.getPages().getPage("Page-1");
// set shape id
shape1_ID = 7;
shape2_ID = 494;
// Glue shapes
page.glueShapes(shape1_ID, aspose.diagram.ConnectionPointPlace.CENTER, shape2_ID);
diagram.save("out-GlueVisioShapes.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```
