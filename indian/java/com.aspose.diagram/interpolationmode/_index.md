---
title: InterpolationMode
second_title: Aspose.Diagram for Java API Reference
description: InterpolationMode एन्यूमरेशन वह एल्गोरिद्म निर्दिष्ट करता है जो छवियों को स्केल या घुमाते समय उपयोग किया जाता है।
type: docs
weight: 206
url: /hi/java/com.aspose.diagram/interpolationmode/
---

**Inheritance:**
java.lang.Object
```
public final class InterpolationMode
```

InterpolationMode एन्यूमरेशन वह एल्गोरिद्म निर्दिष्ट करता है जो छवियों को स्केल या घुमाते समय उपयोग किया जाता है।
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [BICUBIC](#BICUBIC) | बाइक्यूबिक इंटरपोलेशन को निर्दिष्ट करता है। |
| [BILINEAR](#BILINEAR) | बिलीनियर इंटरपोलेशन को निर्दिष्ट करता है। |
| [DEFAULT](#DEFAULT) | डिफ़ॉल्ट मोड को निर्दिष्ट करता है। |
| [HIGH](#HIGH) | उच्च गुणवत्ता वाला इंटरपोलेशन निर्दिष्ट करता है। |
| [HIGH_QUALITY_BICUBIC](#HIGH-QUALITY-BICUBIC) | उच्च-गुणवत्ता, बाइक्यूबिक इंटरपोलेशन को निर्दिष्ट करता है। |
| [HIGH_QUALITY_BILINEAR](#HIGH-QUALITY-BILINEAR) | उच्च-गुणवत्ता, बिलीनियर इंटरपोलेशन को निर्दिष्ट करता है। |
| [INVALID](#INVALID) | QualityMode एनेमरेशन के Invalid तत्व के बराबर है। |
| [LOW](#LOW) | निम्न गुणवत्ता वाला इंटरपोलेशन निर्दिष्ट करता है। |
| [NEAREST_NEIGHBOR](#NEAREST-NEIGHBOR) | नज़दीकी-पर्याय इंटरपोलेशन को निर्दिष्ट करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BICUBIC {#BICUBIC}
```
public static final int BICUBIC
```


बाइक्यूबिक इंटरपोलेशन को निर्दिष्ट करता है। कोई प्रीफ़िल्टरिंग नहीं की जाती। यह मोड मूल आकार के 25 प्रतिशत से कम तक छवि को छोटा करने के लिए उपयुक्त नहीं है।

### BILINEAR {#BILINEAR}
```
public static final int BILINEAR
```


बिलीनियर इंटरपोलेशन को निर्दिष्ट करता है। कोई प्रीफ़िल्टरिंग नहीं की जाती। यह मोड मूल आकार के 50 प्रतिशत से कम तक छवि को छोटा करने के लिए उपयुक्त नहीं है।

### DEFAULT {#DEFAULT}
```
public static final int DEFAULT
```


डिफ़ॉल्ट मोड को निर्दिष्ट करता है।

### HIGH {#HIGH}
```
public static final int HIGH
```


उच्च गुणवत्ता वाला इंटरपोलेशन निर्दिष्ट करता है।

### HIGH_QUALITY_BICUBIC {#HIGH-QUALITY-BICUBIC}
```
public static final int HIGH_QUALITY_BICUBIC
```


उच्च-गुणवत्ता, बाइक्यूबिक इंटरपोलेशन को निर्दिष्ट करता है। उच्च-गुणवत्ता वाले संकुचन को सुनिश्चित करने के लिए प्रीफ़िल्टरिंग की जाती है। यह मोड सबसे उच्च गुणवत्ता वाली परिवर्तित छवियों को उत्पन्न करता है।

### HIGH_QUALITY_BILINEAR {#HIGH-QUALITY-BILINEAR}
```
public static final int HIGH_QUALITY_BILINEAR
```


उच्च-गुणवत्ता, बिलीनियर इंटरपोलेशन को निर्दिष्ट करता है। उच्च-गुणवत्ता वाले संकुचन को सुनिश्चित करने के लिए प्रीफ़िल्टरिंग की जाती है।

### INVALID {#INVALID}
```
public static final int INVALID
```


QualityMode एनेमरेशन के Invalid तत्व के बराबर है।

### LOW {#LOW}
```
public static final int LOW
```


निम्न गुणवत्ता वाला इंटरपोलेशन निर्दिष्ट करता है।

### NEAREST_NEIGHBOR {#NEAREST-NEIGHBOR}
```
public static final int NEAREST_NEIGHBOR
```


नज़दीकी-पर्याय इंटरपोलेशन को निर्दिष्ट करता है।

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

