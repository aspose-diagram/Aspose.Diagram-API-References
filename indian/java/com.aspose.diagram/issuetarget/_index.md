---
title: IssueTarget
second_title: Aspose.Diagram for Java API Reference
description: पैरेंट वैलिडेशन इश्यू के टार्गेट के आधार पर यह या तो पेज या पेज और शेप दोनों को निर्दिष्ट करता है, जिससे पैरेंट वैलिडेशन इश्यू जुड़ा होता है।
type: docs
weight: 210
url: /hi/java/com.aspose.diagram/issuetarget/
---

**Inheritance:**
java.lang.Object
```
public class IssueTarget
```

पैरेंट वैलिडेशन इश्यू के टार्गेट के आधार पर, यह या तो पेज, या पेज और शेप दोनों को निर्दिष्ट करता है, जिससे पैरेंट वैलिडेशन इश्यू जुड़ा होता है। यदि पैरेंट वैलिडेशन इश्यू का टार्गेट एक दस्तावेज़ है, तो IssueTarget न तो पेज और न ही शेप को निर्दिष्ट करता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [IssueTarget(long pageID, long shapeID)](#IssueTarget-long-long-) | कंस्ट्रक्टर। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getPageId()](#getPageId--) | पैरेंट वैलिडेशन इश्यू से जुड़े पेज का अद्वितीय पहचानकर्ता निर्दिष्ट करता है। |
| [getShapeId()](#getShapeId--) | पैरेंट वैलिडेशन इश्यू से जुड़े शेप का अद्वितीय पहचानकर्ता निर्दिष्ट करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setPageId(long value)](#setPageId-long-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getPageId()](../../com.aspose.diagram/issuetarget\#getPageId--) |
| [setShapeId(long value)](#setShapeId-long-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getShapeId()](../../com.aspose.diagram/issuetarget\#getShapeId--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### IssueTarget(long pageID, long shapeID) {#IssueTarget-long-long-}
```
public IssueTarget(long pageID, long shapeID)
```


कंस्ट्रक्टर।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| pageID | long |  |
| shapeID | long |  |

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
### getPageId() {#getPageId--}
```
public long getPageId()
```


पैरेंट वैलिडेशन इश्यू से जुड़े पेज का अद्वितीय पहचानकर्ता निर्दिष्ट करता है। यदि टार्गेट दस्तावेज़ है, तो PageID मान 0xFFFFFFFF हो सकता है।

**Returns:**
long
### getShapeId() {#getShapeId--}
```
public long getShapeId()
```


पैरेंट वैलिडेशन इश्यू से जुड़े शेप का अद्वितीय पहचानकर्ता निर्दिष्ट करता है। यदि टार्गेट दस्तावेज़ या पेज है, तो ShapeID मान 0xFFFFFFFF हो सकता है।

**Returns:**
long
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




### setPageId(long value) {#setPageId-long-}
```
public void setPageId(long value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getPageId()](../../com.aspose.diagram/issuetarget\#getPageId--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | long |  |

### setShapeId(long value) {#setShapeId-long-}
```
public void setShapeId(long value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getShapeId()](../../com.aspose.diagram/issuetarget\#getShapeId--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | long |  |

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

