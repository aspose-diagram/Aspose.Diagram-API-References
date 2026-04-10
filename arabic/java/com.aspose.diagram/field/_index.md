---
title: حقل
second_title: Aspose.Diagram لـ Java API Reference
description: يحتوي على عناصر تحدد الدوال والصيغ المدخلة في نص الأشكال.
type: docs
weight: 147
url: /ar/java/com.aspose.diagram/field/
---

**Inheritance:**
java.lang.Object
```
public class Field
```

يحتوي على عناصر تحدد الدوال والصيغ المدخلة في نص الشكل.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Field()](#Field--) | منشئ. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [deepClone()](#deepClone--) | ينشئ نسخة عميقة من هذه المثيلة. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCalendar()](#getCalendar--) | يحدد التقويم المستخدم للخصائص المخصصة، وحقول النص، وصيغ العناصر. |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | علامة تشير إلى ما إذا تم حذف العنصر محليًا. |
| [getDisplayValue()](#getDisplayValue--) | يحصل على القيمة النصية المنسقة لهذا الحقل. |
| [getEditMode()](#getEditMode--) | محجوز للاستخدام المستقبلي. |
| [getFormat()](#getFormat--) | عنصر Format يحدد التنسيق لحقل نصي يكون سلسلة أو رقم أو تاريخ أو وقت أو مدة أو عملة. |
| [getIX()](#getIX--) | فهرس العنصر داخل العنصر الأصل بدءًا من الصفر. |
| [getObjectKind()](#getObjectKind--) | يشير إلى نوع حقل النص. |
| [getType()](#getType--) | النوع يحدد نوع البيانات لقيمة حقل النص. |
| [getUICat()](#getUICat--) | يحدد فئة الحقل المدخل في إصدارات Microsoft Visio التي تسبق Visio 2000. |
| [getUICod()](#getUICod--) | يحدد رمز الحقل المدخل في إصدارات Microsoft Visio التي تسبق Visio 2000. |
| [getUIFmt()](#getUIFmt--) | يحدد تنسيق الحقل المدخل في إصدارات Microsoft Visio التي تسبق Visio 2000. |
| [getValue()](#getValue--) | يحتوي على القيمة لحقل نصي. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getDel()](../../com.aspose.diagram/field\#getDel--) |
| [setIX(int value)](#setIX-int-) | لوصف هذه الخاصية، يرجى الاطلاع على [getIX()](../../com.aspose.diagram/field\#getIX--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Field() {#Field--}
```
public Field()
```


منشئ.

### deepClone() {#deepClone--}
```
public Object deepClone()
```


ينشئ نسخة عميقة من هذه المثيلة.

**Returns:**
java.lang.Object -
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
### getCalendar() {#getCalendar--}
```
public Calendar getCalendar()
```


يحدد التقويم المستخدم للخصائص المخصصة، وحقول النص، وصيغ العناصر.

**Returns:**
[Calendar](../../com.aspose.diagram/calendar)
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
### getDisplayValue() {#getDisplayValue--}
```
public String getDisplayValue()
```


يحصل على القيمة النصية المنسقة لهذا الحقل.

**Returns:**
java.lang.String
### getEditMode() {#getEditMode--}
```
public DoubleValue getEditMode()
```


محجوز للاستخدام المستقبلي.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getFormat() {#getFormat--}
```
public Value getFormat()
```


عنصر Format يحدد التنسيق لحقل نصي يكون سلسلة، رقم، تاريخ أو وقت، مدة، أو عملة. يتم تحديد نوع حقل النص في عنصر Type المقابل.

**Returns:**
[Value](../../com.aspose.diagram/value)
### getIX() {#getIX--}
```
public int getIX()
```


فهرس العنصر داخل العنصر الأصل بدءًا من الصفر.

**Returns:**
int
### getObjectKind() {#getObjectKind--}
```
public ObjectKind getObjectKind()
```


يشير إلى نوع حقل النص.

**Returns:**
[ObjectKind](../../com.aspose.diagram/objectkind)
### getType() {#getType--}
```
public TypeField getType()
```


النوع يحدد نوع البيانات لقيمة حقل النص.

**Returns:**
[TypeField](../../com.aspose.diagram/typefield)
### getUICat() {#getUICat--}
```
public DoubleValue getUICat()
```


يحدد فئة الحقل المدخل في إصدارات Microsoft Visio التي تسبق Visio 2000.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getUICod() {#getUICod--}
```
public DoubleValue getUICod()
```


يحدد رمز الحقل المدخل في إصدارات Microsoft Visio التي تسبق Visio 2000.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getUIFmt() {#getUIFmt--}
```
public DoubleValue getUIFmt()
```


يحدد تنسيق الحقل المدخل في إصدارات Microsoft Visio التي تسبق Visio 2000.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getValue() {#getValue--}
```
public Value getValue()
```


يحتوي على القيمة لحقل نصي.

**Returns:**
[Value](../../com.aspose.diagram/value)
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


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getDel()](../../com.aspose.diagram/field\#getDel--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getIX()](../../com.aspose.diagram/field\#getIX--)

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

