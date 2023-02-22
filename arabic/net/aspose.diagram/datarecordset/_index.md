---
title: DataRecordSet
second_title: Aspose.Diagram لمرجع .NET API
description: تخزين وتنسيق وتحديث وكشف البيانات التي تم الاستعلام عنها من قاعدة بيانات في Microsoft Visio.
type: docs
weight: 1140
url: /ar/net/aspose.diagram/datarecordset/
---
## DataRecordSet class

تخزين وتنسيق وتحديث وكشف البيانات التي تم الاستعلام عنها من قاعدة بيانات في Microsoft Visio.

```csharp
public class DataRecordSet
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [DataRecordSet](datarecordset/)() | المُنشئ. |

## الخصائص

| اسم | وصف |
| --- | --- |
| [ADOData](../../aspose.diagram/datarecordset/adodata/) { get; set; } | يحتوي على XML الذي يتوافق مع مخطط XML الكلاسيكي لـ ADO لمجموعة سجلات ADO والذي يصف البيانات الموجودة في مجموعة سجلات البيانات. |
| [AutoLinkComparison](../../aspose.diagram/datarecordset/autolinkcomparison/) { get; } | تحدد قاعدة تقارن عمودًا في عنصر DataRecordset الأصل مع عنصر بيانات الشكل من آخر إجراء ربط تلقائي ناجح تم تنفيذه في واجهة المستخدم. |
| [Checksum](../../aspose.diagram/datarecordset/checksum/) { get; set; } | قيمة مجموع اختباري ، يتم إنشاؤها بواسطة Visio ، وتستند إلى خصائص مجموعة سجلات البيانات. اضبط هذه السمة على 0 ؛ يقوم Visio بإعادة حساب هذه القيمة في وقت التشغيل. |
| [Command](../../aspose.diagram/datarecordset/command/) { get; set; } | سلسلة الأمر المستخدمة للاستعلام عن البيانات من مصدر البيانات. |
| [ConnectionID](../../aspose.diagram/datarecordset/connectionid/) { get; set; } | معرف الاتصال لكائن DataConnection المرتبط. غير موجود لمصادر بيانات XML . |
| [DataColumns](../../aspose.diagram/datarecordset/datacolumns/) { get; } | يحتوي على جميع عناصر DataColumn في مجموعة سجلات البيانات. |
| [ID](../../aspose.diagram/datarecordset/id/) { get; set; } | معرّف مجموعة سجلات البيانات ، فريد داخل المستند. |
| [Name](../../aspose.diagram/datarecordset/name/) { get; set; } | الاسم المعروض (أو "المألوف") لمجموعة سجلات البيانات. |
| [NextRowID](../../aspose.diagram/datarecordset/nextrowid/) { get; set; } | معرف صف Visio التالي المتاح . |
| [Options](../../aspose.diagram/datarecordset/options/) { get; set; } | خيارات للتطبيق على مجموعة سجلات البيانات. يمكن أن تكون القيم المحتملة أي مجموعة من واحد أو أكثر من القيم الموضحة في الجدول التالي. |
| [PrimaryKeys](../../aspose.diagram/datarecordset/primarykeys/) { get; } | يحدد عمودًا أو أكثر من أعمدة المفاتيح الأساسية في مجموعة سجلات البيانات. |
| [RefreshConflicts](../../aspose.diagram/datarecordset/refreshconflicts/) { get; } | يشير إلى وجود صف في مجموعة سجلات البيانات مرتبط بشكل متعارض بعد تحديث مجموعة سجلات البيانات . معرف الصف - يشير إلى وجود صف في مجموعة سجلات البيانات مرتبط بشكل متعارض بعد تحديث مجموعة سجلات البيانات. - معرف الشكل للشكل المتضمن في التعارض . معرف الصفحة - معرف الصفحة للشكل المتضمن في التعارض . |
| [RefreshInterval](../../aspose.diagram/datarecordset/refreshinterval/) { get; set; } | كم مرة (بالدقائق) يقوم Visio بتحديث مجموعة سجلات البيانات تلقائيًا. يجب أن تكون هذه القيمة 1 أو أكبر. |
| [RefreshNoReconciliationUI](../../aspose.diagram/datarecordset/refreshnoreconciliationui/) { get; set; } | ما إذا كان يجب تعطيل واجهة مستخدم تسوية البيانات. صحيح (1) لتعطيل واجهة المستخدم (UI). خطأ (0) لتمكين واجهة المستخدم . |
| [RefreshOverwriteAll](../../aspose.diagram/datarecordset/refreshoverwriteall/) { get; set; } | ما إذا كان سيتم الكتابة فوق تغييرات المستخدم لتشكيل عناصر البيانات في الأشكال المرتبطة بالبيانات عند تحديث مجموعة سجلات البيانات. |
| [ReplaceLinks](../../aspose.diagram/datarecordset/replacelinks/) { get; set; } | يحدد كيفية معالجة ارتباطات بيانات الشكل عند نسخ الأشكال أو قصها. 1 لاستبدال الروابط الموجودة في الشكل الهدف. 0 للحفاظ على الروابط الموجودة في الشكل الهدف. في حالة عدم وجود هذه السمة ، يسأل Visio المستخدم عما إذا كان سيستبدل الارتباطات عند النسخ أو القص. |
| [RowMaps](../../aspose.diagram/datarecordset/rowmaps/) { get; } | تعيين صف مجموعة سجلات البيانات إلى شكل . معرف الصف - معرف الصف للصف ، فريد داخل مجموعة سجلات البيانات . معرف الشكل للشكل المرتبط بالبيانات في صف مجموعة سجلات البيانات المحدد بواسطة RowID. معرف الصفحة - معرف الصفحة للشكل المرتبط بالبيانات في صف مجموعة سجلات البيانات المعرّف بواسطة RowID. |
| [RowOrder](../../aspose.diagram/datarecordset/roworder/) { get; set; } | ما إذا كان سيتم استخدام ترتيب الصفوف في مجموعة سجلات البيانات كمفتاح أساسي. صواب (1) إذا تم تحديد معرّفات الصفوف بترتيب الصفوف. خطأ (0) إذا تم تحديد معرفات الصف بواسطة قيم في عمود (أعمدة) المفتاح الأساسي لمجموعة سجلات البيانات. |
| [TimeRefreshed](../../aspose.diagram/datarecordset/timerefreshed/) { get; set; } | تاريخ ووقت آخر تحديث لمجموعة سجلات البيانات. |

## طُرق

| اسم | وصف |
| --- | --- |
| [Refresh](../../aspose.diagram/datarecordset/refresh/#refresh)() | يقوم بتنفيذ سلسلة الاستعلام المقترنة بمجموعة DataRecordset المتصلة (غير المستندة إلى XML) ويقوم بتحديث الأشكال المرتبطة ببيانات جديدة من مصدر البيانات التي يتم إرجاعها بواسطة الاستعلام. |
| [Refresh](../../aspose.diagram/datarecordset/refresh/#refresh_1)(DataConnectionType) | يقوم بتنفيذ سلسلة الاستعلام المقترنة بمجموعة DataRecordset المتصلة (غير المستندة إلى XML) ويقوم بتحديث الأشكال المرتبطة ببيانات جديدة من مصدر البيانات التي يتم إرجاعها بواسطة الاستعلام. |

### أنظر أيضا

* مساحة الاسم [Aspose.Diagram](../../aspose.diagram/)
* المجسم [Aspose.Diagram](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Diagram.dll -->
