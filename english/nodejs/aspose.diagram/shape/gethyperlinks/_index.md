---
title: "Shape.getHyperlinks"
linktitle: "getHyperlinks"
articleTitle: "getHyperlinks"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Contains a collection of Hyperlink elements."
type: docs
weight: 380
url: /nodejs/aspose.diagram/shape/gethyperlinks/
---

## getHyperlinks()

Contains a collection of Hyperlink elements.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("Hyperlinks.vsdx");
// get page by name
var page = diagram.getPages().getPage("Page-1");
// get shape by ID
var shape = page.getShapes().getShape(1);
// get hyperlink collection
var hyperlinks = shape.getHyperlinks();
// iterate through the hyperlinks
for (var it = hyperlinks.iterator(); it.hasNext();) {
hyperlink = it.next();
console.log("Address: " + hyperlink.getAddress().getValue());
console.log("Sub Address: " + hyperlink.getSubAddress().getValue());
console.log("Description: " + hyperlink.getDescription().getValue());
}
```
