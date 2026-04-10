---
title: Line
second_title: Aspose.Diagram for Java API 参考
description: 包含指定形状一般位置信息的元素。
type: docs
weight: 221
url: /zh/java/com.aspose.diagram/line/
---

**Inheritance:**
java.lang.Object
```
public class Line
```

包含指定形状一般位置信息的元素。
## 方法

| 方法 | 描述 |
| --- | --- |
| [deepClone()](#deepClone--) | 创建此实例的深度副本。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBeginArrow()](#getBeginArrow--) | 指示线在其第一个顶点是否具有箭头或其他线端格式。 |
| [getBeginArrowSize()](#getBeginArrowSize--) | 确定线起始处箭头的大小。 |
| [getClass()](#getClass--) |  |
| [getCompoundType()](#getCompoundType--) | 指定形状的线复合类型。 |
| [getDel()](#getDel--) | 指示元素是否已在本地删除的标志。 |
| [getEndArrow()](#getEndArrow--) | 指示线在其最后一个顶点是否具有箭头或其他线端格式。 |
| [getEndArrowSize()](#getEndArrowSize--) | 指定线末端箭头的大小。 |
| [getGradientLine()](#getGradientLine--) | 包含形状当前的渐变线格式值 |
| [getLineCap()](#getLineCap--) | 指定线的端点是圆形还是方形。 |
| [getLineColor()](#getLineColor--) | 指定形状的线颜色。 |
| [getLineColorTrans()](#getLineColorTrans--) | 指定形状线颜色的透明度级别，范围从 0（不透明）到 1（完全透明）。 |
| [getLinePattern()](#getLinePattern--) | 指定形状的线型模式 |
| [getLineWeight()](#getLineWeight--) | 指定形状的线粗细。 |
| [getRounding()](#getRounding--) | 指定路径中两个连续段相接处应用的圆弧半径。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBeginArrow(IntValue value)](#setBeginArrow-com.aspose.diagram.IntValue-) | 有关此属性的描述，请参阅 [getBeginArrow()](../../com.aspose.diagram/line\#getBeginArrow--) |
| [setBeginArrowSize(ArrowSize value)](#setBeginArrowSize-com.aspose.diagram.ArrowSize-) | 有关此属性的描述，请参阅 [getBeginArrowSize()](../../com.aspose.diagram/line\#getBeginArrowSize--) |
| [setCompoundType(CompoundType value)](#setCompoundType-com.aspose.diagram.CompoundType-) | 有关此属性的描述，请参阅 [getCompoundType()](../../com.aspose.diagram/line\#getCompoundType--) |
| [setDel(int value)](#setDel-int-) | 有关此属性的描述，请参阅 [getDel()](../../com.aspose.diagram/line\#getDel--) |
| [setEndArrow(IntValue value)](#setEndArrow-com.aspose.diagram.IntValue-) | 有关此属性的描述，请参阅 [getEndArrow()](../../com.aspose.diagram/line\#getEndArrow--) |
| [setEndArrowSize(ArrowSize value)](#setEndArrowSize-com.aspose.diagram.ArrowSize-) | 有关此属性的描述，请参阅 [getEndArrowSize()](../../com.aspose.diagram/line\#getEndArrowSize--) |
| [setLineCap(BoolValue value)](#setLineCap-com.aspose.diagram.BoolValue-) | 有关此属性的描述，请参阅 [getLineCap()](../../com.aspose.diagram/line\#getLineCap--) |
| [setLineColor(ColorValue value)](#setLineColor-com.aspose.diagram.ColorValue-) | 有关此属性的描述，请参阅 [getLineColor()](../../com.aspose.diagram/line\#getLineColor--) |
| [setLineColorTrans(DoubleValue value)](#setLineColorTrans-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getLineColorTrans()](../../com.aspose.diagram/line\#getLineColorTrans--) |
| [setLinePattern(IntValue value)](#setLinePattern-com.aspose.diagram.IntValue-) | 有关此属性的描述，请参阅 [getLinePattern()](../../com.aspose.diagram/line\#getLinePattern--) |
| [setLineWeight(DoubleValue value)](#setLineWeight-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getLineWeight()](../../com.aspose.diagram/line\#getLineWeight--) |
| [setRounding(DoubleValue value)](#setRounding-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getRounding()](../../com.aspose.diagram/line\#getRounding--) |
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
### getBeginArrow() {#getBeginArrow--}
```
public IntValue getBeginArrow()
```


指示线在其第一个顶点是否具有箭头或其他线端格式。输入 0 到 45 之间的数字，或使用带有自定义线端名称的 USE 函数。

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getBeginArrowSize() {#getBeginArrowSize--}
```
public ArrowSize getBeginArrowSize()
```


确定线段起始处箭头的大小。请输入 0 到 6 之间的数字。

**Returns:**
[ArrowSize](../../com.aspose.diagram/arrowsize)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCompoundType() {#getCompoundType--}
```
public CompoundType getCompoundType()
```


指定形状的线复合类型。

**Returns:**
[CompoundType](../../com.aspose.diagram/compoundtype)
### getDel() {#getDel--}
```
public int getDel()
```


一个标志，指示元素是否已在本地删除。值为 1 表示该元素已在本地删除。

**Returns:**
int
### getEndArrow() {#getEndArrow--}
```
public IntValue getEndArrow()
```


指示线在其最后一个顶点是否具有箭头或其他线端格式。

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getEndArrowSize() {#getEndArrowSize--}
```
public ArrowSize getEndArrowSize()
```


指定线末端箭头的大小。

**Returns:**
[ArrowSize](../../com.aspose.diagram/arrowsize)
### getGradientLine() {#getGradientLine--}
```
public GradientFill getGradientLine()
```


包含形状当前的渐变线格式值

**Returns:**
[GradientFill](../../com.aspose.diagram/gradientfill)
### getLineCap() {#getLineCap--}
```
public BoolValue getLineCap()
```


指定线的端点是圆形还是方形。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLineColor() {#getLineColor--}
```
public ColorValue getLineColor()
```


指定形状的线颜色。

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getLineColorTrans() {#getLineColorTrans--}
```
public DoubleValue getLineColorTrans()
```


指定形状线条颜色的透明度级别，范围从 0（不透明）到 1（完全透明）。默认值为 0。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLinePattern() {#getLinePattern--}
```
public IntValue getLinePattern()
```


指定形状的线型模式

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getLineWeight() {#getLineWeight--}
```
public DoubleValue getLineWeight()
```


指定形状的线宽。线宽独立于图形的比例尺。如果对图形进行缩放，线宽保持不变。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getRounding() {#getRounding--}
```
public DoubleValue getRounding()
```


指定路径中相邻两段相接处的圆弧半径。例如，可使用圆角来为矩形添加圆角。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
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




### setBeginArrow(IntValue value) {#setBeginArrow-com.aspose.diagram.IntValue-}
```
public void setBeginArrow(IntValue value)
```


有关此属性的描述，请参阅 [getBeginArrow()](../../com.aspose.diagram/line\#getBeginArrow--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setBeginArrowSize(ArrowSize value) {#setBeginArrowSize-com.aspose.diagram.ArrowSize-}
```
public void setBeginArrowSize(ArrowSize value)
```


有关此属性的描述，请参阅 [getBeginArrowSize()](../../com.aspose.diagram/line\#getBeginArrowSize--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ArrowSize](../../com.aspose.diagram/arrowsize) |  |

### setCompoundType(CompoundType value) {#setCompoundType-com.aspose.diagram.CompoundType-}
```
public void setCompoundType(CompoundType value)
```


有关此属性的描述，请参阅 [getCompoundType()](../../com.aspose.diagram/line\#getCompoundType--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [CompoundType](../../com.aspose.diagram/compoundtype) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


有关此属性的描述，请参阅 [getDel()](../../com.aspose.diagram/line\#getDel--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setEndArrow(IntValue value) {#setEndArrow-com.aspose.diagram.IntValue-}
```
public void setEndArrow(IntValue value)
```


有关此属性的描述，请参阅 [getEndArrow()](../../com.aspose.diagram/line\#getEndArrow--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setEndArrowSize(ArrowSize value) {#setEndArrowSize-com.aspose.diagram.ArrowSize-}
```
public void setEndArrowSize(ArrowSize value)
```


有关此属性的描述，请参阅 [getEndArrowSize()](../../com.aspose.diagram/line\#getEndArrowSize--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ArrowSize](../../com.aspose.diagram/arrowsize) |  |

### setLineCap(BoolValue value) {#setLineCap-com.aspose.diagram.BoolValue-}
```
public void setLineCap(BoolValue value)
```


有关此属性的描述，请参阅 [getLineCap()](../../com.aspose.diagram/line\#getLineCap--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setLineColor(ColorValue value) {#setLineColor-com.aspose.diagram.ColorValue-}
```
public void setLineColor(ColorValue value)
```


有关此属性的描述，请参阅 [getLineColor()](../../com.aspose.diagram/line\#getLineColor--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setLineColorTrans(DoubleValue value) {#setLineColorTrans-com.aspose.diagram.DoubleValue-}
```
public void setLineColorTrans(DoubleValue value)
```


有关此属性的描述，请参阅 [getLineColorTrans()](../../com.aspose.diagram/line\#getLineColorTrans--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setLinePattern(IntValue value) {#setLinePattern-com.aspose.diagram.IntValue-}
```
public void setLinePattern(IntValue value)
```


有关此属性的描述，请参阅 [getLinePattern()](../../com.aspose.diagram/line\#getLinePattern--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setLineWeight(DoubleValue value) {#setLineWeight-com.aspose.diagram.DoubleValue-}
```
public void setLineWeight(DoubleValue value)
```


有关此属性的描述，请参阅 [getLineWeight()](../../com.aspose.diagram/line\#getLineWeight--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setRounding(DoubleValue value) {#setRounding-com.aspose.diagram.DoubleValue-}
```
public void setRounding(DoubleValue value)
```


有关此属性的描述，请参阅 [getRounding()](../../com.aspose.diagram/line\#getRounding--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

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

