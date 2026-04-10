---
title: 连接
second_title: Aspose.Diagram for Java API 参考
description: 包含为形状定义的一个连接点的元素。
type: docs
weight: 78
url: /zh/java/com.aspose.diagram/connection/
---

**Inheritance:**
java.lang.Object
```
public class Connection
```

包含为形状定义的一个连接点的元素。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Connection()](#Connection--) | 构造函数。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [deepClone()](#deepClone--) | 创建此实例的深度副本。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoGen()](#getAutoGen--) | 指定是否自动生成连接点。 |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | 指示元素是否已在本地删除的标志。 |
| [getDirX()](#getDirX--) | 指定匹配连接点所需对齐向量的 x 分量。 |
| [getDirY()](#getDirY--) | 指定匹配连接点所需对齐向量的 y 分量。 |
| [getID()](#getID--) | 元素在其父元素中的唯一 ID。 |
| [getIX()](#getIX--) | 元素在其父元素中的零基索引。 |
| [getName()](#getName--) | 元素的名称。 |
| [getNameU()](#getNameU--) | 元素的通用名称。 |
| [getPrompt()](#getPrompt--) | 包含基于其所在元素的不同提示信息。 |
| [getType()](#getType--) | 根据其所在的元素指定各种类型。 |
| [getX()](#getX--) | 指定形状在局部坐标系中的 x 坐标。 |
| [getY()](#getY--) | 指定形状在局部坐标系中的 y 坐标。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | 有关此属性的描述，请参阅 [getDel()](../../com.aspose.diagram/connection\#getDel--) |
| [setID(int value)](#setID-int-) | 有关此属性的描述，请参阅 [getID()](../../com.aspose.diagram/connection\#getID--) |
| [setIX(int value)](#setIX-int-) | 有关此属性的描述，请参阅 [getIX()](../../com.aspose.diagram/connection\#getIX--) |
| [setName(String value)](#setName-java.lang.String-) | 有关此属性的描述，请参阅 [getName()](../../com.aspose.diagram/connection\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | 有关此属性的描述，请参阅 [getNameU()](../../com.aspose.diagram/connection\#getNameU--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Connection() {#Connection--}
```
public Connection()
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
### getAutoGen() {#getAutoGen--}
```
public BoolValue getAutoGen()
```


指定是否自动生成连接点。值为 1 表示连接点是自动生成的。

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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
### getDirX() {#getDirX--}
```
public DoubleValue getDirX()
```


指定匹配连接点所需对齐向量的 x 分量。DirX 元素还用于定位动态连接器的附加腿部。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDirY() {#getDirY--}
```
public DoubleValue getDirY()
```


指定匹配连接点所需对齐向量的 y 分量。DirY 元素还用于定位动态连接器的附加腿部。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
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


包含基于其所在元素的不同提示信息。

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getType() {#getType--}
```
public TypeConnection getType()
```


根据其所在的元素指定各种类型。

**Returns:**
[TypeConnection](../../com.aspose.diagram/typeconnection)
### getX() {#getX--}
```
public DoubleValue getX()
```


指定形状在局部坐标系中的 x 坐标。

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getY() {#getY--}
```
public DoubleValue getY()
```


指定形状在局部坐标系中的 y 坐标。局部坐标系是指参考框架为形状本身，而非页面的坐标系。

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


有关此属性的描述，请参阅 [getDel()](../../com.aspose.diagram/connection\#getDel--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


有关此属性的描述，请参阅 [getID()](../../com.aspose.diagram/connection\#getID--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


有关此属性的描述，请参阅 [getIX()](../../com.aspose.diagram/connection\#getIX--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


有关此属性的描述，请参阅 [getName()](../../com.aspose.diagram/connection\#getName--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


有关此属性的描述，请参阅 [getNameU()](../../com.aspose.diagram/connection\#getNameU--)

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

