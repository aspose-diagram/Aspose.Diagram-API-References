---
title: PageLayout
second_title: Aspose.Diagram لـ Java API Reference
description: يحتوي على خلايا تتحكم في إعدادات تخطيط الصفحة للأشكال والموصلات مثل التباعد بين جميع الأشكال على الصفحة، التباعد بين جميع الموصلات على الصفحة، ونمط التوجيه لجميع الموصلات على الصفحة.
type: docs
weight: 263
url: /ar/java/com.aspose.diagram/pagelayout/
---

**Inheritance:**
java.lang.Object
```
public class PageLayout
```

يحتوي على خلايا تتحكم في إعدادات تخطيط الصفحة للأشكال والموصلات، مثل المسافة بين جميع الأشكال على الصفحة، والمسافة بين جميع الموصلات على الصفحة، ونمط التوجيه لجميع الموصلات على الصفحة.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAvenueSizeX()](#getAvenueSizeX--) | يحدد مقدار المسافة العمودية بين الأشكال على صفحة الرسم عند استخدام Microsoft Visio لتخطيط الأشكال على صفحة الرسم. |
| [getAvenueSizeY()](#getAvenueSizeY--) | يحدد مقدار المسافة العمودية بين الأشكال على صفحة الرسم عند استخدام Microsoft Visio لتخطيط الأشكال على صفحة الرسم. |
| [getAvoidPageBreaks()](#getAvoidPageBreaks--) | يحدد كيفية وضع الأشكال على الصفحة عندما يتم ترتيب الأشكال عند اختيار المستخدم لأمر "Lay Out Shapes" (قائمة الشكل). |
| [getBlockSizeX()](#getBlockSizeX--) | يحدد حجم الكتلة العمودية، المنطقة التي يجب أن يتناسب فيها كل شكل من أشكالك على صفحة الرسم عند استخدام Microsoft Visio لتخطيط الأشكال على صفحة الرسم. |
| [getBlockSizeY()](#getBlockSizeY--) | يحدد مقدار المسافة الأفقية بين الأشكال على صفحة الرسم عند استخدام Microsoft Visio لتخطيط الأشكال على صفحة الرسم. |
| [getClass()](#getClass--) |  |
| [getCtrlAsInput()](#getCtrlAsInput--) | يحدد أي شكل هو الأصل عند استخدام الأشكال بواسطة مقابض التحكم. |
| [getDel()](#getDel--) | علامة تشير إلى ما إذا تم حذف العنصر محليًا. |
| [getDynamicsOff()](#getDynamicsOff--) | يحدد ما إذا كانت الأشكال القابلة للموضع تتحرك والموصلات تعيد توجيهها حول الأشكال والموصلات الأخرى على صفحة الرسم. |
| [getEnableGrid()](#getEnableGrid--) | يحدد ما إذا كان Microsoft Visio يضع الأشكال بناءً على شبكة صفحة داخلية عندما يختار المستخدم خيار تخطيط الأشكال (قائمة الشكل). |
| [getLineAdjustFrom()](#getLineAdjustFrom--) | يحدد أي الموصلات الديناميكية يجب إبعادها إذا كانت تتقاطع فوق بعضها البعض. |
| [getLineAdjustTo()](#getLineAdjustTo--) | يحدد أي الموصلات الديناميكية يجب ترتيبها فوق بعضها البعض إذا كانت تتقاطع فوق بعضها. |
| [getLineJumpCode()](#getLineJumpCode--) | يحدد نمط قفزة الخط لجميع الموصلات على صفحة الرسم التي لا تملك نمط قفزة خط محلي. |
| [getLineJumpFactorX()](#getLineJumpFactorX--) | يحدد حجم القفزات الخطية على القطاعات الأفقية للموصلات الديناميكية على الصفحة، كنسبة مئوية من قيمة عنصر LineToLineX (الذي يحدد الفاصل الأفقي بين جميع الموصلات على صفحة الرسم). |
| [getLineJumpFactorY()](#getLineJumpFactorY--) | يحدد حجم القفزات الخطية على القطاعات العمودية للموصلات الديناميكية على الصفحة، كنسبة مئوية من قيمة عنصر LineToLineY (الذي يحدد الفاصل العمودي بين جميع الموصلات على صفحة الرسم). |
| [getLineJumpStyle()](#getLineJumpStyle--) | يحدد اتجاه القفزات الخطية على المقاطع الأفقية للموصلات الديناميكية في صفحة الرسم التي لم تقم بتطبيق اتجاه قفزة محلي عليها. |
| [getLineRouteExt()](#getLineRouteExt--) | يحدد المظهر الافتراضي لجميع الموصلات على صفحة. |
| [getLineToLineX()](#getLineToLineX--) | يحدد الحد الأدنى للفاصل الأفقي بين الموصلات الديناميكية على صفحة الرسم. |
| [getLineToLineY()](#getLineToLineY--) | يحدد الحد الأدنى للفاصل العمودي بين الموصلات الديناميكية على صفحة الرسم. |
| [getLineToNodeX()](#getLineToNodeX--) | يحدد الحد الأدنى للفاصل العمودي بين الموصلات الديناميكية والأشكال على صفحة الرسم. |
| [getLineToNodeY()](#getLineToNodeY--) | يحدد حجم الكتلة الأفقية، المنطقة التي يجب أن يتناسب فيها كل شكل من أشكالك على صفحة الرسم عند استخدام Microsoft Visio لتخطيط الأشكال على صفحة الرسم. |
| [getPageLineJumpDirX()](#getPageLineJumpDirX--) | يحدد اتجاه القفزات الخطية على الموصلات الديناميكية العمودية في صفحة الرسم التي لم تقم بتطبيق اتجاه قفزة محلي عليها. |
| [getPageLineJumpDirY()](#getPageLineJumpDirY--) | يحدد الحد الأدنى للفاصل الأفقي بين الموصلات الديناميكية والأشكال على صفحة الرسم. |
| [getPageShapeSplit()](#getPageShapeSplit--) | يشير إلى ما إذا كان يمكن تقسيم الأشكال على الصفحة تلقائيًا. |
| [getPlaceDepth()](#getPlaceDepth--) | يحدد ما إذا كانت الأشكال القابلة للموضع تتحرك بعيدًا عندما يسحب المستخدم شكلًا قابلًا للموضع بالقرب من شكل قابل للموضع آخر على صفحة الرسم. |
| [getPlaceFlip()](#getPlaceFlip--) | يحدد كيفية انعكاس أو تدوير الأشكال القابلة للموضع على الصفحة عندما يتم ترتيب الأشكال باستخدام أمر "Lay Out Shapes" في Microsoft Visio. |
| [getPlaceStyle()](#getPlaceStyle--) | يحدد نمط التوجيه والاتجاه لجميع الموصلات الديناميكية على صفحة الرسم التي لا تملك نمط توجيه محلي. |
| [getPlowCode()](#getPlowCode--) | يحدد الموصلات الديناميكية التي تريد إضافة القفزات إليها. |
| [getResizePage()](#getResizePage--) | يحدد ما إذا كان يجب توسيع الصفحة لتضمين الرسم بعد أن يختار المستخدم خيار تخطيط الأشكال (قائمة الأشكال). |
| [getRouteStyle()](#getRouteStyle--) | بالنسبة للرسم الذي يتم ترتيبه تلقائيًا، يحدد الطريقة التي يُحلل بها الرسم قبل إنشاء التخطيط ويحدد نوع التخطيط. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getDel()](../../com.aspose.diagram/pagelayout\#getDel--) |
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
### getAvenueSizeX() {#getAvenueSizeX--}
```
public DoubleValue getAvenueSizeX()
```


يحدد مقدار المسافة العمودية بين الأشكال على صفحة الرسم عند استخدام Microsoft Visio لتخطيط الأشكال على صفحة الرسم.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getAvenueSizeY() {#getAvenueSizeY--}
```
public DoubleValue getAvenueSizeY()
```


يحدد مقدار المسافة العمودية بين الأشكال على صفحة الرسم عند استخدام Microsoft Visio لتخطيط الأشكال على صفحة الرسم.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getAvoidPageBreaks() {#getAvoidPageBreaks--}
```
public BoolValue getAvoidPageBreaks()
```


يحدد كيفية وضع الأشكال على الصفحة عندما يتم ترتيب الأشكال عند اختيار المستخدم لأمر "Lay Out Shapes" (قائمة الشكل).

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getBlockSizeX() {#getBlockSizeX--}
```
public DoubleValue getBlockSizeX()
```


يحدد حجم الكتلة العمودية، المنطقة التي يجب أن يتناسب فيها كل شكل من أشكالك على صفحة الرسم عند استخدام Microsoft Visio لتخطيط الأشكال على صفحة الرسم.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBlockSizeY() {#getBlockSizeY--}
```
public DoubleValue getBlockSizeY()
```


يحدد مقدار المسافة الأفقية بين الأشكال على صفحة الرسم عند استخدام Microsoft Visio لتخطيط الأشكال على صفحة الرسم.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCtrlAsInput() {#getCtrlAsInput--}
```
public BoolValue getCtrlAsInput()
```


يحدد أي شكل هو الأصل عند استخدام الأشكال بواسطة مقابض التحكم. يحدد هذا العنصر سلوك جميع الأشكال على صفحة الرسم.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getDel() {#getDel--}
```
public int getDel()
```


علامة تشير إلى ما إذا كان العنصر قد تم حذفه محليًا. القيمة 1 تشير إلى أن العنصر تم حذفه محليًا.

**Returns:**
int
### getDynamicsOff() {#getDynamicsOff--}
```
public BoolValue getDynamicsOff()
```


يحدد ما إذا كانت الأشكال القابلة للموضع تتحرك والموصلات تعيد توجيهها حول الأشكال والموصلات الأخرى على صفحة الرسم.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getEnableGrid() {#getEnableGrid--}
```
public BoolValue getEnableGrid()
```


يحدد ما إذا كان Microsoft Visio يضع الأشكال بناءً على شبكة صفحة داخلية عندما يختار المستخدم خيار تخطيط الأشكال (قائمة الشكل).

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLineAdjustFrom() {#getLineAdjustFrom--}
```
public LineAdjustFrom getLineAdjustFrom()
```


يحدد أي الموصلات الديناميكية يجب إبعادها إذا كانت تتقاطع فوق بعضها البعض.

**Returns:**
[LineAdjustFrom](../../com.aspose.diagram/lineadjustfrom)
### getLineAdjustTo() {#getLineAdjustTo--}
```
public LineAdjustTo getLineAdjustTo()
```


يحدد أي الموصلات الديناميكية يجب ترتيبها فوق بعضها البعض إذا كانت تتقاطع فوق بعضها.

**Returns:**
[LineAdjustTo](../../com.aspose.diagram/lineadjustto)
### getLineJumpCode() {#getLineJumpCode--}
```
public LineJumpCode getLineJumpCode()
```


يحدد نمط قفزة الخط لجميع الموصلات على صفحة الرسم التي لا تملك نمط قفزة خط محلي.

**Returns:**
[LineJumpCode](../../com.aspose.diagram/linejumpcode)
### getLineJumpFactorX() {#getLineJumpFactorX--}
```
public DoubleValue getLineJumpFactorX()
```


يحدد حجم القفزات الخطية على القطاعات الأفقية للموصلات الديناميكية على الصفحة، كنسبة مئوية من قيمة عنصر LineToLineX (الذي يحدد الفاصل الأفقي بين جميع الموصلات على صفحة الرسم). تتراوح قيمة هذا العنصر من 0 إلى 10.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineJumpFactorY() {#getLineJumpFactorY--}
```
public DoubleValue getLineJumpFactorY()
```


يحدد حجم القفزات الخطية على القطاعات العمودية للموصلات الديناميكية على الصفحة، كنسبة مئوية من قيمة عنصر LineToLineY (الذي يحدد الفاصل العمودي بين جميع الموصلات على صفحة الرسم). يمكن لهذا العنصر أن يحتوي على قيمة من 0 إلى 10.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineJumpStyle() {#getLineJumpStyle--}
```
public LineJumpStyle getLineJumpStyle()
```


يحدد اتجاه القفزات الخطية على المقاطع الأفقية للموصلات الديناميكية في صفحة الرسم التي لم تقم بتطبيق اتجاه قفزة محلي عليها.

**Returns:**
[LineJumpStyle](../../com.aspose.diagram/linejumpstyle)
### getLineRouteExt() {#getLineRouteExt--}
```
public LineRouteExt getLineRouteExt()
```


يحدد المظهر الافتراضي لجميع الموصلات على صفحة.

**Returns:**
[LineRouteExt](../../com.aspose.diagram/linerouteext)
### getLineToLineX() {#getLineToLineX--}
```
public DoubleValue getLineToLineX()
```


يحدد الحد الأدنى للفاصل الأفقي بين الموصلات الديناميكية على صفحة الرسم.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineToLineY() {#getLineToLineY--}
```
public DoubleValue getLineToLineY()
```


يحدد الحد الأدنى للفاصل العمودي بين الموصلات الديناميكية على صفحة الرسم.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineToNodeX() {#getLineToNodeX--}
```
public DoubleValue getLineToNodeX()
```


يحدد الحد الأدنى للفاصل العمودي بين الموصلات الديناميكية والأشكال على صفحة الرسم.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineToNodeY() {#getLineToNodeY--}
```
public DoubleValue getLineToNodeY()
```


يحدد حجم الكتلة الأفقية، المنطقة التي يجب أن يتناسب فيها كل شكل من أشكالك على صفحة الرسم عند استخدام Microsoft Visio لتخطيط الأشكال على صفحة الرسم.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPageLineJumpDirX() {#getPageLineJumpDirX--}
```
public PageLineJumpDirX getPageLineJumpDirX()
```


يحدد اتجاه القفزات الخطية على الموصلات الديناميكية العمودية في صفحة الرسم التي لم تقم بتطبيق اتجاه قفزة محلي عليها.

**Returns:**
[PageLineJumpDirX](../../com.aspose.diagram/pagelinejumpdirx)
### getPageLineJumpDirY() {#getPageLineJumpDirY--}
```
public PageLineJumpDirY getPageLineJumpDirY()
```


يحدد الحد الأدنى للفاصل الأفقي بين الموصلات الديناميكية والأشكال على صفحة الرسم.

**Returns:**
[PageLineJumpDirY](../../com.aspose.diagram/pagelinejumpdiry)
### getPageShapeSplit() {#getPageShapeSplit--}
```
public BoolValue getPageShapeSplit()
```


يشير إلى ما إذا كان يمكن تقسيم الأشكال على الصفحة تلقائيًا.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getPlaceDepth() {#getPlaceDepth--}
```
public PlaceDepth getPlaceDepth()
```


يحدد ما إذا كانت الأشكال القابلة للموضع تتحرك بعيدًا عندما يسحب المستخدم شكلًا قابلًا للموضع بالقرب من شكل قابل للموضع آخر على صفحة الرسم.

**Returns:**
[PlaceDepth](../../com.aspose.diagram/placedepth)
### getPlaceFlip() {#getPlaceFlip--}
```
public PlaceFlip getPlaceFlip()
```


يحدد كيفية انعكاس أو تدوير الأشكال القابلة للموضع على الصفحة عندما يتم ترتيب الأشكال باستخدام أمر Lay Out Shapes في Microsoft Visio. القيم الست عشرية التالية مسموح بها.

**Returns:**
[PlaceFlip](../../com.aspose.diagram/placeflip)
### getPlaceStyle() {#getPlaceStyle--}
```
public PlaceStyle getPlaceStyle()
```


يحدد نمط التوجيه والاتجاه لجميع الموصلات الديناميكية على صفحة الرسم التي لا تملك نمط توجيه محلي.

**Returns:**
[PlaceStyle](../../com.aspose.diagram/placestyle)
### getPlowCode() {#getPlowCode--}
```
public BoolValue getPlowCode()
```


يحدد الموصلات الديناميكية التي تريد إضافة القفزات إليها.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getResizePage() {#getResizePage--}
```
public BoolValue getResizePage()
```


يحدد ما إذا كان يجب توسيع الصفحة لتضمين الرسم بعد أن يختار المستخدم خيار تخطيط الأشكال (قائمة الأشكال).

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getRouteStyle() {#getRouteStyle--}
```
public RouteStyle getRouteStyle()
```


بالنسبة للرسم الذي يتم ترتيبه تلقائيًا، يحدد الطريقة التي يُحلل بها الرسم قبل إنشاء التخطيط ويحدد نوع التخطيط.

**Returns:**
[RouteStyle](../../com.aspose.diagram/routestyle)
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


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getDel()](../../com.aspose.diagram/pagelayout\#getDel--)

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

