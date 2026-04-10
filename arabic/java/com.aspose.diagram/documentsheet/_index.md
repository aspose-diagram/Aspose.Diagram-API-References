---
title: DocumentSheet
second_title: Aspose.Diagram لـ Java API Reference
description: يحدد بنية ShapeSheet للمستند.
type: docs
weight: 127
url: /ar/java/com.aspose.diagram/documentsheet/
---

**Inheritance:**
java.lang.Object
```
public class DocumentSheet
```

يحدد بنية ShapeSheet للمستند.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAnnotations()](#getAnnotations--) | يحتوي على عناصر تتضمن معلومات حول التعليقات المدخلة في صفحة المستند. |
| [getClass()](#getClass--) |  |
| [getConnectionABCDs()](#getConnectionABCDs--) | يحتوي على مجموعة من عناصر ConnectionABCD. |
| [getConnections()](#getConnections--) | يحتوي على مجموعة من عناصر Connection. |
| [getDocProps()](#getDocProps--) | يحتوي على عناصر تتحكم في جودة معاينة المستند، والنطاق، وصيغة الإخراج. |
| [getFillStyle()](#getFillStyle--) | عنصر StyleSheet الذي يرث منه هذا النمط تنسيق التعبئة. |
| [getForeign()](#getForeign--) | يحتوي على عناصر تحدد العرض والارتفاع لكائن من برنامج آخر يُستخدم في مستند Microsoft Visio. |
| [getForeignData()](#getForeignData--) | يحتوي على BLOB مشفر بتنسيق MIME (Multipurpose Internet Mail Extensions) لبيانات الصورة، مثل ملف ميتافايل Windows أو bitmap أو بيانات OLE. |
| [getHyperlinks()](#getHyperlinks--) | يحتوي على مجموعة من عناصر Hyperlink. |
| [getLineStyle()](#getLineStyle--) | عنصر StyleSheet الذي يرث منه هذا النمط تنسيق الخط. |
| [getName()](#getName--) | اسم العنصر. |
| [getNameU()](#getNameU--) | الاسم العام للعنصر. |
| [getProps()](#getProps--) | يحتوي على مجموعة من عناصر Prop. |
| [getReviewers()](#getReviewers--) | تحتوي على عناصر تحتوي على معلومات تعريفية حول مراجع المستند. |
| [getScratchs()](#getScratchs--) | يحتوي على مجموعة من عناصر Scratch. |
| [getTextStyle()](#getTextStyle--) | عنصر StyleSheet الذي يرث منه هذا النمط تنسيق النص. |
| [getUniqueID()](#getUniqueID--) | معرف GUID (معرف عالمي فريد) يحدد الشكل. |
| [getUsers()](#getUsers--) | يحتوي على مجموعة من عناصر User. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFillStyle(StyleSheet value)](#setFillStyle-com.aspose.diagram.StyleSheet-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getFillStyle()](../../com.aspose.diagram/documentsheet\#getFillStyle--) |
| [setLineStyle(StyleSheet value)](#setLineStyle-com.aspose.diagram.StyleSheet-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getLineStyle()](../../com.aspose.diagram/documentsheet\#getLineStyle--) |
| [setName(String value)](#setName-java.lang.String-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getName()](../../com.aspose.diagram/documentsheet\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getNameU()](../../com.aspose.diagram/documentsheet\#getNameU--) |
| [setTextStyle(StyleSheet value)](#setTextStyle-com.aspose.diagram.StyleSheet-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getTextStyle()](../../com.aspose.diagram/documentsheet\#getTextStyle--) |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getUniqueID()](../../com.aspose.diagram/documentsheet\#getUniqueID--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getAnnotations() {#getAnnotations--}
```
public AnnotationCollection getAnnotations()
```


يحتوي على عناصر تتضمن معلومات حول التعليقات المدخلة في صفحة المستند.

**Returns:**
[AnnotationCollection](../../com.aspose.diagram/annotationcollection)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConnectionABCDs() {#getConnectionABCDs--}
```
public ConnectionABCDCollection getConnectionABCDs()
```


يحتوي على مجموعة من عناصر ConnectionABCD.

**Returns:**
[ConnectionABCDCollection](../../com.aspose.diagram/connectionabcdcollection)
### getConnections() {#getConnections--}
```
public ConnectionCollection getConnections()
```


يحتوي على مجموعة من عناصر Connection.

**Returns:**
[ConnectionCollection](../../com.aspose.diagram/connectioncollection)
### getDocProps() {#getDocProps--}
```
public DocProps getDocProps()
```


يحتوي على عناصر تتحكم في جودة معاينة المستند، والنطاق، وصيغة الإخراج.

**Returns:**
[DocProps](../../com.aspose.diagram/docprops)
### getFillStyle() {#getFillStyle--}
```
public StyleSheet getFillStyle()
```


عنصر StyleSheet الذي يرث منه هذا النمط تنسيق التعبئة.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getForeign() {#getForeign--}
```
public Foreign getForeign()
```


يحتوي على عناصر تحدد العرض والارتفاع لكائن من برنامج آخر يُستخدم في مستند Microsoft Visio. كما يتضمن عناصر تحدد المسافة التي يُزاح فيها صورة الكائن داخل حدوده.

**Returns:**
[Foreign](../../com.aspose.diagram/foreign)
### getForeignData() {#getForeignData--}
```
public ForeignData getForeignData()
```


يحتوي على BLOB مشفر بتنسيق MIME (Multipurpose Internet Mail Extensions) لبيانات الصورة، مثل ملف ميتافايل Windows أو bitmap أو بيانات OLE.

**Returns:**
[ForeignData](../../com.aspose.diagram/foreigndata)
### getHyperlinks() {#getHyperlinks--}
```
public HyperlinkCollection getHyperlinks()
```


يحتوي على مجموعة من عناصر Hyperlink.

**Returns:**
[HyperlinkCollection](../../com.aspose.diagram/hyperlinkcollection)
### getLineStyle() {#getLineStyle--}
```
public StyleSheet getLineStyle()
```


عنصر StyleSheet الذي يرث منه هذا النمط تنسيق الخط.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
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
### getProps() {#getProps--}
```
public PropCollection getProps()
```


يحتوي على مجموعة من عناصر Prop.

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getReviewers() {#getReviewers--}
```
public ReviewerCollection getReviewers()
```


تحتوي على عناصر تحتوي على معلومات تعريفية حول مراجع المستند.

**Returns:**
[ReviewerCollection](../../com.aspose.diagram/reviewercollection)
### getScratchs() {#getScratchs--}
```
public ScratchCollection getScratchs()
```


يحتوي على مجموعة من عناصر Scratch.

**Returns:**
[ScratchCollection](../../com.aspose.diagram/scratchcollection)
### getTextStyle() {#getTextStyle--}
```
public StyleSheet getTextStyle()
```


عنصر StyleSheet الذي يرث منه هذا النمط تنسيق النص.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


معرف GUID (معرف عالمي فريد) يحدد الشكل.

**Returns:**
java.util.UUID
### getUsers() {#getUsers--}
```
public UserCollection getUsers()
```


يحتوي على مجموعة من عناصر User.

**Returns:**
[UserCollection](../../com.aspose.diagram/usercollection)
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




### setFillStyle(StyleSheet value) {#setFillStyle-com.aspose.diagram.StyleSheet-}
```
public void setFillStyle(StyleSheet value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getFillStyle()](../../com.aspose.diagram/documentsheet\#getFillStyle--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setLineStyle(StyleSheet value) {#setLineStyle-com.aspose.diagram.StyleSheet-}
```
public void setLineStyle(StyleSheet value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getLineStyle()](../../com.aspose.diagram/documentsheet\#getLineStyle--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getName()](../../com.aspose.diagram/documentsheet\#getName--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getNameU()](../../com.aspose.diagram/documentsheet\#getNameU--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### setTextStyle(StyleSheet value) {#setTextStyle-com.aspose.diagram.StyleSheet-}
```
public void setTextStyle(StyleSheet value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getTextStyle()](../../com.aspose.diagram/documentsheet\#getTextStyle--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getUniqueID()](../../com.aspose.diagram/documentsheet\#getUniqueID--)

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

