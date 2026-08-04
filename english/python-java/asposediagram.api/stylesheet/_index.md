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
| [ID](/python-java/asposediagram.api/stylesheet/id/) | int | The unique ID of the element within its parent element. |
| [Name](/python-java/asposediagram.api/stylesheet/name/) | String | The name of the element. |
| [NameU](/python-java/asposediagram.api/stylesheet/nameu/) | String | The universal name of the element. |
| [LineStyle](/python-java/asposediagram.api/stylesheet/linestyle/) | StyleSheet | StyleSheet element from which this style inherits line formatting. |
| [FillStyle](/python-java/asposediagram.api/stylesheet/fillstyle/) | StyleSheet | StyleSheet element from which this style inherits fill formatting. |
| [TextStyle](/python-java/asposediagram.api/stylesheet/textstyle/) | StyleSheet | StyleSheet element from which this style inherits text formatting. |
| [Line](/python-java/asposediagram.api/stylesheet/line/) | Line | Contains elements that control line attributes for a shape, such as pattern, weight, and color. These elements determine |
| [Fill](/python-java/asposediagram.api/stylesheet/fill/) | Fill | Contains the current fill formatting values for the shape and the shape's drop shadow, including pattern, foreground col |
| [Event](/python-java/asposediagram.api/stylesheet/event/) | Event | Contains elements that specify formulas that control shape events. |
| [StyleProp](/python-java/asposediagram.api/stylesheet/styleprop/) | StyleProp | Contains elements that control style behavior, such as whether a style includes text, line, and fill attributes. |
| [TextBlock](/python-java/asposediagram.api/stylesheet/textblock/) | TextBlock | Contains elements that specify the alignment, margins, and default tab stop positions of text in a shape's text block. |
| [Protection](/python-java/asposediagram.api/stylesheet/protection/) | Protection | Locking helps prevent inadvertent changes to the shape but does not prevent Microsoft Visio from resetting values in oth |
| [Help](/python-java/asposediagram.api/stylesheet/help/) | Help | Contains elements specifying the Shape element's Help file topic and copyright information. |
| [Misc](/python-java/asposediagram.api/stylesheet/misc/) | Misc | Contains elements specifying the Shape element's Help file topic and copyright information. |
| [RulerGrid](/python-java/asposediagram.api/stylesheet/rulergrid/) | RulerGrid | Contains elements that specify the settings of the page's rulers and grid. |
| [Image](/python-java/asposediagram.api/stylesheet/image/) | Image | Contains the gamma, brightness, contrast, blur, sharpen, denoise, and transparency values for a bitmap. |
| [Group](/python-java/asposediagram.api/stylesheet/group/) | Group | Contains elements that control how you add shapes to a group, move members of a group, and select groups. |
| [Layout](/python-java/asposediagram.api/stylesheet/layout/) | Layout | Contains elements that control shape placement and connector routing settings. |
| [PageLayout](/python-java/asposediagram.api/stylesheet/pagelayout/) | PageLayout | Contains Diagram that control the page layout settings for shapes and connectors, such as spacing between all shapes on  |
| [Chars](/python-java/asposediagram.api/stylesheet/chars/) | CharCollection | Contains a collection of Char elements. |
| [Paras](/python-java/asposediagram.api/stylesheet/paras/) | ParaCollection | Contains a collection of Para elements. |
| [TabsCollection](/python-java/asposediagram.api/stylesheet/tabscollection/) | TabsCollection | Contains a collection of Tab elements. |
| [Connections](/python-java/asposediagram.api/stylesheet/connections/) | ConnectionCollection | Contains a collection of Connection elements. |
| [ConnectionABCDs](/python-java/asposediagram.api/stylesheet/connectionabcds/) | ConnectionABCDCollection | Contains a collection of ConnectionABCD elements. |
| [Foreign](/python-java/asposediagram.api/stylesheet/foreign/) | Foreign | Contains elements specifying the width and height of an object from another program used in a Microsoft Visio document.  |
| [ForeignData](/python-java/asposediagram.api/stylesheet/foreigndata/) | ForeignData | Contains a MIME (Multipurpose Internet Mail Extensions) encoded BLOB of picture data, such as Windows metafile, bitmap,  |

## Methods

| Name | Description |
| --- | --- |
| [deepClone](/python-java/asposediagram.api/stylesheet/deepclone/) | Creates deep copy of this instance. |
