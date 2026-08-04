---
title: "MasterCollection.isExist"
linktitle: "isExist"
articleTitle: "isExist"
second_title: "Aspose.Diagram for Python via Java"
description: "Is exist master in the collection."
type: docs
weight: 70
url: /python-java/asposediagram.api/mastercollection/isexist/
---

## isExist(name) {#isexist}

Is exist master in the collection.

| Parameter | Type | Description |
| --- | --- | --- |
| name | String |  |

**Example:**

```python
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");

diagram = new aspose.diagram.Diagram("BasicShapes.vss");

// check master object by name
isPresent = diagram.getMasters().isExist("60 degree single");

console.log("Master Presence : " + isPresent);
```
