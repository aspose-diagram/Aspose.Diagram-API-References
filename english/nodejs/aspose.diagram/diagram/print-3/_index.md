---
title: "Diagram.print"
linktitle: "print"
articleTitle: "print"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Prints the document,using the standard (no User Interface) print controller and a document name."
type: docs
weight: 540
url: /nodejs/aspose.diagram/diagram/print-3/
---

## print(printerName, documentName)

Prints the document,using the standard (no User Interface) print controller and a document name.

| Parameter | Type | Description |
| --- | --- | --- |
| printerName | String | The name of the printer.Can be Null |
| documentName | String | The document name to display (for example, in a print status dialog box or printer queue) while printing the document. |

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("Pages.vsdx");
// call the print method to print whole Diagram using the printer name
// and set document name in the print job
diagram.print("Microsoft Print to PDF", "Job name while printing with Aspose.Diagram");
```
