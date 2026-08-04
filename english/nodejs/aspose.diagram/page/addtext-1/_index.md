---
title: "Page.addText"
linktitle: "addText"
articleTitle: "addText"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Adds Text with defined PinX and PinY."
type: docs
weight: 120
url: /nodejs/aspose.diagram/page/addtext-1/
---

## addText(pinX, pinY, text)

Adds Text with defined PinX and PinY.

| Parameter | Type | Description |
| --- | --- | --- |
| pinX | Number | Specifies the x-coordinate of the text's pin (center of rotation) in relation to the page. |
| pinY | Number | Specifies the y-coordinate of the text's pin (center of rotation) in relation to the page. |
| text | String | text string. |

**Returns:** Shape — `Shape` Returns a shape object that represents the new text object.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram();
// set parameters
PinX = 1, PinY = 1, Width = 1, Height = 1;
text = "Test text";
// add text to a Visio page
diagram.getPages().getPage(0).addText(PinX, PinY, Width, Height, text);
diagram.save("out-InsertTextShape.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```
