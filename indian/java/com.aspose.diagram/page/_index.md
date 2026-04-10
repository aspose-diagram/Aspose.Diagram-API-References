---
title: Page
second_title: Aspose.Diagram for Java API Reference
description: दस्तावेज़ में एक पृष्ठ को परिभाषित करने वाले तत्व शामिल करता है।
type: docs
weight: 260
url: /hi/java/com.aspose.diagram/page/
---

**Inheritance:**
java.lang.Object
```
public class Page
```

दस्तावेज़ में एक पृष्ठ को परिभाषित करने वाले तत्व शामिल करता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [Page()](#Page--) | कंस्ट्रक्टर। |
| [Page(int ID)](#Page-int-) | कंस्ट्रक्टर। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [addActiveXControl(int type, double pinX, double pinY, double width, double height)](#addActiveXControl-int-double-double-double-double-) | एक Activex कंट्रोल बनाता है। |
| [addComment(Shape shape, String comment)](#addComment-com.aspose.diagram.Shape-java.lang.String-) | एक आकार में टिप्पणी जोड़ता है। |
| [addComment(double pinX, double pinY, String comment)](#addComment-double-double-java.lang.String-) | परिभाषित PinX और PinY के साथ टिप्पणी जोड़ता है। |
| [addComment(long shapeID, String comment)](#addComment-long-java.lang.String-) | आकार की आईडी के साथ आकार में टिप्पणी जोड़ता है। |
| [addShape(Shape newShape, String masterName)](#addShape-com.aspose.diagram.Shape-java.lang.String-) | मास्टर द्वारा निर्मित आकार को विशिष्ट पृष्ठ पर जोड़ता है। |
| [addShape(double pinX, double pinY, double width, double height, InputStream stream)](#addShape-double-double-double-double-java.io.InputStream-) |  |
| [addShape(double pinX, double pinY, double width, double height, InputStream imageStream, InputStream objectDataStream)](#addShape-double-double-double-double-java.io.InputStream-java.io.InputStream-) |  |
| [addShape(double pinX, double pinY, double width, double height, String masterName)](#addShape-double-double-double-double-java.lang.String-) | परिभाषित PinX, PinY, Width और Height के साथ पृष्ठ पर मास्टर द्वारा निर्मित आकार जोड़ता है। |
| [addShape(double pinX, double pinY, String masterName)](#addShape-double-double-java.lang.String-) | परिभाषित PinX और PinY के साथ पृष्ठ पर मास्टर द्वारा निर्मित आकार जोड़ता है। |
| [addText(double pinX, double pinY, double width, double height, String text)](#addText-double-double-double-double-java.lang.String-) | परिभाषित PinX और PinY के साथ टेक्स्ट जोड़ता है। |
| [addText(double pinX, double pinY, double width, double height, String text, String fontName, String fontColor, double size)](#addText-double-double-double-double-java.lang.String-java.lang.String-java.lang.String-double-) | परिभाषित PinX और PinY के साथ टेक्स्ट जोड़ता है। |
| [applyStyle(int textStyle, int lineStyle, int fillStyle)](#applyStyle-int-int-int-) | पूरा पृष्ठ के लिए शैली लागू करता है। |
| [autoSpaceShapes(ShapeCollection shapes, AutoSpaceOptions options)](#autoSpaceShapes-com.aspose.diagram.ShapeCollection-com.aspose.diagram.AutoSpaceOptions-) | आकारों को स्वचालित रूप से स्पेस करता है। |
| [bringForward(long shapeId)](#bringForward-long-) | आईडी द्वारा परिभाषित आकार को z-ऑर्डर में एक स्थिति आगे ले जाता है। |
| [bringToFront(long shapeId)](#bringToFront-long-) | आईडी द्वारा परिभाषित आकार को z-ऑर्डर के सामने ले जाता है। |
| [centerDrawing()](#centerDrawing--) | पृष्ठ के विस्तार के सापेक्ष पृष्ठ के आकारों को केंद्रित करता है। |
| [connectShapesViaConnector(Shape shapeFrom, int placeFrom, Shape shapeTo, int placeTo, Shape connector)](#connectShapesViaConnector-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-) | कनेक्टर के माध्यम से आकारों को जोड़ता है। |
| [connectShapesViaConnector(long shapeFromId, int placeFrom, long shapeToId, int placeTo, long connectorId)](#connectShapesViaConnector-long-int-long-int-long-) | कनेक्टर के माध्यम से आकारों को जोड़ता है। |
| [connectShapesViaConnector(long shapeFromId, String fromConnectionName, long shapeToId, String toConnectionName, long connectorId)](#connectShapesViaConnector-long-java.lang.String-long-java.lang.String-long-) | कनेक्टर के माध्यम से आकारों को जोड़ता है। |
| [connectShapesViaConnectorIndex(Shape shapeFrom, int fromIndex, Shape shapeTo, int toIndex, Shape connector)](#connectShapesViaConnectorIndex-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-) | कनेक्टर इंडेक्स के माध्यम से आकारों को जोड़ता है। |
| [connectShapesViaConnectorIndex(long shapeFromId, int fromIndex, long shapeToId, int toIndex, long connectorId)](#connectShapesViaConnectorIndex-long-int-long-int-long-) | कनेक्टर इंडेक्स के माध्यम से आकारों को जोड़ता है। |
| [copy(Page source)](#copy-com.aspose.diagram.Page-) |  |
| [dispose()](#dispose--) | अनप्रबंधित संसाधनों को मुक्त करने, रिलीज़ करने या रीसेट करने से संबंधित एप्लिकेशन‑परिभाषित कार्यों को निष्पादित करता है। |
| [drawEllipse(double pinX, double pinY, double width, double height)](#drawEllipse-double-double-double-double-) | Ellipse बनाने की प्रक्रिया। |
| [drawLine(double beginX, double beginY, double endX, double endY)](#drawLine-double-double-double-double-) | एकल रेखा बनाने की प्रक्रिया। |
| [drawLine(double pinX, double pinY, double width, double height, double[] xyArray)](#drawLine-double-double-double-double-double---) | रेखा बनाने की प्रक्रिया। |
| [drawPolyline(double pinX, double pinY, double width, double height, double[] xyArray)](#drawPolyline-double-double-double-double-double---) | Polyline बनाने की प्रक्रिया। |
| [drawRectangle(double pinX, double pinY, double width, double height)](#drawRectangle-double-double-double-double-) | आयत बनाने की प्रक्रिया। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAssociatedPage()](#getAssociatedPage--) | ड्रॉइंग के समीक्षकों द्वारा अलग-अलग मार्कअप ओवरले पर चिह्नित मूल ड्रॉइंग पेज का ID। |
| [getBackPage()](#getBackPage--) | पृष्ठ की बैकग्राउंड पेज। |
| [getBackground()](#getBackground--) | एक फ़्लैग जो दर्शाता है कि पृष्ठ बैकग्राउंड पेज है या नहीं। |
| [getClass()](#getClass--) |  |
| [getConnects()](#getConnects--) | ड्रॉइंग में दो आकारों के बीच प्रत्येक कनेक्शन के लिए एक Connect तत्व शामिल करता है। |
| [getID()](#getID--) | तत्व के अपने पैरेंट तत्व के भीतर अद्वितीय ID। |
| [getName()](#getName--) | तत्व का नाम। |
| [getNameU()](#getNameU--) | तत्व का सार्वभौमिक नाम। |
| [getPageSheet()](#getPageSheet--) | पृष्ठ या मास्टर तत्व के लिए पृष्ठ शीट को परिभाषित करने वाले तत्वों को शामिल करता है। |
| [getPages()](#getPages--) | पृष्ठ संग्रह। |
| [getReviewerID()](#getReviewerID--) | मार्कअप ओवरले से जुड़े समीक्षक का ID। |
| [getShapes()](#getShapes--) | आकार संग्रह। |
| [getViewCenterX()](#getViewCenterX--) | ViewCenterX और ViewCenterY एक पृष्ठ पर केंद्र बिंदु निर्दिष्ट करते हैं जिसे नया दृश्य (विंडो) प्रारंभिक रूप से खुलते समय लेता है। |
| [getViewCenterY()](#getViewCenterY--) | ViewCenterX और ViewCenterY एक पृष्ठ पर केंद्र बिंदु निर्दिष्ट करते हैं जिसे नया दृश्य (विंडो) प्रारंभिक रूप से खुलते समय लेता है। |
| [getViewScale()](#getViewScale--) | पृष्ठ के नए दृश्य (विंडो) के खुलने पर उपयोग करने के लिए डिफ़ॉल्ट आवर्धन कारक। |
| [glueShapeToConnectorBeginX(long shapeFromId, String connectionName, long connectorId)](#glueShapeToConnectorBeginX-long-java.lang.String-long-) | आकार को कनेक्टर के BeginX से जोड़ें |
| [glueShapeToConnectorEndX(long shapeToId, String connectionName, long connectorId)](#glueShapeToConnectorEndX-long-java.lang.String-long-) | आकार को कनेक्टर के EndX से जोड़ें |
| [glueShapes(Shape shapeFrom, int placeTo, Shape shapeTo)](#glueShapes-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-) | आकारों को जोड़ें। |
| [glueShapes(long shapeFromId, int placeTo, long shapeToId)](#glueShapes-long-int-long-) | आकारों को जोड़ें |
| [glueShapesInContainer(long shapeFromId, int shapeToBeginConnectionIndex, int shapeToEndConnectionIndex, long shapeToId)](#glueShapesInContainer-long-int-int-long-) | कंटेनर में आकारों को जोड़ें |
| [glueShapesInContainer(long shapeFromId, String shapeToBeginConnectionName, String shapeToEndConnectionName, long shapeToId)](#glueShapesInContainer-long-java.lang.String-java.lang.String-long-) | कनेक्शन नाम का उपयोग करके कंटेनर में आकारों को जोड़ें |
| [glueShapesInContainerByID(long shapeFromId, int shapeToBeginConnectionID, int shapeToEndConnectionID, long shapeToId)](#glueShapesInContainerByID-long-int-int-long-) | कंटेनर में कनेक्शन ID द्वारा आकारों को जोड़ें |
| [hashCode()](#hashCode--) |  |
| [layout(LayoutOptions options)](#layout-com.aspose.diagram.LayoutOptions-) | पृष्ठ के लिए आकारों को व्यवस्थित करता है और/या कनेक्टरों को पुनः मार्गित करता है। |
| [moveTo(int index)](#moveTo-int-) | पृष्ठ को पृष्ठों में किसी अन्य स्थान पर ले जाता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [sendBackward(long shapeId)](#sendBackward-long-) | ID द्वारा परिभाषित एक आकार को Z-क्रम में एक स्थिति पीछे ले जाता है। |
| [sendToBack(long shapeId)](#sendToBack-long-) | ID द्वारा परिभाषित एक आकार को Z-क्रम के अंत में ले जाता है। |
| [setAssociatedPage(Page value)](#setAssociatedPage-com.aspose.diagram.Page-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getAssociatedPage()](../../com.aspose.diagram/page\#getAssociatedPage--) |
| [setBackPage(Page value)](#setBackPage-com.aspose.diagram.Page-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getBackPage()](../../com.aspose.diagram/page\#getBackPage--) |
| [setBackground(int value)](#setBackground-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getBackground()](../../com.aspose.diagram/page\#getBackground--) |
| [setID(int value)](#setID-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getID()](../../com.aspose.diagram/page\#getID--) |
| [setName(String value)](#setName-java.lang.String-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getName()](../../com.aspose.diagram/page\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getNameU()](../../com.aspose.diagram/page\#getNameU--) |
| [setPages(PageCollection value)](#setPages-com.aspose.diagram.PageCollection-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getPages()](../../com.aspose.diagram/page\#getPages--) |
| [setPresetTheme(int value)](#setPresetTheme-int-) | इस पृष्ठ पर एक पूर्वनिर्धारित थीम लागू करें |
| [setPresetThemeQuickStyle(int value)](#setPresetThemeQuickStyle-int-) | इस पृष्ठ पर एक पूर्वनिर्धारित थीम वैरिएंट क्विकस्टाइल लागू करें |
| [setPresetThemeVariant(int value)](#setPresetThemeVariant-int-) | इस पृष्ठ पर एक पूर्वनिर्धारित थीम वैरिएंट लागू करें |
| [setReviewerID(int value)](#setReviewerID-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getReviewerID()](../../com.aspose.diagram/page\#getReviewerID--) |
| [setViewCenterX(double value)](#setViewCenterX-double-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getViewCenterX()](../../com.aspose.diagram/page\#getViewCenterX--) |
| [setViewCenterY(double value)](#setViewCenterY-double-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getViewCenterY()](../../com.aspose.diagram/page\#getViewCenterY--) |
| [setViewScale(double value)](#setViewScale-double-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getViewScale()](../../com.aspose.diagram/page\#getViewScale--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Page() {#Page--}
```
public Page()
```


कंस्ट्रक्टर।

### Page(int ID) {#Page-int-}
```
public Page(int ID)
```


कंस्ट्रक्टर।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| ID | int |  |

### addActiveXControl(int type, double pinX, double pinY, double width, double height) {#addActiveXControl-int-double-double-double-double-}
```
public long addActiveXControl(int type, double pinX, double pinY, double width, double height)
```


एक Activex कंट्रोल बनाता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| प्रकार | int | नियंत्रण का प्रकार। |
| pinX | डबल | पृष्ठ के संदर्भ में आकार के पिन (घूर्णन केंद्र) का x-निर्देशांक निर्दिष्ट करता है। |
| pinY | डबल | पृष्ठ के संदर्भ में आकार के पिन (घूर्णन केंद्र) का y-निर्देशांक निर्दिष्ट करता है। |
| width | डबल | आकार की चौड़ाई इंच में निर्दिष्ट करता है। |
| height | डबल | आकार की ऊँचाई इंच में निर्दिष्ट करता है। |

**Returns:**
long -
### addComment(Shape shape, String comment) {#addComment-com.aspose.diagram.Shape-java.lang.String-}
```
public void addComment(Shape shape, String comment)
```


एक आकार में टिप्पणी जोड़ता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.diagram/shape) | टिप्पणी जोड़ने वाले आकार को निर्दिष्ट करता है। |
| comment | java.lang.String | टिप्पणी की स्ट्रिंग। |

### addComment(double pinX, double pinY, String comment) {#addComment-double-double-java.lang.String-}
```
public void addComment(double pinX, double pinY, String comment)
```


परिभाषित PinX और PinY के साथ टिप्पणी जोड़ता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| pinX | डबल | पृष्ठ के संदर्भ में टिप्पणी के पिन (घूर्णन केंद्र) का x-निर्देशांक निर्दिष्ट करता है। |
| pinY | डबल | पृष्ठ के संदर्भ में टिप्पणी के पिन (घूर्णन केंद्र) का y-निर्देशांक निर्दिष्ट करता है। |
| comment | java.lang.String | टिप्पणी की स्ट्रिंग। |

### addComment(long shapeID, String comment) {#addComment-long-java.lang.String-}
```
public void addComment(long shapeID, String comment)
```


आकार की आईडी के साथ आकार में टिप्पणी जोड़ता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| shapeID | long |  |
| comment | java.lang.String | टिप्पणी की स्ट्रिंग। |

### addShape(Shape newShape, String masterName) {#addShape-com.aspose.diagram.Shape-java.lang.String-}
```
public long addShape(Shape newShape, String masterName)
```


मास्टर द्वारा निर्मित आकार को विशिष्ट पृष्ठ पर जोड़ता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| newShape | [Shape](../../com.aspose.diagram/shape) | नया आकार ऑब्जेक्ट[Shape](../../com.aspose.diagram/shape). |
| masterName | java.lang.String | मास्टर का नाम। |

**Returns:**
long - निर्दिष्ट पृष्ठ पर आकारों के संग्रह में आकार की विशिष्ट ID।
### addShape(double pinX, double pinY, double width, double height, InputStream stream) {#addShape-double-double-double-double-java.io.InputStream-}
```
public long addShape(double pinX, double pinY, double width, double height, InputStream stream)
```




**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| pinX | डबल |  |
| pinY | डबल |  |
| width | डबल |  |
| height | डबल |  |
| स्ट्रीम | java.io.InputStream |  |

**Returns:**
long
### addShape(double pinX, double pinY, double width, double height, InputStream imageStream, InputStream objectDataStream) {#addShape-double-double-double-double-java.io.InputStream-java.io.InputStream-}
```
public long addShape(double pinX, double pinY, double width, double height, InputStream imageStream, InputStream objectDataStream)
```




**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| pinX | डबल |  |
| pinY | डबल |  |
| width | डबल |  |
| height | डबल |  |
| imageStream | java.io.InputStream |  |
| objectDataStream | java.io.InputStream |  |

**Returns:**
long
### addShape(double pinX, double pinY, double width, double height, String masterName) {#addShape-double-double-double-double-java.lang.String-}
```
public long addShape(double pinX, double pinY, double width, double height, String masterName)
```


परिभाषित PinX, PinY, Width और Height के साथ पृष्ठ पर मास्टर द्वारा निर्मित आकार जोड़ता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| pinX | डबल | पृष्ठ के संदर्भ में आकार के पिन (घूर्णन केंद्र) का x-निर्देशांक निर्दिष्ट करता है। |
| pinY | डबल | पृष्ठ के संदर्भ में आकार के पिन (घूर्णन केंद्र) का y-निर्देशांक निर्दिष्ट करता है। |
| width | डबल | आकार की चौड़ाई इंच में निर्दिष्ट करता है। |
| height | डबल | आकार की ऊँचाई इंच में निर्दिष्ट करता है। |
| masterName | java.lang.String | मास्टर का नाम। |

**Returns:**
long - निर्दिष्ट पृष्ठ पर आकारों के संग्रह में आकार की विशिष्ट ID।
### addShape(double pinX, double pinY, String masterName) {#addShape-double-double-java.lang.String-}
```
public long addShape(double pinX, double pinY, String masterName)
```


परिभाषित PinX और PinY के साथ पृष्ठ पर मास्टर द्वारा निर्मित आकार जोड़ता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| pinX | डबल | पृष्ठ के संदर्भ में आकार के पिन (घूर्णन केंद्र) का x-निर्देशांक निर्दिष्ट करता है। |
| pinY | डबल | पृष्ठ के संदर्भ में आकार के पिन (घूर्णन केंद्र) का y-निर्देशांक निर्दिष्ट करता है। |
| masterName | java.lang.String | मास्टर का नाम। |

**Returns:**
long - निर्दिष्ट पृष्ठ पर आकारों के संग्रह में आकार की विशिष्ट ID।
### addText(double pinX, double pinY, double width, double height, String text) {#addText-double-double-double-double-java.lang.String-}
```
public Shape addText(double pinX, double pinY, double width, double height, String text)
```


परिभाषित PinX और PinY के साथ टेक्स्ट जोड़ता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| pinX | डबल | पृष्ठ के सापेक्ष पाठ के पिन (घूर्णन का केंद्र) का x-निर्देशांक निर्दिष्ट करता है। |
| pinY | डबल | पृष्ठ के सापेक्ष पाठ के पिन (घूर्णन का केंद्र) का y-निर्देशांक निर्दिष्ट करता है। |
| width | डबल |  |
| height | डबल |  |
| text | java.lang.String | पाठ स्ट्रिंग। |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - Returns a shape object that represents the new text object.
### addText(double pinX, double pinY, double width, double height, String text, String fontName, String fontColor, double size) {#addText-double-double-double-double-java.lang.String-java.lang.String-java.lang.String-double-}
```
public Shape addText(double pinX, double pinY, double width, double height, String text, String fontName, String fontColor, double size)
```


परिभाषित PinX और PinY के साथ टेक्स्ट जोड़ता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| pinX | डबल | पृष्ठ के सापेक्ष पाठ के पिन (घूर्णन का केंद्र) का x-निर्देशांक निर्दिष्ट करता है। |
| pinY | डबल | पृष्ठ के सापेक्ष पाठ के पिन (घूर्णन का केंद्र) का y-निर्देशांक निर्दिष्ट करता है। |
| width | डबल | पाठ की चौड़ाई निर्दिष्ट करता है। |
| height | डबल | पाठ की ऊँचाई निर्दिष्ट करता है। |
| text | java.lang.String | पाठ स्ट्रिंग। |
| fontName | java.lang.String | पाठ फ़ॉन्ट नाम। |
| fontColor | java.lang.String | पाठ फ़ॉन्ट रंग। |
| size | डबल | पाठ फ़ॉन्ट आकार। |

**Returns:**
[Shape](../../com.aspose.diagram/shape) - Returns a shape object that represents the new text object.
### applyStyle(int textStyle, int lineStyle, int fillStyle) {#applyStyle-int-int-int-}
```
public void applyStyle(int textStyle, int lineStyle, int fillStyle)
```


पूरा पृष्ठ के लिए शैली लागू करता है। डिफ़ॉल्ट मान -1 है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| textStyle | int | पाठ शैली आईडी। |
| lineStyle | int | रेखा शैली आईडी। |
| fillStyle | int | भरण शैली आईडी। |

### autoSpaceShapes(ShapeCollection shapes, AutoSpaceOptions options) {#autoSpaceShapes-com.aspose.diagram.ShapeCollection-com.aspose.diagram.AutoSpaceOptions-}
```
public void autoSpaceShapes(ShapeCollection shapes, AutoSpaceOptions options)
```


आकारों को स्वचालित रूप से स्पेस करता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| shapes | [ShapeCollection](../../com.aspose.diagram/shapecollection) | आकारों को स्वचालित रूप से अंतरित करने को निर्दिष्ट करता है। |
| options | [AutoSpaceOptions](../../com.aspose.diagram/autospaceoptions) |  |

### bringForward(long shapeId) {#bringForward-long-}
```
public void bringForward(long shapeId)
```


आईडी द्वारा परिभाषित आकार को z-ऑर्डर में एक स्थिति आगे ले जाता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| shapeId | long | shape.long की ID |

### bringToFront(long shapeId) {#bringToFront-long-}
```
public void bringToFront(long shapeId)
```


आईडी द्वारा परिभाषित आकार को z-ऑर्डर के सामने ले जाता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| shapeId | long | shape.long की ID |

### centerDrawing() {#centerDrawing--}
```
public void centerDrawing()
```


पृष्ठ के विस्तार के सापेक्ष पृष्ठ के आकारों को केंद्रित करता है। आकारों को केंद्रित करने से उनकी एक-दूसरे के सापेक्ष स्थिति नहीं बदलती।

### connectShapesViaConnector(Shape shapeFrom, int placeFrom, Shape shapeTo, int placeTo, Shape connector) {#connectShapesViaConnector-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-}
```
public void connectShapesViaConnector(Shape shapeFrom, int placeFrom, Shape shapeTo, int placeTo, Shape connector)
```


कनेक्टर के माध्यम से आकारों को जोड़ता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| shapeFrom | [Shape](../../com.aspose.diagram/shape) | कनेक्टर जहाँ शुरू होता है वह आकार [Shape](../../com.aspose.diagram/shape). |
| placeFrom | int | पहले आकार पर वह स्थान जहाँ कनेक्टर जुड़ा जाएगा Aspose.Diagram.Manipulation.ConnectionPointPlace। |
| shapeTo | [Shape](../../com.aspose.diagram/shape) | वह आकार जहाँ कनेक्टर समाप्त होता है [Shape](../../com.aspose.diagram/shape)। |
| placeTo | int | दूसरे आकार पर वह स्थान जहाँ कनेक्टर जुड़ा जाएगा Aspose.Diagram.Manipulation.ConnectionPointPlace। |
| connector | [Shape](../../com.aspose.diagram/shape) | डायनेमिक कनेक्टर प्रकार वाला आकार [Shape](../../com.aspose.diagram/shape)। |

### connectShapesViaConnector(long shapeFromId, int placeFrom, long shapeToId, int placeTo, long connectorId) {#connectShapesViaConnector-long-int-long-int-long-}
```
public void connectShapesViaConnector(long shapeFromId, int placeFrom, long shapeToId, int placeTo, long connectorId)
```


कनेक्टर के माध्यम से आकारों को जोड़ता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| shapeFromId | long | वह आकार जिसका आईडी जहाँ कनेक्टर शुरू होता है [Shape](../../com.aspose.diagram/shape)। |
| placeFrom | int | पहले आकार पर वह स्थान जहाँ कनेक्टर जुड़ा जाएगा Aspose.Diagram.Manipulation.ConnectionPointPlace। |
| shapeToId | long | वह आकार जिसका आईडी जहाँ कनेक्टर समाप्त होता है [Shape](../../com.aspose.diagram/shape)। |
| placeTo | int | दूसरे आकार पर वह स्थान जहाँ कनेक्टर जुड़ा जाएगा Aspose.Diagram.Manipulation.ConnectionPointPlace। |
| connectorId | long | डायनेमिक कनेक्टर प्रकार वाले आकार का आईडी [Shape](../../com.aspose.diagram/shape)। |

### connectShapesViaConnector(long shapeFromId, String fromConnectionName, long shapeToId, String toConnectionName, long connectorId) {#connectShapesViaConnector-long-java.lang.String-long-java.lang.String-long-}
```
public void connectShapesViaConnector(long shapeFromId, String fromConnectionName, long shapeToId, String toConnectionName, long connectorId)
```


कनेक्टर के माध्यम से आकारों को जोड़ता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| shapeFromId | long | वह आकार जिसका आईडी जहाँ कनेक्टर शुरू होता है [Shape](../../com.aspose.diagram/shape)। |
| fromConnectionName | java.lang.String | पहले आकार पर वह कनेक्शन नाम जहाँ कनेक्टर जुड़ा जाएगा। |
| shapeToId | long | वह आकार जिसका आईडी जहाँ कनेक्टर समाप्त होता है [Shape](../../com.aspose.diagram/shape)। |
| toConnectionName | java.lang.String | दूसरे आकार पर वह कनेक्शन नाम जहाँ कनेक्टर जुड़ा जाएगा। |
| connectorId | long | डायनेमिक कनेक्टर प्रकार वाले आकार का आईडी [Shape](../../com.aspose.diagram/shape)। |

### connectShapesViaConnectorIndex(Shape shapeFrom, int fromIndex, Shape shapeTo, int toIndex, Shape connector) {#connectShapesViaConnectorIndex-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-}
```
public void connectShapesViaConnectorIndex(Shape shapeFrom, int fromIndex, Shape shapeTo, int toIndex, Shape connector)
```


कनेक्टर इंडेक्स के माध्यम से आकारों को जोड़ता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| shapeFrom | [Shape](../../com.aspose.diagram/shape) | कनेक्टर जहाँ शुरू होता है वह आकार [Shape](../../com.aspose.diagram/shape). |
| fromIndex | int | पहले आकार पर कनेक्शन का सूचकांक |
| shapeTo | [Shape](../../com.aspose.diagram/shape) | वह आकार जहाँ कनेक्टर समाप्त होता है [Shape](../../com.aspose.diagram/shape)। |
| toIndex | int | दूसरे आकार पर कनेक्शन का सूचकांक |
| connector | [Shape](../../com.aspose.diagram/shape) | डायनेमिक कनेक्टर प्रकार वाला आकार [Shape](../../com.aspose.diagram/shape)। |

### connectShapesViaConnectorIndex(long shapeFromId, int fromIndex, long shapeToId, int toIndex, long connectorId) {#connectShapesViaConnectorIndex-long-int-long-int-long-}
```
public void connectShapesViaConnectorIndex(long shapeFromId, int fromIndex, long shapeToId, int toIndex, long connectorId)
```


कनेक्टर इंडेक्स के माध्यम से आकारों को जोड़ता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| shapeFromId | long | वह आकार जिसका आईडी जहाँ कनेक्टर शुरू होता है [Shape](../../com.aspose.diagram/shape)। |
| fromIndex | int | पहले आकार पर कनेक्शन का सूचकांक |
| shapeToId | long | वह आकार जिसका आईडी जहाँ कनेक्टर समाप्त होता है [Shape](../../com.aspose.diagram/shape)। |
| toIndex | int | दूसरे आकार पर कनेक्शन का सूचकांक |
| connectorId | long | डायनेमिक कनेक्टर प्रकार वाले आकार का आईडी [Shape](../../com.aspose.diagram/shape)। |

### copy(Page source) {#copy-com.aspose.diagram.Page-}
```
public void copy(Page source)
```




**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| source | [Page](../../com.aspose.diagram/page) |  |

### dispose() {#dispose--}
```
public void dispose()
```


अनप्रबंधित संसाधनों को मुक्त करने, रिलीज़ करने या रीसेट करने से संबंधित एप्लिकेशन‑परिभाषित कार्यों को निष्पादित करता है।

### drawEllipse(double pinX, double pinY, double width, double height) {#drawEllipse-double-double-double-double-}
```
public long drawEllipse(double pinX, double pinY, double width, double height)
```


Ellipse बनाने की प्रक्रिया।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| pinX | डबल | पृष्ठ के संदर्भ में आकार के पिन (घूर्णन केंद्र) का x-निर्देशांक निर्दिष्ट करता है। |
| pinY | डबल | पृष्ठ के संदर्भ में आकार के पिन (घूर्णन केंद्र) का y-निर्देशांक निर्दिष्ट करता है। |
| width | डबल | आकार की चौड़ाई निर्दिष्ट करता है |
| height | डबल | आकार की ऊँचाई निर्दिष्ट करता है |

**Returns:**
long -
### drawLine(double beginX, double beginY, double endX, double endY) {#drawLine-double-double-double-double-}
```
public long drawLine(double beginX, double beginY, double endX, double endY)
```


एकल रेखा बनाने की प्रक्रिया।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| beginX | डबल | पृष्ठ के सापेक्ष आकार की स्थिति के प्रारंभिक x-निर्देशांक को निर्दिष्ट करता है। |
| beginY | डबल | पृष्ठ के सापेक्ष आकार की स्थिति के प्रारंभिक y-निर्देशांक को निर्दिष्ट करता है। |
| endX | डबल | पृष्ठ के सापेक्ष आकार की स्थिति के अंतिम x-निर्देशांक को निर्दिष्ट करता है। |
| endY | डबल | पृष्ठ के संबंध में आकार की स्थिति के अंत y-निर्देशांक को निर्दिष्ट करता है। |

**Returns:**
long - निर्दिष्ट पृष्ठ पर आकारों के संग्रह में आकार की विशिष्ट ID।
### drawLine(double pinX, double pinY, double width, double height, double[] xyArray) {#drawLine-double-double-double-double-double---}
```
public long drawLine(double pinX, double pinY, double width, double height, double[] xyArray)
```


रेखा बनाने की प्रक्रिया।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| pinX | डबल | पृष्ठ के संदर्भ में आकार के पिन (घूर्णन केंद्र) का x-निर्देशांक निर्दिष्ट करता है। |
| pinY | डबल | पृष्ठ के संदर्भ में आकार के पिन (घूर्णन केंद्र) का y-निर्देशांक निर्दिष्ट करता है। |
| width | डबल | आकार की चौड़ाई निर्दिष्ट करता है |
| height | डबल | आकार की ऊँचाई निर्दिष्ट करता है |
| xyArray | double[] | एक सरणी जिसमें क्रमबद्ध x और y मान होते हैं जो नए आकार में बिंदुओं को परिभाषित करती है। |

**Returns:**
long - निर्दिष्ट पृष्ठ पर आकारों के संग्रह में आकार की विशिष्ट ID।
### drawPolyline(double pinX, double pinY, double width, double height, double[] xyArray) {#drawPolyline-double-double-double-double-double---}
```
public long drawPolyline(double pinX, double pinY, double width, double height, double[] xyArray)
```


Polyline बनाने की प्रक्रिया।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| pinX | डबल | पृष्ठ के संदर्भ में आकार के पिन (घूर्णन केंद्र) का x-निर्देशांक निर्दिष्ट करता है। |
| pinY | डबल | पृष्ठ के संदर्भ में आकार के पिन (घूर्णन केंद्र) का y-निर्देशांक निर्दिष्ट करता है। |
| width | डबल | आकार की चौड़ाई निर्दिष्ट करता है |
| height | डबल | आकार की ऊँचाई निर्दिष्ट करता है |
| xyArray | double[] | एक सरणी जिसमें क्रमबद्ध x और y मान होते हैं जो नए आकार में बिंदुओं को परिभाषित करती है। |

**Returns:**
long - निर्दिष्ट पृष्ठ पर आकारों के संग्रह में आकार की विशिष्ट ID।
### drawRectangle(double pinX, double pinY, double width, double height) {#drawRectangle-double-double-double-double-}
```
public long drawRectangle(double pinX, double pinY, double width, double height)
```


आयत बनाने की प्रक्रिया।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| pinX | डबल | पृष्ठ के संदर्भ में आकार के पिन (घूर्णन केंद्र) का x-निर्देशांक निर्दिष्ट करता है। |
| pinY | डबल | पृष्ठ के संदर्भ में आकार के पिन (घूर्णन केंद्र) का y-निर्देशांक निर्दिष्ट करता है। |
| width | डबल | आकार की चौड़ाई निर्दिष्ट करता है |
| height | डबल | आकार की ऊँचाई निर्दिष्ट करता है |

**Returns:**
long - निर्दिष्ट पृष्ठ पर आकारों के संग्रह में आकार की विशिष्ट ID।
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
बूलियन
### getAssociatedPage() {#getAssociatedPage--}
```
public Page getAssociatedPage()
```


ड्रॉइंग के समीक्षकों द्वारा अलग-अलग मार्कअप ओवरले पर चिह्नित मूल ड्रॉइंग पेज का ID।

**Returns:**
[Page](../../com.aspose.diagram/page)
### getBackPage() {#getBackPage--}
```
public Page getBackPage()
```


पृष्ठ की बैकग्राउंड पेज।

**Returns:**
[Page](../../com.aspose.diagram/page)
### getBackground() {#getBackground--}
```
public int getBackground()
```


एक फ़्लैग जो दर्शाता है कि पृष्ठ बैकग्राउंड पेज है या नहीं।

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


ड्रॉइंग में दो आकारों के बीच प्रत्येक कनेक्शन के लिए एक Connect तत्व शामिल करता है।

**Returns:**
[ConnectCollection](../../com.aspose.diagram/connectcollection)
### getID() {#getID--}
```
public int getID()
```


तत्व के अपने पैरेंट तत्व के भीतर अद्वितीय ID।

**Returns:**
int
### getName() {#getName--}
```
public String getName()
```


तत्व का नाम।

**Returns:**
java.lang.String
### getNameU() {#getNameU--}
```
public String getNameU()
```


तत्व का सार्वभौमिक नाम।

**Returns:**
java.lang.String
### getPageSheet() {#getPageSheet--}
```
public PageSheet getPageSheet()
```


पृष्ठ या मास्टर तत्व के लिए पृष्ठ शीट को परिभाषित करने वाले तत्वों को शामिल करता है।

**Returns:**
[PageSheet](../../com.aspose.diagram/pagesheet)
### getPages() {#getPages--}
```
public PageCollection getPages()
```


पृष्ठ संग्रह।

**Returns:**
[PageCollection](../../com.aspose.diagram/pagecollection)
### getReviewerID() {#getReviewerID--}
```
public int getReviewerID()
```


मार्कअप ओवरले से जुड़े समीक्षक का ID।

**Returns:**
int
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


आकार संग्रह।

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getViewCenterX() {#getViewCenterX--}
```
public double getViewCenterX()
```


ViewCenterX और ViewCenterY एक पृष्ठ पर केंद्र बिंदु निर्दिष्ट करते हैं जिसे नया दृश्य (विंडो) प्रारंभिक रूप से खुलते समय लेता है।

**Returns:**
डबल
### getViewCenterY() {#getViewCenterY--}
```
public double getViewCenterY()
```


ViewCenterX और ViewCenterY एक पृष्ठ पर केंद्र बिंदु निर्दिष्ट करते हैं जिसे नया दृश्य (विंडो) प्रारंभिक रूप से खुलते समय लेता है।

**Returns:**
डबल
### getViewScale() {#getViewScale--}
```
public double getViewScale()
```


पृष्ठ का नया दृश्य (विंडो) खोलते समय उपयोग करने के लिए डिफ़ॉल्ट आवर्धन कारक। उदाहरण के लिए, 1 = 100%; 1.5 = 150%, आदि।

**Returns:**
डबल
### glueShapeToConnectorBeginX(long shapeFromId, String connectionName, long connectorId) {#glueShapeToConnectorBeginX-long-java.lang.String-long-}
```
public void glueShapeToConnectorBeginX(long shapeFromId, String connectionName, long connectorId)
```


आकार को कनेक्टर के BeginX से जोड़ें

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| shapeFromId | long | वह आकार जिसका आईडी जहाँ कनेक्टर शुरू होता है [Shape](../../com.aspose.diagram/shape)। |
| connectionName | java.lang.String | आकार पर वह कनेक्शन नाम जहाँ कनेक्टर जुड़ जाएगा। |
| connectorId | long | डायनेमिक कनेक्टर प्रकार वाले आकार का आईडी [Shape](../../com.aspose.diagram/shape)। |

### glueShapeToConnectorEndX(long shapeToId, String connectionName, long connectorId) {#glueShapeToConnectorEndX-long-java.lang.String-long-}
```
public void glueShapeToConnectorEndX(long shapeToId, String connectionName, long connectorId)
```


आकार को कनेक्टर के EndX से जोड़ें

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| shapeToId | long | वह आकार जिसका आईडी जहाँ कनेक्टर समाप्त होता है [Shape](../../com.aspose.diagram/shape)। |
| connectionName | java.lang.String | दूसरे आकार पर वह कनेक्शन नाम जहाँ कनेक्टर जुड़ा जाएगा। |
| connectorId | long | डायनेमिक कनेक्टर प्रकार वाले आकार का आईडी [Shape](../../com.aspose.diagram/shape)। |

### glueShapes(Shape shapeFrom, int placeTo, Shape shapeTo) {#glueShapes-com.aspose.diagram.Shape-int-com.aspose.diagram.Shape-}
```
public void glueShapes(Shape shapeFrom, int placeTo, Shape shapeTo)
```


आकारों को जोड़ें।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| shapeFrom | [Shape](../../com.aspose.diagram/shape) | आकार जो [Shape](../../com.aspose.diagram/shape) से चिपकाया गया है। |
| placeTo | int | पहले आकार पर वह स्थान जहाँ Aspose.Diagram.Manipulation.ConnectionPointPlace को चिपकाया जाए। |
| shapeTo | [Shape](../../com.aspose.diagram/shape) | आकार जहाँ [Shape](../../com.aspose.diagram/shape) को चिपकाया जाए। |

### glueShapes(long shapeFromId, int placeTo, long shapeToId) {#glueShapes-long-int-long-}
```
public void glueShapes(long shapeFromId, int placeTo, long shapeToId)
```


आकारों को जोड़ें

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| shapeFromId | long | आकार की ID जो [Shape](../../com.aspose.diagram/shape) से चिपकाया गया है। |
| placeTo | int | पहले आकार पर वह स्थान जहाँ Aspose.Diagram.Manipulation.ConnectionPointPlace को चिपकाया जाए। |
| shapeToId | long | आकार की ID जहाँ [Shape](../../com.aspose.diagram/shape) को चिपकाया जाए। |

### glueShapesInContainer(long shapeFromId, int shapeToBeginConnectionIndex, int shapeToEndConnectionIndex, long shapeToId) {#glueShapesInContainer-long-int-int-long-}
```
public void glueShapesInContainer(long shapeFromId, int shapeToBeginConnectionIndex, int shapeToEndConnectionIndex, long shapeToId)
```


कंटेनर में आकारों को जोड़ें

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| shapeFromId | long | आकार की ID जो [Shape](../../com.aspose.diagram/shape) से चिपकाया गया है। |
| shapeToBeginConnectionIndex | int | पहले कनेक्शन इंडेक्स पर वह स्थान जहाँ चिपकाया जाए। |
| shapeToEndConnectionIndex | int | अंत कनेक्शन इंडेक्स पर वह स्थान जहाँ चिपकाया जाए। |
| shapeToId | long | आकार की ID जहाँ [Shape](../../com.aspose.diagram/shape) को चिपकाया जाए। |

### glueShapesInContainer(long shapeFromId, String shapeToBeginConnectionName, String shapeToEndConnectionName, long shapeToId) {#glueShapesInContainer-long-java.lang.String-java.lang.String-long-}
```
public void glueShapesInContainer(long shapeFromId, String shapeToBeginConnectionName, String shapeToEndConnectionName, long shapeToId)
```


कनेक्शन नाम का उपयोग करके कंटेनर में आकारों को जोड़ें

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| shapeFromId | long | आकार की ID जो [Shape](../../com.aspose.diagram/shape) से चिपकाया गया है। |
| shapeToBeginConnectionName | java.lang.String | पहले कनेक्शन नाम पर वह स्थान जहाँ चिपकाया जाए। |
| shapeToEndConnectionName | java.lang.String | अंत कनेक्शन नाम पर वह स्थान जहाँ चिपकाया जाए। |
| shapeToId | long | आकार की ID जहाँ [Shape](../../com.aspose.diagram/shape) को चिपकाया जाए। |

### glueShapesInContainerByID(long shapeFromId, int shapeToBeginConnectionID, int shapeToEndConnectionID, long shapeToId) {#glueShapesInContainerByID-long-int-int-long-}
```
public void glueShapesInContainerByID(long shapeFromId, int shapeToBeginConnectionID, int shapeToEndConnectionID, long shapeToId)
```


कंटेनर में कनेक्शन ID द्वारा आकारों को जोड़ें

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| shapeFromId | long | आकार की ID जो [Shape](../../com.aspose.diagram/shape) से चिपकाया गया है। |
| shapeToBeginConnectionID | int | पहले कनेक्शन आईडी पर वह स्थान जहाँ चिपकाया जाए। |
| shapeToEndConnectionID | int | अंत कनेक्शन आईडी पर वह स्थान जहाँ चिपकाया जाए। |
| shapeToId | long | आकार की ID जहाँ [Shape](../../com.aspose.diagram/shape) को चिपकाया जाए। |

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


पृष्ठ के लिए आकारों को व्यवस्थित करता है और/या कनेक्टरों को पुनः मार्गित करता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| options | [LayoutOptions](../../com.aspose.diagram/layoutoptions) | [LayoutOptions](../../com.aspose.diagram/layoutoptions) का उपयोग करके लेआउट के विकल्पों को कॉन्फ़िगर किया जा रहा है। |

### moveTo(int index) {#moveTo-int-}
```
public void moveTo(int index)
```


पृष्ठ को पृष्ठों में किसी अन्य स्थान पर ले जाता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| सूचकांक | int | गंतव्य पृष्ठ सूचकांक। |

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


ID द्वारा परिभाषित एक आकार को Z-क्रम में एक स्थिति पीछे ले जाता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| shapeId | long | shape.long की ID |

### sendToBack(long shapeId) {#sendToBack-long-}
```
public void sendToBack(long shapeId)
```


ID द्वारा परिभाषित एक आकार को Z-क्रम के अंत में ले जाता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| shapeId | long | shape.long की ID |

### setAssociatedPage(Page value) {#setAssociatedPage-com.aspose.diagram.Page-}
```
public void setAssociatedPage(Page value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getAssociatedPage()](../../com.aspose.diagram/page\#getAssociatedPage--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setBackPage(Page value) {#setBackPage-com.aspose.diagram.Page-}
```
public void setBackPage(Page value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getBackPage()](../../com.aspose.diagram/page\#getBackPage--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setBackground(int value) {#setBackground-int-}
```
public void setBackground(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getBackground()](../../com.aspose.diagram/page\#getBackground--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getID()](../../com.aspose.diagram/page\#getID--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getName()](../../com.aspose.diagram/page\#getName--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getNameU()](../../com.aspose.diagram/page\#getNameU--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setPages(PageCollection value) {#setPages-com.aspose.diagram.PageCollection-}
```
public void setPages(PageCollection value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getPages()](../../com.aspose.diagram/page\#getPages--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [PageCollection](../../com.aspose.diagram/pagecollection) |  |

### setPresetTheme(int value) {#setPresetTheme-int-}
```
public void setPresetTheme(int value)
```


इस पृष्ठ पर एक पूर्वनिर्धारित थीम लागू करें

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setPresetThemeQuickStyle(int value) {#setPresetThemeQuickStyle-int-}
```
public void setPresetThemeQuickStyle(int value)
```


इस पृष्ठ पर एक पूर्वनिर्धारित थीम वैरिएंट क्विकस्टाइल लागू करें

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setPresetThemeVariant(int value) {#setPresetThemeVariant-int-}
```
public void setPresetThemeVariant(int value)
```


इस पृष्ठ पर एक पूर्वनिर्धारित थीम वैरिएंट लागू करें

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setReviewerID(int value) {#setReviewerID-int-}
```
public void setReviewerID(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getReviewerID()](../../com.aspose.diagram/page\#getReviewerID--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setViewCenterX(double value) {#setViewCenterX-double-}
```
public void setViewCenterX(double value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getViewCenterX()](../../com.aspose.diagram/page\#getViewCenterX--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | डबल |  |

### setViewCenterY(double value) {#setViewCenterY-double-}
```
public void setViewCenterY(double value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getViewCenterY()](../../com.aspose.diagram/page\#getViewCenterY--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | डबल |  |

### setViewScale(double value) {#setViewScale-double-}
```
public void setViewScale(double value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getViewScale()](../../com.aspose.diagram/page\#getViewScale--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | डबल |  |

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
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

