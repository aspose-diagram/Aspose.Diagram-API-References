---
title: "Diagram.addShape"
linktitle: "addShape"
articleTitle: "addShape"
second_title: "Aspose.Diagram for Python via Java"
description: "Adds shape created by master to specific page."
type: docs
weight: 90
url: /python-java/asposediagram.api/diagram/addshape/
---

## addShape(newShape, masterName, pageNumber) (1 of 3) {#addshape}

Adds shape created by master to specific page.

| Parameter | Type | Description |
| --- | --- | --- |
| newShape | Shape | New shape object Shape . |
| masterName | String | Master's name. |
| pageNumber | int | Index of page. |

**Returns:** The unique ID of the shape within shapes collection on the specified page.

---

## addShape(pinX, pinY, masterName, pageNumber) (2 of 3) {#addshape_1}

Adds shape created by master on page with defined PinX and PinY.

| Parameter | Type | Description |
| --- | --- | --- |
| pinX | float | Specifies the x-coordinate of the shape's pin (center of rotation) in relation to the page. |
| pinY | float | Specifies the y-coordinate of the shape's pin (center of rotation) in relation to the page. |
| masterName | String | Master's name. |
| pageNumber | int | Index of page. |

**Returns:** The unique ID of the shape within shapes collection on the specified page.

**Example:**

```python
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");

diagram = new aspose.diagram.Diagram();
templateFileName = "NetApp-FAS-series.vss";

// Add master with stencil file path and master id
masterName = "FAS80xx rear empty";
diagram.addMaster(templateFileName, 2);

// Add master with stencil file path and master name
diagram.addMaster(templateFileName, masterName);

// adds master to diagram from source diagram
src = new aspose.diagram.Diagram(templateFileName);
diagram.addMaster(src, masterName);

// Adds shape with defined PinX and PinY.
diagram.addShape(2.0, 2.0, masterName, 0);
diagram.addShape(6.0, 6.0, masterName, 0);

// Adds shape with defined PinX,PinY,Width and Height.
diagram.addShape(7.0, 3.0, 1.5, 1.5, masterName, 0);

// Save resultant Image file
diagram.save("out-AddMasterFromStencil.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```

---

## addShape(pinX, pinY, width, height, masterName, pageNumber) (3 of 3) {#addshape_2}

Adds shape created by master on page with defined PinX,PinY,Width and Height.

| Parameter | Type | Description |
| --- | --- | --- |
| pinX | float | Specifies the x-coordinate of the shape's pin (center of rotation) in relation to the page. |
| pinY | float | Specifies the y-coordinate of the shape's pin (center of rotation) in relation to the page. |
| width | float | Specifies the width of the shape in inches. |
| height | float | Specifies the height of the shape in inches. |
| masterName | String | Master's name. |
| pageNumber | int | Index of page. |

**Returns:** The unique ID of the shape within shapes collection on the specified page.

**Example:**

```python
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");

diagram = new aspose.diagram.Diagram();
templateFileName = "NetApp-FAS-series.vss";

// Add master with stencil file path and master id
masterName = "FAS80xx rear empty";
diagram.addMaster(templateFileName, 2);

// Add master with stencil file path and master name
diagram.addMaster(templateFileName, masterName);

// adds master to diagram from source diagram
src = new aspose.diagram.Diagram(templateFileName);
diagram.addMaster(src, masterName);

// Adds shape with defined PinX and PinY.
diagram.addShape(2.0, 2.0, masterName, 0);
diagram.addShape(6.0, 6.0, masterName, 0);

// Adds shape with defined PinX,PinY,Width and Height.
diagram.addShape(7.0, 3.0, 1.5, 1.5, masterName, 0);

// Save resultant Image file
diagram.save("out-AddMasterFromStencil.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```
