---
title: Page
second_title: Aspose.Diagram for Java API Reference
description: Contains elements that define a page in the document.
type: docs
weight: 263
url: /java/com.aspose.diagram/page/
---

**Inheritance:**
java.lang.Object
```
public class Page
```

Contains elements that define a page in the document.
## Constructors

| Constructor | Description |
| --- | --- |
| [Page()](#Page--) | Constructor. |
| [Page(int ID)](#Page-int-) | Constructor. |
## Methods

| Method | Description |
| --- | --- |
| [addActiveXControl(int type, double pinX, double pinY, double width, double height)](#addActiveXControl-int-double-double-double-double-) | Creates an Activex Control. |
| [addComment(Shape shape, String comment)](#addComment-com.aspose.diagram.Shape-java.lang.String-) | Adds comment to a shape. |
| [addComment(double pinX, double pinY, String comment)](#addComment-double-double-java.lang.String-) | Adds comment with defined PinX and PinY. |
| [addComment(long shapeID, String comment)](#addComment-long-java.lang.String-) | Adds comment to a shape with shape's id. |
| [addShape(Shape newShape, String masterName)](#addShape-com.aspose.diagram.Shape-java.lang.String-) | Adds shape created by master to specific page. |
| [addShape(double pinX, double pinY, double width, double height, InputStream stream)](#addShape-double-double-double-double-java.io.InputStream-) |  |
| [addShape(double pinX, double pinY, double width, double height, InputStream imageStream, InputStream objectDataStream)](#addShape-double-double-double-double-java.io.InputStream-java.io.InputStream-) |  |
| [addShape(double pinX, double pinY, double width, double height, String masterName)](#addShape-double-double-double-double-java.lang.String-) | Adds shape created by master on page with defined PinX,PinY,Width and Height. |
| [addShape(double pinX, double pinY, String masterName)](#addShape-double-double-java.lang.String-) | Adds shape created by master on page with defined PinX and PinY. |
| [addText(double pinX, double pinY, double width, double height, String text)](#addText-double-double-double-double-java.lang.String-) | Adds Text with defined PinX and PinY. |
| [addText(double pinX, double pinY, double width, double height, String text, String fontName, String fontColor, double size)](#addText-double-double-double-double-java.lang.String-java.lang.String-java.lang.String-double-) | Adds Text with defined PinX and PinY. |
| [applyStyle(int textStyle, int lineStyle, int fillStyle)](#applyStyle-int-int-int-) | Applies style for full page. |
| [autoSpaceShapes(ShapeCollection shapes, AutoSpaceOptions options)](#autoSpaceShapes-com.aspose.diagram.ShapeCollection-com.aspose.diagram.AutoSpaceOptions-) | Auto space shapes |
| [bringForward(long shapeId)](#bringForward-long-) | Brings a shape,defined by ID, forward one position in the z-order. |
| [bringToFront(long shapeId)](#bringToFront-long-) | Brings a shape,defined by ID, to the front of the z-order. |
| [centerDrawing()](#centerDrawing--) | Centers a page's shapes with respect to the extent of the page. |
| [connectShapesViaConnector(Shape shapeFrom, int placeFrom, Shape shapeTo, int placeTo, Shape connector)](#connectShapesViaConnector-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-) | Connect shapes via connector. |
| [connectShapesViaConnector(long shapeFromId, int placeFrom, long shapeToId, int placeTo, long connectorId)](#connectShapesViaConnector-long-int-long-int-long-) | Connect shapes via connector. |
| [connectShapesViaConnector(long shapeFromId, String fromConnectionName, long shapeToId, String toConnectionName, long connectorId)](#connectShapesViaConnector-long-java.lang.String-long-java.lang.String-long-) | Connect shapes via connector. |
| [connectShapesViaConnectorIndex(Shape shapeFrom, int fromIndex, Shape shapeTo, int toIndex, Shape connector)](#connectShapesViaConnectorIndex-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-) | Connect shapes via connector index. |
| [connectShapesViaConnectorIndex(long shapeFromId, int fromIndex, long shapeToId, int toIndex, long connectorId)](#connectShapesViaConnectorIndex-long-int-long-int-long-) | Connect shapes via connector index. |
| [copy(Page source)](#copy-com.aspose.diagram.Page-) |  |
| [dispose()](#dispose--) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [drawEllipse(double pinX, double pinY, double width, double height)](#drawEllipse-double-double-double-double-) | The process of drawing Ellipse. |
| [drawLine(double beginX, double beginY, double endX, double endY)](#drawLine-double-double-double-double-) | The process of drawing a single line. |
| [drawLine(double pinX, double pinY, double width, double height, double[] xyArray)](#drawLine-double-double-double-double-double---) | The process of drawing line. |
| [drawPolyline(double pinX, double pinY, double width, double height, double[] xyArray)](#drawPolyline-double-double-double-double-double---) | The process of drawing Polyline. |
| [drawRectangle(double pinX, double pinY, double width, double height)](#drawRectangle-double-double-double-double-) | The process of drawing rectangle. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAssociatedPage()](#getAssociatedPage--) | The ID of the original drawing page that was marked up on separate markup overlays by reviewers of the drawing. |
| [getBackPage()](#getBackPage--) | The page's background page. |
| [getBackground()](#getBackground--) | A flag indicating if the page is a background page. |
| [getClass()](#getClass--) |  |
| [getConnects()](#getConnects--) | Contains a Connect element for each connection between two shapes in a drawing. |
| [getID()](#getID--) | The unique ID of the element within its parent element. |
| [getName()](#getName--) | The name of the element. |
| [getNameU()](#getNameU--) | The universal name of the element. |
| [getPageSheet()](#getPageSheet--) | Contains elements that define the page sheet for a Page or Master element. |
| [getPages()](#getPages--) | Page collection. |
| [getReviewerID()](#getReviewerID--) | The ID of the reviewer associated with the markup overlay. |
| [getShapes()](#getShapes--) | Shape collection. |
| [getViewCenterX()](#getViewCenterX--) | ViewCenterX and ViewCenterY specify a center point on a page that a new view (window) assumes when it is opened initially. |
| [getViewCenterY()](#getViewCenterY--) | ViewCenterX and ViewCenterY specify a center point on a page that a new view (window) assumes when it is opened initially. |
| [getViewScale()](#getViewScale--) | The default magnification factor to use when a new view (window) of the page is opened. |
| [glueShapeToConnectorBeginX(long shapeFromId, String connectionName, long connectorId)](#glueShapeToConnectorBeginX-long-java.lang.String-long-) | Glue shape to Connector's BeginX |
| [glueShapeToConnectorEndX(long shapeToId, String connectionName, long connectorId)](#glueShapeToConnectorEndX-long-java.lang.String-long-) | Glue shape to Connector's EndX |
| [glueShapes(Shape shapeFrom, int placeTo, Shape shapeTo)](#glueShapes-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-) | Glue shapes. |
| [glueShapes(long shapeFromId, int placeTo, long shapeToId)](#glueShapes-long-int-long-) | Glue shapes |
| [glueShapesInContainer(long shapeFromId, int shapeToBeginConnectionIndex, int shapeToEndConnectionIndex, long shapeToId)](#glueShapesInContainer-long-int-int-long-) | Glue shapes in container |
| [glueShapesInContainer(long shapeFromId, String shapeToBeginConnectionName, String shapeToEndConnectionName, long shapeToId)](#glueShapesInContainer-long-java.lang.String-java.lang.String-long-) | Glue shapes in container using connection name |
| [glueShapesInContainerByID(long shapeFromId, int shapeToBeginConnectionID, int shapeToEndConnectionID, long shapeToId)](#glueShapesInContainerByID-long-int-int-long-) | Glue shapes by connection id in container |
| [hashCode()](#hashCode--) |  |
| [layout(LayoutOptions options)](#layout-com.aspose.diagram.LayoutOptions-) | Lays out the shapes and/or reroutes the connectors for the page. |
| [moveTo(int index)](#moveTo-int-) | Moves the page to another location in the pages. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [sendBackward(long shapeId)](#sendBackward-long-) | Moves a shape,defined by ID, back one position in the z-order. |
| [sendToBack(long shapeId)](#sendToBack-long-) | Moves a shape,defined by ID, to the back of the z-order. |
| [setAssociatedPage(Page value)](#setAssociatedPage-com.aspose.diagram.Page-) | For the description of this property, please see [getAssociatedPage()](../../com.aspose.diagram/page\#getAssociatedPage--) |
| [setBackPage(Page value)](#setBackPage-com.aspose.diagram.Page-) | For the description of this property, please see [getBackPage()](../../com.aspose.diagram/page\#getBackPage--) |
| [setBackground(int value)](#setBackground-int-) | For the description of this property, please see [getBackground()](../../com.aspose.diagram/page\#getBackground--) |
| [setID(int value)](#setID-int-) | For the description of this property, please see [getID()](../../com.aspose.diagram/page\#getID--) |
| [setName(String value)](#setName-java.lang.String-) | For the description of this property, please see [getName()](../../com.aspose.diagram/page\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | For the description of this property, please see [getNameU()](../../com.aspose.diagram/page\#getNameU--) |
| [setPages(PageCollection value)](#setPages-com.aspose.diagram.PageCollection-) | For the description of this property, please see [getPages()](../../com.aspose.diagram/page\#getPages--) |
| [setPresetTheme(int value)](#setPresetTheme-int-) | Apply a preset theme to this page |
| [setPresetThemeQuickStyle(int value)](#setPresetThemeQuickStyle-int-) | Apply a preset theme variant quickstyle to this page |
| [setPresetThemeVariant(int value)](#setPresetThemeVariant-int-) | Apply a preset theme variant to this page |
| [setReviewerID(int value)](#setReviewerID-int-) | For the description of this property, please see [getReviewerID()](../../com.aspose.diagram/page\#getReviewerID--) |
| [setViewCenterX(double value)](#setViewCenterX-double-) | For the description of this property, please see [getViewCenterX()](../../com.aspose.diagram/page\#getViewCenterX--) |
| [setViewCenterY(double value)](#setViewCenterY-double-) | For the description of this property, please see [getViewCenterY()](../../com.aspose.diagram/page\#getViewCenterY--) |
| [setViewScale(double value)](#setViewScale-double-) | For the description of this property, please see [getViewScale()](../../com.aspose.diagram/page\#getViewScale--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Page() {#Page--}
```
public Page()
```


Constructor.

### Page(int ID) {#Page-int-}
```
public Page(int ID)
```


Constructor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ID | int |  |

### addActiveXControl(int type, double pinX, double pinY, double width, double height) {#addActiveXControl-int-double-double-double-double-}
```
public long addActiveXControl(int type, double pinX, double pinY, double width, double height)
```


Creates an Activex Control.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | The type of the control. |
| pinX | double | Specifies the x-coordinate of the shape's pin (center of rotation) in relation to the page. |
| pinY | double | Specifies the y-coordinate of the shape's pin (center of rotation) in relation to the page. |
| width | double | Specifies the width of the shape in inches. |
| height | double | Specifies the height of the shape in inches. |

**Returns:**
long - 
### addComment(Shape shape, String comment) {#addComment-com.aspose.diagram.Shape-java.lang.String-}
```
public void addComment(Shape shape, String comment)
```


Adds comment to a shape.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) | Specifies the shape which is adding comment . |
| comment | java.lang.String | Comment's string. |

### addComment(double pinX, double pinY, String comment) {#addComment-double-double-java.lang.String-}
```
public void addComment(double pinX, double pinY, String comment)
```


Adds comment with defined PinX and PinY.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pinX | double | Specifies the x-coordinate of the comment's pin (center of rotation) in relation to the page. |
| pinY | double | Specifies the y-coordinate of the comment's pin (center of rotation) in relation to the page. |
| comment | java.lang.String | Comment's string. |

### addComment(long shapeID, String comment) {#addComment-long-java.lang.String-}
```
public void addComment(long shapeID, String comment)
```


Adds comment to a shape with shape's id.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeID | long |  |
| comment | java.lang.String | Comment's string. |

### addShape(Shape newShape, String masterName) {#addShape-com.aspose.diagram.Shape-java.lang.String-}
```
public long addShape(Shape newShape, String masterName)
```


Adds shape created by master to specific page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newShape | [Shape](../../com.aspose.diagram/shape) | New shape object[Shape](../../com.aspose.diagram/shape). |
| masterName | java.lang.String | Master's name. |

**Returns:**
long - The unique ID of the shape within shapes collection on the specified page.
### addShape(double pinX, double pinY, double width, double height, InputStream stream) {#addShape-double-double-double-double-java.io.InputStream-}
```
public long addShape(double pinX, double pinY, double width, double height, InputStream stream)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pinX | double |  |
| pinY | double |  |
| width | double |  |
| height | double |  |
| stream | java.io.InputStream |  |

**Returns:**
long
### addShape(double pinX, double pinY, double width, double height, InputStream imageStream, InputStream objectDataStream) {#addShape-double-double-double-double-java.io.InputStream-java.io.InputStream-}
```
public long addShape(double pinX, double pinY, double width, double height, InputStream imageStream, InputStream objectDataStream)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pinX | double |  |
| pinY | double |  |
| width | double |  |
| height | double |  |
| imageStream | java.io.InputStream |  |
| objectDataStream | java.io.InputStream |  |

**Returns:**
long
### addShape(double pinX, double pinY, double width, double height, String masterName) {#addShape-double-double-double-double-java.lang.String-}
```
public long addShape(double pinX, double pinY, double width, double height, String masterName)
```


Adds shape created by master on page with defined PinX,PinY,Width and Height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pinX | double | Specifies the x-coordinate of the shape's pin (center of rotation) in relation to the page. |
| pinY | double | Specifies the y-coordinate of the shape's pin (center of rotation) in relation to the page. |
| width | double | Specifies the width of the shape in inches. |
| height | double | Specifies the height of the shape in inches. |
| masterName | java.lang.String | Master's name. |

**Returns:**
long - The unique ID of the shape within shapes collection on the specified page.
### addShape(double pinX, double pinY, String masterName) {#addShape-double-double-java.lang.String-}
```
public long addShape(double pinX, double pinY, String masterName)
```


Adds shape created by master on page with defined PinX and PinY.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pinX | double | Specifies the x-coordinate of the shape's pin (center of rotation) in relation to the page. |
| pinY | double | Specifies the y-coordinate of the shape's pin (center of rotation) in relation to the page. |
| masterName | java.lang.String | Master's name. |

**Returns:**
long - The unique ID of the shape within shapes collection on the specified page.
### addText(double pinX, double pinY, double width, double height, String text) {#addText-double-double-double-double-java.lang.String-}
```
public Shape addText(double pinX, double pinY, double width, double height, String text)
```


Adds Text with defined PinX and PinY.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pinX | double | Specifies the x-coordinate of the text's pin (center of rotation) in relation to the page. |
| pinY | double | Specifies the y-coordinate of the text's pin (center of rotation) in relation to the page. |
| width | double |  |
| height | double |  |
| text | java.lang.String | text string. |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - Returns a shape object that represents the new text object.
### addText(double pinX, double pinY, double width, double height, String text, String fontName, String fontColor, double size) {#addText-double-double-double-double-java.lang.String-java.lang.String-java.lang.String-double-}
```
public Shape addText(double pinX, double pinY, double width, double height, String text, String fontName, String fontColor, double size)
```


Adds Text with defined PinX and PinY.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pinX | double | Specifies the x-coordinate of the text's pin (center of rotation) in relation to the page. |
| pinY | double | Specifies the y-coordinate of the text's pin (center of rotation) in relation to the page. |
| width | double | Specifies the width of the text. |
| height | double | Specifies the height of the text. |
| text | java.lang.String | text string. |
| fontName | java.lang.String | text font name. |
| fontColor | java.lang.String | text font color. |
| size | double | text font size. |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - Returns a shape object that represents the new text object.
### applyStyle(int textStyle, int lineStyle, int fillStyle) {#applyStyle-int-int-int-}
```
public void applyStyle(int textStyle, int lineStyle, int fillStyle)
```


Applies style for full page. Default value is -1.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| textStyle | int | text Style id. |
| lineStyle | int | line Style id. |
| fillStyle | int | fill Style id. |

### autoSpaceShapes(ShapeCollection shapes, AutoSpaceOptions options) {#autoSpaceShapes-com.aspose.diagram.ShapeCollection-com.aspose.diagram.AutoSpaceOptions-}
```
public void autoSpaceShapes(ShapeCollection shapes, AutoSpaceOptions options)
```


Auto space shapes

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [ShapeCollection](../../com.aspose.diagram/shapecollection) | Specifies the shapes be auto spaced. |
| options | [AutoSpaceOptions](../../com.aspose.diagram/autospaceoptions) |  |

### bringForward(long shapeId) {#bringForward-long-}
```
public void bringForward(long shapeId)
```


Brings a shape,defined by ID, forward one position in the z-order.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeId | long | ID of shape.long |

### bringToFront(long shapeId) {#bringToFront-long-}
```
public void bringToFront(long shapeId)
```


Brings a shape,defined by ID, to the front of the z-order.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeId | long | ID of shape.long |

### centerDrawing() {#centerDrawing--}
```
public void centerDrawing()
```


Centers a page's shapes with respect to the extent of the page. Centering shapes does not change their position relative to each other.

### connectShapesViaConnector(Shape shapeFrom, int placeFrom, Shape shapeTo, int placeTo, Shape connector) {#connectShapesViaConnector-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-}
```
public void connectShapesViaConnector(Shape shapeFrom, int placeFrom, Shape shapeTo, int placeTo, Shape connector)
```


Connect shapes via connector.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeFrom | [Shape](../../com.aspose.diagram/shape) | The shape where the connector begins [Shape](../../com.aspose.diagram/shape). |
| placeFrom | int | The location on the first shape where connector will be connected Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| shapeTo | [Shape](../../com.aspose.diagram/shape) | The shape where the connector ends [Shape](../../com.aspose.diagram/shape). |
| placeTo | int | The location on the second shape where connector will be connected Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| connector | [Shape](../../com.aspose.diagram/shape) | The shape with type Dynamic connector [Shape](../../com.aspose.diagram/shape). |

### connectShapesViaConnector(long shapeFromId, int placeFrom, long shapeToId, int placeTo, long connectorId) {#connectShapesViaConnector-long-int-long-int-long-}
```
public void connectShapesViaConnector(long shapeFromId, int placeFrom, long shapeToId, int placeTo, long connectorId)
```


Connect shapes via connector.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeFromId | long | The ID of shape where the connector begins [Shape](../../com.aspose.diagram/shape). |
| placeFrom | int | The location on the first shape where connector will be connected Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| shapeToId | long | The ID of shape where the connector ends [Shape](../../com.aspose.diagram/shape). |
| placeTo | int | The location on the second shape where connector will be connected Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| connectorId | long | The ID of shape with type Dynamic connector [Shape](../../com.aspose.diagram/shape). |

### connectShapesViaConnector(long shapeFromId, String fromConnectionName, long shapeToId, String toConnectionName, long connectorId) {#connectShapesViaConnector-long-java.lang.String-long-java.lang.String-long-}
```
public void connectShapesViaConnector(long shapeFromId, String fromConnectionName, long shapeToId, String toConnectionName, long connectorId)
```


Connect shapes via connector.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeFromId | long | The ID of shape where the connector begins [Shape](../../com.aspose.diagram/shape). |
| fromConnectionName | java.lang.String | The connection name on the first shape where connector will be connected . |
| shapeToId | long | The ID of shape where the connector ends [Shape](../../com.aspose.diagram/shape). |
| toConnectionName | java.lang.String | The connection name on the second shape where connector will be connected . |
| connectorId | long | The ID of shape with type Dynamic connector [Shape](../../com.aspose.diagram/shape). |

### connectShapesViaConnectorIndex(Shape shapeFrom, int fromIndex, Shape shapeTo, int toIndex, Shape connector) {#connectShapesViaConnectorIndex-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-}
```
public void connectShapesViaConnectorIndex(Shape shapeFrom, int fromIndex, Shape shapeTo, int toIndex, Shape connector)
```


Connect shapes via connector index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeFrom | [Shape](../../com.aspose.diagram/shape) | The shape where the connector begins [Shape](../../com.aspose.diagram/shape). |
| fromIndex | int | The index of the connection on the first shape |
| shapeTo | [Shape](../../com.aspose.diagram/shape) | The shape where the connector ends [Shape](../../com.aspose.diagram/shape). |
| toIndex | int | he index of the connection on the second shape |
| connector | [Shape](../../com.aspose.diagram/shape) | The shape with type Dynamic connector [Shape](../../com.aspose.diagram/shape). |

### connectShapesViaConnectorIndex(long shapeFromId, int fromIndex, long shapeToId, int toIndex, long connectorId) {#connectShapesViaConnectorIndex-long-int-long-int-long-}
```
public void connectShapesViaConnectorIndex(long shapeFromId, int fromIndex, long shapeToId, int toIndex, long connectorId)
```


Connect shapes via connector index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeFromId | long | The ID of shape where the connector begins [Shape](../../com.aspose.diagram/shape). |
| fromIndex | int | The index of the connection on the first shape |
| shapeToId | long | The ID of shape where the connector ends [Shape](../../com.aspose.diagram/shape). |
| toIndex | int | he index of the connection on the second shape |
| connectorId | long | The ID of shape with type Dynamic connector [Shape](../../com.aspose.diagram/shape). |

### copy(Page source) {#copy-com.aspose.diagram.Page-}
```
public void copy(Page source)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [Page](../../com.aspose.diagram/page) |  |

### dispose() {#dispose--}
```
public void dispose()
```


Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

### drawEllipse(double pinX, double pinY, double width, double height) {#drawEllipse-double-double-double-double-}
```
public long drawEllipse(double pinX, double pinY, double width, double height)
```


The process of drawing Ellipse.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pinX | double | Specifies the x-coordinate of the shape's pin (center of rotation) in relation to the page. |
| pinY | double | Specifies the y-coordinate of the shape's pin (center of rotation) in relation to the page. |
| width | double | Specifies the width of the shape |
| height | double | Specifies the height of the shape |

**Returns:**
long - 
### drawLine(double beginX, double beginY, double endX, double endY) {#drawLine-double-double-double-double-}
```
public long drawLine(double beginX, double beginY, double endX, double endY)
```


The process of drawing a single line.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| beginX | double | Specifies the begin x-coordinate of the shape's position in relation to the page. |
| beginY | double | Specifies the begin y-coordinate of the shape's position in relation to the page. |
| endX | double | Specifies the end x-coordinate of the shape's position in relation to the page. |
| endY | double | Specifies the end y-coordinate of the shape's position in relation to the page. |

**Returns:**
long - The unique ID of the shape within shapes collection on the specified page.
### drawLine(double pinX, double pinY, double width, double height, double[] xyArray) {#drawLine-double-double-double-double-double---}
```
public long drawLine(double pinX, double pinY, double width, double height, double[] xyArray)
```


The process of drawing line.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pinX | double | Specifies the x-coordinate of the shape's pin (center of rotation) in relation to the page. |
| pinY | double | Specifies the y-coordinate of the shape's pin (center of rotation) in relation to the page. |
| width | double | Specifies the width of the shape |
| height | double | Specifies the height of the shape |
| xyArray | double[] | An array of alternating x and y values that defines points in the new shape |

**Returns:**
long - The unique ID of the shape within shapes collection on the specified page.
### drawPolyline(double pinX, double pinY, double width, double height, double[] xyArray) {#drawPolyline-double-double-double-double-double---}
```
public long drawPolyline(double pinX, double pinY, double width, double height, double[] xyArray)
```


The process of drawing Polyline.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pinX | double | Specifies the x-coordinate of the shape's pin (center of rotation) in relation to the page. |
| pinY | double | Specifies the y-coordinate of the shape's pin (center of rotation) in relation to the page. |
| width | double | Specifies the width of the shape |
| height | double | Specifies the height of the shape |
| xyArray | double[] | An array of alternating x and y values that defines points in the new shape |

**Returns:**
long - The unique ID of the shape within shapes collection on the specified page.
### drawRectangle(double pinX, double pinY, double width, double height) {#drawRectangle-double-double-double-double-}
```
public long drawRectangle(double pinX, double pinY, double width, double height)
```


The process of drawing rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pinX | double | Specifies the x-coordinate of the shape's pin (center of rotation) in relation to the page. |
| pinY | double | Specifies the y-coordinate of the shape's pin (center of rotation) in relation to the page. |
| width | double | Specifies the width of the shape |
| height | double | Specifies the height of the shape |

**Returns:**
long - The unique ID of the shape within shapes collection on the specified page.
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
### getAssociatedPage() {#getAssociatedPage--}
```
public Page getAssociatedPage()
```


The ID of the original drawing page that was marked up on separate markup overlays by reviewers of the drawing.

**Returns:**
[Page](../../com.aspose.diagram/page)
### getBackPage() {#getBackPage--}
```
public Page getBackPage()
```


The page's background page.

**Returns:**
[Page](../../com.aspose.diagram/page)
### getBackground() {#getBackground--}
```
public int getBackground()
```


A flag indicating if the page is a background page.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConnects() {#getConnects--}
```
public ConnectCollection getConnects()
```


Contains a Connect element for each connection between two shapes in a drawing.

**Returns:**
[ConnectCollection](../../com.aspose.diagram/connectcollection)
### getID() {#getID--}
```
public int getID()
```


The unique ID of the element within its parent element.

**Returns:**
int
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
### getPageSheet() {#getPageSheet--}
```
public PageSheet getPageSheet()
```


Contains elements that define the page sheet for a Page or Master element.

**Returns:**
[PageSheet](../../com.aspose.diagram/pagesheet)
### getPages() {#getPages--}
```
public PageCollection getPages()
```


Page collection.

**Returns:**
[PageCollection](../../com.aspose.diagram/pagecollection)
### getReviewerID() {#getReviewerID--}
```
public int getReviewerID()
```


The ID of the reviewer associated with the markup overlay.

**Returns:**
int
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


Shape collection.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getViewCenterX() {#getViewCenterX--}
```
public double getViewCenterX()
```


ViewCenterX and ViewCenterY specify a center point on a page that a new view (window) assumes when it is opened initially.

**Returns:**
double
### getViewCenterY() {#getViewCenterY--}
```
public double getViewCenterY()
```


ViewCenterX and ViewCenterY specify a center point on a page that a new view (window) assumes when it is opened initially.

**Returns:**
double
### getViewScale() {#getViewScale--}
```
public double getViewScale()
```


The default magnification factor to use when a new view (window) of the page is opened. For example, 1 = 100%; 1.5 = 150%, and so on.

**Returns:**
double
### glueShapeToConnectorBeginX(long shapeFromId, String connectionName, long connectorId) {#glueShapeToConnectorBeginX-long-java.lang.String-long-}
```
public void glueShapeToConnectorBeginX(long shapeFromId, String connectionName, long connectorId)
```


Glue shape to Connector's BeginX

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeFromId | long | The ID of shape where the connector begins [Shape](../../com.aspose.diagram/shape). |
| connectionName | java.lang.String | The connection name on the shape where connector will be connected . |
| connectorId | long | The ID of shape with type Dynamic connector [Shape](../../com.aspose.diagram/shape). |

### glueShapeToConnectorEndX(long shapeToId, String connectionName, long connectorId) {#glueShapeToConnectorEndX-long-java.lang.String-long-}
```
public void glueShapeToConnectorEndX(long shapeToId, String connectionName, long connectorId)
```


Glue shape to Connector's EndX

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeToId | long | The ID of shape where the connector ends [Shape](../../com.aspose.diagram/shape). |
| connectionName | java.lang.String | The connection name on the second shape where connector will be connected . |
| connectorId | long | The ID of shape with type Dynamic connector [Shape](../../com.aspose.diagram/shape). |

### glueShapes(Shape shapeFrom, int placeTo, Shape shapeTo) {#glueShapes-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-}
```
public void glueShapes(Shape shapeFrom, int placeTo, Shape shapeTo)
```


Glue shapes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeFrom | [Shape](../../com.aspose.diagram/shape) | The shape which is glue from [Shape](../../com.aspose.diagram/shape). |
| placeTo | int | The location on the first shape where to glue Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| shapeTo | [Shape](../../com.aspose.diagram/shape) | The shape where to glue to [Shape](../../com.aspose.diagram/shape). |

### glueShapes(long shapeFromId, int placeTo, long shapeToId) {#glueShapes-long-int-long-}
```
public void glueShapes(long shapeFromId, int placeTo, long shapeToId)
```


Glue shapes

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeFromId | long | The ID of shape which is glue from [Shape](../../com.aspose.diagram/shape). |
| placeTo | int | The location on the first shape where to glue Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| shapeToId | long | The ID of shape where to glue to [Shape](../../com.aspose.diagram/shape). |

### glueShapesInContainer(long shapeFromId, int shapeToBeginConnectionIndex, int shapeToEndConnectionIndex, long shapeToId) {#glueShapesInContainer-long-int-int-long-}
```
public void glueShapesInContainer(long shapeFromId, int shapeToBeginConnectionIndex, int shapeToEndConnectionIndex, long shapeToId)
```


Glue shapes in container

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeFromId | long | The ID of shape which is glue from [Shape](../../com.aspose.diagram/shape). |
| shapeToBeginConnectionIndex | int | The location on the first connection index where to glue . |
| shapeToEndConnectionIndex | int | The location on the end connection index where to glue . |
| shapeToId | long | The ID of shape where to glue to [Shape](../../com.aspose.diagram/shape). |

### glueShapesInContainer(long shapeFromId, String shapeToBeginConnectionName, String shapeToEndConnectionName, long shapeToId) {#glueShapesInContainer-long-java.lang.String-java.lang.String-long-}
```
public void glueShapesInContainer(long shapeFromId, String shapeToBeginConnectionName, String shapeToEndConnectionName, long shapeToId)
```


Glue shapes in container using connection name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeFromId | long | The ID of shape which is glue from [Shape](../../com.aspose.diagram/shape). |
| shapeToBeginConnectionName | java.lang.String | The location on the first connection name where to glue . |
| shapeToEndConnectionName | java.lang.String | The location on the end connection name where to glue . |
| shapeToId | long | The ID of shape where to glue to [Shape](../../com.aspose.diagram/shape). |

### glueShapesInContainerByID(long shapeFromId, int shapeToBeginConnectionID, int shapeToEndConnectionID, long shapeToId) {#glueShapesInContainerByID-long-int-int-long-}
```
public void glueShapesInContainerByID(long shapeFromId, int shapeToBeginConnectionID, int shapeToEndConnectionID, long shapeToId)
```


Glue shapes by connection id in container

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeFromId | long | The ID of shape which is glue from [Shape](../../com.aspose.diagram/shape). |
| shapeToBeginConnectionID | int | The location on the first connection id where to glue . |
| shapeToEndConnectionID | int | The location on the end connection id where to glue . |
| shapeToId | long | The ID of shape where to glue to [Shape](../../com.aspose.diagram/shape). |

### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### layout(LayoutOptions options) {#layout-com.aspose.diagram.LayoutOptions-}
```
public void layout(LayoutOptions options)
```


Lays out the shapes and/or reroutes the connectors for the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [LayoutOptions](../../com.aspose.diagram/layoutoptions) | Using the [LayoutOptions](../../com.aspose.diagram/layoutoptions) to configure options of layout. |

### moveTo(int index) {#moveTo-int-}
```
public void moveTo(int index)
```


Moves the page to another location in the pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Destination page index. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### sendBackward(long shapeId) {#sendBackward-long-}
```
public void sendBackward(long shapeId)
```


Moves a shape,defined by ID, back one position in the z-order.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeId | long | ID of shape.long |

### sendToBack(long shapeId) {#sendToBack-long-}
```
public void sendToBack(long shapeId)
```


Moves a shape,defined by ID, to the back of the z-order.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeId | long | ID of shape.long |

### setAssociatedPage(Page value) {#setAssociatedPage-com.aspose.diagram.Page-}
```
public void setAssociatedPage(Page value)
```


For the description of this property, please see [getAssociatedPage()](../../com.aspose.diagram/page\#getAssociatedPage--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setBackPage(Page value) {#setBackPage-com.aspose.diagram.Page-}
```
public void setBackPage(Page value)
```


For the description of this property, please see [getBackPage()](../../com.aspose.diagram/page\#getBackPage--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setBackground(int value) {#setBackground-int-}
```
public void setBackground(int value)
```


For the description of this property, please see [getBackground()](../../com.aspose.diagram/page\#getBackground--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


For the description of this property, please see [getID()](../../com.aspose.diagram/page\#getID--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


For the description of this property, please see [getName()](../../com.aspose.diagram/page\#getName--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


For the description of this property, please see [getNameU()](../../com.aspose.diagram/page\#getNameU--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setPages(PageCollection value) {#setPages-com.aspose.diagram.PageCollection-}
```
public void setPages(PageCollection value)
```


For the description of this property, please see [getPages()](../../com.aspose.diagram/page\#getPages--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PageCollection](../../com.aspose.diagram/pagecollection) |  |

### setPresetTheme(int value) {#setPresetTheme-int-}
```
public void setPresetTheme(int value)
```


Apply a preset theme to this page

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setPresetThemeQuickStyle(int value) {#setPresetThemeQuickStyle-int-}
```
public void setPresetThemeQuickStyle(int value)
```


Apply a preset theme variant quickstyle to this page

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setPresetThemeVariant(int value) {#setPresetThemeVariant-int-}
```
public void setPresetThemeVariant(int value)
```


Apply a preset theme variant to this page

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setReviewerID(int value) {#setReviewerID-int-}
```
public void setReviewerID(int value)
```


For the description of this property, please see [getReviewerID()](../../com.aspose.diagram/page\#getReviewerID--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setViewCenterX(double value) {#setViewCenterX-double-}
```
public void setViewCenterX(double value)
```


For the description of this property, please see [getViewCenterX()](../../com.aspose.diagram/page\#getViewCenterX--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setViewCenterY(double value) {#setViewCenterY-double-}
```
public void setViewCenterY(double value)
```


For the description of this property, please see [getViewCenterY()](../../com.aspose.diagram/page\#getViewCenterY--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setViewScale(double value) {#setViewScale-double-}
```
public void setViewScale(double value)
```


For the description of this property, please see [getViewScale()](../../com.aspose.diagram/page\#getViewScale--)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

