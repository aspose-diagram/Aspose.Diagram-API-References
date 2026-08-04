---
title: "Shape.refreshData"
linktitle: "refreshData"
articleTitle: "refreshData"
second_title: "Aspose.Diagram for Python via Java"
description: ""
type: docs
weight: 210
url: /python-java/asposediagram.api/shape/refreshdata/
---

## refreshData() (1 of 2) {#refreshdata}

---

## refreshData(options) (2 of 2) {#refreshdata_1}

Refreshes shape's position including xform ,connection and geom when changing shape's text or other's .

We will gather shape's data such as shape's text then calculate shape's position. This method is only used to refresh shape's data .

**Example:**

```python
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");

diagram = new aspose.diagram.Diagram("AddingNewShape.vsdx");

// get page by name
page = diagram.getPages().getPage("Page-2");

// Add master with stencil file path and master id
masterName = "Rectangle";
// Add master with stencil file path and master name
diagram.addMaster("BasicShapes.vss", masterName);

// page indexing starts from 0
PageIndex = 1;
width = 2, height = 2, pinX = 4.25, pinY = 4.5;
// Add a new rectangle shape
rectangleId = diagram.addShape(pinX, pinY, width, height, masterName, PageIndex);

// set shape properties
rectangle = page.getShapes().getShape(rectangleId);
rectangle.getXForm().getPinX().setValue(5);
rectangle.getXForm().getPinY().setValue(5);
rectangle.setType(aspose.diagram.TypeValue.SHAPE);
rectangle.getText().getValue().add(new aspose.diagram.Txt("Aspose Diagram"));
rectangle.setTextStyle(diagram.getStyleSheets().get(3));
rectangle.getLine().getLineColor().setValue("#ff0000");
rectangle.getLine().getLineWeight().setValue(0.03);
rectangle.getLine().getRounding().setValue(0.1);
rectangle.getFill().getFillBkgnd().setValue("#ff00ff");
rectangle.getFill().getFillForegnd().setValue("#ebf8df");

rectangle.refreshData();

diagram.save("out-AddShape.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```
