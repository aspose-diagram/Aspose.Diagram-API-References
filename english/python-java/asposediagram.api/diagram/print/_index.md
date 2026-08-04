---
title: "Diagram.print"
linktitle: "print"
articleTitle: "print"
second_title: "Aspose.Diagram for Python via Java"
description: "Print the whole document to the specified printer,using the standard (no User Interface) print controller."
type: docs
weight: 100
url: /python-java/asposediagram.api/diagram/print/
---

## print(printerName) (1 of 2) {#print}

Print the whole document to the specified printer,using the standard (no User Interface) print controller.

If printerName is Null or empty will be used default printer.

| Parameter | Type | Description |
| --- | --- | --- |
| printerName | String | The name of the printer.Can be Null |

---

## print(printerName, documentName) (2 of 2) {#print_1}

Prints the document,using the standard (no User Interface) print controller and a document name.

| Parameter | Type | Description |
| --- | --- | --- |
| printerName | String | The name of the printer.Can be Null |
| documentName | String | The document name to display (for example, in a print status dialog box or printer queue) while printing the document. |

**Example:**

```python
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");

diagram = new aspose.diagram.Diagram("Pages.vsdx");

// call the print method to print whole Diagram using the printer name
// and set document name in the print job
diagram.print("Microsoft Print to PDF", "Job name while printing with Aspose.Diagram");
```
