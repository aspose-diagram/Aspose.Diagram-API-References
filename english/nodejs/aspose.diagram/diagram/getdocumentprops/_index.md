---
title: "Diagram.getDocumentProps"
linktitle: "getDocumentProps"
articleTitle: "getDocumentProps"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Contains document property elements such as the document's title, author, and so on."
type: docs
weight: 260
url: /nodejs/aspose.diagram/diagram/getdocumentprops/
---

## getDocumentProps()

Contains document property elements such as the document's title, author, and so on.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("Introduction.vsdx");
// Display Visio version and document modification time at different stages
console.log("Visio Instance Version : " + diagram.getVersion());
console.log("Full Build Number Created : " + diagram.getDocumentProps().getBuildNumberCreated());
console.log("Full Build Number Edited : " + diagram.getDocumentProps().getBuildNumberEdited());
console.log("Date Created : " + diagram.getDocumentProps().getTimeCreated());
console.log("Date Last Edited : " + diagram.getDocumentProps().getTimeEdited());
console.log("Date Last Printed : " + diagram.getDocumentProps().getTimePrinted());
console.log("Date Last Saved : " + diagram.getDocumentProps().getTimeSaved());
```
