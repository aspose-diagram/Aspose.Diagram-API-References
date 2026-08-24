---
title: DataConnection
second_title: Aspose.Diagram for Java API 参考
description: 抽象化一个或多个 DataRecordset 元素与非 XML 数据源之间的通信。
type: docs
weight: 110
url: /zh/java/com.aspose.diagram/dataconnection/
---

**Inheritance:**
java.lang.Object
```
public class DataConnection
```

抽象化一个或多个 DataRecordset 元素与非 XML 数据源之间的通信。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [DataConnection()](#DataConnection--) | 构造函数。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlwaysUseConnectionFile()](#getAlwaysUseConnectionFile--) | 默认值为 false。 |
| [getClass()](#getClass--) |  |
| [getCommand()](#getCommand--) | 用于查询数据源的命令字符串。 |
| [getConnectionString()](#getConnectionString--) | 定义连接到数据源所需参数的连接字符串。 |
| [getFileName()](#getFileName--) | 连接文件的名称。 |
| [getID()](#getID--) | Visio 为给定连接分配的 ID，在文档中唯一。 |
| [getTimeout()](#getTimeout--) | 在尝试建立连接时的等待时间（分钟），在终止尝试之前。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlwaysUseConnectionFile(int value)](#setAlwaysUseConnectionFile-int-) | 有关此属性的描述，请参阅 [getAlwaysUseConnectionFile()](../../com.aspose.diagram/dataconnection\#getAlwaysUseConnectionFile--) |
| [setCommand(String value)](#setCommand-java.lang.String-) | 有关此属性的描述，请参阅 [getCommand()](../../com.aspose.diagram/dataconnection\#getCommand--) |
| [setConnectionString(String value)](#setConnectionString-java.lang.String-) | 有关此属性的描述，请参阅 [getConnectionString()](../../com.aspose.diagram/dataconnection\#getConnectionString--) |
| [setFileName(String value)](#setFileName-java.lang.String-) | 有关此属性的描述，请参阅 [getFileName()](../../com.aspose.diagram/dataconnection\#getFileName--) |
| [setID(long value)](#setID-long-) | 有关此属性的描述，请参阅 \{@link DataConnection\#(getID() & 0xFFFFFFFFL)\} |
| [setTimeout(long value)](#setTimeout-long-) | 有关此属性的描述，请参阅 [getTimeout()](../../com.aspose.diagram/dataconnection\#getTimeout--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DataConnection() {#DataConnection--}
```
public DataConnection()
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
### getAlwaysUseConnectionFile() {#getAlwaysUseConnectionFile--}
```
public int getAlwaysUseConnectionFile()
```


默认值为 false。有关更多信息，请参阅备注。

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCommand() {#getCommand--}
```
public String getCommand()
```


用于查询数据源的命令字符串。

**Returns:**
java.lang.String
### getConnectionString() {#getConnectionString--}
```
public String getConnectionString()
```


定义连接到数据源所需参数的连接字符串。

**Returns:**
java.lang.String
### getFileName() {#getFileName--}
```
public String getFileName()
```


连接文件的名称。有关更多信息，请参阅备注。

**Returns:**
java.lang.String
### getID() {#getID--}
```
public long getID()
```


Visio 为给定连接分配的 ID，在文档中唯一。

**Returns:**
long
### getTimeout() {#getTimeout--}
```
public long getTimeout()
```


在尝试建立连接时的等待时间（分钟），在终止尝试之前。

**Returns:**
long
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




### setAlwaysUseConnectionFile(int value) {#setAlwaysUseConnectionFile-int-}
```
public void setAlwaysUseConnectionFile(int value)
```


有关此属性的描述，请参阅 [getAlwaysUseConnectionFile()](../../com.aspose.diagram/dataconnection\#getAlwaysUseConnectionFile--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setCommand(String value) {#setCommand-java.lang.String-}
```
public void setCommand(String value)
```


有关此属性的描述，请参阅 [getCommand()](../../com.aspose.diagram/dataconnection\#getCommand--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setConnectionString(String value) {#setConnectionString-java.lang.String-}
```
public void setConnectionString(String value)
```


有关此属性的描述，请参阅 [getConnectionString()](../../com.aspose.diagram/dataconnection\#getConnectionString--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public void setFileName(String value)
```


有关此属性的描述，请参阅 [getFileName()](../../com.aspose.diagram/dataconnection\#getFileName--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setID(long value) {#setID-long-}
```
public void setID(long value)
```


有关此属性的描述，请参阅 \{@link DataConnection\#(getID() & 0xFFFFFFFFL)\}

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long |  |

### setTimeout(long value) {#setTimeout-long-}
```
public void setTimeout(long value)
```


有关此属性的描述，请参阅 [getTimeout()](../../com.aspose.diagram/dataconnection\#getTimeout--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long |  |

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

