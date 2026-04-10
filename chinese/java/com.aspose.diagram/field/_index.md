---
title: 字段
second_title: Aspose.Diagram for Java API 参考
description: 包含指定插入到形状文本中的函数和公式的元素。
type: docs
weight: 147
url: /zh/java/com.aspose.diagram/field/
---

**Inheritance:**
java.lang.Object
```
public class Field
```

包含指定插入到形状文本中的函数和公式的元素。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Field()](#Field--) | 构造函数。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [deepClone()](#deepClone--) | 创建此实例的深度副本。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCalendar()](#getCalendar--) | 确定用于自定义属性、文本字段和元素公式的日历。 |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | 指示元素是否已在本地删除的标志。 |
| [getDisplayValue()](#getDisplayValue--) | 获取此字段的格式化字符串值。 |
| [getEditMode()](#getEditMode--) | 保留供将来使用。 |
| [getFormat()](#getFormat--) | 格式元素指定字符串、数字、日期或时间、持续时间或货币等文本字段的格式。 |
| [getIX()](#getIX--) | 元素在其父元素中的零基索引。 |
| [getObjectKind()](#getObjectKind--) | 指示文本字段的类型。 |
| [getType()](#getType--) | Type 指定文本字段值的数据类型。 |
| [getUICat()](#getUICat--) | 指定在 Visio 2000 之前版本的 Microsoft Visio 中插入字段的类别。 |
| [getUICod()](#getUICod--) | 指定在 Visio 2000 之前版本的 Microsoft Visio 中插入字段的代码。 |
| [getUIFmt()](#getUIFmt--) | 指定在 Visio 2000 之前版本的 Microsoft Visio 中插入字段的格式。 |
| [getValue()](#getValue--) | 它包含文本字段的值。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | 有关此属性的描述，请参阅 [getDel()](../../com.aspose.diagram/field\#getDel--) |
| [setIX(int value)](#setIX-int-) | 有关此属性的描述，请参阅 [getIX()](../../com.aspose.diagram/field\#getIX--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Field() {#Field--}
```
public Field()
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
### getCalendar() {#getCalendar--}
```
public Calendar getCalendar()
```


确定用于自定义属性、文本字段和元素公式的日历。

**Returns:**
[Calendar](../../com.aspose.diagram/calendar)
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
### getDisplayValue() {#getDisplayValue--}
```
public String getDisplayValue()
```


获取此字段的格式化字符串值。

**Returns:**
java.lang.String
### getEditMode() {#getEditMode--}
```
public DoubleValue getEditMode()
```


保留供将来使用。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getFormat() {#getFormat--}
```
public Value getFormat()
```


Format 元素指定文本字段的格式，该字段可以是字符串、数字、日期或时间、持续时间或货币。文本字段的类型在相应的 Type 元素中指定。

**Returns:**
[Value](../../com.aspose.diagram/value)
### getIX() {#getIX--}
```
public int getIX()
```


元素在其父元素中的零基索引。

**Returns:**
int
### getObjectKind() {#getObjectKind--}
```
public ObjectKind getObjectKind()
```


指示文本字段的类型。

**Returns:**
[ObjectKind](../../com.aspose.diagram/objectkind)
### getType() {#getType--}
```
public TypeField getType()
```


Type 指定文本字段值的数据类型。

**Returns:**
[TypeField](../../com.aspose.diagram/typefield)
### getUICat() {#getUICat--}
```
public DoubleValue getUICat()
```


指定在 Visio 2000 之前版本的 Microsoft Visio 中插入字段的类别。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getUICod() {#getUICod--}
```
public DoubleValue getUICod()
```


指定在 Visio 2000 之前版本的 Microsoft Visio 中插入字段的代码。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getUIFmt() {#getUIFmt--}
```
public DoubleValue getUIFmt()
```


指定在 Visio 2000 之前版本的 Microsoft Visio 中插入字段的格式。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getValue() {#getValue--}
```
public Value getValue()
```


它包含文本字段的值。

**Returns:**
[Value](../../com.aspose.diagram/value)
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


有关此属性的描述，请参阅 [getDel()](../../com.aspose.diagram/field\#getDel--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


有关此属性的描述，请参阅 [getIX()](../../com.aspose.diagram/field\#getIX--)

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

