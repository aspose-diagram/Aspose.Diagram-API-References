---
title: EventItem
second_title: Aspose.Diagram لـ Java API Reference
description: يحتوي على رمز حدث.
type: docs
weight: 145
url: /ar/java/com.aspose.diagram/eventitem/
---

**Inheritance:**
java.lang.Object
```
public class EventItem
```

يُغلف رمز الحدث. عنصر EventItem يمكنه تشغيل إضافة، أو يمكنه إرسال إشعار بالحدث إلى البرنامج المستدعي.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [EventItem()](#EventItem--) | منشئ. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | يحدد رمز الإجراء لعنصر EventItem الأب. لكي يتم حفظ عنصر EventItem في ملف DatadiagramML، يجب أن يكون persistable. |
| [getClass()](#getClass--) |  |
| [getEnabled()](#getEnabled--) | يمثل علامة تشير إلى ما إذا كان الحدث مفعلاً أو معطلاً. |
| [getEventCode()](#getEventCode--) | رمز يشير إلى الحدث الذي يُطلق الإضافة. |
| [getID()](#getID--) | معرّف الحدث. |
| [getTarget()](#getTarget--) | يحدد هدف الحدث. |
| [getTargetArgs()](#getTargetArgs--) | يحدد سلسلة تحتوي على الوسائط التي تُرسل إلى هدف الحدث. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAction(int value)](#setAction-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getAction()](../../com.aspose.diagram/eventitem\#getAction--) |
| [setEnabled(int value)](#setEnabled-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getEnabled()](../../com.aspose.diagram/eventitem\#getEnabled--) |
| [setEventCode(int value)](#setEventCode-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getEventCode()](../../com.aspose.diagram/eventitem\#getEventCode--) |
| [setID(int value)](#setID-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getID()](../../com.aspose.diagram/eventitem\#getID--) |
| [setTarget(String value)](#setTarget-java.lang.String-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getTarget()](../../com.aspose.diagram/eventitem\#getTarget--) |
| [setTargetArgs(String value)](#setTargetArgs-java.lang.String-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getTargetArgs()](../../com.aspose.diagram/eventitem\#getTargetArgs--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EventItem() {#EventItem--}
```
public EventItem()
```


منشئ.

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
### getAction() {#getAction--}
```
public int getAction()
```


يحدد رمز الإجراء لعنصر EventItem الأب. لكي يتم حفظ عنصر EventItem في ملف DatadiagramML، يجب أن يكون persistable. حاليًا، الرمز الإجراء الوحيد الصالح لحدث persistable هو 1 (ONEVENT_ACT_RUNADDON).

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEnabled() {#getEnabled--}
```
public int getEnabled()
```


يمثل علامة تشير إلى ما إذا كان الحدث مفعلاً أو معطلاً.

**Returns:**
int
### getEventCode() {#getEventCode--}
```
public int getEventCode()
```


رمز يشير إلى الحدث الذي يُطلق الإضافة. لمزيد من المعلومات حول رموز الأحداث، راجع رموز الأحداث في مرجع أتمتة Microsoft Visio 2007.

**Returns:**
int
### getID() {#getID--}
```
public int getID()
```


معرّف الحدث.

**Returns:**
int
### getTarget() {#getTarget--}
```
public String getTarget()
```


يحدد هدف الحدث.

**Returns:**
java.lang.String
### getTargetArgs() {#getTargetArgs--}
```
public String getTargetArgs()
```


يحدد سلسلة تحتوي على الوسائط التي تُرسل إلى هدف الحدث.

**Returns:**
java.lang.String
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




### setAction(int value) {#setAction-int-}
```
public void setAction(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getAction()](../../com.aspose.diagram/eventitem\#getAction--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setEnabled(int value) {#setEnabled-int-}
```
public void setEnabled(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getEnabled()](../../com.aspose.diagram/eventitem\#getEnabled--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setEventCode(int value) {#setEventCode-int-}
```
public void setEventCode(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getEventCode()](../../com.aspose.diagram/eventitem\#getEventCode--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getID()](../../com.aspose.diagram/eventitem\#getID--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setTarget(String value) {#setTarget-java.lang.String-}
```
public void setTarget(String value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getTarget()](../../com.aspose.diagram/eventitem\#getTarget--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### setTargetArgs(String value) {#setTargetArgs-java.lang.String-}
```
public void setTargetArgs(String value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getTargetArgs()](../../com.aspose.diagram/eventitem\#getTargetArgs--)

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

