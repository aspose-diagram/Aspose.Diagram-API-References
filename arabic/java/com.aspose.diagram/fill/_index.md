---
title: ملء
second_title: Aspose.Diagram لـ Java API Reference
description: يحتوي على قيم تنسيق التعبئة الحالية للشكل وظل الشكل المتساقط بما في ذلك لون المقدمة للنمط ولون الخلفية.
type: docs
weight: 153
url: /ar/java/com.aspose.diagram/fill/
---

**Inheritance:**
java.lang.Object
```
public class Fill
```

يحتوي على قيم تنسيق التعبئة الحالية للشكل وظل الشكل المنسدل، بما في ذلك النمط، لون المقدمة، ولون الخلفية.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [deepClone()](#deepClone--) | ينشئ نسخة عميقة من هذه المثيلة. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | علامة تشير إلى ما إذا تم حذف العنصر محليًا. |
| [getFillBkgnd()](#getFillBkgnd--) | يحدد اللون المستخدم لخلفية نمط تعبئة الشكل. |
| [getFillBkgndTrans()](#getFillBkgndTrans--) | يحدد مستوى الشفافية للون الخلفية (التعبئة) لنمط تعبئة الشكل، من 0 (معتم تمامًا) إلى 1 (شفاف تمامًا). |
| [getFillForegnd()](#getFillForegnd--) | يحدد اللون المستخدم للمقدمة (الخط) لنمط تعبئة الشكل. |
| [getFillForegndTrans()](#getFillForegndTrans--) | يحدد مستوى الشفافية للون المقدمة (التعبئة) لنمط تعبئة الشكل، من 0 (معتم تمامًا) إلى 1 (شفاف تمامًا). |
| [getFillPattern()](#getFillPattern--) | يحدد نمط التعبئة للشكل. |
| [getGradientFill()](#getGradientFill--) | يحتوي على قيم تنسيق التعبئة المتدرجة الحالية للشكل |
| [getShapeShdwBlur()](#getShapeShdwBlur--) | يحدد حجم ضبابية الظل للشكل. |
| [getShapeShdwObliqueAngle()](#getShapeShdwObliqueAngle--) | يحدد زاوية الاتجاه المائل لظل الشكل. |
| [getShapeShdwOffsetX()](#getShapeShdwOffsetX--) | يحدد المسافة بوحدات الصفحة التي يُزاح فيها ظل الشكل أفقيًا عن الشكل. |
| [getShapeShdwOffsetY()](#getShapeShdwOffsetY--) | يحدد المسافة بوحدات الصفحة التي يُزاح فيها ظل الشكل عموديًا عن الشكل. |
| [getShapeShdwScaleFactor()](#getShapeShdwScaleFactor--) | يحدد النسبة المئوية التي يمكن من خلالها تكبير أو تصغير ظل الشكل. |
| [getShapeShdwShow()](#getShapeShdwShow--) | يحدد نوع الظل لشكل. |
| [getShapeShdwType()](#getShapeShdwType--) | يحدد نوع الظل لشكل. |
| [getShdwBkgnd()](#getShdwBkgnd--) | يحدد اللون المستخدم لخلفية (التعبئة) نمط تعبئة ظل الشكل المتساقط. |
| [getShdwBkgndTrans()](#getShdwBkgndTrans--) | يحدد مستوى الشفافية للخلفية (التعبئة) لنمط تعبئة ظل الشكل المتساقط، من 0.0 (معتم تمامًا) إلى 1.0 (شفاف تمامًا). |
| [getShdwForegnd()](#getShdwForegnd--) | يحدد اللون المستخدم للمقدمة (الخط) لنمط تعبئة ظل الشكل المتساقط. |
| [getShdwForegndTrans()](#getShdwForegndTrans--) | يحدد مستوى الشفافية للمقدمة (الخط) لنمط تعبئة ظل الشكل المتساقط، من 0.0 (معتم تمامًا) إلى 1.0 (شفاف تمامًا). |
| [getShdwPattern()](#getShdwPattern--) | يحدد نمط التعبئة لظل الشكل. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | لوصف هذه الخاصية، يرجى الاطلاع على [getDel()](../../com.aspose.diagram/fill\#getDel--) |
| [setFillBkgnd(ColorValue value)](#setFillBkgnd-com.aspose.diagram.ColorValue-) | لوصف هذه الخاصية، يرجى الاطلاع على [getFillBkgnd()](../../com.aspose.diagram/fill\#getFillBkgnd--) |
| [setFillBkgndTrans(DoubleValue value)](#setFillBkgndTrans-com.aspose.diagram.DoubleValue-) | لوصف هذه الخاصية، يرجى الاطلاع على [getFillBkgndTrans()](../../com.aspose.diagram/fill\#getFillBkgndTrans--) |
| [setFillForegnd(ColorValue value)](#setFillForegnd-com.aspose.diagram.ColorValue-) | لوصف هذه الخاصية، يرجى الاطلاع على [getFillForegnd()](../../com.aspose.diagram/fill\#getFillForegnd--) |
| [setFillForegndTrans(DoubleValue value)](#setFillForegndTrans-com.aspose.diagram.DoubleValue-) | لوصف هذه الخاصية، يرجى الاطلاع على [getFillForegndTrans()](../../com.aspose.diagram/fill\#getFillForegndTrans--) |
| [setFillPattern(IntValue value)](#setFillPattern-com.aspose.diagram.IntValue-) | لوصف هذه الخاصية، يرجى الاطلاع على [getFillPattern()](../../com.aspose.diagram/fill\#getFillPattern--) |
| [setShapeShdwBlur(DoubleValue value)](#setShapeShdwBlur-com.aspose.diagram.DoubleValue-) | لوصف هذه الخاصية، يرجى الاطلاع على [getShapeShdwBlur()](../../com.aspose.diagram/fill\#getShapeShdwBlur--) |
| [setShapeShdwObliqueAngle(DoubleValue value)](#setShapeShdwObliqueAngle-com.aspose.diagram.DoubleValue-) | لوصف هذه الخاصية، يرجى الاطلاع على [getShapeShdwObliqueAngle()](../../com.aspose.diagram/fill\#getShapeShdwObliqueAngle--) |
| [setShapeShdwOffsetX(DoubleValue value)](#setShapeShdwOffsetX-com.aspose.diagram.DoubleValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getShapeShdwOffsetX()](../../com.aspose.diagram/fill\#getShapeShdwOffsetX--) |
| [setShapeShdwOffsetY(DoubleValue value)](#setShapeShdwOffsetY-com.aspose.diagram.DoubleValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getShapeShdwOffsetY()](../../com.aspose.diagram/fill\#getShapeShdwOffsetY--) |
| [setShapeShdwScaleFactor(DoubleValue value)](#setShapeShdwScaleFactor-com.aspose.diagram.DoubleValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getShapeShdwScaleFactor()](../../com.aspose.diagram/fill\#getShapeShdwScaleFactor--) |
| [setShapeShdwShow(ShapeShdwShow value)](#setShapeShdwShow-com.aspose.diagram.ShapeShdwShow-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getShapeShdwShow()](../../com.aspose.diagram/fill\#getShapeShdwShow--) |
| [setShapeShdwType(ShapeShdwType value)](#setShapeShdwType-com.aspose.diagram.ShapeShdwType-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getShapeShdwType()](../../com.aspose.diagram/fill\#getShapeShdwType--) |
| [setShdwBkgnd(ColorValue value)](#setShdwBkgnd-com.aspose.diagram.ColorValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getShdwBkgnd()](../../com.aspose.diagram/fill\#getShdwBkgnd--) |
| [setShdwBkgndTrans(DoubleValue value)](#setShdwBkgndTrans-com.aspose.diagram.DoubleValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getShdwBkgndTrans()](../../com.aspose.diagram/fill\#getShdwBkgndTrans--) |
| [setShdwForegnd(ColorValue value)](#setShdwForegnd-com.aspose.diagram.ColorValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getShdwForegnd()](../../com.aspose.diagram/fill\#getShdwForegnd--) |
| [setShdwForegndTrans(DoubleValue value)](#setShdwForegndTrans-com.aspose.diagram.DoubleValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getShdwForegndTrans()](../../com.aspose.diagram/fill\#getShdwForegndTrans--) |
| [setShdwPattern(IntValue value)](#setShdwPattern-com.aspose.diagram.IntValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getShdwPattern()](../../com.aspose.diagram/fill\#getShdwPattern--) |
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
### getFillBkgnd() {#getFillBkgnd--}
```
public ColorValue getFillBkgnd()
```


يحدد اللون المستخدم لخلفية نمط تعبئة الشكل.

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getFillBkgndTrans() {#getFillBkgndTrans--}
```
public DoubleValue getFillBkgndTrans()
```


يحدد مستوى الشفافية للون الخلفية (التعبئة) لنمط تعبئة الشكل، من 0 (معتم تمامًا) إلى 1 (شفاف تمامًا).

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getFillForegnd() {#getFillForegnd--}
```
public ColorValue getFillForegnd()
```


يحدد اللون المستخدم للمقدمة (الخط) لنمط تعبئة الشكل.

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getFillForegndTrans() {#getFillForegndTrans--}
```
public DoubleValue getFillForegndTrans()
```


يحدد مستوى الشفافية للون المقدمة (التعبئة) لنمط تعبئة الشكل، من 0 (معتم تمامًا) إلى 1 (شفاف تمامًا).

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getFillPattern() {#getFillPattern--}
```
public IntValue getFillPattern()
```


يحدد نمط التعبئة للشكل.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getGradientFill() {#getGradientFill--}
```
public GradientFill getGradientFill()
```


يحتوي على قيم تنسيق التعبئة المتدرجة الحالية للشكل

**Returns:**
[GradientFill](../../com.aspose.diagram/gradientfill)
### getShapeShdwBlur() {#getShapeShdwBlur--}
```
public DoubleValue getShapeShdwBlur()
```


يحدد حجم تمويه الظل لشكل. لا يمكن رسم التمويه الآن، ولكن يمكن تحليله من ملف vsdx الآن.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShapeShdwObliqueAngle() {#getShapeShdwObliqueAngle--}
```
public DoubleValue getShapeShdwObliqueAngle()
```


يحدد زاوية الاتجاه المائل لظل الشكل.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShapeShdwOffsetX() {#getShapeShdwOffsetX--}
```
public DoubleValue getShapeShdwOffsetX()
```


يحدد المسافة بوحدات الصفحة التي يُزاح فيها ظل الشكل أفقيًا عن الشكل.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShapeShdwOffsetY() {#getShapeShdwOffsetY--}
```
public DoubleValue getShapeShdwOffsetY()
```


يحدد المسافة بوحدات الصفحة التي يُزاح فيها ظل الشكل عموديًا عن الشكل.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShapeShdwScaleFactor() {#getShapeShdwScaleFactor--}
```
public DoubleValue getShapeShdwScaleFactor()
```


يحدد النسبة المئوية التي يمكن من خلالها تكبير أو تصغير ظل الشكل.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShapeShdwShow() {#getShapeShdwShow--}
```
public ShapeShdwShow getShapeShdwShow()
```


يحدد نوع الظل لشكل.

**Returns:**
[ShapeShdwShow](../../com.aspose.diagram/shapeshdwshow)
### getShapeShdwType() {#getShapeShdwType--}
```
public ShapeShdwType getShapeShdwType()
```


يحدد نوع الظل لشكل.

**Returns:**
[ShapeShdwType](../../com.aspose.diagram/shapeshdwtype)
### getShdwBkgnd() {#getShdwBkgnd--}
```
public ColorValue getShdwBkgnd()
```


يحدد اللون المستخدم لخلفية (التعبئة) نمط تعبئة ظل الشكل المتساقط.

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getShdwBkgndTrans() {#getShdwBkgndTrans--}
```
public DoubleValue getShdwBkgndTrans()
```


يحدد مستوى الشفافية للخلفية (التعبئة) لنمط تعبئة ظل الشكل المتساقط، من 0.0 (معتم تمامًا) إلى 1.0 (شفاف تمامًا).

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwForegnd() {#getShdwForegnd--}
```
public ColorValue getShdwForegnd()
```


يحدد اللون المستخدم للمقدمة (الخط) لنمط تعبئة ظل الشكل المتساقط.

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getShdwForegndTrans() {#getShdwForegndTrans--}
```
public DoubleValue getShdwForegndTrans()
```


يحدد مستوى الشفافية للمقدمة (الخط) لنمط تعبئة ظل الشكل المتساقط، من 0.0 (معتم تمامًا) إلى 1.0 (شفاف تمامًا).

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwPattern() {#getShdwPattern--}
```
public IntValue getShdwPattern()
```


يحدد نمط التعبئة لظل الشكل.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
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


لوصف هذه الخاصية، يرجى الاطلاع على [getDel()](../../com.aspose.diagram/fill\#getDel--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setFillBkgnd(ColorValue value) {#setFillBkgnd-com.aspose.diagram.ColorValue-}
```
public void setFillBkgnd(ColorValue value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getFillBkgnd()](../../com.aspose.diagram/fill\#getFillBkgnd--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setFillBkgndTrans(DoubleValue value) {#setFillBkgndTrans-com.aspose.diagram.DoubleValue-}
```
public void setFillBkgndTrans(DoubleValue value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getFillBkgndTrans()](../../com.aspose.diagram/fill\#getFillBkgndTrans--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setFillForegnd(ColorValue value) {#setFillForegnd-com.aspose.diagram.ColorValue-}
```
public void setFillForegnd(ColorValue value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getFillForegnd()](../../com.aspose.diagram/fill\#getFillForegnd--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setFillForegndTrans(DoubleValue value) {#setFillForegndTrans-com.aspose.diagram.DoubleValue-}
```
public void setFillForegndTrans(DoubleValue value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getFillForegndTrans()](../../com.aspose.diagram/fill\#getFillForegndTrans--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setFillPattern(IntValue value) {#setFillPattern-com.aspose.diagram.IntValue-}
```
public void setFillPattern(IntValue value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getFillPattern()](../../com.aspose.diagram/fill\#getFillPattern--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setShapeShdwBlur(DoubleValue value) {#setShapeShdwBlur-com.aspose.diagram.DoubleValue-}
```
public void setShapeShdwBlur(DoubleValue value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getShapeShdwBlur()](../../com.aspose.diagram/fill\#getShapeShdwBlur--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShapeShdwObliqueAngle(DoubleValue value) {#setShapeShdwObliqueAngle-com.aspose.diagram.DoubleValue-}
```
public void setShapeShdwObliqueAngle(DoubleValue value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getShapeShdwObliqueAngle()](../../com.aspose.diagram/fill\#getShapeShdwObliqueAngle--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShapeShdwOffsetX(DoubleValue value) {#setShapeShdwOffsetX-com.aspose.diagram.DoubleValue-}
```
public void setShapeShdwOffsetX(DoubleValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getShapeShdwOffsetX()](../../com.aspose.diagram/fill\#getShapeShdwOffsetX--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShapeShdwOffsetY(DoubleValue value) {#setShapeShdwOffsetY-com.aspose.diagram.DoubleValue-}
```
public void setShapeShdwOffsetY(DoubleValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getShapeShdwOffsetY()](../../com.aspose.diagram/fill\#getShapeShdwOffsetY--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShapeShdwScaleFactor(DoubleValue value) {#setShapeShdwScaleFactor-com.aspose.diagram.DoubleValue-}
```
public void setShapeShdwScaleFactor(DoubleValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getShapeShdwScaleFactor()](../../com.aspose.diagram/fill\#getShapeShdwScaleFactor--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShapeShdwShow(ShapeShdwShow value) {#setShapeShdwShow-com.aspose.diagram.ShapeShdwShow-}
```
public void setShapeShdwShow(ShapeShdwShow value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getShapeShdwShow()](../../com.aspose.diagram/fill\#getShapeShdwShow--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ShapeShdwShow](../../com.aspose.diagram/shapeshdwshow) |  |

### setShapeShdwType(ShapeShdwType value) {#setShapeShdwType-com.aspose.diagram.ShapeShdwType-}
```
public void setShapeShdwType(ShapeShdwType value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getShapeShdwType()](../../com.aspose.diagram/fill\#getShapeShdwType--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ShapeShdwType](../../com.aspose.diagram/shapeshdwtype) |  |

### setShdwBkgnd(ColorValue value) {#setShdwBkgnd-com.aspose.diagram.ColorValue-}
```
public void setShdwBkgnd(ColorValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getShdwBkgnd()](../../com.aspose.diagram/fill\#getShdwBkgnd--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setShdwBkgndTrans(DoubleValue value) {#setShdwBkgndTrans-com.aspose.diagram.DoubleValue-}
```
public void setShdwBkgndTrans(DoubleValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getShdwBkgndTrans()](../../com.aspose.diagram/fill\#getShdwBkgndTrans--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShdwForegnd(ColorValue value) {#setShdwForegnd-com.aspose.diagram.ColorValue-}
```
public void setShdwForegnd(ColorValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getShdwForegnd()](../../com.aspose.diagram/fill\#getShdwForegnd--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setShdwForegndTrans(DoubleValue value) {#setShdwForegndTrans-com.aspose.diagram.DoubleValue-}
```
public void setShdwForegndTrans(DoubleValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getShdwForegndTrans()](../../com.aspose.diagram/fill\#getShdwForegndTrans--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShdwPattern(IntValue value) {#setShdwPattern-com.aspose.diagram.IntValue-}
```
public void setShdwPattern(IntValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getShdwPattern()](../../com.aspose.diagram/fill\#getShdwPattern--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

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

