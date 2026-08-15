---
title: PdfSaveOptions
second_title: Aspose.Diagram for Java API Reference
description: डायग्राम पृष्ठों को PDF में रेंडर करते समय अतिरिक्त विकल्प निर्दिष्ट करने की अनुमति देता है।
type: docs
weight: 281
url: /hi/java/com.aspose.diagram/pdfsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class PdfSaveOptions extends RenderingSaveOptions
```

डायग्राम पृष्ठों को PDF में रेंडर करते समय अतिरिक्त विकल्प निर्दिष्ट करने की अनुमति देता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [PdfSaveOptions()](#PdfSaveOptions--) | इस वर्ग का एक नया उदाहरण प्रारंभ करता है जिसका उपयोग Aspose.Diagram.SaveFileFormat प्रारूप में दस्तावेज़ सहेजने के लिए किया जा सकता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | निर्दिष्ट सहेजने के प्रारूप के लिए उपयुक्त वर्ग की एक सहेजने विकल्प वस्तु बनाता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCompliance()](#getCompliance--) | जेनरेट किए गए PDF दस्तावेज़ के लिए वांछित अनुपालन स्तर। |
| [getDefaultFont()](#getDefaultFont--) | जब आरेख में अक्षर यूनिकोड होते हैं और सही फ़ॉन्ट मान सेट नहीं किया गया हो या फ़ॉन्ट स्थानीय रूप से स्थापित न हो, तो वे पीडीएफ, छवि या XPS में ब्लॉक के रूप में दिखाई दे सकते हैं। |
| [getEmfRenderSetting()](#getEmfRenderSetting--) | Emf मेटाफाइल रेंडरिंग के लिए सेटिंग। |
| [getEncryptionDetails()](#getEncryptionDetails--) | एक एन्क्रिप्शन विवरण। |
| [getEnlargePage()](#getEnlargePage--) | निर्दिष्ट करता है कि पृष्ठ को बड़ा किया जाए या नहीं। |
| [getExportGuideShapes()](#getExportGuideShapes--) | निर्धारित करता है कि गाइड आकारों को निर्यात करने की आवश्यकता है या नहीं। |
| [getExportHiddenPage()](#getExportHiddenPage--) | निर्धारित करता है कि छिपे पृष्ठ को निर्यात करने की आवश्यकता है या नहीं। |
| [getHorizontalResolution()](#getHorizontalResolution--) | उत्पन्न छवियों के लिए क्षैतिज रिज़ॉल्यूशन, डॉट्स प्रति इंच में। |
| [getJpegQuality()](#getJpegQuality--) | छवियों के लिए JPEG संपीड़न की गुणवत्ता निर्दिष्ट करता है (यदि JPEG संपीड़न उपयोग किया जाता है)। |
| [getPageCount()](#getPageCount--) | PDF में रेंडर करने के लिए पृष्ठों की संख्या। |
| [getPageIndex()](#getPageIndex--) | रेंडर करने के पहले पृष्ठ का 0-आधारित सूचकांक। |
| [getPageSavingCallback()](#getPageSavingCallback--) | पृष्ठ सहेजने की प्रक्रिया की प्रगति को नियंत्रित/संकेत करता है। |
| [getPageSize()](#getPageSize--) | जनरेट किए गए चित्रों के लिए पृष्ठ आकार। |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | निर्दिष्ट करता है कि सभी पृष्ठ छवि में सहेजे जाएंगे या केवल अग्रभूमि। |
| [getSaveFormat()](#getSaveFormat--) | यदि इस सहेजने विकल्प वस्तु का उपयोग किया जाता है तो रेंडर किए गए आरेख पृष्ठों को किस प्रारूप में सहेजा जाएगा, यह निर्दिष्ट करता है। |
| [getShapes()](#getShapes--) | रेंडर करने के लिए आकार। |
| [getSplitMultiPages()](#getSplitMultiPages--) | पृष्ठ की सेटिंग के अनुसार डायग्राम को कई पृष्ठों में विभाजित किया जाए या नहीं, यह निर्धारित करता है। |
| [getTextCompression()](#getTextCompression--) | छवियों को छोड़कर सभी कंटेंट स्ट्रीम्स के लिए उपयोग किए जाने वाले संपीड़न प्रकार को निर्दिष्ट करता है। |
| [getVerticalResolution()](#getVerticalResolution--) | उत्पन्न छवियों के लिए ऊर्ध्वाधर रिज़ॉल्यूशन, डॉट्स प्रति इंच में। |
| [getWarningCallback()](#getWarningCallback--) | चेतावनी कॉलबैक। |
| [hashCode()](#hashCode--) |  |
| [isExportComments()](#isExportComments--) | निर्धारित करता है कि टिप्पणियों को निर्यात करने की आवश्यकता है या नहीं। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompliance(int value)](#setCompliance-int-) | इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getCompliance()](../../com.aspose.diagram/pdfsaveoptions\\#getCompliance--) |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setEmfRenderSetting(int value)](#setEmfRenderSetting-int-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--) |
| [setEncryptionDetails(PdfEncryptionDetails value)](#setEncryptionDetails-com.aspose.diagram.PdfEncryptionDetails-) | इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getEncryptionDetails()](../../com.aspose.diagram/pdfsaveoptions\\#getEncryptionDetails--) |
| [setEnlargePage(boolean value)](#setEnlargePage-boolean-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--) |
| [setExportComments(boolean value)](#setExportComments-boolean-) | इस गुण का विवरण देखने के लिए, कृपया देखें [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--) |
| [setExportGuideShapes(boolean value)](#setExportGuideShapes-boolean-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--) |
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getExportHiddenPage()](../../com.aspose.diagram/pdfsaveoptions\\#getExportHiddenPage--) |
| [setHorizontalResolution(int value)](#setHorizontalResolution-int-) | इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getHorizontalResolution()](../../com.aspose.diagram/pdfsaveoptions\\#getHorizontalResolution--) |
| [setJpegQuality(int value)](#setJpegQuality-int-) | इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getJpegQuality()](../../com.aspose.diagram/pdfsaveoptions\\#getJpegQuality--) |
| [setPageCount(int value)](#setPageCount-int-) | इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getPageCount()](../../com.aspose.diagram/pdfsaveoptions\\#getPageCount--) |
| [setPageIndex(int value)](#setPageIndex-int-) | इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getPageIndex()](../../com.aspose.diagram/pdfsaveoptions\\#getPageIndex--) |
| [setPageSavingCallback(IPageSavingCallback value)](#setPageSavingCallback-com.aspose.diagram.IPageSavingCallback-) | इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getPageSavingCallback()](../../com.aspose.diagram/pdfsaveoptions\\#getPageSavingCallback--) |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getSaveForegroundPagesOnly()](../../com.aspose.diagram/pdfsaveoptions\\#getSaveForegroundPagesOnly--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getSaveFormat()](../../com.aspose.diagram/pdfsaveoptions\\#getSaveFormat--) |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) |
| [setSplitMultiPages(boolean value)](#setSplitMultiPages-boolean-) | इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getSplitMultiPages()](../../com.aspose.diagram/pdfsaveoptions\\#getSplitMultiPages--) |
| [setTextCompression(int value)](#setTextCompression-int-) | इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getTextCompression()](../../com.aspose.diagram/pdfsaveoptions\\#getTextCompression--) |
| [setVerticalResolution(int value)](#setVerticalResolution-int-) | इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getVerticalResolution()](../../com.aspose.diagram/pdfsaveoptions\\#getVerticalResolution--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
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
### getCompliance() {#getCompliance--}
```
public int getCompliance()
```


उत्पन्न PDF दस्तावेज़ के लिए वांछित अनुरूपता स्तर। डिफ़ॉल्ट है PdfCompliance.PDF\_15।

**Returns:**
int
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
### getEncryptionDetails() {#getEncryptionDetails--}
```
public PdfEncryptionDetails getEncryptionDetails()
```


एक एन्क्रिप्शन विवरण। यदि सेट नहीं किया गया, तो कोई एन्क्रिप्शन नहीं किया जाएगा।

**Returns:**
[PdfEncryptionDetails](../../com.aspose.diagram/pdfencryptiondetails)
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
### getHorizontalResolution() {#getHorizontalResolution--}
```
public int getHorizontalResolution()
```


उत्पन्न छवियों के लिए क्षैतिज रिज़ॉल्यूशन, डॉट्स प्रति इंच में। यह EMF फ़ॉर्मेट छवियों को छोड़कर इमेज जेनरेट करने की विधि पर लागू होता है। डिफ़ॉल्ट मान 96 है।

**Returns:**
int
### getJpegQuality() {#getJpegQuality--}
```
public int getJpegQuality()
```


छवियों के लिए JPEG संपीड़न की गुणवत्ता निर्दिष्ट करता है (यदि JPEG संपीड़न उपयोग किया जाता है)। डिफ़ॉल्ट 95 है।

**Returns:**
int
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


PDF में रेंडर करने के लिए पृष्ठों की संख्या। डिफ़ॉल्ट MaxValue है, जिसका अर्थ है कि डायग्राम के सभी पृष्ठ रेंडर किए जाएंगे।

**Returns:**
int
### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


रेंडर करने के पहले पृष्ठ का 0-आधारित सूचकांक। डिफ़ॉल्ट 0 है।

**Returns:**
int
### getPageSavingCallback() {#getPageSavingCallback--}
```
public IPageSavingCallback getPageSavingCallback()
```


पृष्ठ सहेजने की प्रक्रिया की प्रगति को नियंत्रित/संकेत करता है।

**Returns:**
[IPageSavingCallback](../../com.aspose.diagram/ipagesavingcallback)
### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


जनरेट किए गए चित्रों के लिए पृष्ठ आकार। यह [PageSize](../../com.aspose.diagram/pagesize) या null हो सकता है। डिफ़ॉल्ट मान null है। यदि PageSize null है तो जनरेट किए गए चित्र का पृष्ठ आकार स्रोत आरेख से प्राप्त किया जाता है।

**Returns:**
[PageSize](../../com.aspose.diagram/pagesize)
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
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


रेंडर करने के लिए आकार। डिफ़ॉल्ट गणना 0 है।

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getSplitMultiPages() {#getSplitMultiPages--}
```
public boolean getSplitMultiPages()
```


पृष्ठ की सेटिंग के अनुसार डायग्राम को कई पृष्ठों में विभाजित किया जाए या नहीं, यह निर्धारित करता है। डिफ़ॉल्ट मान false है।

**Returns:**
बूलियन
### getTextCompression() {#getTextCompression--}
```
public int getTextCompression()
```


सभी कंटेंट स्ट्रीम्स (छवियों को छोड़कर) के लिए उपयोग किए जाने वाले संपीड़न प्रकार को निर्दिष्ट करता है। डिफ़ॉल्ट है PdfTextCompression.FLATE।

**Returns:**
int
### getVerticalResolution() {#getVerticalResolution--}
```
public int getVerticalResolution()
```


जनरेट की गई छवियों के लिए ऊर्ध्वाधर रिज़ॉल्यूशन, डॉट्स प्रति इंच में। Emf फ़ॉर्मेट छवि को छोड़कर इमेज जनरेट करने की विधि पर लागू होता है। डिफ़ॉल्ट मान 96 है।

**Returns:**
int
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




### setCompliance(int value) {#setCompliance-int-}
```
public void setCompliance(int value)
```


इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getCompliance()](../../com.aspose.diagram/pdfsaveoptions\\#getCompliance--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

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

### setEncryptionDetails(PdfEncryptionDetails value) {#setEncryptionDetails-com.aspose.diagram.PdfEncryptionDetails-}
```
public void setEncryptionDetails(PdfEncryptionDetails value)
```


इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getEncryptionDetails()](../../com.aspose.diagram/pdfsaveoptions\\#getEncryptionDetails--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [PdfEncryptionDetails](../../com.aspose.diagram/pdfencryptiondetails) |  |

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


इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getExportHiddenPage()](../../com.aspose.diagram/pdfsaveoptions\\#getExportHiddenPage--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### setHorizontalResolution(int value) {#setHorizontalResolution-int-}
```
public void setHorizontalResolution(int value)
```


इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getHorizontalResolution()](../../com.aspose.diagram/pdfsaveoptions\\#getHorizontalResolution--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public void setJpegQuality(int value)
```


इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getJpegQuality()](../../com.aspose.diagram/pdfsaveoptions\\#getJpegQuality--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getPageCount()](../../com.aspose.diagram/pdfsaveoptions\\#getPageCount--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getPageIndex()](../../com.aspose.diagram/pdfsaveoptions\\#getPageIndex--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setPageSavingCallback(IPageSavingCallback value) {#setPageSavingCallback-com.aspose.diagram.IPageSavingCallback-}
```
public void setPageSavingCallback(IPageSavingCallback value)
```


इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getPageSavingCallback()](../../com.aspose.diagram/pdfsaveoptions\\#getPageSavingCallback--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [IPageSavingCallback](../../com.aspose.diagram/ipagesavingcallback) |  |

### setPageSize(PageSize value) {#setPageSize-com.aspose.diagram.PageSize-}
```
public void setPageSize(PageSize value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [PageSize](../../com.aspose.diagram/pagesize) |  |

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getSaveForegroundPagesOnly()](../../com.aspose.diagram/pdfsaveoptions\\#getSaveForegroundPagesOnly--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getSaveFormat()](../../com.aspose.diagram/pdfsaveoptions\\#getSaveFormat--)

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

### setSplitMultiPages(boolean value) {#setSplitMultiPages-boolean-}
```
public void setSplitMultiPages(boolean value)
```


इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getSplitMultiPages()](../../com.aspose.diagram/pdfsaveoptions\\#getSplitMultiPages--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### setTextCompression(int value) {#setTextCompression-int-}
```
public void setTextCompression(int value)
```


इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getTextCompression()](../../com.aspose.diagram/pdfsaveoptions\\#getTextCompression--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setVerticalResolution(int value) {#setVerticalResolution-int-}
```
public void setVerticalResolution(int value)
```


इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getVerticalResolution()](../../com.aspose.diagram/pdfsaveoptions\\#getVerticalResolution--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

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

