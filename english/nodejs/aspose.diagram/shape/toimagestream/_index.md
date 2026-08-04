---
title: "Shape.toImageStream"
linktitle: "toImageStream"
articleTitle: "toImageStream"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Creates the shape image and saves it to a stream in the specified format."
type: docs
weight: 20
url: /nodejs/aspose.diagram/shape/toimagestream/
---

## toImageStream(shape, stream, options) (static)

Creates the shape image and saves it to a stream in the specified format.

| Parameter | Type | Description |
| --- | --- | --- |
| shape | Shape | The shape object to save |
| stream | WritableStream | The stream |
| options | ImageSaveOptions | ImageSaveOptions |

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
var fs = require("fs");
var diagram = new aspose.diagram.Diagram("example.vsdx");
var page = diagram.getPages().getPage("Page-1");
var shape = page.getShapes().getShape(1);
var writeStream = fs.createWriteStream("output.png");
var options = new aspose.diagram.ImageSaveOptions(aspose.diagram.SaveFileFormat.PNG);
aspose.diagram.Shape.toImageStream(shape, writeStream, options);
```
