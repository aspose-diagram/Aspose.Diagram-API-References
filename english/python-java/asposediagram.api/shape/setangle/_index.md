---
title: "Shape.setAngle"
linktitle: "setAngle"
articleTitle: "setAngle"
second_title: "Aspose.Diagram for Python via Java"
description: "Sets new angle of shape."
type: docs
weight: 260
url: /python-java/asposediagram.api/shape/setangle/
---

## setAngle(angle) {#setangle}

Sets new angle of shape. The angle's unit is radian.

| Parameter | Type | Description |
| --- | --- | --- |
| angle | float | New angle which unit is radian not degree double . |

**Example:**

```python
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");

diagram = new aspose.diagram.Diagram("RetrieveShapeInfo.vsd");

shape = diagram.getPages().getPage("Page-2").getShapes().getShape(2);

// Add a shape and set the angle
shape.setAngle(190);

diagram.save("out-RotateVisioShape.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```
