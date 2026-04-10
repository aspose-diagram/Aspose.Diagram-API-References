---
title: SVGSaveOptions
second_title: Aspose.Diagram for Java API Reference
description: डायग्राम पृष्ठों को SVG में रेंडर करते समय अतिरिक्त विकल्प निर्दिष्ट करने की अनुमति देता है।
type: docs
weight: 347
url: /hi/java/com.aspose.diagram/svgsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class SVGSaveOptions extends RenderingSaveOptions
```

डायग्राम पृष्ठों को SVG में रेंडर करते समय अतिरिक्त विकल्प निर्दिष्ट करने की अनुमति देता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [SVGSaveOptions()](#SVGSaveOptions--) | इस वर्ग का एक नया उदाहरण प्रारंभ करता है जिसका उपयोग Aspose.Diagram.SaveFileFormat प्रारूप में दस्तावेज़ सहेजने के लिए किया जा सकता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | निर्दिष्ट सहेजने के प्रारूप के लिए उपयुक्त वर्ग की एक सहेजने विकल्प वस्तु बनाता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCustomImagePath()](#getCustomImagePath--) | उपयोगकर्ता द्वारा निर्दिष्ट पथ (URL) जो उत्पन्न SVG फ़ाइल में छवि के लिए सहेजा गया है। |
| [getDefaultFont()](#getDefaultFont--) | जब आरेख में अक्षर यूनिकोड होते हैं और सही फ़ॉन्ट मान सेट नहीं किया गया हो या फ़ॉन्ट स्थानीय रूप से स्थापित न हो, तो वे पीडीएफ, छवि या XPS में ब्लॉक के रूप में दिखाई दे सकते हैं। |
| [getEmfRenderSetting()](#getEmfRenderSetting--) | Emf मेटाफाइल रेंडरिंग के लिए सेटिंग। |
| [getEnlargePage()](#getEnlargePage--) | निर्दिष्ट करता है कि पृष्ठ को बड़ा किया जाए या नहीं। |
| [getExportElementAsRectTag()](#getExportElementAsRectTag--) | परिभाषित करता है कि आयत तत्वों को rect टैग के रूप में निर्यात करने की आवश्यकता है या नहीं। |
| [getExportGuideShapes()](#getExportGuideShapes--) | निर्धारित करता है कि गाइड आकारों को निर्यात करने की आवश्यकता है या नहीं। |
| [getExportHiddenPage()](#getExportHiddenPage--) | निर्धारित करता है कि छिपे पृष्ठ को निर्यात करने की आवश्यकता है या नहीं। |
| [getPageIndex()](#getPageIndex--) | रेंडर करने वाले पृष्ठ का 0-आधारित सूचकांक। |
| [getPageSize()](#getPageSize--) | जनरेट किए गए चित्रों के लिए पृष्ठ आकार। |
| [getQuality()](#getQuality--) | एक मान जो उत्पन्न छवियों की गुणवत्ता निर्धारित करता है और केवल JPEG प्रारूप में पृष्ठ सहेजते समय लागू होता है। |
| [getSVGFitToViewPort()](#getSVGFitToViewPort--) | यदि यह गुण true है, तो उत्पन्न SVG व्यूपोर्ट में फिट हो जाएगा। |
| [getSaveFormat()](#getSaveFormat--) | यदि इस save options ऑब्जेक्ट का उपयोग किया जाता है तो दस्तावेज़ को जिस प्रारूप में सहेजा जाएगा, वह निर्दिष्ट करता है। |
| [getShapes()](#getShapes--) | रेंडर करने के लिए आकार। |
| [getWarningCallback()](#getWarningCallback--) | चेतावनी कॉलबैक। |
| [hashCode()](#hashCode--) |  |
| [isExportComments()](#isExportComments--) | निर्धारित करता है कि टिप्पणियों को निर्यात करने की आवश्यकता है या नहीं। |
| [isExportScaleInMatrix()](#isExportScaleInMatrix--) | परिभाषित करता है कि मैट्रिक्स में निर्यात स्केल की आवश्यकता है या नहीं। |
| [isSavingCustomLinePattern()](#isSavingCustomLinePattern--) | परिभाषित करता है कि कस्टम लाइन पैटर्न सहेजा जाए या नहीं। |
| [isSavingImageSeparately()](#isSavingImageSeparately--) | परिभाषित करता है कि छवि को अलग से सहेजा जाए या नहीं। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomImagePath(String value)](#setCustomImagePath-java.lang.String-) | इस गुण के विवरण के लिए, कृपया देखें [getCustomImagePath()](../../com.aspose.diagram/svgsaveoptions\#getCustomImagePath--) |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setEmfRenderSetting(int value)](#setEmfRenderSetting-int-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--) |
| [setEnlargePage(boolean value)](#setEnlargePage-boolean-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--) |
| [setExportComments(boolean value)](#setExportComments-boolean-) | इस गुण का विवरण देखने के लिए, कृपया देखें [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--) |
| [setExportElementAsRectTag(boolean value)](#setExportElementAsRectTag-boolean-) | इस गुण के विवरण के लिए, कृपया देखें [getExportElementAsRectTag()](../../com.aspose.diagram/svgsaveoptions\#getExportElementAsRectTag--) |
| [setExportGuideShapes(boolean value)](#setExportGuideShapes-boolean-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--) |
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | इस गुण के विवरण के लिए, कृपया देखें [getExportHiddenPage()](../../com.aspose.diagram/svgsaveoptions\#getExportHiddenPage--) |
| [setExportScaleInMatrix(boolean value)](#setExportScaleInMatrix-boolean-) | इस गुण के विवरण के लिए, कृपया देखें [isExportScaleInMatrix()](../../com.aspose.diagram/svgsaveoptions\#isExportScaleInMatrix--) |
| [setPageIndex(int value)](#setPageIndex-int-) | इस गुण के विवरण के लिए, कृपया देखें [getPageIndex()](../../com.aspose.diagram/svgsaveoptions\#getPageIndex--) |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) |
| [setQuality(int value)](#setQuality-int-) | इस गुण के विवरण के लिए, कृपया देखें [getQuality()](../../com.aspose.diagram/svgsaveoptions\#getQuality--) |
| [setSVGFitToViewPort(boolean value)](#setSVGFitToViewPort-boolean-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getSVGFitToViewPort()](../../com.aspose.diagram/svgsaveoptions\#getSVGFitToViewPort--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getSaveFormat()](../../com.aspose.diagram/saveoptions\#getSaveFormat--) |
| [setSavingCustomLinePattern(boolean value)](#setSavingCustomLinePattern-boolean-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [isSavingCustomLinePattern()](../../com.aspose.diagram/svgsaveoptions\#isSavingCustomLinePattern--) |
| [setSavingImageSeparately(boolean value)](#setSavingImageSeparately-boolean-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [isSavingImageSeparately()](../../com.aspose.diagram/svgsaveoptions\#isSavingImageSeparately--) |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SVGSaveOptions() {#SVGSaveOptions--}
```
public SVGSaveOptions()
```


इस वर्ग का एक नया उदाहरण प्रारंभ करता है जिसका उपयोग Aspose.Diagram.SaveFileFormat प्रारूप में दस्तावेज़ सहेजने के लिए किया जा सकता है।

### createSaveOptions(int saveFormat) {#createSaveOptions-int-}
```
public static SaveOptions createSaveOptions(int saveFormat)
```


निर्दिष्ट सहेजने के प्रारूप के लिए उपयुक्त वर्ग की एक सहेजने विकल्प वस्तु बनाता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| saveFormat | int | Aspose.Diagram.SaveFileFormat जिसके लिए एक सहेज विकल्प वस्तु बनानी है। |

**Returns:**
[SaveOptions](../../com.aspose.diagram/saveoptions) - An object of a class that derives from [SaveOptions](../../com.aspose.diagram/saveoptions).
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
### getCustomImagePath() {#getCustomImagePath--}
```
public String getCustomImagePath()
```


उपयोगकर्ता द्वारा निर्धारित कस्टम पाथ (URL) उत्पन्न SVG फ़ाइल में छवि के लिए सहेजा जाता है। यदि उपयोगकर्ता द्वारा परिभाषित नहीं किया गया, तो वर्तमान डायरेक्टरी का उपयोग किया जाएगा।

**Returns:**
java.lang.String
### getDefaultFont() {#getDefaultFont--}
```
public String getDefaultFont()
```


जब आरेख में अक्षर यूनिकोड हों और सही फ़ॉन्ट मान सेट न किया गया हो या फ़ॉन्ट स्थानीय रूप से स्थापित न हो, तो वे PDF, छवि या XPS में ब्लॉक के रूप में दिख सकते हैं। इन अक्षरों को दिखाने के लिए MingLiu या MS Gothic जैसे DefaultFont सेट करें।

**Returns:**
java.lang.String
### getEmfRenderSetting() {#getEmfRenderSetting--}
```
public int getEmfRenderSetting()
```


EMF मेटाफाइल को रेंडर करने के लिए सेटिंग। "EMF+ Dual" के रूप में पहचाने गए EMF मेटाफाइल दोनों EMF+ रिकॉर्ड और EMF रिकॉर्ड रख सकते हैं। इन दोनों प्रकार के रिकॉर्ड का उपयोग छवि को रेंडर करने के लिए किया जा सकता है, केवल EMF+ रिकॉर्ड, या केवल EMF रिकॉर्ड। जब EmfPlusPrefer सेट किया जाता है, तो EMF+ रिकॉर्ड पार्स किए जाएंगे, अन्यथा केवल EMF रिकॉर्ड पार्स किए जाएंगे। डिफ़ॉल्ट मान EmfOnly है"/>.

**Returns:**
int
### getEnlargePage() {#getEnlargePage--}
```
public boolean getEnlargePage()
```


निर्दिष्ट करता है कि पृष्ठ को बड़ा किया जाए या नहीं। यदि true है - पृष्ठ बड़ा किया जाएगा। यदि false है - पृष्ठ बड़ा नहीं किया जाएगा। डिफ़ॉल्ट मान true है।

**Returns:**
बूलियन
### getExportElementAsRectTag() {#getExportElementAsRectTag--}
```
public boolean getExportElementAsRectTag()
```


निर्धारित करता है कि आयताकार तत्वों को rect टैग के रूप में निर्यात करना आवश्यक है या नहीं। डिफ़ॉल्ट मान false है।

**Returns:**
बूलियन
### getExportGuideShapes() {#getExportGuideShapes--}
```
public boolean getExportGuideShapes()
```


निर्धारित करता है कि गाइड आकारों को निर्यात करने की आवश्यकता है या नहीं। डिफ़ॉल्ट मान true है।

**Returns:**
बूलियन
### getExportHiddenPage() {#getExportHiddenPage--}
```
public boolean getExportHiddenPage()
```


निर्धारित करता है कि छिपे पृष्ठ को निर्यात करने की आवश्यकता है या नहीं। डिफ़ॉल्ट मान true है।

**Returns:**
बूलियन
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


रेंडर करने के लिए पृष्ठ का 0-आधारित इंडेक्स। डिफ़ॉल्ट 0 है।

**Returns:**
int
### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


जनरेट किए गए चित्रों के लिए पृष्ठ आकार। यह [PageSize](../../com.aspose.diagram/pagesize) या null हो सकता है। डिफ़ॉल्ट मान null है। यदि PageSize null है तो जनरेट किए गए चित्र का पृष्ठ आकार स्रोत आरेख से प्राप्त किया जाता है।

**Returns:**
[PageSize](../../com.aspose.diagram/pagesize)
### getQuality() {#getQuality--}
```
public int getQuality()
```


एक मान जो उत्पन्न छवियों की गुणवत्ता निर्धारित करता है और केवल JPEG फ़ॉर्मेट में पृष्ठों को सहेजते समय लागू होता है। डिफ़ॉल्ट मान 100 है और यह केवल JPEG में सहेजते समय प्रभावी होता है। मान 0 से 100 के बीच होना चाहिए। डिफ़ॉल्ट मान 100 है।

**Returns:**
int
### getSVGFitToViewPort() {#getSVGFitToViewPort--}
```
public boolean getSVGFitToViewPort()
```


यदि यह गुण true है, तो उत्पन्न SVG व्यूपोर्ट में फिट हो जाएगा।

**Returns:**
बूलियन
### getSaveFormat() {#getSaveFormat--}
```
public int getSaveFormat()
```


यदि इस save options ऑब्जेक्ट का उपयोग किया जाता है तो दस्तावेज़ को जिस प्रारूप में सहेजा जाएगा, वह निर्दिष्ट करता है।

**Returns:**
int
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


रेंडर करने के लिए आकार। डिफ़ॉल्ट गणना 0 है।

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getWarningCallback() {#getWarningCallback--}
```
public IWarningCallback getWarningCallback()
```


चेतावनी कॉलबैक।

**Returns:**
[IWarningCallback](../../com.aspose.diagram/iwarningcallback)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isExportComments() {#isExportComments--}
```
public boolean isExportComments()
```


निर्धारित करता है कि टिप्पणी निर्यात करनी है या नहीं। डिफ़ॉल्ट मान false है।

**Returns:**
बूलियन
### isExportScaleInMatrix() {#isExportScaleInMatrix--}
```
public boolean isExportScaleInMatrix()
```


निर्धारित करता है कि मैट्रिक्स में स्केल निर्यात करना आवश्यक है या नहीं। डिफ़ॉल्ट मान true है।

**Returns:**
बूलियन
### isSavingCustomLinePattern() {#isSavingCustomLinePattern--}
```
public boolean isSavingCustomLinePattern()
```


परिभाषित करता है कि कस्टम लाइन पैटर्न सहेजा जाए या नहीं।

**Returns:**
बूलियन
### isSavingImageSeparately() {#isSavingImageSeparately--}
```
public boolean isSavingImageSeparately()
```


परिभाषित करता है कि छवि को अलग से सहेजा जाए या नहीं।

**Returns:**
बूलियन
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setCustomImagePath(String value) {#setCustomImagePath-java.lang.String-}
```
public void setCustomImagePath(String value)
```


इस गुण के विवरण के लिए, कृपया देखें [getCustomImagePath()](../../com.aspose.diagram/svgsaveoptions\#getCustomImagePath--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public void setDefaultFont(String value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setEmfRenderSetting(int value) {#setEmfRenderSetting-int-}
```
public void setEmfRenderSetting(int value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setEnlargePage(boolean value) {#setEnlargePage-boolean-}
```
public void setEnlargePage(boolean value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### setExportComments(boolean value) {#setExportComments-boolean-}
```
public void setExportComments(boolean value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### setExportElementAsRectTag(boolean value) {#setExportElementAsRectTag-boolean-}
```
public void setExportElementAsRectTag(boolean value)
```


इस गुण के विवरण के लिए, कृपया देखें [getExportElementAsRectTag()](../../com.aspose.diagram/svgsaveoptions\#getExportElementAsRectTag--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### setExportGuideShapes(boolean value) {#setExportGuideShapes-boolean-}
```
public void setExportGuideShapes(boolean value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### setExportHiddenPage(boolean value) {#setExportHiddenPage-boolean-}
```
public void setExportHiddenPage(boolean value)
```


इस गुण के विवरण के लिए, कृपया देखें [getExportHiddenPage()](../../com.aspose.diagram/svgsaveoptions\#getExportHiddenPage--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### setExportScaleInMatrix(boolean value) {#setExportScaleInMatrix-boolean-}
```
public void setExportScaleInMatrix(boolean value)
```


इस गुण के विवरण के लिए, कृपया देखें [isExportScaleInMatrix()](../../com.aspose.diagram/svgsaveoptions\#isExportScaleInMatrix--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


इस गुण के विवरण के लिए, कृपया देखें [getPageIndex()](../../com.aspose.diagram/svgsaveoptions\#getPageIndex--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setPageSize(PageSize value) {#setPageSize-com.aspose.diagram.PageSize-}
```
public void setPageSize(PageSize value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [PageSize](../../com.aspose.diagram/pagesize) |  |

### setQuality(int value) {#setQuality-int-}
```
public void setQuality(int value)
```


इस गुण के विवरण के लिए, कृपया देखें [getQuality()](../../com.aspose.diagram/svgsaveoptions\#getQuality--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setSVGFitToViewPort(boolean value) {#setSVGFitToViewPort-boolean-}
```
public void setSVGFitToViewPort(boolean value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getSVGFitToViewPort()](../../com.aspose.diagram/svgsaveoptions\#getSVGFitToViewPort--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getSaveFormat()](../../com.aspose.diagram/saveoptions\#getSaveFormat--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setSavingCustomLinePattern(boolean value) {#setSavingCustomLinePattern-boolean-}
```
public void setSavingCustomLinePattern(boolean value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [isSavingCustomLinePattern()](../../com.aspose.diagram/svgsaveoptions\#isSavingCustomLinePattern--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### setSavingImageSeparately(boolean value) {#setSavingImageSeparately-boolean-}
```
public void setSavingImageSeparately(boolean value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [isSavingImageSeparately()](../../com.aspose.diagram/svgsaveoptions\#isSavingImageSeparately--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### setShapes(ShapeCollection value) {#setShapes-com.aspose.diagram.ShapeCollection-}
```
public void setShapes(ShapeCollection value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [ShapeCollection](../../com.aspose.diagram/shapecollection) |  |

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.diagram.IWarningCallback-}
```
public void setWarningCallback(IWarningCallback value)
```




**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.diagram/iwarningcallback) |  |

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

