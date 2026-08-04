---
title: "FileFormatUtil.detectFileFormatFromStream"
linktitle: "detectFileFormatFromStream"
articleTitle: "detectFileFormatFromStream"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Detects and returns the information about a format of a visio stored in a stream."
type: docs
weight: 40
url: /nodejs/aspose.diagram/fileformatutil/detectfileformatfromstream/
---

## detectFileFormatFromStream(stream, callback) (static)

Detects and returns the information about a format of a visio stored in a stream.

| Parameter | Type | Description |
| --- | --- | --- |
| stream | ReadableStream | The stream |
| callback | Callback | The callback function |

**Returns:** FileFormatInfo — `FileFormatInfo` A FileFormatInfo object that contains the detected information.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
var fs = require("fs");
var readStream = fs.createReadStream("example.vsdx");
aspose.diagram.FileFormatUtil.detectFileFormatFromStream(readStream, function(result, err) {
if (!err) {
console.log("detect result: " + result.getFileFormatType());
}
});
```
