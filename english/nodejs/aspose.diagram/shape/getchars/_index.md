---
title: "Shape.getChars"
linktitle: "getChars"
articleTitle: "getChars"
second_title: "Aspose.Diagram for Node.js via Java"
description: "Contains a collection of Char elements."
type: docs
weight: 140
url: /nodejs/aspose.diagram/shape/getchars/
---

## getChars()

Contains a collection of Char elements.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("ApplyFontOnText.vsdx");
sourceShape = null;
// get page by name
page = diagram.getPages().getPage("Page-1");
// get shape by ID
shape = page.getShapes().getShape(1);
// clear shape text values and chars
shape.getText().getValue().clear();
shape.getChars().clear();
// mark character run and add text
shape.getText().getValue().add(new aspose.diagram.Cp(0));
shape.getText().getValue().add(new aspose.diagram.Txt("TextStyle_Regular\n"));
shape.getText().getValue().add(new aspose.diagram.Cp(1));
shape.getText().getValue().add(new aspose.diagram.Txt("TextStyle_Bold_Italic\n"));
shape.getText().getValue().add(new aspose.diagram.Cp(2));
shape.getText().getValue().add(new aspose.diagram.Txt("TextStyle_Underline_Italic\n"));
shape.getText().getValue().add(new aspose.diagram.Cp(3));
shape.getText().getValue().add(new aspose.diagram.Txt("TextStyle_Bold_Italic_Underline"));
// add formatting characters
shape.getChars().add(new aspose.diagram.Char());
shape.getChars().add(new aspose.diagram.Char());
shape.getChars().add(new aspose.diagram.Char());
shape.getChars().add(new aspose.diagram.Char());
// set properties e.g. color, font, size and style etc.
shape.getChars().get(0).setIX(0);
shape.getChars().get(0).getColor().setValue("#FF0000");
shape.getChars().get(0).getFont().setValue(4);
shape.getChars().get(0).getSize().setValue(0.22);
shape.getChars().get(0).getStyle().setValue(aspose.diagram.StyleValue.UNDEFINED);
// set properties e.g. color, font, size and style etc.
shape.getChars().get(1).setIX(1);
shape.getChars().get(1).getColor().setValue("#FF00FF");
shape.getChars().get(1).getFont().setValue(4);
shape.getChars().get(1).getSize().setValue(0.22);
shape.getChars().get(1).getStyle().setValue(aspose.diagram.StyleValue.BOLD |aspose.diagram. StyleValue.ITALIC);
// set properties e.g. color, font, size and style etc.
shape.getChars().get(2).setIX(2);
shape.getChars().get(2).getColor().setValue("#00FF00");
shape.getChars().get(2).getFont().setValue(4);
shape.getChars().get(2).getSize().setValue(0.22);
shape.getChars().get(2).getStyle().setValue(aspose.diagram.StyleValue.UNDERLINE | aspose.diagram.StyleValue.ITALIC);
// set properties e.g. color, font, size and style etc.
shape.getChars().get(3).setIX(3);
shape.getChars().get(3).getColor().setValue("#3333FF");
shape.getChars().get(3).getFont().setValue(4);
shape.getChars().get(3).getSize().setValue(0.22);
shape.getChars().get(3).getStyle().setValue(aspose.diagram.StyleValue.BOLD | aspose.diagram.StyleValue.ITALIC | aspose.diagram.StyleValue.UNDERLINE);
diagram.save("out-ApplyFontOnText.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```
