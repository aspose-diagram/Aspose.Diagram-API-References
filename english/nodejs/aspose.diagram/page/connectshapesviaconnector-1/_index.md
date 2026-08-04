---
title: "Page.connectShapesViaConnector"
linktitle: "connectShapesViaConnector"
articleTitle: "connectShapesViaConnector"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Connect shapes via connector."
type: docs
weight: 190
url: /nodejs/aspose.diagram/page/connectshapesviaconnector-1/
---

## connectShapesViaConnector(shapeFromId, placeFrom, shapeToId, placeTo, connectorId)

Connect shapes via connector.

| Parameter | Type | Description |
| --- | --- | --- |
| shapeFromId | long | The ID of shape where the connector begins |
| placeFrom | Number | ConnectionPointPlace |
| shapeToId | long | The ID of shape where the connector ends |
| placeTo | Number | ConnectionPointPlace |
| connectorId | long | The ID of shape with type Dynamic connector |

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("AddingNewShape.vsdx");
// set sub shape ids
shapeFromId = 2;
shapeToId = 4;
// access a particular page
page = diagram.getPages().getPage("Page-3");
// initialize connector shape
shape = new aspose.diagram.Shape();
shape.getLine().getEndArrow().setValue(4);
shape.getLine().getLineWeight().setValue(0.01388);
// add shape
connecter1Id = page.addShape(shape, "Dynamic connector");
// connect sub-shapes
page.connectShapesViaConnector(
shapeFromId,
aspose.diagram.ConnectionPointPlace.RIGHT,
shapeToId,
aspose.diagram.ConnectionPointPlace.LEFT,
connecter1Id);
diagram.save("out-ConnectVisioSubShapes.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```
