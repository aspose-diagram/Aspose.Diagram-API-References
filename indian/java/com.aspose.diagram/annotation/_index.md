---
title: एनोटेशन
second_title: Aspose.Diagram for Java API Reference
description: ऐसे तत्व शामिल हैं जिनमें दस्तावेज़ पृष्ठ में डाले गए टिप्पणियों की जानकारी होती है।
type: docs
weight: 20
url: /hi/java/com.aspose.diagram/annotation/
---

**Inheritance:**
java.lang.Object
```
public class Annotation
```

ऐसे तत्व शामिल हैं जिनमें दस्तावेज़ पृष्ठ में डाले गए टिप्पणियों की जानकारी होती है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getComment()](#getComment--) | एक आकार के लिए स्ट्रिंग स्वरूप में टिप्पणी पाठ शामिल करता है। |
| [getDate()](#getDate--) | निर्दिष्ट करता है कि टिप्पणी कब बनाई गई थी |
| [getDel()](#getDel--) | एक फ़्लैग जो दर्शाता है कि तत्व स्थानीय रूप से हटाया गया है या नहीं। |
| [getEditDate()](#getEditDate--) | निर्दिष्ट करता है कि टिप्पणी आखिरी बार कब बदली गई थी |
| [getIX()](#getIX--) | उसके पैरेंट तत्व के भीतर तत्व का शून्य-आधारित सूचकांक। |
| [getLangID()](#getLangID--) | सेल फ़ॉर्मूला, टेक्स्ट, कस्टम प्रॉपर्टी, या टिप्पणी जिस भाषा में दर्ज की गई थी, उसके लोकैल आईडी (LCID) को दर्शाता है। |
| [getMarkerIndex()](#getMarkerIndex--) | एक टिप्पणी मार्कर को सौंपा गया सूचकांक संख्या निर्दिष्ट करता है। |
| [getReviewerID()](#getReviewerID--) | दस्तावेज़ में मार्कअप जोड़ने वाले समीक्षक की आईडी संख्या शामिल करता है। |
| [getShapeID()](#getShapeID--) | टिप्पणी का आकार आईडी। |
| [getX()](#getX--) | पृष्ठ निर्देशांक में टिप्पणी मार्कर का x-निर्देशांक। |
| [getY()](#getY--) | पृष्ठ निर्देशांक में टिप्पणी मार्कर का y-निर्देशांक। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getDel()](../../com.aspose.diagram/annotation\#getDel--) |
| [setIX(int value)](#setIX-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getIX()](../../com.aspose.diagram/annotation\#getIX--) |
| [setShapeID(int value)](#setShapeID-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getShapeID()](../../com.aspose.diagram/annotation\#getShapeID--) |
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getComment() {#getComment--}
```
public Str2Value getComment()
```


एक आकार के लिए स्ट्रिंग स्वरूप में टिप्पणी पाठ शामिल करता है।

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getDate() {#getDate--}
```
public DateValue getDate()
```


निर्दिष्ट करता है कि टिप्पणी कब बनाई गई थी

**Returns:**
[DateValue](../../com.aspose.diagram/datevalue)
### getDel() {#getDel--}
```
public int getDel()
```


एक फ़्लैग जो दर्शाता है कि तत्व स्थानीय रूप से हटाया गया है या नहीं। मान 1 यह संकेत देता है कि तत्व स्थानीय रूप से हटाया गया था।

**Returns:**
int
### getEditDate() {#getEditDate--}
```
public DateValue getEditDate()
```


निर्दिष्ट करता है कि टिप्पणी आखिरी बार कब बदली गई थी

**Returns:**
[DateValue](../../com.aspose.diagram/datevalue)
### getIX() {#getIX--}
```
public int getIX()
```


उसके पैरेंट तत्व के भीतर तत्व का शून्य-आधारित सूचकांक।

**Returns:**
int
### getLangID() {#getLangID--}
```
public IntValue getLangID()
```


सेल फ़ॉर्मूला, टेक्स्ट, कस्टम प्रॉपर्टी, या टिप्पणी जिस भाषा में दर्ज की गई थी, उसके लोकैल आईडी (LCID) को दर्शाता है।

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getMarkerIndex() {#getMarkerIndex--}
```
public IntValue getMarkerIndex()
```


एक टिप्पणी मार्कर को सौंपा गया सूचकांक संख्या निर्दिष्ट करता है।

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getReviewerID() {#getReviewerID--}
```
public IntValue getReviewerID()
```


दस्तावेज़ में मार्कअप जोड़ने वाले समीक्षक की आईडी संख्या शामिल करता है।

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getShapeID() {#getShapeID--}
```
public int getShapeID()
```


टिप्पणी का आकार आईडी।

**Returns:**
int
### getX() {#getX--}
```
public DoubleValue getX()
```


पृष्ठ निर्देशांक में टिप्पणी मार्कर का x-निर्देशांक।

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getY() {#getY--}
```
public DoubleValue getY()
```


पृष्ठ निर्देशांक में टिप्पणी मार्कर का y-निर्देशांक।

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


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getDel()](../../com.aspose.diagram/annotation\#getDel--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getIX()](../../com.aspose.diagram/annotation\#getIX--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setShapeID(int value) {#setShapeID-int-}
```
public void setShapeID(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getShapeID()](../../com.aspose.diagram/annotation\#getShapeID--)

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

