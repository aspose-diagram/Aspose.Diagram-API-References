---
title: "PdfSaveOptions.setExportHiddenPage"
linktitle: "setExportHiddenPage"
articleTitle: "setExportHiddenPage"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Defines whether need exporting the hidden page or not."
type: docs
weight: 320
url: /nodejs/aspose.diagram/pdfsaveoptions/setexporthiddenpage/
---

## setExportHiddenPage()

Defines whether need exporting the hidden page or not. Default value is true.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("Pages.vsdx");
// get a particular page
page = diagram.getPages().getPage("Flow 2");
// set Visio page visiblity
page.getPageSheet().getPageProps().getUIVisibility().setValue(aspose.diagram.BOOL.TRUE);
// initialize PDF save options
options = new aspose.diagram.PdfSaveOptions();
// set export option of hidden Visio pages
options.setExportHiddenPage(false);
diagram.save("out-ExportOfHiddenVisioPagesToPDF.pdf", options);
```
