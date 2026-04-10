---
title: 属性
second_title: Aspose.Diagram for Java API 参考
description: 包含用于定义自定义属性的元素以及用于将数据关联到形状的元素。
type: docs
weight: 309
url: /zh/java/com.aspose.diagram/prop/
---

**Inheritance:**
java.lang.Object
```
public class Prop
```

包含用于定义自定义属性的元素以及用于将数据关联到形状的元素。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Prop()](#Prop--) | 构造函数。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [deepClone()](#deepClone--) | 创建此实例的深度副本。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCalendar()](#getCalendar--) | 确定用于自定义属性、文本字段和元素公式的日历。 |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | 指示元素是否已在本地删除的标志。 |
| [getFormat()](#getFormat--) | Format 元素指定自定义属性的格式，该属性可以是字符串、固定列表、数字、可变列表、日期或时间、持续时间或货币。 |
| [getID()](#getID--) | 元素在其父元素中的唯一 ID。 |
| [getIX()](#getIX--) | 元素在其父元素中的零基索引。 |
| [getInvisible()](#getInvisible--) | Invisible 元素指定自定义属性在 Microsoft Visio 的自定义属性对话框中是否可见。 |
| [getLabel()](#getLabel--) | 指定在自定义属性对话框中显示给用户的标签。 |
| [getLangID()](#getLangID--) | 指示输入单元格公式、文本、自定义属性或注释的语言的区域标识符 (LCID)。 |
| [getName()](#getName--) | 元素的名称。 |
| [getNameU()](#getNameU--) | 元素的通用名称。 |
| [getPrompt()](#getPrompt--) | Prompt 元素指定在自定义属性对话框中属性被选中时显示给用户的描述性或指令性文本。 |
| [getSortKey()](#getSortKey--) | 它指定一个键，用于决定自定义属性在应用程序用户界面中列出的顺序。 |
| [getType()](#getType--) | Type 指定自定义属性值的数据类型。 |
| [getValue()](#getValue--) | 包含特定解决方案的、在显式命名空间前缀的、符合规范的 XML 数据，并随文档一起存储。 |
| [getVerify()](#getVerify--) | 指定在创建实例或复制/复制形状时，是否向用户询问输入形状的自定义属性信息。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | 有关此属性的描述，请参阅 [getDel()](../../com.aspose.diagram/prop\#getDel--) |
| [setID(int value)](#setID-int-) | 有关此属性的描述，请参阅 [getID()](../../com.aspose.diagram/prop\#getID--) |
| [setIX(int value)](#setIX-int-) | 有关此属性的描述，请参阅 [getIX()](../../com.aspose.diagram/prop\#getIX--) |
| [setName(String value)](#setName-java.lang.String-) | 有关此属性的描述，请参阅 [getName()](../../com.aspose.diagram/prop\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | 有关此属性的描述，请参阅 [getNameU()](../../com.aspose.diagram/prop\#getNameU--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Prop() {#Prop--}
```
public Prop()
```


构造函数。

### deepClone() {#deepClone--}
```
public Prop deepClone()
```


创建此实例的深度副本。

**Returns:**
[Prop](../../com.aspose.diagram/prop) - 
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
### getFormat() {#getFormat--}
```
public StrValue getFormat()
```


Format 元素指定自定义属性的格式，该属性可以是字符串、固定列表、数字、可变列表、日期或时间、持续时间或货币。自定义属性类型在相应的 Type 元素中指定。

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
### getID() {#getID--}
```
public int getID()
```


元素在其父元素中的唯一 ID。

**Returns:**
int
### getIX() {#getIX--}
```
public int getIX()
```


元素在其父元素中的零基索引。

**Returns:**
int
### getInvisible() {#getInvisible--}
```
public BoolValue getInvisible()
```


Invisible 元素指定自定义属性在 Microsoft Visio 的自定义属性对话框中是否可见。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLabel() {#getLabel--}
```
public Str2Value getLabel()
```


指定在自定义属性对话框中显示给用户的标签。

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getLangID() {#getLangID--}
```
public IntValue getLangID()
```


指示输入单元格公式、文本、自定义属性或注释的语言的区域标识符 (LCID)。

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getName() {#getName--}
```
public String getName()
```


元素的名称。

**Returns:**
java.lang.String
### getNameU() {#getNameU--}
```
public String getNameU()
```


元素的通用名称。

**Returns:**
java.lang.String
### getPrompt() {#getPrompt--}
```
public Str2Value getPrompt()
```


Prompt 元素指定描述性或指令性文本，当属性被选中时，该文本会显示在自定义属性对话框中。该文本在鼠标指针悬停在自定义属性窗口中的属性上时，也会作为工具提示显示。

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getSortKey() {#getSortKey--}
```
public Str2Value getSortKey()
```


它指定一个键，用于决定自定义属性在应用程序用户界面中列出的顺序。

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getType() {#getType--}
```
public TypeProp getType()
```


Type 指定自定义属性值的数据类型。

**Returns:**
[TypeProp](../../com.aspose.diagram/typeprop)
### getValue() {#getValue--}
```
public Value getValue()
```


包含特定解决方案的、在显式命名空间前缀的、符合规范的 XML 数据，并随文档一起存储。

**Returns:**
[Value](../../com.aspose.diagram/value)
### getVerify() {#getVerify--}
```
public BoolValue getVerify()
```


指定在创建实例或复制/复制形状时，是否向用户询问输入形状的自定义属性信息。

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


有关此属性的描述，请参阅 [getDel()](../../com.aspose.diagram/prop\#getDel--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


有关此属性的描述，请参阅 [getID()](../../com.aspose.diagram/prop\#getID--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


有关此属性的描述，请参阅 [getIX()](../../com.aspose.diagram/prop\#getIX--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


有关此属性的描述，请参阅 [getName()](../../com.aspose.diagram/prop\#getName--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


有关此属性的描述，请参阅 [getNameU()](../../com.aspose.diagram/prop\#getNameU--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

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

