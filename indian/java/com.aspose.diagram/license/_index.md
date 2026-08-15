---
title: लाइसेंस
second_title: Aspose.Diagram for Java API Reference
description: घटक को लाइसेंस करने के लिए विधियाँ प्रदान करता है।
type: docs
weight: 219
url: /hi/java/com.aspose.diagram/license/
---

**Inheritance:**
java.lang.Object
```
public class License
```

घटक को लाइसेंस करने के लिए विधियाँ प्रदान करता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [License()](#License--) | इस क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | कंपोनेंट को लाइसेंस करता है। |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | कंपोनेंट को लाइसेंस करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### License() {#License--}
```
public License()
```


इस क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है।

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




### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public void setLicense(InputStream stream)
```


कंपोनेंट को लाइसेंस करता है।

स्ट्रीम से लाइसेंस लोड करने के लिए इस मेथड का उपयोग करें।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.InputStream | एक स्ट्रीम जिसमें लाइसेंस शामिल है। |

### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public void setLicense(String licenseName)
```


कंपोनेंट को लाइसेंस करता है।

निम्नलिखित स्थानों में लाइसेंस खोजने का प्रयास करता है:

1. स्पष्ट पथ।

2. कंपोनेंट असेंबली का फ़ोल्डर।

3. क्लाइंट की कॉलिंग असेंबली का फ़ोल्डर।

4. एंट्री असेंबली का फ़ोल्डर।

5. क्लाइंट की कॉलिंग असेंबली में एम्बेडेड रिसोर्स।

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. स्पष्ट पथ।

2. क्लाइंट की कॉलिंग असेंबली में एम्बेडेड रिसोर्स।

2. कंपोनेंट जार फ़ाइल का फ़ोल्डर।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| licenseName | java.lang.String |  |

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

