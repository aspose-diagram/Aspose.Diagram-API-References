---
title: "Diagram.addMaster"
linktitle: "addMaster"
articleTitle: "addMaster"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Adds master to diagram from template file by master's ID."
type: docs
weight: 90
url: /nodejs/aspose.diagram/diagram/addmaster-2/
---

## addMaster(templateFilePath, masterID)

Adds master to diagram from template file by master's ID.

| Parameter | Type | Description |
| --- | --- | --- |
| templateFilePath | String | Path to template file(can be vdx, vst or vsd format). |
| masterID | Number | The unique ID of the master within masters collection in template. |

**Returns:** Number — `Number` The unique ID of the master within masters collection in this diagram.

**Example:**

```js
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
