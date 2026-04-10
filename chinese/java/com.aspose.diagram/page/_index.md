---
title: 页面
second_title: Aspose.Diagram for Java API 参考
description: 包含定义文档页面的元素。
type: docs
weight: 260
url: /zh/java/com.aspose.diagram/page/
---

**Inheritance:**
java.lang.Object
```
public class Page
```

包含定义文档页面的元素。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Page()](#Page--) | 构造函数。 |
| [Page(int ID)](#Page-int-) | 构造函数。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [addActiveXControl(int type, double pinX, double pinY, double width, double height)](#addActiveXControl-int-double-double-double-double-) | 创建一个 Activex 控件。 |
| [addComment(Shape shape, String comment)](#addComment-com.aspose.diagram.Shape-java.lang.String-) | 向形状添加注释。 |
| [addComment(double pinX, double pinY, String comment)](#addComment-double-double-java.lang.String-) | 添加带有定义的 PinX 和 PinY 的注释。 |
| [addComment(long shapeID, String comment)](#addComment-long-java.lang.String-) | 向形状（使用形状的 ID）添加注释。 |
| [addShape(Shape newShape, String masterName)](#addShape-com.aspose.diagram.Shape-java.lang.String-) | 将由母版创建的形状添加到指定页面。 |
| [addShape(double pinX, double pinY, double width, double height, InputStream stream)](#addShape-double-double-double-double-java.io.InputStream-) |  |
| [addShape(double pinX, double pinY, double width, double height, InputStream imageStream, InputStream objectDataStream)](#addShape-double-double-double-double-java.io.InputStream-java.io.InputStream-) |  |
| [addShape(double pinX, double pinY, double width, double height, String masterName)](#addShape-double-double-double-double-java.lang.String-) | 在页面上将由母版创建的形状添加，使用定义的 PinX、PinY、宽度和高度。 |
| [addShape(double pinX, double pinY, String masterName)](#addShape-double-double-java.lang.String-) | 在页面上将由母版创建的形状添加，使用定义的 PinX 和 PinY。 |
| [addText(double pinX, double pinY, double width, double height, String text)](#addText-double-double-double-double-java.lang.String-) | 添加带有定义的 PinX 和 PinY 的文本。 |
| [addText(double pinX, double pinY, double width, double height, String text, String fontName, String fontColor, double size)](#addText-double-double-double-double-java.lang.String-java.lang.String-java.lang.String-double-) | 添加带有定义的 PinX 和 PinY 的文本。 |
| [applyStyle(int textStyle, int lineStyle, int fillStyle)](#applyStyle-int-int-int-) | 对整页应用样式。 |
| [autoSpaceShapes(ShapeCollection shapes, AutoSpaceOptions options)](#autoSpaceShapes-com.aspose.diagram.ShapeCollection-com.aspose.diagram.AutoSpaceOptions-) | 自动间距形状。 |
| [bringForward(long shapeId)](#bringForward-long-) | 将由 ID 定义的形状在 Z 顺序中向前移动一个位置。 |
| [bringToFront(long shapeId)](#bringToFront-long-) | 将由 ID 定义的形状置于 Z 顺序的最前面。 |
| [centerDrawing()](#centerDrawing--) | 根据页面的范围居中页面上的形状。 |
| [connectShapesViaConnector(Shape shapeFrom, int placeFrom, Shape shapeTo, int placeTo, Shape connector)](#connectShapesViaConnector-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-) | 通过连接器连接形状。 |
| [connectShapesViaConnector(long shapeFromId, int placeFrom, long shapeToId, int placeTo, long connectorId)](#connectShapesViaConnector-long-int-long-int-long-) | 通过连接器连接形状。 |
| [connectShapesViaConnector(long shapeFromId, String fromConnectionName, long shapeToId, String toConnectionName, long connectorId)](#connectShapesViaConnector-long-java.lang.String-long-java.lang.String-long-) | 通过连接器连接形状。 |
| [connectShapesViaConnectorIndex(Shape shapeFrom, int fromIndex, Shape shapeTo, int toIndex, Shape connector)](#connectShapesViaConnectorIndex-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-) | 通过连接器索引连接形状。 |
| [connectShapesViaConnectorIndex(long shapeFromId, int fromIndex, long shapeToId, int toIndex, long connectorId)](#connectShapesViaConnectorIndex-long-int-long-int-long-) | 通过连接器索引连接形状。 |
| [copy(Page source)](#copy-com.aspose.diagram.Page-) |  |
| [dispose()](#dispose--) | 执行应用程序定义的任务，涉及释放、释放或重置非托管资源。 |
| [drawEllipse(double pinX, double pinY, double width, double height)](#drawEllipse-double-double-double-double-) | 绘制椭圆的过程。 |
| [drawLine(double beginX, double beginY, double endX, double endY)](#drawLine-double-double-double-double-) | 绘制单线的过程。 |
| [drawLine(double pinX, double pinY, double width, double height, double[] xyArray)](#drawLine-double-double-double-double-double---) | 绘制线条的过程。 |
| [drawPolyline(double pinX, double pinY, double width, double height, double[] xyArray)](#drawPolyline-double-double-double-double-double---) | 绘制折线的过程。 |
| [drawRectangle(double pinX, double pinY, double width, double height)](#drawRectangle-double-double-double-double-) | 绘制矩形的过程。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAssociatedPage()](#getAssociatedPage--) | 原始绘图页面的 ID，该页面已被绘图审阅者在单独的标注覆盖层上进行标记。 |
| [getBackPage()](#getBackPage--) | 页面的背景页面。 |
| [getBackground()](#getBackground--) | 指示页面是否为背景页的标志。 |
| [getClass()](#getClass--) |  |
| [getConnects()](#getConnects--) | 为绘图中两个形状之间的每个连接包含一个 Connect 元素。 |
| [getID()](#getID--) | 元素在其父元素中的唯一 ID。 |
| [getName()](#getName--) | 元素的名称。 |
| [getNameU()](#getNameU--) | 元素的通用名称。 |
| [getPageSheet()](#getPageSheet--) | 包含定义页面或母版元素的页面工作表的元素。 |
| [getPages()](#getPages--) | 页面集合。 |
| [getReviewerID()](#getReviewerID--) | 与标注覆盖层关联的审阅者的 ID。 |
| [getShapes()](#getShapes--) | 形状集合。 |
| [getViewCenterX()](#getViewCenterX--) | ViewCenterX 和 ViewCenterY 指定页面上的中心点，新视图（窗口）在首次打开时将采用该中心点。 |
| [getViewCenterY()](#getViewCenterY--) | ViewCenterX 和 ViewCenterY 指定页面上的中心点，新视图（窗口）在首次打开时将采用该中心点。 |
| [getViewScale()](#getViewScale--) | 打开页面的新视图（窗口）时使用的默认放大倍率。 |
| [glueShapeToConnectorBeginX(long shapeFromId, String connectionName, long connectorId)](#glueShapeToConnectorBeginX-long-java.lang.String-long-) | 将形状粘贴到连接器的 BeginX。 |
| [glueShapeToConnectorEndX(long shapeToId, String connectionName, long connectorId)](#glueShapeToConnectorEndX-long-java.lang.String-long-) | 将形状粘贴到连接器的 EndX。 |
| [glueShapes(Shape shapeFrom, int placeTo, Shape shapeTo)](#glueShapes-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-) | 粘贴形状。 |
| [glueShapes(long shapeFromId, int placeTo, long shapeToId)](#glueShapes-long-int-long-) | 粘贴形状 |
| [glueShapesInContainer(long shapeFromId, int shapeToBeginConnectionIndex, int shapeToEndConnectionIndex, long shapeToId)](#glueShapesInContainer-long-int-int-long-) | 在容器中粘贴形状 |
| [glueShapesInContainer(long shapeFromId, String shapeToBeginConnectionName, String shapeToEndConnectionName, long shapeToId)](#glueShapesInContainer-long-java.lang.String-java.lang.String-long-) | 使用连接名称在容器中粘贴形状 |
| [glueShapesInContainerByID(long shapeFromId, int shapeToBeginConnectionID, int shapeToEndConnectionID, long shapeToId)](#glueShapesInContainerByID-long-int-int-long-) | 通过连接 ID 在容器中粘贴形状 |
| [hashCode()](#hashCode--) |  |
| [layout(LayoutOptions options)](#layout-com.aspose.diagram.LayoutOptions-) | 为页面布局形状和/或重新路由连接器。 |
| [moveTo(int index)](#moveTo-int-) | 将页面移动到页面列表中的其他位置。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [sendBackward(long shapeId)](#sendBackward-long-) | 将由 ID 定义的形状在 Z 顺序中向后移动一个位置。 |
| [sendToBack(long shapeId)](#sendToBack-long-) | 将由 ID 定义的形状移动到 Z 顺序的最底层。 |
| [setAssociatedPage(Page value)](#setAssociatedPage-com.aspose.diagram.Page-) | 有关此属性的描述，请参阅 [getAssociatedPage()](../../com.aspose.diagram/page\#getAssociatedPage--) |
| [setBackPage(Page value)](#setBackPage-com.aspose.diagram.Page-) | 有关此属性的描述，请参阅 [getBackPage()](../../com.aspose.diagram/page\#getBackPage--) |
| [setBackground(int value)](#setBackground-int-) | 有关此属性的描述，请参阅 [getBackground()](../../com.aspose.diagram/page\#getBackground--) |
| [setID(int value)](#setID-int-) | 有关此属性的描述，请参阅 [getID()](../../com.aspose.diagram/page\#getID--) |
| [setName(String value)](#setName-java.lang.String-) | 有关此属性的描述，请参阅 [getName()](../../com.aspose.diagram/page\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | 有关此属性的描述，请参阅 [getNameU()](../../com.aspose.diagram/page\#getNameU--) |
| [setPages(PageCollection value)](#setPages-com.aspose.diagram.PageCollection-) | 有关此属性的描述，请参阅 [getPages()](../../com.aspose.diagram/page\#getPages--) |
| [setPresetTheme(int value)](#setPresetTheme-int-) | 将预设主题应用于此页面 |
| [setPresetThemeQuickStyle(int value)](#setPresetThemeQuickStyle-int-) | 将预设主题变体快速样式应用于此页面 |
| [setPresetThemeVariant(int value)](#setPresetThemeVariant-int-) | 将预设主题变体应用于此页面 |
| [setReviewerID(int value)](#setReviewerID-int-) | 有关此属性的描述，请参阅 [getReviewerID()](../../com.aspose.diagram/page\#getReviewerID--) |
| [setViewCenterX(double value)](#setViewCenterX-double-) | 有关此属性的描述，请参阅 [getViewCenterX()](../../com.aspose.diagram/page\#getViewCenterX--) |
| [setViewCenterY(double value)](#setViewCenterY-double-) | 有关此属性的描述，请参阅 [getViewCenterY()](../../com.aspose.diagram/page\#getViewCenterY--) |
| [setViewScale(double value)](#setViewScale-double-) | 有关此属性的描述，请参阅 [getViewScale()](../../com.aspose.diagram/page\#getViewScale--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Page() {#Page--}
```
public Page()
```


构造函数。

### Page(int ID) {#Page-int-}
```
public Page(int ID)
```


构造函数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ID | int |  |

### addActiveXControl(int type, double pinX, double pinY, double width, double height) {#addActiveXControl-int-double-double-double-double-}
```
public long addActiveXControl(int type, double pinX, double pinY, double width, double height)
```


创建一个 Activex 控件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 类型 | int | 控件的类型。 |
| pinX | double | 指定相对于页面的形状针（旋转中心）的 X 坐标。 |
| pinY | double | 指定相对于页面的形状针（旋转中心）的 Y 坐标。 |
| width | double | 指定形状的宽度（英寸）。 |
| height | double | 指定形状的高度（英寸）。 |

**Returns:**
long -
### addComment(Shape shape, String comment) {#addComment-com.aspose.diagram.Shape-java.lang.String-}
```
public void addComment(Shape shape, String comment)
```


向形状添加注释。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) | 指定正在添加注释的形状。 |
| comment | java.lang.String | 注释的字符串。 |

### addComment(double pinX, double pinY, String comment) {#addComment-double-double-java.lang.String-}
```
public void addComment(double pinX, double pinY, String comment)
```


添加带有定义的 PinX 和 PinY 的注释。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pinX | double | 指定相对于页面的注释针（旋转中心）的 X 坐标。 |
| pinY | double | 指定相对于页面的注释针（旋转中心）的 Y 坐标。 |
| comment | java.lang.String | 注释的字符串。 |

### addComment(long shapeID, String comment) {#addComment-long-java.lang.String-}
```
public void addComment(long shapeID, String comment)
```


向形状（使用形状的 ID）添加注释。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapeID | long |  |
| comment | java.lang.String | 注释的字符串。 |

### addShape(Shape newShape, String masterName) {#addShape-com.aspose.diagram.Shape-java.lang.String-}
```
public long addShape(Shape newShape, String masterName)
```


将由母版创建的形状添加到指定页面。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newShape | [Shape](../../com.aspose.diagram/shape) | 新的形状对象[Shape](../../com.aspose.diagram/shape)。 |
| masterName | java.lang.String | 母版的名称。 |

**Returns:**
long - 指定页面上形状集合中形状的唯一 ID。
### addShape(double pinX, double pinY, double width, double height, InputStream stream) {#addShape-double-double-double-double-java.io.InputStream-}
```
public long addShape(double pinX, double pinY, double width, double height, InputStream stream)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pinX | double |  |
| pinY | double |  |
| width | double |  |
| height | double |  |
| 流 | java.io.InputStream |  |

**Returns:**
long
### addShape(double pinX, double pinY, double width, double height, InputStream imageStream, InputStream objectDataStream) {#addShape-double-double-double-double-java.io.InputStream-java.io.InputStream-}
```
public long addShape(double pinX, double pinY, double width, double height, InputStream imageStream, InputStream objectDataStream)
```




**Parameters:**
| 参数 | 类型 | 描述 |
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


在页面上将由母版创建的形状添加，使用定义的 PinX、PinY、宽度和高度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pinX | double | 指定相对于页面的形状针（旋转中心）的 X 坐标。 |
| pinY | double | 指定相对于页面的形状针（旋转中心）的 Y 坐标。 |
| width | double | 指定形状的宽度（英寸）。 |
| height | double | 指定形状的高度（英寸）。 |
| masterName | java.lang.String | 母版的名称。 |

**Returns:**
long - 指定页面上形状集合中形状的唯一 ID。
### addShape(double pinX, double pinY, String masterName) {#addShape-double-double-java.lang.String-}
```
public long addShape(double pinX, double pinY, String masterName)
```


在页面上将由母版创建的形状添加，使用定义的 PinX 和 PinY。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pinX | double | 指定相对于页面的形状针（旋转中心）的 X 坐标。 |
| pinY | double | 指定相对于页面的形状针（旋转中心）的 Y 坐标。 |
| masterName | java.lang.String | 母版的名称。 |

**Returns:**
long - 指定页面上形状集合中形状的唯一 ID。
### addText(double pinX, double pinY, double width, double height, String text) {#addText-double-double-double-double-java.lang.String-}
```
public Shape addText(double pinX, double pinY, double width, double height, String text)
```


添加带有定义的 PinX 和 PinY 的文本。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pinX | double | 指定文本针脚（旋转中心）相对于页面的 x 坐标。 |
| pinY | double | 指定文本针脚（旋转中心）相对于页面的 y 坐标。 |
| width | double |  |
| height | double |  |
| text | java.lang.String | 文本字符串。 |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - Returns a shape object that represents the new text object.
### addText(double pinX, double pinY, double width, double height, String text, String fontName, String fontColor, double size) {#addText-double-double-double-double-java.lang.String-java.lang.String-java.lang.String-double-}
```
public Shape addText(double pinX, double pinY, double width, double height, String text, String fontName, String fontColor, double size)
```


添加带有定义的 PinX 和 PinY 的文本。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pinX | double | 指定文本针脚（旋转中心）相对于页面的 x 坐标。 |
| pinY | double | 指定文本针脚（旋转中心）相对于页面的 y 坐标。 |
| width | double | 指定文本的宽度。 |
| height | double | 指定文本的高度。 |
| text | java.lang.String | 文本字符串。 |
| fontName | java.lang.String | 文本字体名称。 |
| fontColor | java.lang.String | 文本字体颜色。 |
| size | double | 文本字体大小。 |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - Returns a shape object that represents the new text object.
### applyStyle(int textStyle, int lineStyle, int fillStyle) {#applyStyle-int-int-int-}
```
public void applyStyle(int textStyle, int lineStyle, int fillStyle)
```


对整页应用样式。默认值为 -1。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| textStyle | int | 文本 Style ID。 |
| lineStyle | int | 线条 Style ID。 |
| fillStyle | int | 填充 Style ID。 |

### autoSpaceShapes(ShapeCollection shapes, AutoSpaceOptions options) {#autoSpaceShapes-com.aspose.diagram.ShapeCollection-com.aspose.diagram.AutoSpaceOptions-}
```
public void autoSpaceShapes(ShapeCollection shapes, AutoSpaceOptions options)
```


自动间距形状。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapes | [ShapeCollection](../../com.aspose.diagram/shapecollection) | 指定形状自动间距。 |
| options | [AutoSpaceOptions](../../com.aspose.diagram/autospaceoptions) |  |

### bringForward(long shapeId) {#bringForward-long-}
```
public void bringForward(long shapeId)
```


将由 ID 定义的形状在 Z 顺序中向前移动一个位置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapeId | long | shape.long 的 ID |

### bringToFront(long shapeId) {#bringToFront-long-}
```
public void bringToFront(long shapeId)
```


将由 ID 定义的形状置于 Z 顺序的最前面。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapeId | long | shape.long 的 ID |

### centerDrawing() {#centerDrawing--}
```
public void centerDrawing()
```


将页面的形状相对于页面的范围居中。居中形状不会改变它们相互之间的位置。

### connectShapesViaConnector(Shape shapeFrom, int placeFrom, Shape shapeTo, int placeTo, Shape connector) {#connectShapesViaConnector-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-}
```
public void connectShapesViaConnector(Shape shapeFrom, int placeFrom, Shape shapeTo, int placeTo, Shape connector)
```


通过连接器连接形状。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapeFrom | [Shape](../../com.aspose.diagram/shape) | 连接器开始的形状 [Shape](../../com.aspose.diagram/shape)。 |
| placeFrom | int | 连接器将在第一形状上连接的位置 Aspose.Diagram.Manipulation.ConnectionPointPlace。 |
| shapeTo | [Shape](../../com.aspose.diagram/shape) | 连接器结束的形状 [Shape](../../com.aspose.diagram/shape)。 |
| placeTo | int | 连接器将在第二形状上连接的位置 Aspose.Diagram.Manipulation.ConnectionPointPlace。 |
| connector | [Shape](../../com.aspose.diagram/shape) | 类型为 Dynamic connector 的形状 [Shape](../../com.aspose.diagram/shape)。 |

### connectShapesViaConnector(long shapeFromId, int placeFrom, long shapeToId, int placeTo, long connectorId) {#connectShapesViaConnector-long-int-long-int-long-}
```
public void connectShapesViaConnector(long shapeFromId, int placeFrom, long shapeToId, int placeTo, long connectorId)
```


通过连接器连接形状。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapeFromId | long | 连接器开始的形状的 ID [Shape](../../com.aspose.diagram/shape)。 |
| placeFrom | int | 连接器将在第一形状上连接的位置 Aspose.Diagram.Manipulation.ConnectionPointPlace。 |
| shapeToId | long | 连接器结束的形状的 ID [Shape](../../com.aspose.diagram/shape)。 |
| placeTo | int | 连接器将在第二形状上连接的位置 Aspose.Diagram.Manipulation.ConnectionPointPlace。 |
| connectorId | long | 类型为 Dynamic connector 的形状的 ID [Shape](../../com.aspose.diagram/shape)。 |

### connectShapesViaConnector(long shapeFromId, String fromConnectionName, long shapeToId, String toConnectionName, long connectorId) {#connectShapesViaConnector-long-java.lang.String-long-java.lang.String-long-}
```
public void connectShapesViaConnector(long shapeFromId, String fromConnectionName, long shapeToId, String toConnectionName, long connectorId)
```


通过连接器连接形状。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapeFromId | long | 连接器开始的形状的 ID [Shape](../../com.aspose.diagram/shape)。 |
| fromConnectionName | java.lang.String | 连接器将在第一形状上连接的连接名称。 |
| shapeToId | long | 连接器结束的形状的 ID [Shape](../../com.aspose.diagram/shape)。 |
| toConnectionName | java.lang.String | 连接器将在第二形状上连接的连接名称。 |
| connectorId | long | 类型为 Dynamic connector 的形状的 ID [Shape](../../com.aspose.diagram/shape)。 |

### connectShapesViaConnectorIndex(Shape shapeFrom, int fromIndex, Shape shapeTo, int toIndex, Shape connector) {#connectShapesViaConnectorIndex-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-}
```
public void connectShapesViaConnectorIndex(Shape shapeFrom, int fromIndex, Shape shapeTo, int toIndex, Shape connector)
```


通过连接器索引连接形状。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapeFrom | [Shape](../../com.aspose.diagram/shape) | 连接器开始的形状 [Shape](../../com.aspose.diagram/shape)。 |
| fromIndex | int | 第一形状上连接的索引 |
| shapeTo | [Shape](../../com.aspose.diagram/shape) | 连接器结束的形状 [Shape](../../com.aspose.diagram/shape)。 |
| toIndex | int | 第二形状上连接的索引 |
| connector | [Shape](../../com.aspose.diagram/shape) | 类型为 Dynamic connector 的形状 [Shape](../../com.aspose.diagram/shape)。 |

### connectShapesViaConnectorIndex(long shapeFromId, int fromIndex, long shapeToId, int toIndex, long connectorId) {#connectShapesViaConnectorIndex-long-int-long-int-long-}
```
public void connectShapesViaConnectorIndex(long shapeFromId, int fromIndex, long shapeToId, int toIndex, long connectorId)
```


通过连接器索引连接形状。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapeFromId | long | 连接器开始的形状的 ID [Shape](../../com.aspose.diagram/shape)。 |
| fromIndex | int | 第一形状上连接的索引 |
| shapeToId | long | 连接器结束的形状的 ID [Shape](../../com.aspose.diagram/shape)。 |
| toIndex | int | 第二形状上连接的索引 |
| connectorId | long | 类型为 Dynamic connector 的形状的 ID [Shape](../../com.aspose.diagram/shape)。 |

### copy(Page source) {#copy-com.aspose.diagram.Page-}
```
public void copy(Page source)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [Page](../../com.aspose.diagram/page) |  |

### dispose() {#dispose--}
```
public void dispose()
```


执行应用程序定义的任务，涉及释放、释放或重置非托管资源。

### drawEllipse(double pinX, double pinY, double width, double height) {#drawEllipse-double-double-double-double-}
```
public long drawEllipse(double pinX, double pinY, double width, double height)
```


绘制椭圆的过程。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pinX | double | 指定相对于页面的形状针（旋转中心）的 X 坐标。 |
| pinY | double | 指定相对于页面的形状针（旋转中心）的 Y 坐标。 |
| width | double | 指定形状的宽度 |
| height | double | 指定形状的高度 |

**Returns:**
long -
### drawLine(double beginX, double beginY, double endX, double endY) {#drawLine-double-double-double-double-}
```
public long drawLine(double beginX, double beginY, double endX, double endY)
```


绘制单线的过程。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| beginX | double | 指定相对于页面的形状位置的起始 x 坐标。 |
| beginY | double | 指定相对于页面的形状位置的起始 y 坐标。 |
| endX | double | 指定相对于页面的形状位置的结束 x 坐标。 |
| endY | double | 指定相对于页面的形状位置的结束 y 坐标。 |

**Returns:**
long - 指定页面上形状集合中形状的唯一 ID。
### drawLine(double pinX, double pinY, double width, double height, double[] xyArray) {#drawLine-double-double-double-double-double---}
```
public long drawLine(double pinX, double pinY, double width, double height, double[] xyArray)
```


绘制线条的过程。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pinX | double | 指定相对于页面的形状针（旋转中心）的 X 坐标。 |
| pinY | double | 指定相对于页面的形状针（旋转中心）的 Y 坐标。 |
| width | double | 指定形状的宽度 |
| height | double | 指定形状的高度 |
| xyArray | double[] | 一个交替的 x 和 y 值数组，用于定义新形状中的点 |

**Returns:**
long - 指定页面上形状集合中形状的唯一 ID。
### drawPolyline(double pinX, double pinY, double width, double height, double[] xyArray) {#drawPolyline-double-double-double-double-double---}
```
public long drawPolyline(double pinX, double pinY, double width, double height, double[] xyArray)
```


绘制折线的过程。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pinX | double | 指定相对于页面的形状针（旋转中心）的 X 坐标。 |
| pinY | double | 指定相对于页面的形状针（旋转中心）的 Y 坐标。 |
| width | double | 指定形状的宽度 |
| height | double | 指定形状的高度 |
| xyArray | double[] | 一个交替的 x 和 y 值数组，用于定义新形状中的点 |

**Returns:**
long - 指定页面上形状集合中形状的唯一 ID。
### drawRectangle(double pinX, double pinY, double width, double height) {#drawRectangle-double-double-double-double-}
```
public long drawRectangle(double pinX, double pinY, double width, double height)
```


绘制矩形的过程。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pinX | double | 指定相对于页面的形状针（旋转中心）的 X 坐标。 |
| pinY | double | 指定相对于页面的形状针（旋转中心）的 Y 坐标。 |
| width | double | 指定形状的宽度 |
| height | double | 指定形状的高度 |

**Returns:**
long - 指定页面上形状集合中形状的唯一 ID。
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
布尔
### getAssociatedPage() {#getAssociatedPage--}
```
public Page getAssociatedPage()
```


原始绘图页面的 ID，该页面已被绘图审阅者在单独的标注覆盖层上进行标记。

**Returns:**
[Page](../../com.aspose.diagram/page)
### getBackPage() {#getBackPage--}
```
public Page getBackPage()
```


页面的背景页面。

**Returns:**
[Page](../../com.aspose.diagram/page)
### getBackground() {#getBackground--}
```
public int getBackground()
```


指示页面是否为背景页的标志。

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


为绘图中两个形状之间的每个连接包含一个 Connect 元素。

**Returns:**
[ConnectCollection](../../com.aspose.diagram/connectcollection)
### getID() {#getID--}
```
public int getID()
```


元素在其父元素中的唯一 ID。

**Returns:**
int
### getName() {#getName--}
```
public String getName()
```


元素的名称。

**Returns:**
java.lang.String
### getNameU() {#getNameU--}
```
public String getNameU()
```


元素的通用名称。

**Returns:**
java.lang.String
### getPageSheet() {#getPageSheet--}
```
public PageSheet getPageSheet()
```


包含定义页面或母版元素的页面工作表的元素。

**Returns:**
[PageSheet](../../com.aspose.diagram/pagesheet)
### getPages() {#getPages--}
```
public PageCollection getPages()
```


页面集合。

**Returns:**
[PageCollection](../../com.aspose.diagram/pagecollection)
### getReviewerID() {#getReviewerID--}
```
public int getReviewerID()
```


与标注覆盖层关联的审阅者的 ID。

**Returns:**
int
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


形状集合。

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getViewCenterX() {#getViewCenterX--}
```
public double getViewCenterX()
```


ViewCenterX 和 ViewCenterY 指定页面上的中心点，新视图（窗口）在首次打开时将采用该中心点。

**Returns:**
double
### getViewCenterY() {#getViewCenterY--}
```
public double getViewCenterY()
```


ViewCenterX 和 ViewCenterY 指定页面上的中心点，新视图（窗口）在首次打开时将采用该中心点。

**Returns:**
double
### getViewScale() {#getViewScale--}
```
public double getViewScale()
```


在打开页面的新视图（窗口）时使用的默认放大系数。例如，1 = 100%；1.5 = 150%，依此类推。

**Returns:**
double
### glueShapeToConnectorBeginX(long shapeFromId, String connectionName, long connectorId) {#glueShapeToConnectorBeginX-long-java.lang.String-long-}
```
public void glueShapeToConnectorBeginX(long shapeFromId, String connectionName, long connectorId)
```


将形状粘贴到连接器的 BeginX。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapeFromId | long | 连接器开始的形状的 ID [Shape](../../com.aspose.diagram/shape)。 |
| connectionName | java.lang.String | 形状上连接器将连接的连接名称。 |
| connectorId | long | 类型为 Dynamic connector 的形状的 ID [Shape](../../com.aspose.diagram/shape)。 |

### glueShapeToConnectorEndX(long shapeToId, String connectionName, long connectorId) {#glueShapeToConnectorEndX-long-java.lang.String-long-}
```
public void glueShapeToConnectorEndX(long shapeToId, String connectionName, long connectorId)
```


将形状粘贴到连接器的 EndX。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapeToId | long | 连接器结束的形状的 ID [Shape](../../com.aspose.diagram/shape)。 |
| connectionName | java.lang.String | 连接器将在第二形状上连接的连接名称。 |
| connectorId | long | 类型为 Dynamic connector 的形状的 ID [Shape](../../com.aspose.diagram/shape)。 |

### glueShapes(Shape shapeFrom, int placeTo, Shape shapeTo) {#glueShapes-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-}
```
public void glueShapes(Shape shapeFrom, int placeTo, Shape shapeTo)
```


粘贴形状。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapeFrom | [Shape](../../com.aspose.diagram/shape) | 从 [Shape](../../com.aspose.diagram/shape) 粘连的形状。 |
| placeTo | int | 在第一个形状上粘连 Aspose.Diagram.Manipulation.ConnectionPointPlace 的位置。 |
| shapeTo | [Shape](../../com.aspose.diagram/shape) | 粘连到的形状 [Shape](../../com.aspose.diagram/shape)。 |

### glueShapes(long shapeFromId, int placeTo, long shapeToId) {#glueShapes-long-int-long-}
```
public void glueShapes(long shapeFromId, int placeTo, long shapeToId)
```


粘贴形状

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapeFromId | long | 从 [Shape](../../com.aspose.diagram/shape) 粘连的形状的 ID。 |
| placeTo | int | 在第一个形状上粘连 Aspose.Diagram.Manipulation.ConnectionPointPlace 的位置。 |
| shapeToId | long | 粘连到的形状 [Shape](../../com.aspose.diagram/shape) 的 ID。 |

### glueShapesInContainer(long shapeFromId, int shapeToBeginConnectionIndex, int shapeToEndConnectionIndex, long shapeToId) {#glueShapesInContainer-long-int-int-long-}
```
public void glueShapesInContainer(long shapeFromId, int shapeToBeginConnectionIndex, int shapeToEndConnectionIndex, long shapeToId)
```


在容器中粘贴形状

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapeFromId | long | 从 [Shape](../../com.aspose.diagram/shape) 粘连的形状的 ID。 |
| shapeToBeginConnectionIndex | int | 在第一个连接索引上粘连的位置。 |
| shapeToEndConnectionIndex | int | 在结束连接索引上粘连的位置。 |
| shapeToId | long | 粘连到的形状 [Shape](../../com.aspose.diagram/shape) 的 ID。 |

### glueShapesInContainer(long shapeFromId, String shapeToBeginConnectionName, String shapeToEndConnectionName, long shapeToId) {#glueShapesInContainer-long-java.lang.String-java.lang.String-long-}
```
public void glueShapesInContainer(long shapeFromId, String shapeToBeginConnectionName, String shapeToEndConnectionName, long shapeToId)
```


使用连接名称在容器中粘贴形状

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapeFromId | long | 从 [Shape](../../com.aspose.diagram/shape) 粘连的形状的 ID。 |
| shapeToBeginConnectionName | java.lang.String | 在第一个连接名称上粘连的位置。 |
| shapeToEndConnectionName | java.lang.String | 在结束连接名称上粘连的位置。 |
| shapeToId | long | 粘连到的形状 [Shape](../../com.aspose.diagram/shape) 的 ID。 |

### glueShapesInContainerByID(long shapeFromId, int shapeToBeginConnectionID, int shapeToEndConnectionID, long shapeToId) {#glueShapesInContainerByID-long-int-int-long-}
```
public void glueShapesInContainerByID(long shapeFromId, int shapeToBeginConnectionID, int shapeToEndConnectionID, long shapeToId)
```


通过连接 ID 在容器中粘贴形状

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapeFromId | long | 从 [Shape](../../com.aspose.diagram/shape) 粘连的形状的 ID。 |
| shapeToBeginConnectionID | int | 在第一个连接 ID 上粘连的位置。 |
| shapeToEndConnectionID | int | 在结束连接 ID 上粘连的位置。 |
| shapeToId | long | 粘连到的形状 [Shape](../../com.aspose.diagram/shape) 的 ID。 |

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


为页面布局形状和/或重新路由连接器。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | [LayoutOptions](../../com.aspose.diagram/layoutoptions) | 使用 [LayoutOptions](../../com.aspose.diagram/layoutoptions) 配置布局选项。 |

### moveTo(int index) {#moveTo-int-}
```
public void moveTo(int index)
```


将页面移动到页面列表中的其他位置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | int | 目标页面索引。 |

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


将由 ID 定义的形状在 Z 顺序中向后移动一个位置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapeId | long | shape.long 的 ID |

### sendToBack(long shapeId) {#sendToBack-long-}
```
public void sendToBack(long shapeId)
```


将由 ID 定义的形状移动到 Z 顺序的最底层。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapeId | long | shape.long 的 ID |

### setAssociatedPage(Page value) {#setAssociatedPage-com.aspose.diagram.Page-}
```
public void setAssociatedPage(Page value)
```


有关此属性的描述，请参阅 [getAssociatedPage()](../../com.aspose.diagram/page\#getAssociatedPage--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setBackPage(Page value) {#setBackPage-com.aspose.diagram.Page-}
```
public void setBackPage(Page value)
```


有关此属性的描述，请参阅 [getBackPage()](../../com.aspose.diagram/page\#getBackPage--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setBackground(int value) {#setBackground-int-}
```
public void setBackground(int value)
```


有关此属性的描述，请参阅 [getBackground()](../../com.aspose.diagram/page\#getBackground--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


有关此属性的描述，请参阅 [getID()](../../com.aspose.diagram/page\#getID--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


有关此属性的描述，请参阅 [getName()](../../com.aspose.diagram/page\#getName--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


有关此属性的描述，请参阅 [getNameU()](../../com.aspose.diagram/page\#getNameU--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setPages(PageCollection value) {#setPages-com.aspose.diagram.PageCollection-}
```
public void setPages(PageCollection value)
```


有关此属性的描述，请参阅 [getPages()](../../com.aspose.diagram/page\#getPages--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PageCollection](../../com.aspose.diagram/pagecollection) |  |

### setPresetTheme(int value) {#setPresetTheme-int-}
```
public void setPresetTheme(int value)
```


将预设主题应用于此页面

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setPresetThemeQuickStyle(int value) {#setPresetThemeQuickStyle-int-}
```
public void setPresetThemeQuickStyle(int value)
```


将预设主题变体快速样式应用于此页面

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setPresetThemeVariant(int value) {#setPresetThemeVariant-int-}
```
public void setPresetThemeVariant(int value)
```


将预设主题变体应用于此页面

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setReviewerID(int value) {#setReviewerID-int-}
```
public void setReviewerID(int value)
```


有关此属性的描述，请参阅 [getReviewerID()](../../com.aspose.diagram/page\#getReviewerID--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setViewCenterX(double value) {#setViewCenterX-double-}
```
public void setViewCenterX(double value)
```


有关此属性的描述，请参阅 [getViewCenterX()](../../com.aspose.diagram/page\#getViewCenterX--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setViewCenterY(double value) {#setViewCenterY-double-}
```
public void setViewCenterY(double value)
```


有关此属性的描述，请参阅 [getViewCenterY()](../../com.aspose.diagram/page\#getViewCenterY--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setViewScale(double value) {#setViewScale-double-}
```
public void setViewScale(double value)
```


有关此属性的描述，请参阅 [getViewScale()](../../com.aspose.diagram/page\#getViewScale--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double |  |

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

