---
title: تخطيط
second_title: Aspose.Diagram لـ Java API Reference
description: يحتوي على عناصر تتحكم في وضع الشكل وإعدادات توجيه الموصلات.
type: docs
weight: 215
url: /ar/java/com.aspose.diagram/layout/
---

**Inheritance:**
java.lang.Object
```
public class Layout
```

يحتوي على عناصر تتحكم في وضع الشكل وإعدادات توجيه الموصلات.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getConFixedCode()](#getConFixedCode--) | يحدد متى يعيد الموصل توجيه نفسه. |
| [getConLineJumpCode()](#getConLineJumpCode--) | يحدد ما إذا كان الموصل يقفز عندما يتقاطع موصلان، |
| [getConLineJumpDirX()](#getConLineJumpDirX--) | يحدد اتجاه القفزة الخطية للقفزات الخطية التي تحدث على مقطع أفقي من موصل ديناميكي. |
| [getConLineJumpDirY()](#getConLineJumpDirY--) | يحدد اتجاه القفزة الخطية للقفزات الخطية التي تحدث على مقطع عمودي من موصل ديناميكي. |
| [getConLineJumpStyle()](#getConLineJumpStyle--) | يحدد نمط القفزة الخطية للقفزات الخطية على موصل ديناميكي. |
| [getConLineRouteExt()](#getConLineRouteExt--) | يحدد مظهر الموصل. |
| [getDel()](#getDel--) | علامة تشير إلى ما إذا تم حذف العنصر محليًا. |
| [getDisplayLevel()](#getDisplayLevel--) | يحدد نطاق مستوى العرض (النطاق النسبي لتجميع ترتيب Z) للشكل. |
| [getRelationships()](#getRelationships--) | يخزن العلاقات بين الحاويات والقوائم والتعليقات التوضيحية والأشكال. |
| [getShapeFixedCode()](#getShapeFixedCode--) | يحدد سلوك وضع الشكل القابل للموضع. |
| [getShapePermeablePlace()](#getShapePermeablePlace--) | يحدد ما إذا كان يمكن وضع الأشكال القابلة للموضع فوق شكل عندما يختار المستخدم خيار ترتيب الأشكال (قائمة الأشكال). |
| [getShapePermeableX()](#getShapePermeableX--) | يحدد ما إذا كان يمكن للموصل المرور أفقياً عبر الشكل. |
| [getShapePermeableY()](#getShapePermeableY--) | يحدد ما إذا كان يمكن للموصل المرور عمودياً عبر الشكل. |
| [getShapePlaceFlip()](#getShapePlaceFlip--) | يحدد كيفية انعكاس الشكل القابل للموضع و/أو تدويره على الصفحة عندما يختار المستخدم Lay Out Shapes (قائمة Shapes). |
| [getShapePlaceStyle()](#getShapePlaceStyle--) | يحدد نمط وضع العناصر الفرعية. |
| [getShapePlowCode()](#getShapePlowCode--) | يحدد ما إذا كان الشكل القابل للموضع يتحرك بعيدًا عندما تقوم بسحب شكل قابل للموضع آخر بالقرب من الشكل على صفحة الرسم. |
| [getShapeRouteStyle()](#getShapeRouteStyle--) | يحدد نمط التوجيه والاتجاه للموصل على صفحة الرسم. |
| [getShapeSplit()](#getShapeSplit--) | يحدد ما إذا كان هذا الشكل يمكنه تقسيم الأشكال القابلة للتقسيم. |
| [getShapeSplittable()](#getShapeSplittable--) | يحدد ما إذا كان يمكن تقسيم هذا الشكل أحادي البعد. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getDel()](../../com.aspose.diagram/layout\#getDel--) |
| [setShapePlaceStyle(ShapePlaceStyle value)](#setShapePlaceStyle-com.aspose.diagram.ShapePlaceStyle-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getShapePlaceStyle()](../../com.aspose.diagram/layout\#getShapePlaceStyle--) |
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
### getConFixedCode() {#getConFixedCode--}
```
public ConFixedCode getConFixedCode()
```


يحدد متى يعيد الموصل توجيه نفسه.

**Returns:**
[ConFixedCode](../../com.aspose.diagram/confixedcode)
### getConLineJumpCode() {#getConLineJumpCode--}
```
public ConLineJumpCode getConLineJumpCode()
```


يحدد ما إذا كان الموصل يقفز عندما يتقاطع موصلان،

**Returns:**
[ConLineJumpCode](../../com.aspose.diagram/conlinejumpcode)
### getConLineJumpDirX() {#getConLineJumpDirX--}
```
public ConLineJumpDirX getConLineJumpDirX()
```


يحدد اتجاه القفزة الخطية للقفزات الخطية التي تحدث على مقطع أفقي من موصل ديناميكي.

**Returns:**
[ConLineJumpDirX](../../com.aspose.diagram/conlinejumpdirx)
### getConLineJumpDirY() {#getConLineJumpDirY--}
```
public ConLineJumpDirY getConLineJumpDirY()
```


يحدد اتجاه القفزة الخطية للقفزات الخطية التي تحدث على مقطع عمودي من موصل ديناميكي.

**Returns:**
[ConLineJumpDirY](../../com.aspose.diagram/conlinejumpdiry)
### getConLineJumpStyle() {#getConLineJumpStyle--}
```
public ConLineJumpStyle getConLineJumpStyle()
```


يحدد نمط القفزة الخطية للقفزات الخطية على موصل ديناميكي.

**Returns:**
[ConLineJumpStyle](../../com.aspose.diagram/conlinejumpstyle)
### getConLineRouteExt() {#getConLineRouteExt--}
```
public ConLineRouteExt getConLineRouteExt()
```


يحدد مظهر الموصل.

**Returns:**
[ConLineRouteExt](../../com.aspose.diagram/conlinerouteext)
### getDel() {#getDel--}
```
public int getDel()
```


علامة تشير إلى ما إذا كان العنصر قد تم حذفه محليًا. القيمة 1 تشير إلى أن العنصر تم حذفه محليًا.

**Returns:**
int
### getDisplayLevel() {#getDisplayLevel--}
```
public IntValue getDisplayLevel()
```


يحدد نطاق مستوى العرض (النطاق النسبي لتجميع ترتيب Z) للشكل.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getRelationships() {#getRelationships--}
```
public BoolValue getRelationships()
```


يخزن العلاقات بين الحاويات والقوائم والتعليقات التوضيحية والأشكال.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapeFixedCode() {#getShapeFixedCode--}
```
public ShapeFixedCode getShapeFixedCode()
```


يحدد سلوك وضع الشكل القابل للموضع.

**Returns:**
[ShapeFixedCode](../../com.aspose.diagram/shapefixedcode)
### getShapePermeablePlace() {#getShapePermeablePlace--}
```
public BoolValue getShapePermeablePlace()
```


يحدد ما إذا كان يمكن وضع الأشكال القابلة للموضع فوق شكل عندما يختار المستخدم خيار ترتيب الأشكال (قائمة الأشكال).

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapePermeableX() {#getShapePermeableX--}
```
public BoolValue getShapePermeableX()
```


يحدد ما إذا كان يمكن للموصل المرور أفقياً عبر الشكل.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapePermeableY() {#getShapePermeableY--}
```
public BoolValue getShapePermeableY()
```


يحدد ما إذا كان يمكن للموصل المرور عمودياً عبر الشكل.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapePlaceFlip() {#getShapePlaceFlip--}
```
public ShapePlaceFlip getShapePlaceFlip()
```


يحدد كيفية انعكاس الشكل القابل للموضع و/أو تدويره على الصفحة عندما يختار المستخدم Lay Out Shapes (قائمة Shapes).

**Returns:**
[ShapePlaceFlip](../../com.aspose.diagram/shapeplaceflip)
### getShapePlaceStyle() {#getShapePlaceStyle--}
```
public ShapePlaceStyle getShapePlaceStyle()
```


يحدد نمط وضع العناصر الفرعية.

**Returns:**
[ShapePlaceStyle](../../com.aspose.diagram/shapeplacestyle)
### getShapePlowCode() {#getShapePlowCode--}
```
public ShapePlowCode getShapePlowCode()
```


يحدد ما إذا كان الشكل القابل للموضع يتحرك بعيدًا عندما تقوم بسحب شكل قابل للموضع آخر بالقرب من الشكل على صفحة الرسم.

**Returns:**
[ShapePlowCode](../../com.aspose.diagram/shapeplowcode)
### getShapeRouteStyle() {#getShapeRouteStyle--}
```
public ShapeRouteStyle getShapeRouteStyle()
```


يحدد نمط التوجيه والاتجاه للموصل على صفحة الرسم.

**Returns:**
[ShapeRouteStyle](../../com.aspose.diagram/shaperoutestyle)
### getShapeSplit() {#getShapeSplit--}
```
public BoolValue getShapeSplit()
```


يحدد ما إذا كان هذا الشكل يمكنه تقسيم الأشكال القابلة للتقسيم.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapeSplittable() {#getShapeSplittable--}
```
public BoolValue getShapeSplittable()
```


يحدد ما إذا كان يمكن تقسيم هذا الشكل أحادي البعد.

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


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getDel()](../../com.aspose.diagram/layout\#getDel--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setShapePlaceStyle(ShapePlaceStyle value) {#setShapePlaceStyle-com.aspose.diagram.ShapePlaceStyle-}
```
public void setShapePlaceStyle(ShapePlaceStyle value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getShapePlaceStyle()](../../com.aspose.diagram/layout\#getShapePlaceStyle--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ShapePlaceStyle](../../com.aspose.diagram/shapeplacestyle) |  |

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

