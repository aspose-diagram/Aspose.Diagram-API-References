---
title: HTMLSaveOptions
second_title: Aspose.Diagram for Java API Reference
description: डायग्राम पृष्ठों को HTML में रेंडर करते समय अतिरिक्त विकल्प निर्दिष्ट करने की अनुमति देता है।
type: docs
weight: 187
url: /hi/java/com.aspose.diagram/htmlsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class HTMLSaveOptions extends RenderingSaveOptions
```

डायग्राम पृष्ठों को HTML में रेंडर करते समय अतिरिक्त विकल्प निर्दिष्ट करने की अनुमति देता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [HTMLSaveOptions()](#HTMLSaveOptions--) | इस वर्ग का एक नया उदाहरण प्रारंभ करता है जिसका उपयोग Aspose.Diagram.SaveFileFormat प्रारूप में दस्तावेज़ सहेजने के लिए किया जा सकता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | निर्दिष्ट सहेजने के प्रारूप के लिए उपयुक्त वर्ग की एक सहेजने विकल्प वस्तु बनाता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultFont()](#getDefaultFont--) | जब आरेख में अक्षर यूनिकोड होते हैं और सही फ़ॉन्ट मान सेट नहीं किया गया हो या फ़ॉन्ट स्थानीय रूप से स्थापित न हो, तो वे पीडीएफ, छवि या XPS में ब्लॉक के रूप में दिखाई दे सकते हैं। |
| [getEmfRenderSetting()](#getEmfRenderSetting--) | Emf मेटाफाइल रेंडरिंग के लिए सेटिंग। |
| [getEnlargePage()](#getEnlargePage--) | निर्दिष्ट करता है कि पृष्ठ को बड़ा किया जाए या नहीं। |
| [getExportGuideShapes()](#getExportGuideShapes--) | निर्धारित करता है कि गाइड आकारों को निर्यात करने की आवश्यकता है या नहीं। |
| [getExportHiddenPage()](#getExportHiddenPage--) | निर्धारित करता है कि छिपे पृष्ठ को निर्यात करने की आवश्यकता है या नहीं। |
| [getPageCount()](#getPageCount--) | HTML में रेंडर करने के पृष्ठों की संख्या। |
| [getPageIndex()](#getPageIndex--) | रेंडर करने के पहले पृष्ठ का 0-आधारित सूचकांक। |
| [getPageSize()](#getPageSize--) | जनरेट किए गए चित्रों के लिए पृष्ठ आकार। |
| [getResolution()](#getResolution--) | जनरेट किए गए HTML की रिज़ॉल्यूशन, डॉट्स प्रति इंच में। |
| [getSaveAsSingleFile()](#getSaveAsSingleFile--) | निर्देशित करता है कि HTML को एकल फ़ाइल के रूप में सहेजा जाए या नहीं। |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | निर्दिष्ट करता है कि सभी पृष्ठ छवि में सहेजे जाएंगे या केवल अग्रभूमि। |
| [getSaveFormat()](#getSaveFormat--) | यदि इस सहेजने विकल्प वस्तु का उपयोग किया जाता है तो रेंडर किए गए आरेख पृष्ठों को किस प्रारूप में सहेजा जाएगा, यह निर्दिष्ट करता है। |
| [getSaveTitle()](#getSaveTitle--) | निर्धारित करता है कि शीर्षक को निर्यात करने की आवश्यकता है या नहीं। |
| [getSaveToolBar()](#getSaveToolBar--) | निर्दिष्ट करता है कि टूलबार सहेजा जाए या नहीं। डिफ़ॉल्ट मान true है। |
| [getShapes()](#getShapes--) | रेंडर करने के लिए आकार। |
| [getStreamProvider()](#getStreamProvider--) | वस्तुओं को निर्यात करने के लिए IStreamProvider। |
| [getTitle()](#getTitle--) | HTML में रेंडर करने के लिए आरेख का शीर्षक। |
| [getWarningCallback()](#getWarningCallback--) | चेतावनी कॉलबैक। |
| [hashCode()](#hashCode--) |  |
| [isExportComments()](#isExportComments--) | निर्धारित करता है कि टिप्पणियों को निर्यात करने की आवश्यकता है या नहीं। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setEmfRenderSetting(int value)](#setEmfRenderSetting-int-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--) |
| [setEnlargePage(boolean value)](#setEnlargePage-boolean-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--) |
| [setExportComments(boolean value)](#setExportComments-boolean-) | इस गुण का विवरण देखने के लिए, कृपया देखें [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--) |
| [setExportGuideShapes(boolean value)](#setExportGuideShapes-boolean-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--) |
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getExportHiddenPage()](../../com.aspose.diagram/htmlsaveoptions\#getExportHiddenPage--) |
| [setPageCount(int value)](#setPageCount-int-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getPageCount()](../../com.aspose.diagram/htmlsaveoptions\#getPageCount--) |
| [setPageIndex(int value)](#setPageIndex-int-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getPageIndex()](../../com.aspose.diagram/htmlsaveoptions\#getPageIndex--) |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) |
| [setResolution(int value)](#setResolution-int-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getResolution()](../../com.aspose.diagram/htmlsaveoptions\#getResolution--) |
| [setSaveAsSingleFile(boolean value)](#setSaveAsSingleFile-boolean-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getSaveAsSingleFile()](../../com.aspose.diagram/htmlsaveoptions\#getSaveAsSingleFile--) |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getSaveForegroundPagesOnly()](../../com.aspose.diagram/htmlsaveoptions\#getSaveForegroundPagesOnly--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getSaveFormat()](../../com.aspose.diagram/htmlsaveoptions\#getSaveFormat--) |
| [setSaveTitle(boolean value)](#setSaveTitle-boolean-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getSaveTitle()](../../com.aspose.diagram/htmlsaveoptions\#getSaveTitle--) |
| [setSaveToolBar(boolean value)](#setSaveToolBar-boolean-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getSaveToolBar()](../../com.aspose.diagram/htmlsaveoptions\#getSaveToolBar--) |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) |
| [setStreamProvider(IStreamProvider value)](#setStreamProvider-com.aspose.diagram.IStreamProvider-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getStreamProvider()](../../com.aspose.diagram/htmlsaveoptions\#getStreamProvider--) |
| [setTitle(String value)](#setTitle-java.lang.String-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getTitle()](../../com.aspose.diagram/htmlsaveoptions\#getTitle--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HTMLSaveOptions() {#HTMLSaveOptions--}
```
public HTMLSaveOptions()
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
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


