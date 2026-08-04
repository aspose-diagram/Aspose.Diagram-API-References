---
title: "Page.getConnects"
linktitle: "getConnects"
articleTitle: "getConnects"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Contains a Connect element for each connection between two shapes in a drawing."
type: docs
weight: 380
url: /nodejs/aspose.diagram/page/getconnects/
---

## getConnects()

Contains a Connect element for each connection between two shapes in a drawing.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("RetrieveConnectorInfo.vsd");
connects = diagram.getPages().getPage(0).getConnects();
for (var it = connects.iterator(); it.hasNext();) {
connector = it.next();
// Display information about the Connectors
console.log("From Shape ID : " + connector.getFromSheet());
console.log("To Shape ID : " + connector.getToSheet());
}
```
