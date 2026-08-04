---
title: "Shape.getTextBlock"
linktitle: "getTextBlock"
articleTitle: "getTextBlock"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Contains elements that specify the alignment, margins, and default tab stop positions of text in a shape's text block."
type: docs
weight: 900
url: /nodejs/aspose.diagram/shape/gettextblock/
---

## getTextBlock()

Contains elements that specify the alignment, margins, and default tab stop positions of text in a shape's text block.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("TextBoxes.vsdx");
// get the page by its name
page1 = diagram.getPages().getPage("Page-1");
// get shape by its ID
shape = page1.getShapes().getShape(1);
// set orientation angle
margin = new aspose.diagram.DoubleValue(4, aspose.diagram.MeasureConst.PT);
// set left, right, top and bottom margins of the shape's text block
shape.getTextBlock().setLeftMargin(margin);
shape.getTextBlock().setRightMargin(margin);
shape.getTextBlock().setTopMargin(margin);
shape.getTextBlock().setBottomMargin(margin);
// set the text direction
shape.getTextBlock().getTextDirection().setValue(aspose.diagram.TextDirectionValue.VERTICAL);
// set the text alignment
shape.getTextBlock().getVerticalAlign().setValue(aspose.diagram.VerticalAlignValue.MIDDLE);
// set the text block background color
shape.getTextBlock().getTextBkgnd().getUfe().setF("RGB(95,108,53)");
// set the background color transparency in percent
shape.getTextBlock().getTextBkgndTrans().setValue(50);
// set the distance between default tab stops for the selected shape.
shape.getTextBlock().getDefaultTabStop().setValue(2);
diagram.save("out-FormatShapeTextBlockSection.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```
