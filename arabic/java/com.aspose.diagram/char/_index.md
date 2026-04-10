---
title: Char
second_title: Aspose.Diagram لـ Java API Reference
description: يحتوي على سمات التنسيق لنص الأشكال مثل لون الخط، نمط النص، حالة الأحرف، الموضع بالنسبة إلى الخط الأساسي، وحجم النقطة.
type: docs
weight: 45
url: /ar/java/com.aspose.diagram/char/
---

**Inheritance:**
java.lang.Object
```
public class Char
```

يحتوي على سمات التنسيق لنص الشكل، مثل الخط، اللون، نمط النص، الحالة، الموضع بالنسبة للخط الأساسي، وحجم النقطة.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Char()](#Char--) | منشئ. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [deepClone()](#deepClone--) | ينشئ نسخة عميقة من هذه المثيلة. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAsianFont()](#getAsianFont--) | يحدد رقم المعرف للخط المستخدم لتنسيق النص الذي يحتوي على أحرف آسيوية. |
| [getAsianFontName()](#getAsianFontName--) | يحدد اسم الخط الآسيوي للخط المستخدم لتنسيق النص. يُستخدم في Visio 2013. |
| [getCase()](#getCase--) | يحدد حالة نص الشكل. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | عند وجوده داخل عنصر Char، عنصر Color. |
| [getColorTrans()](#getColorTrans--) | يحدد درجة الشفافية للون نص طبقة أو شكل، من 0 (معتم تمامًا) إلى 1 (شفاف تمامًا). |
| [getComplexScriptFont()](#getComplexScriptFont--) | يحتوي على رقم الخط المستخدم لتنسيق النص المكوّن من أحرف نصية معقدة. |
| [getComplexScriptFontName()](#getComplexScriptFontName--) | يحدد اسم خط ComplexScript للخط المستخدم لتنسيق النص. يُستخدم في Visio 2013. |
| [getComplexScriptSize()](#getComplexScriptSize--) | حجم الخط المستخدم لتنسيق النص المكوّن من أحرف نصية معقدة. |
| [getDblUnderline()](#getDblUnderline--) | يحدد ما إذا كان نطاق النص يحتوي على خط سفلي مزدوج. |
| [getDel()](#getDel--) | علامة تشير إلى ما إذا تم حذف العنصر محليًا. |
| [getDoubleStrikethrough()](#getDoubleStrikethrough--) | يحدد ما إذا كان النص مُنسقًا كخط مزدوج مشطوب. |
| [getFont()](#getFont--) | يحدد رقم المعرف للخط المستخدم لتنسيق النص. |
| [getFontName()](#getFontName--) | يحدد اسم الخط المستخدم لتنسيق النص. إنه يُستخدم لبرنامج Visio 2013. |
| [getFontScale()](#getFontScale--) | يحدد عرض الخط. |
| [getHighlight()](#getHighlight--) | يحدد التمييز. |
| [getIX()](#getIX--) | فهرس العنصر داخل العنصر الأصل بدءًا من الصفر. |
| [getLangID()](#getLangID--) | يشير إلى معرف اللغة (LCID) للغة التي تم إدخال صيغة الخلية أو النص أو الخاصية المخصصة أو التعليق بها. |
| [getLetterspace()](#getLetterspace--) | يحدد مقدار المسافة بين حرفين أو أكثر. |
| [getLocale()](#getLocale--) | يحدد إعداد اللغة لتشغيل النص لأغراض التدقيق الإملائي. |
| [getLocalizeFont()](#getLocalizeFont--) | يحدد ما إذا كان نص الشكل يجب أن يُعرب (يُترجم إلى لغة أخرى). |
| [getOverline()](#getOverline--) | يحدد ما إذا كان للنص خط فوقه. |
| [getPerpendicular()](#getPerpendicular--) | يحدد ما إذا كان حقل النص يظهر عموديًا على النص الآخر في كتلة النص. |
| [getPos()](#getPos--) | يحدد موضع نص الشكل بالنسبة إلى خط الأساس. |
| [getRTLText()](#getRTLText--) | يحدد ما إذا كان اتجاه النص لتشغيل الأحرف الحالي من اليسار إلى اليمين أو من اليمين إلى اليسار. |
| [getSize()](#getSize--) | يحدد حجم النص في كتلة النص الخاصة بالشكل. |
| [getStrikethru()](#getStrikethru--) | يحدد ما إذا كان النص مُنسقًا كخط مشطوب. |
| [getStyle()](#getStyle--) | يحدد تنسيق الأحرف المطبق على نطاق من النص في كتلة النص الخاصة بالشكل. |
| [getUseVertical()](#getUseVertical--) | يحدد ما إذا كان تشغيل الأحرف عموديًا أو أفقيًا. |
| [hashCode()](#hashCode--) |  |
| [isBold()](#isBold--) | يشير إلى ما إذا كان الخط غامقًا. |
| [isDoubleStrikethrough()](#isDoubleStrikethrough--) | يشير إلى ما إذا كان الخط doubleStrikethrough. |
| [isDoubleUnderline()](#isDoubleUnderline--) | يشير إلى ما إذا كان الخط تحته خط مزدوج. |
| [isItalic()](#isItalic--) | يشير إلى ما إذا كان الخط مائلًا. |
| [isStrikethrough()](#isStrikethrough--) | يشير إلى ما إذا كان الخط مشطوبًا. |
| [isSubscript()](#isSubscript--) | يشير إلى ما إذا كان الخط نصًا سفليًا. |
| [isSuperscript()](#isSuperscript--) | يشير إلى ما إذا كان الخط نصًا علويًا. |
| [isUnderline()](#isUnderline--) | يشير إلى ما إذا كان الخط تحته خط. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAsianFont(IntValue value)](#setAsianFont-com.aspose.diagram.IntValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getAsianFont()](../../com.aspose.diagram/char\#getAsianFont--) |
| [setAsianFontName(StrValue value)](#setAsianFontName-com.aspose.diagram.StrValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getAsianFontName()](../../com.aspose.diagram/char\#getAsianFontName--) |
| [setCase(Case value)](#setCase-com.aspose.diagram.Case-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getCase()](../../com.aspose.diagram/char\#getCase--) |
| [setColor(ColorValue value)](#setColor-com.aspose.diagram.ColorValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getColor()](../../com.aspose.diagram/char\#getColor--) |
| [setColorTrans(DoubleValue value)](#setColorTrans-com.aspose.diagram.DoubleValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getColorTrans()](../../com.aspose.diagram/char\#getColorTrans--) |
| [setComplexScriptFont(IntValue value)](#setComplexScriptFont-com.aspose.diagram.IntValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getComplexScriptFont()](../../com.aspose.diagram/char\#getComplexScriptFont--) |
| [setComplexScriptFontName(StrValue value)](#setComplexScriptFontName-com.aspose.diagram.StrValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getComplexScriptFontName()](../../com.aspose.diagram/char\#getComplexScriptFontName--) |
| [setComplexScriptSize(DoubleValue value)](#setComplexScriptSize-com.aspose.diagram.DoubleValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getComplexScriptSize()](../../com.aspose.diagram/char\#getComplexScriptSize--) |
| [setDblUnderline(BoolValue value)](#setDblUnderline-com.aspose.diagram.BoolValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getDblUnderline()](../../com.aspose.diagram/char\#getDblUnderline--) |
| [setDel(int value)](#setDel-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getDel()](../../com.aspose.diagram/char\#getDel--) |
| [setDoubleStrikethrough(BoolValue value)](#setDoubleStrikethrough-com.aspose.diagram.BoolValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getDoubleStrikethrough()](../../com.aspose.diagram/char\#getDoubleStrikethrough--) |
| [setFont(IntValue value)](#setFont-com.aspose.diagram.IntValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getFont()](../../com.aspose.diagram/char\#getFont--) |
| [setFontName(StrValue value)](#setFontName-com.aspose.diagram.StrValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getFontName()](../../com.aspose.diagram/char\#getFontName--) |
| [setFontScale(DoubleValue value)](#setFontScale-com.aspose.diagram.DoubleValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getFontScale()](../../com.aspose.diagram/char\#getFontScale--) |
| [setHighlight(BoolValue value)](#setHighlight-com.aspose.diagram.BoolValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getHighlight()](../../com.aspose.diagram/char\#getHighlight--) |
| [setIX(int value)](#setIX-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getIX()](../../com.aspose.diagram/char\#getIX--) |
| [setLangID(IntValue value)](#setLangID-com.aspose.diagram.IntValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getLangID()](../../com.aspose.diagram/char\#getLangID--) |
| [setLetterspace(DoubleValue value)](#setLetterspace-com.aspose.diagram.DoubleValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getLetterspace()](../../com.aspose.diagram/char\#getLetterspace--) |
| [setLocale(StrValue value)](#setLocale-com.aspose.diagram.StrValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getLocale()](../../com.aspose.diagram/char\#getLocale--) |
| [setLocalizeFont(LocalizeFont value)](#setLocalizeFont-com.aspose.diagram.LocalizeFont-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getLocalizeFont()](../../com.aspose.diagram/char\#getLocalizeFont--) |
| [setOverline(BoolValue value)](#setOverline-com.aspose.diagram.BoolValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getOverline()](../../com.aspose.diagram/char\#getOverline--) |
| [setPerpendicular(StrValue value)](#setPerpendicular-com.aspose.diagram.StrValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getPerpendicular()](../../com.aspose.diagram/char\#getPerpendicular--) |
| [setPos(Pos value)](#setPos-com.aspose.diagram.Pos-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getPos()](../../com.aspose.diagram/char\#getPos--) |
| [setRTLText(BoolValue value)](#setRTLText-com.aspose.diagram.BoolValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getRTLText()](../../com.aspose.diagram/char\#getRTLText--) |
| [setSize(DoubleValue value)](#setSize-com.aspose.diagram.DoubleValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getSize()](../../com.aspose.diagram/char\#getSize--) |
| [setStrikethru(BoolValue value)](#setStrikethru-com.aspose.diagram.BoolValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getStrikethru()](../../com.aspose.diagram/char\#getStrikethru--) |
| [setStyle(Style value)](#setStyle-com.aspose.diagram.Style-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getStyle()](../../com.aspose.diagram/char\#getStyle--) |
| [setUseVertical(BoolValue value)](#setUseVertical-com.aspose.diagram.BoolValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getUseVertical()](../../com.aspose.diagram/char\#getUseVertical--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Char() {#Char--}
```
public Char()
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
### getAsianFont() {#getAsianFont--}
```
public IntValue getAsianFont()
```


يحدد رقم المعرف للخط المستخدم لتنسيق النص الذي يحتوي على أحرف آسيوية.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getAsianFontName() {#getAsianFontName--}
```
public StrValue getAsianFontName()
```


يحدد اسم الخط الآسيوي للخط المستخدم لتنسيق النص. يُستخدم في Visio 2013.

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
### getCase() {#getCase--}
```
public Case getCase()
```


يحدد حالة نص الشكل.

**Returns:**
[Case](../../com.aspose.diagram/case)
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


عند وجوده داخل عنصر Char، عنصر Color.

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getColorTrans() {#getColorTrans--}
```
public DoubleValue getColorTrans()
```


يحدد درجة الشفافية للون نص طبقة أو شكل، من 0 (معتم تمامًا) إلى 1 (شفاف تمامًا).

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getComplexScriptFont() {#getComplexScriptFont--}
```
public IntValue getComplexScriptFont()
```


يحتوي على رقم الخط المستخدم لتنسيق النص المكوّن من أحرف النصوص المعقدة. النصوص المعقدة هي لغات تحتاج أحرفها إلى ربط أو تشكيل، مثل اللغات من اليمين إلى اليسار (العربية، الفارسية، العبرية، والأردية) وعدة لغات جنوب آسيوية.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getComplexScriptFontName() {#getComplexScriptFontName--}
```
public StrValue getComplexScriptFontName()
```


يحدد اسم خط ComplexScript للخط المستخدم لتنسيق النص. يُستخدم في Visio 2013.

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
### getComplexScriptSize() {#getComplexScriptSize--}
```
public DoubleValue getComplexScriptSize()
```


حجم الخط المستخدم لتنسيق النص المكوّن من أحرف النصوص المعقدة. النصوص المعقدة هي لغات تتطلب حروفها ربطًا أو تشكيلًا، مثل اللغات من اليمين إلى اليسار (العربية، الفارسية، العبرية، والأردية) وعدة لغات جنوب آسيوية.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDblUnderline() {#getDblUnderline--}
```
public BoolValue getDblUnderline()
```


يحدد ما إذا كان نطاق النص يحتوي على خط سفلي مزدوج.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getDel() {#getDel--}
```
public int getDel()
```


علامة تشير إلى ما إذا كان العنصر قد تم حذفه محليًا. القيمة 1 تشير إلى أن العنصر تم حذفه محليًا.

**Returns:**
int
### getDoubleStrikethrough() {#getDoubleStrikethrough--}
```
public BoolValue getDoubleStrikethrough()
```


يحدد ما إذا كان النص مُنسقًا كخط مزدوج مشطوب.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getFont() {#getFont--}
```
public IntValue getFont()
```


يحدد رقم المعرف للخط المستخدم لتنسيق النص.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getFontName() {#getFontName--}
```
public StrValue getFontName()
```


يحدد اسم الخط المستخدم لتنسيق النص. إنه يُستخدم لبرنامج Visio 2013.

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
### getFontScale() {#getFontScale--}
```
public DoubleValue getFontScale()
```


يحدد عرض الخط.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getHighlight() {#getHighlight--}
```
public BoolValue getHighlight()
```


يحدد التمييز.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getIX() {#getIX--}
```
public int getIX()
```


فهرس العنصر داخل العنصر الأصل بدءًا من الصفر.

**Returns:**
int
### getLangID() {#getLangID--}
```
public IntValue getLangID()
```


يشير إلى معرف اللغة (LCID) للغة التي تم إدخال صيغة الخلية أو النص أو الخاصية المخصصة أو التعليق بها. للحصول على قائمة اللغات المدعومة من تطبيقات Microsoft Office ومعرفات اللغات المقابلة لها، راجع عنصر DocLangID.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getLetterspace() {#getLetterspace--}
```
public DoubleValue getLetterspace()
```


يحدد مقدار المسافة بين حرفين أو أكثر. يمكن إضافة أو حذف المسافة بزيادات قدرها 1/20 نقطة.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLocale() {#getLocale--}
```
public StrValue getLocale()
```


يحدد إعداد اللغة لتشغيل النص لأغراض التدقيق الإملائي.

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
### getLocalizeFont() {#getLocalizeFont--}
```
public LocalizeFont getLocalizeFont()
```


يحدد ما إذا كان نص الشكل يجب أن يُعرب (يُترجم إلى لغة أخرى).

**Returns:**
[LocalizeFont](../../com.aspose.diagram/localizefont)
### getOverline() {#getOverline--}
```
public BoolValue getOverline()
```


يحدد ما إذا كان للنص خط فوقه.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getPerpendicular() {#getPerpendicular--}
```
public StrValue getPerpendicular()
```


يحدد ما إذا كان حقل النص يظهر عموديًا على النص الآخر في كتلة النص.

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
### getPos() {#getPos--}
```
public Pos getPos()
```


يحدد موضع نص الشكل بالنسبة إلى خط الأساس.

**Returns:**
[Pos](../../com.aspose.diagram/pos)
### getRTLText() {#getRTLText--}
```
public BoolValue getRTLText()
```


يحدد ما إذا كان اتجاه النص لتشغيل الأحرف الحالي من اليسار إلى اليمين أو من اليمين إلى اليسار.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getSize() {#getSize--}
```
public DoubleValue getSize()
```


يحدد حجم النص في كتلة النص الخاصة بالشكل.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getStrikethru() {#getStrikethru--}
```
public BoolValue getStrikethru()
```


يحدد ما إذا كان النص مُنسقًا كخط مشطوب.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getStyle() {#getStyle--}
```
public Style getStyle()
```


يحدد تنسيق الأحرف المطبق على نطاق من النص في كتلة النص الخاصة بالشكل.

**Returns:**
[Style](../../com.aspose.diagram/style)
### getUseVertical() {#getUseVertical--}
```
public BoolValue getUseVertical()
```


يحدد ما إذا كان تشغيل الأحرف عموديًا أو أفقيًا.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isBold() {#isBold--}
```
public boolean isBold()
```


يشير إلى ما إذا كان الخط غامقًا.

**Returns:**
منطقي
### isDoubleStrikethrough() {#isDoubleStrikethrough--}
```
public boolean isDoubleStrikethrough()
```


يشير إلى ما إذا كان الخط doubleStrikethrough.

**Returns:**
منطقي
### isDoubleUnderline() {#isDoubleUnderline--}
```
public boolean isDoubleUnderline()
```


يشير إلى ما إذا كان الخط تحته خط مزدوج.

**Returns:**
منطقي
### isItalic() {#isItalic--}
```
public boolean isItalic()
```


يشير إلى ما إذا كان الخط مائلًا.

**Returns:**
منطقي
### isStrikethrough() {#isStrikethrough--}
```
public boolean isStrikethrough()
```


يشير إلى ما إذا كان الخط مشطوبًا.

**Returns:**
منطقي
### isSubscript() {#isSubscript--}
```
public boolean isSubscript()
```


يشير إلى ما إذا كان الخط نصًا سفليًا.

**Returns:**
منطقي
### isSuperscript() {#isSuperscript--}
```
public boolean isSuperscript()
```


يشير إلى ما إذا كان الخط نصًا علويًا.

**Returns:**
منطقي
### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


يشير إلى ما إذا كان الخط تحته خط.

**Returns:**
منطقي
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAsianFont(IntValue value) {#setAsianFont-com.aspose.diagram.IntValue-}
```
public void setAsianFont(IntValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getAsianFont()](../../com.aspose.diagram/char\#getAsianFont--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setAsianFontName(StrValue value) {#setAsianFontName-com.aspose.diagram.StrValue-}
```
public void setAsianFontName(StrValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getAsianFontName()](../../com.aspose.diagram/char\#getAsianFontName--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [StrValue](../../com.aspose.diagram/strvalue) |  |

### setCase(Case value) {#setCase-com.aspose.diagram.Case-}
```
public void setCase(Case value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getCase()](../../com.aspose.diagram/char\#getCase--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Case](../../com.aspose.diagram/case) |  |

### setColor(ColorValue value) {#setColor-com.aspose.diagram.ColorValue-}
```
public void setColor(ColorValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getColor()](../../com.aspose.diagram/char\#getColor--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setColorTrans(DoubleValue value) {#setColorTrans-com.aspose.diagram.DoubleValue-}
```
public void setColorTrans(DoubleValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getColorTrans()](../../com.aspose.diagram/char\#getColorTrans--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setComplexScriptFont(IntValue value) {#setComplexScriptFont-com.aspose.diagram.IntValue-}
```
public void setComplexScriptFont(IntValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getComplexScriptFont()](../../com.aspose.diagram/char\#getComplexScriptFont--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setComplexScriptFontName(StrValue value) {#setComplexScriptFontName-com.aspose.diagram.StrValue-}
```
public void setComplexScriptFontName(StrValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getComplexScriptFontName()](../../com.aspose.diagram/char\#getComplexScriptFontName--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [StrValue](../../com.aspose.diagram/strvalue) |  |

### setComplexScriptSize(DoubleValue value) {#setComplexScriptSize-com.aspose.diagram.DoubleValue-}
```
public void setComplexScriptSize(DoubleValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getComplexScriptSize()](../../com.aspose.diagram/char\#getComplexScriptSize--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setDblUnderline(BoolValue value) {#setDblUnderline-com.aspose.diagram.BoolValue-}
```
public void setDblUnderline(BoolValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getDblUnderline()](../../com.aspose.diagram/char\#getDblUnderline--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getDel()](../../com.aspose.diagram/char\#getDel--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setDoubleStrikethrough(BoolValue value) {#setDoubleStrikethrough-com.aspose.diagram.BoolValue-}
```
public void setDoubleStrikethrough(BoolValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getDoubleStrikethrough()](../../com.aspose.diagram/char\#getDoubleStrikethrough--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setFont(IntValue value) {#setFont-com.aspose.diagram.IntValue-}
```
public void setFont(IntValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getFont()](../../com.aspose.diagram/char\#getFont--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setFontName(StrValue value) {#setFontName-com.aspose.diagram.StrValue-}
```
public void setFontName(StrValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getFontName()](../../com.aspose.diagram/char\#getFontName--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [StrValue](../../com.aspose.diagram/strvalue) |  |

### setFontScale(DoubleValue value) {#setFontScale-com.aspose.diagram.DoubleValue-}
```
public void setFontScale(DoubleValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getFontScale()](../../com.aspose.diagram/char\#getFontScale--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setHighlight(BoolValue value) {#setHighlight-com.aspose.diagram.BoolValue-}
```
public void setHighlight(BoolValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getHighlight()](../../com.aspose.diagram/char\#getHighlight--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getIX()](../../com.aspose.diagram/char\#getIX--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setLangID(IntValue value) {#setLangID-com.aspose.diagram.IntValue-}
```
public void setLangID(IntValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getLangID()](../../com.aspose.diagram/char\#getLangID--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setLetterspace(DoubleValue value) {#setLetterspace-com.aspose.diagram.DoubleValue-}
```
public void setLetterspace(DoubleValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getLetterspace()](../../com.aspose.diagram/char\#getLetterspace--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setLocale(StrValue value) {#setLocale-com.aspose.diagram.StrValue-}
```
public void setLocale(StrValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getLocale()](../../com.aspose.diagram/char\#getLocale--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [StrValue](../../com.aspose.diagram/strvalue) |  |

### setLocalizeFont(LocalizeFont value) {#setLocalizeFont-com.aspose.diagram.LocalizeFont-}
```
public void setLocalizeFont(LocalizeFont value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getLocalizeFont()](../../com.aspose.diagram/char\#getLocalizeFont--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [LocalizeFont](../../com.aspose.diagram/localizefont) |  |

### setOverline(BoolValue value) {#setOverline-com.aspose.diagram.BoolValue-}
```
public void setOverline(BoolValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getOverline()](../../com.aspose.diagram/char\#getOverline--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setPerpendicular(StrValue value) {#setPerpendicular-com.aspose.diagram.StrValue-}
```
public void setPerpendicular(StrValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getPerpendicular()](../../com.aspose.diagram/char\#getPerpendicular--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [StrValue](../../com.aspose.diagram/strvalue) |  |

### setPos(Pos value) {#setPos-com.aspose.diagram.Pos-}
```
public void setPos(Pos value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getPos()](../../com.aspose.diagram/char\#getPos--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Pos](../../com.aspose.diagram/pos) |  |

### setRTLText(BoolValue value) {#setRTLText-com.aspose.diagram.BoolValue-}
```
public void setRTLText(BoolValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getRTLText()](../../com.aspose.diagram/char\#getRTLText--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setSize(DoubleValue value) {#setSize-com.aspose.diagram.DoubleValue-}
```
public void setSize(DoubleValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getSize()](../../com.aspose.diagram/char\#getSize--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setStrikethru(BoolValue value) {#setStrikethru-com.aspose.diagram.BoolValue-}
```
public void setStrikethru(BoolValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getStrikethru()](../../com.aspose.diagram/char\#getStrikethru--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setStyle(Style value) {#setStyle-com.aspose.diagram.Style-}
```
public void setStyle(Style value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getStyle()](../../com.aspose.diagram/char\#getStyle--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Style](../../com.aspose.diagram/style) |  |

### setUseVertical(BoolValue value) {#setUseVertical-com.aspose.diagram.BoolValue-}
```
public void setUseVertical(BoolValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getUseVertical()](../../com.aspose.diagram/char\#getUseVertical--)

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

