---
title: "Shape.getForeignData"
linktitle: "getForeignData"
articleTitle: "getForeignData"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Contains a MIME (Multipurpose Internet Mail Extensions) encoded BLOB of picture data, such as Windows metafile, bitmap, or OLE data."
type: docs
weight: 340
url: /nodejs/aspose.diagram/shape/getforeigndata/
---

## getForeignData()

Contains a MIME (Multipurpose Internet Mail Extensions) encoded BLOB of picture data, such as Windows metafile, bitmap, or OLE data.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
fs = require("fs");
diagram = new aspose.diagram.Diagram("ExtractAllImagesFromPage.vsd");
// Enter page index i.e. 0 for first one
for (var it = diagram.getPages().getPage(0).getShapes().iterator(); it.hasNext();) {
shape = it.next();
// Filter shapes by type Foreign
if (shape.getType() == aspose.diagram.TypeValue.FOREIGN) {
output = fs.writeFileSync("out" + shape.getID() + ".bmp", shape.getForeignData().getValue());
}
}
```
