---
title: "Shape.setConnectorsType"
linktitle: "setConnectorsType"
articleTitle: "setConnectorsType"
second_title: "Aspose.Diagram for Python via Java"
description: "Set Connectors type"
type: docs
weight: 40
url: /python-java/asposediagram.api/shape/setconnectorstype/
---

## setConnectorsType(type) {#setconnectorstype}

Set Connectors type

| Parameter | Type | Description |
| --- | --- | --- |
| type | int | A ConnectorsTypeValue value. Connectors type value |

**Example:**

```python
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");

diagram = new aspose.diagram.Diagram("RetrieveShapeInfo.vsd");

// get a dynamic connector type shape by id
shape = diagram.getPages().getPage("Page-2").getShapes().getShape(3);

// set dynamic connector appearance
shape.setConnectorsType(aspose.diagram.ConnectorsTypeValue.STRAIGHT_LINES);

diagram.save("out-SetConnectorAppearance.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```
