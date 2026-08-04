---
title: "MasterCollection.isExist"
linktitle: "isExist"
articleTitle: "isExist"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Is exist master in the collection."
type: docs
weight: 90
url: /nodejs/aspose.diagram/mastercollection/isexist/
---

## isExist(name)

Is exist master in the collection.

| Parameter | Type | Description |
| --- | --- | --- |
| name | String |  |

**Returns:** boolean — `boolean`

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("BasicShapes.vss");
// check master object by name
isPresent = diagram.getMasters().isExist("60 degree single");
console.log("Master Presence : " + isPresent);
```
