---
title: Group
second_title: Aspose.Diagram لـ Java API Reference
description: يحتوي على عناصر تتحكم في كيفية إضافة الأشكال إلى مجموعة، وتحريك أعضاء المجموعة، وتحديد المجموعات.
type: docs
weight: 186
url: /ar/java/com.aspose.diagram/group/
---

**Inheritance:**
java.lang.Object
```
public class Group
```

يحتوي على عناصر تتحكم في كيفية إضافة الأشكال إلى مجموعة، نقل أعضاء المجموعة، واختيار المجموعات.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | علامة تشير إلى ما إذا تم حذف العنصر محليًا. |
| [getDisplayMode()](#getDisplayMode--) | عند وجوده داخل عنصر Group، يحدد عنصر DisplayMode كيفية عرض الشكل الجماعي وأعضائه. |
| [getDontMoveChildren()](#getDontMoveChildren--) | يحدد ما إذا كان بإمكانك سحب الأشكال داخل مجموعة باستخدام الفأرة. |
| [getSelectMode()](#getSelectMode--) | يحدد كيفية اختيار المستخدم لشكل مجموعة وأعضائها. |
| [hashCode()](#hashCode--) |  |
| [isDropTarget()](#isDropTarget--) | يحدد ما إذا كانت المجموعة تسمح بإضافة شكل إليها عندما يتم إسقاط الشكل على المجموعة. |
| [isSnapTarget()](#isSnapTarget--) | يحدد ما إذا كان الالتقاط إلى مجموعة أو إلى الأشكال داخل المجموعة مفعلاً. |
| [isTextEditTarget()](#isTextEditTarget--) | يحدد كيفية تعيين النص إلى مجموعة. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getDel()](../../com.aspose.diagram/group\#getDel--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getDel() {#getDel--}
```
public int getDel()
```


علامة تشير إلى ما إذا كان العنصر قد تم حذفه محليًا. القيمة 1 تشير إلى أن العنصر تم حذفه محليًا.

**Returns:**
int
### getDisplayMode() {#getDisplayMode--}
```
public DisplayMode getDisplayMode()
```


عند وجوده داخل عنصر Group، يحدد عنصر DisplayMode كيفية عرض الشكل الجماعي وأعضائه.

**Returns:**
[DisplayMode](../../com.aspose.diagram/displaymode)
### getDontMoveChildren() {#getDontMoveChildren--}
```
public BoolValue getDontMoveChildren()
```


يحدد ما إذا كان بإمكانك سحب الأشكال داخل مجموعة باستخدام الفأرة.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getSelectMode() {#getSelectMode--}
```
public SelectMode getSelectMode()
```


يحدد كيفية اختيار المستخدم لشكل مجموعة وأعضائها.

**Returns:**
[SelectMode](../../com.aspose.diagram/selectmode)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDropTarget() {#isDropTarget--}
```
public BoolValue isDropTarget()
```


يحدد ما إذا كانت المجموعة تسمح بإضافة شكل إليها عندما يتم إسقاط الشكل على المجموعة.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### isSnapTarget() {#isSnapTarget--}
```
public BoolValue isSnapTarget()
```


يحدد ما إذا كان الالتقاط إلى مجموعة أو إلى الأشكال داخل المجموعة مفعلاً.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### isTextEditTarget() {#isTextEditTarget--}
```
public BoolValue isTextEditTarget()
```


يحدد كيفية تعيين النص إلى مجموعة.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getDel()](../../com.aspose.diagram/group\#getDel--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

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

