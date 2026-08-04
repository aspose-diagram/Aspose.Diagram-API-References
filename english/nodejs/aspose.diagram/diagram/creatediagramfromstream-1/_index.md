---
title: "Diagram.createDiagramFromStream"
linktitle: "createDiagramFromStream"
articleTitle: "createDiagramFromStream"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Public class constructor, loads the diagram from the stream using predefined format."
type: docs
weight: 30
url: /nodejs/aspose.diagram/diagram/creatediagramfromstream-1/
---

## createDiagramFromStream(stream, format, callback) (static)

Public class constructor, loads the diagram from the stream using predefined format.

| Parameter | Type | Description |
| --- | --- | --- |
| stream | ReadableStream | The data stream |
| format | Number | A |
| callback | Callback | The callback function |

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
var fs = require("fs");
var readStream = fs.createReadStream("example.vsdx");
aspose.diagram.Diagram.createDiagramFromStream(readStream, aspose.diagram.LoadFileFormat.VSDX, function(diagram, err) {
if (err) {
console.log("open error");
return;
}
diagram.save("output.vsdx", aspose.diagram.SaveFileFormat.VSDX);
});
```
