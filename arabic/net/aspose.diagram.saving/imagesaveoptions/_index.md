---
title: ImageSaveOptions
second_title: Aspose.Diagram لمرجع .NET API
description: يسمح بتحديد خيارات إضافية عند عرض صفحات الرسم التخطيطي للصور.
type: docs
weight: 3280
url: /ar/net/aspose.diagram.saving/imagesaveoptions/
---
## ImageSaveOptions class

يسمح بتحديد خيارات إضافية عند عرض صفحات الرسم التخطيطي للصور.

```csharp
public class ImageSaveOptions : RenderingSaveOptions
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [ImageSaveOptions](imagesaveoptions/)(SaveFileFormat) | يقوم بتهيئة مثيل جديد من هذه الفئة يمكن استخدامه لحفظ الصور المعروضة في ملف[`شجار`](../../aspose.diagram/savefileformat/) ، [`بي إن جي`](../../aspose.diagram/savefileformat/) و[`بمب`](../../aspose.diagram/savefileformat/) و[`إمف`](../../aspose.diagram/savefileformat/) أو[`JPEG`](../../aspose.diagram/savefileformat/) التنسيق . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Area](../../aspose.diagram.saving/renderingsaveoptions/area/) { get; set; } | الحصول على أو تعيين مساحة الأشكال التي سيتم حفظها . |
| [CompositingQuality](../../aspose.diagram.saving/imagesaveoptions/compositingquality/) { get; set; } | يحدد مستوى الجودة لاستخدامه أثناء التركيب. |
| [ContentZoom](../../aspose.diagram.saving/imagesaveoptions/contentzoom/) { get; set; } | تتشابه هذه المعلمة مع المقياس ، ولكنها لا تؤثر على حجم الصورة التي تم إنشاؤها. |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont/) { get; set; } | عندما تكون الأحرف في الرسم التخطيطي أحادية الرمز ولا يتم تعيينها بقيمة الخط الصحيحة أو لم يتم تثبيت الخط محليًا ، قد تظهر ككتلة في pdf أو الصورة أو XPS. قم بتعيين الخط الافتراضي مثل MingLiu أو MS Gothic لإظهار هذه الأحرف . |
| [EmfRenderSetting](../../aspose.diagram.saving/renderingsaveoptions/emfrendersetting/) { get; set; } | إعداد عرض ملف تعريف Emf . |
| [EnlargePage](../../aspose.diagram.saving/renderingsaveoptions/enlargepage/) { get; set; } | تحديد ما إذا كان تكبير الصفحة . |
| [ExportGuideShapes](../../aspose.diagram.saving/renderingsaveoptions/exportguideshapes/) { get; set; } | يحدد ما إذا كنت بحاجة إلى تصدير أشكال الدليل أم لا. |
| [ExportHiddenPage](../../aspose.diagram.saving/imagesaveoptions/exporthiddenpage/) { get; set; } | يحدد ما إذا كنت بحاجة إلى تصدير الصفحة المخفية أم لا. |
| [ImageBrightness](../../aspose.diagram.saving/imagesaveoptions/imagebrightness/) { get; set; } | الحصول على أو ضبط سطوع الصور التي تم إنشاؤها. |
| [ImageColorMode](../../aspose.diagram.saving/imagesaveoptions/imagecolormode/) { get; set; } | الحصول على أو تحديد وضع الألوان للصور التي تم إنشاؤها. |
| [ImageContrast](../../aspose.diagram.saving/imagesaveoptions/imagecontrast/) { get; set; } | الحصول على أو تعيين التباين للصور التي تم إنشاؤها. |
| [InterpolationMode](../../aspose.diagram.saving/imagesaveoptions/interpolationmode/) { get; set; } | يحدد الخوارزمية المستخدمة عند قياس الصور أو تدويرها. |
| [IsExportComments](../../aspose.diagram.saving/renderingsaveoptions/isexportcomments/) { get; set; } | يحدد ما إذا كنت بحاجة إلى تصدير التعليقات أم لا. |
| [JpegQuality](../../aspose.diagram.saving/imagesaveoptions/jpegquality/) { get; set; } | الحصول على أو تعيين قيمة تحدد جودة صور JPEG التي تم إنشاؤها. |
| [PageCount](../../aspose.diagram.saving/imagesaveoptions/pagecount/) { get; set; } | الحصول على أو تعيين عدد الصفحات التي سيتم عرضها عند الحفظ في ملف TIFF متعدد الصفحات. القيمة الافتراضية هي MaxValue مما يعني أنه سيتم عرض جميع صفحات الرسم التخطيطي. |
| [PageIndex](../../aspose.diagram.saving/imagesaveoptions/pageindex/) { get; set; } | الحصول على الفهرس الصفري للصفحة الأولى المراد عرضها أو تعيينه. الافتراضي هو 0. |
| [PageSize](../../aspose.diagram.saving/renderingsaveoptions/pagesize/) { get; set; } | الحصول على أو تعيين حجم الصفحة للصور المنشأة. يمكن أن يكون[`PageSize`](../pagesize/) أو لاغية. |
| [PixelOffsetMode](../../aspose.diagram.saving/imagesaveoptions/pixeloffsetmode/) { get; set; } | الحصول على قيمة أو تعيينها لتحديد كيفية إزاحة وحدات البكسل أثناء العرض. |
| [Resolution](../../aspose.diagram.saving/imagesaveoptions/resolution/) { get; set; } | الحصول على أو تعيين دقة الصور التي تم إنشاؤها ، بالنقاط في البوصة . |
| [SameAsPdfConversionArea](../../aspose.diagram.saving/imagesaveoptions/sameaspdfconversionarea/) { get; set; } | يحدد ما إذا كان حفظ المساحة مثل pdf . |
| [SaveForegroundPagesOnly](../../aspose.diagram.saving/imagesaveoptions/saveforegroundpagesonly/) { get; set; } | يحدد ما إذا كان سيتم حفظ جميع الصفحات في صورة أم في المقدمة فقط. |
| override [SaveFormat](../../aspose.diagram.saving/imagesaveoptions/saveformat/) { get; set; } | يحدد التنسيق الذي سيتم حفظ صفحات الرسم التخطيطي به إذا تم استخدام كائن خيارات الحفظ هذا.[`شجار`](../../aspose.diagram/savefileformat/) و[`بي إن جي`](../../aspose.diagram/savefileformat/) ، [`بمب`](../../aspose.diagram/savefileformat/) و[`إمف`](../../aspose.diagram/savefileformat/) أو[`JPEG`](../../aspose.diagram/savefileformat/) . |
| [Scale](../../aspose.diagram.saving/imagesaveoptions/scale/) { get; set; } | الحصول على أو تحديد عامل التكبير / التصغير للصور التي تم إنشاؤها. |
| [Shapes](../../aspose.diagram.saving/renderingsaveoptions/shapes/) { get; set; } | الحصول على الأشكال أو تعيينها للعرض. العد الافتراضي هو 0. |
| [SmoothingMode](../../aspose.diagram.saving/imagesaveoptions/smoothingmode/) { get; set; } | يحدد ما إذا كان التنعيم (منع الحواف) مطبقًا على الخطوط والمنحنيات وحواف المساحات المعبأة. |
| [TiffCompression](../../aspose.diagram.saving/imagesaveoptions/tiffcompression/) { get; set; } | الحصول على أو تحديد نوع الضغط المراد تطبيقه عند حفظ الصور المُنشأة بتنسيق TIFF. |
| [WarningCallback](../../aspose.diagram.saving/saveoptions/warningcallback/) { get; set; } | الحصول على رد اتصال التحذير أو تعيينه . |

### أنظر أيضا

* class [RenderingSaveOptions](../renderingsaveoptions/)
* مساحة الاسم [Aspose.Diagram.Saving](../../aspose.diagram.saving/)
* المجسم [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
