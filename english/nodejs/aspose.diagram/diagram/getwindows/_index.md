---
title: "Diagram.getWindows"
linktitle: "getWindows"
articleTitle: "getWindows"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Contains the Window elements for a document."
type: docs
weight: 480
url: /nodejs/aspose.diagram/diagram/getwindows/
---

## getWindows()

Contains the Window elements for a document.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("TextBoxes.vsdx");
// iterate through the window elements
for (it = diagram.getWindows().iterator(); it.hasNext();) {
window = it.next();
console.log("ID: " + window.getID());
console.log("Type: " + window.getWindowType());
console.log("Window height: " + window.getWindowHeight());
console.log("Window width: " + window.getWindowWidth());
console.log("Window state: " + window.getWindowState());
}
```
