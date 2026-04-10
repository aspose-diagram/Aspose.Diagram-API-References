---
title: DiagramSaveOptions
second_title: Aspose.Diagram لـ Java API Reference
description: يمكن استخدامه لتحديد خيارات إضافية عند حفظ مخطط بصيغة Visio VDXVSX.
type: docs
weight: 119
url: /ar/java/com.aspose.diagram/diagramsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions)
```
public class DiagramSaveOptions extends SaveOptions
```

يمكن استخدامه لتحديد خيارات إضافية عند حفظ مخطط بصيغة Visio (VDX\VSX). في الوقت الحالي يوفر خاصية SaveFormat فقط، ولكن في المستقبل ستُضاف خيارات أخرى.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [DiagramSaveOptions()](#DiagramSaveOptions--) | ينشئ مثيلًا جديدًا من هذه الفئة يمكن استخدامه لحفظ مخطط بصيغة VDX. |
| [DiagramSaveOptions(int saveFormat)](#DiagramSaveOptions-int-) | يُنشئ مثيلاً جديدًا من هذه الفئة يمكن استخدامه لحفظ مخطط بصيغة VDX أو VSX. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | ينشئ كائن خيارات حفظ من فئة مناسبة لتنسيق الحفظ المحدد. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoFitPageToDrawingContent()](#getAutoFitPageToDrawingContent--) | يحدد ما إذا كان يجب تكبير الصفحة لتناسب محتوى الرسم أم لا. |
| [getClass()](#getClass--) |  |
| [getDefaultFont()](#getDefaultFont--) | عند تكون الأحرف في المخطط يونيكود ولم يتم تعيين قيمة الخط الصحيحة أو لم يتم تثبيت الخط محليًا، قد تظهر ككتل في PDF أو صورة أو XPS. |
| [getSaveFormat()](#getSaveFormat--) | يحدد الصيغة التي سيتم حفظ المخطط المُصوَّر بها إذا تم استخدام كائن خيارات الحفظ هذا. |
| [getWarningCallback()](#getWarningCallback--) | دالة رد النداء للتحذير. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoFitPageToDrawingContent(boolean value)](#setAutoFitPageToDrawingContent-boolean-) | لوصف هذه الخاصية، يرجى الاطلاع على [getAutoFitPageToDrawingContent()](../../com.aspose.diagram/diagramsaveoptions\#getAutoFitPageToDrawingContent--) |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | للوصف الخاص بهذه الخاصية، يرجى الاطلاع على [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | لوصف هذه الخاصية، يرجى الاطلاع على [getSaveFormat()](../../com.aspose.diagram/diagramsaveoptions\#getSaveFormat--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DiagramSaveOptions() {#DiagramSaveOptions--}
```
public DiagramSaveOptions()
```


ينشئ مثيلًا جديدًا من هذه الفئة يمكن استخدامه لحفظ مخطط بصيغة VDX.

### DiagramSaveOptions(int saveFormat) {#DiagramSaveOptions-int-}
```
public DiagramSaveOptions(int saveFormat)
```


يُنشئ مثيلاً جديدًا من هذه الفئة يمكن استخدامه لحفظ مخطط بصيغة VDX أو VSX.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| saveFormat | int |  |

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
### getAutoFitPageToDrawingContent() {#getAutoFitPageToDrawingContent--}
```
public boolean getAutoFitPageToDrawingContent()
```


يحدد ما إذا كان يجب تكبير الصفحة لتناسب محتوى الرسم أم لا. القيمة الافتراضية هي false.

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
### getSaveFormat() {#getSaveFormat--}
```
public int getSaveFormat()
```


يحدد الصيغة التي سيتم حفظ المخطط المُصوَّر بها إذا تم استخدام كائن خيارات الحفظ هذا. يمكن أن تكون Aspose.Diagram.SaveFileFormat أو Aspose.Diagram.SaveFileFormat.

**Returns:**
int
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




### setAutoFitPageToDrawingContent(boolean value) {#setAutoFitPageToDrawingContent-boolean-}
```
public void setAutoFitPageToDrawingContent(boolean value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getAutoFitPageToDrawingContent()](../../com.aspose.diagram/diagramsaveoptions\#getAutoFitPageToDrawingContent--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | منطقي |  |

### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public void setDefaultFont(String value)
```


للوصف الخاص بهذه الخاصية، يرجى الاطلاع على [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getSaveFormat()](../../com.aspose.diagram/diagramsaveoptions\#getSaveFormat--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

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

