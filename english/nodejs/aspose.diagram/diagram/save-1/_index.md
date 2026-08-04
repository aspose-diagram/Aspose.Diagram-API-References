---
title: "Diagram.save"
linktitle: "save"
articleTitle: "save"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Saves the diagram to a file using the specified save options."
type: docs
weight: 60
url: /nodejs/aspose.diagram/diagram/save-1/
---

## save(diagram, stream, options) (static)

Saves the diagram to a file using the specified save options.

| Parameter | Type | Description |
| --- | --- | --- |
| diagram | Diagram | The diagram object to save |
| stream | WritableStream | The stream |
| options | SaveOptions | SaveOptions |

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
var fs = require("fs");
var diagram = new aspose.diagram.Diagram("example.vsdx");
var writeStream = fs.createWriteStream("output-stream.vsdx");
var options = new aspose.diagram.DiagramSaveOptions(aspose.diagram.SaveFileFormat.VSDX);
aspose.diagram.Diagram.saveToStream(diagram, writeStream, options);
```
