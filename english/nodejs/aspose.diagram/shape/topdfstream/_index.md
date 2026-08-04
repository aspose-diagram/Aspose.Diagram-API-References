---
title: "Shape.toPdfStream"
linktitle: "toPdfStream"
articleTitle: "toPdfStream"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Creates the shape pdf and saves it to a stream."
type: docs
weight: 30
url: /nodejs/aspose.diagram/shape/topdfstream/
---

## toPdfStream(shape, stream) (static)

Creates the shape pdf and saves it to a stream.

| Parameter | Type | Description |
| --- | --- | --- |
| shape | Shape | The shape object to save |
| stream | WritableStream | The stream |

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
var fs = require("fs");
var diagram = new aspose.diagram.Diagram("example.vsdx");
var page = diagram.getPages().getPage("Page-1");
var shape = page.getShapes().getShape(1);
var writeStream = fs.createWriteStream("output.pdf");
aspose.diagram.Shape.toPdfStream(shape, writeStream);
```
