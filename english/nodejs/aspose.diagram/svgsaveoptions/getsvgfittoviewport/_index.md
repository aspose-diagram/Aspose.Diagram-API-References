---
title: "SVGSaveOptions.getSVGFitToViewPort"
linktitle: "getSVGFitToViewPort"
articleTitle: "getSVGFitToViewPort"
second_title: "Aspose.Diagram for Node.js via Java"
description: "if this property is true, the generated svg will fit to view port."
type: docs
weight: 150
url: /nodejs/aspose.diagram/svgsaveoptions/getsvgfittoviewport/
---

## getSVGFitToViewPort()

if this property is true, the generated svg will fit to view port.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("Pages.vsdx");
// get a particular page
page = diagram.getPages().getPage("Flow 2");
// set Visio page visiblity
page.getPageSheet().getPageProps().getUIVisibility().setValue(aspose.diagram.BOOL.TRUE);
// initialize SVG save options
options = new aspose.diagram.SVGSaveOptions();
// set export option of hidden Visio pages
options.setExportHiddenPage(false);
// Set SVG fit to view port
options.setSVGFitToViewPort(true);
// Set export element as Rectangle
options.setExportElementAsRectTag(true);
diagram.save("out-ExportOfHiddenVisioPagesToSVG.svg", options);
```
