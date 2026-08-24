---
title: EventItem
second_title: Aspose.Diagram for Java API 参考
description: 封装事件代码。
type: docs
weight: 145
url: /zh/java/com.aspose.diagram/eventitem/
---

**Inheritance:**
java.lang.Object
```
public class EventItem
```

封装事件代码。EventItem 元素可以触发两种操作：它可以运行加载项，或向调用程序发送事件通知。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EventItem()](#EventItem--) | 构造函数。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | 指定父 EventItem 元素的操作代码。要将 EventItem 元素保存到 DatadiagramML 文件中，必须是可持久化的。 |
| [getClass()](#getClass--) |  |
| [getEnabled()](#getEnabled--) | 表示指示事件是启用还是禁用的标志。 |
| [getEventCode()](#getEventCode--) | 指示触发加载项的事件的代码。 |
| [getID()](#getID--) | 事件的 ID。 |
| [getTarget()](#getTarget--) | 指定事件的目标。 |
| [getTargetArgs()](#getTargetArgs--) | 指定包含要发送到事件目标的参数的字符串。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAction(int value)](#setAction-int-) | 有关此属性的描述，请参阅 [getAction()](../../com.aspose.diagram/eventitem\#getAction--) |
| [setEnabled(int value)](#setEnabled-int-) | 有关此属性的描述，请参阅 [getEnabled()](../../com.aspose.diagram/eventitem\#getEnabled--) |
| [setEventCode(int value)](#setEventCode-int-) | 有关此属性的描述，请参阅 [getEventCode()](../../com.aspose.diagram/eventitem\#getEventCode--) |
| [setID(int value)](#setID-int-) | 有关此属性的描述，请参阅 [getID()](../../com.aspose.diagram/eventitem\#getID--) |
| [setTarget(String value)](#setTarget-java.lang.String-) | 有关此属性的描述，请参阅 [getTarget()](../../com.aspose.diagram/eventitem\#getTarget--) |
| [setTargetArgs(String value)](#setTargetArgs-java.lang.String-) | 有关此属性的描述，请参阅 [getTargetArgs()](../../com.aspose.diagram/eventitem\#getTargetArgs--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EventItem() {#EventItem--}
```
public EventItem()
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
### getAction() {#getAction--}
```
public int getAction()
```


指定父 EventItem 元素的操作代码。要将 EventItem 元素保存到 DatadiagramML 文件中，必须是可持久化的。目前，可持久化事件唯一有效的操作代码是 1（ONEVENT_ACT_RUNADDON）。

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEnabled() {#getEnabled--}
```
public int getEnabled()
```


表示指示事件是启用还是禁用的标志。

**Returns:**
int
### getEventCode() {#getEventCode--}
```
public int getEventCode()
```


指示触发加载项的事件的代码。有关事件代码的更多信息，请参阅 Microsoft Visio 2007 Automation Reference 中的 Event Codes。

**Returns:**
int
### getID() {#getID--}
```
public int getID()
```


事件的 ID。

**Returns:**
int
### getTarget() {#getTarget--}
```
public String getTarget()
```


指定事件的目标。

**Returns:**
java.lang.String
### getTargetArgs() {#getTargetArgs--}
```
public String getTargetArgs()
```


指定包含要发送到事件目标的参数的字符串。

**Returns:**
java.lang.String
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




### setAction(int value) {#setAction-int-}
```
public void setAction(int value)
```


有关此属性的描述，请参阅 [getAction()](../../com.aspose.diagram/eventitem\#getAction--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setEnabled(int value) {#setEnabled-int-}
```
public void setEnabled(int value)
```


有关此属性的描述，请参阅 [getEnabled()](../../com.aspose.diagram/eventitem\#getEnabled--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setEventCode(int value) {#setEventCode-int-}
```
public void setEventCode(int value)
```


有关此属性的描述，请参阅 [getEventCode()](../../com.aspose.diagram/eventitem\#getEventCode--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


有关此属性的描述，请参阅 [getID()](../../com.aspose.diagram/eventitem\#getID--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setTarget(String value) {#setTarget-java.lang.String-}
```
public void setTarget(String value)
```


有关此属性的描述，请参阅 [getTarget()](../../com.aspose.diagram/eventitem\#getTarget--)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setTargetArgs(String value) {#setTargetArgs-java.lang.String-}
```
public void setTargetArgs(String value)
```


有关此属性的描述，请参阅 [getTargetArgs()](../../com.aspose.diagram/eventitem\#getTargetArgs--)

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

