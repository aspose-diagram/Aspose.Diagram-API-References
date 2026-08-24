---
title: TextBlock
second_title: Aspose.Diagram for Java API 参考
description: 包含指定形状文本块中文本对齐边距和默认制表位位置的元素。
type: docs
weight: 400
url: /zh/java/com.aspose.diagram/textblock/
---

**Inheritance:**
java.lang.Object
```
public class TextBlock
```

包含指定形状文本块中文本对齐、边距和默认制表位位置的元素。
## 方法

| 方法 | 描述 |
| --- | --- |
| [deepClone()](#deepClone--) | 创建此实例的深度副本。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBottomMargin()](#getBottomMargin--) | 确定文本块底部边缘与其包含的最后一行文本之间的距离。 |
| [getClass()](#getClass--) |  |
| [getDefaultTabStop()](#getDefaultTabStop--) | 指定文本块中默认制表位的间隔。 |
| [getDel()](#getDel--) | 指示元素是否已在本地删除的标志。 |
| [getLeftMargin()](#getLeftMargin--) | 指定文本块左边缘与其包含的文本之间的距离。 |
| [getRightMargin()](#getRightMargin--) | 指定文本块右边缘与其包含的文本之间的距离。 |
| [getTextBkgnd()](#getTextBkgnd--) | 指定形状的文本背景颜色。 |
| [getTextBkgndTrans()](#getTextBkgndTrans--) | 指定形状文本块背景颜色的透明度级别，范围从 0（完全不透明）到 1（完全透明）。 |
| [getTextDirection()](#getTextDirection--) | 指定文本块中字符的方向。 |
| [getTopMargin()](#getTopMargin--) | 指定文本块顶部边缘与其包含的第一行文本之间的距离。 |
| [getVerticalAlign()](#getVerticalAlign--) | 指定文本块内文本的垂直对齐方式。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBottomMargin(DoubleValue value)](#setBottomMargin-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getBottomMargin()](../../com.aspose.diagram/textblock\#getBottomMargin--) |
| [setDefaultTabStop(DoubleValue value)](#setDefaultTabStop-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getDefaultTabStop()](../../com.aspose.diagram/textblock\#getDefaultTabStop--) |
| [setDel(int value)](#setDel-int-) | 有关此属性的描述，请参阅 [getDel()](../../com.aspose.diagram/textblock\#getDel--) |
| [setLeftMargin(DoubleValue value)](#setLeftMargin-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getLeftMargin()](../../com.aspose.diagram/textblock\#getLeftMargin--) |
| [setRightMargin(DoubleValue value)](#setRightMargin-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getRightMargin()](../../com.aspose.diagram/textblock\#getRightMargin--) |
| [setTextBkgnd(ColorValue value)](#setTextBkgnd-com.aspose.diagram.ColorValue-) | 有关此属性的描述，请参阅 [getTextBkgnd()](../../com.aspose.diagram/textblock\#getTextBkgnd--) |
| [setTextBkgndTrans(DoubleValue value)](#setTextBkgndTrans-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getTextBkgndTrans()](../../com.aspose.diagram/textblock\#getTextBkgndTrans--) |
| [setTextDirection(TextDirection value)](#setTextDirection-com.aspose.diagram.TextDirection-) | 有关此属性的描述，请参见 [getTextDirection()](../../com.aspose.diagram/textblock\#getTextDirection--) |
| [setTopMargin(DoubleValue value)](#setTopMargin-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参见 [getTopMargin()](../../com.aspose.diagram/textblock\#getTopMargin--) |
| [setVerticalAlign(VerticalAlign value)](#setVerticalAlign-com.aspose.diagram.VerticalAlign-) | 有关此属性的描述，请参见 [getVerticalAlign()](../../com.aspose.diagram/textblock\#getVerticalAlign--) |
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
### getBottomMargin() {#getBottomMargin--}
```
public DoubleValue getBottomMargin()
```


确定文本块底部边界与其包含的最后一行文本之间的距离。默认值为 4 pt。此值不受绘图比例的影响。如果绘图被缩放，底部边距保持不变。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultTabStop() {#getDefaultTabStop--}
```
public DoubleValue getDefaultTabStop()
```


指定文本块中默认制表位的间隔。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDel() {#getDel--}
```
public int getDel()
```


一个标志，指示元素是否已在本地删除。值为 1 表示该元素已在本地删除。

**Returns:**
int
### getLeftMargin() {#getLeftMargin--}
```
public DoubleValue getLeftMargin()
```


指定文本块左侧边界与其包含的文本之间的距离。此值不受绘图比例的影响。如果绘图被缩放，左侧边距保持不变。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getRightMargin() {#getRightMargin--}
```
public DoubleValue getRightMargin()
```


指定文本块右侧边界与其包含的文本之间的距离。此值不受绘图比例的影响。如果绘图被缩放，右侧边距保持不变。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTextBkgnd() {#getTextBkgnd--}
```
public ColorValue getTextBkgnd()
```


指定形状的文本背景颜色。

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getTextBkgndTrans() {#getTextBkgndTrans--}
```
public DoubleValue getTextBkgndTrans()
```


指定形状文本块背景颜色的透明度级别，范围从 0（完全不透明）到 1（完全透明）。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTextDirection() {#getTextDirection--}
```
public TextDirection getTextDirection()
```


指定文本块中字符的方向。

**Returns:**
[TextDirection](../../com.aspose.diagram/textdirection)
### getTopMargin() {#getTopMargin--}
```
public DoubleValue getTopMargin()
```


指定文本块顶部边缘与其包含的第一行文本之间的距离。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getVerticalAlign() {#getVerticalAlign--}
```
public VerticalAlign getVerticalAlign()
```


指定文本块内文本的垂直对齐方式。

**Returns:**
[VerticalAlign](../../com.aspose.diagram/verticalalign)
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




### setBottomMargin(DoubleValue value) {#setBottomMargin-com.aspose.diagram.DoubleValue-}
```
public void setBottomMargin(DoubleValue value)
```


有关此属性的描述，请参阅 [getBottomMargin()](../../com.aspose.diagram/textblock\#getBottomMargin--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setDefaultTabStop(DoubleValue value) {#setDefaultTabStop-com.aspose.diagram.DoubleValue-}
```
public void setDefaultTabStop(DoubleValue value)
```


有关此属性的描述，请参阅 [getDefaultTabStop()](../../com.aspose.diagram/textblock\#getDefaultTabStop--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


有关此属性的描述，请参阅 [getDel()](../../com.aspose.diagram/textblock\#getDel--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setLeftMargin(DoubleValue value) {#setLeftMargin-com.aspose.diagram.DoubleValue-}
```
public void setLeftMargin(DoubleValue value)
```


有关此属性的描述，请参阅 [getLeftMargin()](../../com.aspose.diagram/textblock\#getLeftMargin--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setRightMargin(DoubleValue value) {#setRightMargin-com.aspose.diagram.DoubleValue-}
```
public void setRightMargin(DoubleValue value)
```


有关此属性的描述，请参阅 [getRightMargin()](../../com.aspose.diagram/textblock\#getRightMargin--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTextBkgnd(ColorValue value) {#setTextBkgnd-com.aspose.diagram.ColorValue-}
```
public void setTextBkgnd(ColorValue value)
```


有关此属性的描述，请参阅 [getTextBkgnd()](../../com.aspose.diagram/textblock\#getTextBkgnd--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setTextBkgndTrans(DoubleValue value) {#setTextBkgndTrans-com.aspose.diagram.DoubleValue-}
```
public void setTextBkgndTrans(DoubleValue value)
```


有关此属性的描述，请参阅 [getTextBkgndTrans()](../../com.aspose.diagram/textblock\#getTextBkgndTrans--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTextDirection(TextDirection value) {#setTextDirection-com.aspose.diagram.TextDirection-}
```
public void setTextDirection(TextDirection value)
```


有关此属性的描述，请参见 [getTextDirection()](../../com.aspose.diagram/textblock\#getTextDirection--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TextDirection](../../com.aspose.diagram/textdirection) |  |

### setTopMargin(DoubleValue value) {#setTopMargin-com.aspose.diagram.DoubleValue-}
```
public void setTopMargin(DoubleValue value)
```


有关此属性的描述，请参见 [getTopMargin()](../../com.aspose.diagram/textblock\#getTopMargin--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setVerticalAlign(VerticalAlign value) {#setVerticalAlign-com.aspose.diagram.VerticalAlign-}
```
public void setVerticalAlign(VerticalAlign value)
```


有关此属性的描述，请参见 [getVerticalAlign()](../../com.aspose.diagram/textblock\#getVerticalAlign--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [VerticalAlign](../../com.aspose.diagram/verticalalign) |  |

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

