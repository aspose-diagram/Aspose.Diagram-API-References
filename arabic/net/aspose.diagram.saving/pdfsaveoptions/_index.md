---
title: PdfSaveOptions
second_title: Aspose.Diagram لمرجع .NET API
description: يسمح بتحديد خيارات إضافية عند تقديم صفحات الرسم التخطيطي إلى PDF.
type: docs
weight: 3410
url: /ar/net/aspose.diagram.saving/pdfsaveoptions/
---
## PdfSaveOptions class

يسمح بتحديد خيارات إضافية عند تقديم صفحات الرسم التخطيطي إلى PDF.

```csharp
public class PdfSaveOptions : RenderingSaveOptions
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions/)() | يقوم بتهيئة مثيل جديد من هذه الفئة يمكن استخدامه لحفظ مستند بتنسيق[`بي دي إف`](../../aspose.diagram/savefileformat/) التنسيق . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Area](../../aspose.diagram.saving/renderingsaveoptions/area/) { get; set; } | الحصول على أو تعيين مساحة الأشكال التي سيتم حفظها . |
| [Compliance](../../aspose.diagram.saving/pdfsaveoptions/compliance/) { get; set; } | مستوى المطابقة المطلوب لمستند PDF الذي تم إنشاؤه. الافتراضي هوPdf15 . |
| virtual [DefaultFont](../../aspose.diagram.saving/saveoptions/defaultfont/) { get; set; } | عندما تكون الأحرف في الرسم التخطيطي أحادية الرمز ولا يتم تعيينها بقيمة الخط الصحيحة أو لم يتم تثبيت الخط محليًا ، قد تظهر ككتلة في pdf أو الصورة أو XPS. قم بتعيين الخط الافتراضي مثل MingLiu أو MS Gothic لإظهار هذه الأحرف . |
| [DigitalSignatureDetails](../../aspose.diagram.saving/pdfsaveoptions/digitalsignaturedetails/) { get; set; } | الحصول على تفاصيل التوقيع الرقمي أو تعيينها. إذا لم يتم التعيين ، فلن يتم تنفيذ أي توقيع. |
| [EmfRenderSetting](../../aspose.diagram.saving/renderingsaveoptions/emfrendersetting/) { get; set; } | إعداد عرض ملف تعريف Emf . |
| [EncryptionDetails](../../aspose.diagram.saving/pdfsaveoptions/encryptiondetails/) { get; set; } | الحصول على تفاصيل التشفير أو تعيينها. إذا لم يتم التعيين ، فلن يتم إجراء أي تشفير. |
| [EnlargePage](../../aspose.diagram.saving/renderingsaveoptions/enlargepage/) { get; set; } | تحديد ما إذا كان تكبير الصفحة . |
| [ExportGuideShapes](../../aspose.diagram.saving/renderingsaveoptions/exportguideshapes/) { get; set; } | يحدد ما إذا كنت بحاجة إلى تصدير أشكال الدليل أم لا. |
| [ExportHiddenPage](../../aspose.diagram.saving/pdfsaveoptions/exporthiddenpage/) { get; set; } | يحدد ما إذا كنت بحاجة إلى تصدير الصفحة المخفية أم لا. |
| [HorizontalResolution](../../aspose.diagram.saving/pdfsaveoptions/horizontalresolution/) { get; set; } | الحصول على الدقة الأفقية أو ضبطها للصور التي تم إنشاؤها ، بالنقاط في البوصة . يطبق طريقة إنشاء الصورة باستثناء الصور بتنسيق Emf. |
| [IsExportComments](../../aspose.diagram.saving/renderingsaveoptions/isexportcomments/) { get; set; } | يحدد ما إذا كنت بحاجة إلى تصدير التعليقات أم لا. |
| [JpegQuality](../../aspose.diagram.saving/pdfsaveoptions/jpegquality/) { get; set; } | يحدد جودة ضغط JPEG للصور (إذا تم استخدام ضغط JPEG) . الافتراضي هو 95. |
| [PageCount](../../aspose.diagram.saving/pdfsaveoptions/pagecount/) { get; set; } | الحصول على أو تعيين عدد الصفحات التي سيتم عرضها في PDF . القيمة الافتراضية هي MaxValue مما يعني أنه سيتم عرض جميع صفحات الرسم التخطيطي. |
| [PageIndex](../../aspose.diagram.saving/pdfsaveoptions/pageindex/) { get; set; } | الحصول على الفهرس الصفري للصفحة الأولى المراد عرضها أو تعيينه. الافتراضي هو 0. |
| [PageSavingCallback](../../aspose.diagram.saving/pdfsaveoptions/pagesavingcallback/) { get; set; } | التحكم / الإشارة إلى تقدم عملية حفظ الصفحة. |
| [PageSize](../../aspose.diagram.saving/renderingsaveoptions/pagesize/) { get; set; } | الحصول على أو تعيين حجم الصفحة للصور المنشأة. يمكن أن يكون[`PageSize`](../pagesize/) أو لاغية. |
| [SaveForegroundPagesOnly](../../aspose.diagram.saving/pdfsaveoptions/saveforegroundpagesonly/) { get; set; } | يحدد ما إذا كان سيتم حفظ جميع الصفحات في صورة أم في المقدمة فقط. |
| override [SaveFormat](../../aspose.diagram.saving/pdfsaveoptions/saveformat/) { get; set; } | يحدد التنسيق الذي سيتم حفظ صفحات الرسم التخطيطي به إذا تم استخدام كائن خيارات الحفظ هذا.[`بي دي إف`](../../aspose.diagram/savefileformat/) فقط . |
| [Shapes](../../aspose.diagram.saving/renderingsaveoptions/shapes/) { get; set; } | الحصول على الأشكال أو تعيينها للعرض. العد الافتراضي هو 0. |
| [SplitMultiPages](../../aspose.diagram.saving/pdfsaveoptions/splitmultipages/) { get; set; } | يحدد ما إذا كان الرسم التخطيطي مقسمًا إلى صفحات متعددة وفقًا لإعداد الصفحة. |
| [TextCompression](../../aspose.diagram.saving/pdfsaveoptions/textcompression/) { get; set; } | يحدد نوع الضغط الذي سيتم استخدامه لجميع تدفقات المحتوى باستثناء الصور. الافتراضي هوFlate . |
| [VerticalResolution](../../aspose.diagram.saving/pdfsaveoptions/verticalresolution/) { get; set; } | الحصول على الدقة الرأسية للصور المُنشأة أو تعيينها ، بالنقاط في البوصة . يطبق طريقة إنشاء الصورة باستثناء صورة بتنسيق Emf. |
| [WarningCallback](../../aspose.diagram.saving/pdfsaveoptions/warningcallback/) { get; set; } | الحصول على رد اتصال التحذير أو تعيينه . |

### أنظر أيضا

* class [RenderingSaveOptions](../renderingsaveoptions/)
* مساحة الاسم [Aspose.Diagram.Saving](../../aspose.diagram.saving/)
* المجسم [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
