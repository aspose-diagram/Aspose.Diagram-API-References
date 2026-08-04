---
title: "StyleSheet Class"
linktitle: "StyleSheet"
articleTitle: "StyleSheet"
second_title: "Aspose.Diagram for Python via Java"
description: "Represents a style defined in a document."
type: docs
weight: 3370
url: /python-java/asposediagram.api/stylesheet/
---

## StyleSheet class

Represents a style defined in a document.

```python
StyleSheet()
```

Constructor.

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [ID](./id/) | int | The unique ID of the element within its parent element. |
| [Name](./name/) | String | The name of the element. |
| [NameU](./nameu/) | String | The universal name of the element. |
| [LineStyle](./linestyle/) | StyleSheet | StyleSheet element from which this style inherits line formatting. |
| [FillStyle](./fillstyle/) | StyleSheet | StyleSheet element from which this style inherits fill formatting. |
| [TextStyle](./textstyle/) | StyleSheet | StyleSheet element from which this style inherits text formatting. |
| [Line](./line/) | Line | Contains elements that control line attributes for a shape, such as pattern, weight, and color. These elements determine |
| [Fill](./fill/) | Fill | Contains the current fill formatting values for the shape and the shape's drop shadow, including pattern, foreground col |
| [Event](./event/) | Event | Contains elements that specify formulas that control shape events. |
| [StyleProp](./styleprop/) | StyleProp | Contains elements that control style behavior, such as whether a style includes text, line, and fill attributes. |
| [TextBlock](./textblock/) | TextBlock | Contains elements that specify the alignment, margins, and default tab stop positions of text in a shape's text block. |
| [Protection](./protection/) | Protection | Locking helps prevent inadvertent changes to the shape but does not prevent Microsoft Visio from resetting values in oth |
| [Help](./help/) | Help | Contains elements specifying the Shape element's Help file topic and copyright information. |
| [Misc](./misc/) | Misc | Contains elements specifying the Shape element's Help file topic and copyright information. |
| [RulerGrid](./rulergrid/) | RulerGrid | Contains elements that specify the settings of the page's rulers and grid. |
| [Image](./image/) | Image | Contains the gamma, brightness, contrast, blur, sharpen, denoise, and transparency values for a bitmap. |
| [Group](./group/) | Group | Contains elements that control how you add shapes to a group, move members of a group, and select groups. |
| [Layout](./layout/) | Layout | Contains elements that control shape placement and connector routing settings. |
| [PageLayout](./pagelayout/) | PageLayout | Contains Diagram that control the page layout settings for shapes and connectors, such as spacing between all shapes on  |
| [Chars](./chars/) | CharCollection | Contains a collection of Char elements. |
| [Paras](./paras/) | ParaCollection | Contains a collection of Para elements. |
| [TabsCollection](./tabscollection/) | TabsCollection | Contains a collection of Tab elements. |
| [Connections](./connections/) | ConnectionCollection | Contains a collection of Connection elements. |
| [ConnectionABCDs](./connectionabcds/) | ConnectionABCDCollection | Contains a collection of ConnectionABCD elements. |
| [Foreign](./foreign/) | Foreign | Contains elements specifying the width and height of an object from another program used in a Microsoft Visio document.  |
| [ForeignData](./foreigndata/) | ForeignData | Contains a MIME (Multipurpose Internet Mail Extensions) encoded BLOB of picture data, such as Windows metafile, bitmap,  |

## Methods

| Name | Description |
| --- | --- |
| [deepClone](./deepclone/) | Creates deep copy of this instance. |
