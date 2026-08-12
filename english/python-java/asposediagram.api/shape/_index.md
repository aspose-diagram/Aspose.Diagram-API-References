---
title: "Shape"
linktitle: "Shape"
second_title: "Aspose.Diagram for Python via Java API Reference"
description: "Contains elements that define a shape in a Master, Page, or group shape element."
type: docs
weight: 3030
url: /python-java/asposediagram.api/shape/
---

## Shape class

Contains elements that define a shape in a Master, Page, or group shape element.

## Constructors

| Name | Description |
| --- | --- |
| [Shape](#constructor) | Constructor. |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [ID](#id) | long | The unique ID of the element within its parent element. |
| [Del](#del) | int | A flag indicating whether the element is deleted locally. A value of 1 indicates that the element is deleted locally. Th |
| [UniqueID](#uniqueid) | UUID | A GUID (globally unique identifier) assigned to the shape. |
| [Name](#name) | String | The name of the element. |
| [NameU](#nameu) | String | The universal name of the element. |
| [Type](#type) | int | The type of a shape. It may be one of the following values: Group, Shape, Guide, or Foreign. The value of the property i |
| [LineStyle](#linestyle) | StyleSheet | StyleSheet from which this shape inherits line formatting |
| [FillStyle](#fillstyle) | StyleSheet | StyleSheet from which this shape inherits fill formatting. |
| [TextStyle](#textstyle) | StyleSheet | StyleSheet from which this shape inherits text formatting. |
| [Shapes](#shapes) | ShapeCollection | Contains a collection of Shape elements. |
| [Text](#text) | Text | Contains the text of a shape. |
| [XForm](#xform) | XForm | Contains elements specifying general positioning information about a shape. |
| [Line](#line) | Line | Contains elements that control line attributes for a shape, such as pattern, weight, and color. These elements determine |
| [Fill](#fill) | Fill | Contains the current fill formatting values for the shape and the shape's drop shadow, including pattern, foreground col |
| [HasThemeColor](#hasthemecolor) | boolean | Gets whether the shape has theme color. |
| [InheritChars](#inheritchars) | CharCollection | Contains the char values for the shape inherit by the master shape. |
| [InheritProps](#inheritprops) | PropCollection | Contains the props for the shape inherit by the master shape. |
| [InheritFields](#inheritfields) | FieldCollection | Contains the fields for the shape inherit by the master shape. |
| [InheritActs](#inheritacts) | ActCollection | Contains the actions for the shape inherit by the master shape. |
| [InheritHyperlinks](#inherithyperlinks) | HyperlinkCollection | Contains the Hyperlinks for the shape inherit by the master shape. |
| [InheritXForm](#inheritxform) | XForm |  |
| [InheritXForm1D](#inheritxform1d) | XForm1D |  |
| [InheritMisc](#inheritmisc) | Misc | Contains the Misc for the shape inherit by the master shape. |
| [InheritProtection](#inheritprotection) | Protection | Contains the Protection for the shape inherit by the master shape. |
| [InheritEvent](#inheritevent) | Event | Contains the Event for the shape inherit by the master shape. |
| [InheritLayerMem](#inheritlayermem) | LayerMem | Contains the LayerMem for the shape inherit by the master shape. |
| [InheritHelp](#inherithelp) | Help | Contains the Help for the shape inherit by the master shape. |
| [InheritLayout](#inheritlayout) | Layout | Contains the Layout for the shape inherit by the master shape. |
| [InheritControls](#inheritcontrols) | ControlCollection | Contains the controls for the shape inherit by the master shape. |
| [InheritConnections](#inheritconnections) | ConnectionCollection | Contains the connections for the shape inherit by the master shape. |
| [InheritScratchs](#inheritscratchs) | ScratchCollection | Contains the scratchs for the shape inherit by the master shape. |
| [InheritGroup](#inheritgroup) | Group |  |
| [InheritUsers](#inheritusers) | UserCollection | Contains the users for the shape inherit by the master shape. |
| [InheritTextXForm](#inherittextxform) | TextXForm | Contains the textxform values for the shape inherit by the parent style and the master shape. |
| [InheritGeoms](#inheritgeoms) | GeomCollection | Contains the Geoms values for the shape inherit by the master shape. |
| [InheritParas](#inheritparas) | ParaCollection | Contains the paras for the shape inherit by the parent style and the master shape. |
| [InheritTabs](#inherittabs) | TabsCollection | Contains the tabs for the shape inherit by the parent style and the master shape. |
| [InheritTextBlock](#inherittextblock) | TextBlock | Contains the textblock values for the shape inherit by the parent style and the master shape. |
| [InheritLine](#inheritline) | Line | Contains the line formatting values for the shape inherit by the parent style and the master shape. |
| [InheritFill](#inheritfill) | Fill | Contains the fill formatting values for the shape inherit by the parent style and the master shape. |
| [XForm1D](#xform1d) | XForm1D | Contains x- and y-coordinates of the begin point and end point of a 1-D shape. This element appears for 1-D shapes only. |
| [Event](#event) | Event | Contains elements that specify formulas that control shape events. |
| [LayerMem](#layermem) | LayerMem | Contains the LayerMember element, which specifies each layer to which the shape is assigned. |
| [Foreign](#foreign) | Foreign | Contains elements specifying the width and height of an object from another program used in a Microsoft Visio document.  |
| [TextBlock](#textblock) | TextBlock | Contains elements that specify the alignment, margins, and default tab stop positions of text in a shape's text block. |
| [TextXForm](#textxform) | TextXForm | Contains elements that specify positioning information about a shape's text block. |
| [Align](#align) | Align | Indicates the alignment of a shape with respect to the guide or guide point to which the shape is glued. The Align eleme |
| [Protection](#protection) | Protection | Locking helps prevent inadvertent changes to the shape but does not prevent Microsoft Visio from resetting values in oth |
| [Help](#help) | Help | Contains elements specifying the Shape element's Help file topic and copyright information. |
| [Misc](#misc) | Misc | Contains elements specifying the Shape element's Help file topic and copyright information. |
| [Image](#image) | Image | Contains the gamma, brightness, contrast, blur, sharpen, denoise, and transparency values for a bitmap. |
| [Group](#group) | Group | Contains elements that control how you add shapes to a group, move members of a group, and select groups. |
| [Layout](#layout) | Layout | Contains elements that control shape placement and connector routing settings. |
| [Chars](#chars) | CharCollection | Contains a collection of Char elements. |
| [Paras](#paras) | ParaCollection | Contains a collection of Para elements. |
| [Scratchs](#scratchs) | ScratchCollection | Contains a collection of Scratch elements. |
| [Connections](#connections) | ConnectionCollection | Contains a collection of Connection elements. |
| [ContainerProperties](#containerproperties) | ContainerProperties | Contains shape's ContainerProperties. |
| [ConnectionABCDs](#connectionabcds) | ConnectionABCDCollection | Contains a collection of ConnectionABCD elements. |
| [Fields](#fields) | FieldCollection | Contains a collection of Field elements. |
| [Controls](#controls) | ControlCollection | Contains a collection of Control elements. |
| [Geoms](#geoms) | GeomCollection | Contains a collection of Geom elements. |
| [Acts](#acts) | ActCollection | Contains a collection of Act elements. |
| [Users](#users) | UserCollection | Contains a collection of User elements. |
| [Props](#props) | PropCollection | Contains a collection of Prop elements. |
| [Hyperlinks](#hyperlinks) | HyperlinkCollection | Contains a collection of Hyperlink elements. |
| [SmartTagDefs](#smarttagdefs) | SmartTagDefCollection | Contains a collection of SmartTagDef elements. |
| [TabsCollection](#tabscollection) | TabsCollection | Contains a collection of Tab elements. |
| [Data1](#data1) | String | Contains an arbitrary string value that is used to supply additional information about a shape. |
| [Data2](#data2) | String | Contains an arbitrary string value that is used to supply additional information about a shape. |
| [Data3](#data3) | String | Contains an arbitrary string value that is used to supply additional information about a shape. |
| [ClippingPath](#clippingpath) | String | Contains Clipping Path string value. |
| [ForeignData](#foreigndata) | ForeignData | Contains a MIME (Multipurpose Internet Mail Extensions) encoded BLOB of picture data, such as Windows metafile, bitmap,  |
| [MasterShape](#mastershape) | Shape | This attribute may only be present in shapes that are members of a group shape, and the group is an instance of a master |
| [Master](#master) | Master | The Master from which the shape inherits its data. |
| [ParentShape](#parentshape) | Shape | Shape's parent. |
| [RootShape](#rootshape) | Shape | Returns the top-level shape of an instance if this shape is part of a master instance. Read-only. |
| [Diagram](#diagram) | Diagram | Root element of Visio objects hierarchy. |
| [Page](#page) | Page | Root element of Visio objects hierarchy. |
| [OneD](#oned) | boolean | Determines whether the shape behaves as a one-dimensional (1-D) object. Read-only. |
| [TwoD](#twod) | boolean | Determines whether the shape behaves as a two-dimensional (2-D) object. |
| [ControlData](#controldata) | byte[] | Gets the data of control. |
| [ActiveXControl](#activexcontrol) | ActiveXControl | Gets the ActiveX control. |
| [ZOrderIndex](#zorderindex) | int | Returns the index of a shape in the z-order except the guide shape. |
| [PresetTheme](#presettheme) | int | Apply a preset theme to this shape The value of the property is PresetThemeValue integer constant. |
| [PresetThemeVariant](#presetthemevariant) | int | Apply a preset theme variant to this shape The value of the property is PresetThemeVariantValue integer constant. |
| [PresetThemeQuickStyle](#presetthemequickstyle) | int | Apply a preset theme variant quickstyle to this shape The value of the property is PresetQuickStyleValue integer constan |
| [ThreeDFormat](#threedformat) | ThreeDFormat | Gets the ThreeDFormat. |

## Methods

| Name | Description |
| --- | --- |
| [convertToGroup](#converttogroup) | Converts a selection or an object from another application (a linked or embedded object) to a group. |
| [getConnectorsType](#getconnectorstype) | Get Connectors type |
| [setConnectorJumpValue](#setconnectorjumpvalue) | Set Jump code value and Jump style value for Connector |
| [setConnectorsType](#setconnectorstype) | Set Connectors type |
| [getRelationFlag](#getrelationflag) | Returns RelationFlag that represents the relationship of one shape to another shape. |
| [getRelationShapeCollection](#getrelationshapecollection) | Returns RelationShapeCollection that represents the relationshapes of one shape. |
| [setPresetThemeStyleMatrics](#setpresetthemestylematrics) | pply a preset theme variant quickstyle to this shape, like theme styles options in shape styles dropdown list |
| [copy](#copy) |  |
| [bringForward](#bringforward) | Brings the shape forward one position in the z-order. |
| [sendBackward](#sendbackward) | Moves the shape back one position in the z-order. |
| [bringToFront](#bringtofront) | Brings the shape to the front of the z-order. |
| [sendToBack](#sendtoback) | Moves the shape to the back of the z-order. |
| [getConnectorRule](#getconnectorrule) | Returns a connectorRule that contains the shape id and connecton that are connected to the shape. |
| [connectedShapes](#connectedshapes) | Returns an array that contains the identifiers (IDs) of the shapes that are connected to the shape. |
| [isInGroup](#isingroup) | Indicates whether this shape is in a group shape. |
| [isContain](#iscontain) | Indicates whether this shape is contain another shape. |
| [isIntersect](#isintersect) | Indicates whether this shape is intersect another shape. |
| [isConnected](#isconnected) | Indicates whether this two shapes are connected. |
| [centerDrawing](#centerdrawing) | Center the shape with respect to the extent of the page |
| [isGlued](#isglued) | Indicates whether this two shapes are glued. |
| [refreshData](#refreshdata) |  |
| [gluedShapes](#gluedshapes) | Returns an array that contains the identifiers of the shapes that are glued to a shape. |
| [dependsOnShapes](#dependsonshapes) | Returns an array that contains the identifiers of the shapes that are depends on a shape. |
| [setWidth](#setwidth) | Sets new width of shape. |
| [setHeight](#setheight) | Sets new height of shape. |
| [setAngle](#setangle) | Sets new angle of shape. The angle's unit is radian. |
| [moveTo](#moveto) | Moves shape on new absolute position on the page. |
| [move](#move) | Moves shape on the dX and dY inches from current position. |
| [getDisplayText](#getdisplaytext) | Get the text displayed on the interface |
| [getPureText](#getpuretext) | Get the text string |
| [ungroup](#ungroup) | Ungroup Shape |
| [replaceText](#replacetext) | Replace the text string of a shape . |
| [toPdf](#topdf) | Saves the shape to a pdf file. |

### Shape() {#constructor}

Constructor.

### Shape.ID property {#id}

The unique ID of the element within its parent element.

**Type:** long

### Shape.Del property {#del}

A flag indicating whether the element is deleted locally. A value of 1 indicates that the element is deleted locally. The value of the property is BOOL integer constant.

**Type:** int

### Shape.UniqueID property {#uniqueid}

A GUID (globally unique identifier) assigned to the shape.

**Type:** UUID

### Shape.Name property {#name}

The name of the element.

**Type:** String

### Shape.NameU property {#nameu}

The universal name of the element.

**Type:** String

### Shape.Type property {#type}

The type of a shape. It may be one of the following values: Group, Shape, Guide, or Foreign. The value of the property is TypeValue integer constant.

**Type:** int

### Shape.LineStyle property {#linestyle}

StyleSheet from which this shape inherits line formatting

**Type:** StyleSheet

### Shape.FillStyle property {#fillstyle}

StyleSheet from which this shape inherits fill formatting.

**Type:** StyleSheet

### Shape.TextStyle property {#textstyle}

StyleSheet from which this shape inherits text formatting.

**Type:** StyleSheet

### Shape.Shapes property {#shapes}

Contains a collection of Shape elements.

**Type:** ShapeCollection

### Shape.Text property {#text}

Contains the text of a shape.

**Type:** Text

### Shape.XForm property {#xform}

Contains elements specifying general positioning information about a shape.

**Type:** XForm

### Shape.Line property {#line}

Contains elements that control line attributes for a shape, such as pattern, weight, and color. These elements determine whether the line ends are formatted (for example, with an arrowhead), the size of line end formats, radius of the rounding circle applied to the line, and line cap style (round or square).

**Type:** Line

### Shape.Fill property {#fill}

Contains the current fill formatting values for the shape and the shape's drop shadow, including pattern, foreground color, and background color.

**Type:** Fill

### Shape.HasThemeColor property {#hasthemecolor}

Gets whether the shape has theme color.

**Type:** boolean

### Shape.InheritChars property {#inheritchars}

Contains the char values for the shape inherit by the master shape.

**Type:** CharCollection

### Shape.InheritProps property {#inheritprops}

Contains the props for the shape inherit by the master shape.

**Type:** PropCollection

### Shape.InheritFields property {#inheritfields}

Contains the fields for the shape inherit by the master shape.

**Type:** FieldCollection

### Shape.InheritActs property {#inheritacts}

Contains the actions for the shape inherit by the master shape.

**Type:** ActCollection

### Shape.InheritHyperlinks property {#inherithyperlinks}

Contains the Hyperlinks for the shape inherit by the master shape.

**Type:** HyperlinkCollection

### Shape.InheritXForm property {#inheritxform}

**Type:** XForm

### Shape.InheritXForm1D property {#inheritxform1d}

**Type:** XForm1D

### Shape.InheritMisc property {#inheritmisc}

Contains the Misc for the shape inherit by the master shape.

**Type:** Misc

### Shape.InheritProtection property {#inheritprotection}

Contains the Protection for the shape inherit by the master shape.

**Type:** Protection

### Shape.InheritEvent property {#inheritevent}

Contains the Event for the shape inherit by the master shape.

**Type:** Event

### Shape.InheritLayerMem property {#inheritlayermem}

Contains the LayerMem for the shape inherit by the master shape.

**Type:** LayerMem

### Shape.InheritHelp property {#inherithelp}

Contains the Help for the shape inherit by the master shape.

**Type:** Help

### Shape.InheritLayout property {#inheritlayout}

Contains the Layout for the shape inherit by the master shape.

**Type:** Layout

### Shape.InheritControls property {#inheritcontrols}

Contains the controls for the shape inherit by the master shape.

**Type:** ControlCollection

### Shape.InheritConnections property {#inheritconnections}

Contains the connections for the shape inherit by the master shape.

**Type:** ConnectionCollection

### Shape.InheritScratchs property {#inheritscratchs}

Contains the scratchs for the shape inherit by the master shape.

**Type:** ScratchCollection

### Shape.InheritGroup property {#inheritgroup}

**Type:** Group

### Shape.InheritUsers property {#inheritusers}

Contains the users for the shape inherit by the master shape.

**Type:** UserCollection

### Shape.InheritTextXForm property {#inherittextxform}

Contains the textxform values for the shape inherit by the parent style and the master shape.

**Type:** TextXForm

### Shape.InheritGeoms property {#inheritgeoms}

Contains the Geoms values for the shape inherit by the master shape.

**Type:** GeomCollection

### Shape.InheritParas property {#inheritparas}

Contains the paras for the shape inherit by the parent style and the master shape.

**Type:** ParaCollection

### Shape.InheritTabs property {#inherittabs}

Contains the tabs for the shape inherit by the parent style and the master shape.

**Type:** TabsCollection

### Shape.InheritTextBlock property {#inherittextblock}

Contains the textblock values for the shape inherit by the parent style and the master shape.

**Type:** TextBlock

### Shape.InheritLine property {#inheritline}

Contains the line formatting values for the shape inherit by the parent style and the master shape.

**Type:** Line

### Shape.InheritFill property {#inheritfill}

Contains the fill formatting values for the shape inherit by the parent style and the master shape.

**Type:** Fill

### Shape.XForm1D property {#xform1d}

Contains x- and y-coordinates of the begin point and end point of a 1-D shape. This element appears for 1-D shapes only.

**Type:** XForm1D

### Shape.Event property {#event}

Contains elements that specify formulas that control shape events.

**Type:** Event

### Shape.LayerMem property {#layermem}

Contains the LayerMember element, which specifies each layer to which the shape is assigned.

**Type:** LayerMem

### Shape.Foreign property {#foreign}

Contains elements specifying the width and height of an object from another program used in a Microsoft Visio document. Also includes elements specifying the distance the object's image is offset within its borders.

**Type:** Foreign

### Shape.TextBlock property {#textblock}

Contains elements that specify the alignment, margins, and default tab stop positions of text in a shape's text block.

**Type:** TextBlock

### Shape.TextXForm property {#textxform}

Contains elements that specify positioning information about a shape's text block.

**Type:** TextXForm

### Shape.Align property {#align}

Indicates the alignment of a shape with respect to the guide or guide point to which the shape is glued. The Align element appears only for shapes that are glued to guides or guide points.

**Type:** Align

### Shape.Protection property {#protection}

Locking helps prevent inadvertent changes to the shape but does not prevent Microsoft Visio from resetting values in other circumstances. It also does not protect against changes made in the ShapeSheet window.

**Type:** Protection

### Shape.Help property {#help}

Contains elements specifying the Shape element's Help file topic and copyright information.

**Type:** Help

### Shape.Misc property {#misc}

Contains elements specifying the Shape element's Help file topic and copyright information.

**Type:** Misc

### Shape.Image property {#image}

Contains the gamma, brightness, contrast, blur, sharpen, denoise, and transparency values for a bitmap.

**Type:** Image

### Shape.Group property {#group}

Contains elements that control how you add shapes to a group, move members of a group, and select groups.

**Type:** Group

### Shape.Layout property {#layout}

Contains elements that control shape placement and connector routing settings.

**Type:** Layout

### Shape.Chars property {#chars}

Contains a collection of Char elements.

**Type:** CharCollection

### Shape.Paras property {#paras}

Contains a collection of Para elements.

**Type:** ParaCollection

### Shape.Scratchs property {#scratchs}

Contains a collection of Scratch elements.

**Type:** ScratchCollection

### Shape.Connections property {#connections}

Contains a collection of Connection elements.

**Type:** ConnectionCollection

### Shape.ContainerProperties property {#containerproperties}

Contains shape's ContainerProperties.

**Type:** ContainerProperties

### Shape.ConnectionABCDs property {#connectionabcds}

Contains a collection of ConnectionABCD elements.

**Type:** ConnectionABCDCollection

### Shape.Fields property {#fields}

Contains a collection of Field elements.

**Type:** FieldCollection

### Shape.Controls property {#controls}

Contains a collection of Control elements.

**Type:** ControlCollection

### Shape.Geoms property {#geoms}

Contains a collection of Geom elements.

**Type:** GeomCollection

### Shape.Acts property {#acts}

Contains a collection of Act elements.

**Type:** ActCollection

### Shape.Users property {#users}

Contains a collection of User elements.

**Type:** UserCollection

### Shape.Props property {#props}

Contains a collection of Prop elements.

**Type:** PropCollection

### Shape.Hyperlinks property {#hyperlinks}

Contains a collection of Hyperlink elements.

**Type:** HyperlinkCollection

### Shape.SmartTagDefs property {#smarttagdefs}

Contains a collection of SmartTagDef elements.

**Type:** SmartTagDefCollection

### Shape.TabsCollection property {#tabscollection}

Contains a collection of Tab elements.

**Type:** TabsCollection

### Shape.Data1 property {#data1}

Contains an arbitrary string value that is used to supply additional information about a shape.

**Type:** String

### Shape.Data2 property {#data2}

Contains an arbitrary string value that is used to supply additional information about a shape.

**Type:** String

### Shape.Data3 property {#data3}

Contains an arbitrary string value that is used to supply additional information about a shape.

**Type:** String

### Shape.ClippingPath property {#clippingpath}

Contains Clipping Path string value.

**Type:** String

### Shape.ForeignData property {#foreigndata}

Contains a MIME (Multipurpose Internet Mail Extensions) encoded BLOB of picture data, such as Windows metafile, bitmap, or OLE data.

**Type:** ForeignData

### Shape.MasterShape property {#mastershape}

This attribute may only be present in shapes that are members of a group shape, and the group is an instance of a master. The attribute contains an ID that references the corresponding sub-shape in the master.

**Type:** Shape

### Shape.Master property {#master}

The Master from which the shape inherits its data.

**Type:** Master

### Shape.ParentShape property {#parentshape}

Shape's parent.

**Type:** Shape

### Shape.RootShape property {#rootshape}

Returns the top-level shape of an instance if this shape is part of a master instance. Read-only.

**Type:** Shape

### Shape.Diagram property {#diagram}

Root element of Visio objects hierarchy.

**Type:** Diagram

### Shape.Page property {#page}

Root element of Visio objects hierarchy.

**Type:** Page

### Shape.OneD property {#oned}

Determines whether the shape behaves as a one-dimensional (1-D) object. Read-only.

**Type:** boolean

### Shape.TwoD property {#twod}

Determines whether the shape behaves as a two-dimensional (2-D) object.

**Type:** boolean

### Shape.ControlData property {#controldata}

Gets the data of control.

**Type:** byte[]

### Shape.ActiveXControl property {#activexcontrol}

Gets the ActiveX control.

**Type:** ActiveXControl

### Shape.ZOrderIndex property {#zorderindex}

Returns the index of a shape in the z-order except the guide shape.

**Type:** int

### Shape.PresetTheme property {#presettheme}

Apply a preset theme to this shape The value of the property is PresetThemeValue integer constant.

**Type:** int

### Shape.PresetThemeVariant property {#presetthemevariant}

Apply a preset theme variant to this shape The value of the property is PresetThemeVariantValue integer constant.

**Type:** int

### Shape.PresetThemeQuickStyle property {#presetthemequickstyle}

Apply a preset theme variant quickstyle to this shape The value of the property is PresetQuickStyleValue integer constant.

**Type:** int

### Shape.ThreeDFormat property {#threedformat}

Gets the ThreeDFormat.

**Type:** ThreeDFormat

### convertToGroup() {#converttogroup}

Converts a selection or an object from another application (a linked or embedded object) to a group.

### getConnectorsType() {#getconnectorstype}

Get Connectors type

### setConnectorJumpValue(code, style) {#setconnectorjumpvalue}

Set Jump code value and Jump style value for Connector

| Parameter | Type | Description |
| --- | --- | --- |
| code | int | A ConLineJumpCodeValue value. Jump Code Value |
| style | int | A ConLineJumpStyleValue value. Jump Code Style |

### setConnectorsType(type) {#setconnectorstype}

Set Connectors type

| Parameter | Type | Description |
| --- | --- | --- |
| type | int | A ConnectorsTypeValue value. Connectors type value |

**Example:**

```python
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");

diagram = new aspose.diagram.Diagram("RetrieveShapeInfo.vsd");

// get a dynamic connector type shape by id
shape = diagram.getPages().getPage("Page-2").getShapes().getShape(3);

// set dynamic connector appearance
shape.setConnectorsType(aspose.diagram.ConnectorsTypeValue.STRAIGHT_LINES);

diagram.save("out-SetConnectorAppearance.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```

### getRelationFlag(shape) {#getrelationflag}

Returns RelationFlag that represents the relationship of one shape to another shape.

| Parameter | Type | Description |
| --- | --- | --- |
| shape | Shape | Shape |

### getRelationShapeCollection() {#getrelationshapecollection}

Returns RelationShapeCollection that represents the relationshapes of one shape.

### setPresetThemeStyleMatrics(styleIndex, colorIndex) {#setpresetthemestylematrics}

pply a preset theme variant quickstyle to this shape, like theme styles options in shape styles dropdown list

| Parameter | Type | Description |
| --- | --- | --- |
| styleIndex | int | A PresetStyleMatricsValue value. the row of style matrics |
| colorIndex | int | A PresetColorMatricsValue value. the column of style matrics |

### copy(source) {#copy}

| Parameter | Type | Description |
| --- | --- | --- |
| source | Shape | Source shape |

### bringForward() {#bringforward}

Brings the shape forward one position in the z-order.

### sendBackward() {#sendbackward}

Moves the shape back one position in the z-order.

### bringToFront() {#bringtofront}

Brings the shape to the front of the z-order.

### sendToBack() {#sendtoback}

Moves the shape to the back of the z-order.

### getConnectorRule() {#getconnectorrule}

Returns a connectorRule that contains the shape id and connecton that are connected to the shape.

**Returns:** ConnectorRule.

### connectedShapes(flag, categoryFilter) {#connectedshapes}

Returns an array that contains the identifiers (IDs) of the shapes that are connected to the shape.

| Parameter | Type | Description |
| --- | --- | --- |
| flag | int | A ConnectedShapesFlags value. Filters the array of returned shape IDs by the directionality of the connectors. See Remarks for possible values ConnectedShapesFlags . |
| categoryFilter | String | Filters the array of returned shape IDs by limiting it to the IDs of shapes that match the specified category java.lang.String . |

**Returns:** IDs array long .

**Example:**

```python
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

### isInGroup() {#isingroup}

Indicates whether this shape is in a group shape.

**Example:**

```python
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");

diagram = new aspose.diagram.Diagram("AddingNewShape.vsdx");

// get a sub-shape by page name, group shape ID, and then sub-shape ID
shape = diagram.getPages().getPage("Page-3").getShapes().getShape(13).getShapes().getShape(2);
console.log("Is it in a Group: " + shape.isInGroup());
```

### isContain(shape) {#iscontain}

Indicates whether this shape is contain another shape.

### isIntersect(shape) {#isintersect}

Indicates whether this shape is intersect another shape.

### isConnected(shape) {#isconnected}

Indicates whether this two shapes are connected.

| Parameter | Type | Description |
| --- | --- | --- |
| shape | Shape | shape |

**Example:**

```python
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

### centerDrawing() {#centerdrawing}

Center the shape with respect to the extent of the page

### isGlued(shape) {#isglued}

Indicates whether this two shapes are glued.

| Parameter | Type | Description |
| --- | --- | --- |
| shape | Shape | shape |

### refreshData() (1 of 2) {#refreshdata}

---

### refreshData(options) (2 of 2) {#refreshdata-1}

Refreshes shape's position including xform ,connection and geom when changing shape's text or other's .

We will gather shape's data such as shape's text then calculate shape's position. This method is only used to refresh shape's data .

**Example:**

```python
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

### gluedShapes(flag, categoryFilter, otherShape) {#gluedshapes}

Returns an array that contains the identifiers of the shapes that are glued to a shape.

| Parameter | Type | Description |
| --- | --- | --- |
| flag | int | A GluedShapesFlags value. The dimensionality and directionality of the connection points of the shapes to return.See Remarks for possible values GluedShapesFlags . |
| categoryFilter | String | Filters the array of returned shape IDs by limiting it to the IDs of shapes that match the specified category java.lang.String . |
| otherShape | Shape | Optional: additional shape to which returned shapes must also be glued, can be Shape or null. |

**Returns:** IDs array long .

**Example:**

```python
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

### dependsOnShapes() {#dependsonshapes}

Returns an array that contains the identifiers of the shapes that are depends on a shape.

**Returns:** IDs array long .

### setWidth(width) {#setwidth}

Sets new width of shape.

| Parameter | Type | Description |
| --- | --- | --- |
| width | float | New width double . |

### setHeight(height) {#setheight}

Sets new height of shape.

| Parameter | Type | Description |
| --- | --- | --- |
| height | float | New height double . |

### setAngle(angle) {#setangle}

Sets new angle of shape. The angle's unit is radian.

| Parameter | Type | Description |
| --- | --- | --- |
| angle | float | New angle which unit is radian not degree double . |

**Example:**

```python
var aspose = aspose || {};
aspose.diagram = require("aspose.diagram");

diagram = new aspose.diagram.Diagram("RetrieveShapeInfo.vsd");

shape = diagram.getPages().getPage("Page-2").getShapes().getShape(2);

// Add a shape and set the angle
shape.setAngle(190);

diagram.save("out-RotateVisioShape.vsdx", aspose.diagram.SaveFileFormat.VSDX);
```

### moveTo(newPinX, newPinY) {#moveto}

Moves shape on new absolute position on the page.

| Parameter | Type | Description |
| --- | --- | --- |
| newPinX | float | New x-coordinate of the shape's pin (center of rotation) in relation to the origin of its parent. double . |
| newPinY | float | New y-coordinate of the shape's pin (center of rotation) in relation to the origin of its parent. double . |

### move(dX, dY) {#move}

Moves shape on the dX and dY inches from current position.

| Parameter | Type | Description |
| --- | --- | --- |
| dX | float | X offset double . |
| dY | float | Y offset double . |

**Example:**

```python
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

### getDisplayText() {#getdisplaytext}

Get the text displayed on the interface

### getPureText() {#getpuretext}

Get the text string

### ungroup() {#ungroup}

Ungroup Shape

### replaceText(text, replaceText) {#replacetext}

Replace the text string of a shape .

### toPdf(fileName) {#topdf}

Saves the shape to a pdf file.

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | the pdf file name with full path |
