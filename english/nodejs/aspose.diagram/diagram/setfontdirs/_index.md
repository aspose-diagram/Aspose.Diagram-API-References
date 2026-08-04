---
title: "Diagram.setFontDirs"
linktitle: "setFontDirs"
articleTitle: "setFontDirs"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Indicates the Fonts folder path"
type: docs
weight: 630
url: /nodejs/aspose.diagram/diagram/setfontdirs/
---

## setFontDirs()

Indicates the Fonts folder path

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
var fontDirs = ["C:\\MyFonts\\", "D:\\Misc\\Fonts\\"];
diagram = new aspose.diagram.Diagram("SpecifyFontLocation.vsdx");
// setting the custom font directories
diagram.setFontDirs(fontDirs);
// saving Visio diagram in PDF format
diagram.save("out-SpecifyFontLocation.pdf", aspose.diagram.SaveFileFormat.PDF);
```
