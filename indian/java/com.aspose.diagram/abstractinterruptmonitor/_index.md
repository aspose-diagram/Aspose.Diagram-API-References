---
title: AbstractInterruptMonitor
second_title: Aspose.Diagram for Java API Reference
description: सभी समय-साध्य ऑपरेशनों में बाधा अनुरोधों के लिए मॉनिटर।
type: docs
weight: 10
url: /hi/java/com.aspose.diagram/abstractinterruptmonitor/
---

**Inheritance:**
java.lang.Object
```
public abstract class AbstractInterruptMonitor
```

सभी समय-साध्य ऑपरेशनों में बाधा अनुरोधों के लिए मॉनिटर।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [AbstractInterruptMonitor()](#AbstractInterruptMonitor--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [isInterruptionRequested()](#isInterruptionRequested--) | बताता है कि वर्तमान ऑपरेशन के लिए बाधा का अनुरोध किया गया है या नहीं। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AbstractInterruptMonitor() {#AbstractInterruptMonitor--}
```
public AbstractInterruptMonitor()
```


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
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```


बताता है कि वर्तमान ऑपरेशन के लिए बाधा का अनुरोध किया गया है या नहीं। यदि सत्य है तो वर्तमान ऑपरेशन बाधित हो जाएगा।

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

