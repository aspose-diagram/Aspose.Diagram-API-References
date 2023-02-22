---
title: Diagram
second_title: Aspose.Diagram لمرجع .NET API
description: العنصر الجذر في التسلسل الهرمي لكائنات Visio.
type: docs
weight: 1170
url: /ar/net/aspose.diagram/diagram/
---
## Diagram class

العنصر الجذر في التسلسل الهرمي لكائنات Visio.

```csharp
public class Diagram : IDisposable
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [Diagram](diagram/#constructor)() | Default_Constructor |
| [Diagram](diagram/#constructor_1)(Stream) | مُنشئ الفئة العامة ، يقوم بتحميل الرسم التخطيطي من الدفق. |
| [Diagram](diagram/#constructor_4)(string) | مُنشئ الفئة العامة ، يقوم بتحميل الرسم التخطيطي من الملف. |
| [Diagram](diagram/#constructor_2)(Stream, LoadFileFormat) | مُنشئ الفئة العامة ، يقوم بتحميل الرسم التخطيطي من الدفق باستخدام تنسيق محدد مسبقًا. |
| [Diagram](diagram/#constructor_3)(Stream, LoadOptions) | مُنشئ الفئة العامة ، يقوم بتحميل الرسم التخطيطي من الدفق باستخدام خيارات ملف التحميل المحددة مسبقًا. |
| [Diagram](diagram/#constructor_5)(string, LoadFileFormat) | مُنشئ الفئة العامة ، يقوم بتحميل الرسم التخطيطي من الملف باستخدام تنسيق محدد مسبقًا. |
| [Diagram](diagram/#constructor_6)(string, LoadOptions) | مُنشئ الفئة العامة ، يقوم بتحميل الرسم التخطيطي من الملف باستخدام خيارات ملف التحميل المحددة مسبقًا. |

## الخصائص

| اسم | وصف |
| --- | --- |
| [ActivePage](../../aspose.diagram/diagram/activepage/) { get; } | يحدد الصفحة النشطة |
| [Buildnum](../../aspose.diagram/diagram/buildnum/) { get; set; } | رقم الإصدار لمثيل Visio المستخدم لإنشاء المستند. |
| [Colors](../../aspose.diagram/diagram/colors/) { get; } | يحتوي على جدول ألوان المستند. يحتوي كل مستند على جدول لون واحد ، والذي يسرد 24 لونًا قياسيًا متاحًا للتطبيق على الكائنات مثل الأشكال والنص والطبقات في المستند. |
| [DataConnections](../../aspose.diagram/diagram/dataconnections/) { get; } | يحتوي على عناصر DataConnection للمستند. |
| [DataRecordSets](../../aspose.diagram/diagram/datarecordsets/) { get; } | مجموعة كائنات DataRecordset المقترنة بكائن مستند. |
| [DocLangID](../../aspose.diagram/diagram/doclangid/) { get; set; } | المعرف الفريد للغة واجهة المستخدم التي حددها المستخدم في تفضيلات اللغة لـ Microsoft Office 2010. |
| [DocumentProps](../../aspose.diagram/diagram/documentprops/) { get; } | يحتوي على عناصر خصائص المستند مثل عنوان المستند والمؤلف وما إلى ذلك. |
| [DocumentSettings](../../aspose.diagram/diagram/documentsettings/) { get; } | يحتوي على العناصر التي تحدد إعدادات المستند. |
| [DocumentSheet](../../aspose.diagram/diagram/documentsheet/) { get; } | تحديد بنية ورقة الشكل للمستند. |
| [EmailRoutingData](../../aspose.diagram/diagram/emailroutingdata/) { get; set; } | يحتوي على MIME (ملحقات بريد الإنترنت متعدد الأغراض) المشفرة قسيمة توجيه البريد الإلكتروني MAPI للمستند. |
| [EventItems](../../aspose.diagram/diagram/eventitems/) { get; } | يحتوي على عنصر EventItem لكل حدث يجب أن يستجيب له الكائن. |
| [FontDirs](../../aspose.diagram/diagram/fontdirs/) { set; } | يشير إلى مسار مجلد الخطوط |
| [Fonts](../../aspose.diagram/diagram/fonts/) { get; } | يحتوي على مجموعة من عناصر الخط |
| [HeaderFooter](../../aspose.diagram/diagram/headerfooter/) { get; } | يحتوي على عناصر لرأس المستند وتذييله . |
| [InterruptMonitor](../../aspose.diagram/diagram/interruptmonitor/) { get; set; } | الحصول على شاشة المقاطعة وتعيينها. |
| [Key](../../aspose.diagram/diagram/key/) { get; set; } | يشير إلى ما إذا كان قد تم تعديل المستند خارج Visio. إذا كان موجودًا ، فسيقوم Visio باختبار محتويات الملف بالكامل. حذف للملفات التي تقوم بإنشائها خارج Visio . |
| [Masters](../../aspose.diagram/diagram/masters/) { get; } | كائنات المجموعة الرئيسية. |
| [Metric](../../aspose.diagram/diagram/metric/) { get; set; } | ما إذا كان سيتم استخدام الوحدات المترية في الرسم. اضبط هذه السمة على True (1) لاستخدام الوحدات المترية ؛ اضبطه على خطأ (0) لاستخدام الوحدات الإنجليزية. |
| [Pages](../../aspose.diagram/diagram/pages/) { get; } | كائنات صفحة المجموعة . |
| [RibbonX](../../aspose.diagram/diagram/ribbonx/) { get; set; } | سلسلة الشريط XML التي تم تمريرها إلى المستند لتخصيص واجهة مستخدم الشريط. |
| [SolutionXMLs](../../aspose.diagram/diagram/solutionxmls/) { get; } | قيمة XML . |
| [Start](../../aspose.diagram/diagram/start/) { get; set; } | يشير إلى ما إذا كان قد تم تعديل المستند خارج Visio. في حالة وجوده ، سيقوم Visio باختبار محتويات الملف بالكامل. حذف للملفات التي تقوم بإنشائها خارج Visio . |
| [StyleSheets](../../aspose.diagram/diagram/stylesheets/) { get; } | مجموعة كائنات StyleSheet . |
| [UserCustomUI](../../aspose.diagram/diagram/usercustomui/) { get; set; } | سلسلة الشريط XML التي تم تمريرها إلى المستند لتخصيص شريط أدوات الوصول السريع أو الشريط. |
| [Validation](../../aspose.diagram/diagram/validation/) { get; } | يخزن معلومات حول التحقق من صحة الرسم التخطيطي للمستند. |
| [VbaProject](../../aspose.diagram/diagram/vbaproject/) { get; } | يحصل على VbaProject[`VbaProject`](./vbaproject/) . |
| [VbProjectData](../../aspose.diagram/diagram/vbprojectdata/) { get; set; } | يحتوي على Microsoft Visual Basic لبيانات مشروع التطبيقات بتنسيق MIME (ملحقات بريد الإنترنت متعدد الأغراض) المشفر. |
| [Version](../../aspose.diagram/diagram/version/) { get; set; } | رقم إصدار مثيل Visio. برنامج Microsoft Visio 2010 = 14. |
| [Windows](../../aspose.diagram/diagram/windows/) { get; } | يحتوي على عناصر Window لمستند . |

## طُرق

| اسم | وصف |
| --- | --- |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster)(Diagram, string) | يضيف رئيسي إلى الرسم التخطيطي من الرسم التخطيطي المصدر بواسطة اسم أو اسم السيد U. |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_1)(Stream, int) | يضيف الرئيسي إلى الرسم التخطيطي من دفق القالب بواسطة معرف السيد . |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_2)(Stream, string) | يضيف رئيسي إلى الرسم التخطيطي من قالب تيار حسب اسم السيد أو الاسم U. |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_3)(string, int) | يضيف الرئيسي إلى الرسم التخطيطي من ملف القالب بواسطة معرف السيد . |
| [AddMaster](../../aspose.diagram/diagram/addmaster/#addmaster_4)(string, string) | إضافة رئيسي إلى رسم تخطيطي من ملف قالب بواسطة اسم أو اسم السيد U. |
| [AddShape](../../aspose.diagram/diagram/addshape/#addshape)(Shape, string, int) | يضيف الشكل الذي تم إنشاؤه بواسطة الرئيسي إلى صفحة معينة. |
| [AddShape](../../aspose.diagram/diagram/addshape/#addshape_2)(double, double, string, int) | يضيف الشكل الذي تم إنشاؤه بواسطة السيد على الصفحة مع تعريف PinX و PinY. |
| [AddShape](../../aspose.diagram/diagram/addshape/#addshape_1)(double, double, double, double, string, int) | يضيف الشكل الذي تم إنشاؤه بواسطة السيد على الصفحة مع تعريف PinX و PinY والعرض والارتفاع. |
| [Combine](../../aspose.diagram/diagram/combine/)(Diagram) | دمج كائن مخطط آخر . |
| [CopyTheme](../../aspose.diagram/diagram/copytheme/)(Diagram) | نسخ النسق من مخطط المصدر. |
| [Dispose](../../aspose.diagram/diagram/dispose/)() | يؤدي مهام محددة بواسطة التطبيق مرتبطة بتحرير الموارد غير المُدارة أو تحريرها أو إعادة تعيينها. |
| [GetDefaultFontDir](../../aspose.diagram/diagram/getdefaultfontdir/)() | احصل على مسار مجلد الخطوط الافتراضية |
| [GetUnusedStyles](../../aspose.diagram/diagram/getunusedstyles/)() | احصل على الأنماط غير المستخدمة |
| [HasHiddenInfo](../../aspose.diagram/diagram/hashiddeninfo/)() | يشير إلى ما إذا كان هذا الرسم البياني يحتوي على معلومات مخفية. |
| [Layout](../../aspose.diagram/diagram/layout/)(LayoutOptions) | يرسم الأشكال و / أو يعيد توجيه الموصلات لجميع صفحات الرسم التخطيطي. |
| [Print](../../aspose.diagram/diagram/print/#print)() | طباعة المستند بالكامل على الطابعة الافتراضية. |
| [Print](../../aspose.diagram/diagram/print/#print_2)(PrinterSettings) | يطبع المستند وفقًا لإعدادات الطابعة المحددة ، باستخدام وحدة تحكم الطباعة القياسية (بدون واجهة مستخدم). |
| [Print](../../aspose.diagram/diagram/print/#print_1)(PrintSaveOptions) | طباعة المستند بالكامل على الطابعة الافتراضية. |
| [Print](../../aspose.diagram/diagram/print/#print_6)(string) | اطبع المستند بالكامل على الطابعة المحددة باستخدام وحدة تحكم الطباعة القياسية (بدون واجهة مستخدم). |
| [Print](../../aspose.diagram/diagram/print/#print_3)(PrinterSettings, PrintSaveOptions) | يطبع المستند وفقًا لإعدادات الطابعة المحددة ، باستخدام وحدة تحكم الطباعة القياسية (بدون واجهة مستخدم). |
| [Print](../../aspose.diagram/diagram/print/#print_4)(PrinterSettings, string) | طباعة المستند وفقًا لإعدادات الطابعة المحددة ، باستخدام وحدة تحكم الطباعة القياسية (بدون واجهة مستخدم) واسم المستند. |
| [Print](../../aspose.diagram/diagram/print/#print_7)(string, PrintSaveOptions) | اطبع المستند بالكامل على الطابعة المحددة باستخدام وحدة تحكم الطباعة القياسية (بدون واجهة مستخدم). |
| [Print](../../aspose.diagram/diagram/print/#print_8)(string, string) | طباعة المستند باستخدام وحدة تحكم الطباعة القياسية (بدون واجهة مستخدم) واسم المستند. |
| [Print](../../aspose.diagram/diagram/print/#print_5)(PrinterSettings, string, PrintSaveOptions) | طباعة المستند وفقًا لإعدادات الطابعة المحددة ، باستخدام وحدة تحكم الطباعة القياسية (بدون واجهة مستخدم) واسم المستند. |
| [Print](../../aspose.diagram/diagram/print/#print_9)(string, string, PrintSaveOptions) | طباعة المستند باستخدام وحدة تحكم الطباعة القياسية (بدون واجهة مستخدم) واسم المستند. |
| [Refresh](../../aspose.diagram/diagram/refresh/)() | يستدعي طريقة التحديث لجميع DataRecordSet في الرسم التخطيطي. |
| [RemoveHiddenInformation](../../aspose.diagram/diagram/removehiddeninformation/)(int) | إزالة المعلومات غير المستخدمة |
| [RemoveMacro](../../aspose.diagram/diagram/removemacro/)() | يزيل VBA / الماكرو من هذا الرسم التخطيطي. |
| [Save](../../aspose.diagram/diagram/save/#save)(Stream, SaveFileFormat) | يحفظ بيانات الرسم التخطيطي في الدفق. |
| [Save](../../aspose.diagram/diagram/save/#save_1)(Stream, SaveOptions) | يحفظ الرسم التخطيطي في دفق باستخدام خيارات الحفظ المحددة. |
| [Save](../../aspose.diagram/diagram/save/#save_2)(string, SaveFileFormat) | يحفظ بيانات الرسم التخطيطي في الملف. |
| [Save](../../aspose.diagram/diagram/save/#save_3)(string, SaveOptions) | يحفظ المستند في ملف باستخدام خيارات الحفظ المحددة. |
| static [Export](../../aspose.diagram/diagram/export/#export)(Stream, Stream) | تصدير الرسم التخطيطي من دفق vsd إلى تنسيق دفق vdw. لم يتم التنفيذ بعد. |
| static [Export](../../aspose.diagram/diagram/export/#export_1)(Stream, string) | تصدير الرسم التخطيطي من دفق vsd إلى تنسيق ملف * .vdw. لم يتم التنفيذ بعد. |
| static [Export](../../aspose.diagram/diagram/export/#export_2)(string, Stream) | تصدير الرسم التخطيطي من ملف vsd إلى تنسيق دفق vdw. لم يتم التنفيذ بعد. |
| static [Export](../../aspose.diagram/diagram/export/#export_3)(string, string) | تصدير الرسم التخطيطي من تنسيق vsd إلى تنسيق vdw. لم يتم التنفيذ بعد. |

### أنظر أيضا

* مساحة الاسم [Aspose.Diagram](../../aspose.diagram/)
* المجسم [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
