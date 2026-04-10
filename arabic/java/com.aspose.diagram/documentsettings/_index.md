---
title: DocumentSettings
second_title: Aspose.Diagram لـ Java API Reference
description: يحتوي على عناصر تحدد إعدادات المستند.
type: docs
weight: 126
url: /ar/java/com.aspose.diagram/documentsettings/
---

**Inheritance:**
java.lang.Object
```
public class DocumentSettings
```

يحتوي على عناصر تحدد إعدادات المستند.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAttachedToolbars()](#getAttachedToolbars--) | ملف واجهة مستخدم Microsoft Visio (VSU) مشفر بتنسيق MIME (Multipurpose Internet Mail Extensions) يمثل أدوات شريط أدوات مخصصة. |
| [getClass()](#getClass--) |  |
| [getCustomMenusFile()](#getCustomMenusFile--) | يحتوي على اسم ملف واجهة مستخدم Microsoft Visio (.vsu) الذي يحدد القوائم المخصصة ومفاتيح الاختصار لمستند. |
| [getCustomToolbarsFile()](#getCustomToolbarsFile--) | يحتوي على اسم ملف واجهة مستخدم Microsoft Visio (.vsu) الذي يحدد شريط أدوات مخصص وأشرطة الحالة لمستند. |
| [getDefaultFillStyle()](#getDefaultFillStyle--) | يحدد معرّف عنصر StyleSheet. |
| [getDefaultGuideStyle()](#getDefaultGuideStyle--) | يحدد معرّف عنصر StyleSheet. |
| [getDefaultLineStyle()](#getDefaultLineStyle--) | يحدد معرّف عنصر StyleSheet. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | يحدد معرّف عنصر StyleSheet. |
| [getDynamicGridEnabled()](#getDynamicGridEnabled--) | يحدد ما إذا كانت ميزة الشبكة الديناميكية مفعلة لمستند أو نافذة. |
| [getGlueSettings()](#getGlueSettings--) | يحدد الكائنات التي تلصق إليها الأشكال عندما يكون اللصق مفعلاً في المستند. |
| [getProtectBkgnds()](#getProtectBkgnds--) | يحدد ما إذا كان يُمنع المستخدم من حذف أو تعديل صفحات الخلفية. |
| [getProtectMasters()](#getProtectMasters--) | يحدد ما إذا كان يُمنع المستخدم من إنشاء أو تعديل أو حذف القوالب الرئيسية. |
| [getProtectShapes()](#getProtectShapes--) | يحدد ما إذا كان يُمنع المستخدم من تحديد الأشكال التي تم تعيين عنصر LockSelect لها إلى 1. |
| [getProtectStyles()](#getProtectStyles--) | يحدد ما إذا كان يُمنع المستخدم من إنشاء الأنماط أو تعديلها. |
| [getSnapAngles()](#getSnapAngles--) | يحتوي على مجموعة من عناصر SnapAngle. |
| [getSnapExtensions()](#getSnapExtensions--) | يحدد ما إذا كان إعداد امتداد الالتقاط المحدد مفعلاً أو معطلاً للنافذة النشطة. |
| [getSnapSettings()](#getSnapSettings--) | يحدد الكائنات التي يلتقط إليها الأشكال عندما يكون الالتقاط مفعلاً في النافذة. |
| [getTopPage()](#getTopPage--) | يحدد معرّف الصفحة التي يجب عرضها عند فتح المستند بواسطة Microsoft Visio. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAttachedToolbars(byte[] value)](#setAttachedToolbars-byte---) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getAttachedToolbars()](../../com.aspose.diagram/documentsettings\#getAttachedToolbars--) |
| [setCustomMenusFile(String value)](#setCustomMenusFile-java.lang.String-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getCustomMenusFile()](../../com.aspose.diagram/documentsettings\#getCustomMenusFile--) |
| [setCustomToolbarsFile(String value)](#setCustomToolbarsFile-java.lang.String-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getCustomToolbarsFile()](../../com.aspose.diagram/documentsettings\#getCustomToolbarsFile--) |
| [setDefaultFillStyle(int value)](#setDefaultFillStyle-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getDefaultFillStyle()](../../com.aspose.diagram/documentsettings\#getDefaultFillStyle--) |
| [setDefaultGuideStyle(int value)](#setDefaultGuideStyle-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getDefaultGuideStyle()](../../com.aspose.diagram/documentsettings\#getDefaultGuideStyle--) |
| [setDefaultLineStyle(int value)](#setDefaultLineStyle-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getDefaultLineStyle()](../../com.aspose.diagram/documentsettings\#getDefaultLineStyle--) |
| [setDefaultTextStyle(int value)](#setDefaultTextStyle-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getDefaultTextStyle()](../../com.aspose.diagram/documentsettings\#getDefaultTextStyle--) |
| [setDynamicGridEnabled(int value)](#setDynamicGridEnabled-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getDynamicGridEnabled()](../../com.aspose.diagram/documentsettings\#getDynamicGridEnabled--) |
| [setGlueSettings(int value)](#setGlueSettings-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getGlueSettings()](../../com.aspose.diagram/documentsettings\#getGlueSettings--) |
| [setProtectBkgnds(int value)](#setProtectBkgnds-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getProtectBkgnds()](../../com.aspose.diagram/documentsettings\#getProtectBkgnds--) |
| [setProtectMasters(int value)](#setProtectMasters-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getProtectMasters()](../../com.aspose.diagram/documentsettings\#getProtectMasters--) |
| [setProtectShapes(int value)](#setProtectShapes-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getProtectShapes()](../../com.aspose.diagram/documentsettings\#getProtectShapes--) |
| [setProtectStyles(int value)](#setProtectStyles-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getProtectStyles()](../../com.aspose.diagram/documentsettings\#getProtectStyles--) |
| [setSnapAngles(FloatPointNumCollection value)](#setSnapAngles-com.aspose.diagram.FloatPointNumCollection-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getSnapAngles()](../../com.aspose.diagram/documentsettings\#getSnapAngles--) |
| [setSnapExtensions(int value)](#setSnapExtensions-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getSnapExtensions()](../../com.aspose.diagram/documentsettings\#getSnapExtensions--) |
| [setSnapSettings(int value)](#setSnapSettings-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getSnapSettings()](../../com.aspose.diagram/documentsettings\#getSnapSettings--) |
| [setTopPage(int value)](#setTopPage-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getTopPage()](../../com.aspose.diagram/documentsettings\#getTopPage--) |
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
### getAttachedToolbars() {#getAttachedToolbars--}
```
public byte[] getAttachedToolbars()
```


ملف واجهة مستخدم Microsoft Visio (VSU) مشفر بتنسيق MIME (Multipurpose Internet Mail Extensions) يمثل أدوات شريط أدوات مخصصة.

**Returns:**
byte[]
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCustomMenusFile() {#getCustomMenusFile--}
```
public String getCustomMenusFile()
```


يحتوي على اسم ملف واجهة مستخدم Microsoft Visio (.vsu) الذي يحدد القوائم المخصصة ومفاتيح الاختصار لمستند.

**Returns:**
java.lang.String
### getCustomToolbarsFile() {#getCustomToolbarsFile--}
```
public String getCustomToolbarsFile()
```


يحتوي على اسم ملف واجهة مستخدم Microsoft Visio (.vsu) الذي يحدد شريط أدوات مخصص وأشرطة الحالة لمستند.

**Returns:**
java.lang.String
### getDefaultFillStyle() {#getDefaultFillStyle--}
```
public int getDefaultFillStyle()
```


يحدد معرّف عنصر StyleSheet. في المرة التالية التي ينشئ فيها المستخدم شكلًا باستخدام أداة الرسم، يرث الشكل نمط التعبئة من عنصر StyleSheet المحدد.

**Returns:**
int
### getDefaultGuideStyle() {#getDefaultGuideStyle--}
```
public int getDefaultGuideStyle()
```


يحدد معرّف عنصر StyleSheet. في المرة التالية التي ينشئ فيها المستخدم دليلًا، يرث الدليل نمط الدليل من عنصر StyleSheet المحدد.

**Returns:**
int
### getDefaultLineStyle() {#getDefaultLineStyle--}
```
public int getDefaultLineStyle()
```


يحدد معرّف عنصر StyleSheet. في المرة التالية التي ينشئ فيها المستخدم شكلًا باستخدام أداة الرسم، يرث الشكل نمط الخط من عنصر StyleSheet المحدد.

**Returns:**
int
### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public int getDefaultTextStyle()
```


يحدد معرّف عنصر StyleSheet. في المرة التالية التي ينشئ فيها المستخدم شكلًا باستخدام أداة الرسم، يرث الشكل نمط النص من عنصر StyleSheet المحدد.

**Returns:**
int
### getDynamicGridEnabled() {#getDynamicGridEnabled--}
```
public int getDynamicGridEnabled()
```


يحدد ما إذا كانت ميزة الشبكة الديناميكية مفعلة لمستند أو نافذة.

**Returns:**
int
### getGlueSettings() {#getGlueSettings--}
```
public int getGlueSettings()
```


يحدد الكائنات التي تلصق إليها الأشكال عندما يكون اللصق مفعلاً في المستند.

**Returns:**
int
### getProtectBkgnds() {#getProtectBkgnds--}
```
public int getProtectBkgnds()
```


يحدد ما إذا كان يُمنع المستخدم من حذف أو تعديل صفحات الخلفية.

**Returns:**
int
### getProtectMasters() {#getProtectMasters--}
```
public int getProtectMasters()
```


يحدد ما إذا كان يُمنع المستخدم من إنشاء أو تعديل أو حذف القوالب. بغض النظر عن هذا الإعداد، لا يزال بإمكان المستخدم إنشاء نسخ من القوالب.

**Returns:**
int
### getProtectShapes() {#getProtectShapes--}
```
public int getProtectShapes()
```


يحدد ما إذا كان يُمنع المستخدم من تحديد الأشكال التي تم تعيين عنصر LockSelect لها إلى 1.

**Returns:**
int
### getProtectStyles() {#getProtectStyles--}
```
public int getProtectStyles()
```


يحدد ما إذا كان يُمنع المستخدم من إنشاء أو تعديل الأنماط. ومع ذلك، بغض النظر عن هذا الإعداد، لا يزال بإمكان المستخدم تطبيق الأنماط.

**Returns:**
int
### getSnapAngles() {#getSnapAngles--}
```
public FloatPointNumCollection getSnapAngles()
```


يحتوي على مجموعة من عناصر SnapAngle.

**Returns:**
[FloatPointNumCollection](../../com.aspose.diagram/floatpointnumcollection)
### getSnapExtensions() {#getSnapExtensions--}
```
public int getSnapExtensions()
```


يحدد ما إذا كان إعداد امتداد الالتقاط المحدد مفعلاً أو معطلاً للنافذة النشطة.

**Returns:**
int
### getSnapSettings() {#getSnapSettings--}
```
public int getSnapSettings()
```


يحدد الكائنات التي يلتقط إليها الأشكال عندما يكون الالتقاط مفعلاً في النافذة.

**Returns:**
int
### getTopPage() {#getTopPage--}
```
public int getTopPage()
```


يحدد معرّف الصفحة التي يجب عرضها عند فتح المستند بواسطة Microsoft Visio.

**Returns:**
int
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




### setAttachedToolbars(byte[] value) {#setAttachedToolbars-byte---}
```
public void setAttachedToolbars(byte[] value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getAttachedToolbars()](../../com.aspose.diagram/documentsettings\#getAttachedToolbars--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | byte[] |  |

### setCustomMenusFile(String value) {#setCustomMenusFile-java.lang.String-}
```
public void setCustomMenusFile(String value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getCustomMenusFile()](../../com.aspose.diagram/documentsettings\#getCustomMenusFile--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### setCustomToolbarsFile(String value) {#setCustomToolbarsFile-java.lang.String-}
```
public void setCustomToolbarsFile(String value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getCustomToolbarsFile()](../../com.aspose.diagram/documentsettings\#getCustomToolbarsFile--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### setDefaultFillStyle(int value) {#setDefaultFillStyle-int-}
```
public void setDefaultFillStyle(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getDefaultFillStyle()](../../com.aspose.diagram/documentsettings\#getDefaultFillStyle--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setDefaultGuideStyle(int value) {#setDefaultGuideStyle-int-}
```
public void setDefaultGuideStyle(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getDefaultGuideStyle()](../../com.aspose.diagram/documentsettings\#getDefaultGuideStyle--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setDefaultLineStyle(int value) {#setDefaultLineStyle-int-}
```
public void setDefaultLineStyle(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getDefaultLineStyle()](../../com.aspose.diagram/documentsettings\#getDefaultLineStyle--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setDefaultTextStyle(int value) {#setDefaultTextStyle-int-}
```
public void setDefaultTextStyle(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getDefaultTextStyle()](../../com.aspose.diagram/documentsettings\#getDefaultTextStyle--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setDynamicGridEnabled(int value) {#setDynamicGridEnabled-int-}
```
public void setDynamicGridEnabled(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getDynamicGridEnabled()](../../com.aspose.diagram/documentsettings\#getDynamicGridEnabled--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setGlueSettings(int value) {#setGlueSettings-int-}
```
public void setGlueSettings(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getGlueSettings()](../../com.aspose.diagram/documentsettings\#getGlueSettings--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setProtectBkgnds(int value) {#setProtectBkgnds-int-}
```
public void setProtectBkgnds(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getProtectBkgnds()](../../com.aspose.diagram/documentsettings\#getProtectBkgnds--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setProtectMasters(int value) {#setProtectMasters-int-}
```
public void setProtectMasters(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getProtectMasters()](../../com.aspose.diagram/documentsettings\#getProtectMasters--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setProtectShapes(int value) {#setProtectShapes-int-}
```
public void setProtectShapes(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getProtectShapes()](../../com.aspose.diagram/documentsettings\#getProtectShapes--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setProtectStyles(int value) {#setProtectStyles-int-}
```
public void setProtectStyles(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getProtectStyles()](../../com.aspose.diagram/documentsettings\#getProtectStyles--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setSnapAngles(FloatPointNumCollection value) {#setSnapAngles-com.aspose.diagram.FloatPointNumCollection-}
```
public void setSnapAngles(FloatPointNumCollection value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getSnapAngles()](../../com.aspose.diagram/documentsettings\#getSnapAngles--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [FloatPointNumCollection](../../com.aspose.diagram/floatpointnumcollection) |  |

### setSnapExtensions(int value) {#setSnapExtensions-int-}
```
public void setSnapExtensions(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getSnapExtensions()](../../com.aspose.diagram/documentsettings\#getSnapExtensions--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setSnapSettings(int value) {#setSnapSettings-int-}
```
public void setSnapSettings(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getSnapSettings()](../../com.aspose.diagram/documentsettings\#getSnapSettings--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setTopPage(int value) {#setTopPage-int-}
```
public void setTopPage(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getTopPage()](../../com.aspose.diagram/documentsettings\#getTopPage--)

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

