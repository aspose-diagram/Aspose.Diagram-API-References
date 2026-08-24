---
title: Para
second_title: Aspose.Diagram for Java API 参考
description: 包含形状文本的段落格式元素，例如缩进、行间距、项目符号以及段落的水平对齐方式。
type: docs
weight: 274
url: /zh/java/com.aspose.diagram/para/
---

**Inheritance:**
java.lang.Object
```
public class Para
```

包含形状文本的段落格式元素，例如缩进、行距、项目符号以及段落的水平对齐方式。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Para()](#Para--) | 构造函数。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [deepClone()](#deepClone--) | 创建此实例的深度副本。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBullet()](#getBullet--) | 确定项目符号样式。 |
| [getBulletFont()](#getBulletFont--) | 表示在指定自定义项目符号字符串且 Bullet 元素的值非零时，用于格式化文本的字体编号。 |
| [getBulletFontSize()](#getBulletFontSize--) | 指定项目符号的大小。 |
| [getBulletStr()](#getBulletStr--) | "用于创建自定义项目符号样式。 |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | 指示元素是否已在本地删除的标志。 |
| [getFlags()](#getFlags--) | 指示文本方向是从左到右还是从右到左。 |
| [getHorzAlign()](#getHorzAlign--) | 指定形状文本块中文本的水平对齐方式。 |
| [getIX()](#getIX--) | 元素在其父元素中的零基索引。 |
| [getIndFirst()](#getIndFirst--) | 指定形状文本块中每个段落的首行相对于段落左缩进的缩进距离。 |
| [getIndLeft()](#getIndLeft--) | 指定段落中所有文本行相对于文本块左边距的缩进距离。 |
| [getIndRight()](#getIndRight--) | 指定段落中所有文本行相对于文本块右边距的缩进距离。 |
| [getLocalizeBulletFont()](#getLocalizeBulletFont--) | 指定是否应对项目符号字体进行本地化（翻译成其他语言）。 |
| [getSpAfter()](#getSpAfter--) | 指定在形状文本块中每个段落之后插入的空间量。 |
| [getSpBefore()](#getSpBefore--) | 指定在形状文本块中每个段落之前插入的空间量。 |
| [getSpLine()](#getSpLine--) | 指定一行文本与下一行之间的距离，100% 表示文本行的高度。 |
| [getTextPosAfterBullet()](#getTextPosAfterBullet--) | 表示段落第一行与项目符号之间的距离。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBullet(Bullet value)](#setBullet-com.aspose.diagram.Bullet-) | 有关此属性的描述，请参阅 [getBullet()](../../com.aspose.diagram/para\#getBullet--) |
| [setBulletFont(IntValue value)](#setBulletFont-com.aspose.diagram.IntValue-) | 有关此属性的描述，请参阅 [getBulletFont()](../../com.aspose.diagram/para\#getBulletFont--) |
| [setBulletFontSize(DoubleValue value)](#setBulletFontSize-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getBulletFontSize()](../../com.aspose.diagram/para\#getBulletFontSize--) |
| [setBulletStr(Str2Value value)](#setBulletStr-com.aspose.diagram.Str2Value-) | 有关此属性的描述，请参阅 [getBulletStr()](../../com.aspose.diagram/para\#getBulletStr--) |
| [setDel(int value)](#setDel-int-) | 有关此属性的描述，请参阅 [getDel()](../../com.aspose.diagram/para\#getDel--) |
| [setFlags(BoolValue value)](#setFlags-com.aspose.diagram.BoolValue-) | 有关此属性的描述，请参阅 [getFlags()](../../com.aspose.diagram/para\#getFlags--) |
| [setHorzAlign(HorzAlign value)](#setHorzAlign-com.aspose.diagram.HorzAlign-) | 有关此属性的描述，请参阅 [getHorzAlign()](../../com.aspose.diagram/para\#getHorzAlign--) |
| [setIX(int value)](#setIX-int-) | 有关此属性的描述，请参阅 [getIX()](../../com.aspose.diagram/para\#getIX--) |
| [setIndFirst(DoubleValue value)](#setIndFirst-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getIndFirst()](../../com.aspose.diagram/para\#getIndFirst--) |
| [setIndLeft(DoubleValue value)](#setIndLeft-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getIndLeft()](../../com.aspose.diagram/para\#getIndLeft--) |
| [setIndRight(DoubleValue value)](#setIndRight-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getIndRight()](../../com.aspose.diagram/para\#getIndRight--) |
| [setLocalizeBulletFont(LocalizeFont value)](#setLocalizeBulletFont-com.aspose.diagram.LocalizeFont-) | 有关此属性的描述，请参阅 [getLocalizeBulletFont()](../../com.aspose.diagram/para\#getLocalizeBulletFont--) |
| [setSpAfter(DoubleValue value)](#setSpAfter-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getSpAfter()](../../com.aspose.diagram/para\#getSpAfter--) |
| [setSpBefore(DoubleValue value)](#setSpBefore-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getSpBefore()](../../com.aspose.diagram/para\#getSpBefore--) |
| [setSpLine(DoubleValue value)](#setSpLine-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getSpLine()](../../com.aspose.diagram/para\#getSpLine--) |
| [setTextPosAfterBullet(DoubleValue value)](#setTextPosAfterBullet-com.aspose.diagram.DoubleValue-) | 有关此属性的描述，请参阅 [getTextPosAfterBullet()](../../com.aspose.diagram/para\#getTextPosAfterBullet--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Para() {#Para--}
```
public Para()
```


构造函数。

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
### getBullet() {#getBullet--}
```
public Bullet getBullet()
```


确定项目符号样式。

**Returns:**
[Bullet](../../com.aspose.diagram/bullet)
### getBulletFont() {#getBulletFont--}
```
public IntValue getBulletFont()
```


表示在指定自定义项目符号字符串且 Bullet 元素的值非零时，用于格式化文本的字体编号。

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getBulletFontSize() {#getBulletFontSize--}
```
public DoubleValue getBulletFontSize()
```


指定项目符号的大小。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBulletStr() {#getBulletStr--}
```
public Str2Value getBulletStr()
```


"用于创建自定义项目符号样式。将样式作为字符串输入（在引号内）。例如，您可以输入字符串，""ooo."""

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
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
### getFlags() {#getFlags--}
```
public BoolValue getFlags()
```


指示文本方向是从左到右还是从右到左。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getHorzAlign() {#getHorzAlign--}
```
public HorzAlign getHorzAlign()
```


指定形状文本块中文本的水平对齐方式。

**Returns:**
[HorzAlign](../../com.aspose.diagram/horzalign)
### getIX() {#getIX--}
```
public int getIX()
```


元素在其父元素中的零基索引。

**Returns:**
int
### getIndFirst() {#getIndFirst--}
```
public DoubleValue getIndFirst()
```


指定形状文本块中每个段落的第一行相对于段落左缩进的缩进距离。此值不受绘图比例的影响。如果绘图被缩放，第一行缩进保持不变。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getIndLeft() {#getIndLeft--}
```
public DoubleValue getIndLeft()
```


指定段落中所有文本行相对于文本块左边距的缩进距离。此值不受绘图比例的影响。如果绘图被缩放，左侧缩进保持不变。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getIndRight() {#getIndRight--}
```
public DoubleValue getIndRight()
```


指定段落中所有文本行相对于文本块右边距的缩进距离。此值独立于绘图的比例。如果绘图被缩放，右侧缩进保持不变。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLocalizeBulletFont() {#getLocalizeBulletFont--}
```
public LocalizeFont getLocalizeBulletFont()
```


指定是否应对项目符号字体进行本地化（翻译成其他语言）。

**Returns:**
[LocalizeFont](../../com.aspose.diagram/localizefont)
### getSpAfter() {#getSpAfter--}
```
public DoubleValue getSpAfter()
```


指定在形状文本块中每个段落之后插入的空间量。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getSpBefore() {#getSpBefore--}
```
public DoubleValue getSpBefore()
```


指定在形状文本块中每个段落之前插入的空间量。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getSpLine() {#getSpLine--}
```
public DoubleValue getSpLine()
```


指定一行文本与下一行之间的距离，100% 表示文本行的高度。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTextPosAfterBullet() {#getTextPosAfterBullet--}
```
public DoubleValue getTextPosAfterBullet()
```


表示段落第一行与项目符号之间的距离。

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




### setBullet(Bullet value) {#setBullet-com.aspose.diagram.Bullet-}
```
public void setBullet(Bullet value)
```


有关此属性的描述，请参阅 [getBullet()](../../com.aspose.diagram/para\#getBullet--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Bullet](../../com.aspose.diagram/bullet) |  |

### setBulletFont(IntValue value) {#setBulletFont-com.aspose.diagram.IntValue-}
```
public void setBulletFont(IntValue value)
```


有关此属性的描述，请参阅 [getBulletFont()](../../com.aspose.diagram/para\#getBulletFont--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setBulletFontSize(DoubleValue value) {#setBulletFontSize-com.aspose.diagram.DoubleValue-}
```
public void setBulletFontSize(DoubleValue value)
```


有关此属性的描述，请参阅 [getBulletFontSize()](../../com.aspose.diagram/para\#getBulletFontSize--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setBulletStr(Str2Value value) {#setBulletStr-com.aspose.diagram.Str2Value-}
```
public void setBulletStr(Str2Value value)
```


有关此属性的描述，请参阅 [getBulletStr()](../../com.aspose.diagram/para\#getBulletStr--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Str2Value](../../com.aspose.diagram/str2value) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


有关此属性的描述，请参阅 [getDel()](../../com.aspose.diagram/para\#getDel--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setFlags(BoolValue value) {#setFlags-com.aspose.diagram.BoolValue-}
```
public void setFlags(BoolValue value)
```


有关此属性的描述，请参阅 [getFlags()](../../com.aspose.diagram/para\#getFlags--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setHorzAlign(HorzAlign value) {#setHorzAlign-com.aspose.diagram.HorzAlign-}
```
public void setHorzAlign(HorzAlign value)
```


有关此属性的描述，请参阅 [getHorzAlign()](../../com.aspose.diagram/para\#getHorzAlign--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [HorzAlign](../../com.aspose.diagram/horzalign) |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


有关此属性的描述，请参阅 [getIX()](../../com.aspose.diagram/para\#getIX--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setIndFirst(DoubleValue value) {#setIndFirst-com.aspose.diagram.DoubleValue-}
```
public void setIndFirst(DoubleValue value)
```


有关此属性的描述，请参阅 [getIndFirst()](../../com.aspose.diagram/para\#getIndFirst--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setIndLeft(DoubleValue value) {#setIndLeft-com.aspose.diagram.DoubleValue-}
```
public void setIndLeft(DoubleValue value)
```


有关此属性的描述，请参阅 [getIndLeft()](../../com.aspose.diagram/para\#getIndLeft--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setIndRight(DoubleValue value) {#setIndRight-com.aspose.diagram.DoubleValue-}
```
public void setIndRight(DoubleValue value)
```


有关此属性的描述，请参阅 [getIndRight()](../../com.aspose.diagram/para\#getIndRight--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setLocalizeBulletFont(LocalizeFont value) {#setLocalizeBulletFont-com.aspose.diagram.LocalizeFont-}
```
public void setLocalizeBulletFont(LocalizeFont value)
```


有关此属性的描述，请参阅 [getLocalizeBulletFont()](../../com.aspose.diagram/para\#getLocalizeBulletFont--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [LocalizeFont](../../com.aspose.diagram/localizefont) |  |

### setSpAfter(DoubleValue value) {#setSpAfter-com.aspose.diagram.DoubleValue-}
```
public void setSpAfter(DoubleValue value)
```


有关此属性的描述，请参阅 [getSpAfter()](../../com.aspose.diagram/para\#getSpAfter--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setSpBefore(DoubleValue value) {#setSpBefore-com.aspose.diagram.DoubleValue-}
```
public void setSpBefore(DoubleValue value)
```


有关此属性的描述，请参阅 [getSpBefore()](../../com.aspose.diagram/para\#getSpBefore--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setSpLine(DoubleValue value) {#setSpLine-com.aspose.diagram.DoubleValue-}
```
public void setSpLine(DoubleValue value)
```


有关此属性的描述，请参阅 [getSpLine()](../../com.aspose.diagram/para\#getSpLine--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTextPosAfterBullet(DoubleValue value) {#setTextPosAfterBullet-com.aspose.diagram.DoubleValue-}
```
public void setTextPosAfterBullet(DoubleValue value)
```


有关此属性的描述，请参阅 [getTextPosAfterBullet()](../../com.aspose.diagram/para\#getTextPosAfterBullet--)

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

