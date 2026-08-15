---
title: Encoding
second_title: Aspose.Diagram لـ Java API Reference
description: يمثل ترميز الأحرف.
type: docs
weight: 143
url: /ar/java/com.aspose.diagram/encoding/
---

**Inheritance:**
java.lang.Object
```
public class Encoding
```

يمثل ترميز الأحرف.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Encoding()](#Encoding--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Encoding other)](#equals-com.aspose.diagram.Encoding-) | يحدد ما إذا كان كائن Encoding المحدد يساوي المثيل الحالي. |
| [equals(Object o)](#equals-java.lang.Object-) | يحدد ما إذا كان الكائن المحدد يساوي المثيل الحالي. |
| [getASCII()](#getASCII--) | يحصل على ترميز لمجموعة الأحرف ASCII (7 بت). |
| [getBigEndianUnicode()](#getBigEndianUnicode--) | يحصل على ترميز لتنسيق UTF-16 باستخدام ترتيب البايتات كبير النهاية. |
| [getClass()](#getClass--) |  |
| [getDefault()](#getDefault--) | يحصل على ترميز لصفحة الشيفرة ANSI الحالية لنظام التشغيل. |
| [getEncoding(int codePage)](#getEncoding-int-) | يرجع الترميز المرتبط بمعرف صفحة الشيفرة المحدد. |
| [getEncoding(String charsetName)](#getEncoding-java.lang.String-) | يرجع ترميزًا مرتبطًا باسم مجموعة الأحرف المحدد. |
| [getEncoding(Charset charset)](#getEncoding-java.nio.charset.Charset-) | يرجع ترميزًا مرتبطًا بكائن مجموعة الأحرف المحدد. |
| [getUTF7()](#getUTF7--) | يحصل على ترميز لتنسيق UTF-7. |
| [getUTF8()](#getUTF8--) | يحصل على ترميز لتنسيق UTF-8. |
| [getUTF8NoBOM()](#getUTF8NoBOM--) | يحصل على ترميز لتنسيق UTF-8 بدون معرف UTF-8. |
| [getUnicode()](#getUnicode--) | يحصل على ترميز لتنسيق UTF-16 باستخدام ترتيب البايتات صغير النهاية. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Encoding() {#Encoding--}
```
public Encoding()
```


### equals(Encoding other) {#equals-com.aspose.diagram.Encoding-}
```
public boolean equals(Encoding other)
```


يحدد ما إذا كان كائن Encoding المحدد يساوي المثيل الحالي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| other | [Encoding](../../com.aspose.diagram/encoding) | كائن Encoding للمقارنة مع المثيل الحالي. |

**Returns:**
boolean - true إذا كانت القيمة تساوي المثيل الحالي؛ وإلا false.
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


يحدد ما إذا كان الكائن المحدد يساوي المثيل الحالي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| o | java.lang.Object | الكائن للمقارنة مع المثيل الحالي. |

**Returns:**
منطقي - true إذا كانت القيمة مثيلًا لـ Encoding وتساوي المثيل الحالي؛ وإلا false.
### getASCII() {#getASCII--}
```
public static Encoding getASCII()
```


يحصل على ترميز لمجموعة الأحرف ASCII (7 بت).

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - A Encoding object for the ASCII (7-bit) character set.
### getBigEndianUnicode() {#getBigEndianUnicode--}
```
public static Encoding getBigEndianUnicode()
```


يحصل على ترميز لتنسيق UTF-16 باستخدام ترتيب البايتات كبير النهاية.

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - A Encoding object for the UTF-16 format using the big endian byte
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefault() {#getDefault--}
```
public static Encoding getDefault()
```


يحصل على ترميز لصفحة الشيفرة ANSI الحالية لنظام التشغيل.

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - An encoding for the operating system's current ANSI code page.
### getEncoding(int codePage) {#getEncoding-int-}
```
public static Encoding getEncoding(int codePage)
```


يرجع الترميز المرتبط بمعرف صفحة الشيفرة المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| codePage | int | معرّف صفحة الترميز للترميز المفضّل. -or- 0، لاستخدام الترميز الافتراضي. |

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - The Encoding object associated with the specified code page.
### getEncoding(String charsetName) {#getEncoding-java.lang.String-}
```
public static Encoding getEncoding(String charsetName)
```


يرجع ترميزًا مرتبطًا باسم مجموعة الأحرف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| charsetName | java.lang.String | اسم مجموعة الأحرف المحدد |

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - The Encoding object associated with the specified charset name.
### getEncoding(Charset charset) {#getEncoding-java.nio.charset.Charset-}
```
public static Encoding getEncoding(Charset charset)
```


يرجع ترميزًا مرتبطًا بكائن مجموعة الأحرف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| charset | java.nio.charset.Charset | كائن مجموعة الأحرف المحدد |

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - The Encoding object associated with the specified charset object.
### getUTF7() {#getUTF7--}
```
public static Encoding getUTF7()
```


يحصل على ترميز لتنسيق UTF-7.

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - A Encoding object for the UTF-7 format.
### getUTF8() {#getUTF8--}
```
public static Encoding getUTF8()
```


يحصل على ترميز لتنسيق UTF-8.

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - A Encoding object for the UTF-8 format.
### getUTF8NoBOM() {#getUTF8NoBOM--}
```
public static Encoding getUTF8NoBOM()
```


يحصل على ترميز لتنسيق UTF-8 بدون معرف UTF-8.

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - A Encoding object for the UTF-8 format without UTF-8 identifier.
### getUnicode() {#getUnicode--}
```
public static Encoding getUnicode()
```


يحصل على ترميز لتنسيق UTF-16 باستخدام ترتيب البايتات صغير النهاية.

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - A Encoding object for the UTF-16 format using the little endian byte
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

