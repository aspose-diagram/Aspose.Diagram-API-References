---
title: "Page.addActiveXControl"
linktitle: "addActiveXControl"
articleTitle: "addActiveXControl"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Creates an Activex Control."
type: docs
weight: 20
url: /nodejs/aspose.diagram/page/addactivexcontrol/
---

## addActiveXControl(type, pinX, pinY, width, height)

Creates an Activex Control.

| Parameter | Type | Description |
| --- | --- | --- |
| type | Number | ControlType |
| pinX | Number | Specifies the x-coordinate of the shape's pin (center of rotation) in relation to the page. |
| pinY | Number | Specifies the y-coordinate of the shape's pin (center of rotation) in relation to the page. |
| width | Number | Specifies the width of the shape in inches. |
| height | Number | Specifies the height of the shape in inches. |

**Returns:** long — `long`

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
// Instantiate Diagram Object
diagram = new aspose.diagram.Diagram();
// Insert an ActiveX control
diagram.getPages().get(0).addActiveXControl(aspose.diagram.ControlType.IMAGE, 1, 1, 1, 1);
diagram.save("out-InsertActiveXControl.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```
