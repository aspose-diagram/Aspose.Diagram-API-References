---
title: "DiagramSaveOptions.setAutoFitPageToDrawingContent"
linktitle: "setAutoFitPageToDrawingContent"
articleTitle: "setAutoFitPageToDrawingContent"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Defines whether need enlarge page to fit drawing content or not."
type: docs
weight: 70
url: /nodejs/aspose.diagram/diagramsaveoptions/setautofitpagetodrawingcontent/
---

## setAutoFitPageToDrawingContent()

Defines whether need enlarge page to fit drawing content or not. Default value is false.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("BFlowcht.vsdx");
// use saving options
options = new aspose.diagram.DiagramSaveOptions(aspose.diagram.SaveFileFormat.VSDX);
// set Auto fit page property
options.setAutoFitPageToDrawingContent(true);
// save Visio diagram
diagram.save("out-AutoFitShapesInVisio.vsdx", options);
```
