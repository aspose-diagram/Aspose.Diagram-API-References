---
title: SmartTagDef
second_title: Aspose.Diagram for Java API 参考
description: 包含为形状或页面定义的每个智能标签提供信息的元素。
type: docs
weight: 374
url: /zh/java/com.aspose.diagram/smarttagdef/
---

**Inheritance:**
java.lang.Object
```
public class SmartTagDef
```

包含为形状或页面定义的每个智能标签提供信息的元素。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SmartTagDef()](#SmartTagDef--) | 构造函数。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getButtonFace()](#getButtonFace--) | 它包含显示在智能标签按钮上的按钮面图像的 ID。 |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | 指示元素是否已在本地删除的标志。 |
| [getDescription()](#getDescription--) | Description 元素包含一个字符串，用于描述智能标签，当用户将鼠标悬停在标签上时会显示为工具提示。 |
| [getDisabled()](#getDisabled--) | Disabled 元素决定智能标签是否出现在绘图窗口中。 |
| [getDisplayMode()](#getDisplayMode--) | DisplayMode 元素决定智能标签是在用户将鼠标悬停在标签上时出现、在形状被选中时出现，还是始终出现。 |
| [getID()](#getID--) | 元素在其父元素中的唯一 ID。 |
| [getName()](#getName--) | 元素的名称。 |
| [getNameU()](#getNameU--) | 元素的通用名称。 |
| [getTagName()](#getTagName--) | 它包含智能标签的名称，该名称用作将智能标签与其操作关联的键。 |
| [getX()](#getX--) | 在形状本地坐标系中放置智能标签按钮的 x 坐标位置。 |
| [getXJustify()](#getXJustify--) | 智能标签按钮相对于 X 和 Y 元素定义的点的 x 偏移量。 |
| [getY()](#getY--) | 在形状本地坐标系中放置智能标签按钮的 y 坐标位置。 |
| [getYJustify()](#getYJustify--) | 智能标签按钮相对于 X 和 Y 元素定义的点的 y 偏移量。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | 有关此属性的描述，请参阅 [getDel()](../../com.aspose.diagram/smarttagdef\#getDel--) |
| [setID(int value)](#setID-int-) | 有关此属性的描述，请参阅 [getID()](../../com.aspose.diagram/smarttagdef\#getID--) |
| [setName(String value)](#setName-java.lang.String-) | 有关此属性的描述，请参阅 [getName()](../../com.aspose.diagram/smarttagdef\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | 有关此属性的描述，请参阅 [getNameU()](../../com.aspose.diagram/smarttagdef\#getNameU--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SmartTagDef() {#SmartTagDef--}
```
public SmartTagDef()
```


构造函数。

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
### getButtonFace() {#getButtonFace--}
```
public Str2Value getButtonFace()
```


它包含显示在智能标签按钮上的按钮面图像的 ID。

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
### getDescription() {#getDescription--}
```
public Str2Value getDescription()
```


Description 元素包含一个字符串，用于描述智能标签，当用户将鼠标悬停在标签上时会显示为工具提示。

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getDisabled() {#getDisabled--}
```
public BoolValue getDisabled()
```


Disabled 元素决定智能标签是否出现在绘图窗口中。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getDisplayMode() {#getDisplayMode--}
```
public DisplayModeSmartTagDef getDisplayMode()
```


DisplayMode 元素决定智能标签是在用户将鼠标悬停在标签上时出现、在形状被选中时出现，还是始终出现。

**Returns:**
[DisplayModeSmartTagDef](../../com.aspose.diagram/displaymodesmarttagdef)
### getID() {#getID--}
```
public int getID()
```


元素在其父元素中的唯一 ID。

**Returns:**
int
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
### getTagName() {#getTagName--}
```
public Str2Value getTagName()
```


它包含智能标签的名称，该名称用作将智能标签与其操作关联的键。

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getX() {#getX--}
```
public DoubleValue getX()
```


在形状本地坐标系中放置智能标签按钮的 x 坐标位置。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getXJustify() {#getXJustify--}
```
public XJustify getXJustify()
```


智能标签按钮相对于 X 和 Y 元素定义的点的 x 偏移量。

**Returns:**
[XJustify](../../com.aspose.diagram/xjustify)
### getY() {#getY--}
```
public DoubleValue getY()
```


在形状本地坐标系中放置智能标签按钮的 y 坐标位置。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getYJustify() {#getYJustify--}
```
public YJustify getYJustify()
```


智能标签按钮相对于 X 和 Y 元素定义的点的 y 偏移量。

**Returns:**
[YJustify](../../com.aspose.diagram/yjustify)
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


有关此属性的描述，请参阅 [getDel()](../../com.aspose.diagram/smarttagdef\#getDel--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


有关此属性的描述，请参阅 [getID()](../../com.aspose.diagram/smarttagdef\#getID--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


有关此属性的描述，请参阅 [getName()](../../com.aspose.diagram/smarttagdef\#getName--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


有关此属性的描述，请参阅 [getNameU()](../../com.aspose.diagram/smarttagdef\#getNameU--)

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

