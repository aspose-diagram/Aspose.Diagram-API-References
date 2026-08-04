---
title: "Diagram.addMaster"
linktitle: "addMaster"
articleTitle: "addMaster"
second_title: "Aspose.Diagram for Python via Java"
description: "Adds master to diagram from source diagram by master's Name or NameU."
type: docs
weight: 50
url: /python-java/asposediagram.api/diagram/addmaster/
---

## addMaster(srcDiagram, masterName) (1 of 3) {#addmaster}

Adds master to diagram from source diagram by master's Name or NameU.

| Parameter | Type | Description |
| --- | --- | --- |
| srcDiagram | Diagram | source diagram. |
| masterName | String | Master's Name or NameU. |

**Returns:** The unique ID of the master within masters collection in this diagram.

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

## addMaster(templateFilePath, masterName) (2 of 3) {#addmaster_1}

Adds master to diagram from template file by master's Name or NameU.

| Parameter | Type | Description |
| --- | --- | --- |
| templateFilePath | String | Path to template file(can be vdx, vst or vsd format). |
| masterName | String | Master's Name or NameU. |

**Returns:** The unique ID of the master within masters collection in this diagram.

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

## addMaster(templateFilePath, masterID) (3 of 3) {#addmaster_2}

Adds master to diagram from template file by master's ID.

| Parameter | Type | Description |
| --- | --- | --- |
| templateFilePath | String | Path to template file(can be vdx, vst or vsd format). |
| masterID | int | The unique ID of the master within masters collection in template. |

**Returns:** The unique ID of the master within masters collection in this diagram.

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
