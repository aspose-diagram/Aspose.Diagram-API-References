---
title: مخطط
second_title: Aspose.Diagram لـ Java API Reference
description: العنصر الجذر لهرمية كائنات Visio.
type: docs
weight: 117
url: /ar/java/com.aspose.diagram/diagram/
---

**Inheritance:**
java.lang.Object
```
public class Diagram
```

العنصر الجذر لهرمية كائنات Visio.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Diagram()](#Diagram--) |  |
| [Diagram(String filename)](#Diagram-java.lang.String-) | منشئ الفئة العامة، يحمل المخطط من الملف. |
| [Diagram(InputStream stream)](#Diagram-java.io.InputStream-) | منشئ الفئة العامة، يحمل المخطط من التدفق. |
| [Diagram(InputStream stream, int format)](#Diagram-java.io.InputStream-int-) | منشئ الفئة العامة، يحمل المخطط من التدفق باستخدام تنسيق مسبق التعريف. |
| [Diagram(InputStream stream, LoadOptions options)](#Diagram-java.io.InputStream-com.aspose.diagram.LoadOptions-) | منشئ الفئة العامة، يحمل المخطط من التدفق باستخدام خيارات تحميل الملف المسبقة. |
| [Diagram(String filename, int format)](#Diagram-java.lang.String-int-) | منشئ الفئة العامة، يحمل المخطط من الملف باستخدام تنسيق مسبق التعريف. |
| [Diagram(String filename, LoadOptions options)](#Diagram-java.lang.String-com.aspose.diagram.LoadOptions-) | منشئ الفئة العامة، يحمل المخطط من الملف باستخدام خيارات تحميل الملف المسبقة. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [addMaster(Diagram srcDiagram, String masterName)](#addMaster-com.aspose.diagram.Diagram-java.lang.String-) | يضيف master إلى المخطط من مخطط المصدر باستخدام اسم master أو NameU. |
| [addMaster(InputStream templateStream, int masterID)](#addMaster-java.io.InputStream-int-) | يضيف master إلى المخطط من تدفق القالب باستخدام معرف master. |
| [addMaster(InputStream templateStream, String masterName)](#addMaster-java.io.InputStream-java.lang.String-) | يضيف master إلى المخطط من تدفق القالب باستخدام اسم master أو NameU. |
| [addMaster(String templateFilePath, int masterID)](#addMaster-java.lang.String-int-) | يضيف master إلى المخطط من ملف القالب باستخدام معرف master. |
| [addMaster(String templateFilePath, String masterName)](#addMaster-java.lang.String-java.lang.String-) | يضيف master إلى المخطط من ملف القالب باستخدام اسم master أو NameU. |
| [addShape(Shape newShape, String masterName, int pageNumber)](#addShape-com.aspose.diagram.Shape-java.lang.String-int-) | يضيف شكلًا تم إنشاؤه بواسطة القالب إلى صفحة محددة. |
| [addShape(double pinX, double pinY, double width, double height, String masterName, int pageNumber)](#addShape-double-double-double-double-java.lang.String-int-) | يضيف شكلًا تم إنشاؤه بواسطة القالب على الصفحة مع PinX و PinY والعرض والارتفاع المحددين. |
| [addShape(double pinX, double pinY, String masterName, int pageNumber)](#addShape-double-double-java.lang.String-int-) | يضيف شكلًا تم إنشاؤه بواسطة القالب على الصفحة مع PinX و PinY المحددين. |
| [combine(Diagram secondDiagram)](#combine-com.aspose.diagram.Diagram-) | يجمع كائن Diagram آخر. |
| [copyTheme(Diagram source)](#copyTheme-com.aspose.diagram.Diagram-) | ينسخ Theme من مخطط مصدر. |
| [dispose()](#dispose--) | ينفّذ مهامًا محددة من قبل التطبيق مرتبطة بتحرير أو إطلاق أو إعادة ضبط الموارد غير المُدارة. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [export(InputStream inputVsd, InputStream outputVdw)](#export-java.io.InputStream-java.io.InputStream-) | يصدّر المخطط من تدفق vsd إلى تنسيق تدفق vdw. |
| [export(InputStream inputVsd, String outputVdw)](#export-java.io.InputStream-java.lang.String-) | يصدّر المخطط من تدفق vsd إلى تنسيق ملف *.vdw. |
| [export(String inputVsd, InputStream outputVdw)](#export-java.lang.String-java.io.InputStream-) | يصدّر المخطط من ملف vsd إلى تنسيق تدفق vdw. |
| [export(String inputVsd, String outputVdw)](#export-java.lang.String-java.lang.String-) | يصدّر المخطط من vsd إلى تنسيق vdw. |
| [getActivePage()](#getActivePage--) | يحدد الصفحة النشطة |
| [getBuildnum()](#getBuildnum--) | رقم البناء لنسخة Visio المستخدمة لإنشاء المستند. |
| [getClass()](#getClass--) |  |
| [getColors()](#getColors--) | يحتوي على جدول ألوان المستند. |
| [getDataConnections()](#getDataConnections--) | يحتوي على عناصر DataConnection للمستند. |
| [getDataRecordSets()](#getDataRecordSets--) | مجموعة كائنات DataRecordset المرتبطة بكائن Document. |
| [getDefaultFontDir()](#getDefaultFontDir--) | احصل على مسار مجلد الخطوط الافتراضية |
| [getDocLangID()](#getDocLangID--) | معرّف اللغة الفريد لواجهة المستخدم الذي حدده المستخدم في تفضيلات لغة Microsoft Office 2010. |
| [getDocumentProps()](#getDocumentProps--) | يحتوي على عناصر خصائص المستند مثل عنوان المستند، المؤلف، وما إلى ذلك. |
| [getDocumentSettings()](#getDocumentSettings--) | يحتوي على عناصر تحدد إعدادات المستند. |
| [getDocumentSheet()](#getDocumentSheet--) | يحدد بنية ShapeSheet للمستند. |
| [getEmailRoutingData()](#getEmailRoutingData--) | يحتوي على قسيمة توجيه بريد إلكتروني MAPI مشفرة بتنسيق MIME (Multipurpose Internet Mail Extensions) للمستند. |
| [getEventItems()](#getEventItems--) | يحتوي على عنصر EventItem لكل حدث يجب أن يستجيب له الكائن. |
| [getFonts()](#getFonts--) | يحتوي على مجموعة من عناصر Font |
| [getHeaderFooter()](#getHeaderFooter--) | يحتوي على عناصر لترويسة وتذييل المستند. |
| [getInterruptMonitor()](#getInterruptMonitor--) | مراقب المقاطعة. |
| [getKey()](#getKey--) | يشير إلى ما إذا تم تعديل المستند خارج Visio. |
| [getMasters()](#getMasters--) | مجموعة كائنات Master. |
| [getMetric()](#getMetric--) | ما إذا كان يجب استخدام الوحدات المتريّة في الرسم. |
| [getPages()](#getPages--) | مجموعة كائنات Page. |
| [getRibbonX()](#getRibbonX--) | سلسلة Ribbon XML التي يتم تمريرها إلى المستند لتخصيص واجهة المستخدم لشريط الأدوات. |
| [getSolutionXMLs()](#getSolutionXMLs--) | قيمة XML. |
| [getStart()](#getStart--) | يشير إلى ما إذا تم تعديل المستند خارج Visio. |
| [getStyleSheets()](#getStyleSheets--) | مجموعة كائنات StyleSheet. |
| [getUnusedStyles()](#getUnusedStyles--) | احصل على الأنماط غير المستخدمة |
| [getUserCustomUI()](#getUserCustomUI--) | سلسلة Ribbon XML التي يتم تمريرها إلى المستند لتخصيص شريط الوصول السريع أو الشريط. |
| [getValidation()](#getValidation--) | يخزن معلومات حول التحقق من صحة المخطط للوثيقة. |
| [getVbProjectData()](#getVbProjectData--) | يحتوي على بيانات مشروع Microsoft Visual Basic for Applications بتنسيق MIME (Multipurpose Internet Mail Extensions) المشفر. |
| [getVbaProject()](#getVbaProject--) | يحصل على VbaProject[getVbaProject()](../../com.aspose.diagram/diagram\#getVbaProject--). |
| [getVersion()](#getVersion--) | رقم الإصدار لنسخة Visio. |
| [getWindows()](#getWindows--) | يحتوي على عناصر Window للمستند. |
| [hasHiddenInfo()](#hasHiddenInfo--) | يشير إلى ما إذا كان هذا المخطط يحتوي على معلومات مخفية. |
| [hashCode()](#hashCode--) |  |
| [layout(LayoutOptions options)](#layout-com.aspose.diagram.LayoutOptions-) | يقوم بترتيب الأشكال و/أو إعادة توجيه الموصلات لجميع صفحات المخطط. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [print(String printerName)](#print-java.lang.String-) | اطبع المستند بالكامل إلى الطابعة المحددة، باستخدام وحدة التحكم في الطباعة القياسية (بدون واجهة مستخدم). |
| [print(String printerName, PrintSaveOptions options)](#print-java.lang.String-com.aspose.diagram.PrintSaveOptions-) | اطبع المستند بالكامل إلى الطابعة المحددة، باستخدام وحدة التحكم في الطباعة القياسية (بدون واجهة مستخدم). |
| [print(String printerName, String documentName)](#print-java.lang.String-java.lang.String-) | يطبع المستند، باستخدام وحدة التحكم في الطباعة القياسية (بدون واجهة مستخدم) واسم المستند. |
| [print(String printerName, String documentName, PrintSaveOptions options)](#print-java.lang.String-java.lang.String-com.aspose.diagram.PrintSaveOptions-) | يطبع المستند، باستخدام وحدة التحكم في الطباعة القياسية (بدون واجهة مستخدم) واسم المستند. |
| [removeHiddenInformation(int item)](#removeHiddenInformation-int-) | إزالة المعلومات غير المستخدمة |
| [removeMacro()](#removeMacro--) | يزيل VBA/الماكرو من هذا المخطط. |
| [save(OutputStream stream, SaveOptions saveOptions)](#save-java.io.OutputStream-com.aspose.diagram.SaveOptions-) | احفظ المخطط إلى الدفق. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | احفظ المخطط إلى الدفق. |
| [save(String filename, SaveOptions options)](#save-java.lang.String-com.aspose.diagram.SaveOptions-) | يحفظ المستند إلى ملف باستخدام خيارات الحفظ المحددة. |
| [save(String filename, int format)](#save-java.lang.String-int-) | يحفظ بيانات المخطط إلى الملف. |
| [setBuildnum(long value)](#setBuildnum-long-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getBuildnum()](../../com.aspose.diagram/diagram\\#getBuildnum--) |
| [setDocLangID(int value)](#setDocLangID-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getDocLangID()](../../com.aspose.diagram/diagram\\#getDocLangID--) |
| [setEmailRoutingData(byte[] value)](#setEmailRoutingData-byte---) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getEmailRoutingData()](../../com.aspose.diagram/diagram\\#getEmailRoutingData--) |
| [setFontDirs(String[] value)](#setFontDirs-java.lang.String---) | يشير إلى مسار مجلد الخطوط |
| [setInterruptMonitor(AbstractInterruptMonitor value)](#setInterruptMonitor-com.aspose.diagram.AbstractInterruptMonitor-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getInterruptMonitor()](../../com.aspose.diagram/diagram\\#getInterruptMonitor--) |
| [setKey(String value)](#setKey-java.lang.String-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getKey()](../../com.aspose.diagram/diagram\\#getKey--) |
| [setMetric(int value)](#setMetric-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getMetric()](../../com.aspose.diagram/diagram\\#getMetric--) |
| [setRibbonX(String value)](#setRibbonX-java.lang.String-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getRibbonX()](../../com.aspose.diagram/diagram\\#getRibbonX--) |
| [setStart(long value)](#setStart-long-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getStart()](../../com.aspose.diagram/diagram\\#getStart--) |
| [setUserCustomUI(String value)](#setUserCustomUI-java.lang.String-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getUserCustomUI()](../../com.aspose.diagram/diagram\\#getUserCustomUI--) |
| [setVbProjectData(byte[] value)](#setVbProjectData-byte---) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getVbProjectData()](../../com.aspose.diagram/diagram\\#getVbProjectData--) |
| [setVersion(String value)](#setVersion-java.lang.String-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getVersion()](../../com.aspose.diagram/diagram\\#getVersion--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Diagram() {#Diagram--}
```
public Diagram()
```


### Diagram(String filename) {#Diagram-java.lang.String-}
```
public Diagram(String filename)
```


منشئ الفئة العامة، يحمل المخطط من الملف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| اسم الملف | java.lang.String | اسم الملف. |

### Diagram(InputStream stream) {#Diagram-java.io.InputStream-}
```
public Diagram(InputStream stream)
```


منشئ الفئة العامة، يحمل المخطط من التدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | java.io.InputStream | دفق البيانات. |

### Diagram(InputStream stream, int format) {#Diagram-java.io.InputStream-int-}
```
public Diagram(InputStream stream, int format)
```


منشئ الفئة العامة، يحمل المخطط من التدفق باستخدام تنسيق مسبق التعريف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | java.io.InputStream | دفق البيانات. |
| تنسيق | int | بيانات Aspose.Diagram.LoadFileFormat. |

### Diagram(InputStream stream, LoadOptions options) {#Diagram-java.io.InputStream-com.aspose.diagram.LoadOptions-}
```
public Diagram(InputStream stream, LoadOptions options)
```


منشئ الفئة العامة، يحمل المخطط من التدفق باستخدام خيارات تحميل الملف المسبقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | java.io.InputStream | دفق البيانات. |
| options | [LoadOptions](../../com.aspose.diagram/loadoptions) | بيانات [LoadOptions](../../com.aspose.diagram/loadoptions). |

### Diagram(String filename, int format) {#Diagram-java.lang.String-int-}
```
public Diagram(String filename, int format)
```


منشئ الفئة العامة، يحمل المخطط من الملف باستخدام تنسيق مسبق التعريف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| اسم الملف | java.lang.String | اسم الملف. |
| تنسيق | int | تنسيق الملف. |

### Diagram(String filename, LoadOptions options) {#Diagram-java.lang.String-com.aspose.diagram.LoadOptions-}
```
public Diagram(String filename, LoadOptions options)
```


منشئ الفئة العامة، يحمل المخطط من الملف باستخدام خيارات تحميل الملف المسبقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| اسم الملف | java.lang.String | اسم الملف. |
| options | [LoadOptions](../../com.aspose.diagram/loadoptions) | بيانات [LoadOptions](../../com.aspose.diagram/loadoptions). |

### addMaster(Diagram srcDiagram, String masterName) {#addMaster-com.aspose.diagram.Diagram-java.lang.String-}
```
public int addMaster(Diagram srcDiagram, String masterName)
```


يضيف master إلى المخطط من مخطط المصدر باستخدام اسم master أو NameU.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| srcDiagram | [Diagram](../../com.aspose.diagram/diagram) | مخطط المصدر. |
| masterName | java.lang.String | اسم Master أو NameU. |

**Returns:**
int - المعرف الفريد للماستر داخل مجموعة الماسترز في هذا المخطط.
### addMaster(InputStream templateStream, int masterID) {#addMaster-java.io.InputStream-int-}
```
public int addMaster(InputStream templateStream, int masterID)
```


يضيف master إلى المخطط من تدفق القالب باستخدام معرف master.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق القالب | java.io.InputStream | تدفق القالب. |
| معرف الماستر | int | المعرف الفريد للماستر داخل مجموعة الماسترز في القالب. |

**Returns:**
int - المعرف الفريد للماستر داخل مجموعة الماسترز في هذا المخطط.
### addMaster(InputStream templateStream, String masterName) {#addMaster-java.io.InputStream-java.lang.String-}
```
public int addMaster(InputStream templateStream, String masterName)
```


يضيف master إلى المخطط من تدفق القالب باستخدام اسم master أو NameU.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق القالب | java.io.InputStream | تدفق القالب. |
| masterName | java.lang.String | اسم Master أو NameU. |

**Returns:**
int - المعرف الفريد للماستر داخل مجموعة الماسترز في هذا المخطط.
### addMaster(String templateFilePath, int masterID) {#addMaster-java.lang.String-int-}
```
public int addMaster(String templateFilePath, int masterID)
```


يضيف master إلى المخطط من ملف القالب باستخدام معرف master.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| templateFilePath | java.lang.String | مسار ملف القالب (يمكن أن يكون بتنسيق vdx أو vst أو vsd). |
| معرف الماستر | int | المعرف الفريد للماستر داخل مجموعة الماسترز في القالب. |

**Returns:**
int - المعرف الفريد للماستر داخل مجموعة الماسترز في هذا المخطط.
### addMaster(String templateFilePath, String masterName) {#addMaster-java.lang.String-java.lang.String-}
```
public int addMaster(String templateFilePath, String masterName)
```


يضيف master إلى المخطط من ملف القالب باستخدام اسم master أو NameU.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| templateFilePath | java.lang.String | مسار ملف القالب (يمكن أن يكون بتنسيق vdx أو vst أو vsd). |
| masterName | java.lang.String | اسم Master أو NameU. |

**Returns:**
int - المعرف الفريد للماستر داخل مجموعة الماسترز في هذا المخطط.
### addShape(Shape newShape, String masterName, int pageNumber) {#addShape-com.aspose.diagram.Shape-java.lang.String-int-}
```
public long addShape(Shape newShape, String masterName, int pageNumber)
```


يضيف شكلًا تم إنشاؤه بواسطة القالب إلى صفحة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newShape | [Shape](../../com.aspose.diagram/shape) | كائن شكل جديد[Shape](../../com.aspose.diagram/shape). |
| masterName | java.lang.String | اسم القالب. |
| pageNumber | int | فهرس الصفحة. |

**Returns:**
long - المعرف الفريد للشكل داخل مجموعة الأشكال في الصفحة المحددة.
### addShape(double pinX, double pinY, double width, double height, String masterName, int pageNumber) {#addShape-double-double-double-double-java.lang.String-int-}
```
public long addShape(double pinX, double pinY, double width, double height, String masterName, int pageNumber)
```


يضيف شكلًا تم إنشاؤه بواسطة القالب على الصفحة مع PinX و PinY والعرض والارتفاع المحددين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pinX | double | يحدد الإحداثي السيني لدبوس الشكل (مركز الدوران) بالنسبة للصفحة. |
| pinY | double | يحدد الإحداثي الصادي لدبوس الشكل (مركز الدوران) بالنسبة للصفحة. |
| width | double | يحدد عرض الشكل بالبوصة. |
| height | double | يحدد ارتفاع الشكل بالبوصة. |
| masterName | java.lang.String | اسم القالب. |
| pageNumber | int | فهرس الصفحة. |

**Returns:**
long - المعرف الفريد للشكل داخل مجموعة الأشكال في الصفحة المحددة.
### addShape(double pinX, double pinY, String masterName, int pageNumber) {#addShape-double-double-java.lang.String-int-}
```
public long addShape(double pinX, double pinY, String masterName, int pageNumber)
```


يضيف شكلًا تم إنشاؤه بواسطة القالب على الصفحة مع PinX و PinY المحددين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pinX | double | يحدد الإحداثي السيني لدبوس الشكل (مركز الدوران) بالنسبة للصفحة. |
| pinY | double | يحدد الإحداثي الصادي لدبوس الشكل (مركز الدوران) بالنسبة للصفحة. |
| masterName | java.lang.String | اسم القالب. |
| pageNumber | int | فهرس الصفحة. |

**Returns:**
long - المعرف الفريد للشكل داخل مجموعة الأشكال في الصفحة المحددة.
### combine(Diagram secondDiagram) {#combine-com.aspose.diagram.Diagram-}
```
public void combine(Diagram secondDiagram)
```


يجمع كائن Diagram آخر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| secondDiagram | [Diagram](../../com.aspose.diagram/diagram) | كائن Diagram آخر. |

### copyTheme(Diagram source) {#copyTheme-com.aspose.diagram.Diagram-}
```
public void copyTheme(Diagram source)
```


ينسخ Theme من مخطط مصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [Diagram](../../com.aspose.diagram/diagram) | مخطط المصدر. |

### dispose() {#dispose--}
```
public void dispose()
```


ينفّذ مهامًا محددة من قبل التطبيق مرتبطة بتحرير أو إطلاق أو إعادة ضبط الموارد غير المُدارة.

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
### export(InputStream inputVsd, InputStream outputVdw) {#export-java.io.InputStream-java.io.InputStream-}
```
public static void export(InputStream inputVsd, InputStream outputVdw)
```


يصدّر المخطط من تدفق vsd إلى تنسيق تدفق vdw. لم يتم تنفيذها بعد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| inputVsd | java.io.InputStream | تدفق vsd. |
| outputVdw | java.io.InputStream | تدفق vdw. |

### export(InputStream inputVsd, String outputVdw) {#export-java.io.InputStream-java.lang.String-}
```
public static void export(InputStream inputVsd, String outputVdw)
```


يصدّر المخطط من تدفق vsd إلى تنسيق ملف \*.vdw. لم يتم تنفيذها بعد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| inputVsd | java.io.InputStream | اسم ملف \*.vsd. |
| outputVdw | java.lang.String | تدفق vdw. |

### export(String inputVsd, InputStream outputVdw) {#export-java.lang.String-java.io.InputStream-}
```
public static void export(String inputVsd, InputStream outputVdw)
```


يصدّر المخطط من ملف vsd إلى تنسيق تدفق vdw. لم يتم تنفيذها بعد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| inputVsd | java.lang.String | اسم ملف \*.vsd. |
| outputVdw | java.io.InputStream | تدفق vdw. |

### export(String inputVsd, String outputVdw) {#export-java.lang.String-java.lang.String-}
```
public static void export(String inputVsd, String outputVdw)
```


يصدّر المخطط من vsd إلى تنسيق vdw. لم يتم تنفيذها بعد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| inputVsd | java.lang.String | اسم ملف \*.vsd. |
| outputVdw | java.lang.String | اسم ملف \*.vdw. |

### getActivePage() {#getActivePage--}
```
public Page getActivePage()
```


يحدد الصفحة النشطة

**Returns:**
[Page](../../com.aspose.diagram/page)
### getBuildnum() {#getBuildnum--}
```
public long getBuildnum()
```


رقم البناء لنسخة Visio المستخدمة لإنشاء المستند.

**Returns:**
long
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColors() {#getColors--}
```
public ColorEntryCollection getColors()
```


يحتوي على جدول ألوان المستند. يحتوي كل مستند على جدول ألوان واحد، يُدرج 24 لونًا قياسيًا متاحًا لتطبيقها على الكائنات مثل الأشكال والنص والطبقات في المستند.

**Returns:**
[ColorEntryCollection](../../com.aspose.diagram/colorentrycollection)
### getDataConnections() {#getDataConnections--}
```
public DataConnectionCollection getDataConnections()
```


يحتوي على عناصر DataConnection للمستند.

**Returns:**
[DataConnectionCollection](../../com.aspose.diagram/dataconnectioncollection)
### getDataRecordSets() {#getDataRecordSets--}
```
public DataRecordSetCollection getDataRecordSets()
```


مجموعة كائنات DataRecordset المرتبطة بكائن Document.

**Returns:**
[DataRecordSetCollection](../../com.aspose.diagram/datarecordsetcollection)
### getDefaultFontDir() {#getDefaultFontDir--}
```
public String getDefaultFontDir()
```


احصل على مسار مجلد الخطوط الافتراضية

**Returns:**
java.lang.String
### getDocLangID() {#getDocLangID--}
```
public int getDocLangID()
```


معرّف اللغة الفريد لواجهة المستخدم الذي حدده المستخدم في تفضيلات لغة Microsoft Office 2010.

**Returns:**
int
### getDocumentProps() {#getDocumentProps--}
```
public DocumentProperties getDocumentProps()
```


يحتوي على عناصر خصائص المستند مثل عنوان المستند، المؤلف، وما إلى ذلك.

**Returns:**
[DocumentProperties](../../com.aspose.diagram/documentproperties)
### getDocumentSettings() {#getDocumentSettings--}
```
public DocumentSettings getDocumentSettings()
```


يحتوي على عناصر تحدد إعدادات المستند.

**Returns:**
[DocumentSettings](../../com.aspose.diagram/documentsettings)
### getDocumentSheet() {#getDocumentSheet--}
```
public DocumentSheet getDocumentSheet()
```


يحدد بنية ShapeSheet للمستند.

**Returns:**
[DocumentSheet](../../com.aspose.diagram/documentsheet)
### getEmailRoutingData() {#getEmailRoutingData--}
```
public byte[] getEmailRoutingData()
```


يحتوي على قسيمة توجيه بريد إلكتروني MAPI مشفرة بتنسيق MIME (Multipurpose Internet Mail Extensions) للمستند.

**Returns:**
byte[]
### getEventItems() {#getEventItems--}
```
public EventItemCollection getEventItems()
```


يحتوي على عنصر EventItem لكل حدث يجب أن يستجيب له الكائن.

**Returns:**
[EventItemCollection](../../com.aspose.diagram/eventitemcollection)
### getFonts() {#getFonts--}
```
public FontCollection getFonts()
```


يحتوي على مجموعة من عناصر Font

**Returns:**
[FontCollection](../../com.aspose.diagram/fontcollection)
### getHeaderFooter() {#getHeaderFooter--}
```
public HeaderFooter getHeaderFooter()
```


يحتوي على عناصر لترويسة وتذييل المستند.

**Returns:**
[HeaderFooter](../../com.aspose.diagram/headerfooter)
### getInterruptMonitor() {#getInterruptMonitor--}
```
public AbstractInterruptMonitor getInterruptMonitor()
```


مراقب المقاطعة.

**Returns:**
[AbstractInterruptMonitor](../../com.aspose.diagram/abstractinterruptmonitor)
### getKey() {#getKey--}
```
public String getKey()
```


يشير إلى ما إذا تم تعديل المستند خارج Visio. إذا كان موجودًا، سيقوم Visio باختبار محتويات الملف بالكامل. احذف ذلك للملفات التي تنشئها خارج Visio.

**Returns:**
java.lang.String
### getMasters() {#getMasters--}
```
public MasterCollection getMasters()
```


مجموعة كائنات Master.

**Returns:**
[MasterCollection](../../com.aspose.diagram/mastercollection)
### getMetric() {#getMetric--}
```
public int getMetric()
```


ما إذا كان سيتم استخدام الوحدات المتريّة في الرسم. اضبط هذه الخاصية إلى True (1) لاستخدام الوحدات المتريّة؛ واضبطها إلى False (0) لاستخدام الوحدات الإنجليزية.

**Returns:**
int
### getPages() {#getPages--}
```
public PageCollection getPages()
```


مجموعة كائنات Page.

**Returns:**
[PageCollection](../../com.aspose.diagram/pagecollection)
### getRibbonX() {#getRibbonX--}
```
public String getRibbonX()
```


سلسلة Ribbon XML التي يتم تمريرها إلى المستند لتخصيص واجهة المستخدم لشريط الأدوات.

**Returns:**
java.lang.String
### getSolutionXMLs() {#getSolutionXMLs--}
```
public SolutionXMLCollection getSolutionXMLs()
```


قيمة XML.

**Returns:**
[SolutionXMLCollection](../../com.aspose.diagram/solutionxmlcollection)
### getStart() {#getStart--}
```
public long getStart()
```


يشير إلى ما إذا تم تعديل المستند خارج Visio. إذا كان موجودًا، سيقوم Visio باختبار محتويات الملف بالكامل. احذف ذلك للملفات التي تنشئها خارج Visio.

**Returns:**
long
### getStyleSheets() {#getStyleSheets--}
```
public StyleSheetCollection getStyleSheets()
```


مجموعة كائنات StyleSheet.

**Returns:**
[StyleSheetCollection](../../com.aspose.diagram/stylesheetcollection)
### getUnusedStyles() {#getUnusedStyles--}
```
public StyleSheetCollection getUnusedStyles()
```


احصل على الأنماط غير المستخدمة

**Returns:**
[StyleSheetCollection](../../com.aspose.diagram/stylesheetcollection)
### getUserCustomUI() {#getUserCustomUI--}
```
public String getUserCustomUI()
```


سلسلة Ribbon XML التي يتم تمريرها إلى المستند لتخصيص شريط الوصول السريع أو الشريط.

**Returns:**
java.lang.String
### getValidation() {#getValidation--}
```
public Validation getValidation()
```


يخزن معلومات حول التحقق من صحة المخطط للوثيقة.

**Returns:**
[Validation](../../com.aspose.diagram/validation)
### getVbProjectData() {#getVbProjectData--}
```
public byte[] getVbProjectData()
```


يحتوي على بيانات مشروع Microsoft Visual Basic for Applications بتنسيق MIME (Multipurpose Internet Mail Extensions) المشفر.

**Returns:**
byte[]
### getVbaProject() {#getVbaProject--}
```
public VbaProject getVbaProject()
```


يحصل على VbaProject[getVbaProject()](../../com.aspose.diagram/diagram\#getVbaProject--).

**Returns:**
[VbaProject](../../com.aspose.diagram/vbaproject)
### getVersion() {#getVersion--}
```
public String getVersion()
```


رقم إصدار نسخة Visio. Microsoft Visio 2010 = 14.

**Returns:**
java.lang.String
### getWindows() {#getWindows--}
```
public WindowCollection getWindows()
```


يحتوي على عناصر Window للمستند.

**Returns:**
[WindowCollection](../../com.aspose.diagram/windowcollection)
### hasHiddenInfo() {#hasHiddenInfo--}
```
public boolean hasHiddenInfo()
```


يشير إلى ما إذا كان هذا المخطط يحتوي على معلومات مخفية.

**Returns:**
منطقي
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### layout(LayoutOptions options) {#layout-com.aspose.diagram.LayoutOptions-}
```
public void layout(LayoutOptions options)
```


يقوم بترتيب الأشكال و/أو إعادة توجيه الموصلات لجميع صفحات المخطط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| options | [LayoutOptions](../../com.aspose.diagram/layoutoptions) | استخدام [LayoutOptions](../../com.aspose.diagram/layoutoptions) لتكوين خيارات التخطيط. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### print(String printerName) {#print-java.lang.String-}
```
public void print(String printerName)
```


اطبع المستند بالكامل إلى الطابعة المحددة، باستخدام وحدة التحكم القياسية للطباعة (بدون واجهة مستخدم). إذا كان printerName يساوي Null أو فارغًا، سيتم استخدام الطابعة الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| printerName | java.lang.String | اسم الطابعة. يمكن أن يكون Null. |

### print(String printerName, PrintSaveOptions options) {#print-java.lang.String-com.aspose.diagram.PrintSaveOptions-}
```
public void print(String printerName, PrintSaveOptions options)
```


اطبع المستند بالكامل إلى الطابعة المحددة، باستخدام وحدة التحكم القياسية للطباعة (بدون واجهة مستخدم). إذا كان printerName يساوي Null أو فارغًا، سيتم استخدام الطابعة الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| printerName | java.lang.String | اسم الطابعة. يمكن أن يكون Null. |
| options | [PrintSaveOptions](../../com.aspose.diagram/printsaveoptions) | خيارات الطباعة. |

### print(String printerName, String documentName) {#print-java.lang.String-java.lang.String-}
```
public void print(String printerName, String documentName)
```


يطبع المستند، باستخدام وحدة التحكم في الطباعة القياسية (بدون واجهة مستخدم) واسم المستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| printerName | java.lang.String | اسم الطابعة. يمكن أن يكون Null. |
| documentName | java.lang.String | اسم المستند للعرض (على سبيل المثال، في مربع حوار حالة الطباعة أو طابور الطابعة) أثناء طباعة المستند. |

### print(String printerName, String documentName, PrintSaveOptions options) {#print-java.lang.String-java.lang.String-com.aspose.diagram.PrintSaveOptions-}
```
public void print(String printerName, String documentName, PrintSaveOptions options)
```


يطبع المستند، باستخدام وحدة التحكم في الطباعة القياسية (بدون واجهة مستخدم) واسم المستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| printerName | java.lang.String | اسم الطابعة. يمكن أن يكون Null. |
| documentName | java.lang.String | اسم المستند للعرض (على سبيل المثال، في مربع حوار حالة الطباعة أو طابور الطابعة) أثناء طباعة المستند. |
| options | [PrintSaveOptions](../../com.aspose.diagram/printsaveoptions) | خيارات الطباعة. |

### removeHiddenInformation(int item) {#removeHiddenInformation-int-}
```
public void removeHiddenInformation(int item)
```


إزالة المعلومات غير المستخدمة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | int | RemoveHiddenInfoItem. |

### removeMacro() {#removeMacro--}
```
public void removeMacro()
```


يزيل VBA/الماكرو من هذا المخطط.

### save(OutputStream stream, SaveOptions saveOptions) {#save-java.io.OutputStream-com.aspose.diagram.SaveOptions-}
```
public void save(OutputStream stream, SaveOptions saveOptions)
```


احفظ المخطط إلى الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | java.io.OutputStream | دفق الملف. |
| saveOptions | [SaveOptions](../../com.aspose.diagram/saveoptions) | خيارات الحفظ. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public void save(OutputStream stream, int format)
```


احفظ المخطط إلى الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | java.io.OutputStream | دفق الملف. |
| تنسيق | int |  |

### save(String filename, SaveOptions options) {#save-java.lang.String-com.aspose.diagram.SaveOptions-}
```
public void save(String filename, SaveOptions options)
```


يحفظ المستند إلى ملف باستخدام خيارات الحفظ المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| اسم الملف | java.lang.String | اسم الملف. |
| options | [SaveOptions](../../com.aspose.diagram/saveoptions) | [SaveOptions](../../com.aspose.diagram/saveoptions) حفظ خيارات المخطط. |

### save(String filename, int format) {#save-java.lang.String-int-}
```
public void save(String filename, int format)
```


يحفظ بيانات المخطط إلى الملف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| اسم الملف | java.lang.String | اسم الملف. |
| تنسيق | int | Aspose.Diagram.SaveFileFormat تنسيق حفظ الملف. |

### setBuildnum(long value) {#setBuildnum-long-}
```
public void setBuildnum(long value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getBuildnum()](../../com.aspose.diagram/diagram\\#getBuildnum--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | long |  |

### setDocLangID(int value) {#setDocLangID-int-}
```
public void setDocLangID(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getDocLangID()](../../com.aspose.diagram/diagram\\#getDocLangID--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setEmailRoutingData(byte[] value) {#setEmailRoutingData-byte---}
```
public void setEmailRoutingData(byte[] value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getEmailRoutingData()](../../com.aspose.diagram/diagram\\#getEmailRoutingData--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | byte[] |  |

### setFontDirs(String[] value) {#setFontDirs-java.lang.String---}
```
public void setFontDirs(String[] value)
```


يشير إلى مسار مجلد الخطوط

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String[] |  |

### setInterruptMonitor(AbstractInterruptMonitor value) {#setInterruptMonitor-com.aspose.diagram.AbstractInterruptMonitor-}
```
public void setInterruptMonitor(AbstractInterruptMonitor value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getInterruptMonitor()](../../com.aspose.diagram/diagram\\#getInterruptMonitor--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [AbstractInterruptMonitor](../../com.aspose.diagram/abstractinterruptmonitor) |  |

### setKey(String value) {#setKey-java.lang.String-}
```
public void setKey(String value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getKey()](../../com.aspose.diagram/diagram\\#getKey--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### setMetric(int value) {#setMetric-int-}
```
public void setMetric(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getMetric()](../../com.aspose.diagram/diagram\\#getMetric--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setRibbonX(String value) {#setRibbonX-java.lang.String-}
```
public void setRibbonX(String value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getRibbonX()](../../com.aspose.diagram/diagram\\#getRibbonX--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### setStart(long value) {#setStart-long-}
```
public void setStart(long value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getStart()](../../com.aspose.diagram/diagram\\#getStart--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | long |  |

### setUserCustomUI(String value) {#setUserCustomUI-java.lang.String-}
```
public void setUserCustomUI(String value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getUserCustomUI()](../../com.aspose.diagram/diagram\\#getUserCustomUI--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### setVbProjectData(byte[] value) {#setVbProjectData-byte---}
```
public void setVbProjectData(byte[] value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getVbProjectData()](../../com.aspose.diagram/diagram\\#getVbProjectData--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | byte[] |  |

### setVersion(String value) {#setVersion-java.lang.String-}
```
public void setVersion(String value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getVersion()](../../com.aspose.diagram/diagram\\#getVersion--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

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

