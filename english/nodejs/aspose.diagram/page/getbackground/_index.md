---
title: "Page.getBackground"
linktitle: "getBackground"
articleTitle: "getBackground"
second_title: "Aspose.Diagram for Node.js via Java"
description: "A flag indicating if the page is a background page."
type: docs
weight: 360
url: /nodejs/aspose.diagram/page/getbackground/
---

## getBackground()

A flag indicating if the page is a background page. The value of the property is BOOL integer constant.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("RetrievePageInfo.vdx");
for (var it = diagram.getPages().iterator(); it.hasNext();) {
page = it.next();
// Checks if current page is a background page
if (page.getBackground() == aspose.diagram.BOOL.TRUE) {
// Display information about the background page
console.log("Background Page ID : " + page.getID());
console.log("Background Page Name : " + page.getName());
} else {
// Display information about the foreground page
console.log("\nPage ID : " + page.getID());
console.log("Universal Name : " + page.getNameU());
console.log("ID of the Background Page : " + page.getBackPage());
}
}
```
