---
title: "Shape"
linktitle: "Shape"
second_title: "Aspose.Diagram for Node.js via Java API Reference"
description: "Contains elements that define a shape in a Master, Page, or group shape element."
type: docs
weight: 2300
url: /nodejs/aspose.diagram/shape/
---

## Shape class

Contains elements that define a shape in a Master, Page, or group shape element.

```js
new Shape()
```

Constructor.

## Methods

| Name | Description |
| --- | --- |
| [toImageStream(shape, stream, options)](#toimagestream) *(static)* | Creates the shape image and saves it to a stream in the specified format. |
| [toPdfStream(shape, stream)](#topdfstream) *(static)* | Creates the shape pdf and saves it to a stream. |
| [bringForward()](#bringforward) | Brings the shape forward one position in the z-order. |
| [bringToFront()](#bringtofront) | Brings the shape to the front of the z-order. |
| [centerDrawing()](#centerdrawing) | Center the shape with respect to the extent of the page |
| [connectedShapes(flag, categoryFilter)](#connectedshapes) | Returns an array that contains the identifiers (IDs) of the shapes that are connected to the shape. |
| [convertToGroup()](#converttogroup) | Converts a selection or an object from another application (a linked or embedded object) to a group. |
| [copy(source)](#copy) |  |
| [dependsOnShapes()](#dependsonshapes) | Returns an array that contains the identifiers of the shapes that are depends on a shape. |
| [getActiveXControl()](#getactivexcontrol) | Gets the ActiveX control. |
| [getActs()](#getacts) | Contains a collection of Act elements. |
| [getAlign()](#getalign) | Indicates the alignment of a shape with respect to the guide or guide point to which the shape is glued. The Align eleme |
| [getChars()](#getchars) | Contains a collection of Char elements. |
| [getClippingPath()](#getclippingpath) | Contains Clipping Path string value. |
| [getConnectionABCDs()](#getconnectionabcds) | Contains a collection of ConnectionABCD elements. |
| [getConnections()](#getconnections) | Contains a collection of Connection elements. |
| [getConnectorRule()](#getconnectorrule) | Returns a connectorRule that contains the shape id and connecton that are connected to the shape. |
| [getConnectorsType()](#getconnectorstype) | Get Connectors type |
| [getContainerProperties()](#getcontainerproperties) | Contains shape's ContainerProperties. |
| [getControlData()](#getcontroldata) | Gets the data of control. |
| [getControls()](#getcontrols) | Contains a collection of Control elements. |
| [getData1()](#getdata1) | Contains an arbitrary string value that is used to supply additional information about a shape. |
| [getData2()](#getdata2) | Contains an arbitrary string value that is used to supply additional information about a shape. |
| [getData3()](#getdata3) | Contains an arbitrary string value that is used to supply additional information about a shape. |
| [getDel()](#getdel) | A flag indicating whether the element is deleted locally. A value of 1 indicates that the element is deleted locally. Th |
| [getDiagram()](#getdiagram) | Root element of Visio objects hierarchy. |
| [getDisplayText()](#getdisplaytext) | Get the text displayed on the interface |
| [getEvent()](#getevent) | Contains elements that specify formulas that control shape events. |
| [getFields()](#getfields) | Contains a collection of Field elements. |
| [getFill()](#getfill) | Contains the current fill formatting values for the shape and the shape's drop shadow, including pattern, foreground col |
| [getFillStyle()](#getfillstyle) | StyleSheet from which this shape inherits fill formatting. |
| [getForeign()](#getforeign) | Contains elements specifying the width and height of an object from another program used in a Microsoft Visio document.  |
| [getForeignData()](#getforeigndata) | Contains a MIME (Multipurpose Internet Mail Extensions) encoded BLOB of picture data, such as Windows metafile, bitmap,  |
| [getGeoms()](#getgeoms) | Contains a collection of Geom elements. |
| [getGroup()](#getgroup) | Contains elements that control how you add shapes to a group, move members of a group, and select groups. |
| [getHelp()](#gethelp) | Contains elements specifying the Shape element's Help file topic and copyright information. |
| [getHyperlinks()](#gethyperlinks) | Contains a collection of Hyperlink elements. |
| [getID()](#getid) | The unique ID of the element within its parent element. |
| [getImage()](#getimage) | Contains the gamma, brightness, contrast, blur, sharpen, denoise, and transparency values for a bitmap. |
| [getInheritActs()](#getinheritacts) | Contains the actions for the shape inherit by the master shape. |
| [getInheritChars()](#getinheritchars) | Contains the char values for the shape inherit by the master shape. |
| [getInheritConnections()](#getinheritconnections) | Contains the connections for the shape inherit by the master shape. |
| [getInheritControls()](#getinheritcontrols) | Contains the controls for the shape inherit by the master shape. |
| [getInheritEvent()](#getinheritevent) | Contains the Event for the shape inherit by the master shape. |
| [getInheritFields()](#getinheritfields) | Contains the fields for the shape inherit by the master shape. |
| [getInheritFill()](#getinheritfill) | Contains the fill formatting values for the shape inherit by the parent style and the master shape. |
| [getInheritGeoms()](#getinheritgeoms) | Contains the Geoms values for the shape inherit by the master shape. |
| [getInheritGroup()](#getinheritgroup) |  |
| [getInheritHelp()](#getinherithelp) | Contains the Help for the shape inherit by the master shape. |
| [getInheritHyperlinks()](#getinherithyperlinks) | Contains the Hyperlinks for the shape inherit by the master shape. |
| [getInheritLayerMem()](#getinheritlayermem) | Contains the LayerMem for the shape inherit by the master shape. |
| [getInheritLayout()](#getinheritlayout) | Contains the Layout for the shape inherit by the master shape. |
| [getInheritLine()](#getinheritline) | Contains the line formatting values for the shape inherit by the parent style and the master shape. |
| [getInheritMisc()](#getinheritmisc) | Contains the Misc for the shape inherit by the master shape. |
| [getInheritParas()](#getinheritparas) | Contains the paras for the shape inherit by the parent style and the master shape. |
| [getInheritProps()](#getinheritprops) | Contains the props for the shape inherit by the master shape. |
| [getInheritProtection()](#getinheritprotection) | Contains the Protection for the shape inherit by the master shape. |
| [getInheritScratchs()](#getinheritscratchs) | Contains the scratchs for the shape inherit by the master shape. |
| [getInheritTabs()](#getinherittabs) | Contains the tabs for the shape inherit by the parent style and the master shape. |
| [getInheritTextBlock()](#getinherittextblock) | Contains the textblock values for the shape inherit by the parent style and the master shape. |
| [getInheritTextXForm()](#getinherittextxform) | Contains the textxform values for the shape inherit by the parent style and the master shape. |
| [getInheritUsers()](#getinheritusers) | Contains the users for the shape inherit by the master shape. |
| [getInheritXForm()](#getinheritxform) |  |
| [getInheritXForm1D()](#getinheritxform1d) |  |
| [getLayerMem()](#getlayermem) | Contains the LayerMember element, which specifies each layer to which the shape is assigned. |
| [getLayout()](#getlayout) | Contains elements that control shape placement and connector routing settings. |
| [getLine()](#getline) | Contains elements that control line attributes for a shape, such as pattern, weight, and color. These elements determine |
| [getLineStyle()](#getlinestyle) | StyleSheet from which this shape inherits line formatting |
| [getMaster()](#getmaster) | The Master from which the shape inherits its data. |
| [getMasterShape()](#getmastershape) | This attribute may only be present in shapes that are members of a group shape, and the group is an instance of a master |
| [getMisc()](#getmisc) | Contains elements specifying the Shape element's Help file topic and copyright information. |
| [getName()](#getname) | The name of the element. |
| [getNameU()](#getnameu) | The universal name of the element. |
| [getOneD()](#getoned) | Determines whether the shape behaves as a one-dimensional (1-D) object. Read-only. |
| [getPage()](#getpage) | Root element of Visio objects hierarchy. |
| [getParas()](#getparas) | Contains a collection of Para elements. |
| [getParentShape()](#getparentshape) | Shape's parent. |
| [getProps()](#getprops) | Contains a collection of Prop elements. |
| [getProtection()](#getprotection) | Locking helps prevent inadvertent changes to the shape but does not prevent Microsoft Visio from resetting values in oth |
| [getPureText()](#getpuretext) | Get the text string |
| [getRelationFlag(shape)](#getrelationflag) | Returns RelationFlag that represents the relationship of one shape to another shape. |
| [getRelationShapeCollection()](#getrelationshapecollection) | Returns RelationShapeCollection that represents the relationshapes of one shape. |
| [getRootShape()](#getrootshape) | Returns the top-level shape of an instance if this shape is part of a master instance. Read-only. |
| [getScratchs()](#getscratchs) | Contains a collection of Scratch elements. |
| [getShapes()](#getshapes) | Contains a collection of Shape elements. |
| [getSmartTagDefs()](#getsmarttagdefs) | Contains a collection of SmartTagDef elements. |
| [getTabsCollection()](#gettabscollection) | Contains a collection of Tab elements. |
| [getText()](#gettext) | Contains the text of a shape. |
| [getTextBlock()](#gettextblock) | Contains elements that specify the alignment, margins, and default tab stop positions of text in a shape's text block. |
| [getTextStyle()](#gettextstyle) | StyleSheet from which this shape inherits text formatting. |
| [getTextXForm()](#gettextxform) | Contains elements that specify positioning information about a shape's text block. |
| [getThreeDFormat()](#getthreedformat) | Gets the ThreeDFormat. |
| [getTwoD()](#gettwod) | Determines whether the shape behaves as a two-dimensional (2-D) object. |
| [getType()](#gettype) | The type of a shape. It may be one of the following values: Group, Shape, Guide, or Foreign. The value of the property i |
| [getUniqueID()](#getuniqueid) | A GUID (globally unique identifier) assigned to the shape. |
| [getUsers()](#getusers) | Contains a collection of User elements. |
| [getXForm()](#getxform) | Contains elements specifying general positioning information about a shape. |
| [getXForm1D()](#getxform1d) | Contains x- and y-coordinates of the begin point and end point of a 1-D shape. This element appears for 1-D shapes only. |
| [getZOrderIndex()](#getzorderindex) | Returns the index of a shape in the z-order except the guide shape. |
| [gluedShapes(flag, categoryFilter, otherShape)](#gluedshapes) | Returns an array that contains the identifiers of the shapes that are glued to a shape. |
| [hasThemeColor()](#hasthemecolor) | Gets whether the shape has theme color. |
| [isConnected(shape)](#isconnected) | Indicates whether this two shapes are connected. |
| [isContain()](#iscontain) | Indicates whether this shape is contain another shape. |
| [isGlued(shape)](#isglued) | Indicates whether this two shapes are glued. |
| [isInGroup()](#isingroup) | Indicates whether this shape is in a group shape. |
| [isIntersect()](#isintersect) | Indicates whether this shape is intersect another shape. |
| [move(dX, dY)](#move) | Moves shape on the dX and dY inches from current position. |
| [moveTo(newPinX, newPinY)](#moveto) | Moves shape on new absolute position on the page. |
| [refreshData()](#refreshdata) |  |
| [refreshData()](#refreshdata-1) | Refreshes shape's position including xform ,connection and geom when changing shape's text or other's . We will gather s |
| [replaceText()](#replacetext) | Replace the text string of a shape . |
| [sendBackward()](#sendbackward) | Moves the shape back one position in the z-order. |
| [sendToBack()](#sendtoback) | Moves the shape to the back of the z-order. |
| [setAngle(angle)](#setangle) | Sets new angle of shape. The angle's unit is radian. |
| [setClippingPath()](#setclippingpath) | Contains Clipping Path string value. |
| [setConnectorJumpValue(code, style)](#setconnectorjumpvalue) | Set Jump code value and Jump style value for Connector |
| [setConnectorsType(type)](#setconnectorstype) | Set Connectors type |
| [setContainerProperties()](#setcontainerproperties) | Contains shape's ContainerProperties. |
| [setData1()](#setdata1) | Contains an arbitrary string value that is used to supply additional information about a shape. |
| [setData2()](#setdata2) | Contains an arbitrary string value that is used to supply additional information about a shape. |
| [setData3()](#setdata3) | Contains an arbitrary string value that is used to supply additional information about a shape. |
| [setDel()](#setdel) | A flag indicating whether the element is deleted locally. A value of 1 indicates that the element is deleted locally. Th |
| [setDiagram()](#setdiagram) | Root element of Visio objects hierarchy. |
| [setEvent()](#setevent) | Contains elements that specify formulas that control shape events. |
| [setFillStyle()](#setfillstyle) | StyleSheet from which this shape inherits fill formatting. |
| [setHeight(height)](#setheight) | Sets new height of shape. |
| [setID()](#setid) | The unique ID of the element within its parent element. |
| [setLineStyle()](#setlinestyle) | StyleSheet from which this shape inherits line formatting |
| [setMaster()](#setmaster) | The Master from which the shape inherits its data. |
| [setMasterShape()](#setmastershape) | This attribute may only be present in shapes that are members of a group shape, and the group is an instance of a master |
| [setName()](#setname) | The name of the element. |
| [setNameU()](#setnameu) | The universal name of the element. |
| [setPage()](#setpage) | Root element of Visio objects hierarchy. |
| [setParentShape()](#setparentshape) | Shape's parent. |
| [setPresetTheme()](#setpresettheme) | Apply a preset theme to this shape The value of the property is PresetThemeValue integer constant. |
| [setPresetThemeQuickStyle()](#setpresetthemequickstyle) | Apply a preset theme variant quickstyle to this shape The value of the property is PresetQuickStyleValue integer constan |
| [setPresetThemeStyleMatrics(styleIndex, colorIndex)](#setpresetthemestylematrics) | pply a preset theme variant quickstyle to this shape, like theme styles options in shape styles dropdown list |
| [setPresetThemeVariant()](#setpresetthemevariant) | Apply a preset theme variant to this shape The value of the property is PresetThemeVariantValue integer constant. |
| [setProps()](#setprops) | Contains a collection of Prop elements. |
| [setText()](#settext) | Contains the text of a shape. |
| [setTextStyle()](#settextstyle) | StyleSheet from which this shape inherits text formatting. |
| [setTwoD()](#settwod) | Determines whether the shape behaves as a two-dimensional (2-D) object. |
| [setType()](#settype) | The type of a shape. It may be one of the following values: Group, Shape, Guide, or Foreign. The value of the property i |
| [setWidth(width)](#setwidth) | Sets new width of shape. |
| [setXForm()](#setxform) | Contains elements specifying general positioning information about a shape. |
| [setXForm1D()](#setxform1d) | Contains x- and y-coordinates of the begin point and end point of a 1-D shape. This element appears for 1-D shapes only. |
| [toHTML(fileName, options)](#tohtml) | Creates the html and saves it to a file. |
| [toHTML(stream, options)](#tohtml-1) | Creates the shape html and saves it to a stream in the specified format. |
| [toImage(imageFile, options)](#toimage) | Creates the shape image and saves it to a file. The extension of the file name determines the format of the image. The f |
| [toImage(stream, options)](#toimage-1) | Creates the shape image and saves it to a stream in the specified format. |
| [toPdf(fileName)](#topdf) | Saves the shape to a pdf file. |
| [toSvg(fileName, options)](#tosvg) | Saves the shape to a svg file. |
| [ungroup()](#ungroup) | Ungroup Shape |

### toImageStream(shape, stream, options) (static) {#toimagestream}

Creates the shape image and saves it to a stream in the specified format.

| Parameter | Type | Description |
| --- | --- | --- |
| shape | Shape | The shape object to save |
| stream | WritableStream | The stream |
| options | ImageSaveOptions | ImageSaveOptions |

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
var fs = require("fs");
var diagram = new aspose.diagram.Diagram("example.vsdx");
var page = diagram.getPages().getPage("Page-1");
var shape = page.getShapes().getShape(1);
var writeStream = fs.createWriteStream("output.png");
var options = new aspose.diagram.ImageSaveOptions(aspose.diagram.SaveFileFormat.PNG);
aspose.diagram.Shape.toImageStream(shape, writeStream, options);
```

### toPdfStream(shape, stream) (static) {#topdfstream}

Creates the shape pdf and saves it to a stream.

| Parameter | Type | Description |
| --- | --- | --- |
| shape | Shape | The shape object to save |
| stream | WritableStream | The stream |

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
var fs = require("fs");
var diagram = new aspose.diagram.Diagram("example.vsdx");
var page = diagram.getPages().getPage("Page-1");
var shape = page.getShapes().getShape(1);
var writeStream = fs.createWriteStream("output.pdf");
aspose.diagram.Shape.toPdfStream(shape, writeStream);
```

### bringForward() {#bringforward}

Brings the shape forward one position in the z-order.

### bringToFront() {#bringtofront}

Brings the shape to the front of the z-order.

### centerDrawing() {#centerdrawing}

Center the shape with respect to the extent of the page

### connectedShapes(flag, categoryFilter) {#connectedshapes}

Returns an array that contains the identifiers (IDs) of the shapes that are connected to the shape.

| Parameter | Type | Description |
| --- | --- | --- |
| flag | Number | ConnectedShapesFlags |
| categoryFilter | String | Filters the array of returned shape IDs by limiting it to the IDs of shapes that match the specified category |

**Returns:** Array of long — `Array of long` IDs arraylong.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("AddingNewShape.vsdx");
// get shape by id
shape = diagram.getPages().getPage("Page-3").getShapes().getShape(16);
// get connected shapes
connectedShapeIds = shape.connectedShapes(aspose.diagram.ConnectedShapesFlags.CONNECTED_SHAPES_ALL_NODES, null);
for (let i = 0; i < connectedShapeIds.length; i++) {
shape = diagram.getPages().getPage("Page-3").getShapes().getShape(connectedShapeIds[i]);
console.log("ID: " + shape.getID() + "\t\t Name: " + shape.getName());
}
```

### convertToGroup() {#converttogroup}

Converts a selection or an object from another application (a linked or embedded object) to a group.

### copy(source) {#copy}

| Parameter | Type | Description |
| --- | --- | --- |
| source | Shape | Source shape |

### dependsOnShapes() {#dependsonshapes}

Returns an array that contains the identifiers of the shapes that are depends on a shape.

**Returns:** Array of long — `Array of long` IDs arraylong.

### getActiveXControl() {#getactivexcontrol}

Gets the ActiveX control.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("VisioActiveXControls.vsdx");
// get a Visio page by name
page = diagram.getPages().getPage("Page-1");
// get a shape by ID
shape = page.getShapes().getShape(1);
// get an ActiveX control
activex = shape.getActiveXControl();
// set width of the command button control
activex.setWidth(4);
// set height of the command button control
activex.setHeight(4);
// set caption of the command button control
activex.setCaption("Test Button");
diagram.save("out-RetrieveActiveXControl.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```

### getActs() {#getacts}

Contains a collection of Act elements.

### getAlign() {#getalign}

Indicates the alignment of a shape with respect to the guide or guide point to which the shape is glued. The Align element appears only for shapes that are glued to guides or guide points.

### getChars() {#getchars}

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

### getClippingPath() {#getclippingpath}

Contains Clipping Path string value.

### getConnectionABCDs() {#getconnectionabcds}

Contains a collection of ConnectionABCD elements.

### getConnections() {#getconnections}

Contains a collection of Connection elements.

### getConnectorRule() {#getconnectorrule}

Returns a connectorRule that contains the shape id and connecton that are connected to the shape.

**Returns:** ConnectorRule — `ConnectorRule` ConnectorRule.

### getConnectorsType() {#getconnectorstype}

Get Connectors type

### getContainerProperties() {#getcontainerproperties}

Contains shape's ContainerProperties.

### getControlData() {#getcontroldata}

Gets the data of control.

### getControls() {#getcontrols}

Contains a collection of Control elements.

### getData1() {#getdata1}

Contains an arbitrary string value that is used to supply additional information about a shape.

### getData2() {#getdata2}

Contains an arbitrary string value that is used to supply additional information about a shape.

### getData3() {#getdata3}

Contains an arbitrary string value that is used to supply additional information about a shape.

### getDel() {#getdel}

A flag indicating whether the element is deleted locally. A value of 1 indicates that the element is deleted locally. The value of the property is BOOL integer constant.

### getDiagram() {#getdiagram}

Root element of Visio objects hierarchy.

### getDisplayText() {#getdisplaytext}

Get the text displayed on the interface

### getEvent() {#getevent}

Contains elements that specify formulas that control shape events.

### getFields() {#getfields}

Contains a collection of Field elements.

### getFill() {#getfill}

Contains the current fill formatting values for the shape and the shape's drop shadow, including pattern, foreground color, and background color.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("RetrieveShapeInfo.vsd");
// Find a particular shape and update its foreground color and background color
for (it = diagram.getPages().get(0).getShapes().iterator(); it.hasNext();) {
shape = it.next();
if (shape.getNameU().toLowerCase() == "process") {
shape.getFill().getFillForegnd().setValue("#ebf8df");
shape.getFill().getFillBkgnd().setValue("#dff8eb");
}
}
diagram.save("out-SetFillData.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```

### getFillStyle() {#getfillstyle}

StyleSheet from which this shape inherits fill formatting.

### getForeign() {#getforeign}

Contains elements specifying the width and height of an object from another program used in a Microsoft Visio document. Also includes elements specifying the distance the object's image is offset within its borders.

### getForeignData() {#getforeigndata}

Contains a MIME (Multipurpose Internet Mail Extensions) encoded BLOB of picture data, such as Windows metafile, bitmap, or OLE data.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
fs = require("fs");
diagram = new aspose.diagram.Diagram("ExtractAllImagesFromPage.vsd");
// Enter page index i.e. 0 for first one
for (var it = diagram.getPages().getPage(0).getShapes().iterator(); it.hasNext();) {
shape = it.next();
// Filter shapes by type Foreign
if (shape.getType() == aspose.diagram.TypeValue.FOREIGN) {
output = fs.writeFileSync("out" + shape.getID() + ".bmp", shape.getForeignData().getValue());
}
}
```

### getGeoms() {#getgeoms}

Contains a collection of Geom elements.

### getGroup() {#getgroup}

Contains elements that control how you add shapes to a group, move members of a group, and select groups.

### getHelp() {#gethelp}

Contains elements specifying the Shape element's Help file topic and copyright information.

### getHyperlinks() {#gethyperlinks}

Contains a collection of Hyperlink elements.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("Hyperlinks.vsdx");
// get page by name
var page = diagram.getPages().getPage("Page-1");
// get shape by ID
var shape = page.getShapes().getShape(1);
// get hyperlink collection
var hyperlinks = shape.getHyperlinks();
// iterate through the hyperlinks
for (var it = hyperlinks.iterator(); it.hasNext();) {
hyperlink = it.next();
console.log("Address: " + hyperlink.getAddress().getValue());
console.log("Sub Address: " + hyperlink.getSubAddress().getValue());
console.log("Description: " + hyperlink.getDescription().getValue());
}
```

### getID() {#getid}

The unique ID of the element within its parent element.

### getImage() {#getimage}

Contains the gamma, brightness, contrast, blur, sharpen, denoise, and transparency values for a bitmap.

### getInheritActs() {#getinheritacts}

Contains the actions for the shape inherit by the master shape.

### getInheritChars() {#getinheritchars}

Contains the char values for the shape inherit by the master shape.

### getInheritConnections() {#getinheritconnections}

Contains the connections for the shape inherit by the master shape.

### getInheritControls() {#getinheritcontrols}

Contains the controls for the shape inherit by the master shape.

### getInheritEvent() {#getinheritevent}

Contains the Event for the shape inherit by the master shape.

### getInheritFields() {#getinheritfields}

Contains the fields for the shape inherit by the master shape.

### getInheritFill() {#getinheritfill}

Contains the fill formatting values for the shape inherit by the parent style and the master shape.

### getInheritGeoms() {#getinheritgeoms}

Contains the Geoms values for the shape inherit by the master shape.

### getInheritGroup() {#getinheritgroup}

### getInheritHelp() {#getinherithelp}

Contains the Help for the shape inherit by the master shape.

### getInheritHyperlinks() {#getinherithyperlinks}

Contains the Hyperlinks for the shape inherit by the master shape.

### getInheritLayerMem() {#getinheritlayermem}

Contains the LayerMem for the shape inherit by the master shape.

### getInheritLayout() {#getinheritlayout}

Contains the Layout for the shape inherit by the master shape.

### getInheritLine() {#getinheritline}

Contains the line formatting values for the shape inherit by the parent style and the master shape.

### getInheritMisc() {#getinheritmisc}

Contains the Misc for the shape inherit by the master shape.

### getInheritParas() {#getinheritparas}

Contains the paras for the shape inherit by the parent style and the master shape.

### getInheritProps() {#getinheritprops}

Contains the props for the shape inherit by the master shape.

### getInheritProtection() {#getinheritprotection}

Contains the Protection for the shape inherit by the master shape.

### getInheritScratchs() {#getinheritscratchs}

Contains the scratchs for the shape inherit by the master shape.

### getInheritTabs() {#getinherittabs}

Contains the tabs for the shape inherit by the parent style and the master shape.

### getInheritTextBlock() {#getinherittextblock}

Contains the textblock values for the shape inherit by the parent style and the master shape.

### getInheritTextXForm() {#getinherittextxform}

Contains the textxform values for the shape inherit by the parent style and the master shape.

### getInheritUsers() {#getinheritusers}

Contains the users for the shape inherit by the master shape.

### getInheritXForm() {#getinheritxform}

### getInheritXForm1D() {#getinheritxform1d}

### getLayerMem() {#getlayermem}

Contains the LayerMember element, which specifies each layer to which the shape is assigned.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("Layers.vsdx");
shapes = diagram.getPages().getPage("Page-1").getShapes();
// iterate through the shapes
for (var it = shapes.iterator(); it.hasNext();) {
shape = it.next();
if (shape.getName().toLowerCase() == "shape1") {
// Add shape1 in first two layers. Here "0;1" are indexes of the
// layers
layer = shape.getLayerMem();
layer.getLayerMember().setValue("0;1");
} else if (shape.getName().toLowerCase() == "shape2") {
// Remove shape2 from all the layers
layer = shape.getLayerMem();
layer.getLayerMember().setValue("");
} else if (shape.getName().toLowerCase() == "shape3") {
// Add shape3 in first layer. Here "0" is index of the first
// layer
layer = shape.getLayerMem();
layer.getLayerMember().setValue("0");
}
}
// save diagram
diagram.save("out-ConfigureShapeLayers.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```

### getLayout() {#getlayout}

Contains elements that control shape placement and connector routing settings.

### getLine() {#getline}

Contains elements that control line attributes for a shape, such as pattern, weight, and color. These elements determine whether the line ends are formatted (for example, with an arrowhead), the size of line end formats, radius of the rounding circle applied to the line, and line cap style (round or square).

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("RetrieveShapeInfo.vsd");
// get a shape by id
shape = diagram.getPages().getPage("Page-2").getShapes().getShape(1);
// set line dash type by index
shape.getLine().getLinePattern().setValue(4);
// set line weight, defualt in PT
shape.getLine().getLineWeight().setValue(2);
// set color of the shape's line
shape.getLine().getLineColor().getUfe().setF("RGB(95,108,53)");
// set line rounding, default in inch
shape.getLine().getRounding().setValue(0.3125);
// set line caps
shape.getLine().getLineCap().setValue(aspose.diagram.BOOL.TRUE);
// set line color transparency in percent
shape.getLine().getLineColorTrans().setValue(50);
// add arrows to the connector or curve shapes
// select arrow type by index
shape.getLine().getBeginArrow().setValue(4);
shape.getLine().getEndArrow().setValue(4);
// set arrow size
shape.getLine().getBeginArrowSize().setValue(aspose.diagram.ArrowSizeValue.SMALL);
shape.getLine().getBeginArrowSize().setValue(aspose.diagram.ArrowSizeValue.SMALL);
diagram.save("out-SetLineData.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```

### getLineStyle() {#getlinestyle}

StyleSheet from which this shape inherits line formatting

### getMaster() {#getmaster}

The Master from which the shape inherits its data.

### getMasterShape() {#getmastershape}

This attribute may only be present in shapes that are members of a group shape, and the group is an instance of a master. The attribute contains an ID that references the corresponding sub-shape in the master.

### getMisc() {#getmisc}

Contains elements specifying the Shape element's Help file topic and copyright information.

### getName() {#getname}

The name of the element.

### getNameU() {#getnameu}

The universal name of the element.

### getOneD() {#getoned}

Determines whether the shape behaves as a one-dimensional (1-D) object. Read-only.

### getPage() {#getpage}

Root element of Visio objects hierarchy.

### getParas() {#getparas}

Contains a collection of Para elements.

### getParentShape() {#getparentshape}

Shape's parent.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("AddingNewShape.vsdx");
// get a sub-shape by page name, group shape ID, and then sub-shape ID
shape = diagram.getPages().getPage("Page-3").getShapes().getShape(13).getShapes().getShape(2);
parentShape = shape.getParentShape();
console.log("Parent Shape's Properties:");
console.log("Shape ID: " + parentShape.getID());
console.log("Shape Name: " + parentShape.getName());
console.log("Shape Type: " + parentShape.getType());
```

### getProps() {#getprops}

Contains a collection of Prop elements.

### getProtection() {#getprotection}

Locking helps prevent inadvertent changes to the shape but does not prevent Microsoft Visio from resetting values in other circumstances. It also does not protect against changes made in the ShapeSheet window.

### getPureText() {#getpuretext}

Get the text string

### getRelationFlag(shape) {#getrelationflag}

Returns RelationFlag that represents the relationship of one shape to another shape.

| Parameter | Type | Description |
| --- | --- | --- |
| shape | Shape | Shape |

### getRelationShapeCollection() {#getrelationshapecollection}

Returns RelationShapeCollection that represents the relationshapes of one shape.

### getRootShape() {#getrootshape}

Returns the top-level shape of an instance if this shape is part of a master instance. Read-only.

### getScratchs() {#getscratchs}

Contains a collection of Scratch elements.

### getShapes() {#getshapes}

Contains a collection of Shape elements.

### getSmartTagDefs() {#getsmarttagdefs}

Contains a collection of SmartTagDef elements.

### getTabsCollection() {#gettabscollection}

Contains a collection of Tab elements.

### getText() {#gettext}

Contains the text of a shape.

### getTextBlock() {#gettextblock}

Contains elements that specify the alignment, margins, and default tab stop positions of text in a shape's text block.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("TextBoxes.vsdx");
// get the page by its name
page1 = diagram.getPages().getPage("Page-1");
// get shape by its ID
shape = page1.getShapes().getShape(1);
// set orientation angle
margin = new aspose.diagram.DoubleValue(4, aspose.diagram.MeasureConst.PT);
// set left, right, top and bottom margins of the shape's text block
shape.getTextBlock().setLeftMargin(margin);
shape.getTextBlock().setRightMargin(margin);
shape.getTextBlock().setTopMargin(margin);
shape.getTextBlock().setBottomMargin(margin);
// set the text direction
shape.getTextBlock().getTextDirection().setValue(aspose.diagram.TextDirectionValue.VERTICAL);
// set the text alignment
shape.getTextBlock().getVerticalAlign().setValue(aspose.diagram.VerticalAlignValue.MIDDLE);
// set the text block background color
shape.getTextBlock().getTextBkgnd().getUfe().setF("RGB(95,108,53)");
// set the background color transparency in percent
shape.getTextBlock().getTextBkgndTrans().setValue(50);
// set the distance between default tab stops for the selected shape.
shape.getTextBlock().getDefaultTabStop().setValue(2);
diagram.save("out-FormatShapeTextBlockSection.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```

### getTextStyle() {#gettextstyle}

StyleSheet from which this shape inherits text formatting.

### getTextXForm() {#gettextxform}

Contains elements that specify positioning information about a shape's text block.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("TextBoxes.vsdx");
// get shape
shape = diagram.getPages().getPage("Page-1").getShapes().getShape(1);
// set text position at the bottom,
// TxtLocPinY = "TxtHeight*1" and TxtPinY = "Height*0"
shape.getTextXForm().getTxtLocPinY().setValue(shape.getTextXForm().getTxtHeight().getValue());
shape.getTextXForm().getTxtPinY().setValue(0);
// set orientation angle
angleDeg = 0;
angleRad = (Math.PI / 180) * angleDeg;
shape.getTextXForm().getTxtAngle().setValue(angleRad);
diagram.save("out-SetShapeTextPositionAtBottom.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```

### getThreeDFormat() {#getthreedformat}

Gets the ThreeDFormat.

### getTwoD() {#gettwod}

Determines whether the shape behaves as a two-dimensional (2-D) object.

### getType() {#gettype}

The type of a shape. It may be one of the following values: Group, Shape, Guide, or Foreign. The value of the property is TypeValue integer constant.

### getUniqueID() {#getuniqueid}

A GUID (globally unique identifier) assigned to the shape.

### getUsers() {#getusers}

Contains a collection of User elements.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("TextBoxes.vsdx");
// get page by name
page = diagram.getPages().getPage("Page-1");
// get shape by id
shape = page.getShapes().getShape(2);
// extract user defined cells of the shape
for (it = shape.getUsers().iterator(); it.hasNext();) {
user = it.next();
console.log(user.getName() + ": " + user.getValue().getVal());
}
```

### getXForm() {#getxform}

Contains elements specifying general positioning information about a shape.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("RetrieveShapeInfo.vsd");
// Find a particular shape and update its foreground color and background color
for (it = diagram.getPages().get(0).getShapes().iterator(); it.hasNext();) {
shape = it.next();
if (shape.getNameU().toLowerCase() == "process") {
shape.getXForm().getPinX().setValue(5);
shape.getXForm().getPinY().setValue(5);
}
}
diagram.save("out-SetXFormdata.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```

### getXForm1D() {#getxform1d}

Contains x- and y-coordinates of the begin point and end point of a 1-D shape. This element appears for 1-D shapes only.

### getZOrderIndex() {#getzorderindex}

Returns the index of a shape in the z-order except the guide shape.

### gluedShapes(flag, categoryFilter, otherShape) {#gluedshapes}

Returns an array that contains the identifiers of the shapes that are glued to a shape.

| Parameter | Type | Description |
| --- | --- | --- |
| flag | Number | GluedShapesFlags |
| categoryFilter | String | Filters the array of returned shape IDs by limiting it to the IDs of shapes that match the specified category |
| otherShape | Shape | Optional: additional shape to which returned shapes must also be glued, can be |

**Returns:** Array of long — `Array of long` IDs arraylong.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("RetrieveShapeInfo.vsd");
// get shape by an ID
shape = diagram.getPages().getPage("Page-2").getShapes().getShape(1);
// get all glued 1D shapes
gluedShapeIds = shape.gluedShapes(aspose.diagram.GluedShapesFlags.GLUED_SHAPES_ALL_1_D, null, null);
// display shape ID and name
for (let i = 0; i < gluedShapeIds.length; i++) {
shape = diagram.getPages().get(0).getShapes().getShape(gluedShapeIds[i]);
console.log("ID: " + shape.getID() + "\t\t Name: " + shape.getName());
}
```

### hasThemeColor() {#hasthemecolor}

Gets whether the shape has theme color.

### isConnected(shape) {#isconnected}

Indicates whether this two shapes are connected.

| Parameter | Type | Description |
| --- | --- | --- |
| shape | Shape | shape |

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("RetrieveShapeInfo.vsd");
// get Visio page by name
page = diagram.getPages().getPage("Page-2");
// get Visio shapes by ids
ShapedOne = page.getShapes().getShape(1);
ShapedTwo = page.getShapes().getShape(2);
// determine whether shapes are connected
connected = ShapedOne.isConnected(ShapedTwo);
console.log("Shapes are connected: " + connected);
// determine whether shapes are glued
glued = ShapedOne.isGlued(ShapedTwo);
console.log("Shapes are Glued: " + glued);
```

### isContain() {#iscontain}

Indicates whether this shape is contain another shape.

### isGlued(shape) {#isglued}

Indicates whether this two shapes are glued.

| Parameter | Type | Description |
| --- | --- | --- |
| shape | Shape | shape |

### isInGroup() {#isingroup}

Indicates whether this shape is in a group shape.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("AddingNewShape.vsdx");
// get a sub-shape by page name, group shape ID, and then sub-shape ID
shape = diagram.getPages().getPage("Page-3").getShapes().getShape(13).getShapes().getShape(2);
console.log("Is it in a Group: " + shape.isInGroup());
```

### isIntersect() {#isintersect}

Indicates whether this shape is intersect another shape.

### move(dX, dY) {#move}

Moves shape on the dX and dY inches from current position.

| Parameter | Type | Description |
| --- | --- | --- |
| dX | Number | X offset |
| dY | Number | Y offset |

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("GroupShapes.vsdx");
// get page by name
page = diagram.getPages().getPage("Page-3");
// get shape by id
shape = page.getShapes().getShape(16);
// move shape from its position, it adds values in coordinates
shape.move(1, 1);
diagram.save("out-MoveVisioShape.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```

### moveTo(newPinX, newPinY) {#moveto}

Moves shape on new absolute position on the page.

| Parameter | Type | Description |
| --- | --- | --- |
| newPinX | Number | New x-coordinate of the shape's pin (center of rotation) in relation to the origin of its parent. |
| newPinY | Number | New y-coordinate of the shape's pin (center of rotation) in relation to the origin of its parent. |

### refreshData() {#refreshdata}

### refreshData() {#refreshdata-1}

Refreshes shape's position including xform ,connection and geom when changing shape's text or other's . We will gather shape's data such as shape's text then calculate shape's position. This method is only used to refresh shape's data .

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("AddingNewShape.vsdx");
// get page by name
page = diagram.getPages().getPage("Page-2");
// Add master with stencil file path and master id
masterName = "Rectangle";
// Add master with stencil file path and master name
diagram.addMaster("BasicShapes.vss", masterName);
// page indexing starts from 0
PageIndex = 1;
width = 2, height = 2, pinX = 4.25, pinY = 4.5;
// Add a new rectangle shape
rectangleId = diagram.addShape(pinX, pinY, width, height, masterName, PageIndex);
// set shape properties
rectangle = page.getShapes().getShape(rectangleId);
rectangle.getXForm().getPinX().setValue(5);
rectangle.getXForm().getPinY().setValue(5);
rectangle.setType(aspose.diagram.TypeValue.SHAPE);
rectangle.getText().getValue().add(new aspose.diagram.Txt("Aspose Diagram"));
rectangle.setTextStyle(diagram.getStyleSheets().get(3));
rectangle.getLine().getLineColor().setValue("#ff0000");
rectangle.getLine().getLineWeight().setValue(0.03);
rectangle.getLine().getRounding().setValue(0.1);
rectangle.getFill().getFillBkgnd().setValue("#ff00ff");
rectangle.getFill().getFillForegnd().setValue("#ebf8df");
rectangle.refreshData();
diagram.save("out-AddShape.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```

### replaceText() {#replacetext}

Replace the text string of a shape .

### sendBackward() {#sendbackward}

Moves the shape back one position in the z-order.

### sendToBack() {#sendtoback}

Moves the shape to the back of the z-order.

### setAngle(angle) {#setangle}

Sets new angle of shape. The angle's unit is radian.

| Parameter | Type | Description |
| --- | --- | --- |
| angle | Number | New angle which unit is radian not degree |

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("RetrieveShapeInfo.vsd");
shape = diagram.getPages().getPage("Page-2").getShapes().getShape(2);
// Add a shape and set the angle
shape.setAngle(190);
diagram.save("out-RotateVisioShape.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```

### setClippingPath() {#setclippingpath}

Contains Clipping Path string value.

### setConnectorJumpValue(code, style) {#setconnectorjumpvalue}

Set Jump code value and Jump style value for Connector

| Parameter | Type | Description |
| --- | --- | --- |
| code | Number | ConLineJumpCodeValue |
| style | Number | ConLineJumpStyleValue |

### setConnectorsType(type) {#setconnectorstype}

Set Connectors type

| Parameter | Type | Description |
| --- | --- | --- |
| type | Number | ConnectorsTypeValue |

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("RetrieveShapeInfo.vsd");
// get a dynamic connector type shape by id
shape = diagram.getPages().getPage("Page-2").getShapes().getShape(3);
// set dynamic connector appearance
shape.setConnectorsType(aspose.diagram.ConnectorsTypeValue.STRAIGHT_LINES);
diagram.save("out-SetConnectorAppearance.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```

### setContainerProperties() {#setcontainerproperties}

Contains shape's ContainerProperties.

### setData1() {#setdata1}

Contains an arbitrary string value that is used to supply additional information about a shape.

### setData2() {#setdata2}

Contains an arbitrary string value that is used to supply additional information about a shape.

### setData3() {#setdata3}

Contains an arbitrary string value that is used to supply additional information about a shape.

### setDel() {#setdel}

A flag indicating whether the element is deleted locally. A value of 1 indicates that the element is deleted locally. The value of the property is BOOL integer constant.

### setDiagram() {#setdiagram}

Root element of Visio objects hierarchy.

### setEvent() {#setevent}

Contains elements that specify formulas that control shape events.

### setFillStyle() {#setfillstyle}

StyleSheet from which this shape inherits fill formatting.

### setHeight(height) {#setheight}

Sets new height of shape.

| Parameter | Type | Description |
| --- | --- | --- |
| height | Number | New height |

### setID() {#setid}

The unique ID of the element within its parent element.

### setLineStyle() {#setlinestyle}

StyleSheet from which this shape inherits line formatting

### setMaster() {#setmaster}

The Master from which the shape inherits its data.

### setMasterShape() {#setmastershape}

This attribute may only be present in shapes that are members of a group shape, and the group is an instance of a master. The attribute contains an ID that references the corresponding sub-shape in the master.

### setName() {#setname}

The name of the element.

### setNameU() {#setnameu}

The universal name of the element.

### setPage() {#setpage}

Root element of Visio objects hierarchy.

### setParentShape() {#setparentshape}

Shape's parent.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("AddingNewShape.vsdx");
// get a sub-shape by page name, group shape ID, and then sub-shape ID
shape = diagram.getPages().getPage("Page-3").getShapes().getShape(13).getShapes().getShape(2);
parentShape = shape.getParentShape();
console.log("Parent Shape's Properties:");
console.log("Shape ID: " + parentShape.getID());
console.log("Shape Name: " + parentShape.getName());
console.log("Shape Type: " + parentShape.getType());
```

### setPresetTheme() {#setpresettheme}

Apply a preset theme to this shape The value of the property is PresetThemeValue integer constant.

### setPresetThemeQuickStyle() {#setpresetthemequickstyle}

Apply a preset theme variant quickstyle to this shape The value of the property is PresetQuickStyleValue integer constant.

### setPresetThemeStyleMatrics(styleIndex, colorIndex) {#setpresetthemestylematrics}

pply a preset theme variant quickstyle to this shape, like theme styles options in shape styles dropdown list

| Parameter | Type | Description |
| --- | --- | --- |
| styleIndex | Number | PresetStyleMatricsValue |
| colorIndex | Number | PresetColorMatricsValue |

### setPresetThemeVariant() {#setpresetthemevariant}

Apply a preset theme variant to this shape The value of the property is PresetThemeVariantValue integer constant.

### setProps() {#setprops}

Contains a collection of Prop elements.

### setText() {#settext}

Contains the text of a shape.

### setTextStyle() {#settextstyle}

StyleSheet from which this shape inherits text formatting.

### setTwoD() {#settwod}

Determines whether the shape behaves as a two-dimensional (2-D) object.

### setType() {#settype}

The type of a shape. It may be one of the following values: Group, Shape, Guide, or Foreign. The value of the property is TypeValue integer constant.

### setWidth(width) {#setwidth}

Sets new width of shape.

| Parameter | Type | Description |
| --- | --- | --- |
| width | Number | New width |

### setXForm() {#setxform}

Contains elements specifying general positioning information about a shape.

**Example:**

```js
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");
diagram = new aspose.diagram.Diagram("RetrieveShapeInfo.vsd");
// Find a particular shape and update its foreground color and background color
for (it = diagram.getPages().get(0).getShapes().iterator(); it.hasNext();) {
shape = it.next();
if (shape.getNameU().toLowerCase() == "process") {
shape.getXForm().getPinX().setValue(5);
shape.getXForm().getPinY().setValue(5);
}
}
diagram.save("out-SetXFormdata.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```

### setXForm1D() {#setxform1d}

Contains x- and y-coordinates of the begin point and end point of a 1-D shape. This element appears for 1-D shapes only.

### toHTML(fileName, options) {#tohtml}

Creates the html and saves it to a file.

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | The file name with full path. |
| options | HTMLSaveOptions | html save options |

### toHTML(stream, options) {#tohtml-1}

Creates the shape html and saves it to a stream in the specified format.

| Parameter | Type | Description |
| --- | --- | --- |
| stream | OutputStream | The output stream. |
| options | HTMLSaveOptions | Addtional html creation options |

### toImage(imageFile, options) {#toimage}

Creates the shape image and saves it to a file. The extension of the file name determines the format of the image. The format of the image is specified by using the extension of the file name. For example, if you specify "myfile.png", then the image will be saved in the PNG format. The following file extensions are recognized: .bmp, .gif, .png, .jpg, .jpeg, .tiff, .tif, .emf.

| Parameter | Type | Description |
| --- | --- | --- |
| imageFile | String | The image file name with full path. |
| options | ImageSaveOptions | Additional image creation options |

### toImage(stream, options) {#toimage-1}

Creates the shape image and saves it to a stream in the specified format.

| Parameter | Type | Description |
| --- | --- | --- |
| stream | OutputStream | The output stream. |
| options | ImageSaveOptions | Additional image creation options |

### toPdf(fileName) {#topdf}

Saves the shape to a pdf file.

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | the pdf file name with full path |

### toSvg(fileName, options) {#tosvg}

Saves the shape to a svg file.

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | the svg file name with full path |
| options | SVGSaveOptions | Svg save options |

### ungroup() {#ungroup}

Ungroup Shape
