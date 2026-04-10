---
title: 填充
second_title: Aspose.Diagram for Java API 参考
description: 包含形状及其投影的当前填充格式值，包括图案前景色和背景色。
type: docs
weight: 153
url: /zh/java/com.aspose.diagram/fill/
---

**Inheritance:**
java.lang.Object
```
public class Fill
```

包含形状及其投影的当前填充格式值，包括图案、前景色和背景色。
## 方法

| 方法 | 描述 |
| --- | --- |
| [deepClone()](#deepClone--) | 创建此实例的深度副本。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | 指示元素是否已在本地删除的标志。 |
| [getFillBkgnd()](#getFillBkgnd--) | 指定用于形状填充图案背景的颜色。 |
| [getFillBkgndTrans()](#getFillBkgndTrans--) | 指定形状填充图案背景（填充）颜色的透明度级别，范围从 0（完全不透明）到 1（完全透明）。 |
| [getFillForegnd()](#getFillForegnd--) | 指定用于形状填充图案前景（描边）的颜色。 |
| [getFillForegndTrans()](#getFillForegndTrans--) | 指定形状填充图案前景（填充）颜色的透明度级别，范围从 0（完全不透明）到 1（完全透明）。 |
| [getFillPattern()](#getFillPattern--) | 指定形状的填充图案。 |
| [getGradientFill()](#getGradientFill--) | 包含形状当前的渐变填充格式值 |
| [getShapeShdwBlur()](#getShapeShdwBlur--) | 指定形状阴影的模糊大小。 |
| [getShapeShdwObliqueAngle()](#getShapeShdwObliqueAngle--) | 指定形状阴影的倾斜方向角度。 |
| [getShapeShdwOffsetX()](#getShapeShdwOffsetX--) | 确定形状阴影相对于形状在水平方向上的页面单位偏移距离。 |
| [getShapeShdwOffsetY()](#getShapeShdwOffsetY--) | 确定形状阴影相对于形状在垂直方向上的页面单位偏移距离。 |
| [getShapeShdwScaleFactor()](#getShapeShdwScaleFactor--) | 指定形状阴影可以放大或缩小的百分比。 |
| [getShapeShdwShow()](#getShapeShdwShow--) | 指定形状的阴影类型。 |
| [getShapeShdwType()](#getShapeShdwType--) | 指定形状的阴影类型。 |
| [getShdwBkgnd()](#getShdwBkgnd--) | 指定用于形状投影填充图案背景（填充）的颜色。 |
| [getShdwBkgndTrans()](#getShdwBkgndTrans--) | 指定形状投影填充图案背景（填充）的透明度级别，范围从 0.0（完全不透明）到 1.0（完全透明）。 |
| [getShdwForegnd()](#getShdwForegnd--) | 指定用于形状投影填充图案前景（描边）的颜色。 |
| [getShdwForegndTrans()](#getShdwForegndTrans--) | 指定形状投影填充图案前景（描边）的透明度级别，范围从 0.0（完全不透明）到 1.0（完全透明）。 |
| [getShdwPattern()](#getShdwPattern--) | 指定形状阴影的填充图案。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | 有关此属性的描述，请参阅 [getDel()](../../com.aspose.diagram/fill\#getDel--) |
| [setFillBkgnd(ColorValue value)](#setFillBkgnd-com.aspose.diagram.ColorValue-) | 有关此属性的描述，请参阅 [getFillBkgnd()](../../com.aspose.diagram/fill\#getFillBkgnd--) |
| [setFillBkgndTrans(DoubleValue value)](#setFillBkgndTrans-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getFillBkgndTrans()](../../com.aspose.diagram/fill\#getFillBkgndTrans--) |
| [setFillForegnd(ColorValue value)](#setFillForegnd-com.aspose.diagram.ColorValue-) | 有关此属性的描述，请参阅 [getFillForegnd()](../../com.aspose.diagram/fill\#getFillForegnd--) |
| [setFillForegndTrans(DoubleValue value)](#setFillForegndTrans-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getFillForegndTrans()](../../com.aspose.diagram/fill\#getFillForegndTrans--) |
| [setFillPattern(IntValue value)](#setFillPattern-com.aspose.diagram.IntValue-) | 有关此属性的描述，请参阅 [getFillPattern()](../../com.aspose.diagram/fill\#getFillPattern--) |
| [setShapeShdwBlur(DoubleValue value)](#setShapeShdwBlur-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getShapeShdwBlur()](../../com.aspose.diagram/fill\#getShapeShdwBlur--) |
| [setShapeShdwObliqueAngle(DoubleValue value)](#setShapeShdwObliqueAngle-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getShapeShdwObliqueAngle()](../../com.aspose.diagram/fill\#getShapeShdwObliqueAngle--) |
| [setShapeShdwOffsetX(DoubleValue value)](#setShapeShdwOffsetX-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getShapeShdwOffsetX()](../../com.aspose.diagram/fill\\#getShapeShdwOffsetX--) |
| [setShapeShdwOffsetY(DoubleValue value)](#setShapeShdwOffsetY-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getShapeShdwOffsetY()](../../com.aspose.diagram/fill\\#getShapeShdwOffsetY--) |
| [setShapeShdwScaleFactor(DoubleValue value)](#setShapeShdwScaleFactor-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getShapeShdwScaleFactor()](../../com.aspose.diagram/fill\\#getShapeShdwScaleFactor--) |
| [setShapeShdwShow(ShapeShdwShow value)](#setShapeShdwShow-com.aspose.diagram.ShapeShdwShow-) | 有关此属性的描述，请参阅 [getShapeShdwShow()](../../com.aspose.diagram/fill\\#getShapeShdwShow--) |
| [setShapeShdwType(ShapeShdwType value)](#setShapeShdwType-com.aspose.diagram.ShapeShdwType-) | 有关此属性的描述，请参阅 [getShapeShdwType()](../../com.aspose.diagram/fill\\#getShapeShdwType--) |
| [setShdwBkgnd(ColorValue value)](#setShdwBkgnd-com.aspose.diagram.ColorValue-) | 有关此属性的描述，请参阅 [getShdwBkgnd()](../../com.aspose.diagram/fill\\#getShdwBkgnd--) |
| [setShdwBkgndTrans(DoubleValue value)](#setShdwBkgndTrans-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getShdwBkgndTrans()](../../com.aspose.diagram/fill\\#getShdwBkgndTrans--) |
| [setShdwForegnd(ColorValue value)](#setShdwForegnd-com.aspose.diagram.ColorValue-) | 有关此属性的描述，请参阅 [getShdwForegnd()](../../com.aspose.diagram/fill\\#getShdwForegnd--) |
| [setShdwForegndTrans(DoubleValue value)](#setShdwForegndTrans-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getShdwForegndTrans()](../../com.aspose.diagram/fill\\#getShdwForegndTrans--) |
| [setShdwPattern(IntValue value)](#setShdwPattern-com.aspose.diagram.IntValue-) | 有关此属性的描述，请参阅 [getShdwPattern()](../../com.aspose.diagram/fill\\#getShdwPattern--) |
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
### getFillBkgnd() {#getFillBkgnd--}
```
public ColorValue getFillBkgnd()
```


指定用于形状填充图案背景的颜色。

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getFillBkgndTrans() {#getFillBkgndTrans--}
```
public DoubleValue getFillBkgndTrans()
```


指定形状填充图案背景（填充）颜色的透明度级别，范围从 0（完全不透明）到 1（完全透明）。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getFillForegnd() {#getFillForegnd--}
```
public ColorValue getFillForegnd()
```


指定用于形状填充图案前景（描边）的颜色。

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getFillForegndTrans() {#getFillForegndTrans--}
```
public DoubleValue getFillForegndTrans()
```


指定形状填充图案前景（填充）颜色的透明度级别，范围从 0（完全不透明）到 1（完全透明）。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getFillPattern() {#getFillPattern--}
```
public IntValue getFillPattern()
```


指定形状的填充图案。

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getGradientFill() {#getGradientFill--}
```
public GradientFill getGradientFill()
```


包含形状当前的渐变填充格式值

**Returns:**
[GradientFill](../../com.aspose.diagram/gradientfill)
### getShapeShdwBlur() {#getShapeShdwBlur--}
```
public DoubleValue getShapeShdwBlur()
```


指定形状的阴影模糊大小。目前无法绘制模糊，但可以从 vsdx 解析。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShapeShdwObliqueAngle() {#getShapeShdwObliqueAngle--}
```
public DoubleValue getShapeShdwObliqueAngle()
```


指定形状阴影的倾斜方向角度。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShapeShdwOffsetX() {#getShapeShdwOffsetX--}
```
public DoubleValue getShapeShdwOffsetX()
```


确定形状阴影相对于形状在水平方向上的页面单位偏移距离。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShapeShdwOffsetY() {#getShapeShdwOffsetY--}
```
public DoubleValue getShapeShdwOffsetY()
```


确定形状阴影相对于形状在垂直方向上的页面单位偏移距离。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShapeShdwScaleFactor() {#getShapeShdwScaleFactor--}
```
public DoubleValue getShapeShdwScaleFactor()
```


指定形状阴影可以放大或缩小的百分比。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShapeShdwShow() {#getShapeShdwShow--}
```
public ShapeShdwShow getShapeShdwShow()
```


指定形状的阴影类型。

**Returns:**
[ShapeShdwShow](../../com.aspose.diagram/shapeshdwshow)
### getShapeShdwType() {#getShapeShdwType--}
```
public ShapeShdwType getShapeShdwType()
```


指定形状的阴影类型。

**Returns:**
[ShapeShdwType](../../com.aspose.diagram/shapeshdwtype)
### getShdwBkgnd() {#getShdwBkgnd--}
```
public ColorValue getShdwBkgnd()
```


指定用于形状投影填充图案背景（填充）的颜色。

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getShdwBkgndTrans() {#getShdwBkgndTrans--}
```
public DoubleValue getShdwBkgndTrans()
```


指定形状投影填充图案背景（填充）的透明度级别，范围从 0.0（完全不透明）到 1.0（完全透明）。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwForegnd() {#getShdwForegnd--}
```
public ColorValue getShdwForegnd()
```


指定用于形状投影填充图案前景（描边）的颜色。

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getShdwForegndTrans() {#getShdwForegndTrans--}
```
public DoubleValue getShdwForegndTrans()
```


指定形状投影填充图案前景（描边）的透明度级别，范围从 0.0（完全不透明）到 1.0（完全透明）。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwPattern() {#getShdwPattern--}
```
public IntValue getShdwPattern()
```


指定形状阴影的填充图案。

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
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


有关此属性的描述，请参阅 [getDel()](../../com.aspose.diagram/fill\#getDel--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setFillBkgnd(ColorValue value) {#setFillBkgnd-com.aspose.diagram.ColorValue-}
```
public void setFillBkgnd(ColorValue value)
```


有关此属性的描述，请参阅 [getFillBkgnd()](../../com.aspose.diagram/fill\#getFillBkgnd--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setFillBkgndTrans(DoubleValue value) {#setFillBkgndTrans-com.aspose.diagram.DoubleValue-}
```
public void setFillBkgndTrans(DoubleValue value)
```


有关此属性的描述，请参阅 [getFillBkgndTrans()](../../com.aspose.diagram/fill\#getFillBkgndTrans--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setFillForegnd(ColorValue value) {#setFillForegnd-com.aspose.diagram.ColorValue-}
```
public void setFillForegnd(ColorValue value)
```


有关此属性的描述，请参阅 [getFillForegnd()](../../com.aspose.diagram/fill\#getFillForegnd--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setFillForegndTrans(DoubleValue value) {#setFillForegndTrans-com.aspose.diagram.DoubleValue-}
```
public void setFillForegndTrans(DoubleValue value)
```


有关此属性的描述，请参阅 [getFillForegndTrans()](../../com.aspose.diagram/fill\#getFillForegndTrans--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setFillPattern(IntValue value) {#setFillPattern-com.aspose.diagram.IntValue-}
```
public void setFillPattern(IntValue value)
```


有关此属性的描述，请参阅 [getFillPattern()](../../com.aspose.diagram/fill\#getFillPattern--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setShapeShdwBlur(DoubleValue value) {#setShapeShdwBlur-com.aspose.diagram.DoubleValue-}
```
public void setShapeShdwBlur(DoubleValue value)
```


有关此属性的描述，请参阅 [getShapeShdwBlur()](../../com.aspose.diagram/fill\#getShapeShdwBlur--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShapeShdwObliqueAngle(DoubleValue value) {#setShapeShdwObliqueAngle-com.aspose.diagram.DoubleValue-}
```
public void setShapeShdwObliqueAngle(DoubleValue value)
```


有关此属性的描述，请参阅 [getShapeShdwObliqueAngle()](../../com.aspose.diagram/fill\#getShapeShdwObliqueAngle--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShapeShdwOffsetX(DoubleValue value) {#setShapeShdwOffsetX-com.aspose.diagram.DoubleValue-}
```
public void setShapeShdwOffsetX(DoubleValue value)
```


有关此属性的描述，请参阅 [getShapeShdwOffsetX()](../../com.aspose.diagram/fill\\#getShapeShdwOffsetX--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShapeShdwOffsetY(DoubleValue value) {#setShapeShdwOffsetY-com.aspose.diagram.DoubleValue-}
```
public void setShapeShdwOffsetY(DoubleValue value)
```


有关此属性的描述，请参阅 [getShapeShdwOffsetY()](../../com.aspose.diagram/fill\\#getShapeShdwOffsetY--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShapeShdwScaleFactor(DoubleValue value) {#setShapeShdwScaleFactor-com.aspose.diagram.DoubleValue-}
```
public void setShapeShdwScaleFactor(DoubleValue value)
```


有关此属性的描述，请参阅 [getShapeShdwScaleFactor()](../../com.aspose.diagram/fill\\#getShapeShdwScaleFactor--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShapeShdwShow(ShapeShdwShow value) {#setShapeShdwShow-com.aspose.diagram.ShapeShdwShow-}
```
public void setShapeShdwShow(ShapeShdwShow value)
```


有关此属性的描述，请参阅 [getShapeShdwShow()](../../com.aspose.diagram/fill\\#getShapeShdwShow--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ShapeShdwShow](../../com.aspose.diagram/shapeshdwshow) |  |

### setShapeShdwType(ShapeShdwType value) {#setShapeShdwType-com.aspose.diagram.ShapeShdwType-}
```
public void setShapeShdwType(ShapeShdwType value)
```


有关此属性的描述，请参阅 [getShapeShdwType()](../../com.aspose.diagram/fill\\#getShapeShdwType--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ShapeShdwType](../../com.aspose.diagram/shapeshdwtype) |  |

### setShdwBkgnd(ColorValue value) {#setShdwBkgnd-com.aspose.diagram.ColorValue-}
```
public void setShdwBkgnd(ColorValue value)
```


有关此属性的描述，请参阅 [getShdwBkgnd()](../../com.aspose.diagram/fill\\#getShdwBkgnd--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setShdwBkgndTrans(DoubleValue value) {#setShdwBkgndTrans-com.aspose.diagram.DoubleValue-}
```
public void setShdwBkgndTrans(DoubleValue value)
```


有关此属性的描述，请参阅 [getShdwBkgndTrans()](../../com.aspose.diagram/fill\\#getShdwBkgndTrans--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShdwForegnd(ColorValue value) {#setShdwForegnd-com.aspose.diagram.ColorValue-}
```
public void setShdwForegnd(ColorValue value)
```


有关此属性的描述，请参阅 [getShdwForegnd()](../../com.aspose.diagram/fill\\#getShdwForegnd--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setShdwForegndTrans(DoubleValue value) {#setShdwForegndTrans-com.aspose.diagram.DoubleValue-}
```
public void setShdwForegndTrans(DoubleValue value)
```


有关此属性的描述，请参阅 [getShdwForegndTrans()](../../com.aspose.diagram/fill\\#getShdwForegndTrans--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShdwPattern(IntValue value) {#setShdwPattern-com.aspose.diagram.IntValue-}
```
public void setShdwPattern(IntValue value)
```


有关此属性的描述，请参阅 [getShdwPattern()](../../com.aspose.diagram/fill\\#getShdwPattern--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

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

