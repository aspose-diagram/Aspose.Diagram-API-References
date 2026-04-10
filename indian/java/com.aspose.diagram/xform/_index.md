---
title: XForm
second_title: Aspose.Diagram for Java API Reference
description: ऐसे तत्व शामिल करता है जो पैटर्न वज़न और रंग जैसी आकृति के रेखा गुणों को नियंत्रित करते हैं।
type: docs
weight: 449
url: /hi/java/com.aspose.diagram/xform/
---

**Inheritance:**
java.lang.Object
```
public class XForm
```

एक आकार के लिए रेखा गुणों को नियंत्रित करने वाले तत्व शामिल करता है, जैसे पैटर्न, वजन, और रंग। ये तत्व निर्धारित करते हैं कि क्या रेखा के अंत स्वरूपित हैं (उदाहरण के लिए, तीर के सिर के साथ), रेखा अंत स्वरूपों का आकार, रेखा पर लागू गोलाई वृत्त का त्रिज्या, और रेखा कैप शैली (गोल या वर्ग)।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [deepClone()](#deepClone--) | इस उदाहरण की गहरी प्रतिलिपि बनाता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAngle()](#getAngle--) | आकृति के पैरेंट के सापेक्ष वर्तमान घूर्णन कोण का प्रतिनिधित्व करता है। |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | एक फ़्लैग जो दर्शाता है कि तत्व स्थानीय रूप से हटाया गया है या नहीं। |
| [getFlipX()](#getFlipX--) | यह दर्शाता है कि आकृति को क्षैतिज रूप से उलटा गया है या नहीं |
| [getFlipY()](#getFlipY--) | यह दर्शाता है कि आकृति को लंबवत रूप से उलटा गया है या नहीं। |
| [getHeight()](#getHeight--) | आकृति की ऊँचाई को ड्राइंग इकाइयों में निर्दिष्ट करता है। |
| [getLocPinX()](#getLocPinX--) | आकृति के मूल बिंदु के सापेक्ष आकृति के पिन (घूर्णन केंद्र) का x-निर्देशांक निर्दिष्ट करता है। |
| [getLocPinY()](#getLocPinY--) | आकृति के मूल बिंदु के सापेक्ष आकृति के पिन (घूर्णन केंद्र) का y-निर्देशांक निर्दिष्ट करता है। |
| [getPinPos()](#getPinPos--) | आकृति के पिन की स्थिति निर्दिष्ट करता है |
| [getPinX()](#getPinX--) | माता-पिता के मूल बिंदु के सापेक्ष आकृति के पिन (घूर्णन केंद्र) का x-निर्देशांक निर्दिष्ट करता है। |
| [getPinY()](#getPinY--) | माता-पिता के मूल बिंदु के सापेक्ष आकृति के पिन (घूर्णन केंद्र) का y-निर्देशांक निर्दिष्ट करता है। |
| [getResizeMode()](#getResizeMode--) | जब आकार समूह में हो, तो वर्तमान आकार बदलने के व्यवहार सेटिंग को निर्दिष्ट करता है। |
| [getWidth()](#getWidth--) | संबंधित आकृति की चौड़ाई को ड्राइंग इकाइयों में शामिल करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAngle(DoubleValue value)](#setAngle-com.aspose.diagram.DoubleValue-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getAngle()](../../com.aspose.diagram/xform\#getAngle--) |
| [setDel(int value)](#setDel-int-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getDel()](../../com.aspose.diagram/xform\#getDel--) |
| [setFlipX(BoolValue value)](#setFlipX-com.aspose.diagram.BoolValue-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getFlipX()](../../com.aspose.diagram/xform\#getFlipX--) |
| [setFlipY(BoolValue value)](#setFlipY-com.aspose.diagram.BoolValue-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getFlipY()](../../com.aspose.diagram/xform\#getFlipY--) |
| [setHeight(DoubleValue value)](#setHeight-com.aspose.diagram.DoubleValue-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getHeight()](../../com.aspose.diagram/xform\#getHeight--) |
| [setLocPinX(DoubleValue value)](#setLocPinX-com.aspose.diagram.DoubleValue-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getLocPinX()](../../com.aspose.diagram/xform\#getLocPinX--) |
| [setLocPinY(DoubleValue value)](#setLocPinY-com.aspose.diagram.DoubleValue-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getLocPinY()](../../com.aspose.diagram/xform\#getLocPinY--) |
| [setPinPos(int value)](#setPinPos-int-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getPinPos()](../../com.aspose.diagram/xform\#getPinPos--) |
| [setPinX(DoubleValue value)](#setPinX-com.aspose.diagram.DoubleValue-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getPinX()](../../com.aspose.diagram/xform\#getPinX--) |
| [setPinY(DoubleValue value)](#setPinY-com.aspose.diagram.DoubleValue-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getPinY()](../../com.aspose.diagram/xform\#getPinY--) |
| [setResizeMode(ResizeMode value)](#setResizeMode-com.aspose.diagram.ResizeMode-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getResizeMode()](../../com.aspose.diagram/xform\#getResizeMode--) |
| [setWidth(DoubleValue value)](#setWidth-com.aspose.diagram.DoubleValue-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getWidth()](../../com.aspose.diagram/xform\#getWidth--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getAngle() {#getAngle--}
```
public DoubleValue getAngle()
```


आकृति के पैरेंट के सापेक्ष वर्तमान घूर्णन कोण का प्रतिनिधित्व करता है।

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDel() {#getDel--}
```
public int getDel()
```


एक फ़्लैग जो दर्शाता है कि तत्व स्थानीय रूप से हटाया गया है या नहीं। मान 1 यह संकेत देता है कि तत्व स्थानीय रूप से हटाया गया था।

**Returns:**
int
### getFlipX() {#getFlipX--}
```
public BoolValue getFlipX()
```


यह दर्शाता है कि आकृति को क्षैतिज रूप से उलटा गया है या नहीं

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getFlipY() {#getFlipY--}
```
public BoolValue getFlipY()
```


यह दर्शाता है कि आकृति को लंबवत रूप से उलटा गया है या नहीं।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getHeight() {#getHeight--}
```
public DoubleValue getHeight()
```


आकृति की ऊँचाई को ड्राइंग इकाइयों में निर्दिष्ट करता है।

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLocPinX() {#getLocPinX--}
```
public DoubleValue getLocPinX()
```


आकृति के मूल बिंदु के सापेक्ष आकृति के पिन (घूर्णन केंद्र) का x-निर्देशांक निर्दिष्ट करता है। LocPinX निर्धारित करने के लिए डिफ़ॉल्ट सूत्र है: F='Width\* 0.5'।

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLocPinY() {#getLocPinY--}
```
public DoubleValue getLocPinY()
```


आकृति के मूल बिंदु के सापेक्ष आकृति के पिन (घूर्णन केंद्र) का y-निर्देशांक निर्दिष्ट करता है। LocPinY निर्धारित करने के लिए डिफ़ॉल्ट सूत्र है: F='Height \* 0.5'।

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPinPos() {#getPinPos--}
```
public int getPinPos()
```


आकृति के पिन की स्थिति निर्दिष्ट करता है

**Returns:**
int
### getPinX() {#getPinX--}
```
public DoubleValue getPinX()
```


माता-पिता के मूल बिंदु के सापेक्ष आकृति के पिन (घूर्णन केंद्र) का x-निर्देशांक निर्दिष्ट करता है।

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPinY() {#getPinY--}
```
public DoubleValue getPinY()
```


माता-पिता के मूल बिंदु के सापेक्ष आकृति के पिन (घूर्णन केंद्र) का y-निर्देशांक निर्दिष्ट करता है।

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getResizeMode() {#getResizeMode--}
```
public ResizeMode getResizeMode()
```


जब आकार समूह में हो, तो वर्तमान आकार बदलने के व्यवहार सेटिंग को निर्दिष्ट करता है।

**Returns:**
[ResizeMode](../../com.aspose.diagram/resizemode)
### getWidth() {#getWidth--}
```
public DoubleValue getWidth()
```


संबंधित आकृति की चौड़ाई को ड्राइंग इकाइयों में शामिल करता है।

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




### setAngle(DoubleValue value) {#setAngle-com.aspose.diagram.DoubleValue-}
```
public void setAngle(DoubleValue value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getAngle()](../../com.aspose.diagram/xform\#getAngle--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getDel()](../../com.aspose.diagram/xform\#getDel--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setFlipX(BoolValue value) {#setFlipX-com.aspose.diagram.BoolValue-}
```
public void setFlipX(BoolValue value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getFlipX()](../../com.aspose.diagram/xform\#getFlipX--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setFlipY(BoolValue value) {#setFlipY-com.aspose.diagram.BoolValue-}
```
public void setFlipY(BoolValue value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getFlipY()](../../com.aspose.diagram/xform\#getFlipY--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setHeight(DoubleValue value) {#setHeight-com.aspose.diagram.DoubleValue-}
```
public void setHeight(DoubleValue value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getHeight()](../../com.aspose.diagram/xform\#getHeight--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setLocPinX(DoubleValue value) {#setLocPinX-com.aspose.diagram.DoubleValue-}
```
public void setLocPinX(DoubleValue value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getLocPinX()](../../com.aspose.diagram/xform\#getLocPinX--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setLocPinY(DoubleValue value) {#setLocPinY-com.aspose.diagram.DoubleValue-}
```
public void setLocPinY(DoubleValue value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getLocPinY()](../../com.aspose.diagram/xform\#getLocPinY--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setPinPos(int value) {#setPinPos-int-}
```
public void setPinPos(int value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getPinPos()](../../com.aspose.diagram/xform\#getPinPos--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setPinX(DoubleValue value) {#setPinX-com.aspose.diagram.DoubleValue-}
```
public void setPinX(DoubleValue value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getPinX()](../../com.aspose.diagram/xform\#getPinX--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setPinY(DoubleValue value) {#setPinY-com.aspose.diagram.DoubleValue-}
```
public void setPinY(DoubleValue value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getPinY()](../../com.aspose.diagram/xform\#getPinY--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setResizeMode(ResizeMode value) {#setResizeMode-com.aspose.diagram.ResizeMode-}
```
public void setResizeMode(ResizeMode value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getResizeMode()](../../com.aspose.diagram/xform\#getResizeMode--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [ResizeMode](../../com.aspose.diagram/resizemode) |  |

### setWidth(DoubleValue value) {#setWidth-com.aspose.diagram.DoubleValue-}
```
public void setWidth(DoubleValue value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getWidth()](../../com.aspose.diagram/xform\#getWidth--)

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

