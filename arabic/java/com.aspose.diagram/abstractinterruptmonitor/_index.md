---
title: AbstractInterruptMonitor
second_title: Aspose.Diagram لـ Java API Reference
description: مراقب لطلبات الإيقاف في جميع العمليات المستهلكة للوقت.
type: docs
weight: 10
url: /ar/java/com.aspose.diagram/abstractinterruptmonitor/
---

**Inheritance:**
java.lang.Object
```
public abstract class AbstractInterruptMonitor
```

مراقب لطلبات الإيقاف في جميع العمليات المستهلكة للوقت.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [AbstractInterruptMonitor()](#AbstractInterruptMonitor--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [isInterruptionRequested()](#isInterruptionRequested--) | يشير إلى ما إذا كان تم طلب مقاطعة العملية الحالية. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AbstractInterruptMonitor() {#AbstractInterruptMonitor--}
```
public AbstractInterruptMonitor()
```


### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
منطقي
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```


يشير إلى ما إذا كان تم طلب مقاطعة العملية الحالية. إذا كان صحيحًا فستتم مقاطعة العملية الحالية.

**Returns:**
منطقي
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

