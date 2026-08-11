---
title: "Page"
linktitle: "Page"
second_title: "Aspose.Diagram for Node.js via Java API Reference"
description: "Contains elements that define a page in the document."
type: docs
weight: 1650
url: /nodejs/aspose.diagram/page/
---

## Page class

Contains elements that define a page in the document.

```js
new Page()
```

Constructor.

## Methods

| Name | Description |
| --- | --- |
| [addActiveXControl(type, pinX, pinY, width, height)](#addactivexcontrol) | Creates an Activex Control. |
| [addComment(shapeID, comment)](#addcomment) | Adds comment to a shape with shape's id. |
| [addComment(shape, comment)](#addcomment-1) | Adds comment to a shape. |
| [addComment(pinX, pinY, comment)](#addcomment-2) | Adds comment with defined PinX and PinY. |
| [addShape(pinX, pinY, masterName, isCalculate)](#addshape) | Adds shape created by master on page with defined PinX and PinY. |
| [addShape(pinX, pinY, width, height, masterName, isCalculate)](#addshape-1) | Adds shape created by master on page with defined PinX and PinY. |
| [addShape(pinX, pinY, masterName)](#addshape-2) | Adds shape created by master on page with defined PinX and PinY. |
| [addShape(pinX, pinY, width, height, masterName)](#addshape-3) | Adds shape created by master on page with defined PinX,PinY,Width and Height. |
| [addShape(newShape, masterName)](#addshape-4) | Adds shape created by master to specific page. |
| [addText(pinX, pinY, width, height, text, fontName, fontColor, size)](#addtext) | Adds Text with defined PinX and PinY. |
| [addText(pinX, pinY, text)](#addtext-1) | Adds Text with defined PinX and PinY. |
| [applyStyle(textStyle, lineStyle, fillStyle)](#applystyle) | Applies style for full page. Default value is -1. |
| [autoSpaceShapes(shapes)](#autospaceshapes) | Auto space shapes |
| [bringForward(shapeId)](#bringforward) | Brings a shape,defined by ID, forward one position in the z-order. |
| [bringToFront(shapeId)](#bringtofront) | Brings a shape,defined by ID, to the front of the z-order. |
| [centerDrawing()](#centerdrawing) | Centers a page's shapes with respect to the extent of the page. Centering shapes does not change their position relative |
| [connectShapesViaConnector(shapeFrom, placeFrom, shapeTo, placeTo, connector)](#connectshapesviaconnector) | Connect shapes via connector. |
| [connectShapesViaConnector(shapeFromId, placeFrom, shapeToId, placeTo, connectorId)](#connectshapesviaconnector-1) | Connect shapes via connector. |
| [connectShapesViaConnector(shapeFromId, fromConnectionName, shapeToId, toConnectionName, connectorId)](#connectshapesviaconnector-2) | Connect shapes via connector. |
| [connectShapesViaConnectorIndex(shapeFromId, fromIndex, shapeToId, toIndex, connectorId)](#connectshapesviaconnectorindex) | Connect shapes via connector index. |
| [connectShapesViaConnectorIndex(shapeFrom, fromIndex, shapeTo, toIndex, connector)](#connectshapesviaconnectorindex-1) | Connect shapes via connector index. |
| [constructor_overload$1()](#constructor-overload1) | Constructor. |
| [copy()](#copy) |  |
| [dispose()](#dispose) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [drawEllipse(pinX, pinY, width, height)](#drawellipse) | The process of drawing Ellipse. |
| [drawLine(beginX, beginY, endX, endY)](#drawline) | The process of drawing a single line. |
| [drawLine(pinX, pinY, width, height, xyArray)](#drawline-1) | The process of drawing line. |
| [drawOwal(x1, y1, x2, y2)](#drawowal) | The process of drawing owal. |
| [drawPolyline(xyArray)](#drawpolyline) | The process of drawing Polyline. |
| [drawPolyline(pinX, pinY, width, height, xyArray)](#drawpolyline-1) | The process of drawing Polyline. |
| [drawRectangle(pinX, pinY, width, height)](#drawrectangle) | The process of drawing rectangle. |
| [drawRectangle(x1, y1, x2, y2)](#drawrectangle-1) | The process of drawing rectangle. |
| [dropContainer(targetShape)](#dropcontainer) | The process of creating Container. |
| [getAssociatedPage()](#getassociatedpage) | The ID of the original drawing page that was marked up on separate markup overlays by reviewers of the drawing. |
| [getBackground()](#getbackground) | A flag indicating if the page is a background page. The value of the property is BOOL integer constant. |
| [getBackPage()](#getbackpage) | The page's background page. |
| [getConnects()](#getconnects) | Contains a Connect element for each connection between two shapes in a drawing. |
| [getID()](#getid) | The unique ID of the element within its parent element. |
| [getName()](#getname) | The name of the element. |
| [getNameU()](#getnameu) | The universal name of the element. |
| [getPages()](#getpages) | Page collection. |
| [getPageSheet()](#getpagesheet) | Contains elements that define the page sheet for a Page or Master element. |
| [getReviewerID()](#getreviewerid) | The ID of the reviewer associated with the markup overlay. |
| [getShapes()](#getshapes) | Shape collection. |
| [getViewCenterX()](#getviewcenterx) | ViewCenterX and ViewCenterY specify a center point on a page that a new view (window) assumes when it is opened initiall |
| [getViewCenterY()](#getviewcentery) | ViewCenterX and ViewCenterY specify a center point on a page that a new view (window) assumes when it is opened initiall |
| [getViewScale()](#getviewscale) | The default magnification factor to use when a new view (window) of the page is opened. For example, 1 = 100%; 1.5 = 150 |
| [glueShapes(shapeFrom, placeTo, shapeTo)](#glueshapes) | Glue shapes. |
| [glueShapes(shapeFromId, placeTo, shapeToId)](#glueshapes-1) | Glue shapes |
| [glueShapesInContainer(shapeFromId, shapeToBeginConnectionName, shapeToEndConnectionName, shapeToId)](#glueshapesincontainer) | Glue shapes in container using connection name |
| [glueShapesInContainer(shapeFromId, shapeToBeginConnectionIndex, shapeToEndConnectionIndex, shapeToId)](#glueshapesincontainer-1) | Glue shapes in container |
| [glueShapesInContainerByID(shapeFromId, shapeToBeginConnectionID, shapeToEndConnectionID, shapeToId)](#glueshapesincontainerbyid) | Glue shapes by connection id in container |
| [glueShapeToConnectorBeginX(shapeFromId, connectionName, connectorId)](#glueshapetoconnectorbeginx) | Glue shape to Connector's BeginX |
| [glueShapeToConnectorEndX(shapeToId, connectionName, connectorId)](#glueshapetoconnectorendx) | Glue shape to Connector's EndX |
| [layout(options)](#layout) | Lays out the shapes and/or reroutes the connectors for the page. |
| [moveTo(index)](#moveto) | Moves the page to another location in the pages. |
| [sendBackward(shapeId)](#sendbackward) | Moves a shape,defined by ID, back one position in the z-order. |
| [sendToBack(shapeId)](#sendtoback) | Moves a shape,defined by ID, to the back of the z-order. |
| [setAssociatedPage()](#setassociatedpage) | The ID of the original drawing page that was marked up on separate markup overlays by reviewers of the drawing. |
| [setBackground()](#setbackground) | A flag indicating if the page is a background page. The value of the property is BOOL integer constant. |
| [setBackPage()](#setbackpage) | The page's background page. |
| [setID()](#setid) | The unique ID of the element within its parent element. |
| [setName()](#setname) | The name of the element. |
| [setNameU()](#setnameu) | The universal name of the element. |
| [setPages()](#setpages) | Page collection. |
| [setPresetTheme()](#setpresettheme) | Apply a preset theme to this page The value of the property is PresetThemeValue integer constant. |
| [setPresetThemeQuickStyle()](#setpresetthemequickstyle) | Apply a preset theme variant quickstyle to this page The value of the property is PresetQuickStyleValue integer constant |
| [setPresetThemeVariant()](#setpresetthemevariant) | Apply a preset theme variant to this page The value of the property is PresetThemeVariantValue integer constant. |
| [setReviewerID()](#setreviewerid) | The ID of the reviewer associated with the markup overlay. |
| [setViewCenterX()](#setviewcenterx) | ViewCenterX and ViewCenterY specify a center point on a page that a new view (window) assumes when it is opened initiall |
| [setViewCenterY()](#setviewcentery) | ViewCenterX and ViewCenterY specify a center point on a page that a new view (window) assumes when it is opened initiall |
| [setViewScale()](#setviewscale) | The default magnification factor to use when a new view (window) of the page is opened. For example, 1 = 100%; 1.5 = 150 |

### addActiveXControl(type, pinX, pinY, width, height) {#addactivexcontrol}

Creates an Activex Control.

| Parameter | Type | Description |
| --- | --- | --- |
| type | Number | ControlType |
| pinX | Number | Specifies the x-coordinate of the shape's pin (center of rotation) in relation to the page. |
| pinY | Number | Specifies the y-coordinate of the shape's pin (center of rotation) in relation to the page. |
| width | Number | Specifies the width of the shape in inches. |
| height | Number | Specifies the height of the shape in inches. |

**Returns:** long — `long`

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
// Instantiate Diagram Object
diagram = new aspose.diagram.Diagram();
// Insert an ActiveX control
diagram.getPages().get(0).addActiveXControl(aspose.diagram.ControlType.IMAGE, 1, 1, 1, 1);
diagram.save("out-InsertActiveXControl.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```

### addComment(shapeID, comment) {#addcomment}

Adds comment to a shape with shape's id.

| Parameter | Type | Description |
| --- | --- | --- |
| shapeID | long | The ID of shape which is adding comment. |
| comment | String | Comment's string. |

### addComment(shape, comment) {#addcomment-1}

Adds comment to a shape.

| Parameter | Type | Description |
| --- | --- | --- |
| shape | Shape | Specifies the shape which is adding comment . |
| comment | String | Comment's string. |

### addComment(pinX, pinY, comment) {#addcomment-2}

Adds comment with defined PinX and PinY.

| Parameter | Type | Description |
| --- | --- | --- |
| pinX | Number | Specifies the x-coordinate of the comment's pin (center of rotation) in relation to the page. |
| pinY | Number | Specifies the y-coordinate of the comment's pin (center of rotation) in relation to the page. |
| comment | String | Comment's string. |

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
var diagram = new aspose.diagram.Diagram("Drawing1.vsdx");
// Add comment
diagram.getPages().getPage(0).addComment(7.205905511811023, 3.880708661417323, "test@");
// Save diagram
diagram.save("out-AddPageLevelCommentInVisio.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```

### addShape(pinX, pinY, masterName, isCalculate) {#addshape}

Adds shape created by master on page with defined PinX and PinY.

| Parameter | Type | Description |
| --- | --- | --- |
| pinX | Number | Specifies the x-coordinate of the shape's pin (center of rotation) in relation to the page. |
| pinY | Number | Specifies the y-coordinate of the shape's pin (center of rotation) in relation to the page. |
| masterName | String | Master's name. |
| isCalculate | boolean | Is Calculate shape or not. |

**Returns:** long — `long` The unique ID of the shape within shapes collection on the specified page.

### addShape(pinX, pinY, width, height, masterName, isCalculate) {#addshape-1}

Adds shape created by master on page with defined PinX and PinY.

| Parameter | Type | Description |
| --- | --- | --- |
| pinX | Number | Specifies the x-coordinate of the shape's pin (center of rotation) in relation to the page. |
| pinY | Number | Specifies the y-coordinate of the shape's pin (center of rotation) in relation to the page. |
| width | Number | Specifies the width of the shape in inches. |
| height | Number | Specifies the height of the shape in inches. |
| masterName | String | Master's name. |
| isCalculate | boolean | Is Calculate shape or not. |

**Returns:** long — `long` The unique ID of the shape within shapes collection on the specified page.

### addShape(pinX, pinY, masterName) {#addshape-2}

Adds shape created by master on page with defined PinX and PinY.

| Parameter | Type | Description |
| --- | --- | --- |
| pinX | Number | Specifies the x-coordinate of the shape's pin (center of rotation) in relation to the page. |
| pinY | Number | Specifies the y-coordinate of the shape's pin (center of rotation) in relation to the page. |
| masterName | String | Master's name. |

**Returns:** long — `long` The unique ID of the shape within shapes collection on the specified page.

### addShape(pinX, pinY, width, height, masterName) {#addshape-3}

Adds shape created by master on page with defined PinX,PinY,Width and Height.

| Parameter | Type | Description |
| --- | --- | --- |
| pinX | Number | Specifies the x-coordinate of the shape's pin (center of rotation) in relation to the page. |
| pinY | Number | Specifies the y-coordinate of the shape's pin (center of rotation) in relation to the page. |
| width | Number | Specifies the width of the shape in inches. |
| height | Number | Specifies the height of the shape in inches. |
| masterName | String | Master's name. |

**Returns:** long — `long` The unique ID of the shape within shapes collection on the specified page.

### addShape(newShape, masterName) {#addshape-4}

Adds shape created by master to specific page.

| Parameter | Type | Description |
| --- | --- | --- |
| newShape | Shape | New shape object |
| masterName | String | Master's name. |

**Returns:** long — `long` The unique ID of the shape within shapes collection on the specified page.

### addText(pinX, pinY, width, height, text, fontName, fontColor, size) {#addtext}

Adds Text with defined PinX and PinY.

| Parameter | Type | Description |
| --- | --- | --- |
| pinX | Number | Specifies the x-coordinate of the text's pin (center of rotation) in relation to the page. |
| pinY | Number | Specifies the y-coordinate of the text's pin (center of rotation) in relation to the page. |
| width | Number | Specifies the width of the text. |
| height | Number | Specifies the height of the text. |
| text | String | text string. |
| fontName | String | text font name. |
| fontColor | String | text font color. |
| size | Number | text font size. |

**Returns:** Shape — `Shape` Returns a shape object that represents the new text object.

### addText(pinX, pinY, text) {#addtext-1}

Adds Text with defined PinX and PinY.

| Parameter | Type | Description |
| --- | --- | --- |
| pinX | Number | Specifies the x-coordinate of the text's pin (center of rotation) in relation to the page. |
| pinY | Number | Specifies the y-coordinate of the text's pin (center of rotation) in relation to the page. |
| text | String | text string. |

**Returns:** Shape — `Shape` Returns a shape object that represents the new text object.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram();
// set parameters
PinX = 1, PinY = 1, Width = 1, Height = 1;
text = "Test text";
// add text to a Visio page
diagram.getPages().getPage(0).addText(PinX, PinY, Width, Height, text);
diagram.save("out-InsertTextShape.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```

### applyStyle(textStyle, lineStyle, fillStyle) {#applystyle}

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

### autoSpaceShapes(shapes) {#autospaceshapes}

Auto space shapes

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | ShapeCollection | Specifies the shapes be auto spaced. |

### bringForward(shapeId) {#bringforward}

Brings a shape,defined by ID, forward one position in the z-order.

| Parameter | Type | Description |
| --- | --- | --- |
| shapeId | long | ID of shape. |

### bringToFront(shapeId) {#bringtofront}

Brings a shape,defined by ID, to the front of the z-order.

| Parameter | Type | Description |
| --- | --- | --- |
| shapeId | long | ID of shape. |

### centerDrawing() {#centerdrawing}

Centers a page's shapes with respect to the extent of the page. Centering shapes does not change their position relative to each other.

### connectShapesViaConnector(shapeFrom, placeFrom, shapeTo, placeTo, connector) {#connectshapesviaconnector}

Connect shapes via connector.

| Parameter | Type | Description |
| --- | --- | --- |
| shapeFrom | Shape | The shape where the connector begins |
| placeFrom | Number | ConnectionPointPlace |
| shapeTo | Shape | The shape where the connector ends |
| placeTo | Number | ConnectionPointPlace |
| connector | Shape | The shape with type Dynamic connector |

### connectShapesViaConnector(shapeFromId, placeFrom, shapeToId, placeTo, connectorId) {#connectshapesviaconnector-1}

Connect shapes via connector.

| Parameter | Type | Description |
| --- | --- | --- |
| shapeFromId | long | The ID of shape where the connector begins |
| placeFrom | Number | ConnectionPointPlace |
| shapeToId | long | The ID of shape where the connector ends |
| placeTo | Number | ConnectionPointPlace |
| connectorId | long | The ID of shape with type Dynamic connector |

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("AddingNewShape.vsdx");
// set sub shape ids
shapeFromId = 2;
shapeToId = 4;
// access a particular page
page = diagram.getPages().getPage("Page-3");
// initialize connector shape
shape = new aspose.diagram.Shape();
shape.getLine().getEndArrow().setValue(4);
shape.getLine().getLineWeight().setValue(0.01388);
// add shape
connecter1Id = page.addShape(shape, "Dynamic connector");
// connect sub-shapes
page.connectShapesViaConnector(
shapeFromId,
aspose.diagram.ConnectionPointPlace.RIGHT,
shapeToId,
aspose.diagram.ConnectionPointPlace.LEFT,
connecter1Id);
diagram.save("out-ConnectVisioSubShapes.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```

### connectShapesViaConnector(shapeFromId, fromConnectionName, shapeToId, toConnectionName, connectorId) {#connectshapesviaconnector-2}

Connect shapes via connector.

| Parameter | Type | Description |
| --- | --- | --- |
| shapeFromId | long | The ID of shape where the connector begins |
| fromConnectionName | String | The connection name on the first shape where connector will be connected . |
| shapeToId | long | The ID of shape where the connector ends |
| toConnectionName | String | The connection name on the second shape where connector will be connected . |
| connectorId | long | The ID of shape with type Dynamic connector |

### connectShapesViaConnectorIndex(shapeFromId, fromIndex, shapeToId, toIndex, connectorId) {#connectshapesviaconnectorindex}

Connect shapes via connector index.

| Parameter | Type | Description |
| --- | --- | --- |
| shapeFromId | long | The ID of shape where the connector begins |
| fromIndex | Number | The index of the connection on the first shape |
| shapeToId | long | The ID of shape where the connector ends |
| toIndex | Number | he index of the connection on the second shape |
| connectorId | long | The ID of shape with type Dynamic connector |

### connectShapesViaConnectorIndex(shapeFrom, fromIndex, shapeTo, toIndex, connector) {#connectshapesviaconnectorindex-1}

Connect shapes via connector index.

| Parameter | Type | Description |
| --- | --- | --- |
| shapeFrom | Shape | The shape where the connector begins |
| fromIndex | Number | The index of the connection on the first shape |
| shapeTo | Shape | The shape where the connector ends |
| toIndex | Number | he index of the connection on the second shape |
| connector | Shape | The shape with type Dynamic connector |

### constructor_overload$1() {#constructor-overload1}

Constructor.

### copy() {#copy}

### dispose() {#dispose}

Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

### drawEllipse(pinX, pinY, width, height) {#drawellipse}

The process of drawing Ellipse.

| Parameter | Type | Description |
| --- | --- | --- |
| pinX | Number | Specifies the x-coordinate of the shape's pin (center of rotation) in relation to the page. |
| pinY | Number | Specifies the y-coordinate of the shape's pin (center of rotation) in relation to the page. |
| width | Number | Specifies the width of the shape |
| height | Number | Specifies the height of the shape |

**Returns:** long — `long`

### drawLine(beginX, beginY, endX, endY) {#drawline}

The process of drawing a single line.

| Parameter | Type | Description |
| --- | --- | --- |
| beginX | Number | Specifies the begin x-coordinate of the shape's position in relation to the page. |
| beginY | Number | Specifies the begin y-coordinate of the shape's position in relation to the page. |
| endX | Number | Specifies the end x-coordinate of the shape's position in relation to the page. |
| endY | Number | Specifies the end y-coordinate of the shape's position in relation to the page. |

**Returns:** long — `long` The unique ID of the shape within shapes collection on the specified page.

### drawLine(pinX, pinY, width, height, xyArray) {#drawline-1}

The process of drawing line.

| Parameter | Type | Description |
| --- | --- | --- |
| pinX | Number | Specifies the x-coordinate of the shape's pin (center of rotation) in relation to the page. |
| pinY | Number | Specifies the y-coordinate of the shape's pin (center of rotation) in relation to the page. |
| width | Number | Specifies the width of the shape |
| height | Number | Specifies the height of the shape |
| xyArray | Array of Number | An array of alternating x and y values that defines points in the new shape |

**Returns:** long — `long` The unique ID of the shape within shapes collection on the specified page.

### drawOwal(x1, y1, x2, y2) {#drawowal}

The process of drawing owal.

| Parameter | Type | Description |
| --- | --- | --- |
| x1 | Number | Specifies the x-coordinate representing the lower-left corner of the rectangle |
| y1 | Number | Specifies the y-coordinate representing the lower-left corner of the rectangle |
| x2 | Number | Specifies the x-coordinate representing the top-right corner of the rectangle |
| y2 | Number | Specifies the y-coordinate representing the top-right corner of the rectangle |

**Returns:** long — `long` The unique ID of the shape within shapes collection on the specified page.

### drawPolyline(xyArray) {#drawpolyline}

The process of drawing Polyline.

| Parameter | Type | Description |
| --- | --- | --- |
| xyArray | Array of Number | An array of alternating x and y values that defines points in the new shape |

**Returns:** long — `long` The unique ID of the shape within shapes collection on the specified page.

### drawPolyline(pinX, pinY, width, height, xyArray) {#drawpolyline-1}

The process of drawing Polyline.

| Parameter | Type | Description |
| --- | --- | --- |
| pinX | Number | Specifies the x-coordinate of the shape's pin (center of rotation) in relation to the page. |
| pinY | Number | Specifies the y-coordinate of the shape's pin (center of rotation) in relation to the page. |
| width | Number | Specifies the width of the shape |
| height | Number | Specifies the height of the shape |
| xyArray | Array of Number | An array of alternating x and y values that defines points in the new shape |

**Returns:** long — `long` The unique ID of the shape within shapes collection on the specified page.

### drawRectangle(pinX, pinY, width, height) {#drawrectangle}

The process of drawing rectangle.

| Parameter | Type | Description |
| --- | --- | --- |
| pinX | Number | Specifies the x-coordinate of the shape's pin (center of rotation) in relation to the page. |
| pinY | Number | Specifies the y-coordinate of the shape's pin (center of rotation) in relation to the page. |
| width | Number | Specifies the width of the shape |
| height | Number | Specifies the height of the shape |

**Returns:** long — `long` The unique ID of the shape within shapes collection on the specified page.

### drawRectangle(x1, y1, x2, y2) {#drawrectangle-1}

The process of drawing rectangle.

| Parameter | Type | Description |
| --- | --- | --- |
| x1 | Number | Specifies the x-coordinate representing the lower-left corner of the rectangle |
| y1 | Number | Specifies the y-coordinate representing the lower-left corner of the rectangle |
| x2 | Number | Specifies the x-coordinate representing the top-right corner of the rectangle |
| y2 | Number | Specifies the y-coordinate representing the top-right corner of the rectangle |

**Returns:** long — `long` The unique ID of the shape within shapes collection on the specified page.

### dropContainer(targetShape) {#dropcontainer}

The process of creating Container.

| Parameter | Type | Description |
| --- | --- | --- |
| targetShape | Shape | target shape |

**Returns:** Shape — `Shape` The shape within shapes collection on the specified page.

### getAssociatedPage() {#getassociatedpage}

The ID of the original drawing page that was marked up on separate markup overlays by reviewers of the drawing.

### getBackground() {#getbackground}

A flag indicating if the page is a background page. The value of the property is BOOL integer constant.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("RetrievePageInfo.vdx");
for (var it = diagram.getPages().iterator(); it.hasNext();) {
page = it.next();
// Checks if current page is a background page
if (page.getBackground() == aspose.diagram.BOOL.TRUE) {
// Display information about the background page
console.log("Background Page ID : " + page.getID());
console.log("Background Page Name : " + page.getName());
} else {
// Display information about the foreground page
console.log("\nPage ID : " + page.getID());
console.log("Universal Name : " + page.getNameU());
console.log("ID of the Background Page : " + page.getBackPage());
}
}
```

### getBackPage() {#getbackpage}

The page's background page.

### getConnects() {#getconnects}

Contains a Connect element for each connection between two shapes in a drawing.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("RetrieveConnectorInfo.vsd");
connects = diagram.getPages().getPage(0).getConnects();
for (var it = connects.iterator(); it.hasNext();) {
connector = it.next();
// Display information about the Connectors
console.log("From Shape ID : " + connector.getFromSheet());
console.log("To Shape ID : " + connector.getToSheet());
}
```

### getID() {#getid}

The unique ID of the element within its parent element.

### getName() {#getname}

The name of the element.

### getNameU() {#getnameu}

The universal name of the element.

### getPages() {#getpages}

Page collection.

### getPageSheet() {#getpagesheet}

Contains elements that define the page sheet for a Page or Master element.

### getReviewerID() {#getreviewerid}

The ID of the reviewer associated with the markup overlay.

### getShapes() {#getshapes}

Shape collection.

### getViewCenterX() {#getviewcenterx}

ViewCenterX and ViewCenterY specify a center point on a page that a new view (window) assumes when it is opened initially.

### getViewCenterY() {#getviewcentery}

ViewCenterX and ViewCenterY specify a center point on a page that a new view (window) assumes when it is opened initially.

### getViewScale() {#getviewscale}

The default magnification factor to use when a new view (window) of the page is opened. For example, 1 = 100%; 1.5 = 150%, and so on.

### glueShapes(shapeFrom, placeTo, shapeTo) {#glueshapes}

Glue shapes.

| Parameter | Type | Description |
| --- | --- | --- |
| shapeFrom | Shape | The shape which is glue from |
| placeTo | Number | ConnectionPointPlace |
| shapeTo | Shape | The shape where to glue to |

### glueShapes(shapeFromId, placeTo, shapeToId) {#glueshapes-1}

Glue shapes

| Parameter | Type | Description |
| --- | --- | --- |
| shapeFromId | long | The ID of shape which is glue from |
| placeTo | Number | ConnectionPointPlace |
| shapeToId | long | The ID of shape where to glue to |

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("GlueVisioShapes.vsdx");
// Get a particular page
page = diagram.getPages().getPage("Page-1");
// set shape id
shape1_ID = 7;
shape2_ID = 494;
// Glue shapes
page.glueShapes(shape1_ID, aspose.diagram.ConnectionPointPlace.CENTER, shape2_ID);
diagram.save("out-GlueVisioShapes.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```

### glueShapesInContainer(shapeFromId, shapeToBeginConnectionName, shapeToEndConnectionName, shapeToId) {#glueshapesincontainer}

Glue shapes in container using connection name

| Parameter | Type | Description |
| --- | --- | --- |
| shapeFromId | long | The ID of shape which is glue from |
| shapeToBeginConnectionName | String | The location on the first connection name where to glue . |
| shapeToEndConnectionName | String | The location on the end connection name where to glue . |
| shapeToId | long | The ID of shape where to glue to |

### glueShapesInContainer(shapeFromId, shapeToBeginConnectionIndex, shapeToEndConnectionIndex, shapeToId) {#glueshapesincontainer-1}

Glue shapes in container

| Parameter | Type | Description |
| --- | --- | --- |
| shapeFromId | long | The ID of shape which is glue from |
| shapeToBeginConnectionIndex | Number | The location on the first connection index where to glue . |
| shapeToEndConnectionIndex | Number | The location on the end connection index where to glue . |
| shapeToId | long | The ID of shape where to glue to |

### glueShapesInContainerByID(shapeFromId, shapeToBeginConnectionID, shapeToEndConnectionID, shapeToId) {#glueshapesincontainerbyid}

Glue shapes by connection id in container

| Parameter | Type | Description |
| --- | --- | --- |
| shapeFromId | long | The ID of shape which is glue from |
| shapeToBeginConnectionID | Number | The location on the first connection id where to glue . |
| shapeToEndConnectionID | Number | The location on the end connection id where to glue . |
| shapeToId | long | The ID of shape where to glue to |

### glueShapeToConnectorBeginX(shapeFromId, connectionName, connectorId) {#glueshapetoconnectorbeginx}

Glue shape to Connector's BeginX

| Parameter | Type | Description |
| --- | --- | --- |
| shapeFromId | long | The ID of shape where the connector begins |
| connectionName | String | The connection name on the shape where connector will be connected . |
| connectorId | long | The ID of shape with type Dynamic connector |

### glueShapeToConnectorEndX(shapeToId, connectionName, connectorId) {#glueshapetoconnectorendx}

Glue shape to Connector's EndX

| Parameter | Type | Description |
| --- | --- | --- |
| shapeToId | long | The ID of shape where the connector ends |
| connectionName | String | The connection name on the second shape where connector will be connected . |
| connectorId | long | The ID of shape with type Dynamic connector |

### layout(options) {#layout}

Lays out the shapes and/or reroutes the connectors for the page.

| Parameter | Type | Description |
| --- | --- | --- |
| options | LayoutOptions | Using the |

### moveTo(index) {#moveto}

Moves the page to another location in the pages.

| Parameter | Type | Description |
| --- | --- | --- |
| index | Number | Destination page index. |

### sendBackward(shapeId) {#sendbackward}

Moves a shape,defined by ID, back one position in the z-order.

| Parameter | Type | Description |
| --- | --- | --- |
| shapeId | long | ID of shape. |

### sendToBack(shapeId) {#sendtoback}

Moves a shape,defined by ID, to the back of the z-order.

| Parameter | Type | Description |
| --- | --- | --- |
| shapeId | long | ID of shape. |

### setAssociatedPage() {#setassociatedpage}

The ID of the original drawing page that was marked up on separate markup overlays by reviewers of the drawing.

### setBackground() {#setbackground}

A flag indicating if the page is a background page. The value of the property is BOOL integer constant.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("RetrievePageInfo.vdx");
for (var it = diagram.getPages().iterator(); it.hasNext();) {
page = it.next();
// Checks if current page is a background page
if (page.getBackground() == aspose.diagram.BOOL.TRUE) {
// Display information about the background page
console.log("Background Page ID : " + page.getID());
console.log("Background Page Name : " + page.getName());
} else {
// Display information about the foreground page
console.log("\nPage ID : " + page.getID());
console.log("Universal Name : " + page.getNameU());
console.log("ID of the Background Page : " + page.getBackPage());
}
}
```

### setBackPage() {#setbackpage}

The page's background page.

### setID() {#setid}

The unique ID of the element within its parent element.

### setName() {#setname}

The name of the element.

### setNameU() {#setnameu}

The universal name of the element.

### setPages() {#setpages}

Page collection.

### setPresetTheme() {#setpresettheme}

Apply a preset theme to this page The value of the property is PresetThemeValue integer constant.

### setPresetThemeQuickStyle() {#setpresetthemequickstyle}

Apply a preset theme variant quickstyle to this page The value of the property is PresetQuickStyleValue integer constant.

### setPresetThemeVariant() {#setpresetthemevariant}

Apply a preset theme variant to this page The value of the property is PresetThemeVariantValue integer constant.

### setReviewerID() {#setreviewerid}

The ID of the reviewer associated with the markup overlay.

### setViewCenterX() {#setviewcenterx}

ViewCenterX and ViewCenterY specify a center point on a page that a new view (window) assumes when it is opened initially.

### setViewCenterY() {#setviewcentery}

ViewCenterX and ViewCenterY specify a center point on a page that a new view (window) assumes when it is opened initially.

### setViewScale() {#setviewscale}

The default magnification factor to use when a new view (window) of the page is opened. For example, 1 = 100%; 1.5 = 150%, and so on.
