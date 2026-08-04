---
title: "Diagram.getFonts"
linktitle: "getFonts"
articleTitle: "getFonts"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Contains a collection of Font elements"
type: docs
weight: 310
url: /nodejs/aspose.diagram/diagram/getfonts/
---

## getFonts()

Contains a collection of Font elements

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("RetrieveFontInfo.vsd");
fonts = diagram.getFonts();
for (var it = fonts.iterator(); it.hasNext();) {
font = it.next();
// Display information about the fonts
console.log(font.getName());
}
```
