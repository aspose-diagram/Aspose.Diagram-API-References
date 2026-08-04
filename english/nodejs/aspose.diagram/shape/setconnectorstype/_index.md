---
title: "Shape.setConnectorsType"
linktitle: "setConnectorsType"
articleTitle: "setConnectorsType"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Set Connectors type"
type: docs
weight: 1180
url: /nodejs/aspose.diagram/shape/setconnectorstype/
---

## setConnectorsType(type)

Set Connectors type

| Parameter | Type | Description |
| --- | --- | --- |
| type | Number | ConnectorsTypeValue |

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("RetrieveShapeInfo.vsd");
// get a dynamic connector type shape by id
shape = diagram.getPages().getPage("Page-2").getShapes().getShape(3);
// set dynamic connector appearance
shape.setConnectorsType(aspose.diagram.ConnectorsTypeValue.STRAIGHT_LINES);
diagram.save("out-SetConnectorAppearance.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```
