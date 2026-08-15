---
title: HTMLSaveOptions
second_title: Aspose.Diagram لـ Java API Reference
description: يسمح بتحديد خيارات إضافية عند تحويل صفحات المخطط إلى HTML.
type: docs
weight: 187
url: /ar/java/com.aspose.diagram/htmlsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class HTMLSaveOptions extends RenderingSaveOptions
```

يسمح بتحديد خيارات إضافية عند تحويل صفحات المخطط إلى HTML.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [HTMLSaveOptions()](#HTMLSaveOptions--) | يُنشئ مثيلاً جديدًا من هذه الفئة يمكن استخدامه لحفظ مستند بتنسيق Aspose.Diagram.SaveFileFormat. |
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
| [getExportHiddenPage()](#getExportHiddenPage--) | يحدد ما إذا كان يلزم تصدير الصفحة المخفية أم لا. |
| [getPageCount()](#getPageCount--) | عدد الصفحات التي سيتم عرضها في HTML. |
| [getPageIndex()](#getPageIndex--) | الفهرس القائم على الصفر للصفحة الأولى التي سيتم عرضها. |
| [getPageSize()](#getPageSize--) | حجم الصفحة للصور المُولَّدة. |
| [getResolution()](#getResolution--) | دقة الـ HTML المُولَّد، بوحدة النقاط لكل بوصة. |
| [getSaveAsSingleFile()](#getSaveAsSingleFile--) | يحدد ما إذا كان سيتم حفظ الـ HTML كملف واحد. |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | يحدد ما إذا كانت جميع الصفحات ستحفظ كصورة أم فقط المقدمة. |
| [getSaveFormat()](#getSaveFormat--) | يحدد التنسيق الذي ستحفظ به صفحات المخطط المُعالجة إذا تم استخدام كائن خيارات الحفظ هذا. |
| [getSaveTitle()](#getSaveTitle--) | يحدد ما إذا كان يلزم تصدير العنوان أم لا. |
| [getSaveToolBar()](#getSaveToolBar--) | يحدد ما إذا كان شريط الأدوات سيُحفظ. القيمة الافتراضية هي true. |
| [getShapes()](#getShapes--) | الأشكال التي سيتم عرضها. |
| [getStreamProvider()](#getStreamProvider--) | IStreamProvider لتصدير الكائنات. |
| [getTitle()](#getTitle--) | عنوان المخطط الذي سيتم عرضه في HTML. |
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
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getExportHiddenPage()](../../com.aspose.diagram/htmlsaveoptions\#getExportHiddenPage--) |
| [setPageCount(int value)](#setPageCount-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getPageCount()](../../com.aspose.diagram/htmlsaveoptions\#getPageCount--) |
| [setPageIndex(int value)](#setPageIndex-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getPageIndex()](../../com.aspose.diagram/htmlsaveoptions\#getPageIndex--) |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) |
| [setResolution(int value)](#setResolution-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getResolution()](../../com.aspose.diagram/htmlsaveoptions\#getResolution--) |
| [setSaveAsSingleFile(boolean value)](#setSaveAsSingleFile-boolean-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getSaveAsSingleFile()](../../com.aspose.diagram/htmlsaveoptions\#getSaveAsSingleFile--) |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getSaveForegroundPagesOnly()](../../com.aspose.diagram/htmlsaveoptions\#getSaveForegroundPagesOnly--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getSaveFormat()](../../com.aspose.diagram/htmlsaveoptions\#getSaveFormat--) |
| [setSaveTitle(boolean value)](#setSaveTitle-boolean-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getSaveTitle()](../../com.aspose.diagram/htmlsaveoptions\#getSaveTitle--) |
| [setSaveToolBar(boolean value)](#setSaveToolBar-boolean-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getSaveToolBar()](../../com.aspose.diagram/htmlsaveoptions\#getSaveToolBar--) |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) |
| [setStreamProvider(IStreamProvider value)](#setStreamProvider-com.aspose.diagram.IStreamProvider-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getStreamProvider()](../../com.aspose.diagram/htmlsaveoptions\#getStreamProvider--) |
| [setTitle(String value)](#setTitle-java.lang.String-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getTitle()](../../com.aspose.diagram/htmlsaveoptions\#getTitle--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HTMLSaveOptions() {#HTMLSaveOptions--}
```
public HTMLSaveOptions()
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
### getExportHiddenPage() {#getExportHiddenPage--}
```
public boolean getExportHiddenPage()
```


يحدد ما إذا كان يلزم تصدير الصفحة المخفية أم لا. القيمة الافتراضية هي true.

**Returns:**
منطقي
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


عدد الصفحات التي سيتم تصييرها في HTML. القيمة الافتراضية هي MaxValue مما يعني أنه سيتم تصيير جميع صفحات المخطط.

**Returns:**
int
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


الفهرس القائم على الصفر للصفحة الأولى التي سيتم تصييرها. القيمة الافتراضية هي 0.

**Returns:**
int
### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


