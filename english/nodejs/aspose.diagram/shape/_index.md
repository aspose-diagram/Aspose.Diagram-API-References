---
title: "Shape Class"
linktitle: "Shape"
articleTitle: "Shape"
second_title: "Aspose.Diagram for Node.js via Java"
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
| [toImageStream(shape, stream, options)](./toimagestream/) *(static)* | Creates the shape image and saves it to a stream in the specified format. |
| [toPdfStream(shape, stream)](./topdfstream/) *(static)* | Creates the shape pdf and saves it to a stream. |
| [bringForward()](./bringforward/) | Brings the shape forward one position in the z-order. |
| [bringToFront()](./bringtofront/) | Brings the shape to the front of the z-order. |
| [centerDrawing()](./centerdrawing/) | Center the shape with respect to the extent of the page |
| [connectedShapes(flag, categoryFilter)](./connectedshapes/) | Returns an array that contains the identifiers (IDs) of the shapes that are connected to the shape. |
| [convertToGroup()](./converttogroup/) | Converts a selection or an object from another application (a linked or embedded object) to a group. |
| [copy(source)](./copy/) |  |
| [dependsOnShapes()](./dependsonshapes/) | Returns an array that contains the identifiers of the shapes that are depends on a shape. |
| [getActiveXControl()](./getactivexcontrol/) | Gets the ActiveX control. |
| [getActs()](./getacts/) | Contains a collection of Act elements. |
| [getAlign()](./getalign/) | Indicates the alignment of a shape with respect to the guide or guide point to which the shape is glued. The Align eleme |
| [getChars()](./getchars/) | Contains a collection of Char elements. |
| [getClippingPath()](./getclippingpath/) | Contains Clipping Path string value. |
| [getConnectionABCDs()](./getconnectionabcds/) | Contains a collection of ConnectionABCD elements. |
| [getConnections()](./getconnections/) | Contains a collection of Connection elements. |
| [getConnectorRule()](./getconnectorrule/) | Returns a connectorRule that contains the shape id and connecton that are connected to the shape. |
| [getConnectorsType()](./getconnectorstype/) | Get Connectors type |
| [getContainerProperties()](./getcontainerproperties/) | Contains shape's ContainerProperties. |
| [getControlData()](./getcontroldata/) | Gets the data of control. |
| [getControls()](./getcontrols/) | Contains a collection of Control elements. |
| [getData1()](./getdata1/) | Contains an arbitrary string value that is used to supply additional information about a shape. |
| [getData2()](./getdata2/) | Contains an arbitrary string value that is used to supply additional information about a shape. |
| [getData3()](./getdata3/) | Contains an arbitrary string value that is used to supply additional information about a shape. |
| [getDel()](./getdel/) | A flag indicating whether the element is deleted locally. A value of 1 indicates that the element is deleted locally. Th |
| [getDiagram()](./getdiagram/) | Root element of Visio objects hierarchy. |
| [getDisplayText()](./getdisplaytext/) | Get the text displayed on the interface |
| [getEvent()](./getevent/) | Contains elements that specify formulas that control shape events. |
| [getFields()](./getfields/) | Contains a collection of Field elements. |
| [getFill()](./getfill/) | Contains the current fill formatting values for the shape and the shape's drop shadow, including pattern, foreground col |
| [getFillStyle()](./getfillstyle/) | StyleSheet from which this shape inherits fill formatting. |
| [getForeign()](./getforeign/) | Contains elements specifying the width and height of an object from another program used in a Microsoft Visio document.  |
| [getForeignData()](./getforeigndata/) | Contains a MIME (Multipurpose Internet Mail Extensions) encoded BLOB of picture data, such as Windows metafile, bitmap,  |
| [getGeoms()](./getgeoms/) | Contains a collection of Geom elements. |
| [getGroup()](./getgroup/) | Contains elements that control how you add shapes to a group, move members of a group, and select groups. |
| [getHelp()](./gethelp/) | Contains elements specifying the Shape element's Help file topic and copyright information. |
| [getHyperlinks()](./gethyperlinks/) | Contains a collection of Hyperlink elements. |
| [getID()](./getid/) | The unique ID of the element within its parent element. |
| [getImage()](./getimage/) | Contains the gamma, brightness, contrast, blur, sharpen, denoise, and transparency values for a bitmap. |
| [getInheritActs()](./getinheritacts/) | Contains the actions for the shape inherit by the master shape. |
| [getInheritChars()](./getinheritchars/) | Contains the char values for the shape inherit by the master shape. |
| [getInheritConnections()](./getinheritconnections/) | Contains the connections for the shape inherit by the master shape. |
| [getInheritControls()](./getinheritcontrols/) | Contains the controls for the shape inherit by the master shape. |
| [getInheritEvent()](./getinheritevent/) | Contains the Event for the shape inherit by the master shape. |
| [getInheritFields()](./getinheritfields/) | Contains the fields for the shape inherit by the master shape. |
| [getInheritFill()](./getinheritfill/) | Contains the fill formatting values for the shape inherit by the parent style and the master shape. |
| [getInheritGeoms()](./getinheritgeoms/) | Contains the Geoms values for the shape inherit by the master shape. |
| [getInheritGroup()](./getinheritgroup/) |  |
| [getInheritHelp()](./getinherithelp/) | Contains the Help for the shape inherit by the master shape. |
| [getInheritHyperlinks()](./getinherithyperlinks/) | Contains the Hyperlinks for the shape inherit by the master shape. |
| [getInheritLayerMem()](./getinheritlayermem/) | Contains the LayerMem for the shape inherit by the master shape. |
| [getInheritLayout()](./getinheritlayout/) | Contains the Layout for the shape inherit by the master shape. |
| [getInheritLine()](./getinheritline/) | Contains the line formatting values for the shape inherit by the parent style and the master shape. |
| [getInheritMisc()](./getinheritmisc/) | Contains the Misc for the shape inherit by the master shape. |
| [getInheritParas()](./getinheritparas/) | Contains the paras for the shape inherit by the parent style and the master shape. |
| [getInheritProps()](./getinheritprops/) | Contains the props for the shape inherit by the master shape. |
| [getInheritProtection()](./getinheritprotection/) | Contains the Protection for the shape inherit by the master shape. |
| [getInheritScratchs()](./getinheritscratchs/) | Contains the scratchs for the shape inherit by the master shape. |
| [getInheritTabs()](./getinherittabs/) | Contains the tabs for the shape inherit by the parent style and the master shape. |
| [getInheritTextBlock()](./getinherittextblock/) | Contains the textblock values for the shape inherit by the parent style and the master shape. |
| [getInheritTextXForm()](./getinherittextxform/) | Contains the textxform values for the shape inherit by the parent style and the master shape. |
| [getInheritUsers()](./getinheritusers/) | Contains the users for the shape inherit by the master shape. |
| [getInheritXForm()](./getinheritxform/) |  |
| [getInheritXForm1D()](./getinheritxform1d/) |  |
| [getLayerMem()](./getlayermem/) | Contains the LayerMember element, which specifies each layer to which the shape is assigned. |
| [getLayout()](./getlayout/) | Contains elements that control shape placement and connector routing settings. |
| [getLine()](./getline/) | Contains elements that control line attributes for a shape, such as pattern, weight, and color. These elements determine |
| [getLineStyle()](./getlinestyle/) | StyleSheet from which this shape inherits line formatting |
| [getMaster()](./getmaster/) | The Master from which the shape inherits its data. |
| [getMasterShape()](./getmastershape/) | This attribute may only be present in shapes that are members of a group shape, and the group is an instance of a master |
| [getMisc()](./getmisc/) | Contains elements specifying the Shape element's Help file topic and copyright information. |
| [getName()](./getname/) | The name of the element. |
| [getNameU()](./getnameu/) | The universal name of the element. |
| [getOneD()](./getoned/) | Determines whether the shape behaves as a one-dimensional (1-D) object. Read-only. |
| [getPage()](./getpage/) | Root element of Visio objects hierarchy. |
| [getParas()](./getparas/) | Contains a collection of Para elements. |
| [getParentShape()](./getparentshape/) | Shape's parent. |
| [getProps()](./getprops/) | Contains a collection of Prop elements. |
| [getProtection()](./getprotection/) | Locking helps prevent inadvertent changes to the shape but does not prevent Microsoft Visio from resetting values in oth |
| [getPureText()](./getpuretext/) | Get the text string |
| [getRelationFlag(shape)](./getrelationflag/) | Returns RelationFlag that represents the relationship of one shape to another shape. |
| [getRelationShapeCollection()](./getrelationshapecollection/) | Returns RelationShapeCollection that represents the relationshapes of one shape. |
| [getRootShape()](./getrootshape/) | Returns the top-level shape of an instance if this shape is part of a master instance. Read-only. |
| [getScratchs()](./getscratchs/) | Contains a collection of Scratch elements. |
| [getShapes()](./getshapes/) | Contains a collection of Shape elements. |
| [getSmartTagDefs()](./getsmarttagdefs/) | Contains a collection of SmartTagDef elements. |
| [getTabsCollection()](./gettabscollection/) | Contains a collection of Tab elements. |
| [getText()](./gettext/) | Contains the text of a shape. |
| [getTextBlock()](./gettextblock/) | Contains elements that specify the alignment, margins, and default tab stop positions of text in a shape's text block. |
| [getTextStyle()](./gettextstyle/) | StyleSheet from which this shape inherits text formatting. |
| [getTextXForm()](./gettextxform/) | Contains elements that specify positioning information about a shape's text block. |
| [getThreeDFormat()](./getthreedformat/) | Gets the ThreeDFormat. |
| [getTwoD()](./gettwod/) | Determines whether the shape behaves as a two-dimensional (2-D) object. |
| [getType()](./gettype/) | The type of a shape. It may be one of the following values: Group, Shape, Guide, or Foreign. The value of the property i |
| [getUniqueID()](./getuniqueid/) | A GUID (globally unique identifier) assigned to the shape. |
| [getUsers()](./getusers/) | Contains a collection of User elements. |
| [getXForm()](./getxform/) | Contains elements specifying general positioning information about a shape. |
| [getXForm1D()](./getxform1d/) | Contains x- and y-coordinates of the begin point and end point of a 1-D shape. This element appears for 1-D shapes only. |
| [getZOrderIndex()](./getzorderindex/) | Returns the index of a shape in the z-order except the guide shape. |
| [gluedShapes(flag, categoryFilter, otherShape)](./gluedshapes/) | Returns an array that contains the identifiers of the shapes that are glued to a shape. |
| [hasThemeColor()](./hasthemecolor/) | Gets whether the shape has theme color. |
| [isConnected(shape)](./isconnected/) | Indicates whether this two shapes are connected. |
| [isContain()](./iscontain/) | Indicates whether this shape is contain another shape. |
| [isGlued(shape)](./isglued/) | Indicates whether this two shapes are glued. |
| [isInGroup()](./isingroup/) | Indicates whether this shape is in a group shape. |
| [isIntersect()](./isintersect/) | Indicates whether this shape is intersect another shape. |
| [move(dX, dY)](./move/) | Moves shape on the dX and dY inches from current position. |
| [moveTo(newPinX, newPinY)](./moveto/) | Moves shape on new absolute position on the page. |
| [refreshData()](./refreshdata/) |  |
| [refreshData()](./refreshdata-1/) | Refreshes shape's position including xform ,connection and geom when changing shape's text or other's . We will gather s |
| [replaceText()](./replacetext/) | Replace the text string of a shape . |
| [sendBackward()](./sendbackward/) | Moves the shape back one position in the z-order. |
| [sendToBack()](./sendtoback/) | Moves the shape to the back of the z-order. |
| [setAngle(angle)](./setangle/) | Sets new angle of shape. The angle's unit is radian. |
| [setClippingPath()](./setclippingpath/) | Contains Clipping Path string value. |
| [setConnectorJumpValue(code, style)](./setconnectorjumpvalue/) | Set Jump code value and Jump style value for Connector |
| [setConnectorsType(type)](./setconnectorstype/) | Set Connectors type |
| [setContainerProperties()](./setcontainerproperties/) | Contains shape's ContainerProperties. |
| [setData1()](./setdata1/) | Contains an arbitrary string value that is used to supply additional information about a shape. |
| [setData2()](./setdata2/) | Contains an arbitrary string value that is used to supply additional information about a shape. |
| [setData3()](./setdata3/) | Contains an arbitrary string value that is used to supply additional information about a shape. |
| [setDel()](./setdel/) | A flag indicating whether the element is deleted locally. A value of 1 indicates that the element is deleted locally. Th |
| [setDiagram()](./setdiagram/) | Root element of Visio objects hierarchy. |
| [setEvent()](./setevent/) | Contains elements that specify formulas that control shape events. |
| [setFillStyle()](./setfillstyle/) | StyleSheet from which this shape inherits fill formatting. |
| [setHeight(height)](./setheight/) | Sets new height of shape. |
| [setID()](./setid/) | The unique ID of the element within its parent element. |
| [setLineStyle()](./setlinestyle/) | StyleSheet from which this shape inherits line formatting |
| [setMaster()](./setmaster/) | The Master from which the shape inherits its data. |
| [setMasterShape()](./setmastershape/) | This attribute may only be present in shapes that are members of a group shape, and the group is an instance of a master |
| [setName()](./setname/) | The name of the element. |
| [setNameU()](./setnameu/) | The universal name of the element. |
| [setPage()](./setpage/) | Root element of Visio objects hierarchy. |
| [setParentShape()](./setparentshape/) | Shape's parent. |
| [setPresetTheme()](./setpresettheme/) | Apply a preset theme to this shape The value of the property is PresetThemeValue integer constant. |
| [setPresetThemeQuickStyle()](./setpresetthemequickstyle/) | Apply a preset theme variant quickstyle to this shape The value of the property is PresetQuickStyleValue integer constan |
| [setPresetThemeStyleMatrics(styleIndex, colorIndex)](./setpresetthemestylematrics/) | pply a preset theme variant quickstyle to this shape, like theme styles options in shape styles dropdown list |
| [setPresetThemeVariant()](./setpresetthemevariant/) | Apply a preset theme variant to this shape The value of the property is PresetThemeVariantValue integer constant. |
| [setProps()](./setprops/) | Contains a collection of Prop elements. |
| [setText()](./settext/) | Contains the text of a shape. |
| [setTextStyle()](./settextstyle/) | StyleSheet from which this shape inherits text formatting. |
| [setTwoD()](./settwod/) | Determines whether the shape behaves as a two-dimensional (2-D) object. |
| [setType()](./settype/) | The type of a shape. It may be one of the following values: Group, Shape, Guide, or Foreign. The value of the property i |
| [setWidth(width)](./setwidth/) | Sets new width of shape. |
| [setXForm()](./setxform/) | Contains elements specifying general positioning information about a shape. |
| [setXForm1D()](./setxform1d/) | Contains x- and y-coordinates of the begin point and end point of a 1-D shape. This element appears for 1-D shapes only. |
| [toHTML(fileName, options)](./tohtml/) | Creates the html and saves it to a file. |
| [toHTML(stream, options)](./tohtml-1/) | Creates the shape html and saves it to a stream in the specified format. |
| [toImage(imageFile, options)](./toimage/) | Creates the shape image and saves it to a file. The extension of the file name determines the format of the image. The f |
| [toImage(stream, options)](./toimage-1/) | Creates the shape image and saves it to a stream in the specified format. |
| [toPdf(fileName)](./topdf/) | Saves the shape to a pdf file. |
| [toSvg(fileName, options)](./tosvg/) | Saves the shape to a svg file. |
| [ungroup()](./ungroup/) | Ungroup Shape |
