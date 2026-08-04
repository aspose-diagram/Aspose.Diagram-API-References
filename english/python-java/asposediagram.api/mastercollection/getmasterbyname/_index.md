---
title: "MasterCollection.getMasterByName"
linktitle: "getMasterByName"
articleTitle: "getMasterByName"
second_title: "Aspose.Diagram for Python via Java"
description: "Get master by name."
type: docs
weight: 40
url: /python-java/asposediagram.api/mastercollection/getmasterbyname/
---

## getMasterByName(name) {#getmasterbyname}

Get master by name.

| Parameter | Type | Description |
| --- | --- | --- |
| name | String |  |

**Example:**

```python
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");

diagram = new aspose.diagram.Diagram("BasicShapes.vss");

// Get master object by name
master = diagram.getMasters().getMasterByName("Circle");
console.log("Master ID : " + master.getID());
console.log("Master Name : " + master.getName());
console.log("Master Name : " + master.getUniqueID());
```
