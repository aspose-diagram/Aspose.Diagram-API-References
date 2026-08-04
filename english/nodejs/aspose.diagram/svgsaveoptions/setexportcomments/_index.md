---
title: "SVGSaveOptions.setExportComments"
linktitle: "setExportComments"
articleTitle: "setExportComments"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Defines whether need exporting the comments or not."
type: docs
weight: 260
url: /nodejs/aspose.diagram/svgsaveoptions/setexportcomments/
---

## setExportComments()

Defines whether need exporting the comments or not. Default value is false.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("Pages.vsdx");
// get a particular page
page = diagram.getPages().getPage("Flow 2");
// set Visio page visiblity
page.getPageSheet().getPageProps().getUIVisibility().setValue(aspose.diagram.BOOL.TRUE);
// initialize Image save options
options = new aspose.diagram.ImageSaveOptions(aspose.diagram.SaveFileFormat.JPEG);
// set export option of hidden Visio pages
options.setExportHiddenPage(false);
// set export option of comments
options.setExportComments(false);
diagram.save("out-ExportOfHiddenVisioPagesToImage.jpeg", options);
```
