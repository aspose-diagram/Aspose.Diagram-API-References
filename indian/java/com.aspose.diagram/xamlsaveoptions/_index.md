---
title: XAMLSaveOptions
second_title: Aspose.Diagram for Java API Reference
description: डायग्राम पृष्ठों को XAML में रेंडर करते समय अतिरिक्त विकल्प निर्दिष्ट करने की अनुमति देता है।
type: docs
weight: 448
url: /hi/java/com.aspose.diagram/xamlsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions)
```
public class XAMLSaveOptions extends SaveOptions
```

डायग्राम पृष्ठों को XAML में रेंडर करते समय अतिरिक्त विकल्प निर्दिष्ट करने की अनुमति देता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [XAMLSaveOptions()](#XAMLSaveOptions--) | इस वर्ग का एक नया उदाहरण प्रारंभ करता है जिसका उपयोग Aspose.Diagram.SaveFileFormat प्रारूप में दस्तावेज़ सहेजने के लिए किया जा सकता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | निर्दिष्ट सहेजने के प्रारूप के लिए उपयुक्त वर्ग की एक सहेजने विकल्प वस्तु बनाता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultFont()](#getDefaultFont--) | जब आरेख में अक्षर यूनिकोड होते हैं और सही फ़ॉन्ट मान सेट नहीं किया गया हो या फ़ॉन्ट स्थानीय रूप से स्थापित न हो, तो वे पीडीएफ, छवि या XPS में ब्लॉक के रूप में दिखाई दे सकते हैं। |
| [getPageCount()](#getPageCount--) | XAML में रेंडर करने के लिए पृष्ठों की संख्या। |
| [getPageIndex()](#getPageIndex--) | रेंडर करने के पहले पृष्ठ का 0-आधारित सूचकांक। |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | निर्दिष्ट करता है कि सभी पृष्ठ छवि में सहेजे जाएंगे या केवल अग्रभूमि। |
| [getSaveFormat()](#getSaveFormat--) | यदि इस सहेजने विकल्प वस्तु का उपयोग किया जाता है तो रेंडर किए गए आरेख पृष्ठों को किस प्रारूप में सहेजा जाएगा, यह निर्दिष्ट करता है। |
| [getStreamProvider()](#getStreamProvider--) | वस्तुओं को निर्यात करने के लिए IStreamProvider। |
| [getWarningCallback()](#getWarningCallback--) | चेतावनी कॉलबैक। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setPageCount(int value)](#setPageCount-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getPageCount()](../../com.aspose.diagram/xamlsaveoptions\#getPageCount--) |
| [setPageIndex(int value)](#setPageIndex-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getPageIndex()](../../com.aspose.diagram/xamlsaveoptions\#getPageIndex--) |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getSaveForegroundPagesOnly()](../../com.aspose.diagram/xamlsaveoptions\#getSaveForegroundPagesOnly--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getSaveFormat()](../../com.aspose.diagram/xamlsaveoptions\#getSaveFormat--) |
| [setStreamProvider(IStreamProvider value)](#setStreamProvider-com.aspose.diagram.IStreamProvider-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getStreamProvider()](../../com.aspose.diagram/xamlsaveoptions\#getStreamProvider--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XAMLSaveOptions() {#XAMLSaveOptions--}
```
public XAMLSaveOptions()
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
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


XAML में रेंडर करने के लिए पृष्ठों की संख्या। डिफ़ॉल्ट MaxValue है, जिसका अर्थ है कि आरेख के सभी पृष्ठ रेंडर किए जाएंगे।

**Returns:**
int
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


रेंडर करने के पहले पृष्ठ का 0-आधारित सूचकांक। डिफ़ॉल्ट 0 है।

**Returns:**
int
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
### getStreamProvider() {#getStreamProvider--}
```
public IStreamProvider getStreamProvider()
```


वस्तुओं को निर्यात करने के लिए IStreamProvider।

**Returns:**
[IStreamProvider](../../com.aspose.diagram/istreamprovider)
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

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getPageCount()](../../com.aspose.diagram/xamlsaveoptions\#getPageCount--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getPageIndex()](../../com.aspose.diagram/xamlsaveoptions\#getPageIndex--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getSaveForegroundPagesOnly()](../../com.aspose.diagram/xamlsaveoptions\#getSaveForegroundPagesOnly--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getSaveFormat()](../../com.aspose.diagram/xamlsaveoptions\#getSaveFormat--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setStreamProvider(IStreamProvider value) {#setStreamProvider-com.aspose.diagram.IStreamProvider-}
```
public void setStreamProvider(IStreamProvider value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getStreamProvider()](../../com.aspose.diagram/xamlsaveoptions\#getStreamProvider--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [IStreamProvider](../../com.aspose.diagram/istreamprovider) |  |

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

