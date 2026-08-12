---
title: "FileFormatUtil"
linktitle: "FileFormatUtil"
second_title: "Aspose.Diagram for Python via Java API Reference"
description: "Provides utility methods for converting file format enums to strings or file extensions and back."
type: docs
weight: 1220
url: /python-java/asposediagram.api/fileformatutil/
---

## FileFormatUtil class

Provides utility methods for converting file format enums to strings or file extensions and back.

## Constructors

| Name | Description |
| --- | --- |
| [FileFormatUtil](#constructor) |  |

## Methods

| Name | Description |
| --- | --- |
| [detectFileFormat](#detectfileformat) | Detects and returns the information about a format of a visio stored in a stream. |

### FileFormatUtil() {#constructor}

### detectFileFormat(stream) (1 of 2) {#detectfileformat}

Detects and returns the information about a format of a visio stored in a stream.

| Parameter | Type | Description |
| --- | --- | --- |
| stream | InputStream | The stream |

**Returns:** A FileFormatInfo object that contains the detected information.

---

### detectFileFormat(filePath) (2 of 2) {#detectfileformat-1}

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
