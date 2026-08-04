---
title: "Shape.setAngle"
linktitle: "setAngle"
articleTitle: "setAngle"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Sets new angle of shape."
type: docs
weight: 1150
url: /nodejs/aspose.diagram/shape/setangle/
---

## setAngle(angle)

Sets new angle of shape. The angle's unit is radian.

| Parameter | Type | Description |
| --- | --- | --- |
| angle | Number | New angle which unit is radian not degree |

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("RetrieveShapeInfo.vsd");
shape = diagram.getPages().getPage("Page-2").getShapes().getShape(2);
// Add a shape and set the angle
shape.setAngle(190);
diagram.save("out-RotateVisioShape.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```