HTML में रेंडर करने के लिए पृष्ठों की संख्या। डिफ़ॉल्ट MaxValue है, जिसका अर्थ है आरेख के सभी पृष्ठ रेंडर किए जाएंगे।

**Returns:**
int
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


रेंडर करने के पहले पृष्ठ का 0-आधारित सूचकांक। डिफ़ॉल्ट 0 है।

**Returns:**
int
### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


जनरेट किए गए चित्रों के लिए पृष्ठ आकार। यह [PageSize](../../com.aspose.diagram/pagesize) या null हो सकता है। डिफ़ॉल्ट मान null है। यदि PageSize null है तो जनरेट किए गए चित्र का पृष्ठ आकार स्रोत आरेख से प्राप्त किया जाता है।

**Returns:**
[PageSize](../../com.aspose.diagram/pagesize)
### getResolution() {#getResolution--}
```
public int getResolution()
```


जनरेट किए गए HTML की रिज़ॉल्यूशन, डॉट्स प्रति इंच में। यह प्रॉपर्टी केवल HTML में सहेजते समय प्रभावी होती है। डिफ़ॉल्ट मान 96 है।

**Returns:**
int
### getSaveAsSingleFile() {#getSaveAsSingleFile--}
```
public boolean getSaveAsSingleFile()
```


यह दर्शाता है कि HTML को एकल फ़ाइल के रूप में सहेजा जाए या नहीं। डिफ़ॉल्ट मान false है। यदि कई पृष्ठ हैं, तो उन पृष्ठों और अन्य संसाधनों को अलग-अलग फ़ाइलों में सहेजना होगा। कुछ परिस्थितियों में, उपयोगकर्ता को केवल एक परिणाम फ़ाइल चाहिए हो सकती है, जैसे स्थानांतरण की सुविधा के लिए। ऐसे में उपयोगकर्ता इस प्रॉपर्टी को true सेट कर सकता है।

**Returns:**
बूलियन
### getSaveForegroundPagesOnly() {#getSaveForegroundPagesOnly--}
```
public boolean getSaveForegroundPagesOnly()
```


