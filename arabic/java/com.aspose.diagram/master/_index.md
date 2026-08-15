---
title: Master
second_title: Aspose.Diagram لـ Java API Reference
description: يحتوي على عناصر تُعرّف القالب الرئيسي للمستند.
type: docs
weight: 240
url: /ar/java/com.aspose.diagram/master/
---

**Inheritance:**
java.lang.Object
```
public class Master
```

يحتوي على عناصر تُعرّف master للوثيقة. الـ master هو شكل على القالب تستخدمه بشكل متكرر لإنشاء رسومات. عندما تقوم بسحب شكل من القالب إلى صفحة الرسم، يتحول الشكل إلى نسخة من ذلك الـ master، وتُدرج نسخة محلية من الـ master في الوثيقة.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Master()](#Master--) | منشئ. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [deepClone()](#deepClone--) | ينشئ نسخة عميقة من هذه المثيلة. |
| [dispose()](#dispose--) | ينفّذ مهامًا محددة من قبل التطبيق مرتبطة بتحرير أو إطلاق أو إعادة ضبط الموارد غير المُدارة. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignName()](#getAlignName--) | يحدد ما إذا كان نص الـ master في نافذة القالب محاذى إلى اليسار أو اليمين أو الوسط. |
| [getBaseID()](#getBaseID--) | معرّف GUID (معرّف عالمي فريد) يحدد الـ master عبر المستندات. |
| [getClass()](#getClass--) |  |
| [getConnects()](#getConnects--) | يحتوي على عنصر Connect لكل اتصال بين شكلين في الرسم. |
| [getHidden()](#getHidden--) | يحدد ما إذا كان الـ master مخفيًا في واجهة المستخدم. |
| [getID()](#getID--) | المعرّف الفريد للعنصر داخل العنصر الأب. |
| [getIcon()](#getIcon--) | يحدد أيقونة ثنائية مُشفّرة بتنسيق MIME (ملحقات الإنترنت المتعددة الأغراض) (بتنسيق .ico) لعنصر Master أو MasterShortcut في المستند. |
| [getIconSize()](#getIconSize--) | حجم أيقونة العنصر. |
| [getIconUpdate()](#getIconUpdate--) | يحدد ما إذا كانت الأيقونة مُولَّدة تلقائيًا من الـ master نفسه. |
| [getMatchByName()](#getMatchByName--) | تحدد خاصية MatchByName كيف يقرر Microsoft Visio ما إذا كان master المستند موجودًا بالفعل عندما يتم إسقاط نسخة من master على صفحة الرسم. |
| [getName()](#getName--) | اسم العنصر. |
| [getNameU()](#getNameU--) | الاسم العام للعنصر. |
| [getPageSheet()](#getPageSheet--) | يحتوي على عناصر تُعرّف ورقة الصفحة لعنصر صفحة أو عنصر رئيسي. |
| [getPatternFlags()](#getPatternFlags--) | تحدد سمة PatternFlags ما إذا كان القالب يتصرف كنمط مخصص. |
| [getPrompt()](#getPrompt--) | شريط الحالة وتلميح الأداة يوضحان العنصر. |
| [getShapes()](#getShapes--) | مجموعة من كائنات Shape. |
| [getUniqueID()](#getUniqueID--) | معرف GUID يحدد القالب داخل المستند. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignName(int value)](#setAlignName-int-) | لوصف هذه الخاصية، يرجى الاطلاع على [getAlignName()](../../com.aspose.diagram/master\#getAlignName--) |
| [setBaseID(UUID value)](#setBaseID-java.util.UUID-) | لوصف هذه الخاصية، يرجى الاطلاع على [getBaseID()](../../com.aspose.diagram/master\#getBaseID--) |
| [setHidden(int value)](#setHidden-int-) | لوصف هذه الخاصية، يرجى الاطلاع على [getHidden()](../../com.aspose.diagram/master\#getHidden--) |
| [setID(int value)](#setID-int-) | لوصف هذه الخاصية، يرجى الاطلاع على [getID()](../../com.aspose.diagram/master\#getID--) |
| [setIcon(byte[] value)](#setIcon-byte---) | لوصف هذه الخاصية، يرجى الاطلاع على [getIcon()](../../com.aspose.diagram/master\#getIcon--) |
| [setIconSize(int value)](#setIconSize-int-) | لوصف هذه الخاصية، يرجى الاطلاع على [getIconSize()](../../com.aspose.diagram/master\#getIconSize--) |
| [setIconUpdate(int value)](#setIconUpdate-int-) | لوصف هذه الخاصية، يرجى الاطلاع على [getIconUpdate()](../../com.aspose.diagram/master\#getIconUpdate--) |
| [setMatchByName(int value)](#setMatchByName-int-) | لوصف هذه الخاصية، يرجى الاطلاع على [getMatchByName()](../../com.aspose.diagram/master\#getMatchByName--) |
| [setName(String value)](#setName-java.lang.String-) | لوصف هذه الخاصية، يرجى الاطلاع على [getName()](../../com.aspose.diagram/master\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | لوصف هذه الخاصية، يرجى الاطلاع على [getNameU()](../../com.aspose.diagram/master\#getNameU--) |
| [setPatternFlags(int value)](#setPatternFlags-int-) | لوصف هذه الخاصية، يرجى الاطلاع على [getPatternFlags()](../../com.aspose.diagram/master\#getPatternFlags--) |
| [setPrompt(String value)](#setPrompt-java.lang.String-) | لوصف هذه الخاصية، يرجى الاطلاع على [getPrompt()](../../com.aspose.diagram/master\#getPrompt--) |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | لوصف هذه الخاصية، يرجى الاطلاع على [getUniqueID()](../../com.aspose.diagram/master\#getUniqueID--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Master() {#Master--}
```
public Master()
```


منشئ.

### deepClone() {#deepClone--}
```
public Object deepClone()
```


ينشئ نسخة عميقة من هذه المثيلة.

**Returns:**
java.lang.Object -
### dispose() {#dispose--}
```
public void dispose()
```


ينفّذ مهامًا محددة من قبل التطبيق مرتبطة بتحرير أو إطلاق أو إعادة ضبط الموارد غير المُدارة.

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
### getAlignName() {#getAlignName--}
```
public int getAlignName()
```


يحدد ما إذا كان نص الـ master في نافذة القالب محاذى إلى اليسار أو اليمين أو الوسط.

**Returns:**
int
### getBaseID() {#getBaseID--}
```
public UUID getBaseID()
```


معرّف GUID (معرّف عالمي فريد) يحدد الـ master عبر المستندات.

**Returns:**
java.util.UUID
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConnects() {#getConnects--}
```
public ConnectCollection getConnects()
```


يحتوي على عنصر Connect لكل اتصال بين شكلين في الرسم.

**Returns:**
[ConnectCollection](../../com.aspose.diagram/connectcollection)
### getHidden() {#getHidden--}
```
public int getHidden()
```


يحدد ما إذا كان الـ master مخفيًا في واجهة المستخدم.

**Returns:**
int
### getID() {#getID--}
```
public int getID()
```


المعرّف الفريد للعنصر داخل العنصر الأب.

**Returns:**
int
### getIcon() {#getIcon--}
```
public byte[] getIcon()
```


يحدد أيقونة ثنائية مُشفّرة بتنسيق MIME (ملحقات الإنترنت المتعددة الأغراض) (بتنسيق .ico) لعنصر Master أو MasterShortcut في المستند.

**Returns:**
byte[]
### getIconSize() {#getIconSize--}
```
public int getIconSize()
```


حجم أيقونة العنصر.

**Returns:**
int
### getIconUpdate() {#getIconUpdate--}
```
public int getIconUpdate()
```


يحدد ما إذا كانت الأيقونة مُولَّدة تلقائيًا من الـ master نفسه.

**Returns:**
int
### getMatchByName() {#getMatchByName--}
```
public int getMatchByName()
```


تحدد سمة MatchByName كيفية اتخاذ Microsoft Visio للقرار إذا كان القالب المستند موجودًا بالفعل عندما يتم إسقاط نسخة من القالب على صفحة الرسم. يسمح ذلك بتطبيق التغييرات التي تُجرى على قالب المستند على النسخ الجديدة من القالب، حتى إذا تم سحب النسخ من ملف قالب مستقل.

**Returns:**
int
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
### getPageSheet() {#getPageSheet--}
```
public PageSheet getPageSheet()
```


يحتوي على عناصر تُعرّف ورقة الصفحة لعنصر صفحة أو عنصر رئيسي.

**Returns:**
[PageSheet](../../com.aspose.diagram/pagesheet)
### getPatternFlags() {#getPatternFlags--}
```
public int getPatternFlags()
```


تحدد سمة PatternFlags ما إذا كان القالب يتصرف كنمط مخصص.

**Returns:**
int
### getPrompt() {#getPrompt--}
```
public String getPrompt()
```


شريط الحالة وتلميح الأداة يوضحان العنصر.

**Returns:**
java.lang.String
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


مجموعة من كائنات Shape.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


معرف GUID يحدد القالب داخل المستند.

**Returns:**
java.util.UUID
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




### setAlignName(int value) {#setAlignName-int-}
```
public void setAlignName(int value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getAlignName()](../../com.aspose.diagram/master\#getAlignName--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setBaseID(UUID value) {#setBaseID-java.util.UUID-}
```
public void setBaseID(UUID value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getBaseID()](../../com.aspose.diagram/master\#getBaseID--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.util.UUID |  |

### setHidden(int value) {#setHidden-int-}
```
public void setHidden(int value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getHidden()](../../com.aspose.diagram/master\#getHidden--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getID()](../../com.aspose.diagram/master\#getID--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setIcon(byte[] value) {#setIcon-byte---}
```
public void setIcon(byte[] value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getIcon()](../../com.aspose.diagram/master\#getIcon--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | byte[] |  |

### setIconSize(int value) {#setIconSize-int-}
```
public void setIconSize(int value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getIconSize()](../../com.aspose.diagram/master\#getIconSize--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setIconUpdate(int value) {#setIconUpdate-int-}
```
public void setIconUpdate(int value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getIconUpdate()](../../com.aspose.diagram/master\#getIconUpdate--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setMatchByName(int value) {#setMatchByName-int-}
```
public void setMatchByName(int value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getMatchByName()](../../com.aspose.diagram/master\#getMatchByName--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getName()](../../com.aspose.diagram/master\#getName--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getNameU()](../../com.aspose.diagram/master\#getNameU--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### setPatternFlags(int value) {#setPatternFlags-int-}
```
public void setPatternFlags(int value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getPatternFlags()](../../com.aspose.diagram/master\#getPatternFlags--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setPrompt(String value) {#setPrompt-java.lang.String-}
```
public void setPrompt(String value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getPrompt()](../../com.aspose.diagram/master\#getPrompt--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getUniqueID()](../../com.aspose.diagram/master\#getUniqueID--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.util.UUID |  |

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

