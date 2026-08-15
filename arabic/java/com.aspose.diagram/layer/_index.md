---
title: Layer
second_title: Aspose.Diagram لـ Java API Reference
description: يحتوي على عناصر تُعرّف طبقة واحدة وخصائصها لصفحة.
type: docs
weight: 212
url: /ar/java/com.aspose.diagram/layer/
---

**Inheritance:**
java.lang.Object
```
public class Layer
```

يحتوي على عناصر تُعرّف طبقة واحدة وخصائصها لصفحة.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Layer()](#Layer--) | منشئ. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActive()](#getActive--) | يحدد ما إذا كانت الطبقة نشطة. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | فهرس اللون في جدول الألوان المستخدم لـ فهرس اللون في جدول الألوان المستخدم لعرض الطبقة أو قيمة RGB تحدد لونًا مخصصًا غير موجود في جدول الألوان (على سبيل المثال، \#ff9900). عرض الطبقة |
| [getColorTrans()](#getColorTrans--) | يحدد درجة الشفافية للون نص طبقة أو شكل، من 0 (معتم تمامًا) إلى 1 (شفاف تمامًا). |
| [getDel()](#getDel--) | علامة تشير إلى ما إذا تم حذف العنصر محليًا. |
| [getGlue()](#getGlue--) | يحدد ما إذا كان يمكن لصق الأشكال التابعة للطبقة. |
| [getIX()](#getIX--) | فهرس العنصر داخل العنصر الأصل بدءًا من الصفر. |
| [getLock()](#getLock--) | يحدد ما إذا كانت الأشكال التابعة للطبقة مقفلة من الاختيار أو التحرير. |
| [getName()](#getName--) | العنصر Name يحدد اسم الطبقة. |
| [getNameUniv()](#getNameUniv--) | يحدد الاسم العام للطبقة. |
| [getPrint()](#getPrint--) | يحدد ما إذا كانت الأشكال التابعة للطبقة تُطبع عندما يتم طباعة الرسم. |
| [getSnap()](#getSnap--) | يحدد ما إذا كان يمكن للأشكال الأخرى الالتقاط إلى الأشكال المعينة للطبقة. |
| [getStatus()](#getStatus--) | يحدد ما إذا كانت الطبقة طبقة صالحة للمستند. |
| [getVisible()](#getVisible--) | يحدد ما إذا كانت الأشكال التابعة للطبقة مرئية على صفحة الرسم. |
| [hashCode()](#hashCode--) |  |
| [isColorChecked()](#isColorChecked--) | علامة تشير إلى ما إذا كان العنصر قد تم فحصه محليًا. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setColorChecked(int value)](#setColorChecked-int-) | للتعرف على وصف هذه الخاصية، يرجى الاطلاع على [isColorChecked()](../../com.aspose.diagram/layer\#isColorChecked--) |
| [setDel(int value)](#setDel-int-) | للتعرف على وصف هذه الخاصية، يرجى الاطلاع على [getDel()](../../com.aspose.diagram/layer\#getDel--) |
| [setIX(int value)](#setIX-int-) | للتعرف على وصف هذه الخاصية، يرجى الاطلاع على [getIX()](../../com.aspose.diagram/layer\#getIX--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Layer() {#Layer--}
```
public Layer()
```


منشئ.

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
### getActive() {#getActive--}
```
public BoolValue getActive()
```


يحدد ما إذا كانت الطبقة نشطة. تُعيّن الأشكال التي لم تُحدد مسبقًا إلى طبقات إلى الطبقة (الطبقات) النشطة عند إسقاطها على صفحة الرسم.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public ColorValue getColor()
```


فهرس اللون في جدول الألوان المستخدم لـ فهرس اللون في جدول الألوان المستخدم لعرض الطبقة أو قيمة RGB تحدد لونًا مخصصًا غير موجود في جدول الألوان (على سبيل المثال، \#ff9900). عرض الطبقة

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getColorTrans() {#getColorTrans--}
```
public DoubleValue getColorTrans()
```


يحدد درجة الشفافية للون نص طبقة أو شكل، من 0 (معتم تمامًا) إلى 1 (شفاف تمامًا).

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDel() {#getDel--}
```
public int getDel()
```


علامة تشير إلى ما إذا كان العنصر قد تم حذفه محليًا. القيمة 1 تشير إلى أن العنصر تم حذفه محليًا.

**Returns:**
int
### getGlue() {#getGlue--}
```
public BoolValue getGlue()
```


يحدد ما إذا كان يمكن لصق الأشكال التابعة للطبقة.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getIX() {#getIX--}
```
public int getIX()
```


فهرس العنصر داخل العنصر الأصل بدءًا من الصفر.

**Returns:**
int
### getLock() {#getLock--}
```
public BoolValue getLock()
```


يحدد ما إذا كانت الأشكال التابعة للطبقة مقفلة من الاختيار أو التحرير.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getName() {#getName--}
```
public Str2Value getName()
```


العنصر Name يحدد اسم الطبقة.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getNameUniv() {#getNameUniv--}
```
public Str2Value getNameUniv()
```


يحدد الاسم العام للطبقة.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getPrint() {#getPrint--}
```
public BoolValue getPrint()
```


يحدد ما إذا كانت الأشكال التابعة للطبقة تُطبع عندما يتم طباعة الرسم.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getSnap() {#getSnap--}
```
public BoolValue getSnap()
```


يحدد ما إذا كان يمكن للأشكال الأخرى الالتقاط إلى الأشكال المعينة للطبقة. يمكن للأشكال المعينة للطبقة الالتقاط إلى أشكال أخرى، لكن الأشكال الأخرى لا يمكنها الالتقاط إليها.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getStatus() {#getStatus--}
```
public BoolValue getStatus()
```


يحدد ما إذا كانت الطبقة طبقة صالحة للمستند.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getVisible() {#getVisible--}
```
public BoolValue getVisible()
```


يحدد ما إذا كانت الأشكال التابعة للطبقة مرئية على صفحة الرسم.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isColorChecked() {#isColorChecked--}
```
public int isColorChecked()
```


علامة تشير إلى ما إذا كان العنصر قد تم فحصه محليًا. القيمة 1 تشير إلى أن العنصر تم فحصه محليًا.

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




### setColorChecked(int value) {#setColorChecked-int-}
```
public void setColorChecked(int value)
```


للتعرف على وصف هذه الخاصية، يرجى الاطلاع على [isColorChecked()](../../com.aspose.diagram/layer\#isColorChecked--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


للتعرف على وصف هذه الخاصية، يرجى الاطلاع على [getDel()](../../com.aspose.diagram/layer\#getDel--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


للتعرف على وصف هذه الخاصية، يرجى الاطلاع على [getIX()](../../com.aspose.diagram/layer\#getIX--)

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

