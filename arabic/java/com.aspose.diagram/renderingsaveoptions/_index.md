---
title: RenderingSaveOptions
second_title: Aspose.Diagram لـ Java API Reference
description: هذه فئة أساسية مجردة للفئات التي تسمح للمستخدم بتحديد خيارات إضافية عند حفظ المخطط بصيغة معينة.
type: docs
weight: 327
url: /ar/java/com.aspose.diagram/renderingsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions)
```
public abstract class RenderingSaveOptions extends SaveOptions
```

هذه فئة أساسية مجردة للفئات التي تسمح للمستخدم بتحديد خيارات إضافية عند حفظ المخطط بصيغة معينة.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | ينشئ كائن خيارات حفظ من فئة مناسبة لتنسيق الحفظ المحدد. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultFont()](#getDefaultFont--) | عند تكون الأحرف في المخطط يونيكود ولم يتم تعيين قيمة الخط الصحيحة أو لم يتم تثبيت الخط محليًا، قد تظهر ككتل في PDF أو صورة أو XPS. |
| [getEmfRenderSetting()](#getEmfRenderSetting--) | إعداد لتصوير ملف Emf الميتا. |
| [getEnlargePage()](#getEnlargePage--) | يحدد ما إذا كان سيتم تكبير الصفحة. |
| [getExportGuideShapes()](#getExportGuideShapes--) | يحدد ما إذا كان يلزم تصدير أشكال الدليل أم لا. |
| [getPageSize()](#getPageSize--) | حجم الصفحة للصور المُولَّدة. |
| [getSaveFormat()](#getSaveFormat--) | يحدد الصيغة التي سيتم حفظ المستند بها إذا تم استخدام كائن خيارات الحفظ هذا. |
| [getShapes()](#getShapes--) | الأشكال التي سيتم عرضها. |
| [getWarningCallback()](#getWarningCallback--) | دالة رد النداء للتحذير. |
| [hashCode()](#hashCode--) |  |
| [isExportComments()](#isExportComments--) | يحدد ما إذا كان يلزم تصدير التعليقات أم لا. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | للوصف الخاص بهذه الخاصية، يرجى الاطلاع على [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setEmfRenderSetting(int value)](#setEmfRenderSetting-int-) | للوصف الخاص بهذه الخاصية، يرجى الاطلاع على [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--) |
| [setEnlargePage(boolean value)](#setEnlargePage-boolean-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--) |
| [setExportComments(boolean value)](#setExportComments-boolean-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--) |
| [setExportGuideShapes(boolean value)](#setExportGuideShapes-boolean-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--) |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | لوصف هذه الخاصية، يرجى الاطلاع على [getSaveFormat()](../../com.aspose.diagram/saveoptions\#getSaveFormat--) |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getEmfRenderSetting() {#getEmfRenderSetting--}
```
public int getEmfRenderSetting()
```


إعداد لتصيير ملف Emf التعريفي. يمكن لملفات EMF التي تم تعريفها كـ "EMF+ Dual" أن تحتوي على كل من سجلات EMF+ وسجلات EMF. يمكن استخدام أي نوع من السجلات لتصيير الصورة، سجلات EMF+ فقط، أو سجلات EMF فقط. عندما يتم تعيين EmfPlusPrefer، سيتم تحليل سجلات EMF+، وإلا سيتم تحليل سجلات EMF فقط. القيمة الافتراضية هي EmfOnly"/>.

**Returns:**
int
### getEnlargePage() {#getEnlargePage--}
```
public boolean getEnlargePage()
```


يحدد ما إذا كان يجب تكبير الصفحة. إذا كان true - يتم تكبير الصفحة. إذا كان false - لا يتم تكبير الصفحة. القيمة الافتراضية هي true.

**Returns:**
منطقي
### getExportGuideShapes() {#getExportGuideShapes--}
```
public boolean getExportGuideShapes()
```


يحدد ما إذا كان يلزم تصدير أشكال الدليل أم لا. القيمة الافتراضية هي true.

**Returns:**
منطقي
### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


حجم الصفحة للصور المُولَّدة. يمكن أن يكون [PageSize](../../com.aspose.diagram/pagesize) أو null. القيمة الافتراضية هي null. إذا كان PageSize يساوي null فإن حجم الصفحة للصورة المُولَّدة يُستَخرَج من المخطط المصدر.

**Returns:**
[PageSize](../../com.aspose.diagram/pagesize)
### getSaveFormat() {#getSaveFormat--}
```
public int getSaveFormat()
```


يحدد الصيغة التي سيتم حفظ المستند بها إذا تم استخدام كائن خيارات الحفظ هذا.

**Returns:**
int
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


الأشكال للتصيير. العدد الافتراضي هو 0.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
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
### isExportComments() {#isExportComments--}
```
public boolean isExportComments()
```


يحدد ما إذا كان يجب تصدير التعليقات أم لا. القيمة الافتراضية هي false.

**Returns:**
منطقي
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

### setEmfRenderSetting(int value) {#setEmfRenderSetting-int-}
```
public void setEmfRenderSetting(int value)
```


للوصف الخاص بهذه الخاصية، يرجى الاطلاع على [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setEnlargePage(boolean value) {#setEnlargePage-boolean-}
```
public void setEnlargePage(boolean value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | منطقي |  |

### setExportComments(boolean value) {#setExportComments-boolean-}
```
public void setExportComments(boolean value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | منطقي |  |

### setExportGuideShapes(boolean value) {#setExportGuideShapes-boolean-}
```
public void setExportGuideShapes(boolean value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | منطقي |  |

### setPageSize(PageSize value) {#setPageSize-com.aspose.diagram.PageSize-}
```
public void setPageSize(PageSize value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PageSize](../../com.aspose.diagram/pagesize) |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getSaveFormat()](../../com.aspose.diagram/saveoptions\#getSaveFormat--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setShapes(ShapeCollection value) {#setShapes-com.aspose.diagram.ShapeCollection-}
```
public void setShapes(ShapeCollection value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ShapeCollection](../../com.aspose.diagram/shapecollection) |  |

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

