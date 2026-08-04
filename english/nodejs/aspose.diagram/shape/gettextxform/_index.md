---
title: "Shape.getTextXForm"
linktitle: "getTextXForm"
articleTitle: "getTextXForm"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Contains elements that specify positioning information about a shape's text block."
type: docs
weight: 920
url: /nodejs/aspose.diagram/shape/gettextxform/
---

## getTextXForm()

Contains elements that specify positioning information about a shape's text block.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("TextBoxes.vsdx");
// get shape
shape = diagram.getPages().getPage("Page-1").getShapes().getShape(1);
// set text position at the bottom,
// TxtLocPinY = "TxtHeight*1" and TxtPinY = "Height*0"
shape.getTextXForm().getTxtLocPinY().setValue(shape.getTextXForm().getTxtHeight().getValue());
shape.getTextXForm().getTxtPinY().setValue(0);
// set orientation angle
angleDeg = 0;
angleRad = (Math.PI / 180) * angleDeg;
shape.getTextXForm().getTxtAngle().setValue(angleRad);
diagram.save("out-SetShapeTextPositionAtBottom.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```
