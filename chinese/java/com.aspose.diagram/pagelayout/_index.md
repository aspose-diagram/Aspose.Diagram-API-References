---
title: PageLayout
second_title: Aspose.Diagram for Java API 参考
description: 包含控制页面布局设置的单元格，用于形状和连接线，例如页面上所有形状之间的间距、页面上所有连接线之间的间距以及所有连接线的路由样式。
type: docs
weight: 263
url: /zh/java/com.aspose.diagram/pagelayout/
---

**Inheritance:**
java.lang.Object
```
public class PageLayout
```

包含控制页面布局设置的单元格，这些设置适用于形状和连接线，例如页面上所有形状之间的间距、页面上所有连接线之间的间距以及页面上所有连接线的路由样式。
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAvenueSizeX()](#getAvenueSizeX--) | 确定在使用 Microsoft Visio 对绘图页面上的形状进行布局时，形状之间的垂直间距。 |
| [getAvenueSizeY()](#getAvenueSizeY--) | 确定在使用 Microsoft Visio 对绘图页面上的形状进行布局时，形状之间的垂直间距。 |
| [getAvoidPageBreaks()](#getAvoidPageBreaks--) | 指定当用户在“形状”菜单中选择“布局形状”时，形状在页面上的放置方式。 |
| [getBlockSizeX()](#getBlockSizeX--) | 确定垂直块大小，即在使用 Microsoft Visio 对绘图页面上的形状进行布局时，每个形状必须适应的区域。 |
| [getBlockSizeY()](#getBlockSizeY--) | 确定在使用 Microsoft Visio 对绘图页面上的形状进行布局时，形状之间的水平间距。 |
| [getClass()](#getClass--) |  |
| [getCtrlAsInput()](#getCtrlAsInput--) | 确定在使用控制手柄操作形状时，哪个形状是父形状。 |
| [getDel()](#getDel--) | 指示元素是否已在本地删除的标志。 |
| [getDynamicsOff()](#getDynamicsOff--) | 指定可放置形状是否移动，以及连接线是否在绘图页面上绕过其他形状和连接线重新路由。 |
| [getEnableGrid()](#getEnableGrid--) | 指定当用户选择“布局形状”（形状菜单）时，Microsoft Visio 是否基于内部页面网格布局形状。 |
| [getLineAdjustFrom()](#getLineAdjustFrom--) | 指定在动态连接器相互重叠时需要分开的连接器。 |
| [getLineAdjustTo()](#getLineAdjustTo--) | 指定在动态连接器相互重叠时需要对齐的连接器。 |
| [getLineJumpCode()](#getLineJumpCode--) | 指定绘图页面上所有未设置本地线跳样式的连接器的线跳样式。 |
| [getLineJumpFactorX()](#getLineJumpFactorX--) | 指定页面上动态连接线水平段的跳线大小，作为 LineToLineX 元素值的百分比（该元素指定绘图页面上所有连接线之间的水平间距）。 |
| [getLineJumpFactorY()](#getLineJumpFactorY--) | 指定页面上动态连接线垂直段的跳线大小，作为 LineToLineY 元素值的百分比（该元素指定绘图页面上所有连接线之间的垂直间距）。 |
| [getLineJumpStyle()](#getLineJumpStyle--) | 指定在绘图页面上动态连接线的水平段上未应用本地跳转方向的线路跳转方向。 |
| [getLineRouteExt()](#getLineRouteExt--) | 指定页面上所有连接器的默认外观。 |
| [getLineToLineX()](#getLineToLineX--) | 指定绘图页面上动态连接线之间的最小水平间距。 |
| [getLineToLineY()](#getLineToLineY--) | 指定绘图页面上动态连接线之间的最小垂直间距。 |
| [getLineToNodeX()](#getLineToNodeX--) | 指定绘图页面上动态连接线与形状之间的最小垂直间距。 |
| [getLineToNodeY()](#getLineToNodeY--) | 确定水平块大小，即在使用 Microsoft Visio 对绘图页面上的形状进行布局时，每个形状必须适应的区域。 |
| [getPageLineJumpDirX()](#getPageLineJumpDirX--) | 指定在绘图页面上动态连接线的垂直段上未应用本地跳转方向的线路跳转方向。 |
| [getPageLineJumpDirY()](#getPageLineJumpDirY--) | 指定绘图页面上动态连接线与形状之间的最小水平间距。 |
| [getPageShapeSplit()](#getPageShapeSplit--) | 指示页面上的形状是否可以自动拆分。 |
| [getPlaceDepth()](#getPlaceDepth--) | 指定当用户在绘图页面上将可放置形状拖动到另一个可放置形状附近时，可放置形状是否会移动开。 |
| [getPlaceFlip()](#getPlaceFlip--) | 指定在 Microsoft Visio 中使用“布局形状”命令布局形状时，可放置形状在页面上的翻转和/或旋转方式。 |
| [getPlaceStyle()](#getPlaceStyle--) | 指定绘图页面上所有没有本地路由样式的动态连接器的路由样式和方向。 |
| [getPlowCode()](#getPlowCode--) | 确定要为其添加跳接的动态连接器。 |
| [getResizePage()](#getResizePage--) | 指定在用户选择“布局形状”（形状菜单）后，是否扩大页面以容纳绘图。 |
| [getRouteStyle()](#getRouteStyle--) | 对于自动布局的绘图，指定在创建布局之前对绘图进行分析的方法，并确定布局类型。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | 有关此属性的描述，请参阅 [getDel()](../../com.aspose.diagram/pagelayout\\#getDel--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getAvenueSizeX() {#getAvenueSizeX--}
```
public DoubleValue getAvenueSizeX()
```


确定在使用 Microsoft Visio 对绘图页面上的形状进行布局时，形状之间的垂直间距。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getAvenueSizeY() {#getAvenueSizeY--}
```
public DoubleValue getAvenueSizeY()
```


确定在使用 Microsoft Visio 对绘图页面上的形状进行布局时，形状之间的垂直间距。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getAvoidPageBreaks() {#getAvoidPageBreaks--}
```
public BoolValue getAvoidPageBreaks()
```


指定当用户在“形状”菜单中选择“布局形状”时，形状在页面上的放置方式。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getBlockSizeX() {#getBlockSizeX--}
```
public DoubleValue getBlockSizeX()
```


确定垂直块大小，即在使用 Microsoft Visio 对绘图页面上的形状进行布局时，每个形状必须适应的区域。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBlockSizeY() {#getBlockSizeY--}
```
public DoubleValue getBlockSizeY()
```


确定在使用 Microsoft Visio 对绘图页面上的形状进行布局时，形状之间的水平间距。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCtrlAsInput() {#getCtrlAsInput--}
```
public BoolValue getCtrlAsInput()
```


确定在使用控制手柄操作形状时，哪个形状是父形状。此元素设置绘图页面上所有形状的行为。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getDel() {#getDel--}
```
public int getDel()
```


一个标志，指示元素是否已在本地删除。值为 1 表示该元素已在本地删除。

**Returns:**
int
### getDynamicsOff() {#getDynamicsOff--}
```
public BoolValue getDynamicsOff()
```


指定可放置形状是否移动，以及连接线是否在绘图页面上绕过其他形状和连接线重新路由。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getEnableGrid() {#getEnableGrid--}
```
public BoolValue getEnableGrid()
```


指定当用户选择“布局形状”（形状菜单）时，Microsoft Visio 是否基于内部页面网格布局形状。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLineAdjustFrom() {#getLineAdjustFrom--}
```
public LineAdjustFrom getLineAdjustFrom()
```


指定在动态连接器相互重叠时需要分开的连接器。

**Returns:**
[LineAdjustFrom](../../com.aspose.diagram/lineadjustfrom)
### getLineAdjustTo() {#getLineAdjustTo--}
```
public LineAdjustTo getLineAdjustTo()
```


指定在动态连接器相互重叠时需要对齐的连接器。

**Returns:**
[LineAdjustTo](../../com.aspose.diagram/lineadjustto)
### getLineJumpCode() {#getLineJumpCode--}
```
public LineJumpCode getLineJumpCode()
```


指定绘图页面上所有未设置本地线跳样式的连接器的线跳样式。

**Returns:**
[LineJumpCode](../../com.aspose.diagram/linejumpcode)
### getLineJumpFactorX() {#getLineJumpFactorX--}
```
public DoubleValue getLineJumpFactorX()
```


指定页面上动态连接线水平段的跳线大小，作为 LineToLineX 元素值的百分比（该元素指定绘图页面上所有连接线之间的水平间距）。此元素的取值范围为 0 到 10。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineJumpFactorY() {#getLineJumpFactorY--}
```
public DoubleValue getLineJumpFactorY()
```


指定页面上动态连接线垂直段的跳线大小，作为 LineToLineY 元素值的百分比（该元素指定绘图页面上所有连接线之间的垂直间距）。此元素的取值范围为 0 到 10。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineJumpStyle() {#getLineJumpStyle--}
```
public LineJumpStyle getLineJumpStyle()
```


指定在绘图页面上动态连接线的水平段上未应用本地跳转方向的线路跳转方向。

**Returns:**
[LineJumpStyle](../../com.aspose.diagram/linejumpstyle)
### getLineRouteExt() {#getLineRouteExt--}
```
public LineRouteExt getLineRouteExt()
```


指定页面上所有连接器的默认外观。

**Returns:**
[LineRouteExt](../../com.aspose.diagram/linerouteext)
### getLineToLineX() {#getLineToLineX--}
```
public DoubleValue getLineToLineX()
```


指定绘图页面上动态连接线之间的最小水平间距。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineToLineY() {#getLineToLineY--}
```
public DoubleValue getLineToLineY()
```


指定绘图页面上动态连接线之间的最小垂直间距。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineToNodeX() {#getLineToNodeX--}
```
public DoubleValue getLineToNodeX()
```


指定绘图页面上动态连接线与形状之间的最小垂直间距。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineToNodeY() {#getLineToNodeY--}
```
public DoubleValue getLineToNodeY()
```


确定水平块大小，即在使用 Microsoft Visio 对绘图页面上的形状进行布局时，每个形状必须适应的区域。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPageLineJumpDirX() {#getPageLineJumpDirX--}
```
public PageLineJumpDirX getPageLineJumpDirX()
```


指定在绘图页面上动态连接线的垂直段上未应用本地跳转方向的线路跳转方向。

**Returns:**
[PageLineJumpDirX](../../com.aspose.diagram/pagelinejumpdirx)
### getPageLineJumpDirY() {#getPageLineJumpDirY--}
```
public PageLineJumpDirY getPageLineJumpDirY()
```


指定绘图页面上动态连接线与形状之间的最小水平间距。

**Returns:**
[PageLineJumpDirY](../../com.aspose.diagram/pagelinejumpdiry)
### getPageShapeSplit() {#getPageShapeSplit--}
```
public BoolValue getPageShapeSplit()
```


指示页面上的形状是否可以自动拆分。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getPlaceDepth() {#getPlaceDepth--}
```
public PlaceDepth getPlaceDepth()
```


指定当用户在绘图页面上将可放置形状拖动到另一个可放置形状附近时，可放置形状是否会移动开。

**Returns:**
[PlaceDepth](../../com.aspose.diagram/placedepth)
### getPlaceFlip() {#getPlaceFlip--}
```
public PlaceFlip getPlaceFlip()
```


指定在使用 Microsoft Visio 的“布局形状”命令布置形状时，可放置形状在页面上如何翻转和/或旋转。允许使用以下十六进制值。

**Returns:**
[PlaceFlip](../../com.aspose.diagram/placeflip)
### getPlaceStyle() {#getPlaceStyle--}
```
public PlaceStyle getPlaceStyle()
```


指定绘图页面上所有没有本地路由样式的动态连接器的路由样式和方向。

**Returns:**
[PlaceStyle](../../com.aspose.diagram/placestyle)
### getPlowCode() {#getPlowCode--}
```
public BoolValue getPlowCode()
```


确定要为其添加跳接的动态连接器。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getResizePage() {#getResizePage--}
```
public BoolValue getResizePage()
```


指定在用户选择“布局形状”（形状菜单）后，是否扩大页面以容纳绘图。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getRouteStyle() {#getRouteStyle--}
```
public RouteStyle getRouteStyle()
```


对于自动布局的绘图，指定在创建布局之前对绘图进行分析的方法，并确定布局类型。

**Returns:**
[RouteStyle](../../com.aspose.diagram/routestyle)
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


有关此属性的描述，请参阅 [getDel()](../../com.aspose.diagram/pagelayout\\#getDel--)

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

