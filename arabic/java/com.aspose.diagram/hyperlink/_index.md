---
title: Hyperlink
second_title: Aspose.Diagram لـ Java API Reference
description: يحتوي على عناصر لإنشاء قفزات متعددة بين شكل أو صفحة رسم وصفحة رسم أخرى أو ملف آخر أو موقع ويب.
type: docs
weight: 193
url: /ar/java/com.aspose.diagram/hyperlink/
---

**Inheritance:**
java.lang.Object
```
public class Hyperlink
```

يحتوي على عناصر لإنشاء قفزات متعددة بين شكل أو صفحة رسم وصفحة رسم أخرى، ملف آخر، أو موقع ويب.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Hyperlink()](#Hyperlink--) | منشئ. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [deepClone()](#deepClone--) | ينشئ نسخة عميقة من هذه المثيلة. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAddress()](#getAddress--) | يحدد عنوان URL أو اسم ملف DOS أو مسار UNC للقفز إليه. |
| [getClass()](#getClass--) |  |
| [getDefault()](#getDefault--) | يحدد الارتباط التشعبي الافتراضي لشكل أو صفحة. |
| [getDel()](#getDel--) | علامة تشير إلى ما إذا تم حذف العنصر محليًا. |
| [getDescription()](#getDescription--) | عنصر الوصف يحتوي على سلسلة نصية تصف الارتباط التشعبي. |
| [getExtraInfo()](#getExtraInfo--) | يحتوي على معلومات تُستخدم في حل عنوان URL، مثل إحداثيات خريطة الصورة. |
| [getFrame()](#getFrame--) | يحتوي على اسم الإطار المستهدف عندما يكون Microsoft Visio مفتوحًا كمستند نشط في تطبيق حاوية. |
| [getID()](#getID--) | المعرّف الفريد للعنصر داخل العنصر الأب. |
| [getInvisible()](#getInvisible--) | العنصر غير المرئي يشير إلى ما إذا كان الارتباط التشعبي يظهر في قائمة الاختصار لشكل أو صفحة. |
| [getName()](#getName--) | اسم العنصر. |
| [getNameU()](#getNameU--) | الاسم العام للعنصر. |
| [getNewWindow()](#getNewWindow--) | يحدد ما إذا كان Microsoft Visio يفتح نافذة في موقع جديد عندما يتبع ارتباطًا تشعبيًا لفتح صفحة ويب أو مستند Visio آخر. |
| [getSortKey()](#getSortKey--) | العنصر غير المرئي يشير إلى ما إذا كان الارتباط التشعبي يظهر في قائمة الاختصار لشكل أو صفحة. |
| [getSubAddress()](#getSubAddress--) | يحدد موقعًا داخل المستند الهدف للربط به. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getDel()](../../com.aspose.diagram/hyperlink\#getDel--) |
| [setID(int value)](#setID-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getID()](../../com.aspose.diagram/hyperlink\#getID--) |
| [setName(String value)](#setName-java.lang.String-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getName()](../../com.aspose.diagram/hyperlink\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getNameU()](../../com.aspose.diagram/hyperlink\#getNameU--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Hyperlink() {#Hyperlink--}
```
public Hyperlink()
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
### getAddress() {#getAddress--}
```
public Str2Value getAddress()
```


يحدد عنوان URL أو اسم ملف DOS أو مسار UNC للقفز إليه.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefault() {#getDefault--}
```
public BoolValue getDefault()
```


يحدد الارتباط التشعبي الافتراضي لشكل أو صفحة.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getDel() {#getDel--}
```
public int getDel()
```


علامة تشير إلى ما إذا كان العنصر قد تم حذفه محليًا. القيمة 1 تشير إلى أن العنصر تم حذفه محليًا.

**Returns:**
int
### getDescription() {#getDescription--}
```
public Str2Value getDescription()
```


عنصر الوصف يحتوي على سلسلة نصية تصف الارتباط التشعبي.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getExtraInfo() {#getExtraInfo--}
```
public Str2Value getExtraInfo()
```


يحتوي على معلومات تُستخدم في حل عنوان URL، مثل إحداثيات خريطة الصورة. على سبيل المثال، x=41 y=7 سيحدد إحداثيات خريطة الصورة.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getFrame() {#getFrame--}
```
public Str2Value getFrame()
```


يحتوي على اسم الإطار المستهدف عندما يكون Microsoft Visio مفتوحًا كمستند نشط في تطبيق حاوية. القيمة الافتراضية هي سلسلة فارغة.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getID() {#getID--}
```
public int getID()
```


المعرّف الفريد للعنصر داخل العنصر الأب.

**Returns:**
int
### getInvisible() {#getInvisible--}
```
public BoolValue getInvisible()
```


العنصر غير المرئي يشير إلى ما إذا كان الارتباط التشعبي يظهر في قائمة الاختصار لشكل أو صفحة.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getName() {#getName--}
```
public String getName()
```


اسم العنصر.

**Returns:**
java.lang.String
### getNameU() {#getNameU--}
```
public String getNameU()
```


الاسم العام للعنصر.

**Returns:**
java.lang.String
### getNewWindow() {#getNewWindow--}
```
public BoolValue getNewWindow()
```


يحدد ما إذا كان Microsoft Visio يفتح نافذة في موقع جديد عندما يتبع ارتباطًا تشعبيًا لفتح صفحة ويب أو مستند Visio آخر.

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getSortKey() {#getSortKey--}
```
public Str2Value getSortKey()
```


العنصر غير المرئي يشير إلى ما إذا كان الارتباط التشعبي يظهر في قائمة الاختصار لشكل أو صفحة.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getSubAddress() {#getSubAddress--}
```
public Str2Value getSubAddress()
```


يحدد موقعًا داخل المستند الهدف للربط به.

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
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


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getDel()](../../com.aspose.diagram/hyperlink\#getDel--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getID()](../../com.aspose.diagram/hyperlink\#getID--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getName()](../../com.aspose.diagram/hyperlink\#getName--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getNameU()](../../com.aspose.diagram/hyperlink\#getNameU--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

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