حجم الصفحة للصور المُولَّدة. يمكن أن يكون [PageSize](../../com.aspose.diagram/pagesize) أو null. القيمة الافتراضية هي null. إذا كان PageSize يساوي null فإن حجم الصفحة للصورة المُولَّدة يُستَخرَج من المخطط المصدر.

**Returns:**
[PageSize](../../com.aspose.diagram/pagesize)
### getResolution() {#getResolution--}
```
public int getResolution()
```


دقة الـ html المُولَّد، بوحدة النقاط في البوصة. هذه الخاصية لها تأثير فقط عند الحفظ إلى html. القيمة الافتراضية هي 96.

**Returns:**
int
### getSaveAsSingleFile() {#getSaveAsSingleFile--}
```
public boolean getSaveAsSingleFile()
```


يُشير إلى ما إذا كان يتم حفظ الـ html كملف واحد. القيمة الافتراضية هي false. إذا كان هناك عدة صفحات، تلك الصفحات والموارد الأخرى تحتاج إلى حفظها في ملفات منفصلة. لبعض السيناريوهات، قد يحتاج المستخدم إلى الحصول على ملف ناتج واحد فقط لتسهيل النقل. إذا كان الأمر كذلك، يمكن للمستخدم ضبط هذه الخاصية إلى true.

**Returns:**
منطقي
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
### getSaveTitle() {#getSaveTitle--}
```
public boolean getSaveTitle()
```


يحدد ما إذا كان يجب تصدير العنوان أم لا. القيمة الافتراضية هي true.

**Returns:**
منطقي
### getSaveToolBar() {#getSaveToolBar--}
```
public boolean getSaveToolBar()
```


يحدد ما إذا كان شريط الأدوات سيُحفظ. القيمة الافتراضية هي true.

**Returns:**
منطقي
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


الأشكال للتصيير. العدد الافتراضي هو 0.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getStreamProvider() {#getStreamProvider--}
```
public IStreamProvider getStreamProvider()
```


IStreamProvider لتصدير الكائنات.

**Returns:**
[IStreamProvider](../../com.aspose.diagram/istreamprovider)
### getTitle() {#getTitle--}
```
public String getTitle()
```


عنوان المخطط لتصيره في HTML. إذا كان Title يساوي null سيتم استخدام Diagram.DocumentProperties.Title [DocumentProperties](../../com.aspose.diagram/documentproperties) كعنوان. إذا كان Diagram.DocumentProperties.Title يساوي null أو فارغ سيتم استخدام اسم ملف Diagram كعنوان.

**Returns:**
java.lang.String
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

### setExportHiddenPage(boolean value) {#setExportHiddenPage-boolean-}
```
public void setExportHiddenPage(boolean value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getExportHiddenPage()](../../com.aspose.diagram/htmlsaveoptions\#getExportHiddenPage--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | منطقي |  |

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getPageCount()](../../com.aspose.diagram/htmlsaveoptions\#getPageCount--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getPageIndex()](../../com.aspose.diagram/htmlsaveoptions\#getPageIndex--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setPageSize(PageSize value) {#setPageSize-com.aspose.diagram.PageSize-}
```
public void setPageSize(PageSize value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PageSize](../../com.aspose.diagram/pagesize) |  |

### setResolution(int value) {#setResolution-int-}
```
public void setResolution(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getResolution()](../../com.aspose.diagram/htmlsaveoptions\#getResolution--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setSaveAsSingleFile(boolean value) {#setSaveAsSingleFile-boolean-}
```
public void setSaveAsSingleFile(boolean value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getSaveAsSingleFile()](../../com.aspose.diagram/htmlsaveoptions\#getSaveAsSingleFile--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | منطقي |  |

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getSaveForegroundPagesOnly()](../../com.aspose.diagram/htmlsaveoptions\#getSaveForegroundPagesOnly--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | منطقي |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getSaveFormat()](../../com.aspose.diagram/htmlsaveoptions\#getSaveFormat--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setSaveTitle(boolean value) {#setSaveTitle-boolean-}
```
public void setSaveTitle(boolean value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getSaveTitle()](../../com.aspose.diagram/htmlsaveoptions\#getSaveTitle--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | منطقي |  |

### setSaveToolBar(boolean value) {#setSaveToolBar-boolean-}
```
public void setSaveToolBar(boolean value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getSaveToolBar()](../../com.aspose.diagram/htmlsaveoptions\#getSaveToolBar--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | منطقي |  |

### setShapes(ShapeCollection value) {#setShapes-com.aspose.diagram.ShapeCollection-}
```
public void setShapes(ShapeCollection value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ShapeCollection](../../com.aspose.diagram/shapecollection) |  |

### setStreamProvider(IStreamProvider value) {#setStreamProvider-com.aspose.diagram.IStreamProvider-}
```
public void setStreamProvider(IStreamProvider value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getStreamProvider()](../../com.aspose.diagram/htmlsaveoptions\#getStreamProvider--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [IStreamProvider](../../com.aspose.diagram/istreamprovider) |  |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getTitle()](../../com.aspose.diagram/htmlsaveoptions\#getTitle--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

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

