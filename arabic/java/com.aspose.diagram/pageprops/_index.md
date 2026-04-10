---
title: PageProps
second_title: Aspose.Diagram لـ Java API Reference
description: يحتوي على خلايا تتحكم في سمات الصفحة مثل عرض الصفحة وارتفاعها والقياس.
type: docs
weight: 268
url: /ar/java/com.aspose.diagram/pageprops/
---

**Inheritance:**
java.lang.Object
```
public class PageProps
```

يحتوي على خلايا تتحكم في خصائص الصفحة، مثل عرض الصفحة، ارتفاعها، ومقياسها.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [deepClone()](#deepClone--) | ينشئ نسخة عميقة من هذه المثيلة. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | علامة تشير إلى ما إذا تم حذف العنصر محليًا. |
| [getDrawingResizeType()](#getDrawingResizeType--) | يحدد ما إذا كانت صفحة الرسم تُعيد التحجيم تلقائيًا لتناسب المخطط. |
| [getDrawingScale()](#getDrawingScale--) | يمثل قيمة وحدة الرسم في مقياس الرسم الحالي. |
| [getDrawingScaleType()](#getDrawingScaleType--) | يحدد نوع مقياس الرسم المستخدم للصفحة. |
| [getDrawingSizeType()](#getDrawingSizeType--) | يحدد حجم الرسم للصفحة. |
| [getInhibitSnap()](#getInhibitSnap--) | يحدد ما إذا كانت الأشكال على صفحة المقدمة تلتصق بكائنات أخرى على الصفحة والأشكال على صفحة الخلفية. |
| [getPageHeight()](#getPageHeight--) | يحدد ارتفاع الصفحة بوحدات الرسم. |
| [getPageScale()](#getPageScale--) | يحدد قيمة وحدة الصفحة الافتراضية في مقياس الرسم الحالي. |
| [getPageWidth()](#getPageWidth--) | يحدد عرض الصفحة بوحدات الرسم. |
| [getShdwObliqueAngle()](#getShdwObliqueAngle--) | يحتوي على رقم يحدد زاوية الاتجاه المائل عندما يتم تطبيق نوع الظل الافتراضي للصفحة. |
| [getShdwOffsetX()](#getShdwOffsetX--) | يحدد المسافة بوحدات الصفحة التي يتحرك فيها ظل الشكل الإسقاطي أفقياً عن الشكل. |
| [getShdwOffsetY()](#getShdwOffsetY--) | يحدد المسافة بوحدات الصفحة التي يتحرك فيها ظل الشكل الإسقاطي رأسياً عن الشكل. |
| [getShdwScaleFactor()](#getShdwScaleFactor--) | يحدد النسبة المئوية لتكبير أو تقليل ظل الشكل. |
| [getShdwType()](#getShdwType--) | يشير إلى نوع الظل الافتراضي للصفحة. |
| [getUIVisibility()](#getUIVisibility--) | يحدد ما إذا كان اسم الصفحة معروضاً في واجهة المستخدم (UI). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | لوصف هذه الخاصية، يرجى الاطلاع على [getDel()](../../com.aspose.diagram/pageprops\#getDel--) |
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
### getDrawingResizeType() {#getDrawingResizeType--}
```
public DrawingResizeType getDrawingResizeType()
```


يحدد ما إذا كانت صفحة الرسم تُعيد التحجيم تلقائيًا لتناسب المخطط.

**Returns:**
[DrawingResizeType](../../com.aspose.diagram/drawingresizetype)
### getDrawingScale() {#getDrawingScale--}
```
public DoubleValue getDrawingScale()
```


يمثل قيمة وحدة الرسم في مقياس الرسم الحالي. مقياس الرسم للصفحة هو نسبة وحدة الصفحة الموجودة في عنصر PageScale إلى وحدة الرسم. وحدات هذا العنصر تحدد وحدات الطول الافتراضية (DL) للصفحة.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDrawingScaleType() {#getDrawingScaleType--}
```
public DrawingScaleType getDrawingScaleType()
```


يحدد نوع مقياس الرسم المستخدم للصفحة.

**Returns:**
[DrawingScaleType](../../com.aspose.diagram/drawingscaletype)
### getDrawingSizeType() {#getDrawingSizeType--}
```
public DrawingSizeType getDrawingSizeType()
```


يحدد حجم الرسم للصفحة.

**Returns:**
[DrawingSizeType](../../com.aspose.diagram/drawingsizetype)
### getInhibitSnap() {#getInhibitSnap--}
```
public BoolValue getInhibitSnap()
```


يحدد ما إذا كانت الأشكال على صفحة المقدمة تلتصق بكائنات أخرى على الصفحة والأشكال على صفحة الخلفية.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getPageHeight() {#getPageHeight--}
```
public DoubleValue getPageHeight()
```


يحدد ارتفاع الصفحة بوحدات الرسم.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPageScale() {#getPageScale--}
```
public DoubleValue getPageScale()
```


يحدد قيمة وحدة الصفحة الافتراضية في مقياس الرسم الحالي. مقياس الرسم للصفحة هو نسبة وحدة الصفحة في عنصر PageScale إلى وحدة الرسم المعروضة في عنصر DrawingScale.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPageWidth() {#getPageWidth--}
```
public DoubleValue getPageWidth()
```


يحدد عرض الصفحة بوحدات الرسم.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwObliqueAngle() {#getShdwObliqueAngle--}
```
public DoubleValue getShdwObliqueAngle()
```


يحتوي على رقم يحدد زاوية الاتجاه المائل عندما يتم تطبيق نوع الظل الافتراضي للصفحة.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwOffsetX() {#getShdwOffsetX--}
```
public DoubleValue getShdwOffsetX()
```


يحدد المسافة بوحدات الصفحة التي يتحرك فيها ظل الشكل الإسقاطي أفقياً عن الشكل.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwOffsetY() {#getShdwOffsetY--}
```
public DoubleValue getShdwOffsetY()
```


يحدد المسافة بوحدات الصفحة التي يتحرك فيها ظل الشكل الإسقاطي رأسياً عن الشكل.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwScaleFactor() {#getShdwScaleFactor--}
```
public DoubleValue getShdwScaleFactor()
```


يحدد النسبة المئوية لتكبير أو تقليل ظل الشكل.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwType() {#getShdwType--}
```
public ShdwType getShdwType()
```


يشير إلى نوع الظل الافتراضي للصفحة.

**Returns:**
[ShdwType](../../com.aspose.diagram/shdwtype)
### getUIVisibility() {#getUIVisibility--}
```
public UIVisibility getUIVisibility()
```


يحدد ما إذا كان اسم الصفحة معروضاً في واجهة المستخدم (UI). القيمة 1 تعني أن الصفحة غير مرئية؛ والقيمة 0 تعني أن الصفحة مرئية.

**Returns:**
[UIVisibility](../../com.aspose.diagram/uivisibility)
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


لوصف هذه الخاصية، يرجى الاطلاع على [getDel()](../../com.aspose.diagram/pageprops\#getDel--)

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