निर्दिष्ट करता है कि सभी पृष्ठ छवि में सहेजे जाएंगे या केवल अग्रभूमि। यदि true है - केवल अग्रभूमि पृष्ठ (यदि पृष्ठभूमि मौजूद है तो उसके साथ) रेंडर किए जाते हैं। यदि false है - अग्रभूमि पृष्ठ (यदि पृष्ठभूमि मौजूद है तो उसके साथ) रेंडर होते हैं, उसके बाद खाली पृष्ठभूमि पृष्ठ। यह केवल तब true लौट सकता है जब PageCount > 1 हो। डिफ़ॉल्ट मान false है।

**Returns:**
बूलियन
### getSaveFormat() {#getSaveFormat--}
```
public int getSaveFormat()
```


यदि इस सहेजने विकल्प वस्तु का उपयोग किया जाता है तो रेंडर किए गए आरेख पृष्ठों को किस फ़ॉर्मेट में सहेजा जाएगा, यह निर्दिष्ट करता है। यह केवल Aspose.Diagram.SaveFileFormat हो सकता है।

**Returns:**
int
### getSaveTitle() {#getSaveTitle--}
```
public boolean getSaveTitle()
```


निर्धारित करता है कि शीर्षक निर्यात करना आवश्यक है या नहीं। डिफ़ॉल्ट मान true है।

**Returns:**
बूलियन
### getSaveToolBar() {#getSaveToolBar--}
```
public boolean getSaveToolBar()
```


निर्दिष्ट करता है कि टूलबार सहेजा जाए या नहीं। डिफ़ॉल्ट मान true है।

**Returns:**
बूलियन
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


रेंडर करने के लिए आकार। डिफ़ॉल्ट गणना 0 है।

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getStreamProvider() {#getStreamProvider--}
```
public IStreamProvider getStreamProvider()
```


वस्तुओं को निर्यात करने के लिए IStreamProvider।

**Returns:**
[IStreamProvider](../../com.aspose.diagram/istreamprovider)
### getTitle() {#getTitle--}
```
public String getTitle()
```


HTML में रेंडर करने के लिए आरेख का शीर्षक। यदि Title null है तो Diagram.DocumentProperties.Title [DocumentProperties](../../com.aspose.diagram/documentproperties) को शीर्षक के रूप में उपयोग किया जाएगा। यदि Diagram.DocumentProperties.Title null या खाली है तो आरेख की फ़ाइल नाम को शीर्षक के रूप में उपयोग किया जाएगा।

**Returns:**
java.lang.String
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
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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


इस गुण का विवरण देखने के लिए, कृपया देखें [getExportHiddenPage()](../../com.aspose.diagram/htmlsaveoptions\#getExportHiddenPage--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getPageCount()](../../com.aspose.diagram/htmlsaveoptions\#getPageCount--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getPageIndex()](../../com.aspose.diagram/htmlsaveoptions\#getPageIndex--)

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

### setResolution(int value) {#setResolution-int-}
```
public void setResolution(int value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getResolution()](../../com.aspose.diagram/htmlsaveoptions\#getResolution--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setSaveAsSingleFile(boolean value) {#setSaveAsSingleFile-boolean-}
```
public void setSaveAsSingleFile(boolean value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getSaveAsSingleFile()](../../com.aspose.diagram/htmlsaveoptions\#getSaveAsSingleFile--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getSaveForegroundPagesOnly()](../../com.aspose.diagram/htmlsaveoptions\#getSaveForegroundPagesOnly--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getSaveFormat()](../../com.aspose.diagram/htmlsaveoptions\#getSaveFormat--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setSaveTitle(boolean value) {#setSaveTitle-boolean-}
```
public void setSaveTitle(boolean value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getSaveTitle()](../../com.aspose.diagram/htmlsaveoptions\#getSaveTitle--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### setSaveToolBar(boolean value) {#setSaveToolBar-boolean-}
```
public void setSaveToolBar(boolean value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getSaveToolBar()](../../com.aspose.diagram/htmlsaveoptions\#getSaveToolBar--)

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

### setStreamProvider(IStreamProvider value) {#setStreamProvider-com.aspose.diagram.IStreamProvider-}
```
public void setStreamProvider(IStreamProvider value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getStreamProvider()](../../com.aspose.diagram/htmlsaveoptions\#getStreamProvider--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [IStreamProvider](../../com.aspose.diagram/istreamprovider) |  |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getTitle()](../../com.aspose.diagram/htmlsaveoptions\#getTitle--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

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

