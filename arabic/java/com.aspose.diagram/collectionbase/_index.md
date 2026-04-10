---
title: CollectionBase
second_title: Aspose.Diagram لـ Java API Reference
description: يوفر الفئة الأساسية المجردة لمجموعة ذات نوعية قوية.
type: docs
weight: 50
url: /ar/java/com.aspose.diagram/collectionbase/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public abstract class CollectionBase implements Iterable
```

يوفر الفئة الأساسية المجردة لمجموعة ذات نوعية قوية.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [CollectionBase()](#CollectionBase--) | يقوم بإنشاء نسخة جديدة من فئة CollectionBase بسعة أولية افتراضية. |
| [CollectionBase(int capacity)](#CollectionBase-int-) | يقوم بإنشاء نسخة جديدة من فئة CollectionBase بالسعة المحددة. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [add(Object o)](#add-java.lang.Object-) | يضيف عنصرًا إلى نسخة CollectionBase. |
| [clear()](#clear--) | يزيل جميع الكائنات من نسخة CollectionBase. |
| [contains(Object o)](#contains-java.lang.Object-) | إرجاع ما إذا كانت النسخة تحتوي على هذا الكائن |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int index)](#get-int-) | احصل على عنصر في الموضع المحدد. |
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
### CollectionBase() {#CollectionBase--}
```
public CollectionBase()
```


يقوم بإنشاء نسخة جديدة من فئة CollectionBase بسعة أولية افتراضية.

### CollectionBase(int capacity) {#CollectionBase-int-}
```
public CollectionBase(int capacity)
```


يقوم بإنشاء نسخة جديدة من فئة CollectionBase بالسعة المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| السعة | int | عدد العناصر التي يمكن للقائمة الجديدة تخزينها مبدئيًا. |

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
### get(int index) {#get-int-}
```
public Object get(int index)
```


احصل على عنصر في الموضع المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| فهرس | int | فهرس الموضع المحدد. |

**Returns:**
java.lang.Object - العنصر في الموضع المحدد.
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

