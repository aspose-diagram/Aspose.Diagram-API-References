---
title: TextXForm
second_title: Aspose.Diagram for Java API 参考
description: 包含指定形状文本块位置信息的元素。
type: docs
weight: 405
url: /zh/java/com.aspose.diagram/textxform/
---

**Inheritance:**
java.lang.Object
```
public class TextXForm
```

包含指定形状文本块位置信息的元素。
## 方法

| 方法 | 描述 |
| --- | --- |
| [deepClone()](#deepClone--) | 创建此实例的深度副本。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | 指示元素是否已在本地删除的标志。 |
| [getTxtAngle()](#getTxtAngle--) | 指定文本块相对于形状 x 轴的当前旋转角度。 |
| [getTxtHeight()](#getTxtHeight--) | 指定文本块的高度。 |
| [getTxtLocPinX()](#getTxtLocPinX--) | 指定文本块相对于文本块原点的旋转中心的 x 坐标。 |
| [getTxtLocPinY()](#getTxtLocPinY--) | 指定文本块相对于文本块原点的旋转中心的 y 坐标。 |
| [getTxtPinX()](#getTxtPinX--) | 指定文本块相对于形状原点的旋转中心的 x 坐标。 |
| [getTxtPinY()](#getTxtPinY--) | 指定文本块相对于形状原点的旋转中心的 y 坐标。 |
| [getTxtWidth()](#getTxtWidth--) | 指定文本块的宽度。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | 有关此属性的描述，请参阅 [getDel()](../../com.aspose.diagram/textxform\#getDel--) |
| [setTxtAngle(DoubleValue value)](#setTxtAngle-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getTxtAngle()](../../com.aspose.diagram/textxform\#getTxtAngle--) |
| [setTxtHeight(DoubleValue value)](#setTxtHeight-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getTxtHeight()](../../com.aspose.diagram/textxform\#getTxtHeight--) |
| [setTxtLocPinX(DoubleValue value)](#setTxtLocPinX-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getTxtLocPinX()](../../com.aspose.diagram/textxform\#getTxtLocPinX--) |
| [setTxtLocPinY(DoubleValue value)](#setTxtLocPinY-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getTxtLocPinY()](../../com.aspose.diagram/textxform\#getTxtLocPinY--) |
| [setTxtPinX(DoubleValue value)](#setTxtPinX-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getTxtPinX()](../../com.aspose.diagram/textxform\#getTxtPinX--) |
| [setTxtPinY(DoubleValue value)](#setTxtPinY-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getTxtPinY()](../../com.aspose.diagram/textxform\#getTxtPinY--) |
| [setTxtWidth(DoubleValue value)](#setTxtWidth-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getTxtWidth()](../../com.aspose.diagram/textxform\#getTxtWidth--) |
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
### getTxtAngle() {#getTxtAngle--}
```
public DoubleValue getTxtAngle()
```


指定文本块相对于形状 x 轴的当前旋转角度。默认值为 0 度。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTxtHeight() {#getTxtHeight--}
```
public DoubleValue getTxtHeight()
```


指定文本块的高度。默认公式（计算得到形状的高度）为 F="Height\*1"。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTxtLocPinX() {#getTxtLocPinX--}
```
public DoubleValue getTxtLocPinX()
```


指定文本块相对于文本块原点的旋转中心的 x 坐标。默认公式（计算得到文本块的水平中心）为 F="TxtWidth\*0.5"。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTxtLocPinY() {#getTxtLocPinY--}
```
public DoubleValue getTxtLocPinY()
```


指定文本块相对于文本块原点的旋转中心的 y 坐标。默认公式（计算得到文本块的垂直中心）为 F="TxtHeight\*0.5"。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTxtPinX() {#getTxtPinX--}
```
public DoubleValue getTxtPinX()
```


指定文本块相对于形状原点的旋转中心的 x 坐标。默认公式（计算得到形状的水平中心）为 F="Width\*0.5"。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTxtPinY() {#getTxtPinY--}
```
public DoubleValue getTxtPinY()
```


指定文本块相对于形状原点的旋转中心的 y 坐标。默认公式（计算得到形状的垂直中心）为 F="Height\*0.5"。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTxtWidth() {#getTxtWidth--}
```
public DoubleValue getTxtWidth()
```


指定文本块的宽度。默认公式（计算得到形状的宽度）为 F="Width\*1"。

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




### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


有关此属性的描述，请参阅 [getDel()](../../com.aspose.diagram/textxform\#getDel--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setTxtAngle(DoubleValue value) {#setTxtAngle-com.aspose.diagram.DoubleValue-}
```
public void setTxtAngle(DoubleValue value)
```


有关此属性的描述，请参阅 [getTxtAngle()](../../com.aspose.diagram/textxform\#getTxtAngle--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTxtHeight(DoubleValue value) {#setTxtHeight-com.aspose.diagram.DoubleValue-}
```
public void setTxtHeight(DoubleValue value)
```


有关此属性的描述，请参阅 [getTxtHeight()](../../com.aspose.diagram/textxform\#getTxtHeight--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTxtLocPinX(DoubleValue value) {#setTxtLocPinX-com.aspose.diagram.DoubleValue-}
```
public void setTxtLocPinX(DoubleValue value)
```


有关此属性的描述，请参阅 [getTxtLocPinX()](../../com.aspose.diagram/textxform\#getTxtLocPinX--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTxtLocPinY(DoubleValue value) {#setTxtLocPinY-com.aspose.diagram.DoubleValue-}
```
public void setTxtLocPinY(DoubleValue value)
```


有关此属性的描述，请参阅 [getTxtLocPinY()](../../com.aspose.diagram/textxform\#getTxtLocPinY--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTxtPinX(DoubleValue value) {#setTxtPinX-com.aspose.diagram.DoubleValue-}
```
public void setTxtPinX(DoubleValue value)
```


有关此属性的描述，请参阅 [getTxtPinX()](../../com.aspose.diagram/textxform\#getTxtPinX--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTxtPinY(DoubleValue value) {#setTxtPinY-com.aspose.diagram.DoubleValue-}
```
public void setTxtPinY(DoubleValue value)
```


有关此属性的描述，请参阅 [getTxtPinY()](../../com.aspose.diagram/textxform\#getTxtPinY--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTxtWidth(DoubleValue value) {#setTxtWidth-com.aspose.diagram.DoubleValue-}
```
public void setTxtWidth(DoubleValue value)
```


有关此属性的描述，请参阅 [getTxtWidth()](../../com.aspose.diagram/textxform\#getTxtWidth--)

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

