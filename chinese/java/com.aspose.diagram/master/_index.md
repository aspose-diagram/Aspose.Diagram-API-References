---
title: Master
second_title: Aspose.Diagram for Java API 参考
description: 包含定义文档母版的元素。
type: docs
weight: 240
url: /zh/java/com.aspose.diagram/master/
---

**Inheritance:**
java.lang.Object
```
public class Master
```

包含定义文档 master 的元素。master 是模板（stencil）上的一种形状，您可以重复使用它来创建图纸。当您将形状从模板拖到绘图页面时，该形状成为该 master 的实例，并且该 master 的本地副本会包含在文档中。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Master()](#Master--) | 构造函数。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [deepClone()](#deepClone--) | 创建此实例的深度副本。 |
| [dispose()](#dispose--) | 执行应用程序定义的任务，涉及释放、释放或重置非托管资源。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignName()](#getAlignName--) | 指定 stencil 窗口中 master 的文本是左对齐、右对齐还是居中。 |
| [getBaseID()](#getBaseID--) | 在文档之间标识 master 的 GUID（全局唯一标识符）。 |
| [getClass()](#getClass--) |  |
| [getConnects()](#getConnects--) | 为绘图中两个形状之间的每个连接包含一个 Connect 元素。 |
| [getHidden()](#getHidden--) | 指定 master 在用户界面中是否隐藏。 |
| [getID()](#getID--) | 元素在其父元素中的唯一 ID。 |
| [getIcon()](#getIcon--) | 为文档中的 Master 或 MasterShortcut 元素指定 MIME（多用途互联网邮件扩展）编码的二进制图标（.ico 格式）。 |
| [getIconSize()](#getIconSize--) | 元素图标的大小。 |
| [getIconUpdate()](#getIconUpdate--) | 指定图标是否自动从 master 本身生成。 |
| [getMatchByName()](#getMatchByName--) | MatchByName 属性决定 Microsoft Visio 在将 master 实例拖放到绘图页面时，如何判断文档中是否已存在该 master。 |
| [getName()](#getName--) | 元素的名称。 |
| [getNameU()](#getNameU--) | 元素的通用名称。 |
| [getPageSheet()](#getPageSheet--) | 包含定义页面或母版元素的页面工作表的元素。 |
| [getPatternFlags()](#getPatternFlags--) | PatternFlags 属性决定主控件是否表现为自定义模式。 |
| [getPrompt()](#getPrompt--) | 状态栏和工具提示为该元素提供提示。 |
| [getShapes()](#getShapes--) | Shape 对象的集合。 |
| [getUniqueID()](#getUniqueID--) | 用于标识文档中主控件的 GUID。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignName(int value)](#setAlignName-int-) | 有关此属性的描述，请参阅 [getAlignName()](../../com.aspose.diagram/master\#getAlignName--) |
| [setBaseID(UUID value)](#setBaseID-java.util.UUID-) | 有关此属性的描述，请参阅 [getBaseID()](../../com.aspose.diagram/master\#getBaseID--) |
| [setHidden(int value)](#setHidden-int-) | 有关此属性的描述，请参阅 [getHidden()](../../com.aspose.diagram/master\#getHidden--) |
| [setID(int value)](#setID-int-) | 有关此属性的描述，请参阅 [getID()](../../com.aspose.diagram/master\#getID--) |
| [setIcon(byte[] value)](#setIcon-byte---) | 有关此属性的描述，请参阅 [getIcon()](../../com.aspose.diagram/master\#getIcon--) |
| [setIconSize(int value)](#setIconSize-int-) | 有关此属性的描述，请参阅 [getIconSize()](../../com.aspose.diagram/master\#getIconSize--) |
| [setIconUpdate(int value)](#setIconUpdate-int-) | 有关此属性的描述，请参阅 [getIconUpdate()](../../com.aspose.diagram/master\#getIconUpdate--) |
| [setMatchByName(int value)](#setMatchByName-int-) | 有关此属性的描述，请参阅 [getMatchByName()](../../com.aspose.diagram/master\#getMatchByName--) |
| [setName(String value)](#setName-java.lang.String-) | 有关此属性的描述，请参阅 [getName()](../../com.aspose.diagram/master\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | 有关此属性的描述，请参阅 [getNameU()](../../com.aspose.diagram/master\#getNameU--) |
| [setPatternFlags(int value)](#setPatternFlags-int-) | 有关此属性的描述，请参阅 [getPatternFlags()](../../com.aspose.diagram/master\#getPatternFlags--) |
| [setPrompt(String value)](#setPrompt-java.lang.String-) | 有关此属性的描述，请参阅 [getPrompt()](../../com.aspose.diagram/master\#getPrompt--) |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | 有关此属性的描述，请参阅 [getUniqueID()](../../com.aspose.diagram/master\#getUniqueID--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Master() {#Master--}
```
public Master()
```


构造函数。

### deepClone() {#deepClone--}
```
public Object deepClone()
```


创建此实例的深度副本。

**Returns:**
java.lang.Object -
### dispose() {#dispose--}
```
public void dispose()
```


执行应用程序定义的任务，涉及释放、释放或重置非托管资源。

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
### getAlignName() {#getAlignName--}
```
public int getAlignName()
```


指定 stencil 窗口中 master 的文本是左对齐、右对齐还是居中。

**Returns:**
int
### getBaseID() {#getBaseID--}
```
public UUID getBaseID()
```


在文档之间标识 master 的 GUID（全局唯一标识符）。

**Returns:**
java.util.UUID
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConnects() {#getConnects--}
```
public ConnectCollection getConnects()
```


为绘图中两个形状之间的每个连接包含一个 Connect 元素。

**Returns:**
[ConnectCollection](../../com.aspose.diagram/connectcollection)
### getHidden() {#getHidden--}
```
public int getHidden()
```


指定 master 在用户界面中是否隐藏。

**Returns:**
int
### getID() {#getID--}
```
public int getID()
```


元素在其父元素中的唯一 ID。

**Returns:**
int
### getIcon() {#getIcon--}
```
public byte[] getIcon()
```


为文档中的 Master 或 MasterShortcut 元素指定 MIME（多用途互联网邮件扩展）编码的二进制图标（.ico 格式）。

**Returns:**
byte[]
### getIconSize() {#getIconSize--}
```
public int getIconSize()
```


元素图标的大小。

**Returns:**
int
### getIconUpdate() {#getIconUpdate--}
```
public int getIconUpdate()
```


指定图标是否自动从 master 本身生成。

**Returns:**
int
### getMatchByName() {#getMatchByName--}
```
public int getMatchByName()
```


MatchByName 属性决定 Microsoft Visio 在将主控件实例拖放到绘图页面时，如何判断文档中是否已经存在该主控件。它允许对文档主控件所做的更改应用于该主控件的新实例，即使这些实例是从独立的模板文件中拖动的。

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
### getPageSheet() {#getPageSheet--}
```
public PageSheet getPageSheet()
```


包含定义页面或母版元素的页面工作表的元素。

**Returns:**
[PageSheet](../../com.aspose.diagram/pagesheet)
### getPatternFlags() {#getPatternFlags--}
```
public int getPatternFlags()
```


PatternFlags 属性决定主控件是否表现为自定义模式。

**Returns:**
int
### getPrompt() {#getPrompt--}
```
public String getPrompt()
```


状态栏和工具提示为该元素提供提示。

**Returns:**
java.lang.String
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


Shape 对象的集合。

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


用于标识文档中主控件的 GUID。

**Returns:**
java.util.UUID
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




### setAlignName(int value) {#setAlignName-int-}
```
public void setAlignName(int value)
```


有关此属性的描述，请参阅 [getAlignName()](../../com.aspose.diagram/master\#getAlignName--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setBaseID(UUID value) {#setBaseID-java.util.UUID-}
```
public void setBaseID(UUID value)
```


有关此属性的描述，请参阅 [getBaseID()](../../com.aspose.diagram/master\#getBaseID--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.util.UUID |  |

### setHidden(int value) {#setHidden-int-}
```
public void setHidden(int value)
```


有关此属性的描述，请参阅 [getHidden()](../../com.aspose.diagram/master\#getHidden--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


有关此属性的描述，请参阅 [getID()](../../com.aspose.diagram/master\#getID--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setIcon(byte[] value) {#setIcon-byte---}
```
public void setIcon(byte[] value)
```


有关此属性的描述，请参阅 [getIcon()](../../com.aspose.diagram/master\#getIcon--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte[] |  |

### setIconSize(int value) {#setIconSize-int-}
```
public void setIconSize(int value)
```


有关此属性的描述，请参阅 [getIconSize()](../../com.aspose.diagram/master\#getIconSize--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setIconUpdate(int value) {#setIconUpdate-int-}
```
public void setIconUpdate(int value)
```


有关此属性的描述，请参阅 [getIconUpdate()](../../com.aspose.diagram/master\#getIconUpdate--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setMatchByName(int value) {#setMatchByName-int-}
```
public void setMatchByName(int value)
```


有关此属性的描述，请参阅 [getMatchByName()](../../com.aspose.diagram/master\#getMatchByName--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


有关此属性的描述，请参阅 [getName()](../../com.aspose.diagram/master\#getName--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


有关此属性的描述，请参阅 [getNameU()](../../com.aspose.diagram/master\#getNameU--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setPatternFlags(int value) {#setPatternFlags-int-}
```
public void setPatternFlags(int value)
```


有关此属性的描述，请参阅 [getPatternFlags()](../../com.aspose.diagram/master\#getPatternFlags--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setPrompt(String value) {#setPrompt-java.lang.String-}
```
public void setPrompt(String value)
```


有关此属性的描述，请参阅 [getPrompt()](../../com.aspose.diagram/master\#getPrompt--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


有关此属性的描述，请参阅 [getUniqueID()](../../com.aspose.diagram/master\#getUniqueID--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.util.UUID |  |

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

