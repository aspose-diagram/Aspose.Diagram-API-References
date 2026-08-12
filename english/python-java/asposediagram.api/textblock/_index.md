---
title: "TextBlock"
linktitle: "TextBlock"
second_title: "Aspose.Diagram for Python via Java API Reference"
description: "Contains elements that specify the alignment, margins, and default tab stop positions of text in a shape's text block."
type: docs
weight: 3440
url: /python-java/asposediagram.api/textblock/
---

## TextBlock class

Contains elements that specify the alignment, margins, and default tab stop positions of text in a shape's text block.

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [Del](#del) | int | A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted loca |
| [LeftMargin](#leftmargin) | DoubleValue | Specifies the distance between the left border of the text block and the text it contains. This value is independent of  |
| [RightMargin](#rightmargin) | DoubleValue | Specifies the distance between the right border of the text block and the text it contains. This value is independent of |
| [TopMargin](#topmargin) | DoubleValue | Specifies the distance between the top border of the text block and the first line of text it contains. |
| [BottomMargin](#bottommargin) | DoubleValue | Determines the distance between the bottom border of the text block and the last line of text it contains. The default i |
| [VerticalAlign](#verticalalign) | VerticalAlign | Specifies the vertical alignment of text within the text block. |
| [TextBkgnd](#textbkgnd) | ColorValue | Specifies the text background color for a shape. |
| [DefaultTabStop](#defaulttabstop) | DoubleValue | Specifies the interval of the default tab stops in a text block. |
| [TextDirection](#textdirection) | TextDirection | Specifies the direction of the characters in a text block. |
| [TextBkgndTrans](#textbkgndtrans) | DoubleValue | Specifies the transparency level for the background color of a shape's text block, from 0 (completely opaque) to 1 (comp |

## Methods

| Name | Description |
| --- | --- |
| [deepClone](#deepclone) | Creates deep copy of this instance. |

### TextBlock.Del property {#del}

A flag indicating whether the element has been deleted locally. A value of 1 indicates that the element was deleted locally. The value of the property is BOOL integer constant.

**Type:** int

### TextBlock.LeftMargin property {#leftmargin}

Specifies the distance between the left border of the text block and the text it contains. This value is independent of the scale of the drawing. If the drawing is scaled, the left margin remains the same.

**Type:** DoubleValue

### TextBlock.RightMargin property {#rightmargin}

Specifies the distance between the right border of the text block and the text it contains. This value is independent of the scale of the drawing. If the drawing is scaled, the right margin remains the same.

**Type:** DoubleValue

### TextBlock.TopMargin property {#topmargin}

Specifies the distance between the top border of the text block and the first line of text it contains.

**Type:** DoubleValue

### TextBlock.BottomMargin property {#bottommargin}

Determines the distance between the bottom border of the text block and the last line of text it contains. The default is 4 pt. This value is independent of the scale of the drawing. If the drawing is scaled, the bottom margin remains the same.

**Type:** DoubleValue

### TextBlock.VerticalAlign property {#verticalalign}

Specifies the vertical alignment of text within the text block.

**Type:** VerticalAlign

### TextBlock.TextBkgnd property {#textbkgnd}

Specifies the text background color for a shape.

**Type:** ColorValue

### TextBlock.DefaultTabStop property {#defaulttabstop}

Specifies the interval of the default tab stops in a text block.

**Type:** DoubleValue

### TextBlock.TextDirection property {#textdirection}

Specifies the direction of the characters in a text block.

**Type:** TextDirection

### TextBlock.TextBkgndTrans property {#textbkgndtrans}

Specifies the transparency level for the background color of a shape's text block, from 0 (completely opaque) to 1 (completely transparent).

**Type:** DoubleValue

### deepClone() {#deepclone}

Creates deep copy of this instance.
