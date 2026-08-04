---
title: "Diagram.getStyleSheets"
linktitle: "getStyleSheets"
articleTitle: "getStyleSheets"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Collection StyleSheet objects."
type: docs
weight: 410
url: /nodejs/aspose.diagram/diagram/getstylesheets/
---

## getStyleSheets()

Collection StyleSheet objects.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("ApplyCustomStyleSheets.vsd");
sourceShape = null;
// get page by name
page = diagram.getPages().getPage("Flow 1");
// Find the shape that you want to apply style to
for (it = page.getShapes().iterator(); it.hasNext();) {
shape = it.next();
if (shape.getName() == "Process") {
sourceShape = shape;
break;
}
}
customStyleSheet = null;
// Find the required style sheet
for (it = diagram.getStyleSheets().iterator(); it.hasNext();) {
styleSheet = it.next();
if (styleSheet.getName() == "Callout") {
customStyleSheet = styleSheet;
break;
}
}
if (sourceShape != null && customStyleSheet != null) {
// Apply text style
sourceShape.setTextStyle(customStyleSheet);
// Apply fill style
sourceShape.setFillStyle(customStyleSheet);
// Apply line style
sourceShape.setLineStyle(customStyleSheet);
}
diagram.save("out-ApplyCustomStyleSheets.vdx", aspose.diagram.SaveFileFormat.VDX);
```
