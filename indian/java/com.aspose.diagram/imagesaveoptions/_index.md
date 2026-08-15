---
title: ImageSaveOptions
second_title: Aspose.Diagram for Java API Reference
description: डायग्राम पृष्ठों को इमेज में रेंडर करते समय अतिरिक्त विकल्प निर्दिष्ट करने की अनुमति देता है।
type: docs
weight: 200
url: /hi/java/com.aspose.diagram/imagesaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions), [com.aspose.diagram.RenderingSaveOptions](../../com.aspose.diagram/renderingsaveoptions)
```
public class ImageSaveOptions extends RenderingSaveOptions
```

डायग्राम पृष्ठों को इमेज में रेंडर करते समय अतिरिक्त विकल्प निर्दिष्ट करने की अनुमति देता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [ImageSaveOptions(int saveFormat)](#ImageSaveOptions-int-) | इस क्लास का नया इंस्टेंस प्रारंभ करता है जिसका उपयोग Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat या Aspose.Diagram.SaveFileFormat फ़ॉर्मेट में रेंडर की गई छवियों को सहेजने के लिए किया जा सकता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | निर्दिष्ट सहेजने के प्रारूप के लिए उपयुक्त वर्ग की एक सहेजने विकल्प वस्तु बनाता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCompositingQuality()](#getCompositingQuality--) | कम्पोज़िटिंग के दौरान उपयोग किए जाने वाले क्वालिटी लेवल को निर्दिष्ट करता है। |
| [getContentZoom()](#getContentZoom--) | यह पैरामीटर स्केल के समान है, लेकिन उत्पन्न छवि आकार को प्रभावित नहीं करता। |
| [getDefaultFont()](#getDefaultFont--) | जब आरेख में अक्षर यूनिकोड होते हैं और सही फ़ॉन्ट मान सेट नहीं किया गया हो या फ़ॉन्ट स्थानीय रूप से स्थापित न हो, तो वे पीडीएफ, छवि या XPS में ब्लॉक के रूप में दिखाई दे सकते हैं। |
| [getEmfRenderSetting()](#getEmfRenderSetting--) | Emf मेटाफाइल रेंडरिंग के लिए सेटिंग। |
| [getEnlargePage()](#getEnlargePage--) | निर्दिष्ट करता है कि पृष्ठ को बड़ा किया जाए या नहीं। |
| [getExportGuideShapes()](#getExportGuideShapes--) | निर्धारित करता है कि गाइड आकारों को निर्यात करने की आवश्यकता है या नहीं। |
| [getExportHiddenPage()](#getExportHiddenPage--) | निर्धारित करता है कि छिपे पृष्ठ को निर्यात करने की आवश्यकता है या नहीं। |
| [getImageBrightness()](#getImageBrightness--) | उत्पन्न छवियों के लिए चमक। |
| [getImageColorMode()](#getImageColorMode--) | उत्पन्न छवियों के लिए रंग मोड। |
| [getImageContrast()](#getImageContrast--) | उत्पन्न छवियों के लिए कंट्रास्ट। |
| [getInterpolationMode()](#getInterpolationMode--) | छवियों को स्केल या घुमाते समय उपयोग किए जाने वाले एल्गोरिद्म को निर्दिष्ट करता है। |
| [getJpegQuality()](#getJpegQuality--) | उत्पन्न JPEG छवियों की गुणवत्ता निर्धारित करने वाला मान। |
| [getPageCount()](#getPageCount--) | बहु‑पृष्ठ TIFF फ़ाइल में सहेजते समय रेंडर करने के लिए पृष्ठों की संख्या। |
| [getPageIndex()](#getPageIndex--) | रेंडर करने के पहले पृष्ठ का 0-आधारित सूचकांक। |
| [getPageSize()](#getPageSize--) | जनरेट किए गए चित्रों के लिए पृष्ठ आकार। |
| [getPixelOffsetMode()](#getPixelOffsetMode--) | रेंडरिंग के दौरान पिक्सेल कैसे ऑफ़सेट होते हैं, यह निर्दिष्ट करने वाला मान। |
| [getResolution()](#getResolution--) | उत्पन्न छवियों का रिज़ॉल्यूशन, डॉट्स प्रति इंच में। |
| [getSameAsPdfConversionArea()](#getSameAsPdfConversionArea--) | निर्दिष्ट करता है कि क्या सहेजने का क्षेत्र PDF के समान है। |
| [getSaveForegroundPagesOnly()](#getSaveForegroundPagesOnly--) | निर्दिष्ट करता है कि सभी पृष्ठ छवि में सहेजे जाएंगे या केवल अग्रभूमि। |
| [getSaveFormat()](#getSaveFormat--) | यदि इस सहेजने विकल्प वस्तु का उपयोग किया जाता है तो रेंडर किए गए आरेख पृष्ठों को किस प्रारूप में सहेजा जाएगा, यह निर्दिष्ट करता है। |
| [getScale()](#getScale--) | उत्पन्न छवियों के लिए ज़ूम फ़ैक्टर। |
| [getShapes()](#getShapes--) | रेंडर करने के लिए आकार। |
| [getSmoothingMode()](#getSmoothingMode--) | निर्दिष्ट करता है कि रेखाओं, वक्रों और भरे हुए क्षेत्रों के किनारों पर स्मूदिंग (एंटीएलियासिंग) लागू है या नहीं। |
| [getTiffCompression()](#getTiffCompression--) | TIFF फ़ॉर्मेट में उत्पन्न छवियों को सहेजते समय लागू करने के लिए संपीड़न का प्रकार। |
| [getWarningCallback()](#getWarningCallback--) | चेतावनी कॉलबैक। |
| [hashCode()](#hashCode--) |  |
| [isExportComments()](#isExportComments--) | निर्धारित करता है कि टिप्पणियों को निर्यात करने की आवश्यकता है या नहीं। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompositingQuality(int value)](#setCompositingQuality-int-) | इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getCompositingQuality()](../../com.aspose.diagram/imagesaveoptions\#getCompositingQuality--) |
| [setContentZoom(float value)](#setContentZoom-float-) | इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getContentZoom()](../../com.aspose.diagram/imagesaveoptions\#getContentZoom--) |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setEmfRenderSetting(int value)](#setEmfRenderSetting-int-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getEmfRenderSetting()](../../com.aspose.diagram/renderingsaveoptions\#getEmfRenderSetting--) |
| [setEnlargePage(boolean value)](#setEnlargePage-boolean-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getEnlargePage()](../../com.aspose.diagram/renderingsaveoptions\#getEnlargePage--) |
| [setExportComments(boolean value)](#setExportComments-boolean-) | इस गुण का विवरण देखने के लिए, कृपया देखें [isExportComments()](../../com.aspose.diagram/renderingsaveoptions\#isExportComments--) |
| [setExportGuideShapes(boolean value)](#setExportGuideShapes-boolean-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getExportGuideShapes()](../../com.aspose.diagram/renderingsaveoptions\#getExportGuideShapes--) |
| [setExportHiddenPage(boolean value)](#setExportHiddenPage-boolean-) | इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getExportHiddenPage()](../../com.aspose.diagram/imagesaveoptions\#getExportHiddenPage--) |
| [setImageBrightness(float value)](#setImageBrightness-float-) | इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getImageBrightness()](../../com.aspose.diagram/imagesaveoptions\#getImageBrightness--) |
| [setImageColorMode(int value)](#setImageColorMode-int-) | इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getImageColorMode()](../../com.aspose.diagram/imagesaveoptions\#getImageColorMode--) |
| [setImageContrast(float value)](#setImageContrast-float-) | इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getImageContrast()](../../com.aspose.diagram/imagesaveoptions\#getImageContrast--) |
| [setInterpolationMode(int value)](#setInterpolationMode-int-) | इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getInterpolationMode()](../../com.aspose.diagram/imagesaveoptions\#getInterpolationMode--) |
| [setJpegQuality(int value)](#setJpegQuality-int-) | इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getJpegQuality()](../../com.aspose.diagram/imagesaveoptions\#getJpegQuality--) |
| [setPageCount(int value)](#setPageCount-int-) | इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getPageCount()](../../com.aspose.diagram/imagesaveoptions\#getPageCount--) |
| [setPageIndex(int value)](#setPageIndex-int-) | इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getPageIndex()](../../com.aspose.diagram/imagesaveoptions\#getPageIndex--) |
| [setPageSize(PageSize value)](#setPageSize-com.aspose.diagram.PageSize-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getPageSize()](../../com.aspose.diagram/renderingsaveoptions\#getPageSize--) |
| [setPixelOffsetMode(int value)](#setPixelOffsetMode-int-) | इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getPixelOffsetMode()](../../com.aspose.diagram/imagesaveoptions\#getPixelOffsetMode--) |
| [setResolution(float value)](#setResolution-float-) | इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getResolution()](../../com.aspose.diagram/imagesaveoptions\#getResolution--) |
| [setSameAsPdfConversionArea(boolean value)](#setSameAsPdfConversionArea-boolean-) | इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getSameAsPdfConversionArea()](../../com.aspose.diagram/imagesaveoptions\#getSameAsPdfConversionArea--) |
| [setSaveForegroundPagesOnly(boolean value)](#setSaveForegroundPagesOnly-boolean-) | इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getSaveForegroundPagesOnly()](../../com.aspose.diagram/imagesaveoptions\#getSaveForegroundPagesOnly--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getSaveFormat()](../../com.aspose.diagram/imagesaveoptions\#getSaveFormat--) |
| [setScale(float value)](#setScale-float-) | इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getScale()](../../com.aspose.diagram/imagesaveoptions\#getScale--) |
| [setShapes(ShapeCollection value)](#setShapes-com.aspose.diagram.ShapeCollection-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--) |
| [setSmoothingMode(int value)](#setSmoothingMode-int-) | इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getSmoothingMode()](../../com.aspose.diagram/imagesaveoptions\#getSmoothingMode--) |
| [setTiffCompression(int value)](#setTiffCompression-int-) | इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getTiffCompression()](../../com.aspose.diagram/imagesaveoptions\#getTiffCompression--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImageSaveOptions(int saveFormat) {#ImageSaveOptions-int-}
```
public ImageSaveOptions(int saveFormat)
```


इस क्लास का नया इंस्टेंस प्रारंभ करता है जिसका उपयोग Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat या Aspose.Diagram.SaveFileFormat फ़ॉर्मेट में रेंडर की गई छवियों को सहेजने के लिए किया जा सकता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| saveFormat | int | यह Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat या Aspose.Diagram.SaveFileFormat हो सकता है। |

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
### getCompositingQuality() {#getCompositingQuality--}
```
public int getCompositingQuality()
```


कम्पोज़िटिंग के दौरान उपयोग करने के लिए गुणवत्ता स्तर निर्दिष्ट करता है। यह प्रॉपर्टी केवल रास्टर इमेज फ़ॉर्मैट में सहेजते समय प्रभावी होती है। डिफ़ॉल्ट मान है Aspose.Diagram.Saving.CompositingQuality.

**Returns:**
int
### getContentZoom() {#getContentZoom--}
```
public float getContentZoom()
```


यह पैरामीटर स्केल के समान है, लेकिन उत्पन्न छवि के आकार को प्रभावित नहीं करता। डिफ़ॉल्ट मान 1.0 है। मान 0 से बड़ा होना चाहिए।

**Returns:**
फ़्लोट
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
### getImageBrightness() {#getImageBrightness--}
```
public float getImageBrightness()
```


उत्पन्न छवियों की चमक। यह प्रॉपर्टी केवल रास्टर इमेज फ़ॉर्मैट में सहेजते समय प्रभावी होती है। डिफ़ॉल्ट मान 0.5 है। मान 0 और 1 के बीच होना चाहिए।

**Returns:**
फ़्लोट
### getImageColorMode() {#getImageColorMode--}
```
public int getImageColorMode()
```


उत्पन्न छवियों के लिए रंग मोड। यह प्रॉपर्टी केवल रास्टर इमेज फ़ॉर्मैट में सहेजते समय प्रभावी होती है। डिफ़ॉल्ट मान है Aspose.Diagram.Saving.ImageColorMode.

**Returns:**
int
### getImageContrast() {#getImageContrast--}
```
public float getImageContrast()
```


उत्पन्न छवियों का कंट्रास्ट। यह प्रॉपर्टी केवल रास्टर इमेज फ़ॉर्मैट में सहेजते समय प्रभावी होती है। डिफ़ॉल्ट मान 0.5 है। मान 0 और 1 के बीच होना चाहिए।

**Returns:**
फ़्लोट
### getInterpolationMode() {#getInterpolationMode--}
```
public int getInterpolationMode()
```


छवियों को स्केल या घुमाते समय उपयोग किए जाने वाले एल्गोरिदम को निर्दिष्ट करता है। यह प्रॉपर्टी केवल रास्टर इमेज फ़ॉर्मैट में सहेजते समय प्रभावी होती है। डिफ़ॉल्ट मान है Aspose.Diagram.Saving.InterpolationMode.

**Returns:**
int
### getJpegQuality() {#getJpegQuality--}
```
public int getJpegQuality()
```


उत्पन्न JPEG छवियों की गुणवत्ता निर्धारित करने वाला मान। यह केवल JPEG में सहेजते समय प्रभावी होता है। JPEG फ़ॉर्मैट में सहेजते समय उत्पन्न छवियों की गुणवत्ता प्राप्त या सेट करने के लिए इस प्रॉपर्टी का उपयोग करें। मान 0 से 100 तक हो सकता है जहाँ 0 का अर्थ सबसे खराब गुणवत्ता लेकिन अधिकतम संपीड़न और 100 का अर्थ सबसे अच्छी गुणवत्ता लेकिन न्यूनतम संपीड़न है। डिफ़ॉल्ट मान 95 है।

**Returns:**
int
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


मल्टीपेज TIFF फ़ाइल में सहेजते समय रेंडर करने के लिए पृष्ठों की संख्या। डिफ़ॉल्ट MaxValue है, जिसका अर्थ है कि आरेख के सभी पृष्ठ रेंडर किए जाएंगे।

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
### getPixelOffsetMode() {#getPixelOffsetMode--}
```
public int getPixelOffsetMode()
```


रेंडरिंग के दौरान पिक्सेल कैसे ऑफ़सेट होते हैं, यह निर्दिष्ट करने वाला मान। यह प्रॉपर्टी केवल रास्टर इमेज फ़ॉर्मैट में सहेजते समय प्रभावी होती है। डिफ़ॉल्ट मान है Aspose.Diagram.Saving.PixelOffsetMode.

**Returns:**
int
### getResolution() {#getResolution--}
```
public float getResolution()
```


उत्पन्न छवियों का रिज़ॉल्यूशन, डॉट्स प्रति इंच में। यह प्रॉपर्टी केवल रास्टर इमेज फ़ॉर्मैट में सहेजते समय प्रभावी होती है। डिफ़ॉल्ट मान 96 है।

**Returns:**
फ़्लोट
### getSameAsPdfConversionArea() {#getSameAsPdfConversionArea--}
```
public boolean getSameAsPdfConversionArea()
```


निर्दिष्ट करता है कि सहेजने का क्षेत्र PDF के समान है या नहीं। यदि true है - रेंडर किया गया क्षेत्र PDF के समान होगा। यदि false है - रेंडर किया गया क्षेत्र डिफ़ॉल्ट रहेगा। डिफ़ॉल्ट मान false है।

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


यदि यह सहेजने विकल्प ऑब्जेक्ट उपयोग किया जाता है तो रेंडर किए गए आरेख पृष्ठों को किस फ़ॉर्मैट में सहेजा जाएगा, यह निर्दिष्ट करता है। यह Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat, Aspose.Diagram.SaveFileFormat या Aspose.Diagram.SaveFileFormat हो सकता है।

**Returns:**
int
### getScale() {#getScale--}
```
public float getScale()
```


उत्पन्न छवियों का ज़ूम फ़ैक्टर। डिफ़ॉल्ट मान 1.0 है। मान 0 से बड़ा होना चाहिए।

**Returns:**
फ़्लोट
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


रेंडर करने के लिए आकार। डिफ़ॉल्ट गणना 0 है।

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getSmoothingMode() {#getSmoothingMode--}
```
public int getSmoothingMode()
```


निर्दिष्ट करता है कि लाइनों, वक्रों और भरे हुए क्षेत्रों के किनारों पर स्मूथिंग (एंटीएलियासिंग) लागू की जाए या नहीं। यह प्रॉपर्टी केवल रास्टर इमेज फ़ॉर्मैट में सहेजते समय प्रभावी होती है। डिफ़ॉल्ट मान है Aspose.Diagram.Saving.SmoothingMode.

**Returns:**
int
### getTiffCompression() {#getTiffCompression--}
```
public int getTiffCompression()
```


TIFF फ़ॉर्मैट में उत्पन्न छवियों को सहेजते समय लागू करने के लिए संपीड़न का प्रकार। यह केवल TIFF में सहेजते समय प्रभावी होता है। डिफ़ॉल्ट मान है Aspose.Diagram.Saving.TiffCompression.

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




### setCompositingQuality(int value) {#setCompositingQuality-int-}
```
public void setCompositingQuality(int value)
```


इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getCompositingQuality()](../../com.aspose.diagram/imagesaveoptions\#getCompositingQuality--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setContentZoom(float value) {#setContentZoom-float-}
```
public void setContentZoom(float value)
```


इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getContentZoom()](../../com.aspose.diagram/imagesaveoptions\#getContentZoom--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | फ़्लोट |  |

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


इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getExportHiddenPage()](../../com.aspose.diagram/imagesaveoptions\#getExportHiddenPage--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### setImageBrightness(float value) {#setImageBrightness-float-}
```
public void setImageBrightness(float value)
```


इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getImageBrightness()](../../com.aspose.diagram/imagesaveoptions\#getImageBrightness--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | फ़्लोट |  |

### setImageColorMode(int value) {#setImageColorMode-int-}
```
public void setImageColorMode(int value)
```


इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getImageColorMode()](../../com.aspose.diagram/imagesaveoptions\#getImageColorMode--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setImageContrast(float value) {#setImageContrast-float-}
```
public void setImageContrast(float value)
```


इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getImageContrast()](../../com.aspose.diagram/imagesaveoptions\#getImageContrast--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | फ़्लोट |  |

### setInterpolationMode(int value) {#setInterpolationMode-int-}
```
public void setInterpolationMode(int value)
```


इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getInterpolationMode()](../../com.aspose.diagram/imagesaveoptions\#getInterpolationMode--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public void setJpegQuality(int value)
```


इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getJpegQuality()](../../com.aspose.diagram/imagesaveoptions\#getJpegQuality--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setPageCount(int value) {#setPageCount-int-}
```
public void setPageCount(int value)
```


इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getPageCount()](../../com.aspose.diagram/imagesaveoptions\#getPageCount--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setPageIndex(int value) {#setPageIndex-int-}
```
public void setPageIndex(int value)
```


इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getPageIndex()](../../com.aspose.diagram/imagesaveoptions\#getPageIndex--)

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

### setPixelOffsetMode(int value) {#setPixelOffsetMode-int-}
```
public void setPixelOffsetMode(int value)
```


इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getPixelOffsetMode()](../../com.aspose.diagram/imagesaveoptions\#getPixelOffsetMode--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setResolution(float value) {#setResolution-float-}
```
public void setResolution(float value)
```


इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getResolution()](../../com.aspose.diagram/imagesaveoptions\#getResolution--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | फ़्लोट |  |

### setSameAsPdfConversionArea(boolean value) {#setSameAsPdfConversionArea-boolean-}
```
public void setSameAsPdfConversionArea(boolean value)
```


इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getSameAsPdfConversionArea()](../../com.aspose.diagram/imagesaveoptions\#getSameAsPdfConversionArea--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### setSaveForegroundPagesOnly(boolean value) {#setSaveForegroundPagesOnly-boolean-}
```
public void setSaveForegroundPagesOnly(boolean value)
```


इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getSaveForegroundPagesOnly()](../../com.aspose.diagram/imagesaveoptions\#getSaveForegroundPagesOnly--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getSaveFormat()](../../com.aspose.diagram/imagesaveoptions\#getSaveFormat--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setScale(float value) {#setScale-float-}
```
public void setScale(float value)
```


इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getScale()](../../com.aspose.diagram/imagesaveoptions\#getScale--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | फ़्लोट |  |

### setShapes(ShapeCollection value) {#setShapes-com.aspose.diagram.ShapeCollection-}
```
public void setShapes(ShapeCollection value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getShapes()](../../com.aspose.diagram/renderingsaveoptions\#getShapes--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [ShapeCollection](../../com.aspose.diagram/shapecollection) |  |

### setSmoothingMode(int value) {#setSmoothingMode-int-}
```
public void setSmoothingMode(int value)
```


इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getSmoothingMode()](../../com.aspose.diagram/imagesaveoptions\#getSmoothingMode--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setTiffCompression(int value) {#setTiffCompression-int-}
```
public void setTiffCompression(int value)
```


इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getTiffCompression()](../../com.aspose.diagram/imagesaveoptions\#getTiffCompression--)

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

