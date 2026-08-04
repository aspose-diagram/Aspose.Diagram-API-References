---
title: "Shape.getActiveXControl"
linktitle: "getActiveXControl"
articleTitle: "getActiveXControl"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Gets the ActiveX control."
type: docs
weight: 110
url: /nodejs/aspose.diagram/shape/getactivexcontrol/
---

## getActiveXControl()

Gets the ActiveX control.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("VisioActiveXControls.vsdx");
// get a Visio page by name
page = diagram.getPages().getPage("Page-1");
// get a shape by ID
shape = page.getShapes().getShape(1);
// get an ActiveX control
activex = shape.getActiveXControl();
// set width of the command button control
activex.setWidth(4);
// set height of the command button control
activex.setHeight(4);
// set caption of the command button control
activex.setCaption("Test Button");
diagram.save("out-RetrieveActiveXControl.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```
