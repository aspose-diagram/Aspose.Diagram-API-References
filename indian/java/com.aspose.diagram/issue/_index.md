---
title: Issue
second_title: Aspose.Diagram for Java API Reference
description: दस्तावेज़ में एकल वैधता समस्या को दर्शाता है।
type: docs
weight: 208
url: /hi/java/com.aspose.diagram/issue/
---

**Inheritance:**
java.lang.Object
```
public class Issue
```

दस्तावेज़ में एकल वैधता समस्या को दर्शाता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [Issue()](#Issue--) | कंस्ट्रक्टर |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getID()](#getID--) | मान्यकरण समस्या का अद्वितीय पहचानकर्ता निर्दिष्ट करता है। |
| [getIgnored()](#getIgnored--) | निर्दिष्ट करता है कि मान्यकरण समस्या वर्तमान में अनदेखी की गई है या नहीं। |
| [getIssueTarget()](#getIssueTarget--) | पैरेंट वैधता समस्या के लक्ष्य के आधार पर, पृष्ठ या पृष्ठ और आकार दोनों को निर्दिष्ट करता है, जिससे पैरेंट वैधता समस्या जुड़ी होती है। |
| [getRuleInfo()](#getRuleInfo--) | पैरेंट वैधता मुद्दे से संबंधित वैधता नियम के बारे में जानकारी निर्दिष्ट करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setID(long value)](#setID-long-) | इस गुण के विवरण के लिए, कृपया देखें [getID()](../../com.aspose.diagram/issue\#getID--) |
| [setIgnored(int value)](#setIgnored-int-) | इस गुण के विवरण के लिए, कृपया देखें [getIgnored()](../../com.aspose.diagram/issue\#getIgnored--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Issue() {#Issue--}
```
public Issue()
```


कंस्ट्रक्टर

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
### getID() {#getID--}
```
public long getID()
```


मान्यकरण समस्या का अद्वितीय पहचानकर्ता निर्दिष्ट करता है।

**Returns:**
long
### getIgnored() {#getIgnored--}
```
public int getIgnored()
```


निर्दिष्ट करता है कि मान्यकरण समस्या वर्तमान में अनदेखी की गई है या नहीं। डिफ़ॉल्ट मान False है।

**Returns:**
int
### getIssueTarget() {#getIssueTarget--}
```
public IssueTarget getIssueTarget()
```


पैरेंट वैलिडेशन इश्यू के टार्गेट के आधार पर, यह या तो पेज, या पेज और शेप दोनों को निर्दिष्ट करता है, जिससे पैरेंट वैलिडेशन इश्यू जुड़ा होता है। यदि पैरेंट वैलिडेशन इश्यू का टार्गेट एक दस्तावेज़ है, तो IssueTarget न तो पेज और न ही शेप को निर्दिष्ट करता है।

**Returns:**
[IssueTarget](../../com.aspose.diagram/issuetarget)
### getRuleInfo() {#getRuleInfo--}
```
public RuleInfo getRuleInfo()
```


पैरेंट वैधता मुद्दे से संबंधित वैधता नियम के बारे में जानकारी निर्दिष्ट करता है।

**Returns:**
[RuleInfo](../../com.aspose.diagram/ruleinfo)
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




### setID(long value) {#setID-long-}
```
public void setID(long value)
```


इस गुण के विवरण के लिए, कृपया देखें [getID()](../../com.aspose.diagram/issue\#getID--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | long |  |

### setIgnored(int value) {#setIgnored-int-}
```
public void setIgnored(int value)
```


इस गुण के विवरण के लिए, कृपया देखें [getIgnored()](../../com.aspose.diagram/issue\#getIgnored--)

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

