---
title: PageLayout
second_title: Aspose.Diagram لمرجع .NET API
description: يحتوي على خلايا تتحكم في إعدادات تخطيط الصفحة للأشكال والموصلات  مثل التباعد بين جميع الأشكال على الصفحة  والتباعد بين كافة الموصلات على الصفحة  ونمط التوجيه لكافة الموصلات على الصفحة .
type: docs
weight: 2510
url: /ar/net/aspose.diagram/pagelayout/
---
## PageLayout class

يحتوي على خلايا تتحكم في إعدادات تخطيط الصفحة للأشكال والموصلات ، مثل التباعد بين جميع الأشكال على الصفحة ، والتباعد بين كافة الموصلات على الصفحة ، ونمط التوجيه لكافة الموصلات على الصفحة .

```csharp
public class PageLayout
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [AvenueSizeX](../../aspose.diagram/pagelayout/avenuesizex/) { get; } | تحديد مقدار المسافة العمودية بين الأشكال الموجودة على صفحة الرسم عند استخدام Microsoft Visio لتخطيط الأشكال على صفحة الرسم. |
| [AvenueSizeY](../../aspose.diagram/pagelayout/avenuesizey/) { get; } | تحديد مقدار المسافة العمودية بين الأشكال الموجودة على صفحة الرسم عند استخدام Microsoft Visio لتخطيط الأشكال على صفحة الرسم. |
| [AvoidPageBreaks](../../aspose.diagram/pagelayout/avoidpagebreaks/) { get; } | يحدد كيفية وضع الأشكال على الصفحة عند تخطيط الأشكال عندما يحدد المستخدم تخطيط الأشكال (قائمة الأشكال). |
| [BlockSizeX](../../aspose.diagram/pagelayout/blocksizex/) { get; } | تحديد حجم الكتلة الرأسية ، وهي المنطقة التي يجب احتواء كل شكل من الأشكال فيها على صفحة الرسم عند استخدام Microsoft Visio لتخطيط الأشكال على صفحة الرسم. |
| [BlockSizeY](../../aspose.diagram/pagelayout/blocksizey/) { get; } | تحديد مقدار المسافة الأفقية بين الأشكال الموجودة على صفحة الرسم عند استخدام Microsoft Visio لتخطيط الأشكال على صفحة الرسم. |
| [CtrlAsInput](../../aspose.diagram/pagelayout/ctrlasinput/) { get; } | تحديد الشكل الأصلي عند استخدام الأشكال بواسطة مقابض التحكم. يعيّن هذا العنصر سلوك جميع الأشكال في صفحة الرسم. |
| [Del](../../aspose.diagram/pagelayout/del/) { get; set; } | علامة تشير إلى ما إذا كان قد تم حذف العنصر محليًا. تشير القيمة 1 إلى أنه تم حذف العنصر محليًا. |
| [DynamicsOff](../../aspose.diagram/pagelayout/dynamicsoff/) { get; } | تحديد ما إذا كانت الأشكال القابلة للتثبيت تتحرك وإعادة توجيه الموصلات حول الأشكال والموصلات الأخرى في صفحة الرسم. |
| [EnableGrid](../../aspose.diagram/pagelayout/enablegrid/) { get; } | يحدد ما إذا كان Microsoft Visio يرسم الأشكال بناءً على شبكة صفحة داخلية عندما يحدد المستخدم تخطيط الأشكال (قائمة الشكل). |
| [LineAdjustFrom](../../aspose.diagram/pagelayout/lineadjustfrom/) { get; } | تحديد الموصلات الديناميكية التي يجب فصلها عن بعضها إذا تم توجيهها فوق بعضها البعض . |
| [LineAdjustTo](../../aspose.diagram/pagelayout/lineadjustto/) { get; } | يحدد أي الموصلات الديناميكية تصطف فوق بعضها البعض إذا تم توجيهها فوق بعضها البعض . |
| [LineJumpCode](../../aspose.diagram/pagelayout/linejumpcode/) { get; } | يحدد نمط انتقال السطر لكافة الموصلات الموجودة في صفحة الرسم التي لا تحتوي على نمط انتقال للخط المحلي . |
| [LineJumpFactorX](../../aspose.diagram/pagelayout/linejumpfactorx/) { get; } | يحدد حجم قفزات الخط على المقاطع الأفقية للموصلات الديناميكية على الصفحة ، كنسبة مئوية من قيمة عنصر LineToLineX (الذي يحدد التخليص الأفقي بين جميع الموصلات في صفحة الرسم). تتراوح قيمة هذا العنصر من 0 إلى 10. |
| [LineJumpFactorY](../../aspose.diagram/pagelayout/linejumpfactory/) { get; } | يحدد حجم قفزات الخط على المقاطع الرأسية للموصلات الديناميكية على الصفحة ، كنسبة مئوية من قيمة عنصر LineToLineY (الذي يحدد التخليص الرأسي بين كافة الموصلات في صفحة الرسم). يمكن أن يحتوي هذا العنصر على قيمة من 0 إلى 10. |
| [LineJumpStyle](../../aspose.diagram/pagelayout/linejumpstyle/) { get; } | يحدد اتجاه قفزات الخط على المقاطع الأفقية للموصلات الديناميكية على صفحة الرسم التي لم تقم بتطبيق اتجاه قفزة محلي لها. |
| [LineRouteExt](../../aspose.diagram/pagelayout/linerouteext/) { get; } | تحديد المظهر الافتراضي لجميع الموصلات في الصفحة. |
| [LineToLineX](../../aspose.diagram/pagelayout/linetolinex/) { get; } | تحديد الحد الأدنى للتخليص الأفقي بين الموصلات الديناميكية في صفحة الرسم. |
| [LineToLineY](../../aspose.diagram/pagelayout/linetoliney/) { get; } | تحديد الحد الأدنى للتخليص الرأسي بين الموصلات الديناميكية في صفحة الرسم. |
| [LineToNodeX](../../aspose.diagram/pagelayout/linetonodex/) { get; } | تحديد الحد الأدنى للتخليص الرأسي بين الموصلات الديناميكية والأشكال على صفحة الرسم. |
| [LineToNodeY](../../aspose.diagram/pagelayout/linetonodey/) { get; } | تحديد حجم الكتلة الأفقية ، وهي المنطقة التي يجب احتواء كل شكل من الأشكال فيها على صفحة الرسم عند استخدام Microsoft Visio لتخطيط الأشكال على صفحة الرسم. |
| [PageLineJumpDirX](../../aspose.diagram/pagelayout/pagelinejumpdirx/) { get; } | يحدد اتجاه قفزات الخط على الموصلات الديناميكية العمودية على صفحة الرسم التي لم تقم بتطبيق اتجاه قفزة محلي لها. |
| [PageLineJumpDirY](../../aspose.diagram/pagelayout/pagelinejumpdiry/) { get; } | تحديد الحد الأدنى للتخليص الأفقي بين الموصلات الديناميكية والأشكال على صفحة الرسم. |
| [PageShapeSplit](../../aspose.diagram/pagelayout/pageshapesplit/) { get; } | يشير إلى ما إذا كان يمكن تقسيم الأشكال الموجودة على الصفحة تلقائيًا. |
| [PlaceDepth](../../aspose.diagram/pagelayout/placedepth/) { get; } | يحدد ما إذا كانت الأشكال القابلة للتثبيت تتحرك بعيدًا عندما يسحب المستخدم شكلاً قابلاً للتثبيت بالقرب من شكل آخر قابل للتثبيت على صفحة الرسم. |
| [PlaceFlip](../../aspose.diagram/pagelayout/placeflip/) { get; } | يحدد كيفية قلب الأشكال القابلة للتثبيت و / أو تدويرها على الصفحة عند تخطيط الأشكال باستخدام الأمر Lay Out Shapes في Microsoft Visio. القيم السداسية العشرية التالية مسموح بها. |
| [PlaceStyle](../../aspose.diagram/pagelayout/placestyle/) { get; } | يحدد نمط التوجيه والاتجاه لجميع الموصلات الديناميكية على صفحة الرسم التي لا تحتوي على نمط توجيه محلي. |
| [PlowCode](../../aspose.diagram/pagelayout/plowcode/) { get; } | يحدد الموصلات الديناميكية التي تريد إضافة القفزات إليها . |
| [ResizePage](../../aspose.diagram/pagelayout/resizepage/) { get; } | يحدد ما إذا كان سيتم تكبير الصفحة لإحاطة الرسم بعد أن يقوم المستخدم بتحديد تخطيط الأشكال (قائمة الأشكال). |
| [RouteStyle](../../aspose.diagram/pagelayout/routestyle/) { get; } | بالنسبة للرسم الذي يتم تخطيطه تلقائيًا ، يحدد الطريقة التي يتم بها تحليل الرسم قبل إنشاء التخطيط ويحدد نوع التخطيط . |

### أنظر أيضا

* مساحة الاسم [Aspose.Diagram](../../aspose.diagram/)
* المجسم [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
