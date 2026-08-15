---
title: छवि
second_title: Aspose.Diagram for Java API Reference
description: एक बिटमैप के लिए gamma, brightness, contrast, blur, sharpen, denoise और transparency मानों को शामिल करता है।
type: docs
weight: 196
url: /hi/java/com.aspose.diagram/image/
---

**Inheritance:**
java.lang.Object
```
public class Image
```

बिटमैप के लिए गामा, चमक, कंट्रास्ट, ब्लर, शार्पन, डीनॉइज़ और ट्रांसपेरेंसी मानों को शामिल करता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlur()](#getBlur--) | एक बिटमैप छवि को ब्लर या नरम करता है। |
| [getBrightness()](#getBrightness--) | एक बिटमैप छवि की brightness को समायोजित करता है। |
| [getClass()](#getClass--) |  |
| [getContrast()](#getContrast--) | एक बिटमैप छवि का contrast निर्दिष्ट करता है। |
| [getDel()](#getDel--) | एक फ़्लैग जो दर्शाता है कि तत्व स्थानीय रूप से हटाया गया है या नहीं। |
| [getDenoise()](#getDenoise--) | एक बिटमैप छवि से शोर (पिक्सेल जिनके रंग स्तर यादृच्छिक रूप से वितरित होते हैं) हटाता है। |
| [getGamma()](#getGamma--) | एक विशेष आउटपुट डिवाइस, जैसे मॉनिटर या स्कैनर, के लिए छवि की तीव्रता को समायोजित या सुधारता है। |
| [getSharpen()](#getSharpen--) | एक बिटमैप छवि को शार्पेन करने की मात्रा निर्दिष्ट करता है। |
| [getTransparency()](#getTransparency--) | एक लेयर रंग के लिए ट्रांसपैरेंसी स्तर निर्दिष्ट करता है, 0 (अपारदर्शी) से 1 (पूरी तरह से पारदर्शी) तक। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getDel()](../../com.aspose.diagram/image\\#getDel--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getBlur() {#getBlur--}
```
public DoubleValue getBlur()
```


एक बिटमैप छवि को ब्लर या नरम करता है। Blur तत्व 0 और 1 के बीच का मान रखता है; डिफ़ॉल्ट मान 0 है।

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBrightness() {#getBrightness--}
```
public DoubleValue getBrightness()
```


एक बिटमैप छवि की brightness को समायोजित करता है। Brightness तत्व 0 और 1 के बीच का मान रखता है; डिफ़ॉल्ट मान 0.5 है।

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContrast() {#getContrast--}
```
public DoubleValue getContrast()
```


एक बिटमैप छवि का contrast निर्दिष्ट करता है। Contrast तत्व 0 और 1 के बीच का मान रखता है।

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDel() {#getDel--}
```
public int getDel()
```


एक फ़्लैग जो दर्शाता है कि तत्व स्थानीय रूप से हटाया गया है या नहीं। मान 1 यह संकेत देता है कि तत्व स्थानीय रूप से हटाया गया था।

**Returns:**
int
### getDenoise() {#getDenoise--}
```
public DoubleValue getDenoise()
```


एक बिटमैप छवि से शोर (पिक्सेल जिनके रंग स्तर यादृच्छिक रूप से वितरित होते हैं) हटाता है।

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getGamma() {#getGamma--}
```
public DoubleValue getGamma()
```


एक विशेष आउटपुट डिवाइस, जैसे मॉनिटर या स्कैनर, के लिए छवि की तीव्रता को समायोजित या सुधारता है। डिफ़ॉल्ट मान 1 है (कोई सुधार नहीं।

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getSharpen() {#getSharpen--}
```
public DoubleValue getSharpen()
```


एक बिटमैप छवि को शार्पेन करने की मात्रा निर्दिष्ट करता है। छवि को शार्पेन करने से यह निकटवर्ती पिक्सेल के कॉन्ट्रास्ट को बढ़ाकर फोकस होती है।

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getTransparency() {#getTransparency--}
```
public DoubleValue getTransparency()
```


एक लेयर रंग के लिए ट्रांसपैरेंसी स्तर निर्दिष्ट करता है, 0 (अपारदर्शी) से 1 (पूरी तरह से पारदर्शी) तक।

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
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




### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getDel()](../../com.aspose.diagram/image\\#getDel--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

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

