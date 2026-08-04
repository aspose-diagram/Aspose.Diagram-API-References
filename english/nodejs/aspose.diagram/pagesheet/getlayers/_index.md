---
title: "PageSheet.getLayers"
linktitle: "getLayers"
articleTitle: "getLayers"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Contains a collection of Layer elements."
type: docs
weight: 100
url: /nodejs/aspose.diagram/pagesheet/getlayers/
---

## getLayers()

Contains a collection of Layer elements.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("Layers.vsdx");
// get Visio page
page = diagram.getPages().getPage("Page-1");
layers = page.getPageSheet().getLayers();
// iterate through the layers
for (var it = layers.iterator(); it.hasNext();) {
layer = it.next();
console.log("Name: " + layer.getName().getValue());
console.log("Visibility: " + layer.getVisible().getValue());
console.log("Status: " + layer.getStatus().getValue());
}
```
