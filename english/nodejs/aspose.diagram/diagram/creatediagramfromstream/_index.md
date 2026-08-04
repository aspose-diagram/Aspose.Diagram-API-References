---
title: "Diagram.createDiagramFromStream"
linktitle: "createDiagramFromStream"
articleTitle: "createDiagramFromStream"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Public class constructor, loads the diagram from the stream."
type: docs
weight: 20
url: /nodejs/aspose.diagram/diagram/creatediagramfromstream/
---

## createDiagramFromStream(stream, callback) (static)

Public class constructor, loads the diagram from the stream.

| Parameter | Type | Description |
| --- | --- | --- |
| stream | ReadableStream | The data stream |
| callback | Callback | The callback function |

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
var fs = require("fs");
var readStream = fs.createReadStream("example.vsdx");
aspose.diagram.Diagram.createDiagramFromStream(readStream, function(diagram, err) {
if (err) {
console.log("open error");
return;
}
diagram.save("output.vsdx", aspose.diagram.SaveFileFormat.VSDX);
});
```
