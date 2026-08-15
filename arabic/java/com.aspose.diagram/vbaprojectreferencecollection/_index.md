---
title: VbaProjectReferenceCollection
second_title: Aspose.Diagram لـ Java API Reference
description: يمثل جميع مراجع مشروع VBA.
type: docs
weight: 435
url: /ar/java/com.aspose.diagram/vbaprojectreferencecollection/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.CollectionBase](../../com.aspose.diagram/collectionbase)
```
public class VbaProjectReferenceCollection extends CollectionBase
```

يمثل جميع مراجع مشروع VBA.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [add(Object o)](#add-java.lang.Object-) | يضيف عنصرًا إلى نسخة CollectionBase. |
| [addControlRefrernce(String name, String libid, String twiddledlibid, String extendedLibid)](#addControlRefrernce-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | أضف مرجعًا إلى مكتبة نوع مُعدلة ومكتبة النوع الموسعة الخاصة بها. |
| [addProjectRefrernce(String name, String absoluteLibid, String relativeLibid)](#addProjectRefrernce-java.lang.String-java.lang.String-java.lang.String-) | أضف مرجعًا إلى مشروع VBA خارجي. |
| [addRegisteredReference(String name, String libid)](#addRegisteredReference-java.lang.String-java.lang.String-) | أضف مرجعًا إلى مكتبة نوع Automation. |
| [clear()](#clear--) | يزيل جميع الكائنات من نسخة CollectionBase. |
| [contains(Object o)](#contains-java.lang.Object-) | إرجاع ما إذا كانت النسخة تحتوي على هذا الكائن |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int i)](#get-int-) | احصل على المرجع في القائمة حسب الفهرس. |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | يحصل على عدد العناصر الموجودة في نسخة CollectionBase. |
| [hashCode()](#hashCode--) |  |
| [indexOf(Object o)](#indexOf-java.lang.Object-) | يحدد فهرس عنصر معين في نسخة CollectionBase. |
| [iterator()](#iterator--) | يرجع عدادًا يتكرر عبر نسخة CollectionBase. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeAt(int index)](#removeAt-int-) | يزيل العنصر في الفهرس المحدد. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(Object o) {#add-java.lang.Object-}
```
public int add(Object o)
```


يضيف عنصرًا إلى نسخة CollectionBase.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| o | java.lang.Object | الكائن لإضافته إلى نسخة CollectionBase. |

**Returns:**
int - الموضع الذي تم إدراج العنصر الجديد فيه.
### addControlRefrernce(String name, String libid, String twiddledlibid, String extendedLibid) {#addControlRefrernce-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
```
public int addControlRefrernce(String name, String libid, String twiddledlibid, String extendedLibid)
```


أضف مرجعًا إلى مكتبة نوع مُعدلة ومكتبة النوع الموسعة الخاصة بها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم المرجع. |
| libid | java.lang.String | معرف مكتبة نوع Automation. |
| twiddledlibid | java.lang.String | معرف مكتبة نوع مُعدلة. |
| extendedLibid | java.lang.String | معرّف مكتبة النوع الموسّعة |

**Returns:**
int -
### addProjectRefrernce(String name, String absoluteLibid, String relativeLibid) {#addProjectRefrernce-java.lang.String-java.lang.String-java.lang.String-}
```
public int addProjectRefrernce(String name, String absoluteLibid, String relativeLibid)
```


أضف مرجعًا إلى مشروع VBA خارجي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم المرجع. |
| absoluteLibid | java.lang.String | معرّف مشروع VBA المشار إليه\u9225\u6a9a بمسار مطلق. |
| relativeLibid | java.lang.String | معرّف مشروع VBA المشار إليه\u9225\u6a9a بمسار نسبي. |

**Returns:**
int -
### addRegisteredReference(String name, String libid) {#addRegisteredReference-java.lang.String-java.lang.String-}
```
public int addRegisteredReference(String name, String libid)
```


أضف مرجعًا إلى مكتبة نوع Automation.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم المرجع. |
| libid | java.lang.String | معرف مكتبة نوع Automation. |

**Returns:**
int -
### clear() {#clear--}
```
public void clear()
```


يزيل جميع الكائنات من نسخة CollectionBase.

### contains(Object o) {#contains-java.lang.Object-}
```
public boolean contains(Object o)
```


إرجاع ما إذا كانت النسخة تحتوي على هذا الكائن

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| o | java.lang.Object | كائن اختبار |

**Returns:**
boolean - ما إذا كان المثيل يحتوي على هذا الكائن
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
### get(int i) {#get-int-}
```
public VbaProjectReference get(int i)
```


احصل على المرجع في القائمة حسب الفهرس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| i | int | الفهرس. |

**Returns:**
[VbaProjectReference](../../com.aspose.diagram/vbaprojectreference) - 
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public int getCount()
```


يحصل على عدد العناصر الموجودة في نسخة CollectionBase.

**Returns:**
int - عدد العناصر الموجودة في مثيل CollectionBase.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### indexOf(Object o) {#indexOf-java.lang.Object-}
```
public int indexOf(Object o)
```


يحدد فهرس عنصر معين في نسخة CollectionBase.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| o | java.lang.Object | يحدد فهرس عنصر معين في نسخة CollectionBase. |

**Returns:**
int - فهرس القيمة إذا تم العثور عليها في القائمة؛ وإلا، -1.
### iterator() {#iterator--}
```
public Iterator iterator()
```


يرجع عدادًا يتكرر عبر نسخة CollectionBase.

**Returns:**
java.util.Iterator - مكرّر (iterator) لمثيل CollectionBase.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeAt(int index) {#removeAt-int-}
```
public void removeAt(int index)
```


يزيل العنصر في الفهرس المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| فهرس | int | فهرس العنصر المراد إزالته بدءًا من الصفر. |

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

