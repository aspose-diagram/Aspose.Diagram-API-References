---
title: Page
second_title: Aspose.Diagram لمرجع .NET API
description: يحتوي على عناصر تحدد صفحة في المستند.
type: docs
weight: 2490
url: /ar/net/aspose.diagram/page/
---
## Page class

يحتوي على عناصر تحدد صفحة في المستند.

```csharp
public class Page : IDisposable
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [Page](page/#constructor)() | المُنشئ. |
| [Page](page/#constructor_1)(int) | المُنشئ. |

## الخصائص

| اسم | وصف |
| --- | --- |
| [AssociatedPage](../../aspose.diagram/page/associatedpage/) { get; set; } | معرّف صفحة الرسم الأصلية التي تم ترميزها في تراكبات ترميز منفصلة بواسطة مراجعي الرسم. |
| [Background](../../aspose.diagram/page/background/) { get; set; } | علامة تشير إلى ما إذا كانت الصفحة هي صفحة خلفية. |
| [BackPage](../../aspose.diagram/page/backpage/) { get; set; } | صفحة خلفية الصفحة . |
| [Connects](../../aspose.diagram/page/connects/) { get; } | يحتوي على عنصر اتصال لكل اتصال بين شكلين في الرسم . |
| [ID](../../aspose.diagram/page/id/) { get; set; } | المعرف الفريد للعنصر داخل العنصر الأصل . |
| [Name](../../aspose.diagram/page/name/) { get; set; } | اسم العنصر . |
| [NameU](../../aspose.diagram/page/nameu/) { get; set; } | الاسم العالمي للعنصر . |
| [Pages](../../aspose.diagram/page/pages/) { get; set; } | مجموعة الصفحات. |
| [PageSheet](../../aspose.diagram/page/pagesheet/) { get; } | يحتوي على عناصر تحدد ورقة الصفحة لعنصر صفحة أو عنصر رئيسي. |
| [PresetTheme](../../aspose.diagram/page/presettheme/) { set; } | تطبيق سمة محددة مسبقًا على هذه الصفحة |
| [PresetThemeQuickStyle](../../aspose.diagram/page/presetthemequickstyle/) { set; } | تطبيق Quickstyle لمتغير سمة مُعد مسبقًا على هذه الصفحة |
| [PresetThemeVariant](../../aspose.diagram/page/presetthemevariant/) { set; } | تطبيق متغير سمة مُعد مسبقًا على هذه الصفحة |
| [ReviewerID](../../aspose.diagram/page/reviewerid/) { get; set; } | معرف المراجع المرتبط بتراكب العلامات . |
| [Shapes](../../aspose.diagram/page/shapes/) { get; } | جمع الأشكال . |
| [ViewCenterX](../../aspose.diagram/page/viewcenterx/) { get; set; } | ViewCenterX و ViewCenterY يحددان نقطة مركزية على الصفحة يفترضها العرض الجديد (نافذة) عند فتحه مبدئيًا. |
| [ViewCenterY](../../aspose.diagram/page/viewcentery/) { get; set; } | ViewCenterX و ViewCenterY يحددان نقطة مركزية على الصفحة يفترضها العرض الجديد (نافذة) عند فتحه مبدئيًا. |
| [ViewScale](../../aspose.diagram/page/viewscale/) { get; set; } | عامل التكبير الافتراضي المستخدم عند فتح عرض (نافذة) جديد للصفحة. على سبيل المثال ، 1 = 100٪ ؛ 1.5 = 150٪ وهكذا . |

## طُرق

| اسم | وصف |
| --- | --- |
| [AddActiveXControl](../../aspose.diagram/page/addactivexcontrol/)(ControlType, double, double, double, double) | ينشئ عنصر تحكم Activex . |
| [AddComment](../../aspose.diagram/page/addcomment/#addcomment_2)(long, string) | إضافة تعليق إلى شكل بمعرف الشكل. |
| [AddComment](../../aspose.diagram/page/addcomment/#addcomment)(Shape, string) | إضافة تعليق إلى شكل . |
| [AddComment](../../aspose.diagram/page/addcomment/#addcomment_1)(double, double, string) | إضافة تعليق مع PinX و PinY محدد . |
| [AddShape](../../aspose.diagram/page/addshape/#addshape)(Shape, string) | يضيف الشكل الذي تم إنشاؤه بواسطة الرئيسي إلى صفحة معينة. |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_4)(double, double, string) | يضيف الشكل الذي تم إنشاؤه بواسطة السيد على الصفحة مع تعريف PinX و PinY. |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_1)(double, double, double, double, Stream) |  |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_3)(double, double, double, double, string) | يضيف الشكل الذي تم إنشاؤه بواسطة السيد على الصفحة مع تعريف PinX و PinY والعرض والارتفاع. |
| [AddShape](../../aspose.diagram/page/addshape/#addshape_2)(double, double, double, double, Stream, Stream) |  |
| [AddText](../../aspose.diagram/page/addtext/#addtext)(double, double, double, double, string) | إضافة نص مع PinX و PinY محدد . |
| [AddText](../../aspose.diagram/page/addtext/#addtext_1)(double, double, double, double, string, string, string, double) | إضافة نص مع PinX و PinY محدد . |
| [ApplyStyle](../../aspose.diagram/page/applystyle/)(int, int, int) | يطبق النمط على الصفحة الكاملة . |
| [AutoSpaceShapes](../../aspose.diagram/page/autospaceshapes/)(ShapeCollection, AutoSpaceOptions) | أشكال المساحة التلقائية |
| [BringForward](../../aspose.diagram/page/bringforward/)(long) | يجلب شكلًا محددًا بواسطة المعرف ، ويعيد توجيه موضع واحد في ترتيب z . |
| [BringToFront](../../aspose.diagram/page/bringtofront/)(long) | يقوم بإحضار شكل معرف بواسطة المعرف إلى مقدمة ترتيب z . |
| [CenterDrawing](../../aspose.diagram/page/centerdrawing/)() | توسيط أشكال الصفحة فيما يتعلق بنطاق الصفحة . لا يؤدي توسيط الأشكال إلى تغيير موضعها بالنسبة لبعضها البعض . |
| [ConnectShapesViaConnector](../../aspose.diagram/page/connectshapesviaconnector/#connectshapesviaconnector_1)(long, ConnectionPointPlace, long, ConnectionPointPlace, long) | توصيل الأشكال عبر الموصل . |
| [ConnectShapesViaConnector](../../aspose.diagram/page/connectshapesviaconnector/#connectshapesviaconnector_2)(long, string, long, string, long) | توصيل الأشكال عبر الموصل . |
| [ConnectShapesViaConnector](../../aspose.diagram/page/connectshapesviaconnector/#connectshapesviaconnector)(Shape, ConnectionPointPlace, Shape, ConnectionPointPlace, Shape) | توصيل الأشكال عبر الموصل . |
| [ConnectShapesViaConnectorIndex](../../aspose.diagram/page/connectshapesviaconnectorindex/#connectshapesviaconnectorindex_1)(long, int, long, int, long) | قم بتوصيل الأشكال عبر فهرس الموصل . |
| [ConnectShapesViaConnectorIndex](../../aspose.diagram/page/connectshapesviaconnectorindex/#connectshapesviaconnectorindex)(Shape, int, Shape, int, Shape) | قم بتوصيل الأشكال عبر فهرس الموصل . |
| [Copy](../../aspose.diagram/page/copy/)(Page) |  |
| [Dispose](../../aspose.diagram/page/dispose/)() | يؤدي مهام محددة بواسطة التطبيق مرتبطة بتحرير الموارد غير المُدارة أو تحريرها أو إعادة تعيينها. |
| [DrawBezier](../../aspose.diagram/page/drawbezier/)(double, double, double, double, PointF[]) | عملية رسم البيزير . يجب أن يكون طول النقاط أكبر أو يساوي 3. |
| [DrawEllipse](../../aspose.diagram/page/drawellipse/)(double, double, double, double) | عملية رسم القطع الناقص . |
| [DrawLine](../../aspose.diagram/page/drawline/#drawline)(double, double, double, double) | عملية رسم خط واحد. |
| [DrawLine](../../aspose.diagram/page/drawline/#drawline_1)(double, double, double, double, double[]) | عملية رسم الخط. |
| [DrawLine](../../aspose.diagram/page/drawline/#drawline_2)(double, double, double, double, PointF[]) | عملية رسم الخط. |
| [DrawPolyline](../../aspose.diagram/page/drawpolyline/#drawpolyline)(double, double, double, double, double[]) | عملية رسم Polyline . |
| [DrawPolyline](../../aspose.diagram/page/drawpolyline/#drawpolyline_1)(double, double, double, double, PointF[]) | عملية رسم الخطوط المتعددة . |
| [DrawRectangle](../../aspose.diagram/page/drawrectangle/)(double, double, double, double) | عملية رسم المستطيل . |
| [DrawSpline](../../aspose.diagram/page/drawspline/)(double, double, double, double, PointF[]) | عملية رسم الشريحة . |
| [GlueShapes](../../aspose.diagram/page/glueshapes/#glueshapes_1)(long, ConnectionPointPlace, long) | أشكال الغراء |
| [GlueShapes](../../aspose.diagram/page/glueshapes/#glueshapes)(Shape, ConnectionPointPlace, Shape) | أشكال الغراء. |
| [GlueShapesInContainer](../../aspose.diagram/page/glueshapesincontainer/#glueshapesincontainer)(long, int, int, long) | أشكال الغراء في الحاوية |
| [GlueShapesInContainer](../../aspose.diagram/page/glueshapesincontainer/#glueshapesincontainer_1)(long, string, string, long) | ألصق الأشكال في الحاوية باستخدام اسم الاتصال |
| [GlueShapesInContainerByID](../../aspose.diagram/page/glueshapesincontainerbyid/)(long, int, int, long) | لصق الأشكال حسب معرف الاتصال في الحاوية |
| [GlueShapeToConnectorBeginX](../../aspose.diagram/page/glueshapetoconnectorbeginx/)(long, string, long) | شكل الغراء لبدء الموصل X |
| [GlueShapeToConnectorEndX](../../aspose.diagram/page/glueshapetoconnectorendx/)(long, string, long) | شكل الغراء بنهاية الموصل X |
| [Layout](../../aspose.diagram/page/layout/)(LayoutOptions) | يرسم الأشكال و / أو يعيد توجيه موصلات الصفحة. |
| [MoveTo](../../aspose.diagram/page/moveto/)(int) | لنقل الصفحة إلى مكان آخر في الصفحات. |
| [SendBackward](../../aspose.diagram/page/sendbackward/)(long) | لنقل شكل محدد بواسطة المعرف ، للخلف موضعًا واحدًا بالترتيب z . |
| [SendToBack](../../aspose.diagram/page/sendtoback/)(long) | لنقل شكل معرف بواسطة المعرف إلى الجزء الخلفي من ترتيب z. |

### أنظر أيضا

* مساحة الاسم [Aspose.Diagram](../../aspose.diagram/)
* المجسم [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
