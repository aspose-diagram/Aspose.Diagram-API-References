---
title: Rule
second_title: Aspose.Diagram لـ Java API Reference
description: يمثل قاعدة تحقق واحدة في مجموعة قواعد تحقق المخطط.
type: docs
weight: 338
url: /ar/java/com.aspose.diagram/rule/
---

**Inheritance:**
java.lang.Object
```
public class Rule
```

يمثل قاعدة تحقق واحدة في مجموعة قواعد تحقق المخطط.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Rule()](#Rule--) | منشئ. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCategory()](#getCategory--) | يحدد النص المعروض في عمود الفئة في نافذة المشكلات. |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | وصف قاعدة التحقق التي تظهر في واجهة المستخدم. |
| [getID()](#getID--) | يحدد المعرف الفريد لقاعدة التحقق. |
| [getIgnored()](#getIgnored--) | يحدد ما إذا كانت قاعدة التحقق مُتجاهلة حاليًا. |
| [getNameU()](#getNameU--) | يحدد الاسم العام لقاعدة التحقق. |
| [getRuleFilter()](#getRuleFilter--) | يحدد التعبير المنطقي الذي يحدد ما إذا كان يجب تطبيق قاعدة التحقق على كائن الهدف. |
| [getRuleTarget()](#getRuleTarget--) | يحدد نوع الكائن الذي تنطبق عليه قاعدة التحقق. |
| [getRuleTest()](#getRuleTest--) | يحدد التعبير المنطقي الذي يحدد ما إذا كان كائن الهدف يفي بقاعدة التحقق |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCategory(String value)](#setCategory-java.lang.String-) | لوصف هذه الخاصية، يرجى الاطلاع على [getCategory()](../../com.aspose.diagram/rule\#getCategory--) |
| [setDescription(String value)](#setDescription-java.lang.String-) | لوصف هذه الخاصية، يرجى الاطلاع على [getDescription()](../../com.aspose.diagram/rule\#getDescription--) |
| [setID(long value)](#setID-long-) | لوصف هذه الخاصية، يرجى الاطلاع على [getID()](../../com.aspose.diagram/rule\#getID--) |
| [setIgnored(int value)](#setIgnored-int-) | لوصف هذه الخاصية، يرجى الاطلاع على [getIgnored()](../../com.aspose.diagram/rule\#getIgnored--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | لوصف هذه الخاصية، يرجى الاطلاع على [getNameU()](../../com.aspose.diagram/rule\#getNameU--) |
| [setRuleFilter(RuleValue value)](#setRuleFilter-com.aspose.diagram.RuleValue-) | لوصف هذه الخاصية، يرجى الاطلاع على [getRuleFilter()](../../com.aspose.diagram/rule\#getRuleFilter--) |
| [setRuleTarget(int value)](#setRuleTarget-int-) | لوصف هذه الخاصية، يرجى الاطلاع على [getRuleTarget()](../../com.aspose.diagram/rule\#getRuleTarget--) |
| [setRuleTest(RuleValue value)](#setRuleTest-com.aspose.diagram.RuleValue-) | لوصف هذه الخاصية، يرجى الاطلاع على [getRuleTest()](../../com.aspose.diagram/rule\#getRuleTest--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Rule() {#Rule--}
```
public Rule()
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
### getCategory() {#getCategory--}
```
public String getCategory()
```


يحدد النص المعروض في عمود الفئة في نافذة المشكلات. القيمة الافتراضية هي سلسلة فارغة.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDescription() {#getDescription--}
```
public String getDescription()
```


وصف قاعدة التحقق التي تظهر في واجهة المستخدم. القيمة الافتراضية هي "Unknown".

**Returns:**
java.lang.String
### getID() {#getID--}
```
public long getID()
```


يحدد المعرف الفريد لقاعدة التحقق.

**Returns:**
long
### getIgnored() {#getIgnored--}
```
public int getIgnored()
```


يحدد ما إذا كانت قاعدة التحقق مُتجاهلة حاليًا. القيمة الافتراضية هي False.

**Returns:**
int
### getNameU() {#getNameU--}
```
public String getNameU()
```


يحدد الاسم العام لقاعدة التحقق.

**Returns:**
java.lang.String
### getRuleFilter() {#getRuleFilter--}
```
public RuleValue getRuleFilter()
```


يحدد التعبير المنطقي الذي يحدد ما إذا كان يجب تطبيق قاعدة التحقق على كائن الهدف.

**Returns:**
[RuleValue](../../com.aspose.diagram/rulevalue)
### getRuleTarget() {#getRuleTarget--}
```
public int getRuleTarget()
```


يحدد نوع الكائن الذي تنطبق عليه قاعدة التحقق.

**Returns:**
int
### getRuleTest() {#getRuleTest--}
```
public RuleValue getRuleTest()
```


يحدد التعبير المنطقي الذي يحدد ما إذا كان كائن الهدف يفي بقاعدة التحقق

**Returns:**
[RuleValue](../../com.aspose.diagram/rulevalue)
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




### setCategory(String value) {#setCategory-java.lang.String-}
```
public void setCategory(String value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getCategory()](../../com.aspose.diagram/rule\#getCategory--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### setDescription(String value) {#setDescription-java.lang.String-}
```
public void setDescription(String value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getDescription()](../../com.aspose.diagram/rule\#getDescription--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### setID(long value) {#setID-long-}
```
public void setID(long value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getID()](../../com.aspose.diagram/rule\#getID--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | long |  |

### setIgnored(int value) {#setIgnored-int-}
```
public void setIgnored(int value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getIgnored()](../../com.aspose.diagram/rule\#getIgnored--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getNameU()](../../com.aspose.diagram/rule\#getNameU--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### setRuleFilter(RuleValue value) {#setRuleFilter-com.aspose.diagram.RuleValue-}
```
public void setRuleFilter(RuleValue value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getRuleFilter()](../../com.aspose.diagram/rule\#getRuleFilter--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [RuleValue](../../com.aspose.diagram/rulevalue) |  |

### setRuleTarget(int value) {#setRuleTarget-int-}
```
public void setRuleTarget(int value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getRuleTarget()](../../com.aspose.diagram/rule\#getRuleTarget--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setRuleTest(RuleValue value) {#setRuleTest-com.aspose.diagram.RuleValue-}
```
public void setRuleTest(RuleValue value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getRuleTest()](../../com.aspose.diagram/rule\#getRuleTest--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [RuleValue](../../com.aspose.diagram/rulevalue) |  |

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

