---
title: Para
second_title: Aspose.Diagram لـ Java API Reference
description: يحتوي على عناصر تنسيق الفقرات لنص الأشكال مثل المسافات البادئة وتباعد الأسطر والنقاط ومحاذاة الفقرات أفقياً.
type: docs
weight: 274
url: /ar/java/com.aspose.diagram/para/
---

**Inheritance:**
java.lang.Object
```
public class Para
```

يحتوي على عناصر تنسيق الفقرات لنص الشكل، مثل المسافات البادئة، تباعد الأسطر، القوائم النقطية، والمحاذاة الأفقية للفقرات.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Para()](#Para--) | منشئ. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [deepClone()](#deepClone--) | ينشئ نسخة عميقة من هذه المثيلة. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBullet()](#getBullet--) | يحدد نمط الرصاصة. |
| [getBulletFont()](#getBulletFont--) | يمثل رقم الخط المستخدم لتنسيق النص عندما يتم تحديد سلسلة نقط مخصصة وتكون القيمة في عنصر Bullet غير صفرية. |
| [getBulletFontSize()](#getBulletFontSize--) | يحدد حجم النقطة. |
| [getBulletStr()](#getBulletStr--) | "يُستخدم لإنشاء نمط نقطة مخصص. |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | علامة تشير إلى ما إذا تم حذف العنصر محليًا. |
| [getFlags()](#getFlags--) | يشير إلى ما إذا كان اتجاه النص من اليسار إلى اليمين أو من اليمين إلى اليسار. |
| [getHorzAlign()](#getHorzAlign--) | يحدد محاذاة النص الأفقية في كتلة نص الشكل. |
| [getIX()](#getIX--) | فهرس العنصر داخل العنصر الأصل بدءًا من الصفر. |
| [getIndFirst()](#getIndFirst--) | يحدد المسافة التي يتم فيها إزاحة السطر الأول من كل فقرة في كتلة نص الشكل من المسافة اليسرى للفقرة. |
| [getIndLeft()](#getIndLeft--) | يحدد المسافة التي يتم فيها إزاحة جميع أسطر النص في الفقرة من الهامش الأيسر لكتلة النص. |
| [getIndRight()](#getIndRight--) | يحدد المسافة التي يتم إزاحة جميع أسطر النص في الفقرة منها عن الهامش الأيمن لكتلة النص. |
| [getLocalizeBulletFont()](#getLocalizeBulletFont--) | يحدد ما إذا كان يجب تعريب خط الرصاص (ترجمته إلى لغة أخرى). |
| [getSpAfter()](#getSpAfter--) | يحدد مقدار المسافة التي تُضاف بعد كل فقرة في كتلة نص الشكل. |
| [getSpBefore()](#getSpBefore--) | يحدد مقدار المسافة التي تُضاف قبل كل فقرة في كتلة نص الشكل. |
| [getSpLine()](#getSpLine--) | يحدد المسافة بين سطر نص وآخر، حيث 100٪ تمثل ارتفاع سطر النص. |
| [getTextPosAfterBullet()](#getTextPosAfterBullet--) | يمثل المسافة بين السطر الأول للفقرة والرّصاص. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBullet(Bullet value)](#setBullet-com.aspose.diagram.Bullet-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getBullet()](../../com.aspose.diagram/para\#getBullet--) |
| [setBulletFont(IntValue value)](#setBulletFont-com.aspose.diagram.IntValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getBulletFont()](../../com.aspose.diagram/para\#getBulletFont--) |
| [setBulletFontSize(DoubleValue value)](#setBulletFontSize-com.aspose.diagram.DoubleValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getBulletFontSize()](../../com.aspose.diagram/para\#getBulletFontSize--) |
| [setBulletStr(Str2Value value)](#setBulletStr-com.aspose.diagram.Str2Value-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getBulletStr()](../../com.aspose.diagram/para\#getBulletStr--) |
| [setDel(int value)](#setDel-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getDel()](../../com.aspose.diagram/para\#getDel--) |
| [setFlags(BoolValue value)](#setFlags-com.aspose.diagram.BoolValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getFlags()](../../com.aspose.diagram/para\#getFlags--) |
| [setHorzAlign(HorzAlign value)](#setHorzAlign-com.aspose.diagram.HorzAlign-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getHorzAlign()](../../com.aspose.diagram/para\#getHorzAlign--) |
| [setIX(int value)](#setIX-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getIX()](../../com.aspose.diagram/para\#getIX--) |
| [setIndFirst(DoubleValue value)](#setIndFirst-com.aspose.diagram.DoubleValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getIndFirst()](../../com.aspose.diagram/para\#getIndFirst--) |
| [setIndLeft(DoubleValue value)](#setIndLeft-com.aspose.diagram.DoubleValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getIndLeft()](../../com.aspose.diagram/para\#getIndLeft--) |
| [setIndRight(DoubleValue value)](#setIndRight-com.aspose.diagram.DoubleValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getIndRight()](../../com.aspose.diagram/para\#getIndRight--) |
| [setLocalizeBulletFont(LocalizeFont value)](#setLocalizeBulletFont-com.aspose.diagram.LocalizeFont-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getLocalizeBulletFont()](../../com.aspose.diagram/para\#getLocalizeBulletFont--) |
| [setSpAfter(DoubleValue value)](#setSpAfter-com.aspose.diagram.DoubleValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getSpAfter()](../../com.aspose.diagram/para\#getSpAfter--) |
| [setSpBefore(DoubleValue value)](#setSpBefore-com.aspose.diagram.DoubleValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getSpBefore()](../../com.aspose.diagram/para\#getSpBefore--) |
| [setSpLine(DoubleValue value)](#setSpLine-com.aspose.diagram.DoubleValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getSpLine()](../../com.aspose.diagram/para\#getSpLine--) |
| [setTextPosAfterBullet(DoubleValue value)](#setTextPosAfterBullet-com.aspose.diagram.DoubleValue-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getTextPosAfterBullet()](../../com.aspose.diagram/para\#getTextPosAfterBullet--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Para() {#Para--}
```
public Para()
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
### getBullet() {#getBullet--}
```
public Bullet getBullet()
```


يحدد نمط الرصاصة.

**Returns:**
[Bullet](../../com.aspose.diagram/bullet)
### getBulletFont() {#getBulletFont--}
```
public IntValue getBulletFont()
```


يمثل رقم الخط المستخدم لتنسيق النص عندما يتم تحديد سلسلة نقط مخصصة وتكون القيمة في عنصر Bullet غير صفرية.

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getBulletFontSize() {#getBulletFontSize--}
```
public DoubleValue getBulletFontSize()
```


يحدد حجم النقطة.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBulletStr() {#getBulletStr--}
```
public Str2Value getBulletStr()
```


"يُستخدم لإنشاء نمط رصاص مخصص. أدخل النمط كسلسلة نصية (داخل علامات الاقتباس). على سبيل المثال، يمكنك إدخال السلسلة، ""ooo."""

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
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
### getFlags() {#getFlags--}
```
public BoolValue getFlags()
```


يشير إلى ما إذا كان اتجاه النص من اليسار إلى اليمين أو من اليمين إلى اليسار.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getHorzAlign() {#getHorzAlign--}
```
public HorzAlign getHorzAlign()
```


يحدد محاذاة النص الأفقية في كتلة نص الشكل.

**Returns:**
[HorzAlign](../../com.aspose.diagram/horzalign)
### getIX() {#getIX--}
```
public int getIX()
```


فهرس العنصر داخل العنصر الأصل بدءًا من الصفر.

**Returns:**
int
### getIndFirst() {#getIndFirst--}
```
public DoubleValue getIndFirst()
```


يحدد المسافة التي يتم إزاحة السطر الأول من كل فقرة في كتلة نص الشكل عنها من الإزاحة اليسرى للفقرة. هذه القيمة مستقلة عن مقياس الرسم. إذا تم تحجيم الرسم، يبقى إزاحة السطر الأول كما هي.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getIndLeft() {#getIndLeft--}
```
public DoubleValue getIndLeft()
```


يحدد المسافة التي يتم إزاحة جميع أسطر النص في الفقرة عنها من الهامش الأيسر لكتلة النص. هذه القيمة مستقلة عن مقياس الرسم. إذا تم تحجيم الرسم، يبقى الإزاحة اليسرى كما هي.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getIndRight() {#getIndRight--}
```
public DoubleValue getIndRight()
```


يحدد المسافة التي تُزاح جميع أسطر النص في الفقرة من الهامش الأيمن لكتلة النص. هذه القيمة مستقلة عن مقياس الرسم. إذا تم تحجيم الرسم، يظل الإزاحة اليمنى كما هي.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLocalizeBulletFont() {#getLocalizeBulletFont--}
```
public LocalizeFont getLocalizeBulletFont()
```


يحدد ما إذا كان يجب تعريب خط الرصاص (ترجمته إلى لغة أخرى).

**Returns:**
[LocalizeFont](../../com.aspose.diagram/localizefont)
### getSpAfter() {#getSpAfter--}
```
public DoubleValue getSpAfter()
```


يحدد مقدار المسافة التي تُضاف بعد كل فقرة في كتلة نص الشكل.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getSpBefore() {#getSpBefore--}
```
public DoubleValue getSpBefore()
```


يحدد مقدار المسافة التي تُضاف قبل كل فقرة في كتلة نص الشكل.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getSpLine() {#getSpLine--}
```
public DoubleValue getSpLine()
```


يحدد المسافة بين سطر نص وآخر، حيث 100٪ تمثل ارتفاع سطر النص.

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTextPosAfterBullet() {#getTextPosAfterBullet--}
```
public DoubleValue getTextPosAfterBullet()
```


يمثل المسافة بين السطر الأول للفقرة والرّصاص.

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




### setBullet(Bullet value) {#setBullet-com.aspose.diagram.Bullet-}
```
public void setBullet(Bullet value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getBullet()](../../com.aspose.diagram/para\#getBullet--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Bullet](../../com.aspose.diagram/bullet) |  |

### setBulletFont(IntValue value) {#setBulletFont-com.aspose.diagram.IntValue-}
```
public void setBulletFont(IntValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getBulletFont()](../../com.aspose.diagram/para\#getBulletFont--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setBulletFontSize(DoubleValue value) {#setBulletFontSize-com.aspose.diagram.DoubleValue-}
```
public void setBulletFontSize(DoubleValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getBulletFontSize()](../../com.aspose.diagram/para\#getBulletFontSize--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setBulletStr(Str2Value value) {#setBulletStr-com.aspose.diagram.Str2Value-}
```
public void setBulletStr(Str2Value value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getBulletStr()](../../com.aspose.diagram/para\#getBulletStr--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Str2Value](../../com.aspose.diagram/str2value) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getDel()](../../com.aspose.diagram/para\#getDel--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setFlags(BoolValue value) {#setFlags-com.aspose.diagram.BoolValue-}
```
public void setFlags(BoolValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getFlags()](../../com.aspose.diagram/para\#getFlags--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setHorzAlign(HorzAlign value) {#setHorzAlign-com.aspose.diagram.HorzAlign-}
```
public void setHorzAlign(HorzAlign value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getHorzAlign()](../../com.aspose.diagram/para\#getHorzAlign--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [HorzAlign](../../com.aspose.diagram/horzalign) |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getIX()](../../com.aspose.diagram/para\#getIX--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setIndFirst(DoubleValue value) {#setIndFirst-com.aspose.diagram.DoubleValue-}
```
public void setIndFirst(DoubleValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getIndFirst()](../../com.aspose.diagram/para\#getIndFirst--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setIndLeft(DoubleValue value) {#setIndLeft-com.aspose.diagram.DoubleValue-}
```
public void setIndLeft(DoubleValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getIndLeft()](../../com.aspose.diagram/para\#getIndLeft--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setIndRight(DoubleValue value) {#setIndRight-com.aspose.diagram.DoubleValue-}
```
public void setIndRight(DoubleValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getIndRight()](../../com.aspose.diagram/para\#getIndRight--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setLocalizeBulletFont(LocalizeFont value) {#setLocalizeBulletFont-com.aspose.diagram.LocalizeFont-}
```
public void setLocalizeBulletFont(LocalizeFont value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getLocalizeBulletFont()](../../com.aspose.diagram/para\#getLocalizeBulletFont--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [LocalizeFont](../../com.aspose.diagram/localizefont) |  |

### setSpAfter(DoubleValue value) {#setSpAfter-com.aspose.diagram.DoubleValue-}
```
public void setSpAfter(DoubleValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getSpAfter()](../../com.aspose.diagram/para\#getSpAfter--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setSpBefore(DoubleValue value) {#setSpBefore-com.aspose.diagram.DoubleValue-}
```
public void setSpBefore(DoubleValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getSpBefore()](../../com.aspose.diagram/para\#getSpBefore--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setSpLine(DoubleValue value) {#setSpLine-com.aspose.diagram.DoubleValue-}
```
public void setSpLine(DoubleValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getSpLine()](../../com.aspose.diagram/para\#getSpLine--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setTextPosAfterBullet(DoubleValue value) {#setTextPosAfterBullet-com.aspose.diagram.DoubleValue-}
```
public void setTextPosAfterBullet(DoubleValue value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getTextPosAfterBullet()](../../com.aspose.diagram/para\#getTextPosAfterBullet--)

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

