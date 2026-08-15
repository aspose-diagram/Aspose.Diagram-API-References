---
title: IssueTarget
second_title: Aspose.Diagram لـ Java API Reference
description: اعتمادًا على هدف مشكلة التحقق الأصلية، يحدد إما الصفحة أو كلًا من الصفحة والشكل المرتبط بمشكلة التحقق الأصلية.
type: docs
weight: 210
url: /ar/java/com.aspose.diagram/issuetarget/
---

**Inheritance:**
java.lang.Object
```
public class IssueTarget
```

اعتمادًا على هدف مشكلة التحقق الأصلية، يحدد إما الصفحة أو كلًا من الصفحة والشكل المرتبط بمشكلة التحقق الأصلية. إذا كان هدف مشكلة التحقق الأصلية هو مستند، فإن IssueTarget لا يحدد صفحة ولا شكل.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [IssueTarget(long pageID, long shapeID)](#IssueTarget-long-long-) | منشئ. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getPageId()](#getPageId--) | يحدد المعرف الفريد للصفحة المرتبطة بمشكلة التحقق الأصلية. |
| [getShapeId()](#getShapeId--) | يحدد المعرف الفريد للشكل المرتبط بمشكلة التحقق الأصلية. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setPageId(long value)](#setPageId-long-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getPageId()](../../com.aspose.diagram/issuetarget\#getPageId--) |
| [setShapeId(long value)](#setShapeId-long-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getShapeId()](../../com.aspose.diagram/issuetarget\#getShapeId--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### IssueTarget(long pageID, long shapeID) {#IssueTarget-long-long-}
```
public IssueTarget(long pageID, long shapeID)
```


منشئ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageID | long |  |
| shapeID | long |  |

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
### getPageId() {#getPageId--}
```
public long getPageId()
```


يحدد المعرف الفريد للصفحة المرتبطة بمشكلة التحقق الأصلية. إذا كان الهدف هو المستند، يمكن أن تكون قيمة PageID هي 0xFFFFFFFF.

**Returns:**
long
### getShapeId() {#getShapeId--}
```
public long getShapeId()
```


يحدد المعرف الفريد للشكل المرتبط بمشكلة التحقق الأصلية. إذا كان الهدف هو المستند أو صفحة، يمكن أن تكون قيمة ShapeID هي 0xFFFFFFFF.

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


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getPageId()](../../com.aspose.diagram/issuetarget\#getPageId--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | long |  |

### setShapeId(long value) {#setShapeId-long-}
```
public void setShapeId(long value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getShapeId()](../../com.aspose.diagram/issuetarget\#getShapeId--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | long |  |

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

