---
title: "Shape.setXForm"
linktitle: "setXForm"
articleTitle: "setXForm"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Contains elements specifying general positioning information about a shape."
type: docs
weight: 1460
url: /nodejs/aspose.diagram/shape/setxform/
---

## setXForm()

Contains elements specifying general positioning information about a shape.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("RetrieveShapeInfo.vsd");
// Find a particular shape and update its foreground color and background color
for (it = diagram.getPages().get(0).getShapes().iterator(); it.hasNext();) {
shape = it.next();
if (shape.getNameU().toLowerCase() == "process") {
shape.getXForm().getPinX().setValue(5);
shape.getXForm().getPinY().setValue(5);
}
}
diagram.save("out-SetXFormdata.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```
