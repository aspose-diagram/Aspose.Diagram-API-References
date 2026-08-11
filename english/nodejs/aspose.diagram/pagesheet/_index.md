---
title: "PageSheet"
linktitle: "PageSheet"
second_title: "Aspose.Diagram for Node.js via Java API Reference"
description: "Contains elements that define the page sheet for a Page or Master element."
type: docs
weight: 1730
url: /nodejs/aspose.diagram/pagesheet/
---

## PageSheet class

Contains elements that define the page sheet for a Page or Master element.

## Methods

| Name | Description |
| --- | --- |
| [copy(source)](#copy) | Copies pagesheet from a source object. |
| [getActs()](#getacts) | Contains a collection of Act elements. |
| [getAnnotations()](#getannotations) | Contains elements that contain information about comments inserted into a document page. |
| [getConnectionABCDs()](#getconnectionabcds) | Contains a collection of ConnectionABCD elements. |
| [getConnections()](#getconnections) | Contains a collection of Connection elements. |
| [getFillStyle()](#getfillstyle) | StyleSheet element from which the PageSheet inherits fill formatting. |
| [getForeign()](#getforeign) | Contains elements specifying the width and height of an object from another program used in a Microsoft Visio document.  |
| [getForeignData()](#getforeigndata) | Contains a MIME (Multipurpose Internet Mail Extensions) encoded BLOB of picture data, such as Windows metafile, bitmap,  |
| [getHyperlinks()](#gethyperlinks) | Contains a collection of Hyperlink elements. |
| [getLayers()](#getlayers) | Contains a collection of Layer elements. |
| [getLineStyle()](#getlinestyle) | StyleSheet element from which the PageSheet inherits line formatting. |
| [getPageLayout()](#getpagelayout) | Contains Diagram that control the page layout settings for shapes and connectors, such as spacing between all shapes on  |
| [getPageProps()](#getpageprops) | Contains Diagram that control page attributes, such as the page width, height, and scale. |
| [getPrintProps()](#getprintprops) | Contains elements that control how the drawing page is formatted (appears) on the printer page. |
| [getProps()](#getprops) | Contains a collection of Prop elements. |
| [getRulerGrid()](#getrulergrid) | Contains elements that specify the settings of the page's rulers and grid. |
| [getScratchs()](#getscratchs) | Contains a collection of Scratch elements. |
| [getSmartTagDefs()](#getsmarttagdefs) | Contains a collection of SmartTagDef elements. |
| [getTextStyle()](#gettextstyle) | StyleSheet element from which the PageSheet inherits text formatting. |
| [getUniqueID()](#getuniqueid) | A GUID (globally unique identifier) for the element. |
| [getUsers()](#getusers) | Contains a collection of User elements. |
| [getXForm()](#getxform) | Contains elements specifying general positioning information about a shape. |
| [setFillStyle()](#setfillstyle) | StyleSheet element from which the PageSheet inherits fill formatting. |
| [setLineStyle()](#setlinestyle) | StyleSheet element from which the PageSheet inherits line formatting. |
| [setTextStyle()](#settextstyle) | StyleSheet element from which the PageSheet inherits text formatting. |

### copy(source) {#copy}

Copies pagesheet from a source object.

| Parameter | Type | Description |
| --- | --- | --- |
| source | PageSheet | source pagesheet. |

### getActs() {#getacts}

Contains a collection of Act elements.

### getAnnotations() {#getannotations}

Contains elements that contain information about comments inserted into a document page.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
var diagram = new aspose.diagram.Diagram("Drawing1.vsdx");
// get collection of the annotations
annotations = diagram.getPages().getPage("Page-1").getPageSheet().getAnnotations();
for (var it = annotations.iterator(); it.hasNext();) {
annotation = it.next();
var comment = annotation.getComment().getValue();
comment += "Updation mark";
annotation.getComment().setValue(comment);
}
diagram.save("out-EditPageLevelCommentInVisio.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```

### getConnectionABCDs() {#getconnectionabcds}

Contains a collection of ConnectionABCD elements.

### getConnections() {#getconnections}

Contains a collection of Connection elements.

### getFillStyle() {#getfillstyle}

StyleSheet element from which the PageSheet inherits fill formatting.

### getForeign() {#getforeign}

Contains elements specifying the width and height of an object from another program used in a Microsoft Visio document. Also includes elements specifying the distance the object's image is offset within its borders.

### getForeignData() {#getforeigndata}

Contains a MIME (Multipurpose Internet Mail Extensions) encoded BLOB of picture data, such as Windows metafile, bitmap, or OLE data.

### getHyperlinks() {#gethyperlinks}

Contains a collection of Hyperlink elements.

### getLayers() {#getlayers}

Contains a collection of Layer elements.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("Layers.vsdx");
// get Visio page
page = diagram.getPages().getPage("Page-1");
layers = page.getPageSheet().getLayers();
// iterate through the layers
for (var it = layers.iterator(); it.hasNext();) {
layer = it.next();
console.log("Name: " + layer.getName().getValue());
console.log("Visibility: " + layer.getVisible().getValue());
console.log("Status: " + layer.getStatus().getValue());
}
```

### getLineStyle() {#getlinestyle}

StyleSheet element from which the PageSheet inherits line formatting.

### getPageLayout() {#getpagelayout}

Contains Diagram that control the page layout settings for shapes and connectors, such as spacing between all shapes on the page, spacing between all connectors on the page, and routing style for all connectors on the page.

### getPageProps() {#getpageprops}

Contains Diagram that control page attributes, such as the page width, height, and scale.

### getPrintProps() {#getprintprops}

Contains elements that control how the drawing page is formatted (appears) on the printer page.

### getProps() {#getprops}

Contains a collection of Prop elements.

### getRulerGrid() {#getrulergrid}

Contains elements that specify the settings of the page's rulers and grid.

### getScratchs() {#getscratchs}

Contains a collection of Scratch elements.

### getSmartTagDefs() {#getsmarttagdefs}

Contains a collection of SmartTagDef elements.

### getTextStyle() {#gettextstyle}

StyleSheet element from which the PageSheet inherits text formatting.

### getUniqueID() {#getuniqueid}

A GUID (globally unique identifier) for the element.

### getUsers() {#getusers}

Contains a collection of User elements.

### getXForm() {#getxform}

Contains elements specifying general positioning information about a shape.

### setFillStyle() {#setfillstyle}

StyleSheet element from which the PageSheet inherits fill formatting.

### setLineStyle() {#setlinestyle}

StyleSheet element from which the PageSheet inherits line formatting.

### setTextStyle() {#settextstyle}

StyleSheet element from which the PageSheet inherits text formatting.
