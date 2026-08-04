---
title: "Page.applyStyle"
linktitle: "applyStyle"
articleTitle: "applyStyle"
second_title: "Aspose.Diagram for Python via Java"
description: "Applies style for full page."
type: docs
weight: 40
url: /python-java/asposediagram.api/page/applystyle/
---

## applyStyle(textStyle, lineStyle, fillStyle) {#applystyle}

Applies style for full page.

Default value is -1.

| Parameter | Type | Description |
| --- | --- | --- |
| textStyle | int | text Style id. |
| lineStyle | int | line Style id. |
| fillStyle | int | fill Style id. |

**Example:**

```python
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
