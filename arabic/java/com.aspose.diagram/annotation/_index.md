---
title: تعليق توضيحي
second_title: Aspose.Diagram لـ Java API Reference
description: يحتوي على عناصر تتضمن معلومات حول التعليقات المدخلة في صفحة المستند.
type: docs
weight: 20
url: /ar/java/com.aspose.diagram/annotation/
---

**Inheritance:**
java.lang.Object
```
public class Annotation
```

يحتوي على عناصر تتضمن معلومات حول التعليقات المدخلة في صفحة المستند.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getComment()](#getComment--) | يحتوي على نص التعليق بصيغة سلسلة لشكل. |
| [getDate()](#getDate--) | يحدد متى تم إنشاء التعليق |
| [getDel()](#getDel--) | علامة تشير إلى ما إذا تم حذف العنصر محليًا. |
| [getEditDate()](#getEditDate--) | يحدد متى تم تعديل التعليق آخر مرة |
| [getIX()](#getIX--) | فهرس العنصر داخل العنصر الأصل بدءًا من الصفر. |
| [getLangID()](#getLangID--) | يشير إلى معرف اللغة (LCID) للغة التي تم إدخال صيغة الخلية أو النص أو الخاصية المخصصة أو التعليق بها. |
| [getMarkerIndex()](#getMarkerIndex--) | يحدد رقم الفهرس المخصص لعلامة التعليق. |
| [getReviewerID()](#getReviewerID--) | يحتوي على رقم المعرف للمراجع الذي يضيف العلامات إلى المستند. |
| [getShapeID()](#getShapeID--) | معرف الشكل للتعليق. |
| [getX()](#getX--) | الإحداثي السيني لعلامة التعليق في إحداثيات الصفحة. |
| [getY()](#getY--) | الإحداثي الصادي لعلامة التعليق في إحداثيات الصفحة. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getDel()](../../com.aspose.diagram/annotation\#getDel--) |
| [setIX(int value)](#setIX-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getIX()](../../com.aspose.diagram/annotation\#getIX--) |
| [setShapeID(int value)](#setShapeID-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getShapeID()](../../com.aspose.diagram/annotation\#getShapeID--) |
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
### getComment() {#getComment--}
```
public Str2Value getComment()
```


يحتوي على نص التعليق بصيغة سلسلة لشكل.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getDate() {#getDate--}
```
public DateValue getDate()
```


يحدد متى تم إنشاء التعليق

**Returns:**
[DateValue](../../com.aspose.diagram/datevalue)
### getDel() {#getDel--}
```
public int getDel()
```


علامة تشير إلى ما إذا كان العنصر قد تم حذفه محليًا. القيمة 1 تشير إلى أن العنصر تم حذفه محليًا.

**Returns:**
int
### getEditDate() {#getEditDate--}
```
public DateValue getEditDate()
```


يحدد متى تم تعديل التعليق آخر مرة

**Returns:**
[DateValue](../../com.aspose.diagram/datevalue)
### getIX() {#getIX--}
```
public int getIX()
```


فهرس العنصر داخل العنصر الأصل بدءًا من الصفر.

**Returns:**
int
### getLangID() {#getLangID--}
```
public IntValue getLangID()
```


يشير إلى معرف اللغة (LCID) للغة التي تم إدخال صيغة الخلية أو النص أو الخاصية المخصصة أو التعليق بها.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getMarkerIndex() {#getMarkerIndex--}
```
public IntValue getMarkerIndex()
```


يحدد رقم الفهرس المخصص لعلامة التعليق.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getReviewerID() {#getReviewerID--}
```
public IntValue getReviewerID()
```


يحتوي على رقم المعرف للمراجع الذي يضيف العلامات إلى المستند.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getShapeID() {#getShapeID--}
```
public int getShapeID()
```


معرف الشكل للتعليق.

**Returns:**
int
### getX() {#getX--}
```
public DoubleValue getX()
```


الإحداثي السيني لعلامة التعليق في إحداثيات الصفحة.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getY() {#getY--}
```
public DoubleValue getY()
```


الإحداثي الصادي لعلامة التعليق في إحداثيات الصفحة.

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


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getDel()](../../com.aspose.diagram/annotation\#getDel--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getIX()](../../com.aspose.diagram/annotation\#getIX--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setShapeID(int value) {#setShapeID-int-}
```
public void setShapeID(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getShapeID()](../../com.aspose.diagram/annotation\#getShapeID--)

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

