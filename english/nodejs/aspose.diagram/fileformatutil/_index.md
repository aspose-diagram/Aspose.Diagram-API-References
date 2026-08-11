---
title: "FileFormatUtil"
linktitle: "FileFormatUtil"
second_title: "Aspose.Diagram for Node.js via Java API Reference"
description: "Provides utility methods for converting file format enums to strings or file extensions and back."
type: docs
weight: 890
url: /nodejs/aspose.diagram/fileformatutil/
---

## FileFormatUtil class

Provides utility methods for converting file format enums to strings or file extensions and back.

```js
new FileFormatUtil()
```

## Methods

| Name | Description |
| --- | --- |
| [detectFileFormat(stream)](#detectfileformat) *(static)* | Detects and returns the information about a format of a visio stored in a stream. |
| [detectFileFormat(filePath)](#detectfileformat-1) *(static)* | Detects and returns the information about a format of a visio stored in a file. |
| [detectFileFormatFromStream(stream, callback)](#detectfileformatfromstream) *(static)* | Detects and returns the information about a format of a visio stored in a stream. |

### detectFileFormat(stream) (static) {#detectfileformat}

Detects and returns the information about a format of a visio stored in a stream.

| Parameter | Type | Description |
| --- | --- | --- |
| stream | InputStream | The stream |

**Returns:** FileFormatInfo — `FileFormatInfo` A FileFormatInfo object that contains the detected information.

### detectFileFormat(filePath) (static) {#detectfileformat-1}

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

### detectFileFormatFromStream(stream, callback) (static) {#detectfileformatfromstream}

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
