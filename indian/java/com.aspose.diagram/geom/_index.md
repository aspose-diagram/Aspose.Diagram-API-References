---
title: Geom
second_title: Aspose.Diagram for Java API Reference
description: आकार बनाते हुए रेखाओं और चापों के शीर्ष बिंदुओं के निर्देशांक निर्दिष्ट करने वाले तत्वों को शामिल करता है।
type: docs
weight: 169
url: /hi/java/com.aspose.diagram/geom/
---

**Inheritance:**
java.lang.Object
```
public class Geom
```

ऐसे तत्व शामिल करता है जो आकार बनाते हुए रेखाओं और चापों के शीर्ष बिंदुओं के निर्देशांक निर्दिष्ट करते हैं। यदि आकार में एक से अधिक पाथ हैं, तो प्रत्येक पाथ के लिए एक Geom तत्व होता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [Geom()](#Geom--) | कंस्ट्रक्टर। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [deepClone()](#deepClone--) | इस उदाहरण की गहरी प्रतिलिपि बनाता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCoordinateCol()](#getCoordinateCol--) | निर्देशांक का संग्रह। |
| [getDel()](#getDel--) | एक फ़्लैग जो दर्शाता है कि तत्व स्थानीय रूप से हटाया गया है या नहीं। |
| [getIX()](#getIX--) | उसके पैरेंट तत्व के भीतर तत्व का शून्य-आधारित सूचकांक। |
| [getNextCoordinateIX()](#getNextCoordinateIX--) | अगले आकार के निर्देशांक संग्रह सदस्य के लिए IX मान लौटाता है। |
| [getNoFill()](#getNoFill--) | निर्दिष्ट करता है कि पाथ को भरा जा सकता है या नहीं। |
| [getNoLine()](#getNoLine--) | निर्दिष्ट करता है कि पाथ की सीमा के चारों ओर रेखा खींची गई है या नहीं। |
| [getNoQuickDrag()](#getNoQuickDrag--) | निर्धारित करता है कि उपयोगकर्ता द्वारा Geometry सेक्शन द्वारा परिभाषित भरे हुए क्षेत्र पर क्लिक करने पर आकार को चयनित या खींचा जा सकता है या नहीं। |
| [getNoShow()](#getNoShow--) | निर्दिष्ट करता है कि पाथ ड्राइंग पेज पर प्रदर्शित है या नहीं। |
| [getNoSnap()](#getNoSnap--) | निर्दिष्ट करता है कि अन्य आकार पाथ से स्नैप होते हैं या नहीं। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getDel()](../../com.aspose.diagram/geom\#getDel--) |
| [setIX(int value)](#setIX-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getIX()](../../com.aspose.diagram/geom\#getIX--) |
| [setNoFill(BoolValue value)](#setNoFill-com.aspose.diagram.BoolValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getNoFill()](../../com.aspose.diagram/geom\#getNoFill--) |
| [setNoLine(BoolValue value)](#setNoLine-com.aspose.diagram.BoolValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getNoLine()](../../com.aspose.diagram/geom\#getNoLine--) |
| [setNoQuickDrag(BoolValue value)](#setNoQuickDrag-com.aspose.diagram.BoolValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getNoQuickDrag()](../../com.aspose.diagram/geom\#getNoQuickDrag--) |
| [setNoShow(BoolValue value)](#setNoShow-com.aspose.diagram.BoolValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getNoShow()](../../com.aspose.diagram/geom\#getNoShow--) |
| [setNoSnap(BoolValue value)](#setNoSnap-com.aspose.diagram.BoolValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getNoSnap()](../../com.aspose.diagram/geom\#getNoSnap--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Geom() {#Geom--}
```
public Geom()
```


कंस्ट्रक्टर।

### deepClone() {#deepClone--}
```
public Object deepClone()
```


इस उदाहरण की गहरी प्रतिलिपि बनाता है।

**Returns:**
java.lang.Object -
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
### getCoordinateCol() {#getCoordinateCol--}
```
public CoordinateCollection getCoordinateCol()
```


निर्देशांक संग्रह। यह निर्देशांकों के क्रम को दिखाता है।

**Returns:**
[CoordinateCollection](../../com.aspose.diagram/coordinatecollection)
### getDel() {#getDel--}
```
public int getDel()
```


एक फ़्लैग जो दर्शाता है कि तत्व स्थानीय रूप से हटाया गया है या नहीं। मान 1 यह संकेत देता है कि तत्व स्थानीय रूप से हटाया गया था।

**Returns:**
int
### getIX() {#getIX--}
```
public int getIX()
```


उसके पैरेंट तत्व के भीतर तत्व का शून्य-आधारित सूचकांक।

**Returns:**
int
### getNextCoordinateIX() {#getNextCoordinateIX--}
```
public int getNextCoordinateIX()
```


अगले आकार के निर्देशांक संग्रह सदस्य के लिए IX मान लौटाता है।

**Returns:**
int
### getNoFill() {#getNoFill--}
```
public BoolValue getNoFill()
```


निर्दिष्ट करता है कि पाथ को भरा जा सकता है या नहीं।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoLine() {#getNoLine--}
```
public BoolValue getNoLine()
```


निर्दिष्ट करता है कि पाथ की सीमा के चारों ओर रेखा खींची गई है या नहीं।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoQuickDrag() {#getNoQuickDrag--}
```
public BoolValue getNoQuickDrag()
```


निर्धारित करता है कि उपयोगकर्ता द्वारा Geometry सेक्शन द्वारा परिभाषित भरे हुए क्षेत्र पर क्लिक करने पर आकार को चयनित या खींचा जा सकता है या नहीं।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoShow() {#getNoShow--}
```
public BoolValue getNoShow()
```


निर्दिष्ट करता है कि पाथ ड्राइंग पेज पर प्रदर्शित है या नहीं।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getNoSnap() {#getNoSnap--}
```
public BoolValue getNoSnap()
```


निर्दिष्ट करता है कि अन्य आकार पाथ से स्नैप होते हैं या नहीं।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getDel()](../../com.aspose.diagram/geom\#getDel--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getIX()](../../com.aspose.diagram/geom\#getIX--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setNoFill(BoolValue value) {#setNoFill-com.aspose.diagram.BoolValue-}
```
public void setNoFill(BoolValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getNoFill()](../../com.aspose.diagram/geom\#getNoFill--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setNoLine(BoolValue value) {#setNoLine-com.aspose.diagram.BoolValue-}
```
public void setNoLine(BoolValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getNoLine()](../../com.aspose.diagram/geom\#getNoLine--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setNoQuickDrag(BoolValue value) {#setNoQuickDrag-com.aspose.diagram.BoolValue-}
```
public void setNoQuickDrag(BoolValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getNoQuickDrag()](../../com.aspose.diagram/geom\#getNoQuickDrag--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setNoShow(BoolValue value) {#setNoShow-com.aspose.diagram.BoolValue-}
```
public void setNoShow(BoolValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getNoShow()](../../com.aspose.diagram/geom\#getNoShow--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setNoSnap(BoolValue value) {#setNoSnap-com.aspose.diagram.BoolValue-}
```
public void setNoSnap(BoolValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getNoSnap()](../../com.aspose.diagram/geom\#getNoSnap--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

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

