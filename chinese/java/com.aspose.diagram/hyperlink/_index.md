---
title: 超链接
second_title: Aspose.Diagram for Java API 参考
description: 包含用于在形状或绘图页面与另一个绘图页面、其他文件或网站之间创建多个跳转的元素。
type: docs
weight: 193
url: /zh/java/com.aspose.diagram/hyperlink/
---

**Inheritance:**
java.lang.Object
```
public class Hyperlink
```

包含用于在形状或绘图页面与另一个绘图页面、另一个文件或网站之间创建多个跳转的元素。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Hyperlink()](#Hyperlink--) | 构造函数。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [deepClone()](#deepClone--) | 创建此实例的深度副本。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAddress()](#getAddress--) | 指定要跳转的 URL 地址、DOS 文件名或 UNC 路径。 |
| [getClass()](#getClass--) |  |
| [getDefault()](#getDefault--) | 指定形状或页面的默认超链接。 |
| [getDel()](#getDel--) | 指示元素是否已在本地删除的标志。 |
| [getDescription()](#getDescription--) | Description 元素包含描述超链接的文本字符串。 |
| [getExtraInfo()](#getExtraInfo--) | 包含用于解析 URL 的信息，例如图像映射的坐标。 |
| [getFrame()](#getFrame--) | 包含在 Microsoft Visio 作为容器应用程序中的活动文档打开时要定位的框架名称。 |
| [getID()](#getID--) | 元素在其父元素中的唯一 ID。 |
| [getInvisible()](#getInvisible--) | Invisible 元素指示超链接是否出现在形状或页面的快捷菜单上。 |
| [getName()](#getName--) | 元素的名称。 |
| [getNameU()](#getNameU--) | 元素的通用名称。 |
| [getNewWindow()](#getNewWindow--) | 指定 Microsoft Visio 在遵循超链接打开网页或其他 Visio 文档时，是否在新位置打开窗口。 |
| [getSortKey()](#getSortKey--) | Invisible 元素指示超链接是否出现在形状或页面的快捷菜单上。 |
| [getSubAddress()](#getSubAddress--) | 指定目标文档内的链接位置。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | 有关此属性的描述，请参阅 [getDel()](../../com.aspose.diagram/hyperlink\#getDel--) |
| [setID(int value)](#setID-int-) | 有关此属性的描述，请参阅 [getID()](../../com.aspose.diagram/hyperlink\#getID--) |
| [setName(String value)](#setName-java.lang.String-) | 有关此属性的描述，请参阅 [getName()](../../com.aspose.diagram/hyperlink\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | 有关此属性的描述，请参阅 [getNameU()](../../com.aspose.diagram/hyperlink\#getNameU--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Hyperlink() {#Hyperlink--}
```
public Hyperlink()
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
### getAddress() {#getAddress--}
```
public Str2Value getAddress()
```


指定要跳转的 URL 地址、DOS 文件名或 UNC 路径。

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefault() {#getDefault--}
```
public BoolValue getDefault()
```


指定形状或页面的默认超链接。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getDel() {#getDel--}
```
public int getDel()
```


一个标志，指示元素是否已在本地删除。值为 1 表示该元素已在本地删除。

**Returns:**
int
### getDescription() {#getDescription--}
```
public Str2Value getDescription()
```


Description 元素包含描述超链接的文本字符串。

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getExtraInfo() {#getExtraInfo--}
```
public Str2Value getExtraInfo()
```


包含用于解析 URL 的信息，例如图像映射的坐标。例如，x=41 y=7 将指定图像映射的坐标。

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getFrame() {#getFrame--}
```
public Str2Value getFrame()
```


包含在 Microsoft Visio 作为容器应用程序中的活动文档打开时要定位的框架名称。默认值为空字符串。

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getID() {#getID--}
```
public int getID()
```


元素在其父元素中的唯一 ID。

**Returns:**
int
### getInvisible() {#getInvisible--}
```
public BoolValue getInvisible()
```


Invisible 元素指示超链接是否出现在形状或页面的快捷菜单上。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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
### getNewWindow() {#getNewWindow--}
```
public BoolValue getNewWindow()
```


指定 Microsoft Visio 在遵循超链接打开网页或其他 Visio 文档时，是否在新位置打开窗口。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getSortKey() {#getSortKey--}
```
public Str2Value getSortKey()
```


Invisible 元素指示超链接是否出现在形状或页面的快捷菜单上。

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getSubAddress() {#getSubAddress--}
```
public Str2Value getSubAddress()
```


指定目标文档内的链接位置。

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
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


有关此属性的描述，请参阅 [getDel()](../../com.aspose.diagram/hyperlink\#getDel--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


有关此属性的描述，请参阅 [getID()](../../com.aspose.diagram/hyperlink\#getID--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


有关此属性的描述，请参阅 [getName()](../../com.aspose.diagram/hyperlink\#getName--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


有关此属性的描述，请参阅 [getNameU()](../../com.aspose.diagram/hyperlink\#getNameU--)

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

