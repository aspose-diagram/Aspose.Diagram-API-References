---
title: "Diagram.save"
linktitle: "save"
articleTitle: "save"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Saves the diagram data to the stream."
type: docs
weight: 50
url: /nodejs/aspose.diagram/diagram/save/
---

## save(diagram, stream, saveFormat) (static)

Saves the diagram data to the stream.

| Parameter | Type | Description |
| --- | --- | --- |
| diagram | Diagram | The diagram object to save |
| stream | WritableStream | The stream |
| saveFormat | Number | A |

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
var fs = require("fs");
var diagram = new aspose.diagram.Diagram("example.vsdx");
var writeStream = fs.createWriteStream("output-stream.vsdx");
aspose.diagram.Diagram.saveToStream(diagram, writeStream, aspose.diagram.SaveFileFormat.VSDX);
```
