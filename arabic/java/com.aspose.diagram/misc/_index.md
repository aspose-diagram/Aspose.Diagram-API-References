---
title: متنوع
second_title: Aspose.Diagram لـ Java API Reference
description: يحتوي على عناصر مختلفة من الأشكال والمجموعات مثل تلك التي تتحكم في تمييز الاختيار والرؤية.
type: docs
weight: 247
url: /ar/java/com.aspose.diagram/misc/
---

**Inheritance:**
java.lang.Object
```
public class Misc
```

يحتوي على عناصر مختلفة للأشكال والمجموعات، مثل تلك التي تتحكم في تمييز الاختيار والرؤية.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBegTrigger()](#getBegTrigger--) | يحتوي على صيغة مشغل تم إنشاؤها بواسطة Microsoft Visio تحدد ما إذا كان يجب نقل نقطة البداية لشكل أحادي البعد للحفاظ على اتصاله بشكل آخر. |
| [getCalendar()](#getCalendar--) | يحدد التقويم المستخدم للخصائص المخصصة، وحقول النص، وصيغ العناصر. |
| [getClass()](#getClass--) |  |
| [getComment()](#getComment--) | يحتوي على نص التعليق بصيغة سلسلة لشكل. |
| [getDel()](#getDel--) | علامة تشير إلى ما إذا تم حذف العنصر محليًا. |
| [getDropOnPageScale()](#getDropOnPageScale--) | يحدد النسبة المئوية التي يتم بها تكبير أو تصغير الشكل عند إسقاطه على صفحة الرسم. |
| [getDynFeedback()](#getDynFeedback--) | يحدد نوع التغذية البصرية المقدمة للمستخدمين عند سحب الموصل. |
| [getEndTrigger()](#getEndTrigger--) | يحتوي على صيغة مشغل تم إنشاؤها بواسطة Microsoft Visio. |
| [getGlueType()](#getGlueType--) | يحدد ما إذا كان السماح باللصق الديناميكي (شكل إلى شكل) مسموحًا عند الاتصال بشكل. |
| [getHideText()](#getHideText--) | يخفي النص الخاص بالشكل. |
| [getLangID()](#getLangID--) | يشير إلى معرف اللغة (LCID) للغة التي تم إدخال صيغة الخلية أو النص أو الخاصية المخصصة أو التعليق بها. |
| [getLocalizeMerge()](#getLocalizeMerge--) | يحدد ما إذا كانت الأشكال مُعربة (ما إذا تم إعادة تعيين عنصر LangID الخاص بها) عند نسخها بين المستندات. |
| [getNoAlignBox()](#getNoAlignBox--) | يحدد ما إذا كان مستطيل التحديد يُعرض عندما يتم اختيار الشكل. |
| [getNoCtlHandles()](#getNoCtlHandles--) | يحدد ما إذا كانت مقابض التحكم تُعرض عندما يتم اختيار الشكل. |
| [getNoLiveDynamics()](#getNoLiveDynamics--) | يحدد ما إذا كان الشكل يعيد تحجيمه أو يدور ديناميكيًا عندما يتعامل المستخدم معه. |
| [getNoObjHandles()](#getNoObjHandles--) | يحدد ما إذا كانت مقابض التحديد تُعرض عندما يتم اختيار الشكل. |
| [getNonPrinting()](#getNonPrinting--) | يحدد ما إذا كان يمكن طباعة الشكل المحدد. |
| [getObjType()](#getObjType--) | يحدد ما إذا كان يمكن وضع الكائنات أو توجيهها في المخططات عند استخدام Microsoft Visio لترتيب الأشكال على صفحة الرسم. |
| [getShapeKeywords()](#getShapeKeywords--) | يحتوي على كلمات بحث تم تعيينها إلى أشكال رئيسية مخصصة. |
| [getUpdateAlignBox()](#getUpdateAlignBox--) | يحدد ما إذا كان يجب إعادة حساب مستطيل اختيار الشكل كلما تم تحريك مقبض التحكم. |
| [getWalkPreference()](#getWalkPreference--) | يحدد ما إذا كانت نقطة النهاية لشكل أحادي البعد تنتقل إلى نقطة اتصال أفقية أو عمودية على الشكل الملصوق به، باستخدام اللصق الديناميكي، عندما يتم نقل الشكل إلى موضع غير واضح. |
| [hashCode()](#hashCode--) |  |
| [isDropSource()](#isDropSource--) | يحدد ما إذا كان يمكن إضافة الشكل إلى مجموعة عن طريق إسقاطه على المجموعة. |
| [isReplaceLockShapeData()](#isReplaceLockShapeData--) | يشير إلى ما إذا كانت قيم الخلايا المحددة في الشكل الرئيسي تستبدل القيم (بما في ذلك القيم المحلية) لشكل يتم استبداله أثناء عملية استبدال الشكل. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | لوصف هذه الخاصية، يرجى الاطلاع على [getDel()](../../com.aspose.diagram/misc\#getDel--) |
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
### getBegTrigger() {#getBegTrigger--}
```
public DoubleValue getBegTrigger()
```


يحتوي على صيغة مشغل تم إنشاؤها بواسطة Microsoft Visio تحدد ما إذا كان يجب نقل نقطة البداية لشكل أحادي البعد للحفاظ على اتصاله بشكل آخر.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
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
### getComment() {#getComment--}
```
public Str2Value getComment()
```


يحتوي على نص التعليق بصيغة سلسلة لشكل.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getDel() {#getDel--}
```
public int getDel()
```


علامة تشير إلى ما إذا كان العنصر قد تم حذفه محليًا. القيمة 1 تشير إلى أن العنصر تم حذفه محليًا.

**Returns:**
int
### getDropOnPageScale() {#getDropOnPageScale--}
```
public DoubleValue getDropOnPageScale()
```


يحدد النسبة المئوية التي يتم بها تكبير أو تصغير الشكل عند إسقاطه على صفحة الرسم.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDynFeedback() {#getDynFeedback--}
```
public DynFeedback getDynFeedback()
```


يحدد نوع التغذية البصرية المقدمة للمستخدمين عند سحب الموصل.

**Returns:**
[DynFeedback](../../com.aspose.diagram/dynfeedback)
### getEndTrigger() {#getEndTrigger--}
```
public DoubleValue getEndTrigger()
```


يحتوي على صيغة مشغل تم إنشاؤها بواسطة Microsoft Visio. تحدد صيغة المشغل هذه ما إذا كان يجب نقل نقطة النهاية لشكل أحادي البعد للحفاظ على اتصاله بشكل آخر.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getGlueType() {#getGlueType--}
```
public GlueType getGlueType()
```


يحدد ما إذا كان السماح باللصق الديناميكي (شكل إلى شكل) مسموحًا عند الاتصال بشكل.

**Returns:**
[GlueType](../../com.aspose.diagram/gluetype)
### getHideText() {#getHideText--}
```
public BoolValue getHideText()
```


يخفي النص لشكل. يمكنك عرض النص، تعديل الخصائص، وتطبيق الأنماط على النص في كتلة النص، على الرغم من أن التغييرات لن تظهر حتى تحدد عنصر HideText كـ 0.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLangID() {#getLangID--}
```
public IntValue getLangID()
```


يشير إلى معرف اللغة (LCID) للغة التي تم إدخال صيغة الخلية أو النص أو الخاصية المخصصة أو التعليق بها.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getLocalizeMerge() {#getLocalizeMerge--}
```
public BoolValue getLocalizeMerge()
```


يحدد ما إذا كانت الأشكال مُعربة (ما إذا تم إعادة تعيين عنصر LangID الخاص بها) عند نسخها بين المستندات.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoAlignBox() {#getNoAlignBox--}
```
public BoolValue getNoAlignBox()
```


يحدد ما إذا كان مستطيل التحديد يُعرض عندما يتم اختيار الشكل.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoCtlHandles() {#getNoCtlHandles--}
```
public BoolValue getNoCtlHandles()
```


يحدد ما إذا كانت مقابض التحكم تُعرض عندما يتم اختيار الشكل.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoLiveDynamics() {#getNoLiveDynamics--}
```
public BoolValue getNoLiveDynamics()
```


يحدد ما إذا كان الشكل يعيد تحجيمه أو يدور ديناميكيًا عندما يتعامل المستخدم معه.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoObjHandles() {#getNoObjHandles--}
```
public BoolValue getNoObjHandles()
```


يحدد ما إذا كانت مقابض التحديد تُعرض عندما يتم اختيار الشكل.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNonPrinting() {#getNonPrinting--}
```
public BoolValue getNonPrinting()
```


يحدد ما إذا كان يمكن طباعة الشكل المحدد.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getObjType() {#getObjType--}
```
public ObjType getObjType()
```


يحدد ما إذا كان يمكن وضع الكائنات أو توجيهها في المخططات عند استخدام Microsoft Visio لترتيب الأشكال على صفحة الرسم.

**Returns:**
[ObjType](../../com.aspose.diagram/objtype)
### getShapeKeywords() {#getShapeKeywords--}
```
public Str2Value getShapeKeywords()
```


يحتوي على كلمات بحث تم تعيينها إلى أشكال رئيسية مخصصة.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getUpdateAlignBox() {#getUpdateAlignBox--}
```
public BoolValue getUpdateAlignBox()
```


يحدد ما إذا كان يجب إعادة حساب مستطيل اختيار الشكل كلما تم تحريك مقبض التحكم.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getWalkPreference() {#getWalkPreference--}
```
public WalkPreference getWalkPreference()
```


يحدد ما إذا كانت نقطة النهاية لشكل أحادي البعد تنتقل إلى نقطة اتصال أفقية أو عمودية على الشكل الملصوق به، باستخدام اللصق الديناميكي، عندما يتم نقل الشكل إلى موضع غير واضح.

**Returns:**
[WalkPreference](../../com.aspose.diagram/walkpreference)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDropSource() {#isDropSource--}
```
public BoolValue isDropSource()
```


يحدد ما إذا كان يمكن إضافة الشكل إلى مجموعة عن طريق إسقاطه على المجموعة.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### isReplaceLockShapeData() {#isReplaceLockShapeData--}
```
public BoolValue isReplaceLockShapeData()
```


يشير إلى ما إذا كانت قيم الخلايا المحددة في الشكل الرئيسي تستبدل القيم (بما في ذلك القيم المحلية) لشكل يتم استبداله أثناء عملية استبدال الشكل.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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


لوصف هذه الخاصية، يرجى الاطلاع على [getDel()](../../com.aspose.diagram/misc\#getDel--)

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

