---
title: Geom
second_title: Aspose.Diagram لـ Java API Reference
description: يحتوي على عناصر تحدد إحداثيات رؤوس الخطوط والأقواس التي تُكوّن الشكل.
type: docs
weight: 169
url: /ar/java/com.aspose.diagram/geom/
---

**Inheritance:**
java.lang.Object
```
public class Geom
```

يحتوي على عناصر تحدد إحداثيات رؤوس الخطوط والأقواس التي تُكوّن الشكل. إذا كان الشكل يحتوي على أكثر من مسار، فهناك عنصر Geom لكل مسار.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Geom()](#Geom--) | منشئ. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [deepClone()](#deepClone--) | ينشئ نسخة عميقة من هذه المثيلة. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCoordinateCol()](#getCoordinateCol--) | مجموعة من الإحداثيات. |
| [getDel()](#getDel--) | علامة تشير إلى ما إذا تم حذف العنصر محليًا. |
| [getIX()](#getIX--) | فهرس العنصر داخل العنصر الأصل بدءًا من الصفر. |
| [getNextCoordinateIX()](#getNextCoordinateIX--) | يرجع قيمة IX لعضو مجموعة إحداثيات الشكل التالي. |
| [getNoFill()](#getNoFill--) | يحدد ما إذا كان يمكن ملء المسار. |
| [getNoLine()](#getNoLine--) | يحدد ما إذا كان يتم رسم خط حول حدود المسار. |
| [getNoQuickDrag()](#getNoQuickDrag--) | يحدد ما إذا كان يمكن اختيار الشكل أو سحبه عندما ينقر المستخدم على المنطقة المملوءة المحددة في قسم Geometry. |
| [getNoShow()](#getNoShow--) | يحدد ما إذا كان يتم عرض المسار على صفحة الرسم. |
| [getNoSnap()](#getNoSnap--) | يحدد ما إذا كانت الأشكال الأخرى تنجذب إلى المسار. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getDel()](../../com.aspose.diagram/geom\#getDel--) |
| [setIX(int value)](#setIX-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getIX()](../../com.aspose.diagram/geom\#getIX--) |
| [setNoFill(BoolValue value)](#setNoFill-com.aspose.diagram.BoolValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getNoFill()](../../com.aspose.diagram/geom\#getNoFill--) |
| [setNoLine(BoolValue value)](#setNoLine-com.aspose.diagram.BoolValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getNoLine()](../../com.aspose.diagram/geom\#getNoLine--) |
| [setNoQuickDrag(BoolValue value)](#setNoQuickDrag-com.aspose.diagram.BoolValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getNoQuickDrag()](../../com.aspose.diagram/geom\#getNoQuickDrag--) |
| [setNoShow(BoolValue value)](#setNoShow-com.aspose.diagram.BoolValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getNoShow()](../../com.aspose.diagram/geom\#getNoShow--) |
| [setNoSnap(BoolValue value)](#setNoSnap-com.aspose.diagram.BoolValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getNoSnap()](../../com.aspose.diagram/geom\#getNoSnap--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Geom() {#Geom--}
```
public Geom()
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCoordinateCol() {#getCoordinateCol--}
```
public CoordinateCollection getCoordinateCol()
```


مجموعة من الإحداثيات. تُظهر تسلسل الإحداثيات.

**Returns:**
[CoordinateCollection](../../com.aspose.diagram/coordinatecollection)
### getDel() {#getDel--}
```
public int getDel()
```


علامة تشير إلى ما إذا كان العنصر قد تم حذفه محليًا. القيمة 1 تشير إلى أن العنصر تم حذفه محليًا.

**Returns:**
int
### getIX() {#getIX--}
```
public int getIX()
```


فهرس العنصر داخل العنصر الأصل بدءًا من الصفر.

**Returns:**
int
### getNextCoordinateIX() {#getNextCoordinateIX--}
```
public int getNextCoordinateIX()
```


يرجع قيمة IX لعضو مجموعة إحداثيات الشكل التالي.

**Returns:**
int
### getNoFill() {#getNoFill--}
```
public BoolValue getNoFill()
```


يحدد ما إذا كان يمكن ملء المسار.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoLine() {#getNoLine--}
```
public BoolValue getNoLine()
```


يحدد ما إذا كان يتم رسم خط حول حدود المسار.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoQuickDrag() {#getNoQuickDrag--}
```
public BoolValue getNoQuickDrag()
```


يحدد ما إذا كان يمكن اختيار الشكل أو سحبه عندما ينقر المستخدم على المنطقة المملوءة المحددة في قسم Geometry.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoShow() {#getNoShow--}
```
public BoolValue getNoShow()
```


يحدد ما إذا كان يتم عرض المسار على صفحة الرسم.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoSnap() {#getNoSnap--}
```
public BoolValue getNoSnap()
```


يحدد ما إذا كانت الأشكال الأخرى تنجذب إلى المسار.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getDel()](../../com.aspose.diagram/geom\#getDel--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getIX()](../../com.aspose.diagram/geom\#getIX--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setNoFill(BoolValue value) {#setNoFill-com.aspose.diagram.BoolValue-}
```
public void setNoFill(BoolValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getNoFill()](../../com.aspose.diagram/geom\#getNoFill--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setNoLine(BoolValue value) {#setNoLine-com.aspose.diagram.BoolValue-}
```
public void setNoLine(BoolValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getNoLine()](../../com.aspose.diagram/geom\#getNoLine--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setNoQuickDrag(BoolValue value) {#setNoQuickDrag-com.aspose.diagram.BoolValue-}
```
public void setNoQuickDrag(BoolValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getNoQuickDrag()](../../com.aspose.diagram/geom\#getNoQuickDrag--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setNoShow(BoolValue value) {#setNoShow-com.aspose.diagram.BoolValue-}
```
public void setNoShow(BoolValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getNoShow()](../../com.aspose.diagram/geom\#getNoShow--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setNoSnap(BoolValue value) {#setNoSnap-com.aspose.diagram.BoolValue-}
```
public void setNoSnap(BoolValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getNoSnap()](../../com.aspose.diagram/geom\#getNoSnap--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

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

