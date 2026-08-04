---
title: "Diagram.getSolutionXMLs"
linktitle: "getSolutionXMLs"
articleTitle: "getSolutionXMLs"
second_title: "Aspose.Diagram for Node.js via Java"
description: "XML value."
type: docs
weight: 390
url: /nodejs/aspose.diagram/diagram/getsolutionxmls/
---

## getSolutionXMLs()

XML value.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("SolutionXML.vsdx");
// iterate through SolutionXML elements
for (it = diagram.getSolutionXMLs().iterator(); it.hasNext();) {
solutionXML = it.next();
// get name property
console.log(solutionXML.getName());
// get xml value
console.log(solutionXML.getXmlValue());
}
```
