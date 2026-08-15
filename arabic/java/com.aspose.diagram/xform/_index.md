---
title: XForm
second_title: Aspose.Diagram لـ Java API Reference
description: يحتوي على عناصر تتحكم في خصائص الخط لشكل مثل وزن النمط واللون.
type: docs
weight: 449
url: /ar/java/com.aspose.diagram/xform/
---

**Inheritance:**
java.lang.Object
```
public class XForm
```

يحتوي على عناصر تتحكم في خصائص الخط للشكل، مثل النمط والوزن واللون. تحدد هذه العناصر ما إذا كانت نهايات الخط مُنسقة (على سبيل المثال، بسهم)، حجم تنسيقات نهايات الخط، نصف قطر الدائرة المستديرة المطبقة على الخط، ونمط غطاء الخط (دائري أو مربع).
## الطرق

| طريقة | الوصف |
| --- | --- |
| [deepClone()](#deepClone--) | ينشئ نسخة عميقة من هذه المثيلة. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAngle()](#getAngle--) | يمثل الزاوية الحالية للدوران للشكل بالنسبة إلى العنصر الأصلي. |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | علامة تشير إلى ما إذا تم حذف العنصر محليًا. |
| [getFlipX()](#getFlipX--) | يشير إلى ما إذا تم عكس الشكل أفقيًا |
| [getFlipY()](#getFlipY--) | يشير إلى ما إذا تم عكس الشكل عموديًا. |
| [getHeight()](#getHeight--) | يحدد ارتفاع الشكل بوحدات الرسم. |
| [getLocPinX()](#getLocPinX--) | يحدد الإحداثي السيني لمشبك الشكل (مركز الدوران) بالنسبة لأصل الشكل. |
| [getLocPinY()](#getLocPinY--) | يحدد الإحداثي الصادي لمشبك الشكل (مركز الدوران) بالنسبة لأصل الشكل. |
| [getPinPos()](#getPinPos--) | يحدد موضع المشبك للشكل |
| [getPinX()](#getPinX--) | يحدد الإحداثي السيني لمشبك الشكل (مركز الدوران) بالنسبة لأصل العنصر الأصلي. |
| [getPinY()](#getPinY--) | يحدد الإحداثي الصادي لمشبك الشكل (مركز الدوران) بالنسبة لأصل العنصر الأصلي. |
| [getResizeMode()](#getResizeMode--) | يحدد إعداد سلوك تغيير الحجم الحالي للشكل عندما يكون داخل مجموعة. |
| [getWidth()](#getWidth--) | يحتوي على عرض الشكل المرتبط بوحدات الرسم. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAngle(DoubleValue value)](#setAngle-com.aspose.diagram.DoubleValue-) | لوصف هذه الخاصية، يرجى الاطلاع على [getAngle()](../../com.aspose.diagram/xform\#getAngle--) |
| [setDel(int value)](#setDel-int-) | لوصف هذه الخاصية، يرجى الاطلاع على [getDel()](../../com.aspose.diagram/xform\#getDel--) |
| [setFlipX(BoolValue value)](#setFlipX-com.aspose.diagram.BoolValue-) | لوصف هذه الخاصية، يرجى الاطلاع على [getFlipX()](../../com.aspose.diagram/xform\#getFlipX--) |
| [setFlipY(BoolValue value)](#setFlipY-com.aspose.diagram.BoolValue-) | لوصف هذه الخاصية، يرجى الاطلاع على [getFlipY()](../../com.aspose.diagram/xform\#getFlipY--) |
| [setHeight(DoubleValue value)](#setHeight-com.aspose.diagram.DoubleValue-) | لوصف هذه الخاصية، يرجى الاطلاع على [getHeight()](../../com.aspose.diagram/xform\#getHeight--) |
| [setLocPinX(DoubleValue value)](#setLocPinX-com.aspose.diagram.DoubleValue-) | لوصف هذه الخاصية، يرجى الاطلاع على [getLocPinX()](../../com.aspose.diagram/xform\#getLocPinX--) |
| [setLocPinY(DoubleValue value)](#setLocPinY-com.aspose.diagram.DoubleValue-) | لوصف هذه الخاصية، يرجى الاطلاع على [getLocPinY()](../../com.aspose.diagram/xform\#getLocPinY--) |
| [setPinPos(int value)](#setPinPos-int-) | لوصف هذه الخاصية، يرجى الاطلاع على [getPinPos()](../../com.aspose.diagram/xform\#getPinPos--) |
| [setPinX(DoubleValue value)](#setPinX-com.aspose.diagram.DoubleValue-) | لوصف هذه الخاصية، يرجى الاطلاع على [getPinX()](../../com.aspose.diagram/xform\#getPinX--) |
| [setPinY(DoubleValue value)](#setPinY-com.aspose.diagram.DoubleValue-) | لوصف هذه الخاصية، يرجى الاطلاع على [getPinY()](../../com.aspose.diagram/xform\#getPinY--) |
| [setResizeMode(ResizeMode value)](#setResizeMode-com.aspose.diagram.ResizeMode-) | لوصف هذه الخاصية، يرجى الاطلاع على [getResizeMode()](../../com.aspose.diagram/xform\#getResizeMode--) |
| [setWidth(DoubleValue value)](#setWidth-com.aspose.diagram.DoubleValue-) | لوصف هذه الخاصية، يرجى الاطلاع على [getWidth()](../../com.aspose.diagram/xform\#getWidth--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getAngle() {#getAngle--}
```
public DoubleValue getAngle()
```


يمثل الزاوية الحالية للدوران للشكل بالنسبة إلى العنصر الأصلي.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
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
### getFlipX() {#getFlipX--}
```
public BoolValue getFlipX()
```


يشير إلى ما إذا تم عكس الشكل أفقيًا

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getFlipY() {#getFlipY--}
```
public BoolValue getFlipY()
```


يشير إلى ما إذا تم عكس الشكل عموديًا.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getHeight() {#getHeight--}
```
public DoubleValue getHeight()
```


يحدد ارتفاع الشكل بوحدات الرسم.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLocPinX() {#getLocPinX--}
```
public DoubleValue getLocPinX()
```


يحدد الإحداثي السيني لمشبك الشكل (مركز الدوران) بالنسبة لأصل الشكل. الصيغة الافتراضية لتحديد LocPinX هي: F='Width\* 0.5'.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLocPinY() {#getLocPinY--}
```
public DoubleValue getLocPinY()
```


يحدد الإحداثي الصادي لمشبك الشكل (مركز الدوران) بالنسبة لأصل الشكل. الصيغة الافتراضية لتحديد LocPinY هي: F='Height \* 0.5'.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPinPos() {#getPinPos--}
```
public int getPinPos()
```


يحدد موضع المشبك للشكل

**Returns:**
int
### getPinX() {#getPinX--}
```
public DoubleValue getPinX()
```


يحدد الإحداثي السيني لمشبك الشكل (مركز الدوران) بالنسبة لأصل العنصر الأصلي.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPinY() {#getPinY--}
```
public DoubleValue getPinY()
```


يحدد الإحداثي الصادي لمشبك الشكل (مركز الدوران) بالنسبة لأصل العنصر الأصلي.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getResizeMode() {#getResizeMode--}
```
public ResizeMode getResizeMode()
```


يحدد إعداد سلوك تغيير الحجم الحالي للشكل عندما يكون داخل مجموعة.

**Returns:**
[ResizeMode](../../com.aspose.diagram/resizemode)
### getWidth() {#getWidth--}
```
public DoubleValue getWidth()
```


يحتوي على عرض الشكل المرتبط بوحدات الرسم.

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




### setAngle(DoubleValue value) {#setAngle-com.aspose.diagram.DoubleValue-}
```
public void setAngle(DoubleValue value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getAngle()](../../com.aspose.diagram/xform\#getAngle--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getDel()](../../com.aspose.diagram/xform\#getDel--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setFlipX(BoolValue value) {#setFlipX-com.aspose.diagram.BoolValue-}
```
public void setFlipX(BoolValue value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getFlipX()](../../com.aspose.diagram/xform\#getFlipX--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setFlipY(BoolValue value) {#setFlipY-com.aspose.diagram.BoolValue-}
```
public void setFlipY(BoolValue value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getFlipY()](../../com.aspose.diagram/xform\#getFlipY--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setHeight(DoubleValue value) {#setHeight-com.aspose.diagram.DoubleValue-}
```
public void setHeight(DoubleValue value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getHeight()](../../com.aspose.diagram/xform\#getHeight--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setLocPinX(DoubleValue value) {#setLocPinX-com.aspose.diagram.DoubleValue-}
```
public void setLocPinX(DoubleValue value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getLocPinX()](../../com.aspose.diagram/xform\#getLocPinX--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setLocPinY(DoubleValue value) {#setLocPinY-com.aspose.diagram.DoubleValue-}
```
public void setLocPinY(DoubleValue value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getLocPinY()](../../com.aspose.diagram/xform\#getLocPinY--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setPinPos(int value) {#setPinPos-int-}
```
public void setPinPos(int value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getPinPos()](../../com.aspose.diagram/xform\#getPinPos--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setPinX(DoubleValue value) {#setPinX-com.aspose.diagram.DoubleValue-}
```
public void setPinX(DoubleValue value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getPinX()](../../com.aspose.diagram/xform\#getPinX--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setPinY(DoubleValue value) {#setPinY-com.aspose.diagram.DoubleValue-}
```
public void setPinY(DoubleValue value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getPinY()](../../com.aspose.diagram/xform\#getPinY--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setResizeMode(ResizeMode value) {#setResizeMode-com.aspose.diagram.ResizeMode-}
```
public void setResizeMode(ResizeMode value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getResizeMode()](../../com.aspose.diagram/xform\#getResizeMode--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ResizeMode](../../com.aspose.diagram/resizemode) |  |

### setWidth(DoubleValue value) {#setWidth-com.aspose.diagram.DoubleValue-}
```
public void setWidth(DoubleValue value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getWidth()](../../com.aspose.diagram/xform\#getWidth--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

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

