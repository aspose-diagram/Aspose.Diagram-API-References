---
title: EllipticalArcTo
second_title: Aspose.Diagram for Java API Reference
description: एक दीर्घवृत्तीय चाप के बारे में जानकारी निर्दिष्ट करने वाले तत्व शामिल हैं।
type: docs
weight: 140
url: /hi/java/com.aspose.diagram/ellipticalarcto/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.Coordinate](../../com.aspose.diagram/coordinate)
```
public class EllipticalArcTo extends Coordinate
```

एक दीर्घवृत्तीय चाप के बारे में जानकारी निर्दिष्ट करने वाले तत्व शामिल हैं।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [EllipticalArcTo()](#EllipticalArcTo--) | एक [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto) क्लास का इंस्टेंस बनाता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [deepClone()](#deepClone--) | इस उदाहरण की गहरी प्रतिलिपि बनाता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getA()](#getA--) | आर्क के नियंत्रण बिंदु का x-निर्देशांक। |
| [getB()](#getB--) | आर्क के नियंत्रण बिंदु का y-निर्देशांक। |
| [getC()](#getC--) | आर्क की प्रमुख धुरी का कोण, उसके पैरेंट की x-अक्ष के सापेक्ष। |
| [getClass()](#getClass--) |  |
| [getD()](#getD--) | आर्क की प्रमुख धुरी और लघु धुरी के बीच अनुपात। |
| [getDel()](#getDel--) | एक फ़्लैग जो दर्शाता है कि तत्व स्थानीय रूप से हटाया गया है या नहीं। |
| [getIX()](#getIX--) | उसके पैरेंट तत्व के भीतर तत्व का शून्य-आधारित सूचकांक। |
| [getX()](#getX--) | अण्डाकार आर्क के समाप्ति शिखर का x-निर्देशांक। |
| [getY()](#getY--) | अण्डाकार आर्क के समाप्ति शिखर का y-निर्देशांक। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setA(DoubleValue value)](#setA-com.aspose.diagram.DoubleValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getA()](../../com.aspose.diagram/ellipticalarcto\#getA--) |
| [setB(DoubleValue value)](#setB-com.aspose.diagram.DoubleValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getB()](../../com.aspose.diagram/ellipticalarcto\#getB--) |
| [setC(DoubleValue value)](#setC-com.aspose.diagram.DoubleValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getC()](../../com.aspose.diagram/ellipticalarcto\#getC--) |
| [setD(DoubleValue value)](#setD-com.aspose.diagram.DoubleValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getD()](../../com.aspose.diagram/ellipticalarcto\#getD--) |
| [setDel(int value)](#setDel-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getDel()](../../com.aspose.diagram/ellipticalarcto\#getDel--) |
| [setIX(int value)](#setIX-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getIX()](../../com.aspose.diagram/ellipticalarcto\#getIX--) |
| [setX(DoubleValue value)](#setX-com.aspose.diagram.DoubleValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getX()](../../com.aspose.diagram/ellipticalarcto\#getX--) |
| [setY(DoubleValue value)](#setY-com.aspose.diagram.DoubleValue-) | इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getY()](../../com.aspose.diagram/ellipticalarcto\#getY--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EllipticalArcTo() {#EllipticalArcTo--}
```
public EllipticalArcTo()
```


एक [EllipticalArcTo](../../com.aspose.diagram/ellipticalarcto) क्लास का इंस्टेंस बनाता है।

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
### getA() {#getA--}
```
public DoubleValue getA()
```


आर्क के नियंत्रण बिंदु का x-निर्देशांक। नियंत्रण बिंदु को आर्क के प्रारंभ और समाप्ति शीर्षों के बीच लगभग आधे रास्ते पर स्थित करना सबसे अच्छा है। अन्यथा, नियंत्रण बिंदु से गुजरने के लिए आर्क अत्यधिक आकार में बढ़ सकता है, जिसके परिणाम अप्रत्याशित हो सकते हैं।

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getB() {#getB--}
```
public DoubleValue getB()
```


आर्क के नियंत्रण बिंदु का y-निर्देशांक।

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getC() {#getC--}
```
public DoubleValue getC()
```


आर्क की प्रमुख धुरी का कोण, उसके पैरेंट की x-अक्ष के सापेक्ष।

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getD() {#getD--}
```
public DoubleValue getD()
```


आर्क के प्रमुख अक्ष और लघु अक्ष के अनुपात। इन शब्दों के सामान्य अर्थ के बावजूद, प्रमुख अक्ष को लघु अक्ष से बड़ा होने की आवश्यकता नहीं है, इसलिए यह अनुपात 1 से बड़ा होना आवश्यक नहीं है। इस तत्व को 0 या उससे कम या 1000 से अधिक मान पर सेट करने से अप्रत्याशित परिणाम हो सकते हैं।

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
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
### getX() {#getX--}
```
public DoubleValue getX()
```


अण्डाकार आर्क के समाप्ति शिखर का x-निर्देशांक।

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getY() {#getY--}
```
public DoubleValue getY()
```


अण्डाकार आर्क के समाप्ति शिखर का y-निर्देशांक।

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




### setA(DoubleValue value) {#setA-com.aspose.diagram.DoubleValue-}
```
public void setA(DoubleValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getA()](../../com.aspose.diagram/ellipticalarcto\#getA--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setB(DoubleValue value) {#setB-com.aspose.diagram.DoubleValue-}
```
public void setB(DoubleValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getB()](../../com.aspose.diagram/ellipticalarcto\#getB--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setC(DoubleValue value) {#setC-com.aspose.diagram.DoubleValue-}
```
public void setC(DoubleValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getC()](../../com.aspose.diagram/ellipticalarcto\#getC--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setD(DoubleValue value) {#setD-com.aspose.diagram.DoubleValue-}
```
public void setD(DoubleValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getD()](../../com.aspose.diagram/ellipticalarcto\#getD--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getDel()](../../com.aspose.diagram/ellipticalarcto\#getDel--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getIX()](../../com.aspose.diagram/ellipticalarcto\#getIX--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setX(DoubleValue value) {#setX-com.aspose.diagram.DoubleValue-}
```
public void setX(DoubleValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getX()](../../com.aspose.diagram/ellipticalarcto\#getX--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setY(DoubleValue value) {#setY-com.aspose.diagram.DoubleValue-}
```
public void setY(DoubleValue value)
```


इस प्रॉपर्टी का विवरण देखने के लिए, कृपया देखें [getY()](../../com.aspose.diagram/ellipticalarcto\#getY--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

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

