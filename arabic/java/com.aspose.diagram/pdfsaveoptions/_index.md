---
title: PdfSaveOptions
second_title: Aspose.Diagram لـ Java API Reference
description: يسمح بتحديد خيارات إضافية عند تحويل صفحات المخطط إلى PDF.
type: docs
weight: 281
url: /ar/java/com.aspose.diagram/pdfsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class PdfSaveOptions extends RenderingSaveOptions
```

يسمح بتحديد خيارات إضافية عند تحويل صفحات المخطط إلى PDF.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PdfSaveOptions()](#PdfSaveOptions--) | يُنشئ مثيلاً جديدًا من هذه الفئة يمكن استخدامه لحفظ مستند بتنسيق Aspose.Diagram.SaveFileFormat. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | ينشئ كائن خيارات حفظ من فئة مناسبة لتنسيق الحفظ المحدد. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCompliance()](#getCompliance--) | مستوى التوافق المطلوب للمستند PDF المُنشأ. |
| [getDefaultFont()](#getDefaultFont--) | عند تكون الأحرف في المخطط يونيكود ولم يتم تعيين قيمة الخط الصحيحة أو لم يتم تثبيت الخط محليًا، قد تظهر ككتل في PDF أو صورة أو XPS. |
| [getEmfRenderSetting()](#getEmfRenderSetting--) | إعداد لتصوير ملف Emf الميتا. |
| [getEncryptionDetails()](#getEncryptionDetails--) | تفاصيل التشفير. |
| [getEnlargePage()](#getEnlargePage--) | يحدد ما إذا كان سيتم تكبير الصفحة. |
| [getExportGuideShapes()](#getExportGuideShapes--) | يحدد ما إذا كان يلزم تصدير أشكال الدليل أم لا. |
| [getExportHiddenPage()](#getExportHiddenPage--) | يحدد ما إذا كان يلزم تصدير الصفحة المخفية أم لا. |
| [getHorizontalResolution()](#getHorizontalResolution--) | دقة الأفقية للصور المولدة، بوحدة النقاط في البوصة. |
| [getJpegQuality()](#getJpegQuality--) | يحدد جودة ضغط JPEG للصور (في حال استخدام ضغط JPEG). |
| [getPageCount()](#getPageCount--) | عدد الصفحات التي سيتم عرضها في PDF. |
| [getPageIndex()](#getPageIndex--) | الفهرس القائم على الصفر للصفحة الأولى التي سيتم عرضها. |
| [getPageSavingCallback()](#getPageSavingCallback--) | التحكم/الإشارة إلى تقدم عملية حفظ الصفحة. |
| [getPageSize()](#getPageSize--) | حجم الصفحة للصور المُولَّدة. |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | يحدد ما إذا كانت جميع الصفحات ستحفظ كصورة أم فقط المقدمة. |
| [getSaveFormat()](#getSaveFormat--) | يحدد التنسيق الذي ستحفظ به صفحات المخطط المُعالجة إذا تم استخدام كائن خيارات الحفظ هذا. |
| [getShapes()](#getShapes--) | الأشكال التي سيتم عرضها. |
| [getSplitMultiPages()](#getSplitMultiPages--) | يحدد ما إذا كان سيتم تقسيم المخطط إلى صفحات متعددة وفقًا لإعدادات الصفحة. |
| [getTextCompression()](#getTextCompression--) | يحدد نوع الضغط الذي سيُستخدم لجميع تدفقات المحتوى باستثناء الصور. |
| [getVerticalResolution()](#getVerticalResolution--) | دقة العمودية للصور المولدة، بوحدة النقاط في البوصة. |
| [getWarningCallback()](#getWarningCallback--) | دالة رد النداء للتحذير. |
| [hashCode()](#hashCode--) |  |
| [isExportComments()](#isExportComments--) | يحدد ما إذا كان يلزم تصدير التعليقات أم لا. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompliance(int value)](#setCompliance-int-) | لوصف هذه الخاصية، يرجى الاطلاع على [getCompliance()](../../com.aspose.diagram/pdfsaveoptions\#getCompliance--) |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | للوصف الخاص بهذه الخاصية، يرجى الاطلاع على [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setEmfRenderSetting(int value)](#setEmfRenderSetting-int-) | للوصف الخاص بهذه الخاصية، يرجى الاطلاع على [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--) |
| [setEncryptionDetails(PdfEncryptionDetails value)](#setEncryptionDetails-com.aspose.diagram.PdfEncryptionDetails-) | لوصف هذه الخاصية، يرجى الاطلاع على [getEncryptionDetails()](../../com.aspose.diagram/pdfsaveoptions\#getEncryptionDetails--) |
| [setEnlargePage(boolean value)](#setEnlargePage-boolean-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--) |
| [setExportComments(boolean value)](#setExportComments-boolean-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--) |
| [setExportGuideShapes(boolean value)](#setExportGuideShapes-boolean-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--) |
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | لوصف هذه الخاصية، يرجى الاطلاع على [getExportHiddenPage()](../../com.aspose.diagram/pdfsaveoptions\#getExportHiddenPage--) |
| [setHorizontalResolution(int value)](#setHorizontalResolution-int-) | لوصف هذه الخاصية، يرجى الاطلاع على [getHorizontalResolution()](../../com.aspose.diagram/pdfsaveoptions\#getHorizontalResolution--) |
| [setJpegQuality(int value)](#setJpegQuality-int-) | لوصف هذه الخاصية، يرجى الاطلاع على [getJpegQuality()](../../com.aspose.diagram/pdfsaveoptions\#getJpegQuality--) |
| [setPageCount(int value)](#setPageCount-int-) | لوصف هذه الخاصية، يرجى الاطلاع على [getPageCount()](../../com.aspose.diagram/pdfsaveoptions\#getPageCount--) |
| [setPageIndex(int value)](#setPageIndex-int-) | لوصف هذه الخاصية، يرجى الاطلاع على [getPageIndex()](../../com.aspose.diagram/pdfsaveoptions\#getPageIndex--) |
| [setPageSavingCallback(IPageSavingCallback value)](#setPageSavingCallback-com.aspose.diagram.IPageSavingCallback-) | لوصف هذه الخاصية، يرجى الاطلاع على [getPageSavingCallback()](../../com.aspose.diagram/pdfsaveoptions\#getPageSavingCallback--) |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | لوصف هذه الخاصية، يرجى الاطلاع على [getSaveForegroundPagesOnly()](../../com.aspose.diagram/pdfsaveoptions\#getSaveForegroundPagesOnly--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | لوصف هذه الخاصية، يرجى الاطلاع على [getSaveFormat()](../../com.aspose.diagram/pdfsaveoptions\#getSaveFormat--) |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) |
| [setSplitMultiPages(boolean value)](#setSplitMultiPages-boolean-) | لوصف هذه الخاصية، يرجى الاطلاع على [getSplitMultiPages()](../../com.aspose.diagram/pdfsaveoptions\#getSplitMultiPages--) |
| [setTextCompression(int value)](#setTextCompression-int-) | لوصف هذه الخاصية، يرجى الاطلاع على [getTextCompression()](../../com.aspose.diagram/pdfsaveoptions\#getTextCompression--) |
| [setVerticalResolution(int value)](#setVerticalResolution-int-) | لوصف هذه الخاصية، يرجى الاطلاع على [getVerticalResolution()](../../com.aspose.diagram/pdfsaveoptions\#getVerticalResolution--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
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
### getCompliance() {#getCompliance--}
```
public int getCompliance()
```


مستوى التوافق المطلوب للمستند PDF المولد. القيمة الافتراضية هي PdfCompliance.PDF\_15.

**Returns:**
int
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
### getEncryptionDetails() {#getEncryptionDetails--}
```
public PdfEncryptionDetails getEncryptionDetails()
```


تفاصيل التشفير. إذا لم يتم تعيينها، فلن يتم تنفيذ أي تشفير.

**Returns:**
[PdfEncryptionDetails](../../com.aspose.diagram/pdfencryptiondetails)
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
### getHorizontalResolution() {#getHorizontalResolution--}
```
public int getHorizontalResolution()
```


دقة الأفقية للصور المولدة، بوحدة النقاط في البوصة. ينطبق على طريقة توليد الصور باستثناء صور تنسيق Emf. القيمة الافتراضية هي 96.

**Returns:**
int
### getJpegQuality() {#getJpegQuality--}
```
public int getJpegQuality()
```


يحدد جودة ضغط JPEG للصور (في حال استخدام ضغط JPEG). القيمة الافتراضية هي 95.

**Returns:**
int
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


عدد الصفحات التي سيتم عرضها في PDF. القيمة الافتراضية هي MaxValue مما يعني أنه سيتم عرض جميع صفحات المخطط.

**Returns:**
int
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


الفهرس القائم على الصفر للصفحة الأولى التي سيتم تصييرها. القيمة الافتراضية هي 0.

**Returns:**
int
### getPageSavingCallback() {#getPageSavingCallback--}
```
public IPageSavingCallback getPageSavingCallback()
```


التحكم/الإشارة إلى تقدم عملية حفظ الصفحة.

**Returns:**
[IPageSavingCallback](../../com.aspose.diagram/ipagesavingcallback)
### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


حجم الصفحة للصور المُولَّدة. يمكن أن يكون [PageSize](../../com.aspose.diagram/pagesize) أو null. القيمة الافتراضية هي null. إذا كان PageSize يساوي null فإن حجم الصفحة للصورة المُولَّدة يُستَخرَج من المخطط المصدر.

**Returns:**
[PageSize](../../com.aspose.diagram/pagesize)
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
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


الأشكال للتصيير. العدد الافتراضي هو 0.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getSplitMultiPages() {#getSplitMultiPages--}
```
public boolean getSplitMultiPages()
```


يحدد ما إذا كان سيتم تقسيم المخطط إلى صفحات متعددة وفقًا لإعدادات الصفحة. القيمة الافتراضية هي false.

**Returns:**
منطقي
### getTextCompression() {#getTextCompression--}
```
public int getTextCompression()
```


يحدد نوع الضغط الذي سيُستخدم لجميع تدفقات المحتوى باستثناء الصور. الافتراضي هو PdfTextCompression.FLATE.

**Returns:**
int
### getVerticalResolution() {#getVerticalResolution--}
```
public int getVerticalResolution()
```


الدقة العمودية للصور المُولَّدة، بوحدة النقاط في البوصة. يُطبق على طريقة إنشاء الصورة باستثناء صورة بتنسيق Emf. القيمة الافتراضية هي 96.

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




### setCompliance(int value) {#setCompliance-int-}
```
public void setCompliance(int value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getCompliance()](../../com.aspose.diagram/pdfsaveoptions\#getCompliance--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

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

### setEncryptionDetails(PdfEncryptionDetails value) {#setEncryptionDetails-com.aspose.diagram.PdfEncryptionDetails-}
```
public void setEncryptionDetails(PdfEncryptionDetails value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getEncryptionDetails()](../../com.aspose.diagram/pdfsaveoptions\#getEncryptionDetails--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PdfEncryptionDetails](../../com.aspose.diagram/pdfencryptiondetails) |  |

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


لوصف هذه الخاصية، يرجى الاطلاع على [getExportHiddenPage()](../../com.aspose.diagram/pdfsaveoptions\#getExportHiddenPage--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | منطقي |  |

### setHorizontalResolution(int value) {#setHorizontalResolution-int-}
```
public void setHorizontalResolution(int value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getHorizontalResolution()](../../com.aspose.diagram/pdfsaveoptions\#getHorizontalResolution--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public void setJpegQuality(int value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getJpegQuality()](../../com.aspose.diagram/pdfsaveoptions\#getJpegQuality--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getPageCount()](../../com.aspose.diagram/pdfsaveoptions\#getPageCount--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getPageIndex()](../../com.aspose.diagram/pdfsaveoptions\#getPageIndex--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setPageSavingCallback(IPageSavingCallback value) {#setPageSavingCallback-com.aspose.diagram.IPageSavingCallback-}
```
public void setPageSavingCallback(IPageSavingCallback value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getPageSavingCallback()](../../com.aspose.diagram/pdfsaveoptions\#getPageSavingCallback--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [IPageSavingCallback](../../com.aspose.diagram/ipagesavingcallback) |  |

### setPageSize(PageSize value) {#setPageSize-com.aspose.diagram.PageSize-}
```
public void setPageSize(PageSize value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PageSize](../../com.aspose.diagram/pagesize) |  |

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getSaveForegroundPagesOnly()](../../com.aspose.diagram/pdfsaveoptions\#getSaveForegroundPagesOnly--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | منطقي |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getSaveFormat()](../../com.aspose.diagram/pdfsaveoptions\#getSaveFormat--)

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

### setSplitMultiPages(boolean value) {#setSplitMultiPages-boolean-}
```
public void setSplitMultiPages(boolean value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getSplitMultiPages()](../../com.aspose.diagram/pdfsaveoptions\#getSplitMultiPages--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | منطقي |  |

### setTextCompression(int value) {#setTextCompression-int-}
```
public void setTextCompression(int value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getTextCompression()](../../com.aspose.diagram/pdfsaveoptions\#getTextCompression--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setVerticalResolution(int value) {#setVerticalResolution-int-}
```
public void setVerticalResolution(int value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getVerticalResolution()](../../com.aspose.diagram/pdfsaveoptions\#getVerticalResolution--)

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

