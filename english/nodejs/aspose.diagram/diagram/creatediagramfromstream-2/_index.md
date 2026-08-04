---
title: "Diagram.createDiagramFromStream"
linktitle: "createDiagramFromStream"
articleTitle: "createDiagramFromStream"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Public class constructor, loads the diagram from the file using predefined load file options."
type: docs
weight: 40
url: /nodejs/aspose.diagram/diagram/creatediagramfromstream-2/
---

## createDiagramFromStream(stream, options, callback) (static)

Public class constructor, loads the diagram from the file using predefined load file options.

| Parameter | Type | Description |
| --- | --- | --- |
| stream | ReadableStream | The data stream |
| options | LoadOptions | The data |
| callback | Callback | The callback function |

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
var fs = require("fs");
var readStream = fs.createReadStream("example.vsdx");
options = new aspose.diagram.LoadOptions(aspose.diagram.LoadFileFormat.VSDX);
aspose.diagram.Diagram.createDiagramFromStream(readStream, options, function(diagram, err) {
if (err) {
console.log("open error: " + err);
return;
}
diagram.save("output.vsdx", aspose.diagram.SaveFileFormat.VSDX);
});
```
