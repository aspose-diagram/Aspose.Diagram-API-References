---
title: NURBSTo
second_title: Aspose.Diagram for Java API 参考
description: 包含第二个结点位置的 x 和 y 坐标、最后权重的位置、第一结点的位置、第一权重的位置，以及非均匀有理 B 样条 NURBS 的公式。
type: docs
weight: 250
url: /zh/java/com.aspose.diagram/nurbsto/
---

**Inheritance:**
java.lang.Object，[com.aspose.diagram.Coordinate](../../com.aspose.diagram/coordinate)
```
public class NURBSTo extends Coordinate
```

包含 x 和 y 坐标、第二个结点的位置、最后权重的位置、第一结点的位置、第一权重的位置，以及非均匀有理 B 样条 (NURBS) 的公式。这些信息分别在 X、Y、A、B、C、D 和 E 元素中指定。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [NURBSTo()](#NURBSTo--) | 创建 [NURBSTo](../../com.aspose.diagram/nurbsto) 类的实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [deepClone()](#deepClone--) | 创建此实例的深度副本。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getA()](#getA--) | 非均匀有理 B 样条 (NURBS) 的倒数第二个结点。 |
| [getB()](#getB--) | 非均匀有理 B 样条 (NURBS) 的最后权重。 |
| [getC()](#getC--) | 非均匀有理 B 样条 (NURBS) 的第一个结点。 |
| [getClass()](#getClass--) |  |
| [getD()](#getD--) | 非均匀有理 B 样条 (NURBS) 的第一个权重 |
| [getDel()](#getDel--) | 指示元素是否已在本地删除的标志。 |
| [getE()](#getE--) | 包含非均匀有理 B 样条 (NURBS) 公式。 |
| [getIX()](#getIX--) | 元素在其父元素中的零基索引。 |
| [getX()](#getX--) | 非均匀有理 B 样条 (NURBS) 最后控制点的 x 坐标。 |
| [getY()](#getY--) | 非均匀有理 B 样条 (NURBS) 最后控制点的 y 坐标。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setA(DoubleValue value)](#setA-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getA()](../../com.aspose.diagram/nurbsto\#getA--) |
| [setB(DoubleValue value)](#setB-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getB()](../../com.aspose.diagram/nurbsto\#getB--) |
| [setC(DoubleValue value)](#setC-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getC()](../../com.aspose.diagram/nurbsto\#getC--) |
| [setD(DoubleValue value)](#setD-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getD()](../../com.aspose.diagram/nurbsto\#getD--) |
| [setDel(int value)](#setDel-int-) | 有关此属性的描述，请参阅 [getDel()](../../com.aspose.diagram/nurbsto\#getDel--) |
| [setE(StrValue value)](#setE-com.aspose.diagram.StrValue-) | 有关此属性的描述，请参阅 [getE()](../../com.aspose.diagram/nurbsto\#getE--) |
| [setIX(int value)](#setIX-int-) | 有关此属性的描述，请参阅 [getIX()](../../com.aspose.diagram/nurbsto\#getIX--) |
| [setX(DoubleValue value)](#setX-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getX()](../../com.aspose.diagram/nurbsto\#getX--) |
| [setY(DoubleValue value)](#setY-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getY()](../../com.aspose.diagram/nurbsto\#getY--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NURBSTo() {#NURBSTo--}
```
public NURBSTo()
```


创建 [NURBSTo](../../com.aspose.diagram/nurbsto) 类的实例。

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


非均匀有理 B 样条 (NURBS) 的倒数第二个结点。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getB() {#getB--}
```
public DoubleValue getB()
```


非均匀有理 B 样条 (NURBS) 的最后权重。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getC() {#getC--}
```
public DoubleValue getC()
```


非均匀有理 B 样条 (NURBS) 的第一个结点。

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


非均匀有理 B 样条 (NURBS) 的第一个权重

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDel() {#getDel--}
```
public int getDel()
```


一个标志，指示元素是否已在本地删除。值为 1 表示该元素已在本地删除。

**Returns:**
int
### getE() {#getE--}
```
public StrValue getE()
```


包含非均匀有理 B 样条 (NURBS) 公式。

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
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


非均匀有理 B 样条 (NURBS) 最后控制点的 x 坐标。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getY() {#getY--}
```
public DoubleValue getY()
```


非均匀有理 B 样条 (NURBS) 最后控制点的 y 坐标。

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


有关此属性的描述，请参阅 [getA()](../../com.aspose.diagram/nurbsto\#getA--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setB(DoubleValue value) {#setB-com.aspose.diagram.DoubleValue-}
```
public void setB(DoubleValue value)
```


有关此属性的描述，请参阅 [getB()](../../com.aspose.diagram/nurbsto\#getB--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setC(DoubleValue value) {#setC-com.aspose.diagram.DoubleValue-}
```
public void setC(DoubleValue value)
```


有关此属性的描述，请参阅 [getC()](../../com.aspose.diagram/nurbsto\#getC--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setD(DoubleValue value) {#setD-com.aspose.diagram.DoubleValue-}
```
public void setD(DoubleValue value)
```


有关此属性的描述，请参阅 [getD()](../../com.aspose.diagram/nurbsto\#getD--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


有关此属性的描述，请参阅 [getDel()](../../com.aspose.diagram/nurbsto\#getDel--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setE(StrValue value) {#setE-com.aspose.diagram.StrValue-}
```
public void setE(StrValue value)
```


有关此属性的描述，请参阅 [getE()](../../com.aspose.diagram/nurbsto\#getE--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [StrValue](../../com.aspose.diagram/strvalue) |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


有关此属性的描述，请参阅 [getIX()](../../com.aspose.diagram/nurbsto\#getIX--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setX(DoubleValue value) {#setX-com.aspose.diagram.DoubleValue-}
```
public void setX(DoubleValue value)
```


有关此属性的描述，请参阅 [getX()](../../com.aspose.diagram/nurbsto\#getX--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setY(DoubleValue value) {#setY-com.aspose.diagram.DoubleValue-}
```
public void setY(DoubleValue value)
```


有关此属性的描述，请参阅 [getY()](../../com.aspose.diagram/nurbsto\#getY--)

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

