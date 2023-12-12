---
title: Shape
second_title: Aspose.Diagram for Java API Reference
description: Contains elements that define a shape in a Master Page or group shape element.
type: docs
weight: 361
url: /java/com.aspose.diagram/shape/
---

**Inheritance:**
java.lang.Object
```
public class Shape
```

Contains elements that define a shape in a Master, Page, or group shape element.
## Constructors

| Constructor | Description |
| --- | --- |
| [Shape()](#Shape--) | Constructor. |
## Methods

| Method | Description |
| --- | --- |
| [bringForward()](#bringForward--) | Brings the shape forward one position in the z-order. |
| [bringToFront()](#bringToFront--) | Brings the shape to the front of the z-order. |
| [centerDrawing()](#centerDrawing--) | Center the shape with respect to the extent of the page |
| [connectedShapes(int flag, String categoryFilter)](#connectedShapes-int-java.lang.String-) | Returns an array that contains the identifiers (IDs) of the shapes that are connected to the shape. |
| [convertToGroup()](#convertToGroup--) | Converts a selection or an object from another application (a linked or embedded object) to a group. |
| [copy(Shape source)](#copy-com.aspose.diagram.Shape-) |  |
| [dependsOnShapes()](#dependsOnShapes--) | Returns an array that contains the identifiers of the shapes that are depends on a shape. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActiveXControl()](#getActiveXControl--) | Gets the ActiveX control. |
| [getActs()](#getActs--) | Contains a collection of Act elements. |
| [getAlign()](#getAlign--) | Indicates the alignment of a shape with respect to the guide or guide point to which the shape is glued. |
| [getChars()](#getChars--) | Contains a collection of Char elements. |
| [getClass()](#getClass--) |  |
| [getClippingPath()](#getClippingPath--) |  |
| [getConnectionABCDs()](#getConnectionABCDs--) | Contains a collection of ConnectionABCD elements. |
| [getConnections()](#getConnections--) | Contains a collection of Connection elements. |
| [getConnectorRule()](#getConnectorRule--) | Returns a connectorRule that contains the shape id and connecton that are connected to the shape. |
| [getConnectorsType()](#getConnectorsType--) | Get Connectors type |
| [getControlData()](#getControlData--) | Gets the data of control. |
| [getControls()](#getControls--) | Contains a collection of Control elements. |
| [getData1()](#getData1--) | Contains an arbitrary string value that is used to supply additional information about a shape. |
| [getData2()](#getData2--) | Contains an arbitrary string value that is used to supply additional information about a shape. |
| [getData3()](#getData3--) | Contains an arbitrary string value that is used to supply additional information about a shape. |
| [getDel()](#getDel--) | A flag indicating whether the element is deleted locally. |
| [getDiagram()](#getDiagram--) | Root element of Visio objects hierarchy. |
| [getDisplayText()](#getDisplayText--) | Get the text displayed on the interface |
| [getEvent()](#getEvent--) | Contains elements that specify formulas that control shape events. |
| [getFields()](#getFields--) | Contains a collection of Field elements. |
| [getFill()](#getFill--) | Contains the current fill formatting values for the shape and the shape's drop shadow, including pattern, foreground color, and background color. |
| [getFillStyle()](#getFillStyle--) | StyleSheet from which this shape inherits fill formatting. |
| [getForeign()](#getForeign--) | Contains elements specifying the width and height of an object from another program used in a Microsoft Visio document. |
| [getForeignData()](#getForeignData--) | Contains a MIME (Multipurpose Internet Mail Extensions) encoded BLOB of picture data, such as Windows metafile, bitmap, or OLE data. |
| [getGeoms()](#getGeoms--) | Contains a collection of Geom elements. |
| [getGroup()](#getGroup--) | Contains elements that control how you add shapes to a group, move members of a group, and select groups. |
| [getHelp()](#getHelp--) | Contains elements specifying the Shape element's Help file topic and copyright information. |
| [getHyperlinks()](#getHyperlinks--) | Contains a collection of Hyperlink elements. |
| [getID()](#getID--) | The unique ID of the element within its parent element. |
| [getImage()](#getImage--) | Contains the gamma, brightness, contrast, blur, sharpen, denoise, and transparency values for a bitmap. |
| [getInheritChars()](#getInheritChars--) | Contains the char values for the shape inherit by the master shape. |
| [getInheritFill()](#getInheritFill--) | Contains the fill formatting values for the shape inherit by the parent style and the master shape. |
| [getInheritGeoms()](#getInheritGeoms--) | Contains the Geoms values for the shape inherit by the master shape. |
| [getInheritGroup()](#getInheritGroup--) |  |
| [getInheritLine()](#getInheritLine--) | Contains the line formatting values for the shape inherit by the parent style and the master shape. |
| [getInheritParas()](#getInheritParas--) | Contains the paras for the shape inherit by the parent style and the master shape. |
| [getInheritProps()](#getInheritProps--) | Contains the props for the shape inherit by the master shape. |
| [getInheritTextBlock()](#getInheritTextBlock--) | Contains the textblock values for the shape inherit by the parent style and the master shape. |
| [getInheritUsers()](#getInheritUsers--) | Contains the users for the shape inherit by the master shape. |
| [getLayerMem()](#getLayerMem--) | Contains the LayerMember element, which specifies each layer to which the shape is assigned. |
| [getLayout()](#getLayout--) | Contains elements that control shape placement and connector routing settings. |
| [getLine()](#getLine--) | Contains elements that control line attributes for a shape, such as pattern, weight, and color. |
| [getLineStyle()](#getLineStyle--) | StyleSheet from which this shape inherits line formatting |
| [getMaster()](#getMaster--) | The Master from which the shape inherits its data. |
| [getMasterShape()](#getMasterShape--) | This attribute may only be present in shapes that are members of a group shape, and the group is an instance of a master. |
| [getMisc()](#getMisc--) | Contains elements specifying the Shape element's Help file topic and copyright information. |
| [getName()](#getName--) | The name of the element. |
| [getNameU()](#getNameU--) | The universal name of the element. |
| [getOneD()](#getOneD--) | Determines whether the shape behaves as a one-dimensional (1-D) object. |
| [getPage()](#getPage--) | Root element of Visio objects hierarchy. |
| [getParas()](#getParas--) | Contains a collection of Para elements. |
| [getParentShape()](#getParentShape--) | Shape's parent. |
| [getProps()](#getProps--) | Contains a collection of Prop elements. |
| [getProtection()](#getProtection--) | Locking helps prevent inadvertent changes to the shape but does not prevent Microsoft Visio from resetting values in other circumstances. |
| [getPureText()](#getPureText--) | Get the text string |
| [getRelationFlag(Shape shape)](#getRelationFlag-com.aspose.diagram.Shape-) | Returns RelationFlag that represents the relationship of one shape to another shape. |
| [getRelationShapeCollection()](#getRelationShapeCollection--) | Returns RelationShapeCollection that represents the relationshapes of one shape. |
| [getRootShape()](#getRootShape--) | Returns the top-level shape of an instance if this shape is part of a master instance. |
| [getScratchs()](#getScratchs--) | Contains a collection of Scratch elements. |
| [getShapes()](#getShapes--) | Contains a collection of Shape elements. |
| [getSmartTagDefs()](#getSmartTagDefs--) | Contains a collection of SmartTagDef elements. |
| [getTabsCollection()](#getTabsCollection--) | Contains a collection of Tab elements. |
| [getText()](#getText--) | Contains the text of a shape. |
| [getTextBlock()](#getTextBlock--) | Contains elements that specify the alignment, margins, and default tab stop positions of text in a shape's text block. |
| [getTextStyle()](#getTextStyle--) | StyleSheet from which this shape inherits text formatting. |
| [getTextXForm()](#getTextXForm--) | Contains elements that specify positioning information about a shape's text block. |
| [getThreeDFormat()](#getThreeDFormat--) | Gets the ThreeDFormat. |
| [getTwoD()](#getTwoD--) | Determines whether the shape behaves as a two-dimensional (2-D) object. |
| [getType()](#getType--) | The type of a shape. |
| [getUniqueID()](#getUniqueID--) | A GUID (globally unique identifier) assigned to the shape. |
| [getUsers()](#getUsers--) | Contains a collection of User elements. |
| [getXForm()](#getXForm--) | Contains elements specifying general positioning information about a shape. |
| [getXForm1D()](#getXForm1D--) | Contains x- and y-coordinates of the begin point and end point of a 1-D shape. |
| [getZOrderIndex()](#getZOrderIndex--) | Returns the index of a shape in the z-order except the guide shape. |
| [gluedShapes(int flag, String categoryFilter, Shape otherShape)](#gluedShapes-int-java.lang.String-com.aspose.diagram.Shape-) | Returns an array that contains the identifiers of the shapes that are glued to a shape. |
| [hashCode()](#hashCode--) |  |
| [isConnected(Shape shape)](#isConnected-com.aspose.diagram.Shape-) | Indicates whether this two shapes are connected. |
| [isContain(Shape shape)](#isContain-com.aspose.diagram.Shape-) | Indicates whether this shape is contain another shape. |
| [isGlued(Shape shape)](#isGlued-com.aspose.diagram.Shape-) | Indicates whether this two shapes are glued. |
| [isInGroup()](#isInGroup--) | Indicates whether this shape is in a group shape. |
| [isIntersect(Shape shape)](#isIntersect-com.aspose.diagram.Shape-) | Indicates whether this shape is intersect another shape. |
| [isTextEmpty()](#isTextEmpty--) | Indicate the shape has text and the text is empty or not. |
| [move(double dX, double dY)](#move-double-double-) | Moves shape on the dX and dY inches from current position. |
| [moveTo(double newPinX, double newPinY)](#moveTo-double-double-) | Moves shape on new absolute position on the page. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [refreshData()](#refreshData--) | Refreshes shape's position including xform ,connection and geom when changing shape's text or other's . |
| [replaceText(String text, String replaceText)](#replaceText-java.lang.String-java.lang.String-) | Replace the text string of a shape . |
| [sendBackward()](#sendBackward--) | Moves the shape back one position in the z-order. |
| [sendToBack()](#sendToBack--) | Moves the shape to the back of the z-order. |
| [setAngle(double angle)](#setAngle-double-) | Sets new angle of shape. |
| [setClippingPath(String value)](#setClippingPath-java.lang.String-) | For the description of this property, please see [getClippingPath()](../../com.aspose.diagram/shape\#getClippingPath--) |
| [setConnectorsType(int type)](#setConnectorsType-int-) | Set Connectors type |
| [setData1(String value)](#setData1-java.lang.String-) | For the description of this property, please see [getData1()](../../com.aspose.diagram/shape\#getData1--) |
| [setData2(String value)](#setData2-java.lang.String-) | For the description of this property, please see [getData2()](../../com.aspose.diagram/shape\#getData2--) |
| [setData3(String value)](#setData3-java.lang.String-) | For the description of this property, please see [getData3()](../../com.aspose.diagram/shape\#getData3--) |
| [setDel(int value)](#setDel-int-) | For the description of this property, please see [getDel()](../../com.aspose.diagram/shape\#getDel--) |
| [setDiagram(Diagram value)](#setDiagram-com.aspose.diagram.Diagram-) | For the description of this property, please see [getDiagram()](../../com.aspose.diagram/shape\#getDiagram--) |
| [setEvent(Event value)](#setEvent-com.aspose.diagram.Event-) | For the description of this property, please see [getEvent()](../../com.aspose.diagram/shape\#getEvent--) |
| [setFillStyle(StyleSheet value)](#setFillStyle-com.aspose.diagram.StyleSheet-) | For the description of this property, please see [getFillStyle()](../../com.aspose.diagram/shape\#getFillStyle--) |
| [setHeight(double height)](#setHeight-double-) | Sets new height of shape. |
| [setID(long value)](#setID-long-) | For the description of this property, please see [getID()](../../com.aspose.diagram/shape\#getID--) |
| [setLineStyle(StyleSheet value)](#setLineStyle-com.aspose.diagram.StyleSheet-) | For the description of this property, please see [getLineStyle()](../../com.aspose.diagram/shape\#getLineStyle--) |
| [setMaster(Master value)](#setMaster-com.aspose.diagram.Master-) | For the description of this property, please see [getMaster()](../../com.aspose.diagram/shape\#getMaster--) |
| [setMasterShape(Shape value)](#setMasterShape-com.aspose.diagram.Shape-) | For the description of this property, please see [getMasterShape()](../../com.aspose.diagram/shape\#getMasterShape--) |
| [setName(String value)](#setName-java.lang.String-) | For the description of this property, please see [getName()](../../com.aspose.diagram/shape\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | For the description of this property, please see [getNameU()](../../com.aspose.diagram/shape\#getNameU--) |
| [setPage(Page value)](#setPage-com.aspose.diagram.Page-) | For the description of this property, please see [getPage()](../../com.aspose.diagram/shape\#getPage--) |
| [setParentShape(Shape value)](#setParentShape-com.aspose.diagram.Shape-) | For the description of this property, please see [getParentShape()](../../com.aspose.diagram/shape\#getParentShape--) |
| [setPresetTheme(int value)](#setPresetTheme-int-) | Apply a preset theme to this shape |
| [setPresetThemeQuickStyle(int value)](#setPresetThemeQuickStyle-int-) | Apply a preset theme variant quickstyle to this shape |
| [setPresetThemeStyleMatrics(int styleIndex, int colorIndex)](#setPresetThemeStyleMatrics-int-int-) | pply a preset theme variant quickstyle to this shape, like theme styles options in shape styles dropdown list |
| [setPresetThemeVariant(int value)](#setPresetThemeVariant-int-) | Apply a preset theme variant to this shape |
| [setProps(PropCollection value)](#setProps-com.aspose.diagram.PropCollection-) | For the description of this property, please see [getProps()](../../com.aspose.diagram/shape\#getProps--) |
| [setText(Text value)](#setText-com.aspose.diagram.Text-) | For the description of this property, please see [getText()](../../com.aspose.diagram/shape\#getText--) |
| [setTextStyle(StyleSheet value)](#setTextStyle-com.aspose.diagram.StyleSheet-) | For the description of this property, please see [getTextStyle()](../../com.aspose.diagram/shape\#getTextStyle--) |
| [setTwoD(boolean value)](#setTwoD-boolean-) | For the description of this property, please see [getTwoD()](../../com.aspose.diagram/shape\#getTwoD--) |
| [setType(int value)](#setType-int-) | For the description of this property, please see [getType()](../../com.aspose.diagram/shape\#getType--) |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | For the description of this property, please see [getUniqueID()](../../com.aspose.diagram/shape\#getUniqueID--) |
| [setWidth(double width)](#setWidth-double-) | Sets new width of shape. |
| [setXForm(XForm value)](#setXForm-com.aspose.diagram.XForm-) | For the description of this property, please see [getXForm()](../../com.aspose.diagram/shape\#getXForm--) |
| [setXForm1D(XForm1D value)](#setXForm1D-com.aspose.diagram.XForm1D-) | For the description of this property, please see [getXForm1D()](../../com.aspose.diagram/shape\#getXForm1D--) |
| [toHTML(InputStream stream, HTMLSaveOptions options)](#toHTML-java.io.InputStream-com.aspose.diagram.HTMLSaveOptions-) | Creates the shape html and saves it to a stream in the specified format. |
| [toHTML(OutputStream stream, HTMLSaveOptions options)](#toHTML-java.io.OutputStream-com.aspose.diagram.HTMLSaveOptions-) | Creates the shape html and saves it to a stream in the specified format. |
| [toHTML(String fileName, HTMLSaveOptions options)](#toHTML-java.lang.String-com.aspose.diagram.HTMLSaveOptions-) | Creates the html and saves it to a file. |
| [toImage(InputStream stream, ImageSaveOptions options)](#toImage-java.io.InputStream-com.aspose.diagram.ImageSaveOptions-) | Creates the shape image and saves it to a stream in the specified format. |
| [toImage(OutputStream stream, ImageSaveOptions options)](#toImage-java.io.OutputStream-com.aspose.diagram.ImageSaveOptions-) | Creates the shape image and saves it to a stream in the specified format. |
| [toImage(String imageFile, ImageSaveOptions options)](#toImage-java.lang.String-com.aspose.diagram.ImageSaveOptions-) | Creates the shape image and saves it to a file. |
| [toPdf(InputStream stream)](#toPdf-java.io.InputStream-) | Creates the shape pdf and saves it to a stream. |
| [toPdf(OutputStream stream)](#toPdf-java.io.OutputStream-) | Creates the shape pdf and saves it to a stream. |
| [toPdf(String fileName)](#toPdf-java.lang.String-) | Saves the shape to a pdf file. |
| [toString()](#toString--) |  |
| [toSvg(String imageFile, SVGSaveOptions options)](#toSvg-java.lang.String-com.aspose.diagram.SVGSaveOptions-) | Saves the shape to a svg file. |
| [ungroup()](#ungroup--) | Ungroup Shape |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Shape() {#Shape--}
```
public Shape()
```


Constructor.

### bringForward() {#bringForward--}
```
public void bringForward()
```


Brings the shape forward one position in the z-order.

### bringToFront() {#bringToFront--}
```
public void bringToFront()
```


Brings the shape to the front of the z-order.

### centerDrawing() {#centerDrawing--}
```
public void centerDrawing()
```


Center the shape with respect to the extent of the page

### connectedShapes(int flag, String categoryFilter) {#connectedShapes-int-java.lang.String-}
```
public long[] connectedShapes(int flag, String categoryFilter)
```


Returns an array that contains the identifiers (IDs) of the shapes that are connected to the shape.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| flag | int | Filters the array of returned shape IDs by the directionality of the connectors. See Remarks for possible valuesAspose.Diagram.ConnectedShapesFlags. |
| categoryFilter | java.lang.String | Filters the array of returned shape IDs by limiting it to the IDs of shapes that match the specified categoryString. |

**Returns:**
long[] - IDs arraylong.
### convertToGroup() {#convertToGroup--}
```
public void convertToGroup()
```


Converts a selection or an object from another application (a linked or embedded object) to a group.

### copy(Shape source) {#copy-com.aspose.diagram.Shape-}
```
public void copy(Shape source)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [Shape](../../com.aspose.diagram/shape) |  |

### dependsOnShapes() {#dependsOnShapes--}
```
public long[] dependsOnShapes()
```


Returns an array that contains the identifiers of the shapes that are depends on a shape.

**Returns:**
long[] - IDs arraylong.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getActiveXControl() {#getActiveXControl--}
```
public ActiveXControl getActiveXControl()
```


Gets the ActiveX control.

**Returns:**
[ActiveXControl](../../com.aspose.diagram/activexcontrol)
### getActs() {#getActs--}
```
public ActCollection getActs()
```


Contains a collection of Act elements.

**Returns:**
[ActCollection](../../com.aspose.diagram/actcollection)
### getAlign() {#getAlign--}
```
public Align getAlign()
```


Indicates the alignment of a shape with respect to the guide or guide point to which the shape is glued. The Align element appears only for shapes that are glued to guides or guide points.

**Returns:**
[Align](../../com.aspose.diagram/align)
### getChars() {#getChars--}
```
public CharCollection getChars()
```


Contains a collection of Char elements.

**Returns:**
[CharCollection](../../com.aspose.diagram/charcollection)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClippingPath() {#getClippingPath--}
```
public String getClippingPath()
```




**Returns:**
java.lang.String
### getConnectionABCDs() {#getConnectionABCDs--}
```
public ConnectionABCDCollection getConnectionABCDs()
```


Contains a collection of ConnectionABCD elements.

**Returns:**
[ConnectionABCDCollection](../../com.aspose.diagram/connectionabcdcollection)
### getConnections() {#getConnections--}
```
public ConnectionCollection getConnections()
```


Contains a collection of Connection elements.

**Returns:**
[ConnectionCollection](../../com.aspose.diagram/connectioncollection)
### getConnectorRule() {#getConnectorRule--}
```
public ConnectorRule getConnectorRule()
```


Returns a connectorRule that contains the shape id and connecton that are connected to the shape.

**Returns:**
[ConnectorRule](../../com.aspose.diagram/connectorrule) - ConnectorRule.
### getConnectorsType() {#getConnectorsType--}
```
public int getConnectorsType()
```


Get Connectors type

**Returns:**
int
### getControlData() {#getControlData--}
```
public byte[] getControlData()
```


Gets the data of control.

**Returns:**
byte[]
### getControls() {#getControls--}
```
public ControlCollection getControls()
```


Contains a collection of Control elements.

**Returns:**
[ControlCollection](../../com.aspose.diagram/controlcollection)
### getData1() {#getData1--}
```
public String getData1()
```


Contains an arbitrary string value that is used to supply additional information about a shape.

**Returns:**
java.lang.String
### getData2() {#getData2--}
```
public String getData2()
```


Contains an arbitrary string value that is used to supply additional information about a shape.

**Returns:**
java.lang.String
### getData3() {#getData3--}
```
public String getData3()
```


Contains an arbitrary string value that is used to supply additional information about a shape.

**Returns:**
java.lang.String
### getDel() {#getDel--}
```
public int getDel()
```


A flag indicating whether the element is deleted locally. A value of 1 indicates that the element is deleted locally.

**Returns:**
int
### getDiagram() {#getDiagram--}
```
public Diagram getDiagram()
```


Root element of Visio objects hierarchy.

**Returns:**
[Diagram](../../com.aspose.diagram/diagram)
### getDisplayText() {#getDisplayText--}
```
public String getDisplayText()
```


Get the text displayed on the interface

**Returns:**
java.lang.String
### getEvent() {#getEvent--}
```
public Event getEvent()
```


Contains elements that specify formulas that control shape events.

**Returns:**
[Event](../../com.aspose.diagram/event)
### getFields() {#getFields--}
```
public FieldCollection getFields()
```


Contains a collection of Field elements.

**Returns:**
[FieldCollection](../../com.aspose.diagram/fieldcollection)
### getFill() {#getFill--}
```
public Fill getFill()
```


Contains the current fill formatting values for the shape and the shape's drop shadow, including pattern, foreground color, and background color.

**Returns:**
[Fill](../../com.aspose.diagram/fill)
### getFillStyle() {#getFillStyle--}
```
public StyleSheet getFillStyle()
```


StyleSheet from which this shape inherits fill formatting.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getForeign() {#getForeign--}
```
public Foreign getForeign()
```


Contains elements specifying the width and height of an object from another program used in a Microsoft Visio document. Also includes elements specifying the distance the object's image is offset within its borders.

**Returns:**
[Foreign](../../com.aspose.diagram/foreign)
### getForeignData() {#getForeignData--}
```
public ForeignData getForeignData()
```


Contains a MIME (Multipurpose Internet Mail Extensions) encoded BLOB of picture data, such as Windows metafile, bitmap, or OLE data.

**Returns:**
[ForeignData](../../com.aspose.diagram/foreigndata)
### getGeoms() {#getGeoms--}
```
public GeomCollection getGeoms()
```


Contains a collection of Geom elements.

**Returns:**
[GeomCollection](../../com.aspose.diagram/geomcollection)
### getGroup() {#getGroup--}
```
public Group getGroup()
```


Contains elements that control how you add shapes to a group, move members of a group, and select groups.

**Returns:**
[Group](../../com.aspose.diagram/group)
### getHelp() {#getHelp--}
```
public Help getHelp()
```


Contains elements specifying the Shape element's Help file topic and copyright information.

**Returns:**
[Help](../../com.aspose.diagram/help)
### getHyperlinks() {#getHyperlinks--}
```
public HyperlinkCollection getHyperlinks()
```


Contains a collection of Hyperlink elements.

**Returns:**
[HyperlinkCollection](../../com.aspose.diagram/hyperlinkcollection)
### getID() {#getID--}
```
public long getID()
```


The unique ID of the element within its parent element.

**Returns:**
long
### getImage() {#getImage--}
```
public Image getImage()
```


Contains the gamma, brightness, contrast, blur, sharpen, denoise, and transparency values for a bitmap.

**Returns:**
[Image](../../com.aspose.diagram/image)
### getInheritChars() {#getInheritChars--}
```
public CharCollection getInheritChars()
```


Contains the char values for the shape inherit by the master shape.

**Returns:**
[CharCollection](../../com.aspose.diagram/charcollection)
### getInheritFill() {#getInheritFill--}
```
public Fill getInheritFill()
```


Contains the fill formatting values for the shape inherit by the parent style and the master shape.

**Returns:**
[Fill](../../com.aspose.diagram/fill)
### getInheritGeoms() {#getInheritGeoms--}
```
public GeomCollection getInheritGeoms()
```


Contains the Geoms values for the shape inherit by the master shape.

**Returns:**
[GeomCollection](../../com.aspose.diagram/geomcollection)
### getInheritGroup() {#getInheritGroup--}
```
public Group getInheritGroup()
```




**Returns:**
[Group](../../com.aspose.diagram/group)
### getInheritLine() {#getInheritLine--}
```
public Line getInheritLine()
```


Contains the line formatting values for the shape inherit by the parent style and the master shape.

**Returns:**
[Line](../../com.aspose.diagram/line)
### getInheritParas() {#getInheritParas--}
```
public ParaCollection getInheritParas()
```


Contains the paras for the shape inherit by the parent style and the master shape.

**Returns:**
[ParaCollection](../../com.aspose.diagram/paracollection)
### getInheritProps() {#getInheritProps--}
```
public PropCollection getInheritProps()
```


Contains the props for the shape inherit by the master shape.

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getInheritTextBlock() {#getInheritTextBlock--}
```
public TextBlock getInheritTextBlock()
```


Contains the textblock values for the shape inherit by the parent style and the master shape.

**Returns:**
[TextBlock](../../com.aspose.diagram/textblock)
### getInheritUsers() {#getInheritUsers--}
```
public UserCollection getInheritUsers()
```


Contains the users for the shape inherit by the master shape.

**Returns:**
[UserCollection](../../com.aspose.diagram/usercollection)
### getLayerMem() {#getLayerMem--}
```
public LayerMem getLayerMem()
```


Contains the LayerMember element, which specifies each layer to which the shape is assigned.

**Returns:**
[LayerMem](../../com.aspose.diagram/layermem)
### getLayout() {#getLayout--}
```
public Layout getLayout()
```


Contains elements that control shape placement and connector routing settings.

**Returns:**
[Layout](../../com.aspose.diagram/layout)
### getLine() {#getLine--}
```
public Line getLine()
```


Contains elements that control line attributes for a shape, such as pattern, weight, and color. These elements determine whether the line ends are formatted (for example, with an arrowhead), the size of line end formats, radius of the rounding circle applied to the line, and line cap style (round or square).

**Returns:**
[Line](../../com.aspose.diagram/line)
### getLineStyle() {#getLineStyle--}
```
public StyleSheet getLineStyle()
```


StyleSheet from which this shape inherits line formatting

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getMaster() {#getMaster--}
```
public Master getMaster()
```


The Master from which the shape inherits its data.

**Returns:**
[Master](../../com.aspose.diagram/master)
### getMasterShape() {#getMasterShape--}
```
public Shape getMasterShape()
```


This attribute may only be present in shapes that are members of a group shape, and the group is an instance of a master. The attribute contains an ID that references the corresponding sub-shape in the master.

**Returns:**
[Shape](../../com.aspose.diagram/shape)
### getMisc() {#getMisc--}
```
public Misc getMisc()
```


Contains elements specifying the Shape element's Help file topic and copyright information.

**Returns:**
[Misc](../../com.aspose.diagram/misc)
### getName() {#getName--}
```
public String getName()
```


The name of the element.

**Returns:**
java.lang.String
### getNameU() {#getNameU--}
```
public String getNameU()
```


The universal name of the element.

**Returns:**
java.lang.String
### getOneD() {#getOneD--}
```
public boolean getOneD()
```


Determines whether the shape behaves as a one-dimensional (1-D) object. Read-only.

**Returns:**
boolean
### getPage() {#getPage--}
```
public Page getPage()
```


Root element of Visio objects hierarchy.

**Returns:**
[Page](../../com.aspose.diagram/page)
### getParas() {#getParas--}
```
public ParaCollection getParas()
```


Contains a collection of Para elements.

**Returns:**
[ParaCollection](../../com.aspose.diagram/paracollection)
### getParentShape() {#getParentShape--}
```
public Shape getParentShape()
```


Shape's parent.

**Returns:**
[Shape](../../com.aspose.diagram/shape)
### getProps() {#getProps--}
```
public PropCollection getProps()
```


Contains a collection of Prop elements.

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getProtection() {#getProtection--}
```
public Protection getProtection()
```


Locking helps prevent inadvertent changes to the shape but does not prevent Microsoft Visio from resetting values in other circumstances. It also does not protect against changes made in the ShapeSheet window.

**Returns:**
[Protection](../../com.aspose.diagram/protection)
### getPureText() {#getPureText--}
```
public String getPureText()
```


Get the text string

**Returns:**
java.lang.String
### getRelationFlag(Shape shape) {#getRelationFlag-com.aspose.diagram.Shape-}
```
public int getRelationFlag(Shape shape)
```


Returns RelationFlag that represents the relationship of one shape to another shape.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) |  |

**Returns:**
int
### getRelationShapeCollection() {#getRelationShapeCollection--}
```
public RelationShapeCollection getRelationShapeCollection()
```


Returns RelationShapeCollection that represents the relationshapes of one shape.

**Returns:**
[RelationShapeCollection](../../com.aspose.diagram/relationshapecollection)
### getRootShape() {#getRootShape--}
```
public Shape getRootShape()
```


Returns the top-level shape of an instance if this shape is part of a master instance. Read-only.

**Returns:**
[Shape](../../com.aspose.diagram/shape)
### getScratchs() {#getScratchs--}
```
public ScratchCollection getScratchs()
```


Contains a collection of Scratch elements.

**Returns:**
[ScratchCollection](../../com.aspose.diagram/scratchcollection)
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


Contains a collection of Shape elements.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getSmartTagDefs() {#getSmartTagDefs--}
```
public SmartTagDefCollection getSmartTagDefs()
```


Contains a collection of SmartTagDef elements.

**Returns:**
[SmartTagDefCollection](../../com.aspose.diagram/smarttagdefcollection)
### getTabsCollection() {#getTabsCollection--}
```
public TabsCollection getTabsCollection()
```


Contains a collection of Tab elements.

**Returns:**
[TabsCollection](../../com.aspose.diagram/tabscollection)
### getText() {#getText--}
```
public Text getText()
```


Contains the text of a shape.

**Returns:**
[Text](../../com.aspose.diagram/text)
### getTextBlock() {#getTextBlock--}
```
public TextBlock getTextBlock()
```


Contains elements that specify the alignment, margins, and default tab stop positions of text in a shape's text block.

**Returns:**
[TextBlock](../../com.aspose.diagram/textblock)
### getTextStyle() {#getTextStyle--}
```
public StyleSheet getTextStyle()
```


StyleSheet from which this shape inherits text formatting.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getTextXForm() {#getTextXForm--}
```
public TextXForm getTextXForm()
```


Contains elements that specify positioning information about a shape's text block.

**Returns:**
[TextXForm](../../com.aspose.diagram/textxform)
### getThreeDFormat() {#getThreeDFormat--}
```
public ThreeDFormat getThreeDFormat()
```


Gets the ThreeDFormat.

**Returns:**
[ThreeDFormat](../../com.aspose.diagram/threedformat)
### getTwoD() {#getTwoD--}
```
public boolean getTwoD()
```


Determines whether the shape behaves as a two-dimensional (2-D) object.

**Returns:**
boolean
### getType() {#getType--}
```
public int getType()
```


The type of a shape. It may be one of the following values: Group, Shape, Guide, or Foreign.

**Returns:**
int
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


A GUID (globally unique identifier) assigned to the shape.

**Returns:**
java.util.UUID
### getUsers() {#getUsers--}
```
public UserCollection getUsers()
```


Contains a collection of User elements.

**Returns:**
[UserCollection](../../com.aspose.diagram/usercollection)
### getXForm() {#getXForm--}
```
public XForm getXForm()
```


Contains elements specifying general positioning information about a shape.

**Returns:**
[XForm](../../com.aspose.diagram/xform)
### getXForm1D() {#getXForm1D--}
```
public XForm1D getXForm1D()
```


Contains x- and y-coordinates of the begin point and end point of a 1-D shape. This element appears for 1-D shapes only.

**Returns:**
[XForm1D](../../com.aspose.diagram/xform1d)
### getZOrderIndex() {#getZOrderIndex--}
```
public int getZOrderIndex()
```


Returns the index of a shape in the z-order except the guide shape.

**Returns:**
int
### gluedShapes(int flag, String categoryFilter, Shape otherShape) {#gluedShapes-int-java.lang.String-com.aspose.diagram.Shape-}
```
public long[] gluedShapes(int flag, String categoryFilter, Shape otherShape)
```


Returns an array that contains the identifiers of the shapes that are glued to a shape.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| flag | int | The dimensionality and directionality of the connection points of the shapes to return.See Remarks for possible valuesAspose.Diagram.GluedShapesFlags. |
| categoryFilter | java.lang.String | Filters the array of returned shape IDs by limiting it to the IDs of shapes that match the specified categoryString. |
| otherShape | [Shape](../../com.aspose.diagram/shape) | Optional: additional shape to which returned shapes must also be glued, can be [Shape](../../com.aspose.diagram/shape) or null. |

**Returns:**
long[] - IDs arraylong.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isConnected(Shape shape) {#isConnected-com.aspose.diagram.Shape-}
```
public boolean isConnected(Shape shape)
```


Indicates whether this two shapes are connected.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) | shape |

**Returns:**
boolean
### isContain(Shape shape) {#isContain-com.aspose.diagram.Shape-}
```
public boolean isContain(Shape shape)
```


Indicates whether this shape is contain another shape.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) |  |

**Returns:**
boolean
### isGlued(Shape shape) {#isGlued-com.aspose.diagram.Shape-}
```
public boolean isGlued(Shape shape)
```


Indicates whether this two shapes are glued.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) | shape |

**Returns:**
boolean
### isInGroup() {#isInGroup--}
```
public boolean isInGroup()
```


Indicates whether this shape is in a group shape.

**Returns:**
boolean
### isIntersect(Shape shape) {#isIntersect-com.aspose.diagram.Shape-}
```
public boolean isIntersect(Shape shape)
```


Indicates whether this shape is intersect another shape.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) |  |

**Returns:**
boolean
### isTextEmpty() {#isTextEmpty--}
```
public boolean isTextEmpty()
```


Indicate the shape has text and the text is empty or not.

**Returns:**
boolean
### move(double dX, double dY) {#move-double-double-}
```
public void move(double dX, double dY)
```


Moves shape on the dX and dY inches from current position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dX | double | X offsetdouble. |
| dY | double | Y offsetdouble. |

### moveTo(double newPinX, double newPinY) {#moveTo-double-double-}
```
public void moveTo(double newPinX, double newPinY)
```


Moves shape on new absolute position on the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newPinX | double | New x-coordinate of the shape's pin (center of rotation) in relation to the origin of its parent.double. |
| newPinY | double | New y-coordinate of the shape's pin (center of rotation) in relation to the origin of its parent.double. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### refreshData() {#refreshData--}
```
public void refreshData()
```


Refreshes shape's position including xform ,connection and geom when changing shape's text or other's . We will gather shape's data such as shape's text then calculate shape's position. This method is only used to refresh shape's data .

### replaceText(String text, String replaceText) {#replaceText-java.lang.String-java.lang.String-}
```
public void replaceText(String text, String replaceText)
```


Replace the text string of a shape .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String |  |
| replaceText | java.lang.String |  |

### sendBackward() {#sendBackward--}
```
public void sendBackward()
```


Moves the shape back one position in the z-order.

### sendToBack() {#sendToBack--}
```
public void sendToBack()
```


Moves the shape to the back of the z-order.

### setAngle(double angle) {#setAngle-double-}
```
public void setAngle(double angle)
```


Sets new angle of shape. The angle's unit is radian.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| angle | double | New angle which unit is radian not degreedouble. |

### setClippingPath(String value) {#setClippingPath-java.lang.String-}
```
public void setClippingPath(String value)
```


For the description of this property, please see [getClippingPath()](../../com.aspose.diagram/shape\#getClippingPath--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setConnectorsType(int type) {#setConnectorsType-int-}
```
public void setConnectorsType(int type)
```


Set Connectors type

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int |  |

### setData1(String value) {#setData1-java.lang.String-}
```
public void setData1(String value)
```


For the description of this property, please see [getData1()](../../com.aspose.diagram/shape\#getData1--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setData2(String value) {#setData2-java.lang.String-}
```
public void setData2(String value)
```


For the description of this property, please see [getData2()](../../com.aspose.diagram/shape\#getData2--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setData3(String value) {#setData3-java.lang.String-}
```
public void setData3(String value)
```


For the description of this property, please see [getData3()](../../com.aspose.diagram/shape\#getData3--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


For the description of this property, please see [getDel()](../../com.aspose.diagram/shape\#getDel--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setDiagram(Diagram value) {#setDiagram-com.aspose.diagram.Diagram-}
```
public void setDiagram(Diagram value)
```


For the description of this property, please see [getDiagram()](../../com.aspose.diagram/shape\#getDiagram--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Diagram](../../com.aspose.diagram/diagram) |  |

### setEvent(Event value) {#setEvent-com.aspose.diagram.Event-}
```
public void setEvent(Event value)
```


For the description of this property, please see [getEvent()](../../com.aspose.diagram/shape\#getEvent--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Event](../../com.aspose.diagram/event) |  |

### setFillStyle(StyleSheet value) {#setFillStyle-com.aspose.diagram.StyleSheet-}
```
public void setFillStyle(StyleSheet value)
```


For the description of this property, please see [getFillStyle()](../../com.aspose.diagram/shape\#getFillStyle--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setHeight(double height) {#setHeight-double-}
```
public void setHeight(double height)
```


Sets new height of shape.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| height | double | New heightdouble. |

### setID(long value) {#setID-long-}
```
public void setID(long value)
```


For the description of this property, please see [getID()](../../com.aspose.diagram/shape\#getID--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### setLineStyle(StyleSheet value) {#setLineStyle-com.aspose.diagram.StyleSheet-}
```
public void setLineStyle(StyleSheet value)
```


For the description of this property, please see [getLineStyle()](../../com.aspose.diagram/shape\#getLineStyle--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setMaster(Master value) {#setMaster-com.aspose.diagram.Master-}
```
public void setMaster(Master value)
```


For the description of this property, please see [getMaster()](../../com.aspose.diagram/shape\#getMaster--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Master](../../com.aspose.diagram/master) |  |

### setMasterShape(Shape value) {#setMasterShape-com.aspose.diagram.Shape-}
```
public void setMasterShape(Shape value)
```


For the description of this property, please see [getMasterShape()](../../com.aspose.diagram/shape\#getMasterShape--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Shape](../../com.aspose.diagram/shape) |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


For the description of this property, please see [getName()](../../com.aspose.diagram/shape\#getName--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


For the description of this property, please see [getNameU()](../../com.aspose.diagram/shape\#getNameU--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setPage(Page value) {#setPage-com.aspose.diagram.Page-}
```
public void setPage(Page value)
```


For the description of this property, please see [getPage()](../../com.aspose.diagram/shape\#getPage--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setParentShape(Shape value) {#setParentShape-com.aspose.diagram.Shape-}
```
public void setParentShape(Shape value)
```


For the description of this property, please see [getParentShape()](../../com.aspose.diagram/shape\#getParentShape--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Shape](../../com.aspose.diagram/shape) |  |

### setPresetTheme(int value) {#setPresetTheme-int-}
```
public void setPresetTheme(int value)
```


Apply a preset theme to this shape

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setPresetThemeQuickStyle(int value) {#setPresetThemeQuickStyle-int-}
```
public void setPresetThemeQuickStyle(int value)
```


Apply a preset theme variant quickstyle to this shape

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setPresetThemeStyleMatrics(int styleIndex, int colorIndex) {#setPresetThemeStyleMatrics-int-int-}
```
public void setPresetThemeStyleMatrics(int styleIndex, int colorIndex)
```


pply a preset theme variant quickstyle to this shape, like theme styles options in shape styles dropdown list

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| styleIndex | int | the row of style matrics |
| colorIndex | int | the column of style matrics |

### setPresetThemeVariant(int value) {#setPresetThemeVariant-int-}
```
public void setPresetThemeVariant(int value)
```


Apply a preset theme variant to this shape

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setProps(PropCollection value) {#setProps-com.aspose.diagram.PropCollection-}
```
public void setProps(PropCollection value)
```


For the description of this property, please see [getProps()](../../com.aspose.diagram/shape\#getProps--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PropCollection](../../com.aspose.diagram/propcollection) |  |

### setText(Text value) {#setText-com.aspose.diagram.Text-}
```
public void setText(Text value)
```


For the description of this property, please see [getText()](../../com.aspose.diagram/shape\#getText--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Text](../../com.aspose.diagram/text) |  |

### setTextStyle(StyleSheet value) {#setTextStyle-com.aspose.diagram.StyleSheet-}
```
public void setTextStyle(StyleSheet value)
```


For the description of this property, please see [getTextStyle()](../../com.aspose.diagram/shape\#getTextStyle--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setTwoD(boolean value) {#setTwoD-boolean-}
```
public void setTwoD(boolean value)
```


For the description of this property, please see [getTwoD()](../../com.aspose.diagram/shape\#getTwoD--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setType(int value) {#setType-int-}
```
public void setType(int value)
```


For the description of this property, please see [getType()](../../com.aspose.diagram/shape\#getType--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


For the description of this property, please see [getUniqueID()](../../com.aspose.diagram/shape\#getUniqueID--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.UUID |  |

### setWidth(double width) {#setWidth-double-}
```
public void setWidth(double width)
```


Sets new width of shape.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | double | New widthdouble. |

### setXForm(XForm value) {#setXForm-com.aspose.diagram.XForm-}
```
public void setXForm(XForm value)
```


For the description of this property, please see [getXForm()](../../com.aspose.diagram/shape\#getXForm--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XForm](../../com.aspose.diagram/xform) |  |

### setXForm1D(XForm1D value) {#setXForm1D-com.aspose.diagram.XForm1D-}
```
public void setXForm1D(XForm1D value)
```


For the description of this property, please see [getXForm1D()](../../com.aspose.diagram/shape\#getXForm1D--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XForm1D](../../com.aspose.diagram/xform1d) |  |

### toHTML(InputStream stream, HTMLSaveOptions options) {#toHTML-java.io.InputStream-com.aspose.diagram.HTMLSaveOptions-}
```
public void toHTML(InputStream stream, HTMLSaveOptions options)
```


Creates the shape html and saves it to a stream in the specified format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The output stream. |
| options | [HTMLSaveOptions](../../com.aspose.diagram/htmlsaveoptions) | Addtional html creation options |

### toHTML(OutputStream stream, HTMLSaveOptions options) {#toHTML-java.io.OutputStream-com.aspose.diagram.HTMLSaveOptions-}
```
public void toHTML(OutputStream stream, HTMLSaveOptions options)
```


Creates the shape html and saves it to a stream in the specified format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The output stream. |
| options | [HTMLSaveOptions](../../com.aspose.diagram/htmlsaveoptions) | Addtional html creation options |

### toHTML(String fileName, HTMLSaveOptions options) {#toHTML-java.lang.String-com.aspose.diagram.HTMLSaveOptions-}
```
public void toHTML(String fileName, HTMLSaveOptions options)
```


Creates the html and saves it to a file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String |  |
| options | [HTMLSaveOptions](../../com.aspose.diagram/htmlsaveoptions) | html save options |

### toImage(InputStream stream, ImageSaveOptions options) {#toImage-java.io.InputStream-com.aspose.diagram.ImageSaveOptions-}
```
public void toImage(InputStream stream, ImageSaveOptions options)
```


Creates the shape image and saves it to a stream in the specified format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The output stream. |
| options | [ImageSaveOptions](../../com.aspose.diagram/imagesaveoptions) | Additional image creation options |

### toImage(OutputStream stream, ImageSaveOptions options) {#toImage-java.io.OutputStream-com.aspose.diagram.ImageSaveOptions-}
```
public void toImage(OutputStream stream, ImageSaveOptions options)
```


Creates the shape image and saves it to a stream in the specified format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The output stream. |
| options | [ImageSaveOptions](../../com.aspose.diagram/imagesaveoptions) | Additional image creation options |

### toImage(String imageFile, ImageSaveOptions options) {#toImage-java.lang.String-com.aspose.diagram.ImageSaveOptions-}
```
public void toImage(String imageFile, ImageSaveOptions options)
```


Creates the shape image and saves it to a file. The extension of the file name determines the format of the image.

The format of the image is specified by using the extension of the file name. For example, if you specify "myfile.png", then the image will be saved in the PNG format. The following file extensions are recognized: .bmp, .gif, .png, .jpg, .jpeg, .tiff, .tif, .emf.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageFile | java.lang.String | The image file name with full path. |
| options | [ImageSaveOptions](../../com.aspose.diagram/imagesaveoptions) | Additional image creation options |

### toPdf(InputStream stream) {#toPdf-java.io.InputStream-}
```
public void toPdf(InputStream stream)
```


Creates the shape pdf and saves it to a stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The output stream. |

### toPdf(OutputStream stream) {#toPdf-java.io.OutputStream-}
```
public void toPdf(OutputStream stream)
```


Creates the shape pdf and saves it to a stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The output stream. |

### toPdf(String fileName) {#toPdf-java.lang.String-}
```
public void toPdf(String fileName)
```


Saves the shape to a pdf file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | the pdf file name with full path |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### toSvg(String imageFile, SVGSaveOptions options) {#toSvg-java.lang.String-com.aspose.diagram.SVGSaveOptions-}
```
public void toSvg(String imageFile, SVGSaveOptions options)
```


Saves the shape to a svg file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageFile | java.lang.String |  |
| options | [SVGSaveOptions](../../com.aspose.diagram/svgsaveoptions) |  |

### ungroup() {#ungroup--}
```
public void ungroup()
```


Ungroup Shape

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

