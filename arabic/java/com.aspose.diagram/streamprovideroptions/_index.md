---
title: StreamProviderOptions
second_title: Aspose.Diagram لـ Java API Reference
description: يمثل خيارات الدفق.
type: docs
weight: 390
url: /ar/java/com.aspose.diagram/streamprovideroptions/
---

**Inheritance:**
java.lang.Object
```
public class StreamProviderOptions
```

يمثل خيارات الدفق.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [StreamProviderOptions()](#StreamProviderOptions--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultPath()](#getDefaultPath--) | المسار الافتراضي (URL) المحفوظ في ملف HTML المُولد للمصدر المشار إليه. |
| [getStream()](#getStream--) | يحصل/يضبط تدفق الإخراج لكتابة البيانات المحفوظة |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomPath(String value)](#setCustomPath-java.lang.String-) | المسار المخصص (URL) للمستخدم المحفوظ في ملف HTML المُولد للمصدر المشار إليه. |
| [setStream(OutputStream value)](#setStream-java.io.OutputStream-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getStream()](../../com.aspose.diagram/streamprovideroptions\#getStream--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StreamProviderOptions() {#StreamProviderOptions--}
```
public StreamProviderOptions()
```


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
### getDefaultPath() {#getDefaultPath--}
```
public String getDefaultPath()
```


المسار الافتراضي (URL) المحفوظ في ملف HTML المُولد للمصدر المشار إليه. على سبيل المثال، يتم حفظ بيانات الورقة في xxx\_files/sheet001.htm، يجب أن يكون عنوان URL المستخدم في ملف HTML الرئيسي مثل "src=\"xxx\_files/sheet001.htm\""

**Returns:**
java.lang.String
### getStream() {#getStream--}
```
public OutputStream getStream()
```


يحصل/يضبط تدفق الإخراج لكتابة البيانات المحفوظة

**Returns:**
java.io.OutputStream
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




### setCustomPath(String value) {#setCustomPath-java.lang.String-}
```
public void setCustomPath(String value)
```


المسار المخصص (URL) للمستخدم المحفوظ في ملف HTML المُولد للمصدر المشار إليه. إذا لم يحدده المستخدم، سيتم استخدام DefaultPath. على سبيل المثال، سيقوم المستخدم بحفظ بيانات الورقة إلى d:/sheet001.htm، يجب أن يكون عنوان URL المستخدم في ملف HTML الرئيسي "d:/sheet001.htm" أو أي مسار نسبي صالح يمكن الوصول إليه من ملف HTML الرئيسي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### setStream(OutputStream value) {#setStream-java.io.OutputStream-}
```
public void setStream(OutputStream value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getStream()](../../com.aspose.diagram/streamprovideroptions\#getStream--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.io.OutputStream |  |

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

