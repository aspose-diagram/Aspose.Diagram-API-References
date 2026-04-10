---
title: XAMLSaveOptions
second_title: Aspose.Diagram لـ Java API Reference
description: يسمح بتحديد خيارات إضافية عند تصيير صفحات المخطط إلى XAML.
type: docs
weight: 448
url: /ar/java/com.aspose.diagram/xamlsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions)
```
public class XAMLSaveOptions extends SaveOptions
```

يسمح بتحديد خيارات إضافية عند تصيير صفحات المخطط إلى XAML.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [XAMLSaveOptions()](#XAMLSaveOptions--) | يُنشئ مثيلاً جديدًا من هذه الفئة يمكن استخدامه لحفظ مستند بتنسيق Aspose.Diagram.SaveFileFormat. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | ينشئ كائن خيارات حفظ من فئة مناسبة لتنسيق الحفظ المحدد. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultFont()](#getDefaultFont--) | عند تكون الأحرف في المخطط يونيكود ولم يتم تعيين قيمة الخط الصحيحة أو لم يتم تثبيت الخط محليًا، قد تظهر ككتل في PDF أو صورة أو XPS. |
| [getPageCount()](#getPageCount--) | the number of pages to render in XAML. |
| [getPageIndex()](#getPageIndex--) | الفهرس القائم على الصفر للصفحة الأولى التي سيتم عرضها. |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | يحدد ما إذا كانت جميع الصفحات ستحفظ كصورة أم فقط المقدمة. |
| [getSaveFormat()](#getSaveFormat--) | يحدد التنسيق الذي ستحفظ به صفحات المخطط المُعالجة إذا تم استخدام كائن خيارات الحفظ هذا. |
| [getStreamProvider()](#getStreamProvider--) | IStreamProvider لتصدير الكائنات. |
| [getWarningCallback()](#getWarningCallback--) | دالة رد النداء للتحذير. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | للوصف الخاص بهذه الخاصية، يرجى الاطلاع على [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setPageCount(int value)](#setPageCount-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getPageCount()](../../com.aspose.diagram/xamlsaveoptions\#getPageCount--) |
| [setPageIndex(int value)](#setPageIndex-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getPageIndex()](../../com.aspose.diagram/xamlsaveoptions\#getPageIndex--) |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getSaveForegroundPagesOnly()](../../com.aspose.diagram/xamlsaveoptions\#getSaveForegroundPagesOnly--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getSaveFormat()](../../com.aspose.diagram/xamlsaveoptions\#getSaveFormat--) |
| [setStreamProvider(IStreamProvider value)](#setStreamProvider-com.aspose.diagram.IStreamProvider-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getStreamProvider()](../../com.aspose.diagram/xamlsaveoptions\#getStreamProvider--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XAMLSaveOptions() {#XAMLSaveOptions--}
```
public XAMLSaveOptions()
```


يُنشئ مثيلاً جديدًا من هذه الفئة يمكن استخدامه لحفظ مستند بتنسيق Aspose.Diagram.SaveFileFormat.

### createSaveOptions(int saveFormat) {#createSaveOptions-int-}
```
public static SaveOptions createSaveOptions(int saveFormat)
```


ينشئ كائن خيارات حفظ من فئة مناسبة لتنسيق الحفظ المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| saveFormat | int | تنسيق Aspose.Diagram.SaveFileFormat الذي يُنشأ من أجله كائن خيارات الحفظ. |

**Returns:**
[SaveOptions](../../com.aspose.diagram/saveoptions) - An object of a class that derives from [SaveOptions](../../com.aspose.diagram/saveoptions).
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
### getDefaultFont() {#getDefaultFont--}
```
public String getDefaultFont()
```


عند كون الأحرف في المخطط يونيكود ولم يتم تعيين قيمة الخط الصحيحة أو إذا لم يكن الخط مثبتًا محليًا، قد تظهر ككتل في ملفات PDF أو الصورة أو XPS. قم بتعيين DefaultFont مثل MingLiu أو MS Gothic لعرض هذه الأحرف.

**Returns:**
java.lang.String
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


عدد الصفحات التي سيتم عرضها في XAML. القيمة الافتراضية هي MaxValue مما يعني أنه سيتم عرض جميع صفحات المخطط.

**Returns:**
int
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


الفهرس القائم على الصفر للصفحة الأولى التي سيتم تصييرها. القيمة الافتراضية هي 0.

**Returns:**
int
### getSaveForegroundPagesOnly() {#getSaveForegroundPagesOnly--}
```
public boolean getSaveForegroundPagesOnly()
```


يحدد ما إذا كانت جميع الصفحات سيتم حفظها كصورة أو فقط المقدمة. إذا كان true - يتم تصيير صفحات المقدمة فقط (مع الخلفية إذا كانت موجودة). إذا كان false - يتم تصيير صفحات المقدمة (مع الخلفية إذا كانت موجودة) ثم صفحات الخلفية الفارغة. يمكن إرجاع true فقط عندما يكون PageCount > 1. القيمة الافتراضية هي false.

**Returns:**
منطقي
### getSaveFormat() {#getSaveFormat--}
```
public int getSaveFormat()
```


يحدد الصيغة التي سيتم حفظ صفحات المخطط المُصوَّر بها إذا تم استخدام كائن خيارات الحفظ هذا. يمكن أن يكون Aspose.Diagram.SaveFileFormat فقط.

**Returns:**
int
### getStreamProvider() {#getStreamProvider--}
```
public IStreamProvider getStreamProvider()
```


IStreamProvider لتصدير الكائنات.

**Returns:**
[IStreamProvider](../../com.aspose.diagram/istreamprovider)
### getWarningCallback() {#getWarningCallback--}
```
public IWarningCallback getWarningCallback()
```


دالة رد النداء للتحذير.

**Returns:**
[IWarningCallback](../../com.aspose.diagram/iwarningcallback)
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




### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public void setDefaultFont(String value)
```


للوصف الخاص بهذه الخاصية، يرجى الاطلاع على [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getPageCount()](../../com.aspose.diagram/xamlsaveoptions\#getPageCount--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getPageIndex()](../../com.aspose.diagram/xamlsaveoptions\#getPageIndex--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getSaveForegroundPagesOnly()](../../com.aspose.diagram/xamlsaveoptions\#getSaveForegroundPagesOnly--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | منطقي |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getSaveFormat()](../../com.aspose.diagram/xamlsaveoptions\#getSaveFormat--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setStreamProvider(IStreamProvider value) {#setStreamProvider-com.aspose.diagram.IStreamProvider-}
```
public void setStreamProvider(IStreamProvider value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getStreamProvider()](../../com.aspose.diagram/xamlsaveoptions\#getStreamProvider--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [IStreamProvider](../../com.aspose.diagram/istreamprovider) |  |

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.diagram.IWarningCallback-}
```
public void setWarningCallback(IWarningCallback value)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.diagram/iwarningcallback) |  |

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

