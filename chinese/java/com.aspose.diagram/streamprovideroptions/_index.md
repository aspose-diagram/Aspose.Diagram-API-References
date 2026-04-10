---
title: StreamProviderOptions
second_title: Aspose.Diagram for Java API 参考
description: 表示流选项。
type: docs
weight: 390
url: /zh/java/com.aspose.diagram/streamprovideroptions/
---

**Inheritance:**
java.lang.Object
```
public class StreamProviderOptions
```

表示流选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [StreamProviderOptions()](#StreamProviderOptions--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultPath()](#getDefaultPath--) | 默认路径（URL）保存在生成的 html 文件中，用于引用的源。 |
| [getStream()](#getStream--) | 获取/设置用于写入已保存数据的输出流 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomPath(String value)](#setCustomPath-java.lang.String-) | 用户自定义路径（URL）保存在生成的 html 文件中，用于引用的源。 |
| [setStream(OutputStream value)](#setStream-java.io.OutputStream-) | 有关此属性的描述，请参阅 [getStream()](../../com.aspose.diagram/streamprovideroptions\#getStream--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StreamProviderOptions() {#StreamProviderOptions--}
```
public StreamProviderOptions()
```


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
### getDefaultPath() {#getDefaultPath--}
```
public String getDefaultPath()
```


默认路径（URL）保存在生成的 html 文件中，用于引用的源。例如，工作表数据保存在 xxx\_files/sheet001.htm 中，主 html 文件中使用的 url 应该类似于 "src=\"xxx\_files/sheet001.htm\""

**Returns:**
java.lang.String
### getStream() {#getStream--}
```
public OutputStream getStream()
```


获取/设置用于写入已保存数据的输出流

**Returns:**
java.io.OutputStream
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




### setCustomPath(String value) {#setCustomPath-java.lang.String-}
```
public void setCustomPath(String value)
```


用户自定义路径（URL）保存在生成的 html 文件中，用于引用的源。如果用户未定义，将使用 DefaultPath。例如，工作表数据将由用户保存到 d:/sheet001.htm，主 html 文件中使用的 url 应为 "d:/sheet001.htm" 或其他可被主 html 文件访问的有效相对路径。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setStream(OutputStream value) {#setStream-java.io.OutputStream-}
```
public void setStream(OutputStream value)
```


有关此属性的描述，请参阅 [getStream()](../../com.aspose.diagram/streamprovideroptions\#getStream--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.io.OutputStream |  |

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

