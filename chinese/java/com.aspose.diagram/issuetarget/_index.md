---
title: IssueTarget
second_title: Aspose.Diagram for Java API 参考
description: 根据父验证问题的目标，指定父验证问题关联的页面或页面和形状。
type: docs
weight: 210
url: /zh/java/com.aspose.diagram/issuetarget/
---

**Inheritance:**
java.lang.Object
```
public class IssueTarget
```

根据父验证问题的目标，指定父验证问题关联的页面，或页面和形状两者。如果父验证问题的目标是文档，则 IssueTarget 既不指定页面也不指定形状。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [IssueTarget(long pageID, long shapeID)](#IssueTarget-long-long-) | 构造函数。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getPageId()](#getPageId--) | 指定与父验证问题关联的页面的唯一标识符。 |
| [getShapeId()](#getShapeId--) | 指定与父验证问题关联的形状的唯一标识符。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setPageId(long value)](#setPageId-long-) | 有关此属性的描述，请参阅 [getPageId()](../../com.aspose.diagram/issuetarget\#getPageId--) |
| [setShapeId(long value)](#setShapeId-long-) | 有关此属性的描述，请参阅 [getShapeId()](../../com.aspose.diagram/issuetarget\#getShapeId--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### IssueTarget(long pageID, long shapeID) {#IssueTarget-long-long-}
```
public IssueTarget(long pageID, long shapeID)
```


构造函数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageID | long |  |
| shapeID | long |  |

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
### getPageId() {#getPageId--}
```
public long getPageId()
```


指定与父验证问题关联的页面的唯一标识符。如果目标是文档，则 PageID 值可以为 0xFFFFFFFF。

**Returns:**
long
### getShapeId() {#getShapeId--}
```
public long getShapeId()
```


指定与父验证问题关联的形状的唯一标识符。如果目标是文档或页面，则 ShapeID 值可以为 0xFFFFFFFF。

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




### setPageId(long value) {#setPageId-long-}
```
public void setPageId(long value)
```


有关此属性的描述，请参阅 [getPageId()](../../com.aspose.diagram/issuetarget\#getPageId--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long |  |

### setShapeId(long value) {#setShapeId-long-}
```
public void setShapeId(long value)
```


有关此属性的描述，请参阅 [getShapeId()](../../com.aspose.diagram/issuetarget\#getShapeId--)

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

