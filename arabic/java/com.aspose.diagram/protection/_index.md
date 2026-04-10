---
title: الحماية
second_title: Aspose.Diagram لـ Java API Reference
description: يساعد القفل على منع التغييرات غير المقصودة على الشكل لكنه لا يمنع Microsoft Visio من إعادة تعيين القيم في ظروف أخرى.
type: docs
weight: 312
url: /ar/java/com.aspose.diagram/protection/
---

**Inheritance:**
java.lang.Object
```
public class Protection
```

يساعد القفل في منع التغييرات غير المقصودة على الشكل لكنه لا يمنع Microsoft Visio من إعادة تعيين القيم في ظروف أخرى. كما أنه لا يحمي من التغييرات التي تُجرى في نافذة ShapeSheet.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | علامة تشير إلى ما إذا تم حذف العنصر محليًا. |
| [getLockAspect()](#getLockAspect--) | يحدد ما إذا كان نسبة أبعاد الشكل مقفلة. |
| [getLockBegin()](#getLockBegin--) | يحدد ما إذا كانت نقطة البداية لشكل أحادي البُعد مقفلة في موقع محدد. |
| [getLockCalcWH()](#getLockCalcWH--) | يحدد ما إذا كان مستطيل اختيار الشكل مقفلاً بحيث لا يمكن إعادة حسابه عند تعديل رأس أو تغيير نوع العنصر في عنصر Geom. |
| [getLockCrop()](#getLockCrop--) | يحدد ما إذا كان الكائن الخارجي مقفلاً من القص باستخدام أداة Crop في Microsoft Visio. |
| [getLockCustProp()](#getLockCustProp--) | يحدد ما إذا كان المستخدم يمكنه إضافة أو حذف أو تعديل الخصائص المخصصة في واجهة المستخدم (UI) باستخدام مربع حوار Define Custom Properties. |
| [getLockDelete()](#getLockDelete--) | يحدد ما إذا كان الشكل مقفلاً من الحذف. |
| [getLockEnd()](#getLockEnd--) | يحدد ما إذا كانت نقطة النهاية لشكل أحادي البُعد مقفلة في موقع محدد. |
| [getLockFormat()](#getLockFormat--) | يحدد ما إذا كان تنسيق الشكل مقفلاً بحيث لا يمكن تغييره. |
| [getLockFromGroupFormat()](#getLockFromGroupFormat--) | يسمح للشكل الفرعي بحجب تغييرات التنسيق التي تُطبق على شكل مجموعة الأصل في واجهة Visio، والتي كانت لتنتقل إلى الأشكال الفردية داخل المجموعة. |
| [getLockGroup()](#getLockGroup--) | يحدد ما إذا كانت المجموعة مقفلة بحيث لا يمكن فك تجميعها. |
| [getLockHeight()](#getLockHeight--) | يحدد ما إذا كان ارتفاع الشكل مقفلاً. |
| [getLockMoveX()](#getLockMoveX--) | يحدد ما إذا كان الموقع الأفقي للشكل مقفلاً بحيث لا يمكن تحريكه أفقياً. |
| [getLockMoveY()](#getLockMoveY--) | يحدد ما إذا كان الموقع الرأسي للشكل مقفلاً بحيث لا يمكن تحريكه رأسياً. |
| [getLockRotate()](#getLockRotate--) | يحدد ما إذا كان الشكل مقفلاً من الدوران باستخدام أداة Rotation أو أوامر Rotate Left أو Rotate Right في Microsoft Visio. |
| [getLockSelect()](#getLockSelect--) | يحدد ما إذا كان مستطيل اختيار الشكل مقفلاً بحيث لا يمكن إعادة حسابه عند تعديل رأس أو تغيير نوع العنصر في عنصر Geom. |
| [getLockTextEdit()](#getLockTextEdit--) | يحدد ما إذا كان نص الشكل مقفلاً بحيث لا يمكن تحريره. |
| [getLockThemeColors()](#getLockThemeColors--) | يمنع المستخدمين من تطبيق ألوان السمة على الشكل. |
| [getLockThemeEffects()](#getLockThemeEffects--) | يمنع المستخدمين من تطبيق تأثيرات السمة على الشكل. |
| [getLockVtxEdit()](#getLockVtxEdit--) | يحدد ما إذا كانت رؤوس الشكل مقفلة بحيث لا يمكن تعديلها باستخدام أي أدوات في شريط الأدوات. |
| [getLockWidth()](#getLockWidth--) | يحدد ما إذا كان عرض الشكل مقفلًا بحيث يظل دون تغيير عند تغيير حجم الشكل. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getDel()](../../com.aspose.diagram/protection\#getDel--) |
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
### getLockAspect() {#getLockAspect--}
```
public BoolValue getLockAspect()
```


يحدد ما إذا كان نسبة أبعاد الشكل مقفلة. إذا كانت مقفلة، لا يمكن تغيير حجم الشكل إلا بشكل متناسب؛ ولا يمكن تغيير حجمه في بعد واحد.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockBegin() {#getLockBegin--}
```
public BoolValue getLockBegin()
```


يحدد ما إذا كانت نقطة البداية لشكل أحادي البُعد مقفلة في موقع محدد.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockCalcWH() {#getLockCalcWH--}
```
public BoolValue getLockCalcWH()
```


يحدد ما إذا كان مستطيل اختيار الشكل مقفلاً بحيث لا يمكن إعادة حسابه عند تعديل رأس أو تغيير نوع العنصر في عنصر Geom.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockCrop() {#getLockCrop--}
```
public BoolValue getLockCrop()
```


يحدد ما إذا كان الكائن الخارجي مقفلاً من القص باستخدام أداة Crop في Microsoft Visio.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockCustProp() {#getLockCustProp--}
```
public BoolValue getLockCustProp()
```


يحدد ما إذا كان المستخدم يمكنه إضافة أو حذف أو تعديل الخصائص المخصصة في واجهة المستخدم (UI) باستخدام مربع حوار Define Custom Properties.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockDelete() {#getLockDelete--}
```
public BoolValue getLockDelete()
```


يحدد ما إذا كان الشكل مقفلاً من الحذف.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockEnd() {#getLockEnd--}
```
public BoolValue getLockEnd()
```


يحدد ما إذا كانت نقطة النهاية لشكل أحادي البُعد مقفلة في موقع محدد.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockFormat() {#getLockFormat--}
```
public BoolValue getLockFormat()
```


يحدد ما إذا كان تنسيق الشكل مقفلًا بحيث لا يمكن تغييره. على وجه التحديد، يحمي هذا العنصر من تغيير تنسيق النص أو الخط أو التعبئة، أو تغيير عنصر Style الذي يرثه الشكل.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockFromGroupFormat() {#getLockFromGroupFormat--}
```
public BoolValue getLockFromGroupFormat()
```


يسمح للشكل الفرعي بحجب تغييرات التنسيق التي تُطبق على شكل مجموعة الأصل في واجهة Visio، والتي كانت لتنتقل إلى الأشكال الفردية داخل المجموعة.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockGroup() {#getLockGroup--}
```
public BoolValue getLockGroup()
```


يحدد ما إذا كانت المجموعة مقفلة بحيث لا يمكن فك تجميعها.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockHeight() {#getLockHeight--}
```
public BoolValue getLockHeight()
```


يحدد ما إذا كان ارتفاع الشكل مقفلًا. إذا كان مقفلًا، يبقى ارتفاعه دون تغيير عند تغيير حجم الشكل.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockMoveX() {#getLockMoveX--}
```
public BoolValue getLockMoveX()
```


يحدد ما إذا كان الموقع الأفقي للشكل مقفلاً بحيث لا يمكن تحريكه أفقياً.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockMoveY() {#getLockMoveY--}
```
public BoolValue getLockMoveY()
```


يحدد ما إذا كان الموقع الرأسي للشكل مقفلاً بحيث لا يمكن تحريكه رأسياً.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockRotate() {#getLockRotate--}
```
public BoolValue getLockRotate()
```


يحدد ما إذا كان الشكل مقفلاً من الدوران باستخدام أداة Rotation أو أوامر Rotate Left أو Rotate Right في Microsoft Visio.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockSelect() {#getLockSelect--}
```
public BoolValue getLockSelect()
```


يحدد ما إذا كان مستطيل اختيار الشكل مقفلاً بحيث لا يمكن إعادة حسابه عند تعديل رأس أو تغيير نوع العنصر في عنصر Geom.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockTextEdit() {#getLockTextEdit--}
```
public BoolValue getLockTextEdit()
```


يحدد ما إذا كان نص الشكل مقفلًا بحيث لا يمكن تحريره. ومع ذلك، قد يظل النص قابلًا للتنسيق عن طريق تطبيق نمط، باستخدام خيارات Style في علامة تبويب الخط في مربع حوار النص.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockThemeColors() {#getLockThemeColors--}
```
public BoolValue getLockThemeColors()
```


يمنع المستخدمين من تطبيق ألوان السمة على الشكل.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockThemeEffects() {#getLockThemeEffects--}
```
public BoolValue getLockThemeEffects()
```


يمنع المستخدمين من تطبيق تأثيرات السمة على الشكل.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockVtxEdit() {#getLockVtxEdit--}
```
public BoolValue getLockVtxEdit()
```


يحدد ما إذا كانت رؤوس الشكل مقفلة بحيث لا يمكن تعديلها باستخدام أي أدوات في شريط الأدوات.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockWidth() {#getLockWidth--}
```
public BoolValue getLockWidth()
```


يحدد ما إذا كان عرض الشكل مقفلًا بحيث يظل دون تغيير عند تغيير حجم الشكل.

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


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getDel()](../../com.aspose.diagram/protection\#getDel--)

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

