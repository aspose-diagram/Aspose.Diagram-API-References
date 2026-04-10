---
title: भरण
second_title: Aspose.Diagram for Java API Reference
description: आकार के वर्तमान भराव स्वरूपण मान और आकार की ड्रॉप शैडो को शामिल करता है, जिसमें पैटर्न का अग्रभूमि रंग और पृष्ठभूमि रंग शामिल हैं।
type: docs
weight: 153
url: /hi/java/com.aspose.diagram/fill/
---

**Inheritance:**
java.lang.Object
```
public class Fill
```

आकार और उसके ड्रॉप शैडो के लिए वर्तमान भराव फ़ॉर्मेटिंग मानों को शामिल करता है, जिसमें पैटर्न, अग्रभूमि रंग, और पृष्ठभूमि रंग शामिल हैं।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [deepClone()](#deepClone--) | इस उदाहरण की गहरी प्रतिलिपि बनाता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | एक फ़्लैग जो दर्शाता है कि तत्व स्थानीय रूप से हटाया गया है या नहीं। |
| [getFillBkgnd()](#getFillBkgnd--) | आकार के भराव पैटर्न की पृष्ठभूमि के लिए उपयोग किए जाने वाले रंग को निर्दिष्ट करता है। |
| [getFillBkgndTrans()](#getFillBkgndTrans--) | आकार के भराव पैटर्न की पृष्ठभूमि (भराव) रंग के लिए पारदर्शिता स्तर को निर्दिष्ट करता है, 0 (पूरी तरह अपारदर्शी) से 1 (पूरी तरह पारदर्शी) तक। |
| [getFillForegnd()](#getFillForegnd--) | आकार के भराव पैटर्न की अग्रभूमि (स्ट्रोक) के लिए उपयोग किए जाने वाले रंग को निर्दिष्ट करता है। |
| [getFillForegndTrans()](#getFillForegndTrans--) | आकार के भराव पैटर्न की अग्रभूमि (भराव) रंग के लिए पारदर्शिता स्तर को निर्दिष्ट करता है, 0 (पूरी तरह अपारदर्शी) से 1 (पूरी तरह पारदर्शी) तक। |
| [getFillPattern()](#getFillPattern--) | आकार के लिए भराव पैटर्न को निर्दिष्ट करता है। |
| [getGradientFill()](#getGradientFill--) | आकार के वर्तमान ग्रेडिएंट भराव स्वरूपण मान को शामिल करता है। |
| [getShapeShdwBlur()](#getShapeShdwBlur--) | आकार की छाया ब्लर आकार को निर्दिष्ट करता है। |
| [getShapeShdwObliqueAngle()](#getShapeShdwObliqueAngle--) | आकार की छाया की तिरछी दिशा का कोण निर्दिष्ट करता है। |
| [getShapeShdwOffsetX()](#getShapeShdwOffsetX--) | पृष्ठ इकाइयों में वह दूरी निर्धारित करता है जिससे आकार की छाया आकार से क्षैतिज रूप से ऑफसेट होती है। |
| [getShapeShdwOffsetY()](#getShapeShdwOffsetY--) | पृष्ठ इकाइयों में वह दूरी निर्धारित करता है जिससे आकार की छाया आकार से लंबवत रूप से ऑफसेट होती है। |
| [getShapeShdwScaleFactor()](#getShapeShdwScaleFactor--) | आकार की छाया को कितना प्रतिशत बढ़ाया या घटाया जा सकता है, इसे निर्दिष्ट करता है। |
| [getShapeShdwShow()](#getShapeShdwShow--) | एक आकार के लिए छाया के प्रकार को निर्दिष्ट करता है। |
| [getShapeShdwType()](#getShapeShdwType--) | एक आकार के लिए छाया के प्रकार को निर्दिष्ट करता है। |
| [getShdwBkgnd()](#getShdwBkgnd--) | आकार की ड्रॉप शैडो भराव पैटर्न की पृष्ठभूमि (भराव) के लिए उपयोग किए जाने वाले रंग को निर्दिष्ट करता है। |
| [getShdwBkgndTrans()](#getShdwBkgndTrans--) | आकार की ड्रॉप शैडो भराव पैटर्न की पृष्ठभूमि (भराव) के लिए पारदर्शिता स्तर को निर्दिष्ट करता है, 0.0 (पूरी तरह अपारदर्शी) से 1.0 (पूरी तरह पारदर्शी) तक। |
| [getShdwForegnd()](#getShdwForegnd--) | आकार की ड्रॉप शैडो भराव पैटर्न की अग्रभूमि (स्ट्रोक) के लिए उपयोग किए जाने वाले रंग को निर्दिष्ट करता है। |
| [getShdwForegndTrans()](#getShdwForegndTrans--) | आकार की ड्रॉप शैडो भराव पैटर्न की अग्रभूमि (स्ट्रोक) के लिए पारदर्शिता स्तर को निर्दिष्ट करता है, 0.0 (पूरी तरह अपारदर्शी) से 1.0 (पूरी तरह पारदर्शी) तक। |
| [getShdwPattern()](#getShdwPattern--) | आकार की छाया के लिए भराव पैटर्न को निर्दिष्ट करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getDel()](../../com.aspose.diagram/fill\#getDel--) |
| [setFillBkgnd(ColorValue value)](#setFillBkgnd-com.aspose.diagram.ColorValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getFillBkgnd()](../../com.aspose.diagram/fill\#getFillBkgnd--) |
| [setFillBkgndTrans(DoubleValue value)](#setFillBkgndTrans-com.aspose.diagram.DoubleValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getFillBkgndTrans()](../../com.aspose.diagram/fill\#getFillBkgndTrans--) |
| [setFillForegnd(ColorValue value)](#setFillForegnd-com.aspose.diagram.ColorValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getFillForegnd()](../../com.aspose.diagram/fill\#getFillForegnd--) |
| [setFillForegndTrans(DoubleValue value)](#setFillForegndTrans-com.aspose.diagram.DoubleValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getFillForegndTrans()](../../com.aspose.diagram/fill\#getFillForegndTrans--) |
| [setFillPattern(IntValue value)](#setFillPattern-com.aspose.diagram.IntValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getFillPattern()](../../com.aspose.diagram/fill\#getFillPattern--) |
| [setShapeShdwBlur(DoubleValue value)](#setShapeShdwBlur-com.aspose.diagram.DoubleValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getShapeShdwBlur()](../../com.aspose.diagram/fill\#getShapeShdwBlur--) |
| [setShapeShdwObliqueAngle(DoubleValue value)](#setShapeShdwObliqueAngle-com.aspose.diagram.DoubleValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getShapeShdwObliqueAngle()](../../com.aspose.diagram/fill\#getShapeShdwObliqueAngle--) |
| [setShapeShdwOffsetX(DoubleValue value)](#setShapeShdwOffsetX-com.aspose.diagram.DoubleValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getShapeShdwOffsetX()](../../com.aspose.diagram/fill\#getShapeShdwOffsetX--) |
| [setShapeShdwOffsetY(DoubleValue value)](#setShapeShdwOffsetY-com.aspose.diagram.DoubleValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getShapeShdwOffsetY()](../../com.aspose.diagram/fill\#getShapeShdwOffsetY--) |
| [setShapeShdwScaleFactor(DoubleValue value)](#setShapeShdwScaleFactor-com.aspose.diagram.DoubleValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getShapeShdwScaleFactor()](../../com.aspose.diagram/fill\#getShapeShdwScaleFactor--) |
| [setShapeShdwShow(ShapeShdwShow value)](#setShapeShdwShow-com.aspose.diagram.ShapeShdwShow-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getShapeShdwShow()](../../com.aspose.diagram/fill\#getShapeShdwShow--) |
| [setShapeShdwType(ShapeShdwType value)](#setShapeShdwType-com.aspose.diagram.ShapeShdwType-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getShapeShdwType()](../../com.aspose.diagram/fill\#getShapeShdwType--) |
| [setShdwBkgnd(ColorValue value)](#setShdwBkgnd-com.aspose.diagram.ColorValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getShdwBkgnd()](../../com.aspose.diagram/fill\#getShdwBkgnd--) |
| [setShdwBkgndTrans(DoubleValue value)](#setShdwBkgndTrans-com.aspose.diagram.DoubleValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getShdwBkgndTrans()](../../com.aspose.diagram/fill\#getShdwBkgndTrans--) |
| [setShdwForegnd(ColorValue value)](#setShdwForegnd-com.aspose.diagram.ColorValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getShdwForegnd()](../../com.aspose.diagram/fill\#getShdwForegnd--) |
| [setShdwForegndTrans(DoubleValue value)](#setShdwForegndTrans-com.aspose.diagram.DoubleValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getShdwForegndTrans()](../../com.aspose.diagram/fill\#getShdwForegndTrans--) |
| [setShdwPattern(IntValue value)](#setShdwPattern-com.aspose.diagram.IntValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getShdwPattern()](../../com.aspose.diagram/fill\#getShdwPattern--) |
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
### getFillBkgnd() {#getFillBkgnd--}
```
public ColorValue getFillBkgnd()
```


आकार के भराव पैटर्न की पृष्ठभूमि के लिए उपयोग किए जाने वाले रंग को निर्दिष्ट करता है।

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getFillBkgndTrans() {#getFillBkgndTrans--}
```
public DoubleValue getFillBkgndTrans()
```


आकार के भराव पैटर्न की पृष्ठभूमि (भराव) रंग के लिए पारदर्शिता स्तर को निर्दिष्ट करता है, 0 (पूरी तरह अपारदर्शी) से 1 (पूरी तरह पारदर्शी) तक।

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getFillForegnd() {#getFillForegnd--}
```
public ColorValue getFillForegnd()
```


आकार के भराव पैटर्न की अग्रभूमि (स्ट्रोक) के लिए उपयोग किए जाने वाले रंग को निर्दिष्ट करता है।

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getFillForegndTrans() {#getFillForegndTrans--}
```
public DoubleValue getFillForegndTrans()
```


आकार के भराव पैटर्न की अग्रभूमि (भराव) रंग के लिए पारदर्शिता स्तर को निर्दिष्ट करता है, 0 (पूरी तरह अपारदर्शी) से 1 (पूरी तरह पारदर्शी) तक।

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getFillPattern() {#getFillPattern--}
```
public IntValue getFillPattern()
```


आकार के लिए भराव पैटर्न को निर्दिष्ट करता है।

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getGradientFill() {#getGradientFill--}
```
public GradientFill getGradientFill()
```


आकार के वर्तमान ग्रेडिएंट भराव स्वरूपण मान को शामिल करता है।

**Returns:**
[GradientFill](../../com.aspose.diagram/gradientfill)
### getShapeShdwBlur() {#getShapeShdwBlur--}
```
public DoubleValue getShapeShdwBlur()
```


एक आकार की शैडो ब्लर आकार निर्दिष्ट करता है। अभी ब्लर नहीं बना सकते, लेकिन अब vsdx से पार्स कर सकते हैं।

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShapeShdwObliqueAngle() {#getShapeShdwObliqueAngle--}
```
public DoubleValue getShapeShdwObliqueAngle()
```


आकार की छाया की तिरछी दिशा का कोण निर्दिष्ट करता है।

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShapeShdwOffsetX() {#getShapeShdwOffsetX--}
```
public DoubleValue getShapeShdwOffsetX()
```


पृष्ठ इकाइयों में वह दूरी निर्धारित करता है जिससे आकार की छाया आकार से क्षैतिज रूप से ऑफसेट होती है।

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShapeShdwOffsetY() {#getShapeShdwOffsetY--}
```
public DoubleValue getShapeShdwOffsetY()
```


पृष्ठ इकाइयों में वह दूरी निर्धारित करता है जिससे आकार की छाया आकार से लंबवत रूप से ऑफसेट होती है।

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShapeShdwScaleFactor() {#getShapeShdwScaleFactor--}
```
public DoubleValue getShapeShdwScaleFactor()
```


आकार की छाया को कितना प्रतिशत बढ़ाया या घटाया जा सकता है, इसे निर्दिष्ट करता है।

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShapeShdwShow() {#getShapeShdwShow--}
```
public ShapeShdwShow getShapeShdwShow()
```


एक आकार के लिए छाया के प्रकार को निर्दिष्ट करता है।

**Returns:**
[ShapeShdwShow](../../com.aspose.diagram/shapeshdwshow)
### getShapeShdwType() {#getShapeShdwType--}
```
public ShapeShdwType getShapeShdwType()
```


एक आकार के लिए छाया के प्रकार को निर्दिष्ट करता है।

**Returns:**
[ShapeShdwType](../../com.aspose.diagram/shapeshdwtype)
### getShdwBkgnd() {#getShdwBkgnd--}
```
public ColorValue getShdwBkgnd()
```


आकार की ड्रॉप शैडो भराव पैटर्न की पृष्ठभूमि (भराव) के लिए उपयोग किए जाने वाले रंग को निर्दिष्ट करता है।

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getShdwBkgndTrans() {#getShdwBkgndTrans--}
```
public DoubleValue getShdwBkgndTrans()
```


आकार की ड्रॉप शैडो भराव पैटर्न की पृष्ठभूमि (भराव) के लिए पारदर्शिता स्तर को निर्दिष्ट करता है, 0.0 (पूरी तरह अपारदर्शी) से 1.0 (पूरी तरह पारदर्शी) तक।

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwForegnd() {#getShdwForegnd--}
```
public ColorValue getShdwForegnd()
```


आकार की ड्रॉप शैडो भराव पैटर्न की अग्रभूमि (स्ट्रोक) के लिए उपयोग किए जाने वाले रंग को निर्दिष्ट करता है।

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getShdwForegndTrans() {#getShdwForegndTrans--}
```
public DoubleValue getShdwForegndTrans()
```


आकार की ड्रॉप शैडो भराव पैटर्न की अग्रभूमि (स्ट्रोक) के लिए पारदर्शिता स्तर को निर्दिष्ट करता है, 0.0 (पूरी तरह अपारदर्शी) से 1.0 (पूरी तरह पारदर्शी) तक।

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getShdwPattern() {#getShdwPattern--}
```
public IntValue getShdwPattern()
```


आकार की छाया के लिए भराव पैटर्न को निर्दिष्ट करता है।

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
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


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getDel()](../../com.aspose.diagram/fill\#getDel--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setFillBkgnd(ColorValue value) {#setFillBkgnd-com.aspose.diagram.ColorValue-}
```
public void setFillBkgnd(ColorValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getFillBkgnd()](../../com.aspose.diagram/fill\#getFillBkgnd--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setFillBkgndTrans(DoubleValue value) {#setFillBkgndTrans-com.aspose.diagram.DoubleValue-}
```
public void setFillBkgndTrans(DoubleValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getFillBkgndTrans()](../../com.aspose.diagram/fill\#getFillBkgndTrans--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setFillForegnd(ColorValue value) {#setFillForegnd-com.aspose.diagram.ColorValue-}
```
public void setFillForegnd(ColorValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getFillForegnd()](../../com.aspose.diagram/fill\#getFillForegnd--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setFillForegndTrans(DoubleValue value) {#setFillForegndTrans-com.aspose.diagram.DoubleValue-}
```
public void setFillForegndTrans(DoubleValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getFillForegndTrans()](../../com.aspose.diagram/fill\#getFillForegndTrans--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setFillPattern(IntValue value) {#setFillPattern-com.aspose.diagram.IntValue-}
```
public void setFillPattern(IntValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getFillPattern()](../../com.aspose.diagram/fill\#getFillPattern--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setShapeShdwBlur(DoubleValue value) {#setShapeShdwBlur-com.aspose.diagram.DoubleValue-}
```
public void setShapeShdwBlur(DoubleValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getShapeShdwBlur()](../../com.aspose.diagram/fill\#getShapeShdwBlur--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShapeShdwObliqueAngle(DoubleValue value) {#setShapeShdwObliqueAngle-com.aspose.diagram.DoubleValue-}
```
public void setShapeShdwObliqueAngle(DoubleValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getShapeShdwObliqueAngle()](../../com.aspose.diagram/fill\#getShapeShdwObliqueAngle--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShapeShdwOffsetX(DoubleValue value) {#setShapeShdwOffsetX-com.aspose.diagram.DoubleValue-}
```
public void setShapeShdwOffsetX(DoubleValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getShapeShdwOffsetX()](../../com.aspose.diagram/fill\#getShapeShdwOffsetX--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShapeShdwOffsetY(DoubleValue value) {#setShapeShdwOffsetY-com.aspose.diagram.DoubleValue-}
```
public void setShapeShdwOffsetY(DoubleValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getShapeShdwOffsetY()](../../com.aspose.diagram/fill\#getShapeShdwOffsetY--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShapeShdwScaleFactor(DoubleValue value) {#setShapeShdwScaleFactor-com.aspose.diagram.DoubleValue-}
```
public void setShapeShdwScaleFactor(DoubleValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getShapeShdwScaleFactor()](../../com.aspose.diagram/fill\#getShapeShdwScaleFactor--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShapeShdwShow(ShapeShdwShow value) {#setShapeShdwShow-com.aspose.diagram.ShapeShdwShow-}
```
public void setShapeShdwShow(ShapeShdwShow value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getShapeShdwShow()](../../com.aspose.diagram/fill\#getShapeShdwShow--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [ShapeShdwShow](../../com.aspose.diagram/shapeshdwshow) |  |

### setShapeShdwType(ShapeShdwType value) {#setShapeShdwType-com.aspose.diagram.ShapeShdwType-}
```
public void setShapeShdwType(ShapeShdwType value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getShapeShdwType()](../../com.aspose.diagram/fill\#getShapeShdwType--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [ShapeShdwType](../../com.aspose.diagram/shapeshdwtype) |  |

### setShdwBkgnd(ColorValue value) {#setShdwBkgnd-com.aspose.diagram.ColorValue-}
```
public void setShdwBkgnd(ColorValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getShdwBkgnd()](../../com.aspose.diagram/fill\#getShdwBkgnd--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setShdwBkgndTrans(DoubleValue value) {#setShdwBkgndTrans-com.aspose.diagram.DoubleValue-}
```
public void setShdwBkgndTrans(DoubleValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getShdwBkgndTrans()](../../com.aspose.diagram/fill\#getShdwBkgndTrans--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShdwForegnd(ColorValue value) {#setShdwForegnd-com.aspose.diagram.ColorValue-}
```
public void setShdwForegnd(ColorValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getShdwForegnd()](../../com.aspose.diagram/fill\#getShdwForegnd--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setShdwForegndTrans(DoubleValue value) {#setShdwForegndTrans-com.aspose.diagram.DoubleValue-}
```
public void setShdwForegndTrans(DoubleValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getShdwForegndTrans()](../../com.aspose.diagram/fill\#getShdwForegndTrans--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setShdwPattern(IntValue value) {#setShdwPattern-com.aspose.diagram.IntValue-}
```
public void setShdwPattern(IntValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getShdwPattern()](../../com.aspose.diagram/fill\#getShdwPattern--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

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

