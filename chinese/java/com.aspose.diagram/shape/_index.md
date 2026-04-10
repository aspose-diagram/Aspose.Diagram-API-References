---
title: Shape
second_title: Aspose.Diagram for Java API 参考
description: 包含定义母版页或组合形状元素中形状的元素。
type: docs
weight: 355
url: /zh/java/com.aspose.diagram/shape/
---

**Inheritance:**
java.lang.Object
```
public class Shape
```

包含定义母版、页面或组形状元素中形状的元素。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Shape()](#Shape--) | 构造函数。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [bringForward()](#bringForward--) | 将形状在 Z 顺序中向前移动一个位置。 |
| [bringToFront()](#bringToFront--) | 将形状置于 Z 顺序的最前面。 |
| [centerDrawing()](#centerDrawing--) | 使形状相对于页面范围居中 |
| [connectedShapes(int flag, String categoryFilter)](#connectedShapes-int-java.lang.String-) | 返回一个数组，其中包含与该形状相连的形状的标识符（ID）。 |
| [copy(Shape source)](#copy-com.aspose.diagram.Shape-) |  |
| [dependsOnShapes()](#dependsOnShapes--) | 返回一个数组，其中包含依赖于某个形状的形状的标识符。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActiveXControl()](#getActiveXControl--) | 获取 ActiveX 控件。 |
| [getActs()](#getActs--) | 包含 Act 元素的集合。 |
| [getAlign()](#getAlign--) | 指示形状相对于其粘附的参考线或参考点的对齐方式。 |
| [getChars()](#getChars--) | 包含 Char 元素的集合。 |
| [getClass()](#getClass--) |  |
| [getClippingPath()](#getClippingPath--) |  |
| [getConnectionABCDs()](#getConnectionABCDs--) | 包含 ConnectionABCD 元素的集合。 |
| [getConnections()](#getConnections--) | 包含 Connection 元素的集合。 |
| [getConnectorRule()](#getConnectorRule--) | 返回一个 connectorRule，其中包含与该形状相连的形状 ID 和连接。 |
| [getConnectorsType()](#getConnectorsType--) | 获取连接器类型 |
| [getControlData()](#getControlData--) | 获取控件的数据。 |
| [getControls()](#getControls--) | 包含一组 Control 元素。 |
| [getData1()](#getData1--) | 包含用于提供有关形状的附加信息的任意字符串值。 |
| [getData2()](#getData2--) | 包含用于提供有关形状的附加信息的任意字符串值。 |
| [getData3()](#getData3--) | 包含用于提供有关形状的附加信息的任意字符串值。 |
| [getDel()](#getDel--) | 指示该元素是否在本地被删除的标志。 |
| [getDiagram()](#getDiagram--) | Visio 对象层次结构的根元素。 |
| [getDisplayText()](#getDisplayText--) | 获取界面上显示的文本 |
| [getEvent()](#getEvent--) | 包含指定控制形状事件的公式的元素。 |
| [getFields()](#getFields--) | 包含一组 Field 元素。 |
| [getFill()](#getFill--) | 包含形状及其投影的当前填充格式值，包括图案、前景色和背景色。 |
| [getFillStyle()](#getFillStyle--) | 此形状继承填充格式的 StyleSheet。 |
| [getForeign()](#getForeign--) | 包含指定在 Microsoft Visio 文档中使用的来自其他程序的对象宽度和高度的元素。 |
| [getForeignData()](#getForeignData--) | 包含 MIME（多用途互联网邮件扩展）编码的图片数据 BLOB，例如 Windows 元文件、位图或 OLE 数据。 |
| [getGeoms()](#getGeoms--) | 包含一组 Geom 元素。 |
| [getGroup()](#getGroup--) | 包含控制如何向组添加形状、移动组成员以及选择组的元素。 |
| [getHelp()](#getHelp--) | 包含指定 Shape 元素帮助文件主题和版权信息的元素。 |
| [getHyperlinks()](#getHyperlinks--) | 包含 Hyperlink 元素的集合。 |
| [getID()](#getID--) | 元素在其父元素中的唯一 ID。 |
| [getImage()](#getImage--) | 包含位图的伽马、亮度、对比度、模糊、锐化、去噪和透明度值。 |
| [getInheritChars()](#getInheritChars--) | 包含由母版形状继承的形状字符值。 |
| [getInheritFill()](#getInheritFill--) | 包含由父样式和母版形状继承的形状填充格式值。 |
| [getInheritGeoms()](#getInheritGeoms--) | 包含由母版形状继承的形状的 Geoms 值。 |
| [getInheritLine()](#getInheritLine--) | 包含由父样式和母版形状继承的形状的线条格式值。 |
| [getInheritParas()](#getInheritParas--) | 包含由父样式和母版形状继承的形状的 paras。 |
| [getInheritProps()](#getInheritProps--) | 包含由母版形状继承的形状的 props。 |
| [getInheritTextBlock()](#getInheritTextBlock--) | 包含由父样式和母版形状继承的形状的 textblock 值。 |
| [getInheritUsers()](#getInheritUsers--) | 包含由母版形状继承的形状的 users。 |
| [getLayerMem()](#getLayerMem--) | 包含 LayerMember 元素，指定形状分配到的每个图层。 |
| [getLayout()](#getLayout--) | 包含控制形状放置和连接器路由设置的元素。 |
| [getLine()](#getLine--) | 包含控制形状线条属性的元素，例如图案、粗细和颜色。 |
| [getLineStyle()](#getLineStyle--) | 此形状继承线条格式的 StyleSheet |
| [getMaster()](#getMaster--) | 形状继承其数据的 Master |
| [getMasterShape()](#getMasterShape--) | 此属性只能出现在属于组形状且该组是母版实例的形状中。 |
| [getMisc()](#getMisc--) | 包含指定 Shape 元素帮助文件主题和版权信息的元素。 |
| [getName()](#getName--) | 元素的名称。 |
| [getNameU()](#getNameU--) | 元素的通用名称。 |
| [getOneD()](#getOneD--) | 确定形状是否表现为一维 (1-D) 对象。 |
| [getPage()](#getPage--) | Visio 对象层次结构的根元素。 |
| [getParas()](#getParas--) | 包含 Para 元素的集合。 |
| [getParentShape()](#getParentShape--) | 形状的父级。 |
| [getProps()](#getProps--) | 包含 Prop 元素的集合。 |
| [getProtection()](#getProtection--) | 锁定有助于防止对形状的意外更改，但不会阻止 Microsoft Visio 在其他情况下重置值。 |
| [getPureText()](#getPureText--) | 获取文本字符串 |
| [getRootShape()](#getRootShape--) | 如果此形状是母版实例的一部分，则返回实例的顶层形状。 |
| [getScratchs()](#getScratchs--) | 包含一组 Scratch 元素。 |
| [getShapes()](#getShapes--) | 包含 Shape 元素的集合。 |
| [getSmartTagDefs()](#getSmartTagDefs--) | 包含 SmartTagDef 元素的集合。 |
| [getTabsCollection()](#getTabsCollection--) | 包含 Tab 元素的集合。 |
| [getText()](#getText--) | 包含形状的文本。 |
| [getTextBlock()](#getTextBlock--) | 包含指定形状文本块中文本对齐、边距和默认制表位位置的元素。 |
| [getTextStyle()](#getTextStyle--) | 此形状继承文本格式的 StyleSheet。 |
| [getTextXForm()](#getTextXForm--) | 包含指定形状文本块位置信息的元素。 |
| [getThreeDFormat()](#getThreeDFormat--) | 获取 ThreeDFormat。 |
| [getTwoD()](#getTwoD--) | 确定形状是否表现为二维 (2-D) 对象。 |
| [getType()](#getType--) | 形状的类型。 |
| [getUniqueID()](#getUniqueID--) | 分配给形状的 GUID（全局唯一标识符）。 |
| [getUsers()](#getUsers--) | 包含一组 User 元素。 |
| [getXForm()](#getXForm--) | 包含指定形状一般位置信息的元素。 |
| [getXForm1D()](#getXForm1D--) | 包含一维形状的起点和终点的 x 和 y 坐标。 |
| [getZOrderIndex()](#getZOrderIndex--) | 返回形状在 Z 顺序中的索引（不包括 guide 形状）。 |
| [gluedShapes(int flag, String categoryFilter, Shape otherShape)](#gluedShapes-int-java.lang.String-com.aspose.diagram.Shape-) | 返回一个数组，包含粘贴到形状上的形状标识符。 |
| [hashCode()](#hashCode--) |  |
| [isConnected(Shape shape)](#isConnected-com.aspose.diagram.Shape-) | 指示这两个形状是否已连接。 |
| [isContain(Shape shape)](#isContain-com.aspose.diagram.Shape-) | 指示此形状是否包含另一个形状。 |
| [isGlued(Shape shape)](#isGlued-com.aspose.diagram.Shape-) | 指示这两个形状是否已粘贴。 |
| [isInGroup()](#isInGroup--) | 指示此形状是否位于组形状中。 |
| [isIntersect(Shape shape)](#isIntersect-com.aspose.diagram.Shape-) | 指示此形状是否与另一个形状相交。 |
| [isTextEmpty()](#isTextEmpty--) | 指示该形状是否具有文本以及文本是否为空。 |
| [move(double dX, double dY)](#move-double-double-) | 将形状在 dX 和 dY 英寸上从当前位置移动。 |
| [moveTo(double newPinX, double newPinY)](#moveTo-double-double-) | 将形状移动到页面上的新绝对位置。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [refreshData()](#refreshData--) | 在更改形状的文本或其他属性时，刷新形状的位置，包括 xform、连接和几何体。 |
| [replaceText(String text, String replaceText)](#replaceText-java.lang.String-java.lang.String-) | 替换形状的文本字符串。 |
| [sendBackward()](#sendBackward--) | 将形状在 Z 顺序中向后移动一个位置。 |
| [sendToBack()](#sendToBack--) | 将形状移动到 Z 顺序的最底层。 |
| [setAngle(double angle)](#setAngle-double-) | 设置形状的新角度。 |
| [setClippingPath(String value)](#setClippingPath-java.lang.String-) | 有关此属性的描述，请参阅 [getClippingPath()](../../com.aspose.diagram/shape\#getClippingPath--) |
| [setConnectorsType(int type)](#setConnectorsType-int-) | 设置连接器类型 |
| [setData1(String value)](#setData1-java.lang.String-) | 有关此属性的描述，请参阅 [getData1()](../../com.aspose.diagram/shape\#getData1--) |
| [setData2(String value)](#setData2-java.lang.String-) | 有关此属性的描述，请参阅 [getData2()](../../com.aspose.diagram/shape\#getData2--) |
| [setData3(String value)](#setData3-java.lang.String-) | 有关此属性的描述，请参阅 [getData3()](../../com.aspose.diagram/shape\#getData3--) |
| [setDel(int value)](#setDel-int-) | 有关此属性的描述，请参阅 [getDel()](../../com.aspose.diagram/shape\#getDel--) |
| [setDiagram(Diagram value)](#setDiagram-com.aspose.diagram.Diagram-) | 有关此属性的描述，请参阅 [getDiagram()](../../com.aspose.diagram/shape\#getDiagram--) |
| [setEvent(Event value)](#setEvent-com.aspose.diagram.Event-) | 有关此属性的描述，请参阅 [getEvent()](../../com.aspose.diagram/shape\#getEvent--) |
| [setFillStyle(StyleSheet value)](#setFillStyle-com.aspose.diagram.StyleSheet-) | 有关此属性的描述，请参阅 [getFillStyle()](../../com.aspose.diagram/shape\#getFillStyle--) |
| [setHeight(double height)](#setHeight-double-) | 设置形状的新高度。 |
| [setID(long value)](#setID-long-) | 有关此属性的描述，请参阅 [getID()](../../com.aspose.diagram/shape\#getID--) |
| [setLineStyle(StyleSheet value)](#setLineStyle-com.aspose.diagram.StyleSheet-) | 有关此属性的描述，请参阅 [getLineStyle()](../../com.aspose.diagram/shape\#getLineStyle--) |
| [setMaster(Master value)](#setMaster-com.aspose.diagram.Master-) | 有关此属性的描述，请参阅 [getMaster()](../../com.aspose.diagram/shape\#getMaster--) |
| [setMasterShape(Shape value)](#setMasterShape-com.aspose.diagram.Shape-) | 有关此属性的描述，请参阅 [getMasterShape()](../../com.aspose.diagram/shape\#getMasterShape--) |
| [setName(String value)](#setName-java.lang.String-) | 有关此属性的描述，请参阅 [getName()](../../com.aspose.diagram/shape\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | 有关此属性的描述，请参阅 [getNameU()](../../com.aspose.diagram/shape\#getNameU--) |
| [setPage(Page value)](#setPage-com.aspose.diagram.Page-) | 有关此属性的描述，请参阅 [getPage()](../../com.aspose.diagram/shape\#getPage--) |
| [setParentShape(Shape value)](#setParentShape-com.aspose.diagram.Shape-) | 有关此属性的描述，请参阅 [getParentShape()](../../com.aspose.diagram/shape\#getParentShape--) |
| [setPresetTheme(int value)](#setPresetTheme-int-) | 将预设主题应用于此形状 |
| [setPresetThemeQuickStyle(int value)](#setPresetThemeQuickStyle-int-) | 将预设主题变体快速样式应用于此形状 |
| [setPresetThemeStyleMatrics(int styleIndex, int colorIndex)](#setPresetThemeStyleMatrics-int-int-) | 将预设主题变体快速样式应用于此形状，如形状样式下拉列表中的主题样式选项 |
| [setPresetThemeVariant(int value)](#setPresetThemeVariant-int-) | 将预设主题变体应用于此形状 |
| [setProps(PropCollection value)](#setProps-com.aspose.diagram.PropCollection-) | 有关此属性的描述，请参阅 [getProps()](../../com.aspose.diagram/shape\#getProps--) |
| [setText(Text value)](#setText-com.aspose.diagram.Text-) | 有关此属性的描述，请参阅 [getText()](../../com.aspose.diagram/shape\#getText--) |
| [setTextStyle(StyleSheet value)](#setTextStyle-com.aspose.diagram.StyleSheet-) | 有关此属性的描述，请参阅 [getTextStyle()](../../com.aspose.diagram/shape\#getTextStyle--) |
| [setTwoD(boolean value)](#setTwoD-boolean-) | 有关此属性的描述，请参阅 [getTwoD()](../../com.aspose.diagram/shape\#getTwoD--) |
| [setType(int value)](#setType-int-) | 有关此属性的描述，请参阅 [getType()](../../com.aspose.diagram/shape\#getType--) |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | 有关此属性的描述，请参阅 [getUniqueID()](../../com.aspose.diagram/shape\#getUniqueID--) |
| [setWidth(double width)](#setWidth-double-) | 设置形状的新宽度。 |
| [setXForm(XForm value)](#setXForm-com.aspose.diagram.XForm-) | 有关此属性的描述，请参阅 [getXForm()](../../com.aspose.diagram/shape\#getXForm--) |
| [setXForm1D(XForm1D value)](#setXForm1D-com.aspose.diagram.XForm1D-) | 有关此属性的描述，请参阅 [getXForm1D()](../../com.aspose.diagram/shape\#getXForm1D--) |
| [toHTML(InputStream stream, HTMLSaveOptions options)](#toHTML-java.io.InputStream-com.aspose.diagram.HTMLSaveOptions-) | 创建形状的 HTML 并以指定格式保存到流中。 |
| [toHTML(OutputStream stream, HTMLSaveOptions options)](#toHTML-java.io.OutputStream-com.aspose.diagram.HTMLSaveOptions-) | 创建形状的 HTML 并以指定格式保存到流中。 |
| [toHTML(String fileName, HTMLSaveOptions options)](#toHTML-java.lang.String-com.aspose.diagram.HTMLSaveOptions-) | 创建 HTML 并保存到文件。 |
| [toImage(InputStream stream, ImageSaveOptions options)](#toImage-java.io.InputStream-com.aspose.diagram.ImageSaveOptions-) | 创建形状图像并以指定格式保存到流中。 |
| [toImage(OutputStream stream, ImageSaveOptions options)](#toImage-java.io.OutputStream-com.aspose.diagram.ImageSaveOptions-) | 创建形状图像并以指定格式保存到流中。 |
| [toImage(String imageFile, ImageSaveOptions options)](#toImage-java.lang.String-com.aspose.diagram.ImageSaveOptions-) | 创建形状图像并保存到文件。 |
| [toPdf(InputStream stream)](#toPdf-java.io.InputStream-) | 创建形状 PDF 并保存到流中。 |
| [toPdf(OutputStream stream)](#toPdf-java.io.OutputStream-) | 创建形状 PDF 并保存到流中。 |
| [toPdf(String fileName)](#toPdf-java.lang.String-) | 将形状保存为 PDF 文件。 |
| [toString()](#toString--) |  |
| [toSvg(String imageFile, SVGSaveOptions options)](#toSvg-java.lang.String-com.aspose.diagram.SVGSaveOptions-) | 将形状保存为 SVG 文件。 |
| [ungroup()](#ungroup--) | 取消分组形状 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Shape() {#Shape--}
```
public Shape()
```


构造函数。

### bringForward() {#bringForward--}
```
public void bringForward()
```


将形状在 Z 顺序中向前移动一个位置。

### bringToFront() {#bringToFront--}
```
public void bringToFront()
```


将形状置于 Z 顺序的最前面。

### centerDrawing() {#centerDrawing--}
```
public void centerDrawing()
```


使形状相对于页面范围居中

### connectedShapes(int flag, String categoryFilter) {#connectedShapes-int-java.lang.String-}
```
public long[] connectedShapes(int flag, String categoryFilter)
```


返回一个数组，其中包含与该形状相连的形状的标识符（ID）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 标志 | int | 根据连接器的方向性过滤返回的形状 ID 数组。有关可能的值，请参阅备注 Aspose.Diagram.ConnectedShapesFlags. |
| categoryFilter | java.lang.String | 通过限制为匹配指定 categoryString 的形状的 ID，过滤返回的形状 ID 数组。 |

**Returns:**
long[] - ID 数组 long。
### copy(Shape source) {#copy-com.aspose.diagram.Shape-}
```
public void copy(Shape source)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [Shape](../../com.aspose.diagram/shape) |  |

### dependsOnShapes() {#dependsOnShapes--}
```
public long[] dependsOnShapes()
```


返回一个数组，其中包含依赖于某个形状的形状的标识符。

**Returns:**
long[] - ID 数组 long。
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
### getActiveXControl() {#getActiveXControl--}
```
public ActiveXControl getActiveXControl()
```


获取 ActiveX 控件。

**Returns:**
[ActiveXControl](../../com.aspose.diagram/activexcontrol)
### getActs() {#getActs--}
```
public ActCollection getActs()
```


包含 Act 元素的集合。

**Returns:**
[ActCollection](../../com.aspose.diagram/actcollection)
### getAlign() {#getAlign--}
```
public Align getAlign()
```


指示形状相对于其粘连的参考线或参考点的对齐方式。Align 元素仅在粘连到参考线或参考点的形状上出现。

**Returns:**
[Align](../../com.aspose.diagram/align)
### getChars() {#getChars--}
```
public CharCollection getChars()
```


包含 Char 元素的集合。

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


包含 ConnectionABCD 元素的集合。

**Returns:**
[ConnectionABCDCollection](../../com.aspose.diagram/connectionabcdcollection)
### getConnections() {#getConnections--}
```
public ConnectionCollection getConnections()
```


包含 Connection 元素的集合。

**Returns:**
[ConnectionCollection](../../com.aspose.diagram/connectioncollection)
### getConnectorRule() {#getConnectorRule--}
```
public ConnectorRule getConnectorRule()
```


返回一个 connectorRule，其中包含与该形状相连的形状 ID 和连接。

**Returns:**
[ConnectorRule](../../com.aspose.diagram/connectorrule) - ConnectorRule.
### getConnectorsType() {#getConnectorsType--}
```
public int getConnectorsType()
```


获取连接器类型

**Returns:**
int
### getControlData() {#getControlData--}
```
public byte[] getControlData()
```


获取控件的数据。

**Returns:**
byte[]
### getControls() {#getControls--}
```
public ControlCollection getControls()
```


包含一组 Control 元素。

**Returns:**
[ControlCollection](../../com.aspose.diagram/controlcollection)
### getData1() {#getData1--}
```
public String getData1()
```


包含用于提供有关形状的附加信息的任意字符串值。

**Returns:**
java.lang.String
### getData2() {#getData2--}
```
public String getData2()
```


包含用于提供有关形状的附加信息的任意字符串值。

**Returns:**
java.lang.String
### getData3() {#getData3--}
```
public String getData3()
```


包含用于提供有关形状的附加信息的任意字符串值。

**Returns:**
java.lang.String
### getDel() {#getDel--}
```
public int getDel()
```


标志指示元素是否在本地被删除。值为 1 表示该元素在本地已删除。

**Returns:**
int
### getDiagram() {#getDiagram--}
```
public Diagram getDiagram()
```


Visio 对象层次结构的根元素。

**Returns:**
[Diagram](../../com.aspose.diagram/diagram)
### getDisplayText() {#getDisplayText--}
```
public String getDisplayText()
```


获取界面上显示的文本

**Returns:**
java.lang.String
### getEvent() {#getEvent--}
```
public Event getEvent()
```


包含指定控制形状事件的公式的元素。

**Returns:**
[Event](../../com.aspose.diagram/event)
### getFields() {#getFields--}
```
public FieldCollection getFields()
```


包含一组 Field 元素。

**Returns:**
[FieldCollection](../../com.aspose.diagram/fieldcollection)
### getFill() {#getFill--}
```
public Fill getFill()
```


包含形状及其投影的当前填充格式值，包括图案、前景色和背景色。

**Returns:**
[Fill](../../com.aspose.diagram/fill)
### getFillStyle() {#getFillStyle--}
```
public StyleSheet getFillStyle()
```


此形状继承填充格式的 StyleSheet。

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getForeign() {#getForeign--}
```
public Foreign getForeign()
```


包含指定来自其他程序的对象在 Microsoft Visio 文档中使用的宽度和高度的元素。同时包括指定对象图像在其边界内偏移距离的元素。

**Returns:**
[Foreign](../../com.aspose.diagram/foreign)
### getForeignData() {#getForeignData--}
```
public ForeignData getForeignData()
```


包含 MIME（多用途互联网邮件扩展）编码的图片数据 BLOB，例如 Windows 元文件、位图或 OLE 数据。

**Returns:**
[ForeignData](../../com.aspose.diagram/foreigndata)
### getGeoms() {#getGeoms--}
```
public GeomCollection getGeoms()
```


包含一组 Geom 元素。

**Returns:**
[GeomCollection](../../com.aspose.diagram/geomcollection)
### getGroup() {#getGroup--}
```
public Group getGroup()
```


包含控制如何向组添加形状、移动组成员以及选择组的元素。

**Returns:**
[Group](../../com.aspose.diagram/group)
### getHelp() {#getHelp--}
```
public Help getHelp()
```


包含指定 Shape 元素帮助文件主题和版权信息的元素。

**Returns:**
[Help](../../com.aspose.diagram/help)
### getHyperlinks() {#getHyperlinks--}
```
public HyperlinkCollection getHyperlinks()
```


包含 Hyperlink 元素的集合。

**Returns:**
[HyperlinkCollection](../../com.aspose.diagram/hyperlinkcollection)
### getID() {#getID--}
```
public long getID()
```


元素在其父元素中的唯一 ID。

**Returns:**
long
### getImage() {#getImage--}
```
public Image getImage()
```


包含位图的伽马、亮度、对比度、模糊、锐化、去噪和透明度值。

**Returns:**
[Image](../../com.aspose.diagram/image)
### getInheritChars() {#getInheritChars--}
```
public CharCollection getInheritChars()
```


包含由母版形状继承的形状字符值。

**Returns:**
[CharCollection](../../com.aspose.diagram/charcollection)
### getInheritFill() {#getInheritFill--}
```
public Fill getInheritFill()
```


包含由父样式和母版形状继承的形状填充格式值。

**Returns:**
[Fill](../../com.aspose.diagram/fill)
### getInheritGeoms() {#getInheritGeoms--}
```
public GeomCollection getInheritGeoms()
```


包含由母版形状继承的形状的 Geoms 值。

**Returns:**
[GeomCollection](../../com.aspose.diagram/geomcollection)
### getInheritLine() {#getInheritLine--}
```
public Line getInheritLine()
```


包含由父样式和母版形状继承的形状的线条格式值。

**Returns:**
[Line](../../com.aspose.diagram/line)
### getInheritParas() {#getInheritParas--}
```
public ParaCollection getInheritParas()
```


包含由父样式和母版形状继承的形状的 paras。

**Returns:**
[ParaCollection](../../com.aspose.diagram/paracollection)
### getInheritProps() {#getInheritProps--}
```
public PropCollection getInheritProps()
```


包含由母版形状继承的形状的 props。

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getInheritTextBlock() {#getInheritTextBlock--}
```
public TextBlock getInheritTextBlock()
```


包含由父样式和母版形状继承的形状的 textblock 值。

**Returns:**
[TextBlock](../../com.aspose.diagram/textblock)
### getInheritUsers() {#getInheritUsers--}
```
public UserCollection getInheritUsers()
```


包含由母版形状继承的形状的 users。

**Returns:**
[UserCollection](../../com.aspose.diagram/usercollection)
### getLayerMem() {#getLayerMem--}
```
public LayerMem getLayerMem()
```


包含 LayerMember 元素，指定形状分配到的每个图层。

**Returns:**
[LayerMem](../../com.aspose.diagram/layermem)
### getLayout() {#getLayout--}
```
public Layout getLayout()
```


包含控制形状放置和连接器路由设置的元素。

**Returns:**
[Layout](../../com.aspose.diagram/layout)
### getLine() {#getLine--}
```
public Line getLine()
```


包含控制形状线属性的元素，例如图案、粗细和颜色。这些元素决定线端是否格式化（例如使用箭头），线端格式的大小，应用于线的圆角半径，以及线帽样式（圆形或方形）。

**Returns:**
[Line](../../com.aspose.diagram/line)
### getLineStyle() {#getLineStyle--}
```
public StyleSheet getLineStyle()
```


此形状继承线条格式的 StyleSheet

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getMaster() {#getMaster--}
```
public Master getMaster()
```


形状继承其数据的 Master

**Returns:**
[Master](../../com.aspose.diagram/master)
### getMasterShape() {#getMasterShape--}
```
public Shape getMasterShape()
```


此属性仅可能出现在属于组形状且该组是主形状实例的形状中。该属性包含一个引用主形状中相应子形状的 ID。

**Returns:**
[Shape](../../com.aspose.diagram/shape)
### getMisc() {#getMisc--}
```
public Misc getMisc()
```


包含指定 Shape 元素帮助文件主题和版权信息的元素。

**Returns:**
[Misc](../../com.aspose.diagram/misc)
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
### getOneD() {#getOneD--}
```
public boolean getOneD()
```


确定形状是否表现为一维 (1-D) 对象。只读。

**Returns:**
布尔
### getPage() {#getPage--}
```
public Page getPage()
```


Visio 对象层次结构的根元素。

**Returns:**
[Page](../../com.aspose.diagram/page)
### getParas() {#getParas--}
```
public ParaCollection getParas()
```


包含 Para 元素的集合。

**Returns:**
[ParaCollection](../../com.aspose.diagram/paracollection)
### getParentShape() {#getParentShape--}
```
public Shape getParentShape()
```


形状的父级。

**Returns:**
[Shape](../../com.aspose.diagram/shape)
### getProps() {#getProps--}
```
public PropCollection getProps()
```


包含 Prop 元素的集合。

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getProtection() {#getProtection--}
```
public Protection getProtection()
```


锁定有助于防止对形状的意外更改，但不会阻止 Microsoft Visio 在其他情况下重置值。它也不能防止在 ShapeSheet 窗口中所做的更改。

**Returns:**
[Protection](../../com.aspose.diagram/protection)
### getPureText() {#getPureText--}
```
public String getPureText()
```


获取文本字符串

**Returns:**
java.lang.String
### getRootShape() {#getRootShape--}
```
public Shape getRootShape()
```


如果此形状是主实例的一部分，则返回该实例的顶层形状。只读。

**Returns:**
[Shape](../../com.aspose.diagram/shape)
### getScratchs() {#getScratchs--}
```
public ScratchCollection getScratchs()
```


包含一组 Scratch 元素。

**Returns:**
[ScratchCollection](../../com.aspose.diagram/scratchcollection)
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


包含 Shape 元素的集合。

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getSmartTagDefs() {#getSmartTagDefs--}
```
public SmartTagDefCollection getSmartTagDefs()
```


包含 SmartTagDef 元素的集合。

**Returns:**
[SmartTagDefCollection](../../com.aspose.diagram/smarttagdefcollection)
### getTabsCollection() {#getTabsCollection--}
```
public TabsCollection getTabsCollection()
```


包含 Tab 元素的集合。

**Returns:**
[TabsCollection](../../com.aspose.diagram/tabscollection)
### getText() {#getText--}
```
public Text getText()
```


包含形状的文本。

**Returns:**
[Text](../../com.aspose.diagram/text)
### getTextBlock() {#getTextBlock--}
```
public TextBlock getTextBlock()
```


包含指定形状文本块中文本对齐、边距和默认制表位位置的元素。

**Returns:**
[TextBlock](../../com.aspose.diagram/textblock)
### getTextStyle() {#getTextStyle--}
```
public StyleSheet getTextStyle()
```


此形状继承文本格式的 StyleSheet。

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getTextXForm() {#getTextXForm--}
```
public TextXForm getTextXForm()
```


包含指定形状文本块位置信息的元素。

**Returns:**
[TextXForm](../../com.aspose.diagram/textxform)
### getThreeDFormat() {#getThreeDFormat--}
```
public ThreeDFormat getThreeDFormat()
```


获取 ThreeDFormat。

**Returns:**
[ThreeDFormat](../../com.aspose.diagram/threedformat)
### getTwoD() {#getTwoD--}
```
public boolean getTwoD()
```


确定形状是否表现为二维 (2-D) 对象。

**Returns:**
布尔
### getType() {#getType--}
```
public int getType()
```


形状的类型。可能是以下值之一：Group、Shape、Guide 或 Foreign。

**Returns:**
int
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


分配给形状的 GUID（全局唯一标识符）。

**Returns:**
java.util.UUID
### getUsers() {#getUsers--}
```
public UserCollection getUsers()
```


包含一组 User 元素。

**Returns:**
[UserCollection](../../com.aspose.diagram/usercollection)
### getXForm() {#getXForm--}
```
public XForm getXForm()
```


包含指定形状一般位置信息的元素。

**Returns:**
[XForm](../../com.aspose.diagram/xform)
### getXForm1D() {#getXForm1D--}
```
public XForm1D getXForm1D()
```


包含 1-D 形状的起点和终点的 x 和 y 坐标。此元素仅在 1-D 形状中出现。

**Returns:**
[XForm1D](../../com.aspose.diagram/xform1d)
### getZOrderIndex() {#getZOrderIndex--}
```
public int getZOrderIndex()
```


返回形状在 Z 顺序中的索引（不包括 guide 形状）。

**Returns:**
int
### gluedShapes(int flag, String categoryFilter, Shape otherShape) {#gluedShapes-int-java.lang.String-com.aspose.diagram.Shape-}
```
public long[] gluedShapes(int flag, String categoryFilter, Shape otherShape)
```


返回一个数组，包含粘贴到形状上的形状标识符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 标志 | int | 返回形状的连接点的维度和方向性。有关可能的取值，请参阅备注中的 Aspose.Diagram.GluedShapesFlags。 |
| categoryFilter | java.lang.String | 通过限制为匹配指定 categoryString 的形状的 ID，过滤返回的形状 ID 数组。 |
| otherShape | [Shape](../../com.aspose.diagram/shape) | 可选：返回的形状还必须粘附的额外形状，可以是 [Shape](../../com.aspose.diagram/shape) 或 null。 |

**Returns:**
long[] - ID 数组 long。
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


指示这两个形状是否已连接。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) | shape |

**Returns:**
布尔
### isContain(Shape shape) {#isContain-com.aspose.diagram.Shape-}
```
public boolean isContain(Shape shape)
```


指示此形状是否包含另一个形状。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) |  |

**Returns:**
布尔
### isGlued(Shape shape) {#isGlued-com.aspose.diagram.Shape-}
```
public boolean isGlued(Shape shape)
```


指示这两个形状是否已粘贴。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) | shape |

**Returns:**
布尔
### isInGroup() {#isInGroup--}
```
public boolean isInGroup()
```


指示此形状是否位于组形状中。

**Returns:**
布尔
### isIntersect(Shape shape) {#isIntersect-com.aspose.diagram.Shape-}
```
public boolean isIntersect(Shape shape)
```


指示此形状是否与另一个形状相交。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) |  |

**Returns:**
布尔
### isTextEmpty() {#isTextEmpty--}
```
public boolean isTextEmpty()
```


指示该形状是否具有文本以及文本是否为空。

**Returns:**
布尔
### move(double dX, double dY) {#move-double-double-}
```
public void move(double dX, double dY)
```


将形状在 dX 和 dY 英寸上从当前位置移动。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dX | double | X 偏移 double。 |
| dY | double | Y 偏移 double。 |

### moveTo(double newPinX, double newPinY) {#moveTo-double-double-}
```
public void moveTo(double newPinX, double newPinY)
```


将形状移动到页面上的新绝对位置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newPinX | double | 相对于其父级原点的新 x 坐标（形状针脚的中心，即旋转中心），单位为 double。 |
| newPinY | double | 相对于其父级原点的新 y 坐标（形状针脚的中心，即旋转中心），单位为 double。 |

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


在更改形状的文本或其他属性时，刷新形状的位置，包括 xform、connection 和 geom。我们将收集形状的数据，例如形状的文本，然后计算形状的位置。此方法仅用于刷新形状的数据。

### replaceText(String text, String replaceText) {#replaceText-java.lang.String-java.lang.String-}
```
public void replaceText(String text, String replaceText)
```


替换形状的文本字符串。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String |  |
| replaceText | java.lang.String |  |

### sendBackward() {#sendBackward--}
```
public void sendBackward()
```


将形状在 Z 顺序中向后移动一个位置。

### sendToBack() {#sendToBack--}
```
public void sendToBack()
```


将形状移动到 Z 顺序的最底层。

### setAngle(double angle) {#setAngle-double-}
```
public void setAngle(double angle)
```


设置形状的新角度。角度的单位是弧度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| angle | double | 新角度，单位为弧度而非度，double。 |

### setClippingPath(String value) {#setClippingPath-java.lang.String-}
```
public void setClippingPath(String value)
```


有关此属性的描述，请参阅 [getClippingPath()](../../com.aspose.diagram/shape\#getClippingPath--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setConnectorsType(int type) {#setConnectorsType-int-}
```
public void setConnectorsType(int type)
```


设置连接器类型

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 类型 | int |  |

### setData1(String value) {#setData1-java.lang.String-}
```
public void setData1(String value)
```


有关此属性的描述，请参阅 [getData1()](../../com.aspose.diagram/shape\#getData1--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setData2(String value) {#setData2-java.lang.String-}
```
public void setData2(String value)
```


有关此属性的描述，请参阅 [getData2()](../../com.aspose.diagram/shape\#getData2--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setData3(String value) {#setData3-java.lang.String-}
```
public void setData3(String value)
```


有关此属性的描述，请参阅 [getData3()](../../com.aspose.diagram/shape\#getData3--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


有关此属性的描述，请参阅 [getDel()](../../com.aspose.diagram/shape\#getDel--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setDiagram(Diagram value) {#setDiagram-com.aspose.diagram.Diagram-}
```
public void setDiagram(Diagram value)
```


有关此属性的描述，请参阅 [getDiagram()](../../com.aspose.diagram/shape\#getDiagram--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Diagram](../../com.aspose.diagram/diagram) |  |

### setEvent(Event value) {#setEvent-com.aspose.diagram.Event-}
```
public void setEvent(Event value)
```


有关此属性的描述，请参阅 [getEvent()](../../com.aspose.diagram/shape\#getEvent--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Event](../../com.aspose.diagram/event) |  |

### setFillStyle(StyleSheet value) {#setFillStyle-com.aspose.diagram.StyleSheet-}
```
public void setFillStyle(StyleSheet value)
```


有关此属性的描述，请参阅 [getFillStyle()](../../com.aspose.diagram/shape\#getFillStyle--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setHeight(double height) {#setHeight-double-}
```
public void setHeight(double height)
```


设置形状的新高度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| height | double | New heightdouble. |

### setID(long value) {#setID-long-}
```
public void setID(long value)
```


有关此属性的描述，请参阅 [getID()](../../com.aspose.diagram/shape\#getID--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long |  |

### setLineStyle(StyleSheet value) {#setLineStyle-com.aspose.diagram.StyleSheet-}
```
public void setLineStyle(StyleSheet value)
```


有关此属性的描述，请参阅 [getLineStyle()](../../com.aspose.diagram/shape\#getLineStyle--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setMaster(Master value) {#setMaster-com.aspose.diagram.Master-}
```
public void setMaster(Master value)
```


有关此属性的描述，请参阅 [getMaster()](../../com.aspose.diagram/shape\#getMaster--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Master](../../com.aspose.diagram/master) |  |

### setMasterShape(Shape value) {#setMasterShape-com.aspose.diagram.Shape-}
```
public void setMasterShape(Shape value)
```


有关此属性的描述，请参阅 [getMasterShape()](../../com.aspose.diagram/shape\#getMasterShape--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Shape](../../com.aspose.diagram/shape) |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


有关此属性的描述，请参阅 [getName()](../../com.aspose.diagram/shape\#getName--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


有关此属性的描述，请参阅 [getNameU()](../../com.aspose.diagram/shape\#getNameU--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setPage(Page value) {#setPage-com.aspose.diagram.Page-}
```
public void setPage(Page value)
```


有关此属性的描述，请参阅 [getPage()](../../com.aspose.diagram/shape\#getPage--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setParentShape(Shape value) {#setParentShape-com.aspose.diagram.Shape-}
```
public void setParentShape(Shape value)
```


有关此属性的描述，请参阅 [getParentShape()](../../com.aspose.diagram/shape\#getParentShape--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Shape](../../com.aspose.diagram/shape) |  |

### setPresetTheme(int value) {#setPresetTheme-int-}
```
public void setPresetTheme(int value)
```


将预设主题应用于此形状

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setPresetThemeQuickStyle(int value) {#setPresetThemeQuickStyle-int-}
```
public void setPresetThemeQuickStyle(int value)
```


将预设主题变体快速样式应用于此形状

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setPresetThemeStyleMatrics(int styleIndex, int colorIndex) {#setPresetThemeStyleMatrics-int-int-}
```
public void setPresetThemeStyleMatrics(int styleIndex, int colorIndex)
```


将预设主题变体快速样式应用于此形状，如形状样式下拉列表中的主题样式选项

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| styleIndex | int | the row of style matrics |
| colorIndex | int | the column of style matrics |

### setPresetThemeVariant(int value) {#setPresetThemeVariant-int-}
```
public void setPresetThemeVariant(int value)
```


将预设主题变体应用于此形状

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setProps(PropCollection value) {#setProps-com.aspose.diagram.PropCollection-}
```
public void setProps(PropCollection value)
```


有关此属性的描述，请参阅 [getProps()](../../com.aspose.diagram/shape\#getProps--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PropCollection](../../com.aspose.diagram/propcollection) |  |

### setText(Text value) {#setText-com.aspose.diagram.Text-}
```
public void setText(Text value)
```


有关此属性的描述，请参阅 [getText()](../../com.aspose.diagram/shape\#getText--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Text](../../com.aspose.diagram/text) |  |

### setTextStyle(StyleSheet value) {#setTextStyle-com.aspose.diagram.StyleSheet-}
```
public void setTextStyle(StyleSheet value)
```


有关此属性的描述，请参阅 [getTextStyle()](../../com.aspose.diagram/shape\#getTextStyle--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setTwoD(boolean value) {#setTwoD-boolean-}
```
public void setTwoD(boolean value)
```


有关此属性的描述，请参阅 [getTwoD()](../../com.aspose.diagram/shape\#getTwoD--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### setType(int value) {#setType-int-}
```
public void setType(int value)
```


有关此属性的描述，请参阅 [getType()](../../com.aspose.diagram/shape\#getType--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


有关此属性的描述，请参阅 [getUniqueID()](../../com.aspose.diagram/shape\#getUniqueID--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.util.UUID |  |

### setWidth(double width) {#setWidth-double-}
```
public void setWidth(double width)
```


设置形状的新宽度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| width | double | New widthdouble. |

### setXForm(XForm value) {#setXForm-com.aspose.diagram.XForm-}
```
public void setXForm(XForm value)
```


有关此属性的描述，请参阅 [getXForm()](../../com.aspose.diagram/shape\#getXForm--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [XForm](../../com.aspose.diagram/xform) |  |

### setXForm1D(XForm1D value) {#setXForm1D-com.aspose.diagram.XForm1D-}
```
public void setXForm1D(XForm1D value)
```


有关此属性的描述，请参阅 [getXForm1D()](../../com.aspose.diagram/shape\#getXForm1D--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [XForm1D](../../com.aspose.diagram/xform1d) |  |

### toHTML(InputStream stream, HTMLSaveOptions options) {#toHTML-java.io.InputStream-com.aspose.diagram.HTMLSaveOptions-}
```
public void toHTML(InputStream stream, HTMLSaveOptions options)
```


创建形状的 HTML 并以指定格式保存到流中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.InputStream | The output stream. |
| options | [HTMLSaveOptions](../../com.aspose.diagram/htmlsaveoptions) | Addtional html creation options |

### toHTML(OutputStream stream, HTMLSaveOptions options) {#toHTML-java.io.OutputStream-com.aspose.diagram.HTMLSaveOptions-}
```
public void toHTML(OutputStream stream, HTMLSaveOptions options)
```


创建形状的 HTML 并以指定格式保存到流中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.OutputStream | The output stream. |
| options | [HTMLSaveOptions](../../com.aspose.diagram/htmlsaveoptions) | Addtional html creation options |

### toHTML(String fileName, HTMLSaveOptions options) {#toHTML-java.lang.String-com.aspose.diagram.HTMLSaveOptions-}
```
public void toHTML(String fileName, HTMLSaveOptions options)
```


创建 HTML 并保存到文件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String |  |
| options | [HTMLSaveOptions](../../com.aspose.diagram/htmlsaveoptions) | html save options |

### toImage(InputStream stream, ImageSaveOptions options) {#toImage-java.io.InputStream-com.aspose.diagram.ImageSaveOptions-}
```
public void toImage(InputStream stream, ImageSaveOptions options)
```


创建形状图像并以指定格式保存到流中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.InputStream | The output stream. |
| options | [ImageSaveOptions](../../com.aspose.diagram/imagesaveoptions) | Additional image creation options |

### toImage(OutputStream stream, ImageSaveOptions options) {#toImage-java.io.OutputStream-com.aspose.diagram.ImageSaveOptions-}
```
public void toImage(OutputStream stream, ImageSaveOptions options)
```


创建形状图像并以指定格式保存到流中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.OutputStream | The output stream. |
| options | [ImageSaveOptions](../../com.aspose.diagram/imagesaveoptions) | Additional image creation options |

### toImage(String imageFile, ImageSaveOptions options) {#toImage-java.lang.String-com.aspose.diagram.ImageSaveOptions-}
```
public void toImage(String imageFile, ImageSaveOptions options)
```


Creates the shape image and saves it to a file. The extension of the file name determines the format of the image.

The format of the image is specified by using the extension of the file name. For example, if you specify "myfile.png", then the image will be saved in the PNG format. The following file extensions are recognized: .bmp, .gif, .png, .jpg, .jpeg, .tiff, .tif, .emf.

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageFile | java.lang.String | The image file name with full path. |
| options | [ImageSaveOptions](../../com.aspose.diagram/imagesaveoptions) | Additional image creation options |

### toPdf(InputStream stream) {#toPdf-java.io.InputStream-}
```
public void toPdf(InputStream stream)
```


创建形状 PDF 并保存到流中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.InputStream | The output stream. |

### toPdf(OutputStream stream) {#toPdf-java.io.OutputStream-}
```
public void toPdf(OutputStream stream)
```


创建形状 PDF 并保存到流中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.OutputStream | The output stream. |

### toPdf(String fileName) {#toPdf-java.lang.String-}
```
public void toPdf(String fileName)
```


将形状保存为 PDF 文件。

**Parameters:**
| 参数 | 类型 | 描述 |
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


将形状保存为 SVG 文件。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageFile | java.lang.String |  |
| options | [SVGSaveOptions](../../com.aspose.diagram/svgsaveoptions) |  |

### ungroup() {#ungroup--}
```
public void ungroup()
```


取消分组形状

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

