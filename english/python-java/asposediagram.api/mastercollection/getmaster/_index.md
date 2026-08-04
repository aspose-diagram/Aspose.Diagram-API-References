---
title: "MasterCollection.getMaster"
linktitle: "getMaster"
articleTitle: "getMaster"
second_title: "Aspose.Diagram for Python via Java"
description: "Gets the element at the specified ID."
type: docs
weight: 30
url: /python-java/asposediagram.api/mastercollection/getmaster/
---

## getMaster(ID) {#getmaster}

Gets the element at the specified ID.

| Parameter | Type | Description |
| --- | --- | --- |
| ID | int |  |

**Example:**

```python
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");

diagram = new aspose.diagram.Diagram("RetrieveMasterInfo.vdx");

// Get master object by id
master = diagram.getMasters().getMaster(2);
console.log("Master ID : " + master.getID());
console.log("Master Name : " + master.getName());
console.log("Master Name : " + master.getUniqueID());
```
