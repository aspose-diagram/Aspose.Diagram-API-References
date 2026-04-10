---
title: Window
second_title: Aspose.Diagram for Java API Reference
description: Microsoft Visio इंस्टेंस में एक खुली विंडो को दर्शाता है।
type: docs
weight: 444
url: /hi/java/com.aspose.diagram/window/
---

**Inheritance:**
java.lang.Object
```
public class Window
```

Microsoft Visio इंस्टेंस में एक खुली विंडो का प्रतिनिधित्व करता है। यह तत्व उन जानकारी को शामिल करता है जो DatadiagramML फ़ाइल को Visio द्वारा प्रारंभिक रूप से खोलते समय एप्लिकेशन कार्यक्षेत्र में उपयोगकर्ता इंटरफ़ेस विंडो को बिल्कुल पुनः बनाने के लिए आवश्यक हैं।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [Window()](#Window--) | कंस्ट्रक्टर। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContainer()](#getContainer--) | कंटेनर की आईडी: पेज, शीट, या मास्टर। |
| [getContainerType()](#getContainerType--) | निम्नलिखित मानों में से एक हो सकता है: Document, Page, या Master। |
| [getDocument()](#getDocument--) | इस विंडो में प्रदर्शित दस्तावेज़ का फ़ाइल पथ। |
| [getDynamicGridEnabled()](#getDynamicGridEnabled--) | निर्दिष्ट करता है कि दस्तावेज़ या विंडो के लिए डायनेमिक ग्रिड सुविधा सक्षम है या नहीं। |
| [getGlueSettings()](#getGlueSettings--) | दस्तावेज़ में ग्लू सक्षम होने पर उन वस्तुओं को निर्दिष्ट करता है जिनसे आकार चिपकते हैं। |
| [getID()](#getID--) | तत्व के अपने पैरेंट तत्व के भीतर अद्वितीय ID। |
| [getMaster()](#getMaster--) | यदि यह विंडो एक मास्टर प्रदर्शित कर रही है तो मास्टर आईडी। |
| [getPage()](#getPage--) | यदि यह विंडो एक पेज प्रदर्शित कर रही है तो पेज आईडी। |
| [getParentWindow()](#getParentWindow--) | जिस विंडो में यह स्टेंसिल विंडो सम्मिलित है, उसकी विंडो आईडी। |
| [getReadOnly()](#getReadOnly--) | यदि यह स्टेंसिल दस्तावेज़ स्टेंसिल नहीं है तो रीड-ओनली फ़्लैग। |
| [getSheet()](#getSheet--) | कंटेनर में शीट की आईडी। |
| [getShowConnectionPoints()](#getShowConnectionPoints--) | निर्दिष्ट करता है कि क्या कनेक्शन पॉइंट्स विंडो में दिखाए जाते हैं। |
| [getShowGrid()](#getShowGrid--) | निर्दिष्ट करता है कि क्या ग्रिड ड्रॉइंग विंडो में दिखाया जाता है। |
| [getShowGuides()](#getShowGuides--) | निर्दिष्ट करता है कि क्या गाइड्स ड्रॉइंग विंडो में दिखाए जाते हैं। |
| [getShowPageBreaks()](#getShowPageBreaks--) | निर्दिष्ट करता है कि क्या पेज ब्रेक्स विंडो में दिखाए जाते हैं। |
| [getShowRulers()](#getShowRulers--) | निर्दिष्ट करता है कि क्या रूलर्स ड्रॉइंग विंडो में दिखाए जाते हैं। |
| [getSnapAngles()](#getSnapAngles--) | SnapAngle तत्वों का एक संग्रह शामिल करता है। |
| [getSnapExtensions()](#getSnapExtensions--) | सक्रिय विंडो के लिए एक विशिष्ट स्नैप एक्सटेंशन सेटिंग सक्षम है या अक्षम, यह निर्दिष्ट करता है। |
| [getSnapSettings()](#getSnapSettings--) | विंडो में स्नैप सक्रिय होने पर आकारों के स्नैप होने वाले वस्तुओं को निर्दिष्ट करता है। |
| [getStencilGroup()](#getStencilGroup--) | उस समूह को निर्दिष्ट करता है जिसमें यह विंडो एक सदस्य के रूप में मर्ज्ड स्टेंसिल विंडोज़ शामिल हैं। |
| [getStencilGroupPos()](#getStencilGroupPos--) | एक पूर्णांक शामिल करता है जो विंडो में समूह के भीतर स्टेंसिल की सापेक्ष स्थिति को निर्दिष्ट करता है। |
| [getTabSplitterPos()](#getTabSplitterPos--) | ड्रॉइंग विंडो के पेज टैब कंट्रोल की चौड़ाई को निर्दिष्ट करता है (ड्रॉइंग विंडो की कुल चौड़ाई के अनुपात के रूप में)। |
| [getViewCenterX()](#getViewCenterX--) | वैकल्पिक डबल। |
| [getViewCenterY()](#getViewCenterY--) | वैकल्पिक डबल। |
| [getViewScale()](#getViewScale--) | वैकल्पिक डबल। |
| [getWindowHeight()](#getWindowHeight--) | विंडो आयत की ऊँचाई। |
| [getWindowLeft()](#getWindowLeft--) | विंडो आयत का बायाँ निर्देशांक। |
| [getWindowState()](#getWindowState--) | यह विशेषता निम्नलिखित मानों का योग हो सकती है। |
| [getWindowTop()](#getWindowTop--) | विंडो आयत का शीर्ष निर्देशांक। |
| [getWindowType()](#getWindowType--) | एक एनीमरेटेड मान जो निम्नलिखित में से एक हो सकता है: Drawing, Sheet, Stencil, या Icon। WindowType='Stencil' वाला विंडो तत्व अपने पैरेंट ड्रॉइंग विंडो (WindowType='Drawing') के बाद और किसी भी अन्य ड्रॉइंग विंडो तत्वों से पहले प्रकट होना चाहिए। |
| [getWindowWidth()](#getWindowWidth--) | विंडो आयत की चौड़ाई। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setContainer(int value)](#setContainer-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getContainer()](../../com.aspose.diagram/window\#getContainer--) |
| [setContainerType(int value)](#setContainerType-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getContainerType()](../../com.aspose.diagram/window\#getContainerType--) |
| [setDocument(String value)](#setDocument-java.lang.String-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getDocument()](../../com.aspose.diagram/window\#getDocument--) |
| [setDynamicGridEnabled(int value)](#setDynamicGridEnabled-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getDynamicGridEnabled()](../../com.aspose.diagram/window\#getDynamicGridEnabled--) |
| [setGlueSettings(int value)](#setGlueSettings-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getGlueSettings()](../../com.aspose.diagram/window\#getGlueSettings--) |
| [setID(int value)](#setID-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getID()](../../com.aspose.diagram/window\#getID--) |
| [setMaster(Master value)](#setMaster-com.aspose.diagram.Master-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getMaster()](../../com.aspose.diagram/window\#getMaster--) |
| [setPage(Page value)](#setPage-com.aspose.diagram.Page-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getPage()](../../com.aspose.diagram/window\#getPage--) |
| [setParentWindow(int value)](#setParentWindow-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getParentWindow()](../../com.aspose.diagram/window\#getParentWindow--) |
| [setReadOnly(int value)](#setReadOnly-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getReadOnly()](../../com.aspose.diagram/window\#getReadOnly--) |
| [setSheet(int value)](#setSheet-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getSheet()](../../com.aspose.diagram/window\#getSheet--) |
| [setShowConnectionPoints(int value)](#setShowConnectionPoints-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getShowConnectionPoints()](../../com.aspose.diagram/window\#getShowConnectionPoints--) |
| [setShowGrid(int value)](#setShowGrid-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getShowGrid()](../../com.aspose.diagram/window\#getShowGrid--) |
| [setShowGuides(int value)](#setShowGuides-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getShowGuides()](../../com.aspose.diagram/window\#getShowGuides--) |
| [setShowPageBreaks(int value)](#setShowPageBreaks-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getShowPageBreaks()](../../com.aspose.diagram/window\#getShowPageBreaks--) |
| [setShowRulers(int value)](#setShowRulers-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getShowRulers()](../../com.aspose.diagram/window\#getShowRulers--) |
| [setSnapExtensions(int value)](#setSnapExtensions-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getSnapExtensions()](../../com.aspose.diagram/window\#getSnapExtensions--) |
| [setSnapSettings(int value)](#setSnapSettings-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getSnapSettings()](../../com.aspose.diagram/window\#getSnapSettings--) |
| [setStencilGroup(String value)](#setStencilGroup-java.lang.String-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getStencilGroup()](../../com.aspose.diagram/window\#getStencilGroup--) |
| [setStencilGroupPos(int value)](#setStencilGroupPos-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getStencilGroupPos()](../../com.aspose.diagram/window\#getStencilGroupPos--) |
| [setTabSplitterPos(double value)](#setTabSplitterPos-double-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getTabSplitterPos()](../../com.aspose.diagram/window\#getTabSplitterPos--) |
| [setViewCenterX(double value)](#setViewCenterX-double-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getViewCenterX()](../../com.aspose.diagram/window\#getViewCenterX--) |
| [setViewCenterY(double value)](#setViewCenterY-double-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getViewCenterY()](../../com.aspose.diagram/window\#getViewCenterY--) |
| [setViewScale(double value)](#setViewScale-double-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getViewScale()](../../com.aspose.diagram/window\#getViewScale--) |
| [setWindowHeight(long value)](#setWindowHeight-long-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getWindowHeight()](../../com.aspose.diagram/window\#getWindowHeight--) |
| [setWindowLeft(int value)](#setWindowLeft-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getWindowLeft()](../../com.aspose.diagram/window\#getWindowLeft--) |
| [setWindowState(int value)](#setWindowState-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getWindowState()](../../com.aspose.diagram/window\#getWindowState--) |
| [setWindowTop(int value)](#setWindowTop-int-) | इस गुण के विवरण के लिए, कृपया देखें [getWindowTop()](../../com.aspose.diagram/window\#getWindowTop--) |
| [setWindowType(int value)](#setWindowType-int-) | इस गुण के विवरण के लिए, कृपया देखें [getWindowType()](../../com.aspose.diagram/window\#getWindowType--) |
| [setWindowWidth(long value)](#setWindowWidth-long-) | इस गुण के विवरण के लिए, कृपया देखें [getWindowWidth()](../../com.aspose.diagram/window\#getWindowWidth--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Window() {#Window--}
```
public Window()
```


कंस्ट्रक्टर।

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContainer() {#getContainer--}
```
public int getContainer()
```


कंटेनर का ID: पेज, शीट, या मास्टर। केवल तभी प्रासंगिक और आवश्यक जब ContainerType निर्दिष्ट किया गया हो।

**Returns:**
int
### getContainerType() {#getContainerType--}
```
public int getContainerType()
```


May be one of the following values: Document, Page, or Master. Only relevant when WindowType is specified as Drawing or Sheet.

**Returns:**
int
### getDocument() {#getDocument--}
```
public String getDocument()
```


इस विंडो में प्रदर्शित दस्तावेज़ का फ़ाइल पथ। यह गुण उन विंडो के लिए प्रासंगिक है जिनका WindowType Stencil के रूप में निर्दिष्ट है।

**Returns:**
java.lang.String
### getDynamicGridEnabled() {#getDynamicGridEnabled--}
```
public int getDynamicGridEnabled()
```


निर्दिष्ट करता है कि दस्तावेज़ या विंडो के लिए डायनेमिक ग्रिड सुविधा सक्षम है या नहीं।

**Returns:**
int
### getGlueSettings() {#getGlueSettings--}
```
public int getGlueSettings()
```


दस्तावेज़ में ग्लू सक्षम होने पर उन वस्तुओं को निर्दिष्ट करता है जिनसे आकार चिपकते हैं।

**Returns:**
int
### getID() {#getID--}
```
public int getID()
```


तत्व के अपने पैरेंट तत्व के भीतर अद्वितीय ID।

**Returns:**
int
### getMaster() {#getMaster--}
```
public Master getMaster()
```


यदि यह विंडो एक मास्टर प्रदर्शित कर रही है तो मास्टर आईडी।

**Returns:**
[Master](../../com.aspose.diagram/master)
### getPage() {#getPage--}
```
public Page getPage()
```


यदि यह विंडो कोई पेज प्रदर्शित कर रही है तो पेज ID। केवल तब प्रासंगिक जब WindowType Drawing और ContainerType Page के रूप में निर्दिष्ट हो।

**Returns:**
[Page](../../com.aspose.diagram/page)
### getParentWindow() {#getParentWindow--}
```
public int getParentWindow()
```


उस विंडो का ID जिसमें यह स्टेंसिल विंडो सम्मिलित है। केवल तब प्रासंगिक जब WindowType Stencil के रूप में निर्दिष्ट हो।

**Returns:**
int
### getReadOnly() {#getReadOnly--}
```
public int getReadOnly()
```


यदि यह स्टेंसिल दस्तावेज़ स्टेंसिल नहीं है तो रीड-ओनली फ़्लैग।

**Returns:**
int
### getSheet() {#getSheet--}
```
public int getSheet()
```


कंटेनर में शीट का ID। केवल तब प्रासंगिक जब Container को Sheet के रूप में निर्दिष्ट किया गया हो।

**Returns:**
int
### getShowConnectionPoints() {#getShowConnectionPoints--}
```
public int getShowConnectionPoints()
```


निर्दिष्ट करता है कि क्या कनेक्शन पॉइंट्स विंडो में दिखाए जाते हैं।

**Returns:**
int
### getShowGrid() {#getShowGrid--}
```
public int getShowGrid()
```


निर्दिष्ट करता है कि क्या ग्रिड ड्रॉइंग विंडो में दिखाया जाता है।

**Returns:**
int
### getShowGuides() {#getShowGuides--}
```
public int getShowGuides()
```


निर्दिष्ट करता है कि क्या गाइड्स ड्रॉइंग विंडो में दिखाए जाते हैं।

**Returns:**
int
### getShowPageBreaks() {#getShowPageBreaks--}
```
public int getShowPageBreaks()
```


निर्दिष्ट करता है कि क्या पेज ब्रेक्स विंडो में दिखाए जाते हैं।

**Returns:**
int
### getShowRulers() {#getShowRulers--}
```
public int getShowRulers()
```


निर्दिष्ट करता है कि क्या रूलर्स ड्रॉइंग विंडो में दिखाए जाते हैं।

**Returns:**
int
### getSnapAngles() {#getSnapAngles--}
```
public FloatPointNumCollection getSnapAngles()
```


SnapAngle तत्वों का एक संग्रह शामिल करता है।

**Returns:**
[FloatPointNumCollection](../../com.aspose.diagram/floatpointnumcollection)
### getSnapExtensions() {#getSnapExtensions--}
```
public int getSnapExtensions()
```


निर्दिष्ट करता है कि सक्रिय विंडो के लिए कोई विशिष्ट स्नैप एक्सटेंशन सेटिंग सक्षम है या अक्षम। मान निम्न तालिका में दिए गए मानों के योग हो सकते हैं।

**Returns:**
int
### getSnapSettings() {#getSnapSettings--}
```
public int getSnapSettings()
```


विंडो में स्नैप सक्रिय होने पर उन वस्तुओं को निर्दिष्ट करता है जिनसे आकार स्नैप होते हैं। मान निम्न तालिका के मानों का योग हो सकता है।

**Returns:**
int
### getStencilGroup() {#getStencilGroup--}
```
public String getStencilGroup()
```


विंडो के सदस्य होने वाले मर्ज किए गए स्टेंसिल विंडो समूह को निर्दिष्ट करता है। यह गुण केवल उन Window तत्वों के लिए प्रासंगिक है जिनका WindowType गुण Stencil है, और केवल तभी जब स्टेंसिल विंडो स्टेंसिल विंडो के मर्ज किए गए समूह का हिस्सा हो। सभी स्टेंसिल विंडो जो एक ही मर्ज किए गए समूह का हिस्सा हैं, उनका StencilGroup तत्व मान समान होता है।

**Returns:**
java.lang.String
### getStencilGroupPos() {#getStencilGroupPos--}
```
public int getStencilGroupPos()
```


एक पूर्णांक शामिल करता है जो विंडो में समूह के भीतर स्टेंसिल की सापेक्ष स्थिति को निर्दिष्ट करता है।

**Returns:**
int
### getTabSplitterPos() {#getTabSplitterPos--}
```
public double getTabSplitterPos()
```


ड्रॉइंग विंडो के पेज टैब कंट्रोल की चौड़ाई को निर्दिष्ट करता है (ड्रॉइंग विंडो की कुल चौड़ाई के अनुपात के रूप में)।

**Returns:**
डबल
### getViewCenterX() {#getViewCenterX--}
```
public double getViewCenterX()
```


वैकल्पिक डबल।

**Returns:**
डबल
### getViewCenterY() {#getViewCenterY--}
```
public double getViewCenterY()
```


वैकल्पिक डबल।

**Returns:**
डबल
### getViewScale() {#getViewScale--}
```
public double getViewScale()
```


वैकल्पिक डबल।

**Returns:**
डबल
### getWindowHeight() {#getWindowHeight--}
```
public long getWindowHeight()
```


विंडो आयत की ऊँचाई।

**Returns:**
long
### getWindowLeft() {#getWindowLeft--}
```
public int getWindowLeft()
```


विंडो आयत का बायाँ निर्देशांक।

**Returns:**
int
### getWindowState() {#getWindowState--}
```
public int getWindowState()
```


यह विशेषता निम्नलिखित मानों का योग हो सकती है।

**Returns:**
int
### getWindowTop() {#getWindowTop--}
```
public int getWindowTop()
```


विंडो आयत का शीर्ष निर्देशांक।

**Returns:**
int
### getWindowType() {#getWindowType--}
```
public int getWindowType()
```


एक एनीमरेटेड मान जो निम्नलिखित में से एक हो सकता है: Drawing, Sheet, Stencil, या Icon। WindowType='Stencil' वाला विंडो तत्व अपने पैरेंट ड्रॉइंग विंडो (WindowType='Drawing') के बाद और किसी भी अन्य ड्रॉइंग विंडो तत्वों से पहले प्रकट होना चाहिए।

**Returns:**
int
### getWindowWidth() {#getWindowWidth--}
```
public long getWindowWidth()
```


विंडो आयत की चौड़ाई।

**Returns:**
long
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setContainer(int value) {#setContainer-int-}
```
public void setContainer(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getContainer()](../../com.aspose.diagram/window\#getContainer--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setContainerType(int value) {#setContainerType-int-}
```
public void setContainerType(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getContainerType()](../../com.aspose.diagram/window\#getContainerType--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setDocument(String value) {#setDocument-java.lang.String-}
```
public void setDocument(String value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getDocument()](../../com.aspose.diagram/window\#getDocument--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setDynamicGridEnabled(int value) {#setDynamicGridEnabled-int-}
```
public void setDynamicGridEnabled(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getDynamicGridEnabled()](../../com.aspose.diagram/window\#getDynamicGridEnabled--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setGlueSettings(int value) {#setGlueSettings-int-}
```
public void setGlueSettings(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getGlueSettings()](../../com.aspose.diagram/window\#getGlueSettings--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getID()](../../com.aspose.diagram/window\#getID--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setMaster(Master value) {#setMaster-com.aspose.diagram.Master-}
```
public void setMaster(Master value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getMaster()](../../com.aspose.diagram/window\#getMaster--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [Master](../../com.aspose.diagram/master) |  |

### setPage(Page value) {#setPage-com.aspose.diagram.Page-}
```
public void setPage(Page value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getPage()](../../com.aspose.diagram/window\#getPage--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [Page](../../com.aspose.diagram/page) |  |

### setParentWindow(int value) {#setParentWindow-int-}
```
public void setParentWindow(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getParentWindow()](../../com.aspose.diagram/window\#getParentWindow--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setReadOnly(int value) {#setReadOnly-int-}
```
public void setReadOnly(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getReadOnly()](../../com.aspose.diagram/window\#getReadOnly--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setSheet(int value) {#setSheet-int-}
```
public void setSheet(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getSheet()](../../com.aspose.diagram/window\#getSheet--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setShowConnectionPoints(int value) {#setShowConnectionPoints-int-}
```
public void setShowConnectionPoints(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getShowConnectionPoints()](../../com.aspose.diagram/window\#getShowConnectionPoints--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setShowGrid(int value) {#setShowGrid-int-}
```
public void setShowGrid(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getShowGrid()](../../com.aspose.diagram/window\#getShowGrid--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setShowGuides(int value) {#setShowGuides-int-}
```
public void setShowGuides(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getShowGuides()](../../com.aspose.diagram/window\#getShowGuides--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setShowPageBreaks(int value) {#setShowPageBreaks-int-}
```
public void setShowPageBreaks(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getShowPageBreaks()](../../com.aspose.diagram/window\#getShowPageBreaks--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setShowRulers(int value) {#setShowRulers-int-}
```
public void setShowRulers(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getShowRulers()](../../com.aspose.diagram/window\#getShowRulers--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setSnapExtensions(int value) {#setSnapExtensions-int-}
```
public void setSnapExtensions(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getSnapExtensions()](../../com.aspose.diagram/window\#getSnapExtensions--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setSnapSettings(int value) {#setSnapSettings-int-}
```
public void setSnapSettings(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getSnapSettings()](../../com.aspose.diagram/window\#getSnapSettings--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setStencilGroup(String value) {#setStencilGroup-java.lang.String-}
```
public void setStencilGroup(String value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getStencilGroup()](../../com.aspose.diagram/window\#getStencilGroup--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setStencilGroupPos(int value) {#setStencilGroupPos-int-}
```
public void setStencilGroupPos(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getStencilGroupPos()](../../com.aspose.diagram/window\#getStencilGroupPos--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setTabSplitterPos(double value) {#setTabSplitterPos-double-}
```
public void setTabSplitterPos(double value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getTabSplitterPos()](../../com.aspose.diagram/window\#getTabSplitterPos--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | डबल |  |

### setViewCenterX(double value) {#setViewCenterX-double-}
```
public void setViewCenterX(double value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getViewCenterX()](../../com.aspose.diagram/window\#getViewCenterX--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | डबल |  |

### setViewCenterY(double value) {#setViewCenterY-double-}
```
public void setViewCenterY(double value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getViewCenterY()](../../com.aspose.diagram/window\#getViewCenterY--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | डबल |  |

### setViewScale(double value) {#setViewScale-double-}
```
public void setViewScale(double value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getViewScale()](../../com.aspose.diagram/window\#getViewScale--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | डबल |  |

### setWindowHeight(long value) {#setWindowHeight-long-}
```
public void setWindowHeight(long value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getWindowHeight()](../../com.aspose.diagram/window\#getWindowHeight--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | long |  |

### setWindowLeft(int value) {#setWindowLeft-int-}
```
public void setWindowLeft(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getWindowLeft()](../../com.aspose.diagram/window\#getWindowLeft--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setWindowState(int value) {#setWindowState-int-}
```
public void setWindowState(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getWindowState()](../../com.aspose.diagram/window\#getWindowState--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setWindowTop(int value) {#setWindowTop-int-}
```
public void setWindowTop(int value)
```


इस गुण के विवरण के लिए, कृपया देखें [getWindowTop()](../../com.aspose.diagram/window\#getWindowTop--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setWindowType(int value) {#setWindowType-int-}
```
public void setWindowType(int value)
```


इस गुण के विवरण के लिए, कृपया देखें [getWindowType()](../../com.aspose.diagram/window\#getWindowType--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setWindowWidth(long value) {#setWindowWidth-long-}
```
public void setWindowWidth(long value)
```


इस गुण के विवरण के लिए, कृपया देखें [getWindowWidth()](../../com.aspose.diagram/window\#getWindowWidth--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | long |  |

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

