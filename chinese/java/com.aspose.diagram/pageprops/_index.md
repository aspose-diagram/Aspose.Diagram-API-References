---
title: PageProps
second_title: Aspose.Diagram for Java API 参考
description: 包含控制页面属性（如页面宽度、高度和比例）的单元格。
type: docs
weight: 268
url: /zh/java/com.aspose.diagram/pageprops/
---

**Inheritance:**
java.lang.Object
```
public class PageProps
```

包含控制页面属性的单元格，例如页面宽度、高度和比例。
## 方法

| 方法 | 描述 |
| --- | --- |
| [deepClone()](#deepClone--) | 创建此实例的深度副本。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | 指示元素是否已在本地删除的标志。 |
| [getDrawingResizeType()](#getDrawingResizeType--) | 确定绘图页面是否自动调整大小以适应图表。 |
| [getDrawingScale()](#getDrawingScale--) | 表示当前绘图比例中绘图单位的值。 |
| [getDrawingScaleType()](#getDrawingScaleType--) | 指定页面使用的绘图比例类型。 |
| [getDrawingSizeType()](#getDrawingSizeType--) | 指定页面的绘图尺寸。 |
| [getInhibitSnap()](#getInhibitSnap--) | 指定前景页上的形状是否会捕捉到页面上其他对象以及背景页上的形状。 |
| [getPageHeight()](#getPageHeight--) | 指定页面的高度（以绘图单位为单位）。 |
| [getPageScale()](#getPageScale--) | 指定当前绘图比例中默认页面单位的值。 |
| [getPageWidth()](#getPageWidth--) | 指定页面的宽度（以绘图单位为单位）。 |
| [getShdwObliqueAngle()](#getShdwObliqueAngle--) | 包含一个数字，指定在应用默认页面阴影类型时的斜向角度。 |
| [getShdwOffsetX()](#getShdwOffsetX--) | 指定形状的投影在水平方向上相对于形状的偏移距离（以页面单位为单位）。 |
| [getShdwOffsetY()](#getShdwOffsetY--) | 指定形状的投影在垂直方向上相对于形状的偏移距离（以页面单位为单位）。 |
| [getShdwScaleFactor()](#getShdwScaleFactor--) | 指定放大或缩小形状阴影的百分比。 |
| [getShdwType()](#getShdwType--) | 指示页面的默认阴影类型。 |
| [getUIVisibility()](#getUIVisibility--) | 确定页面名称是否在用户界面 (UI) 中显示。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | 有关此属性的描述，请参阅 [getDel()](../../com.aspose.diagram/pageprops\#getDel--)。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### deepClone() {#deepClone--}
```
public Object deepClone()
```


创建此实例的深度副本。

**Returns:**
java.lang.Object -
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
### getDel() {#getDel--}
```
public int getDel()
```


一个标志，指示元素是否已在本地删除。值为 1 表示该元素已在本地删除。

**Returns:**
int
### getDrawingResizeType() {#getDrawingResizeType--}
```
public DrawingResizeType getDrawingResizeType()
```


确定绘图页面是否自动调整大小以适应图表。

**Returns:**
[DrawingResizeType](../../com.aspose.diagram/drawingresizetype)
### getDrawingScale() {#getDrawingScale--}
```
public DoubleValue getDrawingScale()
```


表示当前绘图比例中绘图单位的值。页面的绘图比例是 PageScale 元素中包含的页面单位与绘图单位的比率。此元素的单位决定页面的默认长度 (DL) 单位。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDrawingScaleType() {#getDrawingScaleType--}
```
public DrawingScaleType getDrawingScaleType()
```


指定页面使用的绘图比例类型。

**Returns:**
[DrawingScaleType](../../com.aspose.diagram/drawingscaletype)
### getDrawingSizeType() {#getDrawingSizeType--}
```
public DrawingSizeType getDrawingSizeType()
```


指定页面的绘图尺寸。

**Returns:**
[DrawingSizeType](../../com.aspose.diagram/drawingsizetype)
### getInhibitSnap() {#getInhibitSnap--}
```
public BoolValue getInhibitSnap()
```


指定前景页上的形状是否会捕捉到页面上其他对象以及背景页上的形状。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getPageHeight() {#getPageHeight--}
```
public DoubleValue getPageHeight()
```


指定页面的高度（以绘图单位为单位）。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPageScale() {#getPageScale--}
```
public DoubleValue getPageScale()
```


指定当前绘图比例中默认页面单位的值。页面的绘图比例是 PageScale 元素中的页面单位与 DrawingScale 元素中显示的绘图单位的比率。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPageWidth() {#getPageWidth--}
```
public DoubleValue getPageWidth()
```


指定页面的宽度（以绘图单位为单位）。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwObliqueAngle() {#getShdwObliqueAngle--}
```
public DoubleValue getShdwObliqueAngle()
```


包含一个数字，指定在应用默认页面阴影类型时的斜向角度。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwOffsetX() {#getShdwOffsetX--}
```
public DoubleValue getShdwOffsetX()
```


指定形状的投影在水平方向上相对于形状的偏移距离（以页面单位为单位）。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwOffsetY() {#getShdwOffsetY--}
```
public DoubleValue getShdwOffsetY()
```


指定形状的投影在垂直方向上相对于形状的偏移距离（以页面单位为单位）。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwScaleFactor() {#getShdwScaleFactor--}
```
public DoubleValue getShdwScaleFactor()
```


指定放大或缩小形状阴影的百分比。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwType() {#getShdwType--}
```
public ShdwType getShdwType()
```


指示页面的默认阴影类型。

**Returns:**
[ShdwType](../../com.aspose.diagram/shdwtype)
### getUIVisibility() {#getUIVisibility--}
```
public UIVisibility getUIVisibility()
```


确定页面名称是否在用户界面 (UI) 中显示。值为 1 表示页面不可见；值为 0 表示页面可见。

**Returns:**
[UIVisibility](../../com.aspose.diagram/uivisibility)
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




### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


有关此属性的描述，请参阅 [getDel()](../../com.aspose.diagram/pageprops\#getDel--)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

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

