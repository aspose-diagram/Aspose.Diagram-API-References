---
title: EventItem
second_title: Aspose.Diagram for Java API Reference
description: एक इवेंट कोड को संलग्न करता है।
type: docs
weight: 145
url: /hi/java/com.aspose.diagram/eventitem/
---

**Inheritance:**
java.lang.Object
```
public class EventItem
```

एक इवेंट कोड को संलग्न करता है। एक EventItem तत्व दो प्रकार की क्रियाओं को ट्रिगर कर सकता है: यह एक ऐड-ऑन चला सकता है, या यह इवेंट की सूचना कॉल करने वाले प्रोग्राम को भेज सकता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [EventItem()](#EventItem--) | कंस्ट्रक्टर। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | पैरेंट EventItem तत्व का एक्शन कोड निर्दिष्ट करता है। एक EventItem तत्व को DatadiagramML फ़ाइल में सहेजने के लिए, इसे स्थायी होना चाहिए। |
| [getClass()](#getClass--) |  |
| [getEnabled()](#getEnabled--) | एक फ़्लैग दर्शाता है जो संकेत करता है कि इवेंट सक्षम है या अक्षम। |
| [getEventCode()](#getEventCode--) | एक कोड जो उस इवेंट को दर्शाता है जो ऐड-ऑन को ट्रिगर करता है। |
| [getID()](#getID--) | इवेंट की आईडी। |
| [getTarget()](#getTarget--) | इवेंट का लक्ष्य निर्दिष्ट करता है। |
| [getTargetArgs()](#getTargetArgs--) | एक स्ट्रिंग निर्दिष्ट करता है जिसमें तर्क होते हैं जिन्हें इवेंट के लक्ष्य को भेजा जाएगा। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAction(int value)](#setAction-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getAction()](../../com.aspose.diagram/eventitem\#getAction--) |
| [setEnabled(int value)](#setEnabled-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getEnabled()](../../com.aspose.diagram/eventitem\#getEnabled--) |
| [setEventCode(int value)](#setEventCode-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getEventCode()](../../com.aspose.diagram/eventitem\#getEventCode--) |
| [setID(int value)](#setID-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getID()](../../com.aspose.diagram/eventitem\#getID--) |
| [setTarget(String value)](#setTarget-java.lang.String-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getTarget()](../../com.aspose.diagram/eventitem\#getTarget--) |
| [setTargetArgs(String value)](#setTargetArgs-java.lang.String-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getTargetArgs()](../../com.aspose.diagram/eventitem\#getTargetArgs--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EventItem() {#EventItem--}
```
public EventItem()
```


कंस्ट्रक्टर।

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
### getAction() {#getAction--}
```
public int getAction()
```


पैरेंट EventItem तत्व का एक्शन कोड निर्दिष्ट करता है। एक EventItem तत्व को DatadiagramML फ़ाइल में सहेजने के लिए, इसे स्थायी होना चाहिए। वर्तमान में, एक स्थायी इवेंट के लिए केवल वैध एक्शन कोड 1 (ONEVENT_ACT_RUNADDON) है।

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEnabled() {#getEnabled--}
```
public int getEnabled()
```


एक फ़्लैग दर्शाता है जो संकेत करता है कि इवेंट सक्षम है या अक्षम।

**Returns:**
int
### getEventCode() {#getEventCode--}
```
public int getEventCode()
```


एक कोड जो उस इवेंट को दर्शाता है जो ऐड-ऑन को ट्रिगर करता है। इवेंट कोड्स के बारे में अधिक जानकारी के लिए, Microsoft Visio 2007 Automation Reference में Event Codes देखें।

**Returns:**
int
### getID() {#getID--}
```
public int getID()
```


इवेंट की आईडी।

**Returns:**
int
### getTarget() {#getTarget--}
```
public String getTarget()
```


इवेंट का लक्ष्य निर्दिष्ट करता है।

**Returns:**
java.lang.String
### getTargetArgs() {#getTargetArgs--}
```
public String getTargetArgs()
```


एक स्ट्रिंग निर्दिष्ट करता है जिसमें तर्क होते हैं जिन्हें इवेंट के लक्ष्य को भेजा जाएगा।

**Returns:**
java.lang.String
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




### setAction(int value) {#setAction-int-}
```
public void setAction(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getAction()](../../com.aspose.diagram/eventitem\#getAction--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setEnabled(int value) {#setEnabled-int-}
```
public void setEnabled(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getEnabled()](../../com.aspose.diagram/eventitem\#getEnabled--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setEventCode(int value) {#setEventCode-int-}
```
public void setEventCode(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getEventCode()](../../com.aspose.diagram/eventitem\#getEventCode--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getID()](../../com.aspose.diagram/eventitem\#getID--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setTarget(String value) {#setTarget-java.lang.String-}
```
public void setTarget(String value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getTarget()](../../com.aspose.diagram/eventitem\#getTarget--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setTargetArgs(String value) {#setTargetArgs-java.lang.String-}
```
public void setTargetArgs(String value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getTargetArgs()](../../com.aspose.diagram/eventitem\#getTargetArgs--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

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

