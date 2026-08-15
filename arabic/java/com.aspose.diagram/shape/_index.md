---
title: شكل
second_title: Aspose.Diagram لـ Java API Reference
description: يحتوي على عناصر تُعرّف شكلًا في صفحة رئيسية أو عنصر شكل مجموعة.
type: docs
weight: 355
url: /ar/java/com.aspose.diagram/shape/
---

**Inheritance:**
java.lang.Object
```
public class Shape
```

يحتوي على عناصر تُعرّف شكلاً في Master أو Page أو عنصر شكل مجموعة.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Shape()](#Shape--) | منشئ. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [bringForward()](#bringForward--) | ينقل الشكل إلى الأمام بموقع واحد في ترتيب الـ z. |
| [bringToFront()](#bringToFront--) | ينقل الشكل إلى مقدمة ترتيب الـ z. |
| [centerDrawing()](#centerDrawing--) | مركز الشكل بالنسبة إلى امتداد الصفحة |
| [connectedShapes(int flag, String categoryFilter)](#connectedShapes-int-java.lang.String-) | يرجع مصفوفة تحتوي على المعرفات (IDs) للأشكال المتصلة بهذا الشكل. |
| [copy(Shape source)](#copy-com.aspose.diagram.Shape-) |  |
| [dependsOnShapes()](#dependsOnShapes--) | يرجع مصفوفة تحتوي على معرفات الأشكال التي تعتمد على شكل ما. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActiveXControl()](#getActiveXControl--) | يحصل على عنصر التحكم ActiveX. |
| [getActs()](#getActs--) | يحتوي على مجموعة من عناصر Act. |
| [getAlign()](#getAlign--) | يشير إلى محاذاة الشكل بالنسبة إلى الدليل أو نقطة الدليل التي يُلصق بها الشكل. |
| [getChars()](#getChars--) | يحتوي على مجموعة من عناصر Char. |
| [getClass()](#getClass--) |  |
| [getClippingPath()](#getClippingPath--) |  |
| [getConnectionABCDs()](#getConnectionABCDs--) | يحتوي على مجموعة من عناصر ConnectionABCD. |
| [getConnections()](#getConnections--) | يحتوي على مجموعة من عناصر Connection. |
| [getConnectorRule()](#getConnectorRule--) | يرجع connectorRule يحتوي على معرف الشكل والاتصال المتصل بالشكل. |
| [getConnectorsType()](#getConnectorsType--) | احصل على نوع الموصلات |
| [getControlData()](#getControlData--) | يحصل على بيانات التحكم. |
| [getControls()](#getControls--) | يحتوي على مجموعة من عناصر Control. |
| [getData1()](#getData1--) | يحتوي على قيمة نصية عشوائية تُستخدم لتوفير معلومات إضافية حول الشكل. |
| [getData2()](#getData2--) | يحتوي على قيمة نصية عشوائية تُستخدم لتوفير معلومات إضافية حول الشكل. |
| [getData3()](#getData3--) | يحتوي على قيمة نصية عشوائية تُستخدم لتوفير معلومات إضافية حول الشكل. |
| [getDel()](#getDel--) | علامة تشير إلى ما إذا كان العنصر محذوفًا محليًا. |
| [getDiagram()](#getDiagram--) | العنصر الجذر لهرمية كائنات Visio. |
| [getDisplayText()](#getDisplayText--) | احصل على النص المعروض في الواجهة |
| [getEvent()](#getEvent--) | يحتوي على عناصر تحدد الصيغ التي تتحكم في أحداث الشكل. |
| [getFields()](#getFields--) | يحتوي على مجموعة من عناصر Field. |
| [getFill()](#getFill--) | يحتوي على قيم تنسيق التعبئة الحالية للشكل وظل الشكل المنسدل، بما في ذلك النمط، لون المقدمة، ولون الخلفية. |
| [getFillStyle()](#getFillStyle--) | ورقة الأنماط التي يرث منها هذا الشكل تنسيق التعبئة. |
| [getForeign()](#getForeign--) | يحتوي على عناصر تحدد العرض والارتفاع لكائن من برنامج آخر يُستخدم في مستند Microsoft Visio. |
| [getForeignData()](#getForeignData--) | يحتوي على BLOB مشفر بتنسيق MIME (Multipurpose Internet Mail Extensions) لبيانات الصورة، مثل ملف ميتافايل Windows أو bitmap أو بيانات OLE. |
| [getGeoms()](#getGeoms--) | يحتوي على مجموعة من عناصر Geom. |
| [getGroup()](#getGroup--) | يحتوي على عناصر تتحكم في كيفية إضافة الأشكال إلى مجموعة، نقل أعضاء المجموعة، واختيار المجموعات. |
| [getHelp()](#getHelp--) | يحتوي على عناصر تحدد موضوع ملف المساعدة لعنصر Shape ومعلومات حقوق النشر. |
| [getHyperlinks()](#getHyperlinks--) | يحتوي على مجموعة من عناصر Hyperlink. |
| [getID()](#getID--) | المعرّف الفريد للعنصر داخل العنصر الأب. |
| [getImage()](#getImage--) | يحتوي على قيم الجاما، السطوع، التباين، الضبابية، الشحذ، إزالة الضوضاء، والشفافية لملف bitmap. |
| [getInheritChars()](#getInheritChars--) | يحتوي على قيم الأحرف التي يرثها الشكل من الشكل الرئيسي. |
| [getInheritFill()](#getInheritFill--) | يحتوي على قيم تنسيق التعبئة التي يرثها الشكل من النمط الأب والشكل الرئيسي. |
| [getInheritGeoms()](#getInheritGeoms--) | يحتوي على قيم Geoms للشكل الموروث من الشكل الرئيسي. |
| [getInheritLine()](#getInheritLine--) | يحتوي على قيم تنسيق الخط للشكل الموروث من نمط الوالد والشكل الرئيسي. |
| [getInheritParas()](#getInheritParas--) | يحتوي على الـ paras للشكل الموروث من نمط الوالد والشكل الرئيسي. |
| [getInheritProps()](#getInheritProps--) | يحتوي على الـ props للشكل الموروث من الشكل الرئيسي. |
| [getInheritTextBlock()](#getInheritTextBlock--) | يحتوي على قيم textblock للشكل الموروث من نمط الوالد والشكل الرئيسي. |
| [getInheritUsers()](#getInheritUsers--) | يحتوي على الـ users للشكل الموروث من الشكل الرئيسي. |
| [getLayerMem()](#getLayerMem--) | يحتوي على عنصر LayerMember، الذي يحدد كل طبقة يُعيّن إليها الشكل. |
| [getLayout()](#getLayout--) | يحتوي على عناصر تتحكم في وضع الشكل وإعدادات توجيه الموصلات. |
| [getLine()](#getLine--) | يحتوي على عناصر تتحكم في سمات الخط لشكل ما، مثل النمط والوزن واللون. |
| [getLineStyle()](#getLineStyle--) | ورقة الأنماط التي يرث منها هذا الشكل تنسيق الخط |
| [getMaster()](#getMaster--) | الماستر الذي يرث منه الشكل بياناته. |
| [getMasterShape()](#getMasterShape--) | قد يتواجد هذا السمة فقط في الأشكال التي هي أعضاء في مجموعة أشكال، وتكون المجموعة نسخة من ماستر. |
| [getMisc()](#getMisc--) | يحتوي على عناصر تحدد موضوع ملف المساعدة لعنصر Shape ومعلومات حقوق النشر. |
| [getName()](#getName--) | اسم العنصر. |
| [getNameU()](#getNameU--) | الاسم العام للعنصر. |
| [getOneD()](#getOneD--) | يحدد ما إذا كان الشكل يتصرف ككائن أحادي البعد (1-D). |
| [getPage()](#getPage--) | العنصر الجذر لهرمية كائنات Visio. |
| [getParas()](#getParas--) | يحتوي على مجموعة من عناصر Para. |
| [getParentShape()](#getParentShape--) | الوالد الخاص بالشكل. |
| [getProps()](#getProps--) | يحتوي على مجموعة من عناصر Prop. |
| [getProtection()](#getProtection--) | يساعد القفل على منع التغييرات غير المقصودة على الشكل لكنه لا يمنع Microsoft Visio من إعادة تعيين القيم في ظروف أخرى. |
| [getPureText()](#getPureText--) | احصل على سلسلة النص |
| [getRootShape()](#getRootShape--) | يعيد الشكل الأعلى المستوى في نسخة إذا كان هذا الشكل جزءًا من نسخة ماستر. |
| [getScratchs()](#getScratchs--) | يحتوي على مجموعة من عناصر Scratch. |
| [getShapes()](#getShapes--) | يحتوي على مجموعة من عناصر Shape. |
| [getSmartTagDefs()](#getSmartTagDefs--) | يحتوي على مجموعة من عناصر SmartTagDef. |
| [getTabsCollection()](#getTabsCollection--) | يحتوي على مجموعة من عناصر التبويب. |
| [getText()](#getText--) | يحتوي على نص الشكل. |
| [getTextBlock()](#getTextBlock--) | يحتوي على عناصر تحدد محاذاة وهوامش ومواقع إيقاف التبويب الافتراضية للنص في كتلة النص الخاصة بالشكل. |
| [getTextStyle()](#getTextStyle--) | ورقة الأنماط التي يرث منها هذا الشكل تنسيق النص. |
| [getTextXForm()](#getTextXForm--) | يحتوي على عناصر تحدد معلومات التموضع حول كتلة النص الخاصة بالشكل. |
| [getThreeDFormat()](#getThreeDFormat--) | يحصل على ThreeDFormat. |
| [getTwoD()](#getTwoD--) | يحدد ما إذا كان الشكل يتصرف ككائن ثنائي الأبعاد (2-D). |
| [getType()](#getType--) | نوع الشكل. |
| [getUniqueID()](#getUniqueID--) | معرف GUID (معرف فريد عالميًا) مخصص للشكل. |
| [getUsers()](#getUsers--) | يحتوي على مجموعة من عناصر User. |
| [getXForm()](#getXForm--) | يحتوي على عناصر تحدد معلومات التموضع العامة حول الشكل. |
| [getXForm1D()](#getXForm1D--) | يحتوي على إحداثيات x و y لنقطة البداية ونقطة النهاية لشكل أحادي البعد. |
| [getZOrderIndex()](#getZOrderIndex--) | يعيد فهرس الشكل في ترتيب z باستثناء شكل الدليل. |
| [gluedShapes(int flag, String categoryFilter, Shape otherShape)](#gluedShapes-int-java.lang.String-com.aspose.diagram.Shape-) | يعيد مصفوفة تحتوي على معرفات الأشكال الملصوقة على شكل ما. |
| [hashCode()](#hashCode--) |  |
| [isConnected(Shape shape)](#isConnected-com.aspose.diagram.Shape-) | يشير إلى ما إذا كان هذان الشكلان متصلان. |
| [isContain(Shape shape)](#isContain-com.aspose.diagram.Shape-) | يشير إلى ما إذا كان هذا الشكل يحتوي على شكل آخر. |
| [isGlued(Shape shape)](#isGlued-com.aspose.diagram.Shape-) | يشير إلى ما إذا كان هذان الشكلان ملصوقان. |
| [isInGroup()](#isInGroup--) | يشير إلى ما إذا كان هذا الشكل داخل مجموعة أشكال. |
| [isIntersect(Shape shape)](#isIntersect-com.aspose.diagram.Shape-) | يشير إلى ما إذا كان هذا الشكل يتقاطع مع شكل آخر. |
| [isTextEmpty()](#isTextEmpty--) | يشير إلى أن الشكل يحتوي على نص وما إذا كان النص فارغًا أم لا. |
| [move(double dX, double dY)](#move-double-double-) | ينقل الشكل بمقدار dX و dY بوصة من الموقع الحالي. |
| [moveTo(double newPinX, double newPinY)](#moveTo-double-double-) | ينقل الشكل إلى موقع مطلق جديد على الصفحة. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [refreshData()](#refreshData--) | يقوم بتحديث موضع الشكل بما في ذلك xform والاتصال والجيوم عند تغيير نص الشكل أو غيره. |
| [replaceText(String text, String replaceText)](#replaceText-java.lang.String-java.lang.String-) | استبدل سلسلة النص الخاصة بالشكل. |
| [sendBackward()](#sendBackward--) | ينقل الشكل خطوة واحدة إلى الخلف في ترتيب z. |
| [sendToBack()](#sendToBack--) | ينقل الشكل إلى الخلف في ترتيب z. |
| [setAngle(double angle)](#setAngle-double-) | يضبط زاوية جديدة للشكل. |
| [setClippingPath(String value)](#setClippingPath-java.lang.String-) | لوصف هذه الخاصية، يرجى الاطلاع على [getClippingPath()](../../com.aspose.diagram/shape\#getClippingPath--) |
| [setConnectorsType(int type)](#setConnectorsType-int-) | تعيين نوع الموصلات |
| [setData1(String value)](#setData1-java.lang.String-) | لوصف هذه الخاصية، يرجى الاطلاع على [getData1()](../../com.aspose.diagram/shape\#getData1--) |
| [setData2(String value)](#setData2-java.lang.String-) | لوصف هذه الخاصية، يرجى الاطلاع على [getData2()](../../com.aspose.diagram/shape\#getData2--) |
| [setData3(String value)](#setData3-java.lang.String-) | لوصف هذه الخاصية، يرجى الاطلاع على [getData3()](../../com.aspose.diagram/shape\#getData3--) |
| [setDel(int value)](#setDel-int-) | لوصف هذه الخاصية، يرجى الاطلاع على [getDel()](../../com.aspose.diagram/shape\#getDel--) |
| [setDiagram(Diagram value)](#setDiagram-com.aspose.diagram.Diagram-) | لوصف هذه الخاصية، يرجى الاطلاع على [getDiagram()](../../com.aspose.diagram/shape\#getDiagram--) |
| [setEvent(Event value)](#setEvent-com.aspose.diagram.Event-) | لوصف هذه الخاصية، يرجى الاطلاع على [getEvent()](../../com.aspose.diagram/shape\#getEvent--) |
| [setFillStyle(StyleSheet value)](#setFillStyle-com.aspose.diagram.StyleSheet-) | لوصف هذه الخاصية، يرجى الاطلاع على [getFillStyle()](../../com.aspose.diagram/shape\#getFillStyle--) |
| [setHeight(double height)](#setHeight-double-) | يضبط ارتفاعًا جديدًا للشكل. |
| [setID(long value)](#setID-long-) | لوصف هذه الخاصية، يرجى الاطلاع على [getID()](../../com.aspose.diagram/shape\#getID--) |
| [setLineStyle(StyleSheet value)](#setLineStyle-com.aspose.diagram.StyleSheet-) | لوصف هذه الخاصية، يرجى الاطلاع على [getLineStyle()](../../com.aspose.diagram/shape\#getLineStyle--) |
| [setMaster(Master value)](#setMaster-com.aspose.diagram.Master-) | لوصف هذه الخاصية، يرجى الاطلاع على [getMaster()](../../com.aspose.diagram/shape\#getMaster--) |
| [setMasterShape(Shape value)](#setMasterShape-com.aspose.diagram.Shape-) | لوصف هذه الخاصية، يرجى الاطلاع على [getMasterShape()](../../com.aspose.diagram/shape\#getMasterShape--) |
| [setName(String value)](#setName-java.lang.String-) | لوصف هذه الخاصية، يرجى الاطلاع على [getName()](../../com.aspose.diagram/shape\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | لوصف هذه الخاصية، يرجى الاطلاع على [getNameU()](../../com.aspose.diagram/shape\#getNameU--) |
| [setPage(Page value)](#setPage-com.aspose.diagram.Page-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getPage()](../../com.aspose.diagram/shape\#getPage--) |
| [setParentShape(Shape value)](#setParentShape-com.aspose.diagram.Shape-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getParentShape()](../../com.aspose.diagram/shape\#getParentShape--) |
| [setPresetTheme(int value)](#setPresetTheme-int-) | تطبيق سمة مسبقة على هذا الشكل |
| [setPresetThemeQuickStyle(int value)](#setPresetThemeQuickStyle-int-) | تطبيق نمط سريع لتغيير نسخة سمة مسبقة على هذا الشكل |
| [setPresetThemeStyleMatrics(int styleIndex, int colorIndex)](#setPresetThemeStyleMatrics-int-int-) | تطبيق نمط سريع لتغيير نسخة سمة مسبقة على هذا الشكل، مثل خيارات أنماط السمة في قائمة أنماط الشكل المنسدلة |
| [setPresetThemeVariant(int value)](#setPresetThemeVariant-int-) | تطبيق نسخة سمة مسبقة على هذا الشكل |
| [setProps(PropCollection value)](#setProps-com.aspose.diagram.PropCollection-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getProps()](../../com.aspose.diagram/shape\#getProps--) |
| [setText(Text value)](#setText-com.aspose.diagram.Text-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getText()](../../com.aspose.diagram/shape\#getText--) |
| [setTextStyle(StyleSheet value)](#setTextStyle-com.aspose.diagram.StyleSheet-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getTextStyle()](../../com.aspose.diagram/shape\#getTextStyle--) |
| [setTwoD(boolean value)](#setTwoD-boolean-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getTwoD()](../../com.aspose.diagram/shape\#getTwoD--) |
| [setType(int value)](#setType-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getType()](../../com.aspose.diagram/shape\#getType--) |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getUniqueID()](../../com.aspose.diagram/shape\#getUniqueID--) |
| [setWidth(double width)](#setWidth-double-) | تعيين عرض جديد للشكل. |
| [setXForm(XForm value)](#setXForm-com.aspose.diagram.XForm-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getXForm()](../../com.aspose.diagram/shape\#getXForm--) |
| [setXForm1D(XForm1D value)](#setXForm1D-com.aspose.diagram.XForm1D-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getXForm1D()](../../com.aspose.diagram/shape\#getXForm1D--) |
| [toHTML(InputStream stream, HTMLSaveOptions options)](#toHTML-java.io.InputStream-com.aspose.diagram.HTMLSaveOptions-) | إنشاء HTML للشكل وحفظه إلى تدفق بالصيغة المحددة. |
| [toHTML(OutputStream stream, HTMLSaveOptions options)](#toHTML-java.io.OutputStream-com.aspose.diagram.HTMLSaveOptions-) | إنشاء HTML للشكل وحفظه إلى تدفق بالصيغة المحددة. |
| [toHTML(String fileName, HTMLSaveOptions options)](#toHTML-java.lang.String-com.aspose.diagram.HTMLSaveOptions-) | إنشاء HTML وحفظه إلى ملف. |
| [toImage(InputStream stream, ImageSaveOptions options)](#toImage-java.io.InputStream-com.aspose.diagram.ImageSaveOptions-) | إنشاء صورة الشكل وحفظها إلى تدفق بالصيغة المحددة. |
| [toImage(OutputStream stream, ImageSaveOptions options)](#toImage-java.io.OutputStream-com.aspose.diagram.ImageSaveOptions-) | إنشاء صورة الشكل وحفظها إلى تدفق بالصيغة المحددة. |
| [toImage(String imageFile, ImageSaveOptions options)](#toImage-java.lang.String-com.aspose.diagram.ImageSaveOptions-) | إنشاء صورة الشكل وحفظها إلى ملف. |
| [toPdf(InputStream stream)](#toPdf-java.io.InputStream-) | إنشاء ملف PDF للشكل وحفظه إلى تدفق. |
| [toPdf(OutputStream stream)](#toPdf-java.io.OutputStream-) | إنشاء ملف PDF للشكل وحفظه إلى تدفق. |
| [toPdf(String fileName)](#toPdf-java.lang.String-) | حفظ الشكل إلى ملف PDF. |
| [toString()](#toString--) |  |
| [toSvg(String imageFile, SVGSaveOptions options)](#toSvg-java.lang.String-com.aspose.diagram.SVGSaveOptions-) | حفظ الشكل إلى ملف SVG. |
| [ungroup()](#ungroup--) | فك تجميع الشكل |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Shape() {#Shape--}
```
public Shape()
```


منشئ.

### bringForward() {#bringForward--}
```
public void bringForward()
```


ينقل الشكل إلى الأمام بموقع واحد في ترتيب الـ z.

### bringToFront() {#bringToFront--}
```
public void bringToFront()
```


ينقل الشكل إلى مقدمة ترتيب الـ z.

### centerDrawing() {#centerDrawing--}
```
public void centerDrawing()
```


مركز الشكل بالنسبة إلى امتداد الصفحة

### connectedShapes(int flag, String categoryFilter) {#connectedShapes-int-java.lang.String-}
```
public long[] connectedShapes(int flag, String categoryFilter)
```


يرجع مصفوفة تحتوي على المعرفات (IDs) للأشكال المتصلة بهذا الشكل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| علامة | int | تصفية مصفوفة معرّفات الأشكال المرتجعة حسب اتجاه الموصلات. راجع الملاحظات للقيم المحتملة Aspose.Diagram.ConnectedShapesFlags. |
| categoryFilter | java.lang.String | يقوم بتصفية مصفوفة معرفات الأشكال المرتجعة عن طريق حصرها على المعرفات للأشكال التي تطابق categoryString المحدد. |

**Returns:**
long[] - مصفوفة معرفات.
### copy(Shape source) {#copy-com.aspose.diagram.Shape-}
```
public void copy(Shape source)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [Shape](../../com.aspose.diagram/shape) |  |

### dependsOnShapes() {#dependsOnShapes--}
```
public long[] dependsOnShapes()
```


يرجع مصفوفة تحتوي على معرفات الأشكال التي تعتمد على شكل ما.

**Returns:**
long[] - مصفوفة معرفات.
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
### getActiveXControl() {#getActiveXControl--}
```
public ActiveXControl getActiveXControl()
```


يحصل على عنصر التحكم ActiveX.

**Returns:**
[ActiveXControl](../../com.aspose.diagram/activexcontrol)
### getActs() {#getActs--}
```
public ActCollection getActs()
```


يحتوي على مجموعة من عناصر Act.

**Returns:**
[ActCollection](../../com.aspose.diagram/actcollection)
### getAlign() {#getAlign--}
```
public Align getAlign()
```


يشير إلى محاذاة الشكل بالنسبة إلى الدليل أو نقطة الدليل التي تم لصق الشكل بها. يظهر عنصر Align فقط للأشكال التي تم لصقها بالدلائل أو نقاط الدليل.

**Returns:**
[Align](../../com.aspose.diagram/align)
### getChars() {#getChars--}
```
public CharCollection getChars()
```


يحتوي على مجموعة من عناصر Char.

**Returns:**
[CharCollection](../../com.aspose.diagram/charcollection)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClippingPath() {#getClippingPath--}
```
public String getClippingPath()
```




**Returns:**
java.lang.String
### getConnectionABCDs() {#getConnectionABCDs--}
```
public ConnectionABCDCollection getConnectionABCDs()
```


يحتوي على مجموعة من عناصر ConnectionABCD.

**Returns:**
[ConnectionABCDCollection](../../com.aspose.diagram/connectionabcdcollection)
### getConnections() {#getConnections--}
```
public ConnectionCollection getConnections()
```


يحتوي على مجموعة من عناصر Connection.

**Returns:**
[ConnectionCollection](../../com.aspose.diagram/connectioncollection)
### getConnectorRule() {#getConnectorRule--}
```
public ConnectorRule getConnectorRule()
```


يرجع connectorRule يحتوي على معرف الشكل والاتصال المتصل بالشكل.

**Returns:**
[ConnectorRule](../../com.aspose.diagram/connectorrule) - ConnectorRule.
### getConnectorsType() {#getConnectorsType--}
```
public int getConnectorsType()
```


احصل على نوع الموصلات

**Returns:**
int
### getControlData() {#getControlData--}
```
public byte[] getControlData()
```


يحصل على بيانات التحكم.

**Returns:**
byte[]
### getControls() {#getControls--}
```
public ControlCollection getControls()
```


يحتوي على مجموعة من عناصر Control.

**Returns:**
[ControlCollection](../../com.aspose.diagram/controlcollection)
### getData1() {#getData1--}
```
public String getData1()
```


يحتوي على قيمة نصية عشوائية تُستخدم لتوفير معلومات إضافية حول الشكل.

**Returns:**
java.lang.String
### getData2() {#getData2--}
```
public String getData2()
```


يحتوي على قيمة نصية عشوائية تُستخدم لتوفير معلومات إضافية حول الشكل.

**Returns:**
java.lang.String
### getData3() {#getData3--}
```
public String getData3()
```


يحتوي على قيمة نصية عشوائية تُستخدم لتوفير معلومات إضافية حول الشكل.

**Returns:**
java.lang.String
### getDel() {#getDel--}
```
public int getDel()
```


علامة تشير إلى ما إذا كان العنصر محذوفًا محليًا. القيمة 1 تشير إلى أن العنصر محذوف محليًا.

**Returns:**
int
### getDiagram() {#getDiagram--}
```
public Diagram getDiagram()
```


العنصر الجذر لهرمية كائنات Visio.

**Returns:**
[Diagram](../../com.aspose.diagram/diagram)
### getDisplayText() {#getDisplayText--}
```
public String getDisplayText()
```


احصل على النص المعروض في الواجهة

**Returns:**
java.lang.String
### getEvent() {#getEvent--}
```
public Event getEvent()
```


يحتوي على عناصر تحدد الصيغ التي تتحكم في أحداث الشكل.

**Returns:**
[Event](../../com.aspose.diagram/event)
### getFields() {#getFields--}
```
public FieldCollection getFields()
```


يحتوي على مجموعة من عناصر Field.

**Returns:**
[FieldCollection](../../com.aspose.diagram/fieldcollection)
### getFill() {#getFill--}
```
public Fill getFill()
```


يحتوي على قيم تنسيق التعبئة الحالية للشكل وظل الشكل المنسدل، بما في ذلك النمط، لون المقدمة، ولون الخلفية.

**Returns:**
[Fill](../../com.aspose.diagram/fill)
### getFillStyle() {#getFillStyle--}
```
public StyleSheet getFillStyle()
```


ورقة الأنماط التي يرث منها هذا الشكل تنسيق التعبئة.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getForeign() {#getForeign--}
```
public Foreign getForeign()
```


يحتوي على عناصر تحدد العرض والارتفاع لكائن من برنامج آخر يُستخدم في مستند Microsoft Visio. كما يتضمن عناصر تحدد المسافة التي يُزاح فيها صورة الكائن داخل حدوده.

**Returns:**
[Foreign](../../com.aspose.diagram/foreign)
### getForeignData() {#getForeignData--}
```
public ForeignData getForeignData()
```


يحتوي على BLOB مشفر بتنسيق MIME (Multipurpose Internet Mail Extensions) لبيانات الصورة، مثل ملف ميتافايل Windows أو bitmap أو بيانات OLE.

**Returns:**
[ForeignData](../../com.aspose.diagram/foreigndata)
### getGeoms() {#getGeoms--}
```
public GeomCollection getGeoms()
```


يحتوي على مجموعة من عناصر Geom.

**Returns:**
[GeomCollection](../../com.aspose.diagram/geomcollection)
### getGroup() {#getGroup--}
```
public Group getGroup()
```


يحتوي على عناصر تتحكم في كيفية إضافة الأشكال إلى مجموعة، نقل أعضاء المجموعة، واختيار المجموعات.

**Returns:**
[Group](../../com.aspose.diagram/group)
### getHelp() {#getHelp--}
```
public Help getHelp()
```


يحتوي على عناصر تحدد موضوع ملف المساعدة لعنصر Shape ومعلومات حقوق النشر.

**Returns:**
[Help](../../com.aspose.diagram/help)
### getHyperlinks() {#getHyperlinks--}
```
public HyperlinkCollection getHyperlinks()
```


يحتوي على مجموعة من عناصر Hyperlink.

**Returns:**
[HyperlinkCollection](../../com.aspose.diagram/hyperlinkcollection)
### getID() {#getID--}
```
public long getID()
```


المعرّف الفريد للعنصر داخل العنصر الأب.

**Returns:**
long
### getImage() {#getImage--}
```
public Image getImage()
```


يحتوي على قيم الجاما، السطوع، التباين، الضبابية، الشحذ، إزالة الضوضاء، والشفافية لملف bitmap.

**Returns:**
[Image](../../com.aspose.diagram/image)
### getInheritChars() {#getInheritChars--}
```
public CharCollection getInheritChars()
```


يحتوي على قيم الأحرف التي يرثها الشكل من الشكل الرئيسي.

**Returns:**
[CharCollection](../../com.aspose.diagram/charcollection)
### getInheritFill() {#getInheritFill--}
```
public Fill getInheritFill()
```


يحتوي على قيم تنسيق التعبئة التي يرثها الشكل من النمط الأب والشكل الرئيسي.

**Returns:**
[Fill](../../com.aspose.diagram/fill)
### getInheritGeoms() {#getInheritGeoms--}
```
public GeomCollection getInheritGeoms()
```


يحتوي على قيم Geoms للشكل الموروث من الشكل الرئيسي.

**Returns:**
[GeomCollection](../../com.aspose.diagram/geomcollection)
### getInheritLine() {#getInheritLine--}
```
public Line getInheritLine()
```


يحتوي على قيم تنسيق الخط للشكل الموروث من نمط الوالد والشكل الرئيسي.

**Returns:**
[Line](../../com.aspose.diagram/line)
### getInheritParas() {#getInheritParas--}
```
public ParaCollection getInheritParas()
```


يحتوي على الـ paras للشكل الموروث من نمط الوالد والشكل الرئيسي.

**Returns:**
[ParaCollection](../../com.aspose.diagram/paracollection)
### getInheritProps() {#getInheritProps--}
```
public PropCollection getInheritProps()
```


يحتوي على الـ props للشكل الموروث من الشكل الرئيسي.

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getInheritTextBlock() {#getInheritTextBlock--}
```
public TextBlock getInheritTextBlock()
```


يحتوي على قيم textblock للشكل الموروث من نمط الوالد والشكل الرئيسي.

**Returns:**
[TextBlock](../../com.aspose.diagram/textblock)
### getInheritUsers() {#getInheritUsers--}
```
public UserCollection getInheritUsers()
```


يحتوي على الـ users للشكل الموروث من الشكل الرئيسي.

**Returns:**
[UserCollection](../../com.aspose.diagram/usercollection)
### getLayerMem() {#getLayerMem--}
```
public LayerMem getLayerMem()
```


يحتوي على عنصر LayerMember، الذي يحدد كل طبقة يُعيّن إليها الشكل.

**Returns:**
[LayerMem](../../com.aspose.diagram/layermem)
### getLayout() {#getLayout--}
```
public Layout getLayout()
```


يحتوي على عناصر تتحكم في وضع الشكل وإعدادات توجيه الموصلات.

**Returns:**
[Layout](../../com.aspose.diagram/layout)
### getLine() {#getLine--}
```
public Line getLine()
```


يحتوي على عناصر تتحكم في خصائص الخط للشكل، مثل النمط والوزن واللون. تحدد هذه العناصر ما إذا كانت نهايات الخط مُنسقة (على سبيل المثال، بسهم)، حجم تنسيقات نهايات الخط، نصف قطر الدائرة المستديرة المطبقة على الخط، ونمط غطاء الخط (دائري أو مربع).

**Returns:**
[Line](../../com.aspose.diagram/line)
### getLineStyle() {#getLineStyle--}
```
public StyleSheet getLineStyle()
```


ورقة الأنماط التي يرث منها هذا الشكل تنسيق الخط

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getMaster() {#getMaster--}
```
public Master getMaster()
```


الماستر الذي يرث منه الشكل بياناته.

**Returns:**
[Master](../../com.aspose.diagram/master)
### getMasterShape() {#getMasterShape--}
```
public Shape getMasterShape()
```


قد يكون هذا السمة موجودًا فقط في الأشكال التي هي أعضاء في group shape، وتكون المجموعة نسخة من master. يحتوي السمة على معرف يشير إلى الشكل الفرعي المقابل في الـ master.

**Returns:**
[Shape](../../com.aspose.diagram/shape)
### getMisc() {#getMisc--}
```
public Misc getMisc()
```


يحتوي على عناصر تحدد موضوع ملف المساعدة لعنصر Shape ومعلومات حقوق النشر.

**Returns:**
[Misc](../../com.aspose.diagram/misc)
### getName() {#getName--}
```
public String getName()
```


اسم العنصر.

**Returns:**
java.lang.String
### getNameU() {#getNameU--}
```
public String getNameU()
```


الاسم العام للعنصر.

**Returns:**
java.lang.String
### getOneD() {#getOneD--}
```
public boolean getOneD()
```


يحدد ما إذا كان الشكل يتصرف ككائن أحادي البعد (1-D). للقراءة فقط.

**Returns:**
منطقي
### getPage() {#getPage--}
```
public Page getPage()
```


العنصر الجذر لهرمية كائنات Visio.

**Returns:**
[Page](../../com.aspose.diagram/page)
### getParas() {#getParas--}
```
public ParaCollection getParas()
```


يحتوي على مجموعة من عناصر Para.

**Returns:**
[ParaCollection](../../com.aspose.diagram/paracollection)
### getParentShape() {#getParentShape--}
```
public Shape getParentShape()
```


الوالد الخاص بالشكل.

**Returns:**
[Shape](../../com.aspose.diagram/shape)
### getProps() {#getProps--}
```
public PropCollection getProps()
```


يحتوي على مجموعة من عناصر Prop.

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getProtection() {#getProtection--}
```
public Protection getProtection()
```


يساعد القفل في منع التغييرات غير المقصودة على الشكل لكنه لا يمنع Microsoft Visio من إعادة تعيين القيم في ظروف أخرى. كما أنه لا يحمي من التغييرات التي تُجرى في نافذة ShapeSheet.

**Returns:**
[Protection](../../com.aspose.diagram/protection)
### getPureText() {#getPureText--}
```
public String getPureText()
```


احصل على سلسلة النص

**Returns:**
java.lang.String
### getRootShape() {#getRootShape--}
```
public Shape getRootShape()
```


يرجع الشكل الأعلى مستوىً في نسخة إذا كان هذا الشكل جزءًا من نسخة master. للقراءة فقط.

**Returns:**
[Shape](../../com.aspose.diagram/shape)
### getScratchs() {#getScratchs--}
```
public ScratchCollection getScratchs()
```


يحتوي على مجموعة من عناصر Scratch.

**Returns:**
[ScratchCollection](../../com.aspose.diagram/scratchcollection)
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


يحتوي على مجموعة من عناصر Shape.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getSmartTagDefs() {#getSmartTagDefs--}
```
public SmartTagDefCollection getSmartTagDefs()
```


يحتوي على مجموعة من عناصر SmartTagDef.

**Returns:**
[SmartTagDefCollection](../../com.aspose.diagram/smarttagdefcollection)
### getTabsCollection() {#getTabsCollection--}
```
public TabsCollection getTabsCollection()
```


يحتوي على مجموعة من عناصر التبويب.

**Returns:**
[TabsCollection](../../com.aspose.diagram/tabscollection)
### getText() {#getText--}
```
public Text getText()
```


يحتوي على نص الشكل.

**Returns:**
[Text](../../com.aspose.diagram/text)
### getTextBlock() {#getTextBlock--}
```
public TextBlock getTextBlock()
```


يحتوي على عناصر تحدد محاذاة وهوامش ومواقع إيقاف التبويب الافتراضية للنص في كتلة النص الخاصة بالشكل.

**Returns:**
[TextBlock](../../com.aspose.diagram/textblock)
### getTextStyle() {#getTextStyle--}
```
public StyleSheet getTextStyle()
```


ورقة الأنماط التي يرث منها هذا الشكل تنسيق النص.

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getTextXForm() {#getTextXForm--}
```
public TextXForm getTextXForm()
```


يحتوي على عناصر تحدد معلومات التموضع حول كتلة النص الخاصة بالشكل.

**Returns:**
[TextXForm](../../com.aspose.diagram/textxform)
### getThreeDFormat() {#getThreeDFormat--}
```
public ThreeDFormat getThreeDFormat()
```


يحصل على ThreeDFormat.

**Returns:**
[ThreeDFormat](../../com.aspose.diagram/threedformat)
### getTwoD() {#getTwoD--}
```
public boolean getTwoD()
```


يحدد ما إذا كان الشكل يتصرف ككائن ثنائي الأبعاد (2-D).

**Returns:**
منطقي
### getType() {#getType--}
```
public int getType()
```


نوع الشكل. قد يكون أحد القيم التالية: Group, Shape, Guide, أو Foreign.

**Returns:**
int
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


معرف GUID (معرف فريد عالميًا) مخصص للشكل.

**Returns:**
java.util.UUID
### getUsers() {#getUsers--}
```
public UserCollection getUsers()
```


يحتوي على مجموعة من عناصر User.

**Returns:**
[UserCollection](../../com.aspose.diagram/usercollection)
### getXForm() {#getXForm--}
```
public XForm getXForm()
```


يحتوي على عناصر تحدد معلومات التموضع العامة حول الشكل.

**Returns:**
[XForm](../../com.aspose.diagram/xform)
### getXForm1D() {#getXForm1D--}
```
public XForm1D getXForm1D()
```


يحتوي على إحداثيات x و y لنقطة البداية ونقطة النهاية لشكل أحادي البعد. يظهر هذا العنصر للأشكال أحادية البعد فقط.

**Returns:**
[XForm1D](../../com.aspose.diagram/xform1d)
### getZOrderIndex() {#getZOrderIndex--}
```
public int getZOrderIndex()
```


يعيد فهرس الشكل في ترتيب z باستثناء شكل الدليل.

**Returns:**
int
### gluedShapes(int flag, String categoryFilter, Shape otherShape) {#gluedShapes-int-java.lang.String-com.aspose.diagram.Shape-}
```
public long[] gluedShapes(int flag, String categoryFilter, Shape otherShape)
```


يعيد مصفوفة تحتوي على معرفات الأشكال الملصوقة على شكل ما.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| علامة | int | الأبعاد والاتجاهية لنقاط الاتصال للأشكال التي سيتم إرجاعها. راجع الملاحظات للقيم المحتملة في Aspose.Diagram.GluedShapesFlags. |
| categoryFilter | java.lang.String | يقوم بتصفية مصفوفة معرفات الأشكال المرتجعة عن طريق حصرها على المعرفات للأشكال التي تطابق categoryString المحدد. |
| otherShape | [Shape](../../com.aspose.diagram/shape) | اختياري: شكل إضافي يجب أن تُلصق إليه الأشكال المرتجعة أيضًا، يمكن أن يكون [Shape](../../com.aspose.diagram/shape) أو null. |

**Returns:**
long[] - مصفوفة معرفات.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isConnected(Shape shape) {#isConnected-com.aspose.diagram.Shape-}
```
public boolean isConnected(Shape shape)
```


يشير إلى ما إذا كان هذان الشكلان متصلان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) | shape |

**Returns:**
منطقي
### isContain(Shape shape) {#isContain-com.aspose.diagram.Shape-}
```
public boolean isContain(Shape shape)
```


يشير إلى ما إذا كان هذا الشكل يحتوي على شكل آخر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) |  |

**Returns:**
منطقي
### isGlued(Shape shape) {#isGlued-com.aspose.diagram.Shape-}
```
public boolean isGlued(Shape shape)
```


يشير إلى ما إذا كان هذان الشكلان ملصوقان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) | shape |

**Returns:**
منطقي
### isInGroup() {#isInGroup--}
```
public boolean isInGroup()
```


يشير إلى ما إذا كان هذا الشكل داخل مجموعة أشكال.

**Returns:**
منطقي
### isIntersect(Shape shape) {#isIntersect-com.aspose.diagram.Shape-}
```
public boolean isIntersect(Shape shape)
```


يشير إلى ما إذا كان هذا الشكل يتقاطع مع شكل آخر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) |  |

**Returns:**
منطقي
### isTextEmpty() {#isTextEmpty--}
```
public boolean isTextEmpty()
```


يشير إلى أن الشكل يحتوي على نص وما إذا كان النص فارغًا أم لا.

**Returns:**
منطقي
### move(double dX, double dY) {#move-double-double-}
```
public void move(double dX, double dY)
```


ينقل الشكل بمقدار dX و dY بوصة من الموقع الحالي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dX | double | إزاحة X double. |
| dY | double | إزاحة Y double. |

### moveTo(double newPinX, double newPinY) {#moveTo-double-double-}
```
public void moveTo(double newPinX, double newPinY)
```


ينقل الشكل إلى موقع مطلق جديد على الصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newPinX | double | الإحداثي X الجديد لدبوس الشكل (مركز الدوران) بالنسبة لأصل العنصر الأب. double. |
| newPinY | double | الإحداثي Y الجديد لدبوس الشكل (مركز الدوران) بالنسبة لأصل العنصر الأب. double. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### refreshData() {#refreshData--}
```
public void refreshData()
```


يقوم بتحديث موضع الشكل بما في ذلك xform والاتصال والجيوم عند تغيير نص الشكل أو غيره. سنجمع بيانات الشكل مثل نص الشكل ثم نحسب موضع الشكل. تُستخدم هذه الطريقة فقط لتحديث بيانات الشكل.

### replaceText(String text, String replaceText) {#replaceText-java.lang.String-java.lang.String-}
```
public void replaceText(String text, String replaceText)
```


استبدل سلسلة النص الخاصة بالشكل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| text | java.lang.String |  |
| replaceText | java.lang.String |  |

### sendBackward() {#sendBackward--}
```
public void sendBackward()
```


ينقل الشكل خطوة واحدة إلى الخلف في ترتيب z.

### sendToBack() {#sendToBack--}
```
public void sendToBack()
```


ينقل الشكل إلى الخلف في ترتيب z.

### setAngle(double angle) {#setAngle-double-}
```
public void setAngle(double angle)
```


يضبط الزاوية الجديدة للشكل. وحدة الزاوية هي الراديان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| angle | double | زاوية جديدة وحدة قياسها راديان ليست درجة double. |

### setClippingPath(String value) {#setClippingPath-java.lang.String-}
```
public void setClippingPath(String value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getClippingPath()](../../com.aspose.diagram/shape\#getClippingPath--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### setConnectorsType(int type) {#setConnectorsType-int-}
```
public void setConnectorsType(int type)
```


تعيين نوع الموصلات

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| النوع | int |  |

### setData1(String value) {#setData1-java.lang.String-}
```
public void setData1(String value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getData1()](../../com.aspose.diagram/shape\#getData1--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### setData2(String value) {#setData2-java.lang.String-}
```
public void setData2(String value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getData2()](../../com.aspose.diagram/shape\#getData2--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### setData3(String value) {#setData3-java.lang.String-}
```
public void setData3(String value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getData3()](../../com.aspose.diagram/shape\#getData3--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getDel()](../../com.aspose.diagram/shape\#getDel--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setDiagram(Diagram value) {#setDiagram-com.aspose.diagram.Diagram-}
```
public void setDiagram(Diagram value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getDiagram()](../../com.aspose.diagram/shape\#getDiagram--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Diagram](../../com.aspose.diagram/diagram) |  |

### setEvent(Event value) {#setEvent-com.aspose.diagram.Event-}
```
public void setEvent(Event value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getEvent()](../../com.aspose.diagram/shape\#getEvent--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Event](../../com.aspose.diagram/event) |  |

### setFillStyle(StyleSheet value) {#setFillStyle-com.aspose.diagram.StyleSheet-}
```
public void setFillStyle(StyleSheet value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getFillStyle()](../../com.aspose.diagram/shape\#getFillStyle--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setHeight(double height) {#setHeight-double-}
```
public void setHeight(double height)
```


يضبط ارتفاعًا جديدًا للشكل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| height | double | جديد heightdouble. |

### setID(long value) {#setID-long-}
```
public void setID(long value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getID()](../../com.aspose.diagram/shape\#getID--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | long |  |

### setLineStyle(StyleSheet value) {#setLineStyle-com.aspose.diagram.StyleSheet-}
```
public void setLineStyle(StyleSheet value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getLineStyle()](../../com.aspose.diagram/shape\#getLineStyle--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setMaster(Master value) {#setMaster-com.aspose.diagram.Master-}
```
public void setMaster(Master value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getMaster()](../../com.aspose.diagram/shape\#getMaster--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Master](../../com.aspose.diagram/master) |  |

### setMasterShape(Shape value) {#setMasterShape-com.aspose.diagram.Shape-}
```
public void setMasterShape(Shape value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getMasterShape()](../../com.aspose.diagram/shape\#getMasterShape--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Shape](../../com.aspose.diagram/shape) |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getName()](../../com.aspose.diagram/shape\#getName--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


لوصف هذه الخاصية، يرجى الاطلاع على [getNameU()](../../com.aspose.diagram/shape\#getNameU--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### setPage(Page value) {#setPage-com.aspose.diagram.Page-}
```
public void setPage(Page value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getPage()](../../com.aspose.diagram/shape\#getPage--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setParentShape(Shape value) {#setParentShape-com.aspose.diagram.Shape-}
```
public void setParentShape(Shape value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getParentShape()](../../com.aspose.diagram/shape\#getParentShape--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Shape](../../com.aspose.diagram/shape) |  |

### setPresetTheme(int value) {#setPresetTheme-int-}
```
public void setPresetTheme(int value)
```


تطبيق سمة مسبقة على هذا الشكل

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setPresetThemeQuickStyle(int value) {#setPresetThemeQuickStyle-int-}
```
public void setPresetThemeQuickStyle(int value)
```


تطبيق نمط سريع لتغيير نسخة سمة مسبقة على هذا الشكل

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setPresetThemeStyleMatrics(int styleIndex, int colorIndex) {#setPresetThemeStyleMatrics-int-int-}
```
public void setPresetThemeStyleMatrics(int styleIndex, int colorIndex)
```


تطبيق نمط سريع لتغيير نسخة سمة مسبقة على هذا الشكل، مثل خيارات أنماط السمة في قائمة أنماط الشكل المنسدلة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| styleIndex | int | صف مصفوفة النمط |
| colorIndex | int | عمود مصفوفة النمط |

### setPresetThemeVariant(int value) {#setPresetThemeVariant-int-}
```
public void setPresetThemeVariant(int value)
```


تطبيق نسخة سمة مسبقة على هذا الشكل

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setProps(PropCollection value) {#setProps-com.aspose.diagram.PropCollection-}
```
public void setProps(PropCollection value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getProps()](../../com.aspose.diagram/shape\#getProps--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PropCollection](../../com.aspose.diagram/propcollection) |  |

### setText(Text value) {#setText-com.aspose.diagram.Text-}
```
public void setText(Text value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getText()](../../com.aspose.diagram/shape\#getText--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Text](../../com.aspose.diagram/text) |  |

### setTextStyle(StyleSheet value) {#setTextStyle-com.aspose.diagram.StyleSheet-}
```
public void setTextStyle(StyleSheet value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getTextStyle()](../../com.aspose.diagram/shape\#getTextStyle--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setTwoD(boolean value) {#setTwoD-boolean-}
```
public void setTwoD(boolean value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getTwoD()](../../com.aspose.diagram/shape\#getTwoD--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | منطقي |  |

### setType(int value) {#setType-int-}
```
public void setType(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getType()](../../com.aspose.diagram/shape\#getType--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getUniqueID()](../../com.aspose.diagram/shape\#getUniqueID--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.util.UUID |  |

### setWidth(double width) {#setWidth-double-}
```
public void setWidth(double width)
```


تعيين عرض جديد للشكل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| width | double | جديد widthdouble. |

### setXForm(XForm value) {#setXForm-com.aspose.diagram.XForm-}
```
public void setXForm(XForm value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getXForm()](../../com.aspose.diagram/shape\#getXForm--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [XForm](../../com.aspose.diagram/xform) |  |

### setXForm1D(XForm1D value) {#setXForm1D-com.aspose.diagram.XForm1D-}
```
public void setXForm1D(XForm1D value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getXForm1D()](../../com.aspose.diagram/shape\#getXForm1D--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [XForm1D](../../com.aspose.diagram/xform1d) |  |

### toHTML(InputStream stream, HTMLSaveOptions options) {#toHTML-java.io.InputStream-com.aspose.diagram.HTMLSaveOptions-}
```
public void toHTML(InputStream stream, HTMLSaveOptions options)
```


إنشاء HTML للشكل وحفظه إلى تدفق بالصيغة المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | java.io.InputStream | دفق الإخراج. |
| options | [HTMLSaveOptions](../../com.aspose.diagram/htmlsaveoptions) | خيارات إنشاء html الإضافية |

### toHTML(OutputStream stream, HTMLSaveOptions options) {#toHTML-java.io.OutputStream-com.aspose.diagram.HTMLSaveOptions-}
```
public void toHTML(OutputStream stream, HTMLSaveOptions options)
```


إنشاء HTML للشكل وحفظه إلى تدفق بالصيغة المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | java.io.OutputStream | دفق الإخراج. |
| options | [HTMLSaveOptions](../../com.aspose.diagram/htmlsaveoptions) | خيارات إنشاء html الإضافية |

### toHTML(String fileName, HTMLSaveOptions options) {#toHTML-java.lang.String-com.aspose.diagram.HTMLSaveOptions-}
```
public void toHTML(String fileName, HTMLSaveOptions options)
```


إنشاء HTML وحفظه إلى ملف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileName | java.lang.String |  |
| options | [HTMLSaveOptions](../../com.aspose.diagram/htmlsaveoptions) | خيارات حفظ html |

### toImage(InputStream stream, ImageSaveOptions options) {#toImage-java.io.InputStream-com.aspose.diagram.ImageSaveOptions-}
```
public void toImage(InputStream stream, ImageSaveOptions options)
```


إنشاء صورة الشكل وحفظها إلى تدفق بالصيغة المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | java.io.InputStream | دفق الإخراج. |
| options | [ImageSaveOptions](../../com.aspose.diagram/imagesaveoptions) | خيارات إنشاء الصورة الإضافية |

### toImage(OutputStream stream, ImageSaveOptions options) {#toImage-java.io.OutputStream-com.aspose.diagram.ImageSaveOptions-}
```
public void toImage(OutputStream stream, ImageSaveOptions options)
```


إنشاء صورة الشكل وحفظها إلى تدفق بالصيغة المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | java.io.OutputStream | دفق الإخراج. |
| options | [ImageSaveOptions](../../com.aspose.diagram/imagesaveoptions) | خيارات إنشاء الصورة الإضافية |

### toImage(String imageFile, ImageSaveOptions options) {#toImage-java.lang.String-com.aspose.diagram.ImageSaveOptions-}
```
public void toImage(String imageFile, ImageSaveOptions options)
```


ينشئ صورة الشكل ويحفظها في ملف. تحدد امتداد اسم الملف تنسيق الصورة.

يتم تحديد تنسيق الصورة باستخدام امتداد اسم الملف. على سبيل المثال، إذا حددت "myfile.png"، فسيتم حفظ الصورة بتنسيق PNG. يتم التعرف على امتدادات الملفات التالية: .bmp, .gif, .png, .jpg, .jpeg, .tiff, .tif, .emf.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| imageFile | java.lang.String | اسم ملف الصورة مع المسار الكامل. |
| options | [ImageSaveOptions](../../com.aspose.diagram/imagesaveoptions) | خيارات إنشاء الصورة الإضافية |

### toPdf(InputStream stream) {#toPdf-java.io.InputStream-}
```
public void toPdf(InputStream stream)
```


إنشاء ملف PDF للشكل وحفظه إلى تدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | java.io.InputStream | دفق الإخراج. |

### toPdf(OutputStream stream) {#toPdf-java.io.OutputStream-}
```
public void toPdf(OutputStream stream)
```


إنشاء ملف PDF للشكل وحفظه إلى تدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | java.io.OutputStream | دفق الإخراج. |

### toPdf(String fileName) {#toPdf-java.lang.String-}
```
public void toPdf(String fileName)
```


حفظ الشكل إلى ملف PDF.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileName | java.lang.String | اسم ملف pdf مع المسار الكامل |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### toSvg(String imageFile, SVGSaveOptions options) {#toSvg-java.lang.String-com.aspose.diagram.SVGSaveOptions-}
```
public void toSvg(String imageFile, SVGSaveOptions options)
```


حفظ الشكل إلى ملف SVG.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| imageFile | java.lang.String |  |
| options | [SVGSaveOptions](../../com.aspose.diagram/svgsaveoptions) |  |

### ungroup() {#ungroup--}
```
public void ungroup()
```


فك تجميع الشكل

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

