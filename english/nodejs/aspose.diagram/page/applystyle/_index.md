---
title: "Page.applyStyle"
linktitle: "applyStyle"
articleTitle: "applyStyle"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Applies style for full page."
type: docs
weight: 130
url: /nodejs/aspose.diagram/page/applystyle/
---

## applyStyle(textStyle, lineStyle, fillStyle)

Applies style for full page. Default value is -1.

| Parameter | Type | Description |
| --- | --- | --- |
| textStyle | Number | text Style id. |
| lineStyle | Number | line Style id. |
| fillStyle | Number | fill Style id. |

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("ReadDiagramFile.vsd");
//Define a new StyleSheet
st = new aspose.diagram.StyleSheet();
st.setID(diagram.getStyleSheets().getCount() + 1);
ch = new aspose.diagram.Char();
ch.getColor().setValue("#00ff00");
ch.setIX(0);
st.getChars().add(ch);
st.getLine().getLineColor().setValue("#ff0000");
st.getLine().getLinePattern().setValue(1);
st.getLine().getLineWeight().setValue(0.01);
st.getFill().getFillForegnd().setValue("#0000ff");
st.getFill().getFillPattern().setValue(1);
st.getFill().getShdwPattern().setValue(0);
//Add the stylesheet to Stylesheets collection
diagram.getStyleSheets().add(st);
shapes = diagram.getPages().get(0).getShapes();
for (var it = shapes.iterator(); it.hasNext();) {
shape = it.next();
shape.getLine().getLinePattern().setValue(1);
shape.getFill().getFillPattern().setValue(1);
}
//Apply the stylesheet
diagram.getPages().get(0).applyStyle(st.getID(), st.getID(), st.getID());
diagram.save("out-ApplyStyleToVisioDiagramPage.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```
