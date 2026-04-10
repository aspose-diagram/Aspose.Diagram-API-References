---
title: Window
second_title: Aspose.Diagram for Java API 参考
description: 表示 Microsoft Visio 实例中的打开窗口。
type: docs
weight: 444
url: /zh/java/com.aspose.diagram/window/
---

**Inheritance:**
java.lang.Object
```
public class Window
```

表示 Microsoft Visio 实例中的打开窗口。此元素包含在 DatadiagramML 文件首次被 Visio 打开时，在应用程序工作区中精确重新创建用户界面窗口所需的信息。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Window()](#Window--) | 构造函数。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContainer()](#getContainer--) | 容器的 ID：页面、工作表或母版。 |
| [getContainerType()](#getContainerType--) | 可能是以下值之一：Document、Page 或 Master。 |
| [getDocument()](#getDocument--) | 此窗口中显示的文档的文件路径。 |
| [getDynamicGridEnabled()](#getDynamicGridEnabled--) | 指定文档或窗口是否启用动态网格功能。 |
| [getGlueSettings()](#getGlueSettings--) | 指定在文档中启用粘连时，形状粘连到的对象。 |
| [getID()](#getID--) | 元素在其父元素中的唯一 ID。 |
| [getMaster()](#getMaster--) | 如果此窗口显示的是母版，则为母版 ID。 |
| [getPage()](#getPage--) | 如果此窗口显示的是页面，则为页面 ID。 |
| [getParentWindow()](#getParentWindow--) | 包含此模板窗口的窗口的 ID。 |
| [getReadOnly()](#getReadOnly--) | 如果此模板不是文档模板，则为只读标志。 |
| [getSheet()](#getSheet--) | 容器中工作表的 ID。 |
| [getShowConnectionPoints()](#getShowConnectionPoints--) | 指定是否在窗口中显示连接点。 |
| [getShowGrid()](#getShowGrid--) | 指定是否在绘图窗口中显示网格。 |
| [getShowGuides()](#getShowGuides--) | 指定是否在绘图窗口中显示参考线。 |
| [getShowPageBreaks()](#getShowPageBreaks--) | 指定是否在窗口中显示分页符。 |
| [getShowRulers()](#getShowRulers--) | 指定是否在绘图窗口中显示标尺。 |
| [getSnapAngles()](#getSnapAngles--) | 包含 SnapAngle 元素的集合。 |
| [getSnapExtensions()](#getSnapExtensions--) | 指定是否为活动窗口启用或禁用特定的捕捉扩展设置。 |
| [getSnapSettings()](#getSnapSettings--) | 指定当窗口中捕捉激活时，形状捕捉到的对象。 |
| [getStencilGroup()](#getStencilGroup--) | 指定窗口所属的合并模板窗口组。 |
| [getStencilGroupPos()](#getStencilGroupPos--) | 包含一个整数，指定模板在窗口中组内的相对位置。 |
| [getTabSplitterPos()](#getTabSplitterPos--) | 指定绘图窗口页面标签控件的宽度（相对于绘图窗口总宽度的比例）。 |
| [getViewCenterX()](#getViewCenterX--) | 可选的双精度数。 |
| [getViewCenterY()](#getViewCenterY--) | 可选的双精度数。 |
| [getViewScale()](#getViewScale--) | 可选的双精度数。 |
| [getWindowHeight()](#getWindowHeight--) | 窗口矩形的高度。 |
| [getWindowLeft()](#getWindowLeft--) | 窗口矩形的左坐标。 |
| [getWindowState()](#getWindowState--) | 此属性可以是以下值的组合。 |
| [getWindowTop()](#getWindowTop--) | 窗口矩形的上坐标。 |
| [getWindowType()](#getWindowType--) | 一个枚举值，可为以下之一：Drawing、Sheet、Stencil 或 Icon。WindowType='Stencil' 的 Window 元素必须在其父绘图窗口（WindowType='Drawing'）之后出现，并且在任何其他绘图窗口元素之前。 |
| [getWindowWidth()](#getWindowWidth--) | 窗口矩形的宽度。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setContainer(int value)](#setContainer-int-) | 有关此属性的描述，请参阅 [getContainer()](../../com.aspose.diagram/window\\#getContainer--) |
| [setContainerType(int value)](#setContainerType-int-) | 有关此属性的描述，请参阅 [getContainerType()](../../com.aspose.diagram/window\\#getContainerType--) |
| [setDocument(String value)](#setDocument-java.lang.String-) | 有关此属性的描述，请参阅 [getDocument()](../../com.aspose.diagram/window\#getDocument--) |
| [setDynamicGridEnabled(int value)](#setDynamicGridEnabled-int-) | 有关此属性的描述，请参阅 [getDynamicGridEnabled()](../../com.aspose.diagram/window\#getDynamicGridEnabled--) |
| [setGlueSettings(int value)](#setGlueSettings-int-) | 有关此属性的描述，请参阅 [getGlueSettings()](../../com.aspose.diagram/window\#getGlueSettings--) |
| [setID(int value)](#setID-int-) | 有关此属性的描述，请参阅 [getID()](../../com.aspose.diagram/window\#getID--) |
| [setMaster(Master value)](#setMaster-com.aspose.diagram.Master-) | 有关此属性的描述，请参阅 [getMaster()](../../com.aspose.diagram/window\#getMaster--) |
| [setPage(Page value)](#setPage-com.aspose.diagram.Page-) | 有关此属性的描述，请参阅 [getPage()](../../com.aspose.diagram/window\#getPage--) |
| [setParentWindow(int value)](#setParentWindow-int-) | 有关此属性的描述，请参阅 [getParentWindow()](../../com.aspose.diagram/window\#getParentWindow--) |
| [setReadOnly(int value)](#setReadOnly-int-) | 有关此属性的描述，请参阅 [getReadOnly()](../../com.aspose.diagram/window\#getReadOnly--) |
| [setSheet(int value)](#setSheet-int-) | 有关此属性的描述，请参阅 [getSheet()](../../com.aspose.diagram/window\#getSheet--) |
| [setShowConnectionPoints(int value)](#setShowConnectionPoints-int-) | 有关此属性的描述，请参阅 [getShowConnectionPoints()](../../com.aspose.diagram/window\#getShowConnectionPoints--) |
| [setShowGrid(int value)](#setShowGrid-int-) | 有关此属性的描述，请参阅 [getShowGrid()](../../com.aspose.diagram/window\#getShowGrid--) |
| [setShowGuides(int value)](#setShowGuides-int-) | 有关此属性的描述，请参阅 [getShowGuides()](../../com.aspose.diagram/window\#getShowGuides--) |
| [setShowPageBreaks(int value)](#setShowPageBreaks-int-) | 有关此属性的描述，请参阅 [getShowPageBreaks()](../../com.aspose.diagram/window\#getShowPageBreaks--) |
| [setShowRulers(int value)](#setShowRulers-int-) | 有关此属性的描述，请参阅 [getShowRulers()](../../com.aspose.diagram/window\#getShowRulers--) |
| [setSnapExtensions(int value)](#setSnapExtensions-int-) | 有关此属性的描述，请参阅 [getSnapExtensions()](../../com.aspose.diagram/window\#getSnapExtensions--) |
| [setSnapSettings(int value)](#setSnapSettings-int-) | 有关此属性的描述，请参阅 [getSnapSettings()](../../com.aspose.diagram/window\#getSnapSettings--) |
| [setStencilGroup(String value)](#setStencilGroup-java.lang.String-) | 有关此属性的描述，请参阅 [getStencilGroup()](../../com.aspose.diagram/window\#getStencilGroup--) |
| [setStencilGroupPos(int value)](#setStencilGroupPos-int-) | 有关此属性的描述，请参阅 [getStencilGroupPos()](../../com.aspose.diagram/window\#getStencilGroupPos--) |
| [setTabSplitterPos(double value)](#setTabSplitterPos-double-) | 有关此属性的描述，请参阅 [getTabSplitterPos()](../../com.aspose.diagram/window\#getTabSplitterPos--) |
| [setViewCenterX(double value)](#setViewCenterX-double-) | 有关此属性的描述，请参阅 [getViewCenterX()](../../com.aspose.diagram/window\#getViewCenterX--) |
| [setViewCenterY(double value)](#setViewCenterY-double-) | 有关此属性的描述，请参阅 [getViewCenterY()](../../com.aspose.diagram/window\#getViewCenterY--) |
| [setViewScale(double value)](#setViewScale-double-) | 有关此属性的描述，请参阅 [getViewScale()](../../com.aspose.diagram/window\#getViewScale--) |
| [setWindowHeight(long value)](#setWindowHeight-long-) | 有关此属性的描述，请参阅 [getWindowHeight()](../../com.aspose.diagram/window\#getWindowHeight--) |
| [setWindowLeft(int value)](#setWindowLeft-int-) | 有关此属性的描述，请参阅 [getWindowLeft()](../../com.aspose.diagram/window\#getWindowLeft--) |
| [setWindowState(int value)](#setWindowState-int-) | 有关此属性的描述，请参阅 [getWindowState()](../../com.aspose.diagram/window\#getWindowState--) |
| [setWindowTop(int value)](#setWindowTop-int-) | 有关此属性的描述，请参阅 [getWindowTop()](../../com.aspose.diagram/window\#getWindowTop--) |
| [setWindowType(int value)](#setWindowType-int-) | 有关此属性的描述，请参阅 [getWindowType()](../../com.aspose.diagram/window\#getWindowType--) |
| [setWindowWidth(long value)](#setWindowWidth-long-) | 有关此属性的描述，请参阅 [getWindowWidth()](../../com.aspose.diagram/window\#getWindowWidth--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Window() {#Window--}
```
public Window()
```


构造函数。

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContainer() {#getContainer--}
```
public int getContainer()
```


容器的 ID：页面、工作表或母版。仅在指定了 ContainerType 时相关且必要。

**Returns:**
int
### getContainerType() {#getContainerType--}
```
public int getContainerType()
```


可能是以下值之一：Document、Page 或 Master。仅在 WindowType 指定为 Drawing 或 Sheet 时相关。

**Returns:**
int
### getDocument() {#getDocument--}
```
public String getDocument()
```


在此窗口中显示的文档的文件路径。此属性适用于 WindowType 指定为 Stencil 的窗口。

**Returns:**
java.lang.String
### getDynamicGridEnabled() {#getDynamicGridEnabled--}
```
public int getDynamicGridEnabled()
```


指定文档或窗口是否启用动态网格功能。

**Returns:**
int
### getGlueSettings() {#getGlueSettings--}
```
public int getGlueSettings()
```


指定在文档中启用粘连时，形状粘连到的对象。

**Returns:**
int
### getID() {#getID--}
```
public int getID()
```


元素在其父元素中的唯一 ID。

**Returns:**
int
### getMaster() {#getMaster--}
```
public Master getMaster()
```


如果此窗口显示的是母版，则为母版 ID。

**Returns:**
[Master](../../com.aspose.diagram/master)
### getPage() {#getPage--}
```
public Page getPage()
```


如果此窗口显示页面，则为页面 ID。仅在 WindowType 指定为 Drawing 且 ContainerType 指定为 Page 时相关。

**Returns:**
[Page](../../com.aspose.diagram/page)
### getParentWindow() {#getParentWindow--}
```
public int getParentWindow()
```


包含此模板窗口的窗口的 ID。仅在 WindowType 指定为 Stencil 时相关。

**Returns:**
int
### getReadOnly() {#getReadOnly--}
```
public int getReadOnly()
```


如果此模板不是文档模板，则为只读标志。

**Returns:**
int
### getSheet() {#getSheet--}
```
public int getSheet()
```


容器中工作表的 ID。仅在 Container 指定为 Sheet 时相关。

**Returns:**
int
### getShowConnectionPoints() {#getShowConnectionPoints--}
```
public int getShowConnectionPoints()
```


指定是否在窗口中显示连接点。

**Returns:**
int
### getShowGrid() {#getShowGrid--}
```
public int getShowGrid()
```


指定是否在绘图窗口中显示网格。

**Returns:**
int
### getShowGuides() {#getShowGuides--}
```
public int getShowGuides()
```


指定是否在绘图窗口中显示参考线。

**Returns:**
int
### getShowPageBreaks() {#getShowPageBreaks--}
```
public int getShowPageBreaks()
```


指定是否在窗口中显示分页符。

**Returns:**
int
### getShowRulers() {#getShowRulers--}
```
public int getShowRulers()
```


指定是否在绘图窗口中显示标尺。

**Returns:**
int
### getSnapAngles() {#getSnapAngles--}
```
public FloatPointNumCollection getSnapAngles()
```


包含 SnapAngle 元素的集合。

**Returns:**
[FloatPointNumCollection](../../com.aspose.diagram/floatpointnumcollection)
### getSnapExtensions() {#getSnapExtensions--}
```
public int getSnapExtensions()
```


指定特定的捕捉扩展设置在活动窗口中是启用还是禁用。该值可以是下表中各值的总和。

**Returns:**
int
### getSnapSettings() {#getSnapSettings--}
```
public int getSnapSettings()
```


指定当窗口中启用捕捉时，形状要捕捉到的对象。该值可以是下表中数值的组合。

**Returns:**
int
### getStencilGroup() {#getStencilGroup--}
```
public String getStencilGroup()
```


指定该窗口所属的合并模板窗口组。此属性仅适用于 WindowType 属性为 Stencil 的 Window 元素，并且仅当该模板窗口是合并模板窗口组的一部分时有效。所有属于同一合并组的模板窗口具有相同的 StencilGroup 元素值。

**Returns:**
java.lang.String
### getStencilGroupPos() {#getStencilGroupPos--}
```
public int getStencilGroupPos()
```


包含一个整数，指定模板在窗口中组内的相对位置。

**Returns:**
int
### getTabSplitterPos() {#getTabSplitterPos--}
```
public double getTabSplitterPos()
```


指定绘图窗口页面标签控件的宽度（相对于绘图窗口总宽度的比例）。

**Returns:**
double
### getViewCenterX() {#getViewCenterX--}
```
public double getViewCenterX()
```


可选的双精度数。

**Returns:**
double
### getViewCenterY() {#getViewCenterY--}
```
public double getViewCenterY()
```


可选的双精度数。

**Returns:**
double
### getViewScale() {#getViewScale--}
```
public double getViewScale()
```


可选的双精度数。

**Returns:**
double
### getWindowHeight() {#getWindowHeight--}
```
public long getWindowHeight()
```


窗口矩形的高度。

**Returns:**
long
### getWindowLeft() {#getWindowLeft--}
```
public int getWindowLeft()
```


窗口矩形的左坐标。

**Returns:**
int
### getWindowState() {#getWindowState--}
```
public int getWindowState()
```


此属性可以是以下值的组合。

**Returns:**
int
### getWindowTop() {#getWindowTop--}
```
public int getWindowTop()
```


窗口矩形的上坐标。

**Returns:**
int
### getWindowType() {#getWindowType--}
```
public int getWindowType()
```


一个枚举值，可为以下之一：Drawing、Sheet、Stencil 或 Icon。WindowType='Stencil' 的 Window 元素必须在其父绘图窗口（WindowType='Drawing'）之后出现，并且在任何其他绘图窗口元素之前。

**Returns:**
int
### getWindowWidth() {#getWindowWidth--}
```
public long getWindowWidth()
```


窗口矩形的宽度。

**Returns:**
long
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setContainer(int value) {#setContainer-int-}
```
public void setContainer(int value)
```


有关此属性的描述，请参阅 [getContainer()](../../com.aspose.diagram/window\\#getContainer--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setContainerType(int value) {#setContainerType-int-}
```
public void setContainerType(int value)
```


有关此属性的描述，请参阅 [getContainerType()](../../com.aspose.diagram/window\\#getContainerType--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setDocument(String value) {#setDocument-java.lang.String-}
```
public void setDocument(String value)
```


有关此属性的描述，请参阅 [getDocument()](../../com.aspose.diagram/window\#getDocument--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setDynamicGridEnabled(int value) {#setDynamicGridEnabled-int-}
```
public void setDynamicGridEnabled(int value)
```


有关此属性的描述，请参阅 [getDynamicGridEnabled()](../../com.aspose.diagram/window\#getDynamicGridEnabled--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setGlueSettings(int value) {#setGlueSettings-int-}
```
public void setGlueSettings(int value)
```


有关此属性的描述，请参阅 [getGlueSettings()](../../com.aspose.diagram/window\#getGlueSettings--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


有关此属性的描述，请参阅 [getID()](../../com.aspose.diagram/window\#getID--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setMaster(Master value) {#setMaster-com.aspose.diagram.Master-}
```
public void setMaster(Master value)
```


有关此属性的描述，请参阅 [getMaster()](../../com.aspose.diagram/window\#getMaster--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Master](../../com.aspose.diagram/master) |  |

### setPage(Page value) {#setPage-com.aspose.diagram.Page-}
```
public void setPage(Page value)
```


有关此属性的描述，请参阅 [getPage()](../../com.aspose.diagram/window\#getPage--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setParentWindow(int value) {#setParentWindow-int-}
```
public void setParentWindow(int value)
```


有关此属性的描述，请参阅 [getParentWindow()](../../com.aspose.diagram/window\#getParentWindow--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setReadOnly(int value) {#setReadOnly-int-}
```
public void setReadOnly(int value)
```


有关此属性的描述，请参阅 [getReadOnly()](../../com.aspose.diagram/window\#getReadOnly--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setSheet(int value) {#setSheet-int-}
```
public void setSheet(int value)
```


有关此属性的描述，请参阅 [getSheet()](../../com.aspose.diagram/window\#getSheet--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setShowConnectionPoints(int value) {#setShowConnectionPoints-int-}
```
public void setShowConnectionPoints(int value)
```


有关此属性的描述，请参阅 [getShowConnectionPoints()](../../com.aspose.diagram/window\#getShowConnectionPoints--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setShowGrid(int value) {#setShowGrid-int-}
```
public void setShowGrid(int value)
```


有关此属性的描述，请参阅 [getShowGrid()](../../com.aspose.diagram/window\#getShowGrid--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setShowGuides(int value) {#setShowGuides-int-}
```
public void setShowGuides(int value)
```


有关此属性的描述，请参阅 [getShowGuides()](../../com.aspose.diagram/window\#getShowGuides--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setShowPageBreaks(int value) {#setShowPageBreaks-int-}
```
public void setShowPageBreaks(int value)
```


有关此属性的描述，请参阅 [getShowPageBreaks()](../../com.aspose.diagram/window\#getShowPageBreaks--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setShowRulers(int value) {#setShowRulers-int-}
```
public void setShowRulers(int value)
```


有关此属性的描述，请参阅 [getShowRulers()](../../com.aspose.diagram/window\#getShowRulers--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setSnapExtensions(int value) {#setSnapExtensions-int-}
```
public void setSnapExtensions(int value)
```


有关此属性的描述，请参阅 [getSnapExtensions()](../../com.aspose.diagram/window\#getSnapExtensions--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setSnapSettings(int value) {#setSnapSettings-int-}
```
public void setSnapSettings(int value)
```


有关此属性的描述，请参阅 [getSnapSettings()](../../com.aspose.diagram/window\#getSnapSettings--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setStencilGroup(String value) {#setStencilGroup-java.lang.String-}
```
public void setStencilGroup(String value)
```


有关此属性的描述，请参阅 [getStencilGroup()](../../com.aspose.diagram/window\#getStencilGroup--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setStencilGroupPos(int value) {#setStencilGroupPos-int-}
```
public void setStencilGroupPos(int value)
```


有关此属性的描述，请参阅 [getStencilGroupPos()](../../com.aspose.diagram/window\#getStencilGroupPos--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setTabSplitterPos(double value) {#setTabSplitterPos-double-}
```
public void setTabSplitterPos(double value)
```


有关此属性的描述，请参阅 [getTabSplitterPos()](../../com.aspose.diagram/window\#getTabSplitterPos--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setViewCenterX(double value) {#setViewCenterX-double-}
```
public void setViewCenterX(double value)
```


有关此属性的描述，请参阅 [getViewCenterX()](../../com.aspose.diagram/window\#getViewCenterX--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setViewCenterY(double value) {#setViewCenterY-double-}
```
public void setViewCenterY(double value)
```


有关此属性的描述，请参阅 [getViewCenterY()](../../com.aspose.diagram/window\#getViewCenterY--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setViewScale(double value) {#setViewScale-double-}
```
public void setViewScale(double value)
```


有关此属性的描述，请参阅 [getViewScale()](../../com.aspose.diagram/window\#getViewScale--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setWindowHeight(long value) {#setWindowHeight-long-}
```
public void setWindowHeight(long value)
```


有关此属性的描述，请参阅 [getWindowHeight()](../../com.aspose.diagram/window\#getWindowHeight--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long |  |

### setWindowLeft(int value) {#setWindowLeft-int-}
```
public void setWindowLeft(int value)
```


有关此属性的描述，请参阅 [getWindowLeft()](../../com.aspose.diagram/window\#getWindowLeft--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setWindowState(int value) {#setWindowState-int-}
```
public void setWindowState(int value)
```


有关此属性的描述，请参阅 [getWindowState()](../../com.aspose.diagram/window\#getWindowState--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setWindowTop(int value) {#setWindowTop-int-}
```
public void setWindowTop(int value)
```


有关此属性的描述，请参阅 [getWindowTop()](../../com.aspose.diagram/window\#getWindowTop--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setWindowType(int value) {#setWindowType-int-}
```
public void setWindowType(int value)
```


有关此属性的描述，请参阅 [getWindowType()](../../com.aspose.diagram/window\#getWindowType--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setWindowWidth(long value) {#setWindowWidth-long-}
```
public void setWindowWidth(long value)
```


有关此属性的描述，请参阅 [getWindowWidth()](../../com.aspose.diagram/window\#getWindowWidth--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long |  |

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

