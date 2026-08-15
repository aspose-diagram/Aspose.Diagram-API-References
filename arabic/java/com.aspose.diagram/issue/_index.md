---
title: Issue
second_title: Aspose.Diagram لـ Java API Reference
description: يمثل مشكلة تحقق واحدة في المستند.
type: docs
weight: 208
url: /ar/java/com.aspose.diagram/issue/
---

**Inheritance:**
java.lang.Object
```
public class Issue
```

يمثل مشكلة تحقق واحدة في المستند.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Issue()](#Issue--) | منشئ |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getID()](#getID--) | يحدد المعرف الفريد لمشكلة التحقق. |
| [getIgnored()](#getIgnored--) | يحدد ما إذا كانت مشكلة التحقق مُتجاهلة حاليًا. |
| [getIssueTarget()](#getIssueTarget--) | اعتمادًا على هدف مشكلة التحقق الأصلية، يحدد إما الصفحة، أو كلًا من الصفحة والشكل الذي ترتبط به مشكلة التحقق الأصلية. |
| [getRuleInfo()](#getRuleInfo--) | يحدد معلومات حول قاعدة التحقق التي تتعلق بها مشكلة التحقق الأصلية. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setID(long value)](#setID-long-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getID()](../../com.aspose.diagram/issue\#getID--) |
| [setIgnored(int value)](#setIgnored-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getIgnored()](../../com.aspose.diagram/issue\#getIgnored--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Issue() {#Issue--}
```
public Issue()
```


منشئ

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
### getID() {#getID--}
```
public long getID()
```


يحدد المعرف الفريد لمشكلة التحقق.

**Returns:**
long
### getIgnored() {#getIgnored--}
```
public int getIgnored()
```


يحدد ما إذا كانت مشكلة التحقق مُتجاهلة حاليًا. القيمة الافتراضية هي False.

**Returns:**
int
### getIssueTarget() {#getIssueTarget--}
```
public IssueTarget getIssueTarget()
```


اعتمادًا على هدف مشكلة التحقق الأصلية، يحدد إما الصفحة أو كلًا من الصفحة والشكل المرتبط بمشكلة التحقق الأصلية. إذا كان هدف مشكلة التحقق الأصلية هو مستند، فإن IssueTarget لا يحدد صفحة ولا شكل.

**Returns:**
[IssueTarget](../../com.aspose.diagram/issuetarget)
### getRuleInfo() {#getRuleInfo--}
```
public RuleInfo getRuleInfo()
```


يحدد معلومات حول قاعدة التحقق التي تتعلق بها مشكلة التحقق الأصلية.

**Returns:**
[RuleInfo](../../com.aspose.diagram/ruleinfo)
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




### setID(long value) {#setID-long-}
```
public void setID(long value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getID()](../../com.aspose.diagram/issue\#getID--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | long |  |

### setIgnored(int value) {#setIgnored-int-}
```
public void setIgnored(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getIgnored()](../../com.aspose.diagram/issue\#getIgnored--)

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

