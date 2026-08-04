---
title: "Master.setIcon"
linktitle: "setIcon"
articleTitle: "setIcon"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Specifies a MIME (Multipurpose Internet Mail Extensions) encoded binary icon (in .ico format) for a Master or MasterShortcut element in a document."
type: docs
weight: 220
url: /nodejs/aspose.diagram/master/seticon/
---

## setIcon()

Specifies a MIME (Multipurpose Internet Mail Extensions) encoded binary icon (in .ico format) for a Master or MasterShortcut element in a document.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
fs = require("fs");
stencil = new aspose.diagram.Diagram("Timeline.vss");
// get master
master = stencil.getMasters().getMasterByName("Diamond milestone");
// get byte array
bytes = master.getIcon();
// create an image file and write byte array to the image
fs.writeFileSync("out-MasterIcon.png", bytes);
```
