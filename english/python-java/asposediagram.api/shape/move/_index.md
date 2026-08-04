---
title: "Shape.move"
linktitle: "move"
articleTitle: "move"
second_title: "Aspose.Diagram for Python via Java"
description: "Moves shape on the dX and dY inches from current position."
type: docs
weight: 280
url: /python-java/asposediagram.api/shape/move/
---

## move(dX, dY) {#move}

Moves shape on the dX and dY inches from current position.

| Parameter | Type | Description |
| --- | --- | --- |
| dX | float | X offset double . |
| dY | float | Y offset double . |

**Example:**

```python
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
