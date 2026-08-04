---
title: "Shape.move"
linktitle: "move"
articleTitle: "move"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Moves shape on the dX and dY inches from current position."
type: docs
weight: 1080
url: /nodejs/aspose.diagram/shape/move/
---

## move(dX, dY)

Moves shape on the dX and dY inches from current position.

| Parameter | Type | Description |
| --- | --- | --- |
| dX | Number | X offset |
| dY | Number | Y offset |

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("GroupShapes.vsdx");
// get page by name
page = diagram.getPages().getPage("Page-3");
// get shape by id
shape = page.getShapes().getShape(16);
// move shape from its position, it adds values in coordinates
shape.move(1, 1);
diagram.save("out-MoveVisioShape.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```
