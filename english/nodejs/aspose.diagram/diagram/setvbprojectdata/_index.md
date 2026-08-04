---
title: "Diagram.setVbProjectData"
linktitle: "setVbProjectData"
articleTitle: "setVbProjectData"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Contains the Microsoft Visual Basic for Applications project data in MIME (Multipurpose Internet Mail Extensions) encoded format."
type: docs
weight: 700
url: /nodejs/aspose.diagram/diagram/setvbprojectdata/
---

## setVbProjectData()

Contains the Microsoft Visual Basic for Applications project data in MIME (Multipurpose Internet Mail Extensions) encoded format.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("Macro.vsdm");
// remove all macros
diagram.setVbProjectData(null);
// save the Visio diagram
diagram.save("out-RemoveMacros.vssm", aspose.diagram.SaveFileFormat.VSSM);
```
