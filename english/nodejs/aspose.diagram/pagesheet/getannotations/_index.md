---
title: "PageSheet.getAnnotations"
linktitle: "getAnnotations"
articleTitle: "getAnnotations"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Contains elements that contain information about comments inserted into a document page."
type: docs
weight: 30
url: /nodejs/aspose.diagram/pagesheet/getannotations/
---

## getAnnotations()

Contains elements that contain information about comments inserted into a document page.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
var diagram = new aspose.diagram.Diagram("Drawing1.vsdx");
// get collection of the annotations
annotations = diagram.getPages().getPage("Page-1").getPageSheet().getAnnotations();
for (var it = annotations.iterator(); it.hasNext();) {
annotation = it.next();
var comment = annotation.getComment().getValue();
comment += "Updation mark";
annotation.getComment().setValue(comment);
}
diagram.save("out-EditPageLevelCommentInVisio.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```
