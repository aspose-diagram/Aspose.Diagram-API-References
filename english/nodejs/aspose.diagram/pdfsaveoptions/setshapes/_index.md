---
title: "PdfSaveOptions.setShapes"
linktitle: "setShapes"
articleTitle: "setShapes"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Gets or sets shapes to render."
type: docs
weight: 410
url: /nodejs/aspose.diagram/pdfsaveoptions/setshapes/
---

## setShapes()

Gets or sets shapes to render. Default count is 0.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("LoadSaveConvert.vsdx");
// create an instance SVG save options class
options = new aspose.diagram.SVGSaveOptions();
shapes = options.getShapes();
// get shapes by page index and shape ID, and then add in the shape collection object
shapes.add(diagram.getPages().get(0).getShapes().getShape(1));
shapes.add(diagram.getPages().get(0).getShapes().getShape(2));
// save Visio drawing
diagram.save("out-SelectiveShapes_out.svg", options);
```
