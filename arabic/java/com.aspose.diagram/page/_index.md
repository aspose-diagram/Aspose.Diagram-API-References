---
title: صفحة
second_title: Aspose.Diagram لـ Java API Reference
description: يحتوي على عناصر تُعرّف صفحة في المستند.
type: docs
weight: 260
url: /ar/java/com.aspose.diagram/page/
---

**Inheritance:**
java.lang.Object
```
public class Page
```

يحتوي على عناصر تُعرّف صفحة في المستند.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Page()](#Page--) | منشئ. |
| [Page(int ID)](#Page-int-) | منشئ. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [addActiveXControl(int type, double pinX, double pinY, double width, double height)](#addActiveXControl-int-double-double-double-double-) | ينشئ عنصر تحكم Activex. |
| [addComment(Shape shape, String comment)](#addComment-com.aspose.diagram.Shape-java.lang.String-) | يضيف تعليقًا إلى شكل. |
| [addComment(double pinX, double pinY, String comment)](#addComment-double-double-java.lang.String-) | يضيف تعليقًا مع PinX و PinY المحددين. |
| [addComment(long shapeID, String comment)](#addComment-long-java.lang.String-) | يضيف تعليقًا إلى شكل باستخدام معرف الشكل. |
| [addShape(Shape newShape, String masterName)](#addShape-com.aspose.diagram.Shape-java.lang.String-) | يضيف شكلًا تم إنشاؤه بواسطة القالب إلى صفحة محددة. |
| [addShape(double pinX, double pinY, double width, double height, InputStream stream)](#addShape-double-double-double-double-java.io.InputStream-) |  |
| [addShape(double pinX, double pinY, double width, double height, InputStream imageStream, InputStream objectDataStream)](#addShape-double-double-double-double-java.io.InputStream-java.io.InputStream-) |  |
| [addShape(double pinX, double pinY, double width, double height, String masterName)](#addShape-double-double-double-double-java.lang.String-) | يضيف شكلًا تم إنشاؤه بواسطة القالب على الصفحة مع PinX و PinY والعرض والارتفاع المحددين. |
| [addShape(double pinX, double pinY, String masterName)](#addShape-double-double-java.lang.String-) | يضيف شكلًا تم إنشاؤه بواسطة القالب على الصفحة مع PinX و PinY المحددين. |
| [addText(double pinX, double pinY, double width, double height, String text)](#addText-double-double-double-double-java.lang.String-) | يضيف نصًا مع PinX و PinY المحددين. |
| [addText(double pinX, double pinY, double width, double height, String text, String fontName, String fontColor, double size)](#addText-double-double-double-double-java.lang.String-java.lang.String-java.lang.String-double-) | يضيف نصًا مع PinX و PinY المحددين. |
| [applyStyle(int textStyle, int lineStyle, int fillStyle)](#applyStyle-int-int-int-) | يطبق النمط على الصفحة الكاملة. |
| [autoSpaceShapes(ShapeCollection shapes, AutoSpaceOptions options)](#autoSpaceShapes-com.aspose.diagram.ShapeCollection-com.aspose.diagram.AutoSpaceOptions-) | توزيع تلقائي للأشكال |
| [bringForward(long shapeId)](#bringForward-long-) | ينقل شكلًا، معرفًا بالمعرف ID، خطوة واحدة إلى الأمام في ترتيب Z. |
| [bringToFront(long shapeId)](#bringToFront-long-) | ينقل شكلًا، معرفًا بالمعرف ID، إلى مقدمة ترتيب Z. |
| [centerDrawing()](#centerDrawing--) | يتمركز أشكال الصفحة بالنسبة إلى امتداد الصفحة. |
| [connectShapesViaConnector(Shape shapeFrom, int placeFrom, Shape shapeTo, int placeTo, Shape connector)](#connectShapesViaConnector-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-) | ربط الأشكال عبر الموصل. |
| [connectShapesViaConnector(long shapeFromId, int placeFrom, long shapeToId, int placeTo, long connectorId)](#connectShapesViaConnector-long-int-long-int-long-) | ربط الأشكال عبر الموصل. |
| [connectShapesViaConnector(long shapeFromId, String fromConnectionName, long shapeToId, String toConnectionName, long connectorId)](#connectShapesViaConnector-long-java.lang.String-long-java.lang.String-long-) | ربط الأشكال عبر الموصل. |
| [connectShapesViaConnectorIndex(Shape shapeFrom, int fromIndex, Shape shapeTo, int toIndex, Shape connector)](#connectShapesViaConnectorIndex-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-) | ربط الأشكال عبر فهرس الموصل. |
| [connectShapesViaConnectorIndex(long shapeFromId, int fromIndex, long shapeToId, int toIndex, long connectorId)](#connectShapesViaConnectorIndex-long-int-long-int-long-) | ربط الأشكال عبر فهرس الموصل. |
| [copy(Page source)](#copy-com.aspose.diagram.Page-) |  |
| [dispose()](#dispose--) | ينفّذ مهامًا محددة من قبل التطبيق مرتبطة بتحرير أو إطلاق أو إعادة ضبط الموارد غير المُدارة. |
| [drawEllipse(double pinX, double pinY, double width, double height)](#drawEllipse-double-double-double-double-) | عملية رسم الشكل البيضاوي. |
| [drawLine(double beginX, double beginY, double endX, double endY)](#drawLine-double-double-double-double-) | عملية رسم خط واحد. |
| [drawLine(double pinX, double pinY, double width, double height, double[] xyArray)](#drawLine-double-double-double-double-double---) | عملية رسم الخط. |
| [drawPolyline(double pinX, double pinY, double width, double height, double[] xyArray)](#drawPolyline-double-double-double-double-double---) | عملية رسم الخط المتعدد. |
| [drawRectangle(double pinX, double pinY, double width, double height)](#drawRectangle-double-double-double-double-) | عملية رسم المستطيل. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAssociatedPage()](#getAssociatedPage--) | معرّف الصفحة الأصلية للرسم التي تم وضع علامات عليها في طبقات علامات منفصلة من قبل مراجعّي الرسم. |
| [getBackPage()](#getBackPage--) | صفحة الخلفية للصفحة. |
| [getBackground()](#getBackground--) | علامة تشير إلى ما إذا كانت الصفحة صفحة خلفية. |
| [getClass()](#getClass--) |  |
| [getConnects()](#getConnects--) | يحتوي على عنصر Connect لكل اتصال بين شكلين في الرسم. |
| [getID()](#getID--) | المعرّف الفريد للعنصر داخل العنصر الأب. |
| [getName()](#getName--) | اسم العنصر. |
| [getNameU()](#getNameU--) | الاسم العام للعنصر. |
| [getPageSheet()](#getPageSheet--) | يحتوي على عناصر تُعرّف ورقة الصفحة لعنصر صفحة أو عنصر رئيسي. |
| [getPages()](#getPages--) | مجموعة الصفحات. |
| [getReviewerID()](#getReviewerID--) | معرّف المراجع المرتبط بطبقة العلامات. |
| [getShapes()](#getShapes--) | مجموعة الأشكال. |
| [getViewCenterX()](#getViewCenterX--) | تحدد ViewCenterX و ViewCenterY نقطة مركزية على الصفحة يتبناها العرض (النافذة) الجديد عند فتحه مبدئياً. |
| [getViewCenterY()](#getViewCenterY--) | تحدد ViewCenterX و ViewCenterY نقطة مركزية على الصفحة يتبناها العرض (النافذة) الجديد عند فتحه مبدئياً. |
| [getViewScale()](#getViewScale--) | عامل التكبير الافتراضي لاستخدامه عند فتح عرض (نافذة) جديد للصفحة. |
| [glueShapeToConnectorBeginX(long shapeFromId, String connectionName, long connectorId)](#glueShapeToConnectorBeginX-long-java.lang.String-long-) | ربط الشكل بـ Connector's BeginX |
| [glueShapeToConnectorEndX(long shapeToId, String connectionName, long connectorId)](#glueShapeToConnectorEndX-long-java.lang.String-long-) | ربط الشكل بـ Connector's EndX |
| [glueShapes(Shape shapeFrom, int placeTo, Shape shapeTo)](#glueShapes-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-) | ربط الأشكال. |
| [glueShapes(long shapeFromId, int placeTo, long shapeToId)](#glueShapes-long-int-long-) | ربط الأشكال |
| [glueShapesInContainer(long shapeFromId, int shapeToBeginConnectionIndex, int shapeToEndConnectionIndex, long shapeToId)](#glueShapesInContainer-long-int-int-long-) | ربط الأشكال في الحاوية |
| [glueShapesInContainer(long shapeFromId, String shapeToBeginConnectionName, String shapeToEndConnectionName, long shapeToId)](#glueShapesInContainer-long-java.lang.String-java.lang.String-long-) | ربط الأشكال في الحاوية باستخدام اسم الاتصال |
| [glueShapesInContainerByID(long shapeFromId, int shapeToBeginConnectionID, int shapeToEndConnectionID, long shapeToId)](#glueShapesInContainerByID-long-int-int-long-) | ربط الأشكال بواسطة معرّف الاتصال في الحاوية |
| [hashCode()](#hashCode--) |  |
| [layout(LayoutOptions options)](#layout-com.aspose.diagram.LayoutOptions-) | ينظم الأشكال و/أو يعيد توجيه الموصلات للصفحة. |
| [moveTo(int index)](#moveTo-int-) | ينقل الصفحة إلى موقع آخر بين الصفحات. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [sendBackward(long shapeId)](#sendBackward-long-) | ينقل شكلًا، معرفًا بالمعرّف، خطوة واحدة إلى الخلف في ترتيب Z. |
| [sendToBack(long shapeId)](#sendToBack-long-) | ينقل شكلًا، معرفًا بالمعرّف، إلى مؤخرة ترتيب Z. |
| [setAssociatedPage(Page value)](#setAssociatedPage-com.aspose.diagram.Page-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getAssociatedPage()](../../com.aspose.diagram/page\#getAssociatedPage--) |
| [setBackPage(Page value)](#setBackPage-com.aspose.diagram.Page-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getBackPage()](../../com.aspose.diagram/page\#getBackPage--) |
| [setBackground(int value)](#setBackground-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getBackground()](../../com.aspose.diagram/page\#getBackground--) |
| [setID(int value)](#setID-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getID()](../../com.aspose.diagram/page\#getID--) |
| [setName(String value)](#setName-java.lang.String-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getName()](../../com.aspose.diagram/page\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getNameU()](../../com.aspose.diagram/page\#getNameU--) |
| [setPages(PageCollection value)](#setPages-com.aspose.diagram.PageCollection-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getPages()](../../com.aspose.diagram/page\#getPages--) |
| [setPresetTheme(int value)](#setPresetTheme-int-) | تطبيق سمة مسبقة الإعداد على هذه الصفحة |
| [setPresetThemeQuickStyle(int value)](#setPresetThemeQuickStyle-int-) | تطبيق نمط سريع لمتغيّر سمة مسبقة الإعداد على هذه الصفحة |
| [setPresetThemeVariant(int value)](#setPresetThemeVariant-int-) | تطبيق متغيّر سمة مسبقة الإعداد على هذه الصفحة |
| [setReviewerID(int value)](#setReviewerID-int-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getReviewerID()](../../com.aspose.diagram/page\#getReviewerID--) |
| [setViewCenterX(double value)](#setViewCenterX-double-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getViewCenterX()](../../com.aspose.diagram/page\#getViewCenterX--) |
| [setViewCenterY(double value)](#setViewCenterY-double-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getViewCenterY()](../../com.aspose.diagram/page\#getViewCenterY--) |
| [setViewScale(double value)](#setViewScale-double-) | للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getViewScale()](../../com.aspose.diagram/page\#getViewScale--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Page() {#Page--}
```
public Page()
```


منشئ.

### Page(int ID) {#Page-int-}
```
public Page(int ID)
```


منشئ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| ID | int |  |

### addActiveXControl(int type, double pinX, double pinY, double width, double height) {#addActiveXControl-int-double-double-double-double-}
```
public long addActiveXControl(int type, double pinX, double pinY, double width, double height)
```


ينشئ عنصر تحكم Activex.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| النوع | int | نوع التحكم. |
| pinX | double | يحدد الإحداثي السيني لدبوس الشكل (مركز الدوران) بالنسبة للصفحة. |
| pinY | double | يحدد الإحداثي الصادي لدبوس الشكل (مركز الدوران) بالنسبة للصفحة. |
| width | double | يحدد عرض الشكل بالبوصة. |
| height | double | يحدد ارتفاع الشكل بالبوصة. |

**Returns:**
long -
### addComment(Shape shape, String comment) {#addComment-com.aspose.diagram.Shape-java.lang.String-}
```
public void addComment(Shape shape, String comment)
```


يضيف تعليقًا إلى شكل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) | يحدد الشكل الذي يضيف التعليق. |
| comment | java.lang.String | سلسلة التعليق. |

### addComment(double pinX, double pinY, String comment) {#addComment-double-double-java.lang.String-}
```
public void addComment(double pinX, double pinY, String comment)
```


يضيف تعليقًا مع PinX و PinY المحددين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pinX | double | يحدد الإحداثي السيني لدبوس التعليق (مركز الدوران) بالنسبة للصفحة. |
| pinY | double | يحدد الإحداثي الصادي لدبوس التعليق (مركز الدوران) بالنسبة للصفحة. |
| comment | java.lang.String | سلسلة التعليق. |

### addComment(long shapeID, String comment) {#addComment-long-java.lang.String-}
```
public void addComment(long shapeID, String comment)
```


يضيف تعليقًا إلى شكل باستخدام معرف الشكل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| shapeID | long |  |
| comment | java.lang.String | سلسلة التعليق. |

### addShape(Shape newShape, String masterName) {#addShape-com.aspose.diagram.Shape-java.lang.String-}
```
public long addShape(Shape newShape, String masterName)
```


يضيف شكلًا تم إنشاؤه بواسطة القالب إلى صفحة محددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newShape | [Shape](../../com.aspose.diagram/shape) | كائن شكل جديد[Shape](../../com.aspose.diagram/shape). |
| masterName | java.lang.String | اسم القالب. |

**Returns:**
long - المعرف الفريد للشكل داخل مجموعة الأشكال في الصفحة المحددة.
### addShape(double pinX, double pinY, double width, double height, InputStream stream) {#addShape-double-double-double-double-java.io.InputStream-}
```
public long addShape(double pinX, double pinY, double width, double height, InputStream stream)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pinX | double |  |
| pinY | double |  |
| width | double |  |
| height | double |  |
| تدفق | java.io.InputStream |  |

**Returns:**
long
### addShape(double pinX, double pinY, double width, double height, InputStream imageStream, InputStream objectDataStream) {#addShape-double-double-double-double-java.io.InputStream-java.io.InputStream-}
```
public long addShape(double pinX, double pinY, double width, double height, InputStream imageStream, InputStream objectDataStream)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pinX | double |  |
| pinY | double |  |
| width | double |  |
| height | double |  |
| imageStream | java.io.InputStream |  |
| objectDataStream | java.io.InputStream |  |

**Returns:**
long
### addShape(double pinX, double pinY, double width, double height, String masterName) {#addShape-double-double-double-double-java.lang.String-}
```
public long addShape(double pinX, double pinY, double width, double height, String masterName)
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

**Returns:**
long - المعرف الفريد للشكل داخل مجموعة الأشكال في الصفحة المحددة.
### addShape(double pinX, double pinY, String masterName) {#addShape-double-double-java.lang.String-}
```
public long addShape(double pinX, double pinY, String masterName)
```


يضيف شكلًا تم إنشاؤه بواسطة القالب على الصفحة مع PinX و PinY المحددين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pinX | double | يحدد الإحداثي السيني لدبوس الشكل (مركز الدوران) بالنسبة للصفحة. |
| pinY | double | يحدد الإحداثي الصادي لدبوس الشكل (مركز الدوران) بالنسبة للصفحة. |
| masterName | java.lang.String | اسم القالب. |

**Returns:**
long - المعرف الفريد للشكل داخل مجموعة الأشكال في الصفحة المحددة.
### addText(double pinX, double pinY, double width, double height, String text) {#addText-double-double-double-double-java.lang.String-}
```
public Shape addText(double pinX, double pinY, double width, double height, String text)
```


يضيف نصًا مع PinX و PinY المحددين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pinX | double | يحدد إحداثي x لمشبك النص (مركز الدوران) بالنسبة إلى الصفحة. |
| pinY | double | يحدد إحداثي y لمشبك النص (مركز الدوران) بالنسبة إلى الصفحة. |
| width | double |  |
| height | double |  |
| text | java.lang.String | سلسلة نصية. |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - Returns a shape object that represents the new text object.
### addText(double pinX, double pinY, double width, double height, String text, String fontName, String fontColor, double size) {#addText-double-double-double-double-java.lang.String-java.lang.String-java.lang.String-double-}
```
public Shape addText(double pinX, double pinY, double width, double height, String text, String fontName, String fontColor, double size)
```


يضيف نصًا مع PinX و PinY المحددين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pinX | double | يحدد إحداثي x لمشبك النص (مركز الدوران) بالنسبة إلى الصفحة. |
| pinY | double | يحدد إحداثي y لمشبك النص (مركز الدوران) بالنسبة إلى الصفحة. |
| width | double | يحدد عرض النص. |
| height | double | يحدد ارتفاع النص. |
| text | java.lang.String | سلسلة نصية. |
| fontName | java.lang.String | اسم خط النص. |
| fontColor | java.lang.String | لون خط النص. |
| size | double | حجم خط النص. |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - Returns a shape object that represents the new text object.
### applyStyle(int textStyle, int lineStyle, int fillStyle) {#applyStyle-int-int-int-}
```
public void applyStyle(int textStyle, int lineStyle, int fillStyle)
```


يطبق النمط على الصفحة بالكامل. القيمة الافتراضية هي -1.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| textStyle | int | معرّف نمط النص. |
| lineStyle | int | معرّف نمط الخط. |
| fillStyle | int | معرّف نمط التعبئة. |

### autoSpaceShapes(ShapeCollection shapes, AutoSpaceOptions options) {#autoSpaceShapes-com.aspose.diagram.ShapeCollection-com.aspose.diagram.AutoSpaceOptions-}
```
public void autoSpaceShapes(ShapeCollection shapes, AutoSpaceOptions options)
```


توزيع تلقائي للأشكال

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| shapes | [ShapeCollection](../../com.aspose.diagram/shapecollection) | يحدد أن الأشكال يتم توزيعها تلقائيًا. |
| options | [AutoSpaceOptions](../../com.aspose.diagram/autospaceoptions) |  |

### bringForward(long shapeId) {#bringForward-long-}
```
public void bringForward(long shapeId)
```


ينقل شكلًا، معرفًا بالمعرف ID، خطوة واحدة إلى الأمام في ترتيب Z.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| shapeId | long | معرّف shape.long |

### bringToFront(long shapeId) {#bringToFront-long-}
```
public void bringToFront(long shapeId)
```


ينقل شكلًا، معرفًا بالمعرف ID، إلى مقدمة ترتيب Z.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| shapeId | long | معرّف shape.long |

### centerDrawing() {#centerDrawing--}
```
public void centerDrawing()
```


يتمركز أشكال الصفحة بالنسبة إلى امتداد الصفحة. لا يغيّر تمركز الأشكال موقعها بالنسبة لبعضها.

### connectShapesViaConnector(Shape shapeFrom, int placeFrom, Shape shapeTo, int placeTo, Shape connector) {#connectShapesViaConnector-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-}
```
public void connectShapesViaConnector(Shape shapeFrom, int placeFrom, Shape shapeTo, int placeTo, Shape connector)
```


ربط الأشكال عبر الموصل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| shapeFrom | [Shape](../../com.aspose.diagram/shape) | الشكل الذي يبدأ منه الموصل [Shape](../../com.aspose.diagram/shape). |
| placeFrom | int | الموقع على الشكل الأول حيث سيتم ربط الموصل Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| shapeTo | [Shape](../../com.aspose.diagram/shape) | الشكل حيث ينتهي الموصل [Shape](../../com.aspose.diagram/shape). |
| placeTo | int | الموقع على الشكل الثاني حيث سيتم ربط الموصل Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| connector | [Shape](../../com.aspose.diagram/shape) | الشكل من النوع Dynamic connector [Shape](../../com.aspose.diagram/shape). |

### connectShapesViaConnector(long shapeFromId, int placeFrom, long shapeToId, int placeTo, long connectorId) {#connectShapesViaConnector-long-int-long-int-long-}
```
public void connectShapesViaConnector(long shapeFromId, int placeFrom, long shapeToId, int placeTo, long connectorId)
```


ربط الأشكال عبر الموصل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| shapeFromId | long | معرّف الشكل حيث يبدأ الموصل [Shape](../../com.aspose.diagram/shape). |
| placeFrom | int | الموقع على الشكل الأول حيث سيتم ربط الموصل Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| shapeToId | long | معرّف الشكل حيث ينتهي الموصل [Shape](../../com.aspose.diagram/shape). |
| placeTo | int | الموقع على الشكل الثاني حيث سيتم ربط الموصل Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| connectorId | long | معرّف الشكل من النوع Dynamic connector [Shape](../../com.aspose.diagram/shape). |

### connectShapesViaConnector(long shapeFromId, String fromConnectionName, long shapeToId, String toConnectionName, long connectorId) {#connectShapesViaConnector-long-java.lang.String-long-java.lang.String-long-}
```
public void connectShapesViaConnector(long shapeFromId, String fromConnectionName, long shapeToId, String toConnectionName, long connectorId)
```


ربط الأشكال عبر الموصل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| shapeFromId | long | معرّف الشكل حيث يبدأ الموصل [Shape](../../com.aspose.diagram/shape). |
| fromConnectionName | java.lang.String | اسم الاتصال على الشكل الأول حيث سيتم ربط الموصل . |
| shapeToId | long | معرّف الشكل حيث ينتهي الموصل [Shape](../../com.aspose.diagram/shape). |
| toConnectionName | java.lang.String | اسم الاتصال على الشكل الثاني حيث سيتم ربط الموصل . |
| connectorId | long | معرّف الشكل من النوع Dynamic connector [Shape](../../com.aspose.diagram/shape). |

### connectShapesViaConnectorIndex(Shape shapeFrom, int fromIndex, Shape shapeTo, int toIndex, Shape connector) {#connectShapesViaConnectorIndex-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-}
```
public void connectShapesViaConnectorIndex(Shape shapeFrom, int fromIndex, Shape shapeTo, int toIndex, Shape connector)
```


ربط الأشكال عبر فهرس الموصل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| shapeFrom | [Shape](../../com.aspose.diagram/shape) | الشكل الذي يبدأ منه الموصل [Shape](../../com.aspose.diagram/shape). |
| fromIndex | int | فهرس الاتصال على الشكل الأول |
| shapeTo | [Shape](../../com.aspose.diagram/shape) | الشكل حيث ينتهي الموصل [Shape](../../com.aspose.diagram/shape). |
| toIndex | int | فهرس الاتصال على الشكل الثاني |
| connector | [Shape](../../com.aspose.diagram/shape) | الشكل من النوع Dynamic connector [Shape](../../com.aspose.diagram/shape). |

### connectShapesViaConnectorIndex(long shapeFromId, int fromIndex, long shapeToId, int toIndex, long connectorId) {#connectShapesViaConnectorIndex-long-int-long-int-long-}
```
public void connectShapesViaConnectorIndex(long shapeFromId, int fromIndex, long shapeToId, int toIndex, long connectorId)
```


ربط الأشكال عبر فهرس الموصل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| shapeFromId | long | معرّف الشكل حيث يبدأ الموصل [Shape](../../com.aspose.diagram/shape). |
| fromIndex | int | فهرس الاتصال على الشكل الأول |
| shapeToId | long | معرّف الشكل حيث ينتهي الموصل [Shape](../../com.aspose.diagram/shape). |
| toIndex | int | فهرس الاتصال على الشكل الثاني |
| connectorId | long | معرّف الشكل من النوع Dynamic connector [Shape](../../com.aspose.diagram/shape). |

### copy(Page source) {#copy-com.aspose.diagram.Page-}
```
public void copy(Page source)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [Page](../../com.aspose.diagram/page) |  |

### dispose() {#dispose--}
```
public void dispose()
```


ينفّذ مهامًا محددة من قبل التطبيق مرتبطة بتحرير أو إطلاق أو إعادة ضبط الموارد غير المُدارة.

### drawEllipse(double pinX, double pinY, double width, double height) {#drawEllipse-double-double-double-double-}
```
public long drawEllipse(double pinX, double pinY, double width, double height)
```


عملية رسم الشكل البيضاوي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pinX | double | يحدد الإحداثي السيني لدبوس الشكل (مركز الدوران) بالنسبة للصفحة. |
| pinY | double | يحدد الإحداثي الصادي لدبوس الشكل (مركز الدوران) بالنسبة للصفحة. |
| width | double | يحدد عرض الشكل |
| height | double | يحدد ارتفاع الشكل |

**Returns:**
long -
### drawLine(double beginX, double beginY, double endX, double endY) {#drawLine-double-double-double-double-}
```
public long drawLine(double beginX, double beginY, double endX, double endY)
```


عملية رسم خط واحد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| beginX | double | يحدد إحداثي x الابتدائي لموضع الشكل بالنسبة للصفحة. |
| beginY | double | يحدد إحداثي y الابتدائي لموضع الشكل بالنسبة للصفحة. |
| endX | double | يحدد إحداثي x النهائي لموضع الشكل بالنسبة للصفحة. |
| endY | double | يحدد إحداثي y النهائي لموضع الشكل بالنسبة للصفحة. |

**Returns:**
long - المعرف الفريد للشكل داخل مجموعة الأشكال في الصفحة المحددة.
### drawLine(double pinX, double pinY, double width, double height, double[] xyArray) {#drawLine-double-double-double-double-double---}
```
public long drawLine(double pinX, double pinY, double width, double height, double[] xyArray)
```


عملية رسم الخط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pinX | double | يحدد الإحداثي السيني لدبوس الشكل (مركز الدوران) بالنسبة للصفحة. |
| pinY | double | يحدد الإحداثي الصادي لدبوس الشكل (مركز الدوران) بالنسبة للصفحة. |
| width | double | يحدد عرض الشكل |
| height | double | يحدد ارتفاع الشكل |
| xyArray | double[] | مصفوفة من قيم x و y المتناوبة التي تحدد النقاط في الشكل الجديد |

**Returns:**
long - المعرف الفريد للشكل داخل مجموعة الأشكال في الصفحة المحددة.
### drawPolyline(double pinX, double pinY, double width, double height, double[] xyArray) {#drawPolyline-double-double-double-double-double---}
```
public long drawPolyline(double pinX, double pinY, double width, double height, double[] xyArray)
```


عملية رسم الخط المتعدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pinX | double | يحدد الإحداثي السيني لدبوس الشكل (مركز الدوران) بالنسبة للصفحة. |
| pinY | double | يحدد الإحداثي الصادي لدبوس الشكل (مركز الدوران) بالنسبة للصفحة. |
| width | double | يحدد عرض الشكل |
| height | double | يحدد ارتفاع الشكل |
| xyArray | double[] | مصفوفة من قيم x و y المتناوبة التي تحدد النقاط في الشكل الجديد |

**Returns:**
long - المعرف الفريد للشكل داخل مجموعة الأشكال في الصفحة المحددة.
### drawRectangle(double pinX, double pinY, double width, double height) {#drawRectangle-double-double-double-double-}
```
public long drawRectangle(double pinX, double pinY, double width, double height)
```


عملية رسم المستطيل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pinX | double | يحدد الإحداثي السيني لدبوس الشكل (مركز الدوران) بالنسبة للصفحة. |
| pinY | double | يحدد الإحداثي الصادي لدبوس الشكل (مركز الدوران) بالنسبة للصفحة. |
| width | double | يحدد عرض الشكل |
| height | double | يحدد ارتفاع الشكل |

**Returns:**
long - المعرف الفريد للشكل داخل مجموعة الأشكال في الصفحة المحددة.
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
### getAssociatedPage() {#getAssociatedPage--}
```
public Page getAssociatedPage()
```


معرّف الصفحة الأصلية للرسم التي تم وضع علامات عليها في طبقات علامات منفصلة من قبل مراجعّي الرسم.

**Returns:**
[Page](../../com.aspose.diagram/page)
### getBackPage() {#getBackPage--}
```
public Page getBackPage()
```


صفحة الخلفية للصفحة.

**Returns:**
[Page](../../com.aspose.diagram/page)
### getBackground() {#getBackground--}
```
public int getBackground()
```


علامة تشير إلى ما إذا كانت الصفحة صفحة خلفية.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConnects() {#getConnects--}
```
public ConnectCollection getConnects()
```


يحتوي على عنصر Connect لكل اتصال بين شكلين في الرسم.

**Returns:**
[ConnectCollection](../../com.aspose.diagram/connectcollection)
### getID() {#getID--}
```
public int getID()
```


المعرّف الفريد للعنصر داخل العنصر الأب.

**Returns:**
int
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
### getPageSheet() {#getPageSheet--}
```
public PageSheet getPageSheet()
```


يحتوي على عناصر تُعرّف ورقة الصفحة لعنصر صفحة أو عنصر رئيسي.

**Returns:**
[PageSheet](../../com.aspose.diagram/pagesheet)
### getPages() {#getPages--}
```
public PageCollection getPages()
```


مجموعة الصفحات.

**Returns:**
[PageCollection](../../com.aspose.diagram/pagecollection)
### getReviewerID() {#getReviewerID--}
```
public int getReviewerID()
```


معرّف المراجع المرتبط بطبقة العلامات.

**Returns:**
int
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


مجموعة الأشكال.

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getViewCenterX() {#getViewCenterX--}
```
public double getViewCenterX()
```


تحدد ViewCenterX و ViewCenterY نقطة مركزية على الصفحة يتبناها العرض (النافذة) الجديد عند فتحه مبدئياً.

**Returns:**
double
### getViewCenterY() {#getViewCenterY--}
```
public double getViewCenterY()
```


تحدد ViewCenterX و ViewCenterY نقطة مركزية على الصفحة يتبناها العرض (النافذة) الجديد عند فتحه مبدئياً.

**Returns:**
double
### getViewScale() {#getViewScale--}
```
public double getViewScale()
```


عامل التكبير الافتراضي الذي يُستخدم عند فتح عرض (نافذة) جديد للصفحة. على سبيل المثال، 1 = 100٪؛ 1.5 = 150٪، وهكذا.

**Returns:**
double
### glueShapeToConnectorBeginX(long shapeFromId, String connectionName, long connectorId) {#glueShapeToConnectorBeginX-long-java.lang.String-long-}
```
public void glueShapeToConnectorBeginX(long shapeFromId, String connectionName, long connectorId)
```


ربط الشكل بـ Connector's BeginX

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| shapeFromId | long | معرّف الشكل حيث يبدأ الموصل [Shape](../../com.aspose.diagram/shape). |
| connectionName | java.lang.String | اسم الاتصال على الشكل حيث سيتم ربط الموصل. |
| connectorId | long | معرّف الشكل من النوع Dynamic connector [Shape](../../com.aspose.diagram/shape). |

### glueShapeToConnectorEndX(long shapeToId, String connectionName, long connectorId) {#glueShapeToConnectorEndX-long-java.lang.String-long-}
```
public void glueShapeToConnectorEndX(long shapeToId, String connectionName, long connectorId)
```


ربط الشكل بـ Connector's EndX

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| shapeToId | long | معرّف الشكل حيث ينتهي الموصل [Shape](../../com.aspose.diagram/shape). |
| connectionName | java.lang.String | اسم الاتصال على الشكل الثاني حيث سيتم ربط الموصل . |
| connectorId | long | معرّف الشكل من النوع Dynamic connector [Shape](../../com.aspose.diagram/shape). |

### glueShapes(Shape shapeFrom, int placeTo, Shape shapeTo) {#glueShapes-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-}
```
public void glueShapes(Shape shapeFrom, int placeTo, Shape shapeTo)
```


ربط الأشكال.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| shapeFrom | [Shape](../../com.aspose.diagram/shape) | الشكل الذي يتم لصقه من [Shape](../../com.aspose.diagram/shape). |
| placeTo | int | الموقع على الشكل الأول حيث يتم لصق Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| shapeTo | [Shape](../../com.aspose.diagram/shape) | الشكل الذي يتم اللصق إليه [Shape](../../com.aspose.diagram/shape). |

### glueShapes(long shapeFromId, int placeTo, long shapeToId) {#glueShapes-long-int-long-}
```
public void glueShapes(long shapeFromId, int placeTo, long shapeToId)
```


ربط الأشكال

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| shapeFromId | long | معرّف الشكل الذي يتم لصقه من [Shape](../../com.aspose.diagram/shape). |
| placeTo | int | الموقع على الشكل الأول حيث يتم لصق Aspose.Diagram.Manipulation.ConnectionPointPlace. |
| shapeToId | long | معرّف الشكل الذي يتم اللصق إليه [Shape](../../com.aspose.diagram/shape). |

### glueShapesInContainer(long shapeFromId, int shapeToBeginConnectionIndex, int shapeToEndConnectionIndex, long shapeToId) {#glueShapesInContainer-long-int-int-long-}
```
public void glueShapesInContainer(long shapeFromId, int shapeToBeginConnectionIndex, int shapeToEndConnectionIndex, long shapeToId)
```


ربط الأشكال في الحاوية

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| shapeFromId | long | معرّف الشكل الذي يتم لصقه من [Shape](../../com.aspose.diagram/shape). |
| shapeToBeginConnectionIndex | int | الموقع على فهرس الاتصال الأول حيث يتم اللصق. |
| shapeToEndConnectionIndex | int | الموقع على فهرس الاتصال النهائي حيث يتم اللصق. |
| shapeToId | long | معرّف الشكل الذي يتم اللصق إليه [Shape](../../com.aspose.diagram/shape). |

### glueShapesInContainer(long shapeFromId, String shapeToBeginConnectionName, String shapeToEndConnectionName, long shapeToId) {#glueShapesInContainer-long-java.lang.String-java.lang.String-long-}
```
public void glueShapesInContainer(long shapeFromId, String shapeToBeginConnectionName, String shapeToEndConnectionName, long shapeToId)
```


ربط الأشكال في الحاوية باستخدام اسم الاتصال

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| shapeFromId | long | معرّف الشكل الذي يتم لصقه من [Shape](../../com.aspose.diagram/shape). |
| shapeToBeginConnectionName | java.lang.String | الموقع على اسم الاتصال الأول حيث يتم اللصق. |
| shapeToEndConnectionName | java.lang.String | الموقع على اسم الاتصال النهائي حيث يتم اللصق. |
| shapeToId | long | معرّف الشكل الذي يتم اللصق إليه [Shape](../../com.aspose.diagram/shape). |

### glueShapesInContainerByID(long shapeFromId, int shapeToBeginConnectionID, int shapeToEndConnectionID, long shapeToId) {#glueShapesInContainerByID-long-int-int-long-}
```
public void glueShapesInContainerByID(long shapeFromId, int shapeToBeginConnectionID, int shapeToEndConnectionID, long shapeToId)
```


ربط الأشكال بواسطة معرّف الاتصال في الحاوية

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| shapeFromId | long | معرّف الشكل الذي يتم لصقه من [Shape](../../com.aspose.diagram/shape). |
| shapeToBeginConnectionID | int | الموقع على معرّف الاتصال الأول حيث يتم اللصق. |
| shapeToEndConnectionID | int | الموقع على معرّف الاتصال النهائي حيث يتم اللصق. |
| shapeToId | long | معرّف الشكل الذي يتم اللصق إليه [Shape](../../com.aspose.diagram/shape). |

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


ينظم الأشكال و/أو يعيد توجيه الموصلات للصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| options | [LayoutOptions](../../com.aspose.diagram/layoutoptions) | استخدام [LayoutOptions](../../com.aspose.diagram/layoutoptions) لتكوين خيارات التخطيط. |

### moveTo(int index) {#moveTo-int-}
```
public void moveTo(int index)
```


ينقل الصفحة إلى موقع آخر بين الصفحات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| فهرس | int | فهرس صفحة الوجهة. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### sendBackward(long shapeId) {#sendBackward-long-}
```
public void sendBackward(long shapeId)
```


ينقل شكلًا، معرفًا بالمعرّف، خطوة واحدة إلى الخلف في ترتيب Z.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| shapeId | long | معرّف shape.long |

### sendToBack(long shapeId) {#sendToBack-long-}
```
public void sendToBack(long shapeId)
```


ينقل شكلًا، معرفًا بالمعرّف، إلى مؤخرة ترتيب Z.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| shapeId | long | معرّف shape.long |

### setAssociatedPage(Page value) {#setAssociatedPage-com.aspose.diagram.Page-}
```
public void setAssociatedPage(Page value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getAssociatedPage()](../../com.aspose.diagram/page\#getAssociatedPage--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setBackPage(Page value) {#setBackPage-com.aspose.diagram.Page-}
```
public void setBackPage(Page value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getBackPage()](../../com.aspose.diagram/page\#getBackPage--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setBackground(int value) {#setBackground-int-}
```
public void setBackground(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getBackground()](../../com.aspose.diagram/page\#getBackground--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getID()](../../com.aspose.diagram/page\#getID--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getName()](../../com.aspose.diagram/page\#getName--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getNameU()](../../com.aspose.diagram/page\#getNameU--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### setPages(PageCollection value) {#setPages-com.aspose.diagram.PageCollection-}
```
public void setPages(PageCollection value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getPages()](../../com.aspose.diagram/page\#getPages--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PageCollection](../../com.aspose.diagram/pagecollection) |  |

### setPresetTheme(int value) {#setPresetTheme-int-}
```
public void setPresetTheme(int value)
```


تطبيق سمة مسبقة الإعداد على هذه الصفحة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setPresetThemeQuickStyle(int value) {#setPresetThemeQuickStyle-int-}
```
public void setPresetThemeQuickStyle(int value)
```


تطبيق نمط سريع لمتغيّر سمة مسبقة الإعداد على هذه الصفحة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setPresetThemeVariant(int value) {#setPresetThemeVariant-int-}
```
public void setPresetThemeVariant(int value)
```


تطبيق متغيّر سمة مسبقة الإعداد على هذه الصفحة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setReviewerID(int value) {#setReviewerID-int-}
```
public void setReviewerID(int value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getReviewerID()](../../com.aspose.diagram/page\#getReviewerID--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### setViewCenterX(double value) {#setViewCenterX-double-}
```
public void setViewCenterX(double value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getViewCenterX()](../../com.aspose.diagram/page\#getViewCenterX--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double |  |

### setViewCenterY(double value) {#setViewCenterY-double-}
```
public void setViewCenterY(double value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getViewCenterY()](../../com.aspose.diagram/page\#getViewCenterY--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double |  |

### setViewScale(double value) {#setViewScale-double-}
```
public void setViewScale(double value)
```


للحصول على وصف هذه الخاصية، يرجى الاطلاع على [getViewScale()](../../com.aspose.diagram/page\#getViewScale--)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double |  |

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

