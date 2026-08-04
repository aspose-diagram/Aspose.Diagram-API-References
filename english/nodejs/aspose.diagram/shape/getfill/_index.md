---
title: "Shape.getFill"
linktitle: "getFill"
articleTitle: "getFill"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Contains the current fill formatting values for the shape and the shape's drop shadow, including pattern, foreground color, and background color."
type: docs
weight: 310
url: /nodejs/aspose.diagram/shape/getfill/
---

## getFill()

Contains the current fill formatting values for the shape and the shape's drop shadow, including pattern, foreground color, and background color.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("RetrieveShapeInfo.vsd");
// Find a particular shape and update its foreground color and background color
for (it = diagram.getPages().get(0).getShapes().iterator(); it.hasNext();) {
shape = it.next();
if (shape.getNameU().toLowerCase() == "process") {
shape.getFill().getFillForegnd().setValue("#ebf8df");
shape.getFill().getFillBkgnd().setValue("#dff8eb");
}
}
diagram.save("out-SetFillData.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```
