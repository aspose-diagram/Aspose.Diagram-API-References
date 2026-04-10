---
title: Encoding
second_title: Aspose.Diagram for Java API Reference
description: एक अक्षर एन्कोडिंग को दर्शाता है।
type: docs
weight: 143
url: /hi/java/com.aspose.diagram/encoding/
---

**Inheritance:**
java.lang.Object
```
public class Encoding
```

एक अक्षर एन्कोडिंग को दर्शाता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [Encoding()](#Encoding--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [equals(Encoding other)](#equals-com.aspose.diagram.Encoding-) | निर्धारित करता है कि निर्दिष्ट Encoding ऑब्जेक्ट वर्तमान उदाहरण के बराबर है या नहीं। |
| [equals(Object o)](#equals-java.lang.Object-) | निर्धारित करता है कि निर्दिष्ट ऑब्जेक्ट वर्तमान उदाहरण के बराबर है या नहीं। |
| [getASCII()](#getASCII--) | ASCII (7-बिट) कैरेक्टर सेट के लिए एन्कोडिंग प्राप्त करता है। |
| [getBigEndianUnicode()](#getBigEndianUnicode--) | बिग एंडियन बाइट क्रम का उपयोग करके UTF-16 फ़ॉर्मेट के लिए एन्कोडिंग प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getDefault()](#getDefault--) | ऑपरेटिंग सिस्टम के वर्तमान ANSI कोड पेज के लिए एन्कोडिंग प्राप्त करता है। |
| [getEncoding(int codePage)](#getEncoding-int-) | निर्दिष्ट कोड पेज पहचानकर्ता से जुड़ी एन्कोडिंग लौटाता है। |
| [getEncoding(String charsetName)](#getEncoding-java.lang.String-) | निर्दिष्ट charset नाम से जुड़ी एन्कोडिंग लौटाता है। |
| [getEncoding(Charset charset)](#getEncoding-java.nio.charset.Charset-) | निर्दिष्ट charset ऑब्जेक्ट से जुड़ी एन्कोडिंग लौटाता है। |
| [getUTF7()](#getUTF7--) | UTF-7 फ़ॉर्मेट के लिए एन्कोडिंग प्राप्त करता है। |
| [getUTF8()](#getUTF8--) | UTF-8 फ़ॉर्मेट के लिए एन्कोडिंग प्राप्त करता है। |
| [getUTF8NoBOM()](#getUTF8NoBOM--) | UTF-8 पहचानकर्ता के बिना UTF-8 फ़ॉर्मेट के लिए एन्कोडिंग प्राप्त करता है। |
| [getUnicode()](#getUnicode--) | लिटिल एंडियन बाइट क्रम का उपयोग करके UTF-16 फ़ॉर्मेट के लिए एन्कोडिंग प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Encoding() {#Encoding--}
```
public Encoding()
```


### equals(Encoding other) {#equals-com.aspose.diagram.Encoding-}
```
public boolean equals(Encoding other)
```


निर्धारित करता है कि निर्दिष्ट Encoding ऑब्जेक्ट वर्तमान उदाहरण के बराबर है या नहीं।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| other | [Encoding](../../com.aspose.diagram/encoding) | वर्तमान उदाहरण से तुलना करने के लिए Encoding ऑब्जेक्ट। |

**Returns:**
boolean - यदि मान वर्तमान उदाहरण के बराबर है तो true; अन्यथा false।
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


निर्धारित करता है कि निर्दिष्ट ऑब्जेक्ट वर्तमान उदाहरण के बराबर है या नहीं।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| o | java.lang.Object | वर्तमान उदाहरण के साथ तुलना करने के लिए ऑब्जेक्ट। |

**Returns:**
बूलियन - true यदि मान Encoding का एक उदाहरण है और वर्तमान उदाहरण के बराबर है; अन्यथा, false.
### getASCII() {#getASCII--}
```
public static Encoding getASCII()
```


ASCII (7-बिट) कैरेक्टर सेट के लिए एन्कोडिंग प्राप्त करता है।

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - A Encoding object for the ASCII (7-bit) character set.
### getBigEndianUnicode() {#getBigEndianUnicode--}
```
public static Encoding getBigEndianUnicode()
```


बिग एंडियन बाइट क्रम का उपयोग करके UTF-16 फ़ॉर्मेट के लिए एन्कोडिंग प्राप्त करता है।

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - A Encoding object for the UTF-16 format using the big endian byte
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefault() {#getDefault--}
```
public static Encoding getDefault()
```


ऑपरेटिंग सिस्टम के वर्तमान ANSI कोड पेज के लिए एन्कोडिंग प्राप्त करता है।

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - An encoding for the operating system's current ANSI code page.
### getEncoding(int codePage) {#getEncoding-int-}
```
public static Encoding getEncoding(int codePage)
```


निर्दिष्ट कोड पेज पहचानकर्ता से जुड़ी एन्कोडिंग लौटाता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| कोडपेज | int | पसंदीदा एन्कोडिंग का कोड पेज पहचानकर्ता। -या- 0, डिफ़ॉल्ट एन्कोडिंग उपयोग करने के लिए। |

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - The Encoding object associated with the specified code page.
### getEncoding(String charsetName) {#getEncoding-java.lang.String-}
```
public static Encoding getEncoding(String charsetName)
```


निर्दिष्ट charset नाम से जुड़ी एन्कोडिंग लौटाता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| कैरेक्टरसेटनाम | java.lang.String | निर्दिष्ट कैरेक्टरसेट नाम |

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - The Encoding object associated with the specified charset name.
### getEncoding(Charset charset) {#getEncoding-java.nio.charset.Charset-}
```
public static Encoding getEncoding(Charset charset)
```


निर्दिष्ट charset ऑब्जेक्ट से जुड़ी एन्कोडिंग लौटाता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| कैरेक्टरसेट | java.nio.charset.Charset | निर्दिष्ट कैरेक्टरसेट ऑब्जेक्ट |

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - The Encoding object associated with the specified charset object.
### getUTF7() {#getUTF7--}
```
public static Encoding getUTF7()
```


UTF-7 फ़ॉर्मेट के लिए एन्कोडिंग प्राप्त करता है।

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - A Encoding object for the UTF-7 format.
### getUTF8() {#getUTF8--}
```
public static Encoding getUTF8()
```


UTF-8 फ़ॉर्मेट के लिए एन्कोडिंग प्राप्त करता है।

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - A Encoding object for the UTF-8 format.
### getUTF8NoBOM() {#getUTF8NoBOM--}
```
public static Encoding getUTF8NoBOM()
```


UTF-8 पहचानकर्ता के बिना UTF-8 फ़ॉर्मेट के लिए एन्कोडिंग प्राप्त करता है।

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - A Encoding object for the UTF-8 format without UTF-8 identifier.
### getUnicode() {#getUnicode--}
```
public static Encoding getUnicode()
```


लिटिल एंडियन बाइट क्रम का उपयोग करके UTF-16 फ़ॉर्मेट के लिए एन्कोडिंग प्राप्त करता है।

**Returns:**
[Encoding](../../com.aspose.diagram/encoding) - A Encoding object for the UTF-16 format using the little endian byte
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

