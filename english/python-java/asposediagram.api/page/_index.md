---
title: "Page"
linktitle: "Page"
second_title: "Aspose.Diagram for Python via Java API Reference"
description: "Contains elements that define a page in the document."
type: docs
weight: 2240
url: /python-java/asposediagram.api/page/
---

## Page class

Contains elements that define a page in the document.

## Constructors

| Name | Description |
| --- | --- |
| [Page](#constructor) | Constructor. |
| [Page](#constructor) | Constructor. |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [Pages](#pages) | PageCollection | Page collection. |
| [Shapes](#shapes) | ShapeCollection | Shape collection. |
| [PageSheet](#pagesheet) | PageSheet | Contains elements that define the page sheet for a Page or Master element. |
| [Connects](#connects) | ConnectCollection | Contains a Connect element for each connection between two shapes in a drawing. |
| [ID](#id) | int | The unique ID of the element within its parent element. |
| [Name](#name) | String | The name of the element. |
| [NameU](#nameu) | String | The universal name of the element. |
| [Background](#background) | int | A flag indicating if the page is a background page. The value of the property is BOOL integer constant. |
| [BackPage](#backpage) | Page | The page's background page. |
| [ViewScale](#viewscale) | float | The default magnification factor to use when a new view (window) of the page is opened. For example, 1 = 100%; 1.5 = 150 |
| [ViewCenterX](#viewcenterx) | float | ViewCenterX and ViewCenterY specify a center point on a page that a new view (window) assumes when it is opened initiall |
| [ViewCenterY](#viewcentery) | float | ViewCenterX and ViewCenterY specify a center point on a page that a new view (window) assumes when it is opened initiall |
| [ReviewerID](#reviewerid) | int | The ID of the reviewer associated with the markup overlay. |
| [AssociatedPage](#associatedpage) | Page | The ID of the original drawing page that was marked up on separate markup overlays by reviewers of the drawing. |
| [PresetTheme](#presettheme) | int | Apply a preset theme to this page The value of the property is PresetThemeValue integer constant. |
| [PresetThemeVariant](#presetthemevariant) | int | Apply a preset theme variant to this page The value of the property is PresetThemeVariantValue integer constant. |
| [PresetThemeQuickStyle](#presetthemequickstyle) | int | Apply a preset theme variant quickstyle to this page The value of the property is PresetQuickStyleValue integer constant |

## Methods

| Name | Description |
| --- | --- |
| [centerDrawing](#centerdrawing) | Centers a page's shapes with respect to the extent of the page. Centering shapes does not change their position relative |
| [copy](#copy) |  |
| [dispose](#dispose) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [applyStyle](#applystyle) | Applies style for full page.

Default value is -1. |
| [moveTo](#moveto) | Moves the page to another location in the pages. |
| [addShape](#addshape) | Adds shape created by master on page with defined PinX and PinY. |
| [connectShapesViaConnector](#connectshapesviaconnector) | Connect shapes via connector. |
| [glueShapeToConnectorBeginX](#glueshapetoconnectorbeginx) | Glue shape to Connector's BeginX |
| [glueShapeToConnectorEndX](#glueshapetoconnectorendx) | Glue shape to Connector's EndX |
| [connectShapesViaConnectorIndex](#connectshapesviaconnectorindex) | Connect shapes via connector index. |
| [glueShapesInContainerByID](#glueshapesincontainerbyid) | Glue shapes by connection id in container |
| [glueShapesInContainer](#glueshapesincontainer) | Glue shapes in container using connection name |
| [bringForward](#bringforward) | Brings a shape,defined by ID, forward one position in the z-order. |
| [sendBackward](#sendbackward) | Moves a shape,defined by ID, back one position in the z-order. |
| [bringToFront](#bringtofront) | Brings a shape,defined by ID, to the front of the z-order. |
| [sendToBack](#sendtoback) | Moves a shape,defined by ID, to the back of the z-order. |
| [addComment](#addcomment) | Adds comment to a shape with shape's id. |
| [autoSpaceShapes](#autospaceshapes) | Auto space shapes |
| [addText](#addtext) | Adds Text with defined PinX and PinY. |
| [drawLine](#drawline) | The process of drawing a single line. |
| [drawRectangle](#drawrectangle) | The process of drawing rectangle. |
| [drawEllipse](#drawellipse) | The process of drawing Ellipse. |
| [drawOwal](#drawowal) | The process of drawing owal. |
| [dropContainer](#dropcontainer) | The process of creating Container. |
| [drawPolyline](#drawpolyline) | The process of drawing Polyline. |

### Page() (1 of 2) {#constructor}

Constructor.

---

### Page(ID) (2 of 2) {#constructor-1}

Constructor.

### Page.Pages property {#pages}

Page collection.

**Type:** PageCollection

### Page.Shapes property {#shapes}

Shape collection.

**Type:** ShapeCollection

### Page.PageSheet property {#pagesheet}

Contains elements that define the page sheet for a Page or Master element.

**Type:** PageSheet

### Page.Connects property {#connects}

Contains a Connect element for each connection between two shapes in a drawing.

**Type:** ConnectCollection

### Page.ID property {#id}

The unique ID of the element within its parent element.

**Type:** int

### Page.Name property {#name}

The name of the element.

**Type:** String

### Page.NameU property {#nameu}

The universal name of the element.

**Type:** String

### Page.Background property {#background}

A flag indicating if the page is a background page. The value of the property is BOOL integer constant.

**Type:** int

### Page.BackPage property {#backpage}

The page's background page.

**Type:** Page

### Page.ViewScale property {#viewscale}

The default magnification factor to use when a new view (window) of the page is opened. For example, 1 = 100%; 1.5 = 150%, and so on.

**Type:** float

### Page.ViewCenterX property {#viewcenterx}

ViewCenterX and ViewCenterY specify a center point on a page that a new view (window) assumes when it is opened initially.

**Type:** float

### Page.ViewCenterY property {#viewcentery}

ViewCenterX and ViewCenterY specify a center point on a page that a new view (window) assumes when it is opened initially.

**Type:** float

### Page.ReviewerID property {#reviewerid}

The ID of the reviewer associated with the markup overlay.

**Type:** int

### Page.AssociatedPage property {#associatedpage}

The ID of the original drawing page that was marked up on separate markup overlays by reviewers of the drawing.

**Type:** Page

### Page.PresetTheme property {#presettheme}

Apply a preset theme to this page The value of the property is PresetThemeValue integer constant.

**Type:** int

### Page.PresetThemeVariant property {#presetthemevariant}

Apply a preset theme variant to this page The value of the property is PresetThemeVariantValue integer constant.

**Type:** int

### Page.PresetThemeQuickStyle property {#presetthemequickstyle}

Apply a preset theme variant quickstyle to this page The value of the property is PresetQuickStyleValue integer constant.

**Type:** int

### centerDrawing() {#centerdrawing}

Centers a page's shapes with respect to the extent of the page. Centering shapes does not change their position relative to each other.

### copy(source) {#copy}

### dispose() {#dispose}

Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

### applyStyle(textStyle, lineStyle, fillStyle) {#applystyle}

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

### moveTo(index) {#moveto}

Moves the page to another location in the pages.

| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Destination page index. |

### addShape(pinX, pinY, masterName, isCalculate) (1 of 5) {#addshape}

Adds shape created by master on page with defined PinX and PinY.

| Parameter | Type | Description |
| --- | --- | --- |
| pinX | float | Specifies the x-coordinate of the shape's pin (center of rotation) in relation to the page. |
| pinY | float | Specifies the y-coordinate of the shape's pin (center of rotation) in relation to the page. |
| masterName | String | Master's name. |
| isCalculate | boolean | Is Calculate shape or not. |

**Returns:** The unique ID of the shape within shapes collection on the specified page.

---

### addShape(pinX, pinY, width, height, masterName, isCalculate) (2 of 5) {#addshape-1}

Adds shape created by master on page with defined PinX and PinY.

| Parameter | Type | Description |
| --- | --- | --- |
| pinX | float | Specifies the x-coordinate of the shape's pin (center of rotation) in relation to the page. |
| pinY | float | Specifies the y-coordinate of the shape's pin (center of rotation) in relation to the page. |
| width | float | Specifies the width of the shape in inches. |
| height | float | Specifies the height of the shape in inches. |
| masterName | String | Master's name. |
| isCalculate | boolean | Is Calculate shape or not. |

**Returns:** The unique ID of the shape within shapes collection on the specified page.

---

### addShape(pinX, pinY, masterName) (3 of 5) {#addshape-2}

Adds shape created by master on page with defined PinX and PinY.

| Parameter | Type | Description |
| --- | --- | --- |
| pinX | float | Specifies the x-coordinate of the shape's pin (center of rotation) in relation to the page. |
| pinY | float | Specifies the y-coordinate of the shape's pin (center of rotation) in relation to the page. |
| masterName | String | Master's name. |

**Returns:** The unique ID of the shape within shapes collection on the specified page.

---

### addShape(pinX, pinY, width, height, masterName) (4 of 5) {#addshape-3}

Adds shape created by master on page with defined PinX,PinY,Width and Height.

| Parameter | Type | Description |
| --- | --- | --- |
| pinX | float | Specifies the x-coordinate of the shape's pin (center of rotation) in relation to the page. |
| pinY | float | Specifies the y-coordinate of the shape's pin (center of rotation) in relation to the page. |
| width | float | Specifies the width of the shape in inches. |
| height | float | Specifies the height of the shape in inches. |
| masterName | String | Master's name. |

**Returns:** The unique ID of the shape within shapes collection on the specified page.

---

### addShape(newShape, masterName) (5 of 5) {#addshape-4}

Adds shape created by master to specific page.

| Parameter | Type | Description |
| --- | --- | --- |
| newShape | Shape | New shape object Shape . |
| masterName | String | Master's name. |

**Returns:** The unique ID of the shape within shapes collection on the specified page.

### connectShapesViaConnector(shapeFromId, fromConnectionName, shapeToId, toConnectionName, connectorId) {#connectshapesviaconnector}

Connect shapes via connector.

| Parameter | Type | Description |
| --- | --- | --- |
| shapeFromId | long | The ID of shape where the connector begins Shape . |
| fromConnectionName | String | The connection name on the first shape where connector will be connected . |
| shapeToId | long | The ID of shape where the connector ends Shape . |
| toConnectionName | String | The connection name on the second shape where connector will be connected . |
| connectorId | long | The ID of shape with type Dynamic connector Shape . |

### glueShapeToConnectorBeginX(shapeFromId, connectionName, connectorId) {#glueshapetoconnectorbeginx}

Glue shape to Connector's BeginX

| Parameter | Type | Description |
| --- | --- | --- |
| shapeFromId | long | The ID of shape where the connector begins Shape . |
| connectionName | String | The connection name on the shape where connector will be connected . |
| connectorId | long | The ID of shape with type Dynamic connector Shape . |

### glueShapeToConnectorEndX(shapeToId, connectionName, connectorId) {#glueshapetoconnectorendx}

Glue shape to Connector's EndX

| Parameter | Type | Description |
| --- | --- | --- |
| shapeToId | long | The ID of shape where the connector ends Shape . |
| connectionName | String | The connection name on the second shape where connector will be connected . |
| connectorId | long | The ID of shape with type Dynamic connector Shape . |

### connectShapesViaConnectorIndex(shapeFromId, fromIndex, shapeToId, toIndex, connectorId) (1 of 2) {#connectshapesviaconnectorindex}

Connect shapes via connector index.

| Parameter | Type | Description |
| --- | --- | --- |
| shapeFromId | long | The ID of shape where the connector begins Shape . |
| fromIndex | int | The index of the connection on the first shape |
| shapeToId | long | The ID of shape where the connector ends Shape . |
| toIndex | int | he index of the connection on the second shape |
| connectorId | long | The ID of shape with type Dynamic connector Shape . |

---

### connectShapesViaConnectorIndex(shapeFrom, fromIndex, shapeTo, toIndex, connector) (2 of 2) {#connectshapesviaconnectorindex-1}

Connect shapes via connector index.

| Parameter | Type | Description |
| --- | --- | --- |
| shapeFrom | Shape | The shape where the connector begins Shape . |
| fromIndex | int | The index of the connection on the first shape |
| shapeTo | Shape | The shape where the connector ends Shape . |
| toIndex | int | he index of the connection on the second shape |
| connector | Shape | The shape with type Dynamic connector Shape . |

### glueShapesInContainerByID(shapeFromId, shapeToBeginConnectionID, shapeToEndConnectionID, shapeToId) {#glueshapesincontainerbyid}

Glue shapes by connection id in container

| Parameter | Type | Description |
| --- | --- | --- |
| shapeFromId | long | The ID of shape which is glue from Shape . |
| shapeToBeginConnectionID | int | The location on the first connection id where to glue . |
| shapeToEndConnectionID | int | The location on the end connection id where to glue . |
| shapeToId | long | The ID of shape where to glue to Shape . |

### glueShapesInContainer(shapeFromId, shapeToBeginConnectionName, shapeToEndConnectionName, shapeToId) (1 of 2) {#glueshapesincontainer}

Glue shapes in container using connection name

| Parameter | Type | Description |
| --- | --- | --- |
| shapeFromId | long | The ID of shape which is glue from Shape . |
| shapeToBeginConnectionName | String | The location on the first connection name where to glue . |
| shapeToEndConnectionName | String | The location on the end connection name where to glue . |
| shapeToId | long | The ID of shape where to glue to Shape . |

---

### glueShapesInContainer(shapeFromId, shapeToBeginConnectionIndex, shapeToEndConnectionIndex, shapeToId) (2 of 2) {#glueshapesincontainer-1}

Glue shapes in container

| Parameter | Type | Description |
| --- | --- | --- |
| shapeFromId | long | The ID of shape which is glue from Shape . |
| shapeToBeginConnectionIndex | int | The location on the first connection index where to glue . |
| shapeToEndConnectionIndex | int | The location on the end connection index where to glue . |
| shapeToId | long | The ID of shape where to glue to Shape . |

### bringForward(shapeId) {#bringforward}

Brings a shape,defined by ID, forward one position in the z-order.

| Parameter | Type | Description |
| --- | --- | --- |
| shapeId | long | ID of shape. long |

### sendBackward(shapeId) {#sendbackward}

Moves a shape,defined by ID, back one position in the z-order.

| Parameter | Type | Description |
| --- | --- | --- |
| shapeId | long | ID of shape. long |

### bringToFront(shapeId) {#bringtofront}

Brings a shape,defined by ID, to the front of the z-order.

| Parameter | Type | Description |
| --- | --- | --- |
| shapeId | long | ID of shape. long |

### sendToBack(shapeId) {#sendtoback}

Moves a shape,defined by ID, to the back of the z-order.

| Parameter | Type | Description |
| --- | --- | --- |
| shapeId | long | ID of shape. long |

### addComment(shapeID, comment) (1 of 3) {#addcomment}

Adds comment to a shape with shape's id.

| Parameter | Type | Description |
| --- | --- | --- |
| shapeID | long | The ID of shape which is adding comment. |
| comment | String | Comment's string. |

---

### addComment(shape, comment) (2 of 3) {#addcomment-1}

Adds comment to a shape.

| Parameter | Type | Description |
| --- | --- | --- |
| shape | Shape | Specifies the shape which is adding comment . |
| comment | String | Comment's string. |

---

### addComment(pinX, pinY, comment) (3 of 3) {#addcomment-2}

Adds comment with defined PinX and PinY.

| Parameter | Type | Description |
| --- | --- | --- |
| pinX | float | Specifies the x-coordinate of the comment's pin (center of rotation) in relation to the page. |
| pinY | float | Specifies the y-coordinate of the comment's pin (center of rotation) in relation to the page. |
| comment | String | Comment's string. |

**Example:**

```python
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");

var diagram = new aspose.diagram.Diagram("Drawing1.vsdx");
// Add comment
diagram.getPages().getPage(0).addComment(7.205905511811023, 3.880708661417323, "test@");
// Save diagram
diagram.save("out-AddPageLevelCommentInVisio.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```

### autoSpaceShapes(shapes, options) {#autospaceshapes}

Auto space shapes

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | ShapeCollection | Specifies the shapes be auto spaced. |

### addText(pinX, pinY, width, height, text, fontName, fontColor, size) (1 of 2) {#addtext}

Adds Text with defined PinX and PinY.

| Parameter | Type | Description |
| --- | --- | --- |
| pinX | float | Specifies the x-coordinate of the text's pin (center of rotation) in relation to the page. |
| pinY | float | Specifies the y-coordinate of the text's pin (center of rotation) in relation to the page. |
| width | float | Specifies the width of the text. |
| height | float | Specifies the height of the text. |
| text | String | text string. |
| fontName | String | text font name. |
| fontColor | String | text font color. |
| size | float | text font size. |

**Returns:** Returns a shape object that represents the new text object.

---

### addText(pinX, pinY, width, height, text) (2 of 2) {#addtext-1}

Adds Text with defined PinX and PinY.

| Parameter | Type | Description |
| --- | --- | --- |
| pinX | float | Specifies the x-coordinate of the text's pin (center of rotation) in relation to the page. |
| pinY | float | Specifies the y-coordinate of the text's pin (center of rotation) in relation to the page. |
| text | String | text string. |

**Returns:** Returns a shape object that represents the new text object.

**Example:**

```python
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

### drawLine(beginX, beginY, endX, endY) (1 of 2) {#drawline}

The process of drawing a single line.

| Parameter | Type | Description |
| --- | --- | --- |
| beginX | float | Specifies the begin x-coordinate of the shape's position in relation to the page. |
| beginY | float | Specifies the begin y-coordinate of the shape's position in relation to the page. |
| endX | float | Specifies the end x-coordinate of the shape's position in relation to the page. |
| endY | float | Specifies the end y-coordinate of the shape's position in relation to the page. |

**Returns:** The unique ID of the shape within shapes collection on the specified page.

---

### drawLine(pinX, pinY, width, height, xyArray) (2 of 2) {#drawline-1}

The process of drawing line.

| Parameter | Type | Description |
| --- | --- | --- |
| pinX | float | Specifies the x-coordinate of the shape's pin (center of rotation) in relation to the page. |
| pinY | float | Specifies the y-coordinate of the shape's pin (center of rotation) in relation to the page. |
| width | float | Specifies the width of the shape |
| height | float | Specifies the height of the shape |
| xyArray | Number Array | An array of alternating x and y values that defines points in the new shape |

**Returns:** The unique ID of the shape within shapes collection on the specified page.

### drawRectangle(pinX, pinY, width, height) (1 of 2) {#drawrectangle}

The process of drawing rectangle.

| Parameter | Type | Description |
| --- | --- | --- |
| pinX | float | Specifies the x-coordinate of the shape's pin (center of rotation) in relation to the page. |
| pinY | float | Specifies the y-coordinate of the shape's pin (center of rotation) in relation to the page. |
| width | float | Specifies the width of the shape |
| height | float | Specifies the height of the shape |

**Returns:** The unique ID of the shape within shapes collection on the specified page.

---

### drawRectangle(x1, y1, x2, y2) (2 of 2) {#drawrectangle-1}

The process of drawing rectangle.

| Parameter | Type | Description |
| --- | --- | --- |
| x1 | float | Specifies the x-coordinate representing the lower-left corner of the rectangle |
| y1 | float | Specifies the y-coordinate representing the lower-left corner of the rectangle |
| x2 | float | Specifies the x-coordinate representing the top-right corner of the rectangle |
| y2 | float | Specifies the y-coordinate representing the top-right corner of the rectangle |

**Returns:** The unique ID of the shape within shapes collection on the specified page.

### drawEllipse(pinX, pinY, width, height) {#drawellipse}

The process of drawing Ellipse.

| Parameter | Type | Description |
| --- | --- | --- |
| pinX | float | Specifies the x-coordinate of the shape's pin (center of rotation) in relation to the page. |
| pinY | float | Specifies the y-coordinate of the shape's pin (center of rotation) in relation to the page. |
| width | float | Specifies the width of the shape |
| height | float | Specifies the height of the shape |

### drawOwal(x1, y1, x2, y2) {#drawowal}

The process of drawing owal.

| Parameter | Type | Description |
| --- | --- | --- |
| x1 | float | Specifies the x-coordinate representing the lower-left corner of the rectangle |
| y1 | float | Specifies the y-coordinate representing the lower-left corner of the rectangle |
| x2 | float | Specifies the x-coordinate representing the top-right corner of the rectangle |
| y2 | float | Specifies the y-coordinate representing the top-right corner of the rectangle |

**Returns:** The unique ID of the shape within shapes collection on the specified page.

### dropContainer(targetShape) {#dropcontainer}

The process of creating Container.

| Parameter | Type | Description |
| --- | --- | --- |
| targetShape | Shape | target shape |

**Returns:** The shape within shapes collection on the specified page.

### drawPolyline(xyArray) (1 of 2) {#drawpolyline}

The process of drawing Polyline.

| Parameter | Type | Description |
| --- | --- | --- |
| xyArray | Number Array | An array of alternating x and y values that defines points in the new shape |

**Returns:** The unique ID of the shape within shapes collection on the specified page.

---

### drawPolyline(pinX, pinY, width, height, xyArray) (2 of 2) {#drawpolyline-1}

The process of drawing Polyline.

| Parameter | Type | Description |
| --- | --- | --- |
| pinX | float | Specifies the x-coordinate of the shape's pin (center of rotation) in relation to the page. |
| pinY | float | Specifies the y-coordinate of the shape's pin (center of rotation) in relation to the page. |
| width | float | Specifies the width of the shape |
| height | float | Specifies the height of the shape |
| xyArray | Number Array | An array of alternating x and y values that defines points in the new shape |

**Returns:** The unique ID of the shape within shapes collection on the specified page.
