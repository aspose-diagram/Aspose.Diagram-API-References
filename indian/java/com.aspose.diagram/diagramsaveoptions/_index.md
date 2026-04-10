---
title: DiagramSaveOptions
second_title: Aspose.Diagram for Java API Reference
description: Can be used to specify additional options when saving a diagram into Visio VDXVSX format.
type: docs
weight: 119
url: /hi/java/com.aspose.diagram/diagramsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.SaveOptions](../../com.aspose.diagram/saveoptions)
```
public class DiagramSaveOptions extends SaveOptions
```

Can be used to specify additional options when saving a diagram into Visio (VDX\\VSX) format. At the moment provides only the SaveFormat property, but in the future will have other options added.
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [DiagramSaveOptions()](#DiagramSaveOptions--) | Initializes a new instance of this class that can be used to save a diagram in the VDX format. |
| [DiagramSaveOptions(int saveFormat)](#DiagramSaveOptions-int-) | इस वर्ग की एक नई इंस्टेंस को प्रारंभ करता है जिसका उपयोग VDX या VSX फ़ॉर्मेट में आरेख को सहेजने के लिए किया जा सकता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [createSaveOptions(int saveFormat)](#createSaveOptions-int-) | निर्दिष्ट सहेजने के प्रारूप के लिए उपयुक्त वर्ग की एक सहेजने विकल्प वस्तु बनाता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoFitPageToDrawingContent()](#getAutoFitPageToDrawingContent--) | निर्धारित करता है कि चित्र सामग्री को फिट करने के लिए पृष्ठ को बड़ा करना आवश्यक है या नहीं। |
| [getClass()](#getClass--) |  |
| [getDefaultFont()](#getDefaultFont--) | जब आरेख में अक्षर यूनिकोड होते हैं और सही फ़ॉन्ट मान सेट नहीं किया गया हो या फ़ॉन्ट स्थानीय रूप से स्थापित न हो, तो वे पीडीएफ, छवि या XPS में ब्लॉक के रूप में दिखाई दे सकते हैं। |
| [getSaveFormat()](#getSaveFormat--) | यदि इस सहेजने विकल्प वस्तु का उपयोग किया जाता है तो रेंडर किए गए आरेख को किस फ़ॉर्मेट में सहेजा जाएगा, यह निर्दिष्ट करता है। |
| [getWarningCallback()](#getWarningCallback--) | चेतावनी कॉलबैक। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoFitPageToDrawingContent(boolean value)](#setAutoFitPageToDrawingContent-boolean-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getAutoFitPageToDrawingContent()](../../com.aspose.diagram/diagramsaveoptions\#getAutoFitPageToDrawingContent--) |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--) |
| [setSaveFormat(int value)](#setSaveFormat-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getSaveFormat()](../../com.aspose.diagram/diagramsaveoptions\#getSaveFormat--) |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.diagram.IWarningCallback-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DiagramSaveOptions() {#DiagramSaveOptions--}
```
public DiagramSaveOptions()
```


Initializes a new instance of this class that can be used to save a diagram in the VDX format.

### DiagramSaveOptions(int saveFormat) {#DiagramSaveOptions-int-}
```
public DiagramSaveOptions(int saveFormat)
```


इस वर्ग की एक नई इंस्टेंस को प्रारंभ करता है जिसका उपयोग VDX या VSX फ़ॉर्मेट में आरेख को सहेजने के लिए किया जा सकता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| saveFormat | int |  |

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
### getAutoFitPageToDrawingContent() {#getAutoFitPageToDrawingContent--}
```
public boolean getAutoFitPageToDrawingContent()
```


निर्धारित करता है कि चित्र सामग्री को फिट करने के लिए पृष्ठ को बड़ा करना आवश्यक है या नहीं। डिफ़ॉल्ट मान false है।

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
### getSaveFormat() {#getSaveFormat--}
```
public int getSaveFormat()
```


यदि इस सहेजने विकल्प वस्तु का उपयोग किया जाता है तो रेंडर किए गए आरेख को किस फ़ॉर्मेट में सहेजा जाएगा, यह निर्दिष्ट करता है। यह Aspose.Diagram.SaveFileFormat या Aspose.Diagram.SaveFileFormat हो सकता है।

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
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAutoFitPageToDrawingContent(boolean value) {#setAutoFitPageToDrawingContent-boolean-}
```
public void setAutoFitPageToDrawingContent(boolean value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getAutoFitPageToDrawingContent()](../../com.aspose.diagram/diagramsaveoptions\#getAutoFitPageToDrawingContent--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | बूलियन |  |

### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public void setDefaultFont(String value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getDefaultFont()](../../com.aspose.diagram/saveoptions\#getDefaultFont--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setSaveFormat(int value) {#setSaveFormat-int-}
```
public void setSaveFormat(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getSaveFormat()](../../com.aspose.diagram/diagramsaveoptions\#getSaveFormat--)

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

