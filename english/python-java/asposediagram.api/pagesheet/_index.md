---
title: "PageSheet"
linktitle: "PageSheet"
second_title: "Aspose.Diagram for Python via Java API Reference"
description: "Contains elements that define the page sheet for a Page or Master element."
type: docs
weight: 2320
url: /python-java/asposediagram.api/pagesheet/
---

## PageSheet class

Contains elements that define the page sheet for a Page or Master element.

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [LineStyle](#linestyle) | StyleSheet | StyleSheet element from which the PageSheet inherits line formatting. |
| [FillStyle](#fillstyle) | StyleSheet | StyleSheet element from which the PageSheet inherits fill formatting. |
| [TextStyle](#textstyle) | StyleSheet | StyleSheet element from which the PageSheet inherits text formatting. |
| [UniqueID](#uniqueid) | UUID | A GUID (globally unique identifier) for the element. |
| [XForm](#xform) | XForm | Contains elements specifying general positioning information about a shape. |
| [PageProps](#pageprops) | PageProps | Contains Diagram that control page attributes, such as the page width, height, and scale. |
| [RulerGrid](#rulergrid) | RulerGrid | Contains elements that specify the settings of the page's rulers and grid. |
| [PageLayout](#pagelayout) | PageLayout | Contains Diagram that control the page layout settings for shapes and connectors, such as spacing between all shapes on  |
| [PrintProps](#printprops) | PrintProps | Contains elements that control how the drawing page is formatted (appears) on the printer page. |
| [Scratchs](#scratchs) | ScratchCollection | Contains a collection of Scratch elements. |
| [Connections](#connections) | ConnectionCollection | Contains a collection of Connection elements. |
| [ConnectionABCDs](#connectionabcds) | ConnectionABCDCollection | Contains a collection of ConnectionABCD elements. |
| [Acts](#acts) | ActCollection | Contains a collection of Act elements. |
| [Layers](#layers) | LayerCollection | Contains a collection of Layer elements. |
| [Users](#users) | UserCollection | Contains a collection of User elements. |
| [Props](#props) | PropCollection | Contains a collection of Prop elements. |
| [Hyperlinks](#hyperlinks) | HyperlinkCollection | Contains a collection of Hyperlink elements. |
| [SmartTagDefs](#smarttagdefs) | SmartTagDefCollection | Contains a collection of SmartTagDef elements. |
| [Annotations](#annotations) | AnnotationCollection | Contains elements that contain information about comments inserted into a document page. |
| [Foreign](#foreign) | Foreign | Contains elements specifying the width and height of an object from another program used in a Microsoft Visio document.  |
| [ForeignData](#foreigndata) | ForeignData | Contains a MIME (Multipurpose Internet Mail Extensions) encoded BLOB of picture data, such as Windows metafile, bitmap,  |

## Methods

| Name | Description |
| --- | --- |
| [copy](#copy) | Copies pagesheet from a source object. |

### PageSheet.LineStyle property {#linestyle}

StyleSheet element from which the PageSheet inherits line formatting.

**Type:** StyleSheet

### PageSheet.FillStyle property {#fillstyle}

StyleSheet element from which the PageSheet inherits fill formatting.

**Type:** StyleSheet

### PageSheet.TextStyle property {#textstyle}

StyleSheet element from which the PageSheet inherits text formatting.

**Type:** StyleSheet

### PageSheet.UniqueID property {#uniqueid}

A GUID (globally unique identifier) for the element.

**Type:** UUID

### PageSheet.XForm property {#xform}

Contains elements specifying general positioning information about a shape.

**Type:** XForm

### PageSheet.PageProps property {#pageprops}

Contains Diagram that control page attributes, such as the page width, height, and scale.

**Type:** PageProps

### PageSheet.RulerGrid property {#rulergrid}

Contains elements that specify the settings of the page's rulers and grid.

**Type:** RulerGrid

### PageSheet.PageLayout property {#pagelayout}

Contains Diagram that control the page layout settings for shapes and connectors, such as spacing between all shapes on the page, spacing between all connectors on the page, and routing style for all connectors on the page.

**Type:** PageLayout

### PageSheet.PrintProps property {#printprops}

Contains elements that control how the drawing page is formatted (appears) on the printer page.

**Type:** PrintProps

### PageSheet.Scratchs property {#scratchs}

Contains a collection of Scratch elements.

**Type:** ScratchCollection

### PageSheet.Connections property {#connections}

Contains a collection of Connection elements.

**Type:** ConnectionCollection

### PageSheet.ConnectionABCDs property {#connectionabcds}

Contains a collection of ConnectionABCD elements.

**Type:** ConnectionABCDCollection

### PageSheet.Acts property {#acts}

Contains a collection of Act elements.

**Type:** ActCollection

### PageSheet.Layers property {#layers}

Contains a collection of Layer elements.

**Type:** LayerCollection

### PageSheet.Users property {#users}

Contains a collection of User elements.

**Type:** UserCollection

### PageSheet.Props property {#props}

Contains a collection of Prop elements.

**Type:** PropCollection

### PageSheet.Hyperlinks property {#hyperlinks}

Contains a collection of Hyperlink elements.

**Type:** HyperlinkCollection

### PageSheet.SmartTagDefs property {#smarttagdefs}

Contains a collection of SmartTagDef elements.

**Type:** SmartTagDefCollection

### PageSheet.Annotations property {#annotations}

Contains elements that contain information about comments inserted into a document page.

**Type:** AnnotationCollection

### PageSheet.Foreign property {#foreign}

Contains elements specifying the width and height of an object from another program used in a Microsoft Visio document. Also includes elements specifying the distance the object's image is offset within its borders.

**Type:** Foreign

### PageSheet.ForeignData property {#foreigndata}

Contains a MIME (Multipurpose Internet Mail Extensions) encoded BLOB of picture data, such as Windows metafile, bitmap, or OLE data.

**Type:** ForeignData

### copy(source) {#copy}

Copies pagesheet from a source object.

| Parameter | Type | Description |
| --- | --- | --- |
| source | PageSheet | source pagesheet. |
