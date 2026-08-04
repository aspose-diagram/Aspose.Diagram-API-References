---
title: "FileFormatUtil.detectFileFormat"
linktitle: "detectFileFormat"
articleTitle: "detectFileFormat"
second_title: "Aspose.Diagram for Python via Java"
description: "Detects and returns the information about a format of a visio stored in a stream."
type: docs
weight: 10
url: /python-java/asposediagram.api/fileformatutil/detectfileformat/
---

## detectFileFormat(stream) (1 of 2) {#detectfileformat}

Detects and returns the information about a format of a visio stored in a stream.

| Parameter | Type | Description |
| --- | --- | --- |
| stream | InputStream | The stream |

**Returns:** A FileFormatInfo object that contains the detected information.

---

## detectFileFormat(filePath) (2 of 2) {#detectfileformat_1}

Detects and returns the information about a format of a visio stored in a file.

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The file path. |

**Returns:** A FileFormatInfo object that contains the detected information.

**Example:**

```python
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");

info = aspose.diagram.FileFormatUtil.detectFileFormat("example.vsdx");
console.log("detect result: " + info.getFileFormatType());
```
