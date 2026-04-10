---
title: RenderingSaveOptions
second_title: Aspose.Diagram for Java API Reference
description: यह एक सारभूत बेस क्लास है उन क्लासों के लिए जो उपयोगकर्ता को किसी विशेष स्वरूप में डायग्राम सहेजते समय अतिरिक्त विकल्प निर्दिष्ट करने की अनुमति देती हैं।
type: docs
weight: 327
url: /hi/java/com.aspose.diagram/renderingsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions)
```
public abstract class RenderingSaveOptions extends SaveOptions
```

यह एक सारभूत बेस क्लास है उन क्लासों के लिए जो उपयोगकर्ता को किसी विशेष स्वरूप में डायग्राम सहेजते समय अतिरिक्त विकल्प निर्दिष्ट करने की अनुमति देती हैं।
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
| [getPageSize()](#getPageSize--) | जनरेट किए गए चित्रों के लिए पृष्ठ आकार। |
| [getSaveFormat()](#getSaveFormat--) | यदि इस save options ऑब्जेक्ट का उपयोग किया जाता है तो दस्तावेज़ को जिस प्रारूप में सहेजा जाएगा, वह निर्दिष्ट करता है। |
| [getShapes()](#getShapes--) | रेंडर करने के लिए आकार। |
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
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getSaveFormat()](../../com.aspose.diagram/saveoptions\#getSaveFormat--) |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


जनरेट किए गए चित्रों के लिए पृष्ठ आकार। यह [PageSize](../../com.aspose.diagram/pagesize) या null हो सकता है। डिफ़ॉल्ट मान null है। यदि PageSize null है तो जनरेट किए गए चित्र का पृष्ठ आकार स्रोत आरेख से प्राप्त किया जाता है।

**Returns:**
[PageSize](../../com.aspose.diagram/pagesize)
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

### setPageSize(PageSize value) {#setPageSize-com.aspose.diagram.PageSize-}
```
public void setPageSize(PageSize value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [PageSize](../../com.aspose.diagram/pagesize) |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getSaveFormat()](../../com.aspose.diagram/saveoptions\#getSaveFormat--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

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

