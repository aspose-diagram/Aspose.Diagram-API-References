---
title: "Shape.getLine"
linktitle: "getLine"
articleTitle: "getLine"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Contains elements that control line attributes for a shape, such as pattern, weight, and color."
type: docs
weight: 680
url: /nodejs/aspose.diagram/shape/getline/
---

## getLine()

Contains elements that control line attributes for a shape, such as pattern, weight, and color. These elements determine whether the line ends are formatted (for example, with an arrowhead), the size of line end formats, radius of the rounding circle applied to the line, and line cap style (round or square).

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("RetrieveShapeInfo.vsd");
// get a shape by id
shape = diagram.getPages().getPage("Page-2").getShapes().getShape(1);
// set line dash type by index
shape.getLine().getLinePattern().setValue(4);
// set line weight, defualt in PT
shape.getLine().getLineWeight().setValue(2);
// set color of the shape's line
shape.getLine().getLineColor().getUfe().setF("RGB(95,108,53)");
// set line rounding, default in inch
shape.getLine().getRounding().setValue(0.3125);
// set line caps
shape.getLine().getLineCap().setValue(aspose.diagram.BOOL.TRUE);
// set line color transparency in percent
shape.getLine().getLineColorTrans().setValue(50);
// add arrows to the connector or curve shapes
// select arrow type by index
shape.getLine().getBeginArrow().setValue(4);
shape.getLine().getEndArrow().setValue(4);
// set arrow size
shape.getLine().getBeginArrowSize().setValue(aspose.diagram.ArrowSizeValue.SMALL);
shape.getLine().getBeginArrowSize().setValue(aspose.diagram.ArrowSizeValue.SMALL);
diagram.save("out-SetLineData.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```
