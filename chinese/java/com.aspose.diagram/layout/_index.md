---
title: 布局
second_title: Aspose.Diagram for Java API 参考
description: 包含控制形状放置和连接器路由设置的元素。
type: docs
weight: 215
url: /zh/java/com.aspose.diagram/layout/
---

**Inheritance:**
java.lang.Object
```
public class Layout
```

包含控制形状放置和连接器路由设置的元素。
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getConFixedCode()](#getConFixedCode--) | 确定连接线何时重新路由。 |
| [getConLineJumpCode()](#getConLineJumpCode--) | 确定当两个连接器交叉时，连接器是否跳过， |
| [getConLineJumpDirX()](#getConLineJumpDirX--) | 确定动态连接线水平段上出现的线跳的跳转方向。 |
| [getConLineJumpDirY()](#getConLineJumpDirY--) | 确定动态连接线垂直段上出现的线跳的跳转方向。 |
| [getConLineJumpStyle()](#getConLineJumpStyle--) | 确定动态连接线线上跳的样式。 |
| [getConLineRouteExt()](#getConLineRouteExt--) | 确定连接线的外观。 |
| [getDel()](#getDel--) | 指示元素是否已在本地删除的标志。 |
| [getDisplayLevel()](#getDisplayLevel--) | 确定形状的显示层级带（Z 顺序分组的相对范围）。 |
| [getRelationships()](#getRelationships--) | 存储容器、列表、标注和形状之间的关系。 |
| [getShapeFixedCode()](#getShapeFixedCode--) | 指定可放置形状的放置行为。 |
| [getShapePermeablePlace()](#getShapePermeablePlace--) | 指定当用户在“布局形状”（形状菜单）中选择时，可放置形状是否可以放置在形状之上。 |
| [getShapePermeableX()](#getShapePermeableX--) | 指定连接器是否可以水平穿过形状。 |
| [getShapePermeableY()](#getShapePermeableY--) | 指定连接器是否可以垂直穿过形状。 |
| [getShapePlaceFlip()](#getShapePlaceFlip--) | 指定当用户在页面上选择“布局形状”（形状菜单）时，可放置形状如何翻转和/或旋转。 |
| [getShapePlaceStyle()](#getShapePlaceStyle--) | 确定子对象的放置样式。 |
| [getShapePlowCode()](#getShapePlowCode--) | 指定当您将另一个可放置形状拖动到绘图页面上靠近该形状时，该可放置形状是否会移动。 |
| [getShapeRouteStyle()](#getShapeRouteStyle--) | 指定绘图页面上连接器的路由样式和方向。 |
| [getShapeSplit()](#getShapeSplit--) | 确定此形状是否可以拆分可拆分的形状。 |
| [getShapeSplittable()](#getShapeSplittable--) | 确定此一维形状是否可以拆分。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | 有关此属性的描述，请参阅 [getDel()](../../com.aspose.diagram/layout\#getDel--) |
| [setShapePlaceStyle(ShapePlaceStyle value)](#setShapePlaceStyle-com.aspose.diagram.ShapePlaceStyle-) | 有关此属性的描述，请参阅 [getShapePlaceStyle()](../../com.aspose.diagram/layout\#getShapePlaceStyle--) |
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConFixedCode() {#getConFixedCode--}
```
public ConFixedCode getConFixedCode()
```


确定连接线何时重新路由。

**Returns:**
[ConFixedCode](../../com.aspose.diagram/confixedcode)
### getConLineJumpCode() {#getConLineJumpCode--}
```
public ConLineJumpCode getConLineJumpCode()
```


确定当两个连接器交叉时，连接器是否跳过，

**Returns:**
[ConLineJumpCode](../../com.aspose.diagram/conlinejumpcode)
### getConLineJumpDirX() {#getConLineJumpDirX--}
```
public ConLineJumpDirX getConLineJumpDirX()
```


确定动态连接线水平段上出现的线跳的跳转方向。

**Returns:**
[ConLineJumpDirX](../../com.aspose.diagram/conlinejumpdirx)
### getConLineJumpDirY() {#getConLineJumpDirY--}
```
public ConLineJumpDirY getConLineJumpDirY()
```


确定动态连接线垂直段上出现的线跳的跳转方向。

**Returns:**
[ConLineJumpDirY](../../com.aspose.diagram/conlinejumpdiry)
### getConLineJumpStyle() {#getConLineJumpStyle--}
```
public ConLineJumpStyle getConLineJumpStyle()
```


确定动态连接线线上跳的样式。

**Returns:**
[ConLineJumpStyle](../../com.aspose.diagram/conlinejumpstyle)
### getConLineRouteExt() {#getConLineRouteExt--}
```
public ConLineRouteExt getConLineRouteExt()
```


确定连接线的外观。

**Returns:**
[ConLineRouteExt](../../com.aspose.diagram/conlinerouteext)
### getDel() {#getDel--}
```
public int getDel()
```


一个标志，指示元素是否已在本地删除。值为 1 表示该元素已在本地删除。

**Returns:**
int
### getDisplayLevel() {#getDisplayLevel--}
```
public IntValue getDisplayLevel()
```


确定形状的显示层级带（Z 顺序分组的相对范围）。

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getRelationships() {#getRelationships--}
```
public BoolValue getRelationships()
```


存储容器、列表、标注和形状之间的关系。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapeFixedCode() {#getShapeFixedCode--}
```
public ShapeFixedCode getShapeFixedCode()
```


指定可放置形状的放置行为。

**Returns:**
[ShapeFixedCode](../../com.aspose.diagram/shapefixedcode)
### getShapePermeablePlace() {#getShapePermeablePlace--}
```
public BoolValue getShapePermeablePlace()
```


指定当用户在“布局形状”（形状菜单）中选择时，可放置形状是否可以放置在形状之上。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapePermeableX() {#getShapePermeableX--}
```
public BoolValue getShapePermeableX()
```


指定连接器是否可以水平穿过形状。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapePermeableY() {#getShapePermeableY--}
```
public BoolValue getShapePermeableY()
```


指定连接器是否可以垂直穿过形状。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapePlaceFlip() {#getShapePlaceFlip--}
```
public ShapePlaceFlip getShapePlaceFlip()
```


指定当用户在页面上选择“布局形状”（形状菜单）时，可放置形状如何翻转和/或旋转。

**Returns:**
[ShapePlaceFlip](../../com.aspose.diagram/shapeplaceflip)
### getShapePlaceStyle() {#getShapePlaceStyle--}
```
public ShapePlaceStyle getShapePlaceStyle()
```


确定子对象的放置样式。

**Returns:**
[ShapePlaceStyle](../../com.aspose.diagram/shapeplacestyle)
### getShapePlowCode() {#getShapePlowCode--}
```
public ShapePlowCode getShapePlowCode()
```


指定当您将另一个可放置形状拖动到绘图页面上靠近该形状时，该可放置形状是否会移动。

**Returns:**
[ShapePlowCode](../../com.aspose.diagram/shapeplowcode)
### getShapeRouteStyle() {#getShapeRouteStyle--}
```
public ShapeRouteStyle getShapeRouteStyle()
```


指定绘图页面上连接器的路由样式和方向。

**Returns:**
[ShapeRouteStyle](../../com.aspose.diagram/shaperoutestyle)
### getShapeSplit() {#getShapeSplit--}
```
public BoolValue getShapeSplit()
```


确定此形状是否可以拆分可拆分的形状。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapeSplittable() {#getShapeSplittable--}
```
public BoolValue getShapeSplittable()
```


确定此一维形状是否可以拆分。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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


有关此属性的描述，请参阅 [getDel()](../../com.aspose.diagram/layout\#getDel--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setShapePlaceStyle(ShapePlaceStyle value) {#setShapePlaceStyle-com.aspose.diagram.ShapePlaceStyle-}
```
public void setShapePlaceStyle(ShapePlaceStyle value)
```


有关此属性的描述，请参阅 [getShapePlaceStyle()](../../com.aspose.diagram/layout\#getShapePlaceStyle--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ShapePlaceStyle](../../com.aspose.diagram/shapeplacestyle) |  |

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

