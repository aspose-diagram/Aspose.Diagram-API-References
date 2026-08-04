---
title: "ImageSaveOptions.getPageIndex"
linktitle: "getPageIndex"
articleTitle: "getPageIndex"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Gets or sets the 0-based index of the first page to render."
type: docs
weight: 160
url: /nodejs/aspose.diagram/imagesaveoptions/getpageindex/
---

## getPageIndex()

Gets or sets the 0-based index of the first page to render. Default is 0.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("ExportPageToImage.vsd");
// Save diagram as PNG
options = new aspose.diagram.ImageSaveOptions(aspose.diagram.SaveFileFormat.PNG);
// Save one page only, by page index
options.setPageIndex(0);
// Save resultant Image file
diagram.save("out-ExportPageToImage.png", options);
```
