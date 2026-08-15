---
title: رخصة
second_title: Aspose.Diagram لـ Java API Reference
description: يوفر طرقًا لترخيص المكوّن.
type: docs
weight: 219
url: /ar/java/com.aspose.diagram/license/
---

**Inheritance:**
java.lang.Object
```
public class License
```

يوفر طرقًا لترخيص المكوّن.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [License()](#License--) | يُنشئ مثيلاً جديدًا لهذه الفئة. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | يُرخص المكوّن. |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | يُرخص المكوّن. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### License() {#License--}
```
public License()
```


يُنشئ مثيلاً جديدًا لهذه الفئة.

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




### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public void setLicense(InputStream stream)
```


يُرخص المكوّن.

استخدم هذه الطريقة لتحميل رخصة من تدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | java.io.InputStream | تدفق يحتوي على الرخصة. |

### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public void setLicense(String licenseName)
```


يُرخص المكوّن.

يحاول العثور على الرخصة في المواقع التالية:

1. مسار صريح.

2. مجلد تجميع المكوّن.

3. مجلد تجميع الاستدعاء الخاص بالعميل.

4. مجلد تجميع الدخول.

5. مورد مدمج في تجميع الاستدعاء الخاص بالعميل.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. مسار صريح.

2. مورد مدمج في تجميع الاستدعاء الخاص بالعميل.

2. مجلد ملف jar الخاص بالمكوّن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| licenseName | java.lang.String |  |

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

