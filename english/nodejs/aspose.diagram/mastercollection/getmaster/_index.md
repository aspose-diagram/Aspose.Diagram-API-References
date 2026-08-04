---
title: "MasterCollection.getMaster"
linktitle: "getMaster"
articleTitle: "getMaster"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Gets the element at the specified ID."
type: docs
weight: 50
url: /nodejs/aspose.diagram/mastercollection/getmaster/
---

## getMaster(ID)

Gets the element at the specified ID.

| Parameter | Type | Description |
| --- | --- | --- |
| ID | Number |  |

**Returns:** Master — `Master`

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("RetrieveMasterInfo.vdx");
// Get master object by id
master = diagram.getMasters().getMaster(2);
console.log("Master ID : " + master.getID());
console.log("Master Name : " + master.getName());
console.log("Master Name : " + master.getUniqueID());
```
