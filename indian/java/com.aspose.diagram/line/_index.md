---
title: Line
second_title: Aspose.Diagram for Java API Reference
description: आकार के बारे में सामान्य पोजिशनिंग जानकारी निर्दिष्ट करने वाले तत्व शामिल हैं।
type: docs
weight: 221
url: /hi/java/com.aspose.diagram/line/
---

**Inheritance:**
java.lang.Object
```
public class Line
```

आकार के बारे में सामान्य पोजिशनिंग जानकारी निर्दिष्ट करने वाले तत्व शामिल हैं।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [deepClone()](#deepClone--) | इस उदाहरण की गहरी प्रतिलिपि बनाता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBeginArrow()](#getBeginArrow--) | निर्देशित करता है कि क्या किसी रेखा के पहले शीर्ष पर तीरमुख या अन्य रेखा अंत प्रारूप है। |
| [getBeginArrowSize()](#getBeginArrowSize--) | रेखा की शुरुआत में तीरमुख का आकार निर्धारित करता है। |
| [getClass()](#getClass--) |  |
| [getCompoundType()](#getCompoundType--) | आकार के रेखा CompoundType को निर्दिष्ट करता है। |
| [getDel()](#getDel--) | एक फ़्लैग जो दर्शाता है कि तत्व स्थानीय रूप से हटाया गया है या नहीं। |
| [getEndArrow()](#getEndArrow--) | निर्देशित करता है कि क्या रेखा के अंतिम शीर्ष पर तीरमुख या अन्य रेखा‑अंत प्रारूप है। |
| [getEndArrowSize()](#getEndArrowSize--) | रेखा के अंत में तीरमुख का आकार निर्दिष्ट करता है। |
| [getGradientLine()](#getGradientLine--) | आकार के लिए वर्तमान ग्रेडिएंट रेखा स्वरूपण मानों को शामिल करता है |
| [getLineCap()](#getLineCap--) | निर्दिष्ट करता है कि रेखा के अंत गोलाकार हैं या वर्गाकार। |
| [getLineColor()](#getLineColor--) | आकार के रेखा रंग को निर्दिष्ट करता है। |
| [getLineColorTrans()](#getLineColorTrans--) | आकार की रेखा रंग की पारदर्शिता स्तर को निर्दिष्ट करता है, 0 (अस्पष्ट) से 1 (पूरी तरह पारदर्शी) तक। |
| [getLinePattern()](#getLinePattern--) | आकार के रेखा पैटर्न को निर्दिष्ट करता है |
| [getLineWeight()](#getLineWeight--) | आकार के रेखा वजन को निर्दिष्ट करता है। |
| [getRounding()](#getRounding--) | पथ के दो क्रमिक खंडों के मिलने पर लागू होने वाले गोलाई चाप की त्रिज्या को निर्दिष्ट करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBeginArrow(IntValue value)](#setBeginArrow-com.aspose.diagram.IntValue-) | इस गुण के विवरण के लिए, कृपया देखें [getBeginArrow()](../../com.aspose.diagram/line\#getBeginArrow--) |
| [setBeginArrowSize(ArrowSize value)](#setBeginArrowSize-com.aspose.diagram.ArrowSize-) | इस गुण के विवरण के लिए, कृपया देखें [getBeginArrowSize()](../../com.aspose.diagram/line\#getBeginArrowSize--) |
| [setCompoundType(CompoundType value)](#setCompoundType-com.aspose.diagram.CompoundType-) | इस गुण के विवरण के लिए, कृपया देखें [getCompoundType()](../../com.aspose.diagram/line\#getCompoundType--) |
| [setDel(int value)](#setDel-int-) | इस गुण के विवरण के लिए, कृपया देखें [getDel()](../../com.aspose.diagram/line\#getDel--) |
| [setEndArrow(IntValue value)](#setEndArrow-com.aspose.diagram.IntValue-) | इस गुण के विवरण के लिए, कृपया देखें [getEndArrow()](../../com.aspose.diagram/line\#getEndArrow--) |
| [setEndArrowSize(ArrowSize value)](#setEndArrowSize-com.aspose.diagram.ArrowSize-) | इस गुण के विवरण के लिए, कृपया देखें [getEndArrowSize()](../../com.aspose.diagram/line\#getEndArrowSize--) |
| [setLineCap(BoolValue value)](#setLineCap-com.aspose.diagram.BoolValue-) | इस गुण के विवरण के लिए, कृपया देखें [getLineCap()](../../com.aspose.diagram/line\#getLineCap--) |
| [setLineColor(ColorValue value)](#setLineColor-com.aspose.diagram.ColorValue-) | इस गुण के विवरण के लिए, कृपया देखें [getLineColor()](../../com.aspose.diagram/line\#getLineColor--) |
| [setLineColorTrans(DoubleValue value)](#setLineColorTrans-com.aspose.diagram.DoubleValue-) | इस गुण के विवरण के लिए, कृपया देखें [getLineColorTrans()](../../com.aspose.diagram/line\#getLineColorTrans--) |
| [setLinePattern(IntValue value)](#setLinePattern-com.aspose.diagram.IntValue-) | इस गुण के विवरण के लिए, कृपया देखें [getLinePattern()](../../com.aspose.diagram/line\#getLinePattern--) |
| [setLineWeight(DoubleValue value)](#setLineWeight-com.aspose.diagram.DoubleValue-) | इस गुण के विवरण के लिए, कृपया देखें [getLineWeight()](../../com.aspose.diagram/line\#getLineWeight--) |
| [setRounding(DoubleValue value)](#setRounding-com.aspose.diagram.DoubleValue-) | इस गुण के विवरण के लिए, कृपया देखें [getRounding()](../../com.aspose.diagram/line\#getRounding--) |
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
### getBeginArrow() {#getBeginArrow--}
```
public IntValue getBeginArrow()
```


निर्देशित करता है कि क्या रेखा के पहले शीर्ष पर तीरमुख या अन्य रेखा अंत प्रारूप है। 0 से 45 तक का संख्या दर्ज करें या कस्टम रेखा अंत के नाम के साथ USE फ़ंक्शन का उपयोग करें।

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getBeginArrowSize() {#getBeginArrowSize--}
```
public ArrowSize getBeginArrowSize()
```


रेखा की शुरुआत में तीर के सिर का आकार निर्धारित करता है। 0 से 6 तक की संख्या दर्ज करें।

**Returns:**
[ArrowSize](../../com.aspose.diagram/arrowsize)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCompoundType() {#getCompoundType--}
```
public CompoundType getCompoundType()
```


आकार के रेखा CompoundType को निर्दिष्ट करता है।

**Returns:**
[CompoundType](../../com.aspose.diagram/compoundtype)
### getDel() {#getDel--}
```
public int getDel()
```


एक फ़्लैग जो दर्शाता है कि तत्व स्थानीय रूप से हटाया गया है या नहीं। मान 1 यह संकेत देता है कि तत्व स्थानीय रूप से हटाया गया था।

**Returns:**
int
### getEndArrow() {#getEndArrow--}
```
public IntValue getEndArrow()
```


निर्देशित करता है कि क्या रेखा के अंतिम शीर्ष पर तीरमुख या अन्य रेखा‑अंत प्रारूप है।

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getEndArrowSize() {#getEndArrowSize--}
```
public ArrowSize getEndArrowSize()
```


रेखा के अंत में तीरमुख का आकार निर्दिष्ट करता है।

**Returns:**
[ArrowSize](../../com.aspose.diagram/arrowsize)
### getGradientLine() {#getGradientLine--}
```
public GradientFill getGradientLine()
```


आकार के लिए वर्तमान ग्रेडिएंट रेखा स्वरूपण मानों को शामिल करता है

**Returns:**
[GradientFill](../../com.aspose.diagram/gradientfill)
### getLineCap() {#getLineCap--}
```
public BoolValue getLineCap()
```


निर्दिष्ट करता है कि रेखा के अंत गोलाकार हैं या वर्गाकार।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLineColor() {#getLineColor--}
```
public ColorValue getLineColor()
```


आकार के रेखा रंग को निर्दिष्ट करता है।

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getLineColorTrans() {#getLineColorTrans--}
```
public DoubleValue getLineColorTrans()
```


एक आकार की रेखा रंग की पारदर्शिता स्तर को निर्दिष्ट करता है, 0 (अपारदर्शी) से 1 (पूरी तरह पारदर्शी) तक। डिफ़ॉल्ट 0 है।

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLinePattern() {#getLinePattern--}
```
public IntValue getLinePattern()
```


आकार के रेखा पैटर्न को निर्दिष्ट करता है

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getLineWeight() {#getLineWeight--}
```
public DoubleValue getLineWeight()
```


एक आकार की रेखा मोटाई को निर्दिष्ट करता है। रेखा मोटाई ड्राइंग के स्केल से स्वतंत्र होती है। यदि ड्राइंग को स्केल किया जाता है, तो रेखा मोटाई समान रहती है।

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getRounding() {#getRounding--}
```
public DoubleValue getRounding()
```


पथ के दो निरंतर खंडों के मिलने पर लागू होने वाले गोलाई चाप की त्रिज्या को निर्दिष्ट करता है। उदाहरण के लिए, गोलाई का उपयोग करके आयत के कोनों को गोल किया जा सकता है।

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




### setBeginArrow(IntValue value) {#setBeginArrow-com.aspose.diagram.IntValue-}
```
public void setBeginArrow(IntValue value)
```


इस गुण के विवरण के लिए, कृपया देखें [getBeginArrow()](../../com.aspose.diagram/line\#getBeginArrow--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setBeginArrowSize(ArrowSize value) {#setBeginArrowSize-com.aspose.diagram.ArrowSize-}
```
public void setBeginArrowSize(ArrowSize value)
```


इस गुण के विवरण के लिए, कृपया देखें [getBeginArrowSize()](../../com.aspose.diagram/line\#getBeginArrowSize--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [ArrowSize](../../com.aspose.diagram/arrowsize) |  |

### setCompoundType(CompoundType value) {#setCompoundType-com.aspose.diagram.CompoundType-}
```
public void setCompoundType(CompoundType value)
```


इस गुण के विवरण के लिए, कृपया देखें [getCompoundType()](../../com.aspose.diagram/line\#getCompoundType--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [CompoundType](../../com.aspose.diagram/compoundtype) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


इस गुण के विवरण के लिए, कृपया देखें [getDel()](../../com.aspose.diagram/line\#getDel--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setEndArrow(IntValue value) {#setEndArrow-com.aspose.diagram.IntValue-}
```
public void setEndArrow(IntValue value)
```


इस गुण के विवरण के लिए, कृपया देखें [getEndArrow()](../../com.aspose.diagram/line\#getEndArrow--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setEndArrowSize(ArrowSize value) {#setEndArrowSize-com.aspose.diagram.ArrowSize-}
```
public void setEndArrowSize(ArrowSize value)
```


इस गुण के विवरण के लिए, कृपया देखें [getEndArrowSize()](../../com.aspose.diagram/line\#getEndArrowSize--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [ArrowSize](../../com.aspose.diagram/arrowsize) |  |

### setLineCap(BoolValue value) {#setLineCap-com.aspose.diagram.BoolValue-}
```
public void setLineCap(BoolValue value)
```


इस गुण के विवरण के लिए, कृपया देखें [getLineCap()](../../com.aspose.diagram/line\#getLineCap--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setLineColor(ColorValue value) {#setLineColor-com.aspose.diagram.ColorValue-}
```
public void setLineColor(ColorValue value)
```


इस गुण के विवरण के लिए, कृपया देखें [getLineColor()](../../com.aspose.diagram/line\#getLineColor--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setLineColorTrans(DoubleValue value) {#setLineColorTrans-com.aspose.diagram.DoubleValue-}
```
public void setLineColorTrans(DoubleValue value)
```


इस गुण के विवरण के लिए, कृपया देखें [getLineColorTrans()](../../com.aspose.diagram/line\#getLineColorTrans--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setLinePattern(IntValue value) {#setLinePattern-com.aspose.diagram.IntValue-}
```
public void setLinePattern(IntValue value)
```


इस गुण के विवरण के लिए, कृपया देखें [getLinePattern()](../../com.aspose.diagram/line\#getLinePattern--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setLineWeight(DoubleValue value) {#setLineWeight-com.aspose.diagram.DoubleValue-}
```
public void setLineWeight(DoubleValue value)
```


इस गुण के विवरण के लिए, कृपया देखें [getLineWeight()](../../com.aspose.diagram/line\#getLineWeight--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setRounding(DoubleValue value) {#setRounding-com.aspose.diagram.DoubleValue-}
```
public void setRounding(DoubleValue value)
```


इस गुण के विवरण के लिए, कृपया देखें [getRounding()](../../com.aspose.diagram/line\#getRounding--)

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

