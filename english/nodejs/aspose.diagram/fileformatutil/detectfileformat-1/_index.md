---
title: "FileFormatUtil.detectFileFormat"
linktitle: "detectFileFormat"
articleTitle: "detectFileFormat"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Detects and returns the information about a format of a visio stored in a file."
type: docs
weight: 30
url: /nodejs/aspose.diagram/fileformatutil/detectfileformat-1/
---

## detectFileFormat(filePath) (static)

Detects and returns the information about a format of a visio stored in a file.

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The file path. |

**Returns:** FileFormatInfo — `FileFormatInfo` A FileFormatInfo object that contains the detected information.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
info = aspose.diagram.FileFormatUtil.detectFileFormat("example.vsdx");
console.log("detect result: " + info.getFileFormatType());
```
