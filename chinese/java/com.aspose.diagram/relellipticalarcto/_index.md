---
title: RelEllipticalArcTo
second_title: Aspose.Diagram for Java API 参考
description: 包含指定椭圆弧信息的元素。坐标以相对坐标指定。
type: docs
weight: 318
url: /zh/java/com.aspose.diagram/relellipticalarcto/
---

**Inheritance:**
java.lang.Object，[com.aspose.diagram.Coordinate](../../com.aspose.diagram/coordinate)
```
public class RelEllipticalArcTo extends Coordinate
```

包含指定椭圆弧信息的元素。坐标以相对坐标指定。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [RelEllipticalArcTo()](#RelEllipticalArcTo--) | 创建 [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto) 类的实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [deepClone()](#deepClone--) | 创建此实例的深度副本。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getA()](#getA--) | 弧的控制点的 x 坐标。 |
| [getB()](#getB--) | 弧的控制点的 y 坐标。 |
| [getC()](#getC--) | 弧的主轴相对于其父对象 x 轴的角度。 |
| [getClass()](#getClass--) |  |
| [getD()](#getD--) | 弧的主轴与次轴的比例。 |
| [getDel()](#getDel--) | 指示元素是否已在本地删除的标志。 |
| [getIX()](#getIX--) | 元素在其父元素中的零基索引。 |
| [getX()](#getX--) | 椭圆弧结束顶点的 x 坐标。 |
| [getY()](#getY--) | 椭圆弧结束顶点的 y 坐标。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setA(DoubleValue value)](#setA-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getA()](../../com.aspose.diagram/relellipticalarcto\#getA--) |
| [setB(DoubleValue value)](#setB-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getB()](../../com.aspose.diagram/relellipticalarcto\#getB--) |
| [setC(DoubleValue value)](#setC-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getC()](../../com.aspose.diagram/relellipticalarcto\#getC--) |
| [setD(DoubleValue value)](#setD-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getD()](../../com.aspose.diagram/relellipticalarcto\#getD--) |
| [setDel(int value)](#setDel-int-) | 有关此属性的描述，请参阅 [getDel()](../../com.aspose.diagram/relellipticalarcto\#getDel--) |
| [setIX(int value)](#setIX-int-) | 有关此属性的描述，请参阅 [getIX()](../../com.aspose.diagram/relellipticalarcto\#getIX--) |
| [setX(DoubleValue value)](#setX-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getX()](../../com.aspose.diagram/relellipticalarcto\#getX--) |
| [setY(DoubleValue value)](#setY-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getY()](../../com.aspose.diagram/relellipticalarcto\#getY--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RelEllipticalArcTo() {#RelEllipticalArcTo--}
```
public RelEllipticalArcTo()
```


创建 [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto) 类的实例。

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
### getA() {#getA--}
```
public DoubleValue getA()
```


弧线控制点的 x 坐标。控制点最好位于弧线起始和结束顶点之间的大约中点处。否则，弧线可能会为了通过控制点而增长到极大的尺寸，导致不可预知的结果。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getB() {#getB--}
```
public DoubleValue getB()
```


弧的控制点的 y 坐标。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getC() {#getC--}
```
public DoubleValue getC()
```


弧的主轴相对于其父对象 x 轴的角度。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getD() {#getD--}
```
public DoubleValue getD()
```


弧线的长轴与短轴的比例。尽管这些词语通常的含义是长轴应大于短轴，但长轴不一定要大于短轴，因此该比例不一定大于 1。将此元素设置为小于等于 0 或大于 1000 的值可能会导致不可预知的结果。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDel() {#getDel--}
```
public int getDel()
```


一个标志，指示元素是否已在本地删除。值为 1 表示该元素已在本地删除。

**Returns:**
int
### getIX() {#getIX--}
```
public int getIX()
```


元素在其父元素中的零基索引。

**Returns:**
int
### getX() {#getX--}
```
public DoubleValue getX()
```


椭圆弧结束顶点的 x 坐标。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getY() {#getY--}
```
public DoubleValue getY()
```


椭圆弧结束顶点的 y 坐标。

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




### setA(DoubleValue value) {#setA-com.aspose.diagram.DoubleValue-}
```
public void setA(DoubleValue value)
```


有关此属性的描述，请参阅 [getA()](../../com.aspose.diagram/relellipticalarcto\#getA--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setB(DoubleValue value) {#setB-com.aspose.diagram.DoubleValue-}
```
public void setB(DoubleValue value)
```


有关此属性的描述，请参阅 [getB()](../../com.aspose.diagram/relellipticalarcto\#getB--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setC(DoubleValue value) {#setC-com.aspose.diagram.DoubleValue-}
```
public void setC(DoubleValue value)
```


有关此属性的描述，请参阅 [getC()](../../com.aspose.diagram/relellipticalarcto\#getC--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setD(DoubleValue value) {#setD-com.aspose.diagram.DoubleValue-}
```
public void setD(DoubleValue value)
```


有关此属性的描述，请参阅 [getD()](../../com.aspose.diagram/relellipticalarcto\#getD--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


有关此属性的描述，请参阅 [getDel()](../../com.aspose.diagram/relellipticalarcto\#getDel--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


有关此属性的描述，请参阅 [getIX()](../../com.aspose.diagram/relellipticalarcto\#getIX--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setX(DoubleValue value) {#setX-com.aspose.diagram.DoubleValue-}
```
public void setX(DoubleValue value)
```


有关此属性的描述，请参阅 [getX()](../../com.aspose.diagram/relellipticalarcto\#getX--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setY(DoubleValue value) {#setY-com.aspose.diagram.DoubleValue-}
```
public void setY(DoubleValue value)
```


有关此属性的描述，请参阅 [getY()](../../com.aspose.diagram/relellipticalarcto\#getY--)

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

