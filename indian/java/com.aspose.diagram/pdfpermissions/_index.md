---
title: PdfPermissions
second_title: Aspose.Diagram for Java API Reference
description: PDF दस्तावेज़ के लिए उपयोगकर्ता अनुमतियों को निर्दिष्ट करता है।
type: docs
weight: 280
url: /hi/java/com.aspose.diagram/pdfpermissions/
---

**Inheritance:**
java.lang.Object
```
public final class PdfPermissions
```

PDF दस्तावेज़ के लिए उपयोगकर्ता अनुमतियों को निर्दिष्ट करता है।
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [ALLOW_ALL](#ALLOW-ALL) | PDF दस्तावेज़ पर सभी ऑपरेशन्स की अनुमति देता है। |
| [CONTENT_COPY](#CONTENT-COPY) | दस्तावेज़ से टेक्स्ट और ग्राफ़िक्स को कॉपी या अन्यथा निकालने की अनुमति देता है, जिसमें एक्सेसिबिलिटी उद्देश्यों के लिए निकासी भी शामिल है। |
| [CONTENT_COPY_FOR_ACCESSIBILITY](#CONTENT-COPY-FOR-ACCESSIBILITY) | विकलांग उपयोगकर्ताओं के लिए एक्सेसिबिलिटी समर्थन में या अन्य उद्देश्यों के लिए टेक्स्ट और ग्राफ़िक्स निकालने की अनुमति देता है। |
| [DISALLOW_ALL](#DISALLOW-ALL) | PDF दस्तावेज़ पर सभी ऑपरेशन्स को प्रतिबंधित करता है। |
| [DOCUMENT_ASSEMBLY](#DOCUMENT-ASSEMBLY) | दस्तावेज़ को असेंबल करने की अनुमति देता है: पृष्ठों को सम्मिलित करना, घुमाना या हटाना और बुकमार्क या थंबनेल इमेज़ जैसे नेविगेशन तत्व बनाना। |
| [FILL_IN](#FILL-IN) | फ़ॉर्म भरने और दस्तावेज़ पर साइन करने की अनुमति देता है। |
| [HIGH_RESOLUTION_PRINTING](#HIGH-RESOLUTION-PRINTING) | दस्तावेज़ को संभवतम उच्च रिज़ॉल्यूशन पर प्रिंट करने की अनुमति देता है। जब RC4 40-बिट एन्क्रिप्शन का उपयोग किया जाता है, तो यह विकल्प अनदेखा किया जाता है और प्रिंटिंग सेट होने पर उच्च रिज़ॉल्यूशन प्रिंटिंग की अनुमति होती है। |
| [MODIFY_ANNOTATIONS](#MODIFY-ANNOTATIONS) | टेक्स्ट एनोटेशन जोड़ने या संशोधित करने की अनुमति देता है। |
| [MODIFY_CONTENTS](#MODIFY-CONTENTS) | दस्तावेज़\u9225\u6a9a सामग्री को संशोधित करने की अनुमति देता है। |
| [PRINTING](#PRINTING) | दस्तावेज़ को प्रिंट करने की अनुमति देता है। |
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
### ALLOW_ALL {#ALLOW-ALL}
```
public static final int ALLOW_ALL
```


PDF दस्तावेज़ पर सभी ऑपरेशन्स की अनुमति देता है।

### CONTENT_COPY {#CONTENT-COPY}
```
public static final int CONTENT_COPY
```


दस्तावेज़ से टेक्स्ट और ग्राफ़िक्स को कॉपी या अन्यथा निकालने की अनुमति देता है, जिसमें एक्सेसिबिलिटी उद्देश्यों के लिए निकासी भी शामिल है।

### CONTENT_COPY_FOR_ACCESSIBILITY {#CONTENT-COPY-FOR-ACCESSIBILITY}
```
public static final int CONTENT_COPY_FOR_ACCESSIBILITY
```


अक्षम उपयोगकर्ताओं के लिए पहुंच समर्थन या अन्य उद्देश्यों के लिए टेक्स्ट और ग्राफ़िक्स निकालने की अनुमति देता है। जब RC4 40-बिट एन्क्रिप्शन का उपयोग किया जाता है, तो यह विकल्प अनदेखा किया जाता है और जब ContentCopy सेट होता है तो पहुंच की अनुमति दी जाती है।

### DISALLOW_ALL {#DISALLOW-ALL}
```
public static final int DISALLOW_ALL
```


PDF दस्तावेज़ पर सभी ऑपरेशनों को निषिद्ध करता है। यह डिफ़ॉल्ट मान है।

### DOCUMENT_ASSEMBLY {#DOCUMENT-ASSEMBLY}
```
public static final int DOCUMENT_ASSEMBLY
```


दस्तावेज़ को असेंबल करने की अनुमति देता है: पृष्ठों को सम्मिलित करना, घुमाना या हटाना और बुकमार्क या थंबनेल छवियों जैसे नेविगेशन तत्व बनाना। जब RC4 40-बिट एन्क्रिप्शन का उपयोग किया जाता है, तो यह विकल्प अनदेखा किया जाता है और जब ModifyContents सेट होता है तो दस्तावेज़ असेंबली की अनुमति दी जाती है।

### FILL_IN {#FILL-IN}
```
public static final int FILL_IN
```


फ़ॉर्म भरने और दस्तावेज़ पर हस्ताक्षर करने की अनुमति देता है। जब RC4 40-बिट एन्क्रिप्शन का उपयोग किया जाता है, तो यह विकल्प अनदेखा किया जाता है और जब ModifyAnnotations सेट होता है तो फ़ॉर्म भरने की अनुमति दी जाती है।

### HIGH_RESOLUTION_PRINTING {#HIGH-RESOLUTION-PRINTING}
```
public static final int HIGH_RESOLUTION_PRINTING
```


दस्तावेज़ को संभवतम उच्च रिज़ॉल्यूशन पर प्रिंट करने की अनुमति देता है। जब RC4 40-बिट एन्क्रिप्शन का उपयोग किया जाता है, तो यह विकल्प अनदेखा किया जाता है और प्रिंटिंग सेट होने पर उच्च रिज़ॉल्यूशन प्रिंटिंग की अनुमति होती है।

### MODIFY_ANNOTATIONS {#MODIFY-ANNOTATIONS}
```
public static final int MODIFY_ANNOTATIONS
```


टेक्स्ट एनोटेशन जोड़ने या संशोधित करने की अनुमति देता है। जब RC4 40-बिट एन्क्रिप्शन का उपयोग किया जाता है, तो यह विकल्प फ़ॉर्म फ़ील्ड भरने की भी अनुमति देता है।

### MODIFY_CONTENTS {#MODIFY-CONTENTS}
```
public static final int MODIFY_CONTENTS
```


दस्तावेज़\u9225\u6a9a सामग्री को संशोधित करने की अनुमति देता है।

### PRINTING {#PRINTING}
```
public static final int PRINTING
```


दस्तावेज़ को प्रिंट करने की अनुमति देता है।

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

