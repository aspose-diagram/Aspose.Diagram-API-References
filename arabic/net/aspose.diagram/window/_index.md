---
title: Window
second_title: Aspose.Diagram لمرجع .NET API
description: يمثل نافذة مفتوحة في مثيل Microsoft Visio. يحتوي هذا العنصر على معلومات ضرورية لإعادة إنشاء نافذة واجهة مستخدم بالضبط في مساحة عمل التطبيق عندما يتم فتح ملف DatadiagramML مبدئيًا بواسطة Visio.
type: docs
weight: 4390
url: /ar/net/aspose.diagram/window/
---
## Window class

يمثل نافذة مفتوحة في مثيل Microsoft Visio. يحتوي هذا العنصر على معلومات ضرورية لإعادة إنشاء نافذة واجهة مستخدم بالضبط في مساحة عمل التطبيق عندما يتم فتح ملف DatadiagramML مبدئيًا بواسطة Visio.

```csharp
public class Window
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [Window](window/)() | المُنشئ. |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Container](../../aspose.diagram/window/container/) { get; set; } | معرّف الحاوية: الصفحة أو الورقة الرئيسية. ذات الصلة والضرورية فقط إذا تم تحديد نوع الحاوية. |
| [ContainerType](../../aspose.diagram/window/containertype/) { get; set; } | قد تكون إحدى القيم التالية: مستند أو صفحة أو رئيسي. مناسب فقط عندما يتم تحديد WindowType كرسم أو ورقة. |
| [Document](../../aspose.diagram/window/document/) { get; set; } | مسار ملف المستند المعروض في هذه النافذة. هذه السمة مناسبة للنوافذ التي تم تحديد WindowType لها على أنها Stencil. |
| [DynamicGridEnabled](../../aspose.diagram/window/dynamicgridenabled/) { get; set; } | يحدد ما إذا كانت ميزة الشبكة الديناميكية ممكنة لمستند أو نافذة. |
| [GlueSettings](../../aspose.diagram/window/gluesettings/) { get; set; } | يحدد الكائنات التي تشكل الالتصاق عند تمكين اللصق في المستند. |
| [ID](../../aspose.diagram/window/id/) { get; set; } | المعرف الفريد للعنصر داخل العنصر الأصل . |
| [Master](../../aspose.diagram/window/master/) { get; set; } | معرّف رئيسي إذا كانت هذه النافذة تعرض رئيسيًا . |
| [Page](../../aspose.diagram/window/page/) { get; set; } | معرف الصفحة إذا كانت هذه النافذة تعرض صفحة. ذو صلة فقط عندما يتم تحديد WindowType كصورة ونوع الحاوية محدد بصفحة. |
| [ParentWindow](../../aspose.diagram/window/parentwindow/) { get; set; } | معرّف النافذة التي تحتوي على نافذة الاستنسل هذه. مناسب فقط عندما يتم تحديد WindowType على أنه Stencil . |
| [ReadOnly](../../aspose.diagram/window/readonly/) { get; set; } | علامة للقراءة فقط إذا لم يكن هذا الاستنسل استنسلًا للمستند. |
| [Sheet](../../aspose.diagram/window/sheet/) { get; set; } | معرف الورقة في الحاوية. ذات صلة فقط عندما يتم تحديد الحاوية على أنها ورقة . |
| [ShowConnectionPoints](../../aspose.diagram/window/showconnectionpoints/) { get; set; } | تحديد ما إذا كانت نقاط الاتصال ستظهر في نافذة أم لا. |
| [ShowGrid](../../aspose.diagram/window/showgrid/) { get; set; } | يحدد ما إذا كانت الشبكة ستظهر في نافذة الرسم. |
| [ShowGuides](../../aspose.diagram/window/showguides/) { get; set; } | تحديد ما إذا كانت الأدلة ستظهر في نافذة الرسم. |
| [ShowPageBreaks](../../aspose.diagram/window/showpagebreaks/) { get; set; } | يحدد ما إذا كانت فواصل الصفحات ستظهر في نافذة أم لا. |
| [ShowRulers](../../aspose.diagram/window/showrulers/) { get; set; } | تحديد ما إذا كانت المساطر ستظهر في نافذة الرسم. |
| [SnapAngles](../../aspose.diagram/window/snapangles/) { get; } | يحتوي على مجموعة من عناصر SnapAngle . |
| [SnapExtensions](../../aspose.diagram/window/snapextensions/) { get; set; } | تحديد ما إذا كان قد تم تمكين أو تعطيل إعداد ملحق snap معين للإطار النشط. يمكن أن تكون القيمة مجموع القيم في الجدول التالي. |
| [SnapSettings](../../aspose.diagram/window/snapsettings/) { get; set; } | تحديد الكائنات التي تنجذب الأشكال إليها عندما يكون Snap نشطًا في النافذة. قد تكون القيمة مجموع القيم في الجدول التالي. |
| [StencilGroup](../../aspose.diagram/window/stencilgroup/) { get; set; } | تحديد مجموعة نوافذ الاستنسل المدمجة التي تكون النافذة عضوًا فيها. هذه السمة مناسبة فقط لعناصر النافذة التي تكون سمة WindowType الخاصة بها هي Stencil ، وفقط إذا كانت نافذة الاستنسل جزءًا من مجموعة مدمجة من نوافذ الاستنسل. جميع نوافذ الاستنسل التي تعد جزءًا من نفس المجموعة المدمجة لها نفس قيمة عنصر StencilGroup. |
| [StencilGroupPos](../../aspose.diagram/window/stencilgrouppos/) { get; set; } | يحتوي على عدد صحيح يحدد الموضع النسبي للاستنسل داخل مجموعة في نافذة. |
| [TabSplitterPos](../../aspose.diagram/window/tabsplitterpos/) { get; set; } | يحدد عرض عنصر تحكم علامة تبويب الصفحة لإطار الرسم (ككسر من إجمالي عرض نافذة الرسم) . |
| [ViewCenterX](../../aspose.diagram/window/viewcenterx/) { get; set; } | مزدوج اختياري . |
| [ViewCenterY](../../aspose.diagram/window/viewcentery/) { get; set; } | مزدوج اختياري . |
| [ViewScale](../../aspose.diagram/window/viewscale/) { get; set; } | مزدوج اختياري . |
| [WindowHeight](../../aspose.diagram/window/windowheight/) { get; set; } | ارتفاع مستطيل النافذة . |
| [WindowLeft](../../aspose.diagram/window/windowleft/) { get; set; } | الإحداثي الأيسر لمستطيل النافذة. |
| [WindowState](../../aspose.diagram/window/windowstate/) { get; set; } | يمكن أن تكون هذه السمة مجموع القيم التالية. |
| [WindowTop](../../aspose.diagram/window/windowtop/) { get; set; } | الإحداثيات العلوية لمستطيل النافذة . |
| [WindowType](../../aspose.diagram/window/windowtype/) { get; set; } | قيمة تم تعدادها والتي قد تكون واحدة مما يلي: الرسم أو الورقة أو الاستنسل أو الأيقونة. يجب أن يظهر عنصر النافذة في WindowType = 'Stencil' بعد نافذة الرسم الأصلية (WindowType = 'Drawing') وقبل أي نافذة رسم أخرى العناصر . |
| [WindowWidth](../../aspose.diagram/window/windowwidth/) { get; set; } | عرض مستطيل النافذة . |

### أنظر أيضا

* مساحة الاسم [Aspose.Diagram](../../aspose.diagram/)
* المجسم [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
