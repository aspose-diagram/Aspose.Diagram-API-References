---
title: "StyleSheet"
linktitle: "StyleSheet"
second_title: "Aspose.Diagram for Python via Java API Reference"
description: "Represents a style defined in a document."
type: docs
weight: 3370
url: /python-java/asposediagram.api/stylesheet/
---

## StyleSheet class

Represents a style defined in a document.

## Constructors

| Name | Description |
| --- | --- |
| [StyleSheet](#constructor) | Constructor. |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [ID](#id) | int | The unique ID of the element within its parent element. |
| [Name](#name) | String | The name of the element. |
| [NameU](#nameu) | String | The universal name of the element. |
| [LineStyle](#linestyle) | StyleSheet | StyleSheet element from which this style inherits line formatting. |
| [FillStyle](#fillstyle) | StyleSheet | StyleSheet element from which this style inherits fill formatting. |
| [TextStyle](#textstyle) | StyleSheet | StyleSheet element from which this style inherits text formatting. |
| [Line](#line) | Line | Contains elements that control line attributes for a shape, such as pattern, weight, and color. These elements determine |
| [Fill](#fill) | Fill | Contains the current fill formatting values for the shape and the shape's drop shadow, including pattern, foreground col |
| [Event](#event) | Event | Contains elements that specify formulas that control shape events. |
| [StyleProp](#styleprop) | StyleProp | Contains elements that control style behavior, such as whether a style includes text, line, and fill attributes. |
| [TextBlock](#textblock) | TextBlock | Contains elements that specify the alignment, margins, and default tab stop positions of text in a shape's text block. |
| [Protection](#protection) | Protection | Locking helps prevent inadvertent changes to the shape but does not prevent Microsoft Visio from resetting values in oth |
| [Help](#help) | Help | Contains elements specifying the Shape element's Help file topic and copyright information. |
| [Misc](#misc) | Misc | Contains elements specifying the Shape element's Help file topic and copyright information. |
| [RulerGrid](#rulergrid) | RulerGrid | Contains elements that specify the settings of the page's rulers and grid. |
| [Image](#image) | Image | Contains the gamma, brightness, contrast, blur, sharpen, denoise, and transparency values for a bitmap. |
| [Group](#group) | Group | Contains elements that control how you add shapes to a group, move members of a group, and select groups. |
| [Layout](#layout) | Layout | Contains elements that control shape placement and connector routing settings. |
| [PageLayout](#pagelayout) | PageLayout | Contains Diagram that control the page layout settings for shapes and connectors, such as spacing between all shapes on  |
| [Chars](#chars) | CharCollection | Contains a collection of Char elements. |
| [Paras](#paras) | ParaCollection | Contains a collection of Para elements. |
| [TabsCollection](#tabscollection) | TabsCollection | Contains a collection of Tab elements. |
| [Connections](#connections) | ConnectionCollection | Contains a collection of Connection elements. |
| [ConnectionABCDs](#connectionabcds) | ConnectionABCDCollection | Contains a collection of ConnectionABCD elements. |
| [Foreign](#foreign) | Foreign | Contains elements specifying the width and height of an object from another program used in a Microsoft Visio document.  |
| [ForeignData](#foreigndata) | ForeignData | Contains a MIME (Multipurpose Internet Mail Extensions) encoded BLOB of picture data, such as Windows metafile, bitmap,  |

## Methods

| Name | Description |
| --- | --- |
| [deepClone](#deepclone) | Creates deep copy of this instance. |

### StyleSheet() {#constructor}

Constructor.

### StyleSheet.ID property {#id}

The unique ID of the element within its parent element.

**Type:** int

### StyleSheet.Name property {#name}

The name of the element.

**Type:** String

### StyleSheet.NameU property {#nameu}

The universal name of the element.

**Type:** String

### StyleSheet.LineStyle property {#linestyle}

StyleSheet element from which this style inherits line formatting.

**Type:** StyleSheet

### StyleSheet.FillStyle property {#fillstyle}

StyleSheet element from which this style inherits fill formatting.

**Type:** StyleSheet

### StyleSheet.TextStyle property {#textstyle}

StyleSheet element from which this style inherits text formatting.

**Type:** StyleSheet

### StyleSheet.Line property {#line}

Contains elements that control line attributes for a shape, such as pattern, weight, and color. These elements determine whether the line ends are formatted (for example, with an arrowhead), the size of line end formats, radius of the rounding circle applied to the line, and line cap style (round or square).

**Type:** Line

### StyleSheet.Fill property {#fill}

Contains the current fill formatting values for the shape and the shape's drop shadow, including pattern, foreground color, and background color.

**Type:** Fill

### StyleSheet.Event property {#event}

Contains elements that specify formulas that control shape events.

**Type:** Event

### StyleSheet.StyleProp property {#styleprop}

Contains elements that control style behavior, such as whether a style includes text, line, and fill attributes.

**Type:** StyleProp

### StyleSheet.TextBlock property {#textblock}

Contains elements that specify the alignment, margins, and default tab stop positions of text in a shape's text block.

**Type:** TextBlock

### StyleSheet.Protection property {#protection}

Locking helps prevent inadvertent changes to the shape but does not prevent Microsoft Visio from resetting values in other circumstances. It also does not protect against changes made in the ShapeSheet window.

**Type:** Protection

### StyleSheet.Help property {#help}

Contains elements specifying the Shape element's Help file topic and copyright information.

**Type:** Help

### StyleSheet.Misc property {#misc}

Contains elements specifying the Shape element's Help file topic and copyright information.

**Type:** Misc

### StyleSheet.RulerGrid property {#rulergrid}

Contains elements that specify the settings of the page's rulers and grid.

**Type:** RulerGrid

### StyleSheet.Image property {#image}

Contains the gamma, brightness, contrast, blur, sharpen, denoise, and transparency values for a bitmap.

**Type:** Image

### StyleSheet.Group property {#group}

Contains elements that control how you add shapes to a group, move members of a group, and select groups.

**Type:** Group

### StyleSheet.Layout property {#layout}

Contains elements that control shape placement and connector routing settings.

**Type:** Layout

### StyleSheet.PageLayout property {#pagelayout}

Contains Diagram that control the page layout settings for shapes and connectors, such as spacing between all shapes on the page, spacing between all connectors on the page, and routing style for all connectors on the page.

**Type:** PageLayout

### StyleSheet.Chars property {#chars}

Contains a collection of Char elements.

**Type:** CharCollection

### StyleSheet.Paras property {#paras}

Contains a collection of Para elements.

**Type:** ParaCollection

### StyleSheet.TabsCollection property {#tabscollection}

Contains a collection of Tab elements.

**Type:** TabsCollection

### StyleSheet.Connections property {#connections}

Contains a collection of Connection elements.

**Type:** ConnectionCollection

### StyleSheet.ConnectionABCDs property {#connectionabcds}

Contains a collection of ConnectionABCD elements.

**Type:** ConnectionABCDCollection

### StyleSheet.Foreign property {#foreign}

Contains elements specifying the width and height of an object from another program used in a Microsoft Visio document. Also includes elements specifying the distance the object's image is offset within its borders.

**Type:** Foreign

### StyleSheet.ForeignData property {#foreigndata}

Contains a MIME (Multipurpose Internet Mail Extensions) encoded BLOB of picture data, such as Windows metafile, bitmap, or OLE data.

**Type:** ForeignData

### deepClone() {#deepclone}

Creates deep copy of this instance.
