---
title: "Page.addText"
linktitle: "addText"
articleTitle: "addText"
second_title: "Aspose.Diagram for Python via Java"
description: "Adds Text with defined PinX and PinY."
type: docs
weight: 190
url: /python-java/asposediagram.api/page/addtext/
---

## addText(pinX, pinY, width, height, text, fontName, fontColor, size) (1 of 2) {#addtext}

Adds Text with defined PinX and PinY.

| Parameter | Type | Description |
| --- | --- | --- |
| pinX | float | Specifies the x-coordinate of the text's pin (center of rotation) in relation to the page. |
| pinY | float | Specifies the y-coordinate of the text's pin (center of rotation) in relation to the page. |
| width | float | Specifies the width of the text. |
| height | float | Specifies the height of the text. |
| text | String | text string. |
| fontName | String | text font name. |
| fontColor | String | text font color. |
| size | float | text font size. |

**Returns:** Returns a shape object that represents the new text object.

---

## addText(pinX, pinY, width, height, text) (2 of 2) {#addtext_1}

Adds Text with defined PinX and PinY.

| Parameter | Type | Description |
| --- | --- | --- |
| pinX | float | Specifies the x-coordinate of the text's pin (center of rotation) in relation to the page. |
| pinY | float | Specifies the y-coordinate of the text's pin (center of rotation) in relation to the page. |
| text | String | text string. |

**Returns:** Returns a shape object that represents the new text object.

**Example:**

```python
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
