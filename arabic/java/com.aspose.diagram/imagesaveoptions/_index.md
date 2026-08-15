---
title: ImageSaveOptions
second_title: Aspose.Diagram لـ Java API Reference
description: يسمح بتحديد خيارات إضافية عند تحويل صفحات المخطط إلى صور.
type: docs
weight: 200
url: /ar/java/com.aspose.diagram/imagesaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class ImageSaveOptions extends RenderingSaveOptions
```

يسمح بتحديد خيارات إضافية عند تحويل صفحات المخطط إلى صور.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [ImageSaveOptions(int saveFormat)](#ImageSaveOptions-int-) | يُنشئ مثيلاً جديداً من هذه الفئة يمكن استخدامه لحفظ الصور المُصَغَّرة بتنسيق Aspose.Diagram.SaveFileFormat، Aspose.Diagram.SaveFileFormat، Aspose.Diagram.SaveFileFormat، Aspose.Diagram.SaveFileFormat أو Aspose.Diagram.SaveFileFormat. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | ينشئ كائن خيارات حفظ من فئة مناسبة لتنسيق الحفظ المحدد. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCompositingQuality()](#getCompositingQuality--) | يحدد مستوى الجودة للاستخدام أثناء التركيب. |
| [getContentZoom()](#getContentZoom--) | هذه المعلمة مشابهة للقياس، لكنها لا تؤثر على حجم الصورة المُولَّدة. |
| [getDefaultFont()](#getDefaultFont--) | عند تكون الأحرف في المخطط يونيكود ولم يتم تعيين قيمة الخط الصحيحة أو لم يتم تثبيت الخط محليًا، قد تظهر ككتل في PDF أو صورة أو XPS. |
| [getEmfRenderSetting()](#getEmfRenderSetting--) | إعداد لتصوير ملف Emf الميتا. |
| [getEnlargePage()](#getEnlargePage--) | يحدد ما إذا كان سيتم تكبير الصفحة. |
| [getExportGuideShapes()](#getExportGuideShapes--) | يحدد ما إذا كان يلزم تصدير أشكال الدليل أم لا. |
| [getExportHiddenPage()](#getExportHiddenPage--) | يحدد ما إذا كان يلزم تصدير الصفحة المخفية أم لا. |
| [getImageBrightness()](#getImageBrightness--) | السطوع للصور المُولَّدة. |
| [getImageColorMode()](#getImageColorMode--) | وضع اللون للصور المُولَّدة. |
| [getImageContrast()](#getImageContrast--) | التباين للصور المُولَّدة. |
| [getInterpolationMode()](#getInterpolationMode--) | يحدد الخوارزمية المستخدمة عند تحجيم أو تدوير الصور. |
| [getJpegQuality()](#getJpegQuality--) | قيمة تحدد جودة صور JPEG المُولَّدة. |
| [getPageCount()](#getPageCount--) | عدد الصفحات التي سيتم عرضها عند الحفظ إلى ملف TIFF متعدد الصفحات. |
| [getPageIndex()](#getPageIndex--) | الفهرس القائم على الصفر للصفحة الأولى التي سيتم عرضها. |
| [getPageSize()](#getPageSize--) | حجم الصفحة للصور المُولَّدة. |
| [getPixelOffsetMode()](#getPixelOffsetMode--) | قيمة تحدد كيفية إزاحة البكسلات أثناء العرض. |
| [getResolution()](#getResolution--) | الدقة للصور المُولَّدة، بوحدة النقاط في البوصة. |
| [getSameAsPdfConversionArea()](#getSameAsPdfConversionArea--) | يحدد ما إذا كانت مساحة الحفظ هي نفسها مثل PDF. |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | يحدد ما إذا كانت جميع الصفحات ستحفظ كصورة أم فقط المقدمة. |
| [getSaveFormat()](#getSaveFormat--) | يحدد التنسيق الذي ستحفظ به صفحات المخطط المُعالجة إذا تم استخدام كائن خيارات الحفظ هذا. |
| [getScale()](#getScale--) | عامل التكبير للصور المُولَّدة. |
| [getShapes()](#getShapes--) | الأشكال التي سيتم عرضها. |
| [getSmoothingMode()](#getSmoothingMode--) | يحدد ما إذا كان يتم تطبيق التنعيم (مضاد التعرج) على الخطوط والمنحنيات وحواف المناطق المملوءة. |
| [getTiffCompression()](#getTiffCompression--) | نوع الضغط الذي يُطبق عند حفظ الصور المُولَّدة بتنسيق TIFF. |
| [getWarningCallback()](#getWarningCallback--) | دالة رد النداء للتحذير. |
| [hashCode()](#hashCode--) |  |
| [isExportComments()](#isExportComments--) | يحدد ما إذا كان يلزم تصدير التعليقات أم لا. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompositingQuality(int value)](#setCompositingQuality-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getCompositingQuality()](../../com.aspose.diagram/imagesaveoptions\#getCompositingQuality--) |
| [setContentZoom(float value)](#setContentZoom-float-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getContentZoom()](../../com.aspose.diagram/imagesaveoptions\#getContentZoom--) |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | للوصف الخاص بهذه الخاصية، يرجى الاطلاع على [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setEmfRenderSetting(int value)](#setEmfRenderSetting-int-) | للوصف الخاص بهذه الخاصية، يرجى الاطلاع على [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--) |
| [setEnlargePage(boolean value)](#setEnlargePage-boolean-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--) |
| [setExportComments(boolean value)](#setExportComments-boolean-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--) |
| [setExportGuideShapes(boolean value)](#setExportGuideShapes-boolean-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--) |
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getExportHiddenPage()](../../com.aspose.diagram/imagesaveoptions\#getExportHiddenPage--) |
| [setImageBrightness(float value)](#setImageBrightness-float-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getImageBrightness()](../../com.aspose.diagram/imagesaveoptions\#getImageBrightness--) |
| [setImageColorMode(int value)](#setImageColorMode-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getImageColorMode()](../../com.aspose.diagram/imagesaveoptions\#getImageColorMode--) |
| [setImageContrast(float value)](#setImageContrast-float-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getImageContrast()](../../com.aspose.diagram/imagesaveoptions\#getImageContrast--) |
| [setInterpolationMode(int value)](#setInterpolationMode-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getInterpolationMode()](../../com.aspose.diagram/imagesaveoptions\#getInterpolationMode--) |
| [setJpegQuality(int value)](#setJpegQuality-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getJpegQuality()](../../com.aspose.diagram/imagesaveoptions\#getJpegQuality--) |
| [setPageCount(int value)](#setPageCount-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getPageCount()](../../com.aspose.diagram/imagesaveoptions\#getPageCount--) |
| [setPageIndex(int value)](#setPageIndex-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getPageIndex()](../../com.aspose.diagram/imagesaveoptions\#getPageIndex--) |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) |
| [setPixelOffsetMode(int value)](#setPixelOffsetMode-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getPixelOffsetMode()](../../com.aspose.diagram/imagesaveoptions\#getPixelOffsetMode--) |
| [setResolution(float value)](#setResolution-float-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getResolution()](../../com.aspose.diagram/imagesaveoptions\#getResolution--) |
| [setSameAsPdfConversionArea(boolean value)](#setSameAsPdfConversionArea-boolean-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getSameAsPdfConversionArea()](../../com.aspose.diagram/imagesaveoptions\#getSameAsPdfConversionArea--) |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getSaveForegroundPagesOnly()](../../com.aspose.diagram/imagesaveoptions\#getSaveForegroundPagesOnly--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getSaveFormat()](../../com.aspose.diagram/imagesaveoptions\#getSaveFormat--) |
| [setScale(float value)](#setScale-float-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getScale()](../../com.aspose.diagram/imagesaveoptions\#getScale--) |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) |
| [setSmoothingMode(int value)](#setSmoothingMode-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getSmoothingMode()](../../com.aspose.diagram/imagesaveoptions\#getSmoothingMode--) |
| [setTiffCompression(int value)](#setTiffCompression-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getTiffCompression()](../../com.aspose.diagram/imagesaveoptions\#getTiffCompression--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImageSaveOptions(int saveFormat) {#ImageSaveOptions-int-}
```
public ImageSaveOptions(int saveFormat)
```


يُنشئ مثيلاً جديداً من هذه الفئة يمكن استخدامه لحفظ الصور المُصَغَّرة بتنسيق Aspose.Diagram.SaveFileFormat، Aspose.Diagram.SaveFileFormat، Aspose.Diagram.SaveFileFormat، Aspose.Diagram.SaveFileFormat أو Aspose.Diagram.SaveFileFormat.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| saveFormat | int | يمكن أن يكون Aspose.Diagram.SaveFileFormat، Aspose.Diagram.SaveFileFormat، Aspose.Diagram.SaveFileFormat، Aspose.Diagram.SaveFileFormat أو Aspose.Diagram.SaveFileFormat. |

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
### getCompositingQuality() {#getCompositingQuality--}
```
public int getCompositingQuality()
```


يحدد مستوى الجودة الذي يُستخدم أثناء التركيب. هذه الخاصية لها تأثير فقط عند الحفظ إلى تنسيقات الصور النقطية. القيمة الافتراضية هي Aspose.Diagram.Saving.CompositingQuality.

**Returns:**
int
### getContentZoom() {#getContentZoom--}
```
public float getContentZoom()
```


هذه المعلمة مشابهة للمعامل scale، لكنها لا تؤثر على حجم الصورة المُولدة. القيمة الافتراضية هي 1.0. يجب أن تكون القيمة أكبر من 0.

**Returns:**
float
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
### getImageBrightness() {#getImageBrightness--}
```
public float getImageBrightness()
```


السطوع للصور المُولدة. هذه الخاصية لها تأثير فقط عند الحفظ إلى تنسيقات الصور النقطية. القيمة الافتراضية هي 0.5. يجب أن تكون القيمة ضمن النطاق بين 0 و 1.

**Returns:**
float
### getImageColorMode() {#getImageColorMode--}
```
public int getImageColorMode()
```


وضع اللون للصور المُولدة. هذه الخاصية لها تأثير فقط عند الحفظ إلى تنسيقات الصور النقطية. القيمة الافتراضية هي Aspose.Diagram.Saving.ImageColorMode.

**Returns:**
int
### getImageContrast() {#getImageContrast--}
```
public float getImageContrast()
```


التباين للصور المُولدة. هذه الخاصية لها تأثير فقط عند الحفظ إلى تنسيقات الصور النقطية. القيمة الافتراضية هي 0.5. يجب أن تكون القيمة ضمن النطاق بين 0 و 1.

**Returns:**
float
### getInterpolationMode() {#getInterpolationMode--}
```
public int getInterpolationMode()
```


يحدد الخوارزمية المستخدمة عند تحجيم أو تدوير الصور. هذه الخاصية لها تأثير فقط عند الحفظ إلى تنسيقات الصور النقطية. القيمة الافتراضية هي Aspose.Diagram.Saving.InterpolationMode.

**Returns:**
int
### getJpegQuality() {#getJpegQuality--}
```
public int getJpegQuality()
```


قيمة تحدد جودة صور JPEG المُولدة. لها تأثير فقط عند الحفظ إلى JPEG. استخدم هذه الخاصية للحصول على جودة الصور المُولدة أو تعيينها عند الحفظ بتنسيق JPEG. قد تتراوح القيمة من 0 إلى 100 حيث 0 تعني أسوأ جودة ولكن أقصى ضغط و100 تعني أفضل جودة ولكن أقل ضغط. القيمة الافتراضية هي 95.

**Returns:**
int
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


عدد الصفحات التي سيتم عرضها عند الحفظ إلى ملف TIFF متعدد الصفحات. القيمة الافتراضية هي MaxValue مما يعني أنه سيتم عرض جميع صفحات المخطط.

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
### getPixelOffsetMode() {#getPixelOffsetMode--}
```
public int getPixelOffsetMode()
```


قيمة تحدد كيفية إزاحة البكسلات أثناء العرض. هذه الخاصية لها تأثير فقط عند الحفظ إلى تنسيقات الصور النقطية. القيمة الافتراضية هي Aspose.Diagram.Saving.PixelOffsetMode.

**Returns:**
int
### getResolution() {#getResolution--}
```
public float getResolution()
```


الدقة للصور المُولدة، بوحدة النقاط في البوصة. هذه الخاصية لها تأثير فقط عند الحفظ إلى تنسيقات الصور النقطية. القيمة الافتراضية هي 96.

**Returns:**
float
### getSameAsPdfConversionArea() {#getSameAsPdfConversionArea--}
```
public boolean getSameAsPdfConversionArea()
```


يحدد ما إذا كانت منطقة الحفظ هي نفسها كما في PDF. إذا كانت true - تكون المنطقة المعروضة هي نفسها كما في PDF. إذا كانت false - تكون المنطقة المعروضة هي الافتراضية. القيمة الافتراضية هي false.

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


يحدد التنسيق الذي سيتم حفظ صفحات المخطط المعروضة به إذا تم استخدام كائن خيارات الحفظ هذا. يمكن أن يكون Aspose.Diagram.SaveFileFormat أو Aspose.Diagram.SaveFileFormat أو Aspose.Diagram.SaveFileFormat أو Aspose.Diagram.SaveFileFormat أو Aspose.Diagram.SaveFileFormat.

**Returns:**
int
### getScale() {#getScale--}
```
public float getScale()
```


عامل التكبير للصور المُولدة. القيمة الافتراضية هي 1.0. يجب أن تكون القيمة أكبر من 0.

**Returns:**
float
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


الأشكال للتصيير. العدد الافتراضي هو 0.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getSmoothingMode() {#getSmoothingMode--}
```
public int getSmoothingMode()
```


يحدد ما إذا كان يتم تطبيق التنعيم (مضاد التعرج) على الخطوط والمنحنيات وحواف المناطق المملوءة. هذه الخاصية لها تأثير فقط عند الحفظ إلى تنسيقات الصور النقطية. القيمة الافتراضية هي Aspose.Diagram.Saving.SmoothingMode.

**Returns:**
int
### getTiffCompression() {#getTiffCompression--}
```
public int getTiffCompression()
```


نوع الضغط الذي يُطبق عند حفظ الصور المُولدة بتنسيق TIFF. له تأثير فقط عند الحفظ إلى TIFF. القيمة الافتراضية هي Aspose.Diagram.Saving.TiffCompression.

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




### setCompositingQuality(int value) {#setCompositingQuality-int-}
```
public void setCompositingQuality(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getCompositingQuality()](../../com.aspose.diagram/imagesaveoptions\#getCompositingQuality--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setContentZoom(float value) {#setContentZoom-float-}
```
public void setContentZoom(float value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getContentZoom()](../../com.aspose.diagram/imagesaveoptions\#getContentZoom--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | float |  |

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


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getExportHiddenPage()](../../com.aspose.diagram/imagesaveoptions\#getExportHiddenPage--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | منطقي |  |

### setImageBrightness(float value) {#setImageBrightness-float-}
```
public void setImageBrightness(float value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getImageBrightness()](../../com.aspose.diagram/imagesaveoptions\#getImageBrightness--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | float |  |

### setImageColorMode(int value) {#setImageColorMode-int-}
```
public void setImageColorMode(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getImageColorMode()](../../com.aspose.diagram/imagesaveoptions\#getImageColorMode--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setImageContrast(float value) {#setImageContrast-float-}
```
public void setImageContrast(float value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getImageContrast()](../../com.aspose.diagram/imagesaveoptions\#getImageContrast--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | float |  |

### setInterpolationMode(int value) {#setInterpolationMode-int-}
```
public void setInterpolationMode(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getInterpolationMode()](../../com.aspose.diagram/imagesaveoptions\#getInterpolationMode--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public void setJpegQuality(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getJpegQuality()](../../com.aspose.diagram/imagesaveoptions\#getJpegQuality--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getPageCount()](../../com.aspose.diagram/imagesaveoptions\#getPageCount--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getPageIndex()](../../com.aspose.diagram/imagesaveoptions\#getPageIndex--)

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

### setPixelOffsetMode(int value) {#setPixelOffsetMode-int-}
```
public void setPixelOffsetMode(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getPixelOffsetMode()](../../com.aspose.diagram/imagesaveoptions\#getPixelOffsetMode--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setResolution(float value) {#setResolution-float-}
```
public void setResolution(float value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getResolution()](../../com.aspose.diagram/imagesaveoptions\#getResolution--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | float |  |

### setSameAsPdfConversionArea(boolean value) {#setSameAsPdfConversionArea-boolean-}
```
public void setSameAsPdfConversionArea(boolean value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getSameAsPdfConversionArea()](../../com.aspose.diagram/imagesaveoptions\#getSameAsPdfConversionArea--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | منطقي |  |

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getSaveForegroundPagesOnly()](../../com.aspose.diagram/imagesaveoptions\#getSaveForegroundPagesOnly--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | منطقي |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getSaveFormat()](../../com.aspose.diagram/imagesaveoptions\#getSaveFormat--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setScale(float value) {#setScale-float-}
```
public void setScale(float value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getScale()](../../com.aspose.diagram/imagesaveoptions\#getScale--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | float |  |

### setShapes(ShapeCollection value) {#setShapes-com.aspose.diagram.ShapeCollection-}
```
public void setShapes(ShapeCollection value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ShapeCollection](../../com.aspose.diagram/shapecollection) |  |

### setSmoothingMode(int value) {#setSmoothingMode-int-}
```
public void setSmoothingMode(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getSmoothingMode()](../../com.aspose.diagram/imagesaveoptions\#getSmoothingMode--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setTiffCompression(int value) {#setTiffCompression-int-}
```
public void setTiffCompression(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getTiffCompression()](../../com.aspose.diagram/imagesaveoptions\#getTiffCompression--)

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

