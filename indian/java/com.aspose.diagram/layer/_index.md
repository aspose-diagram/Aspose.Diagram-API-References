---
title: Layer
second_title: Aspose.Diagram for Java API Reference
description: पृष्ठ के लिए एकल लेयर और उसकी गुणों को परिभाषित करने वाले तत्व शामिल हैं।
type: docs
weight: 212
url: /hi/java/com.aspose.diagram/layer/
---

**Inheritance:**
java.lang.Object
```
public class Layer
```

पृष्ठ के लिए एकल लेयर और उसकी गुणों को परिभाषित करने वाले तत्व शामिल हैं।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [Layer()](#Layer--) | कंस्ट्रक्टर। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActive()](#getActive--) | निर्दिष्ट करता है कि कोई लेयर सक्रिय है या नहीं। |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | लेयर को प्रदर्शित करने के लिए उपयोग की गई रंग तालिका में रंग का सूचकांक या एक RGB मान जो रंग तालिका में नहीं है (उदाहरण के लिए, \#ff9900)। |
| [getColorTrans()](#getColorTrans--) | परत या आकार के पाठ रंग की पारदर्शिता की डिग्री निर्धारित करता है, 0 (पूरी तरह अपारदर्शी) से 1 (पूरी तरह पारदर्शी) तक। |
| [getDel()](#getDel--) | एक फ़्लैग जो दर्शाता है कि तत्व स्थानीय रूप से हटाया गया है या नहीं। |
| [getGlue()](#getGlue--) | निर्दिष्ट करता है कि लेयर से संबंधित आकारों को चिपकाया जा सकता है या नहीं। |
| [getIX()](#getIX--) | उसके पैरेंट तत्व के भीतर तत्व का शून्य-आधारित सूचकांक। |
| [getLock()](#getLock--) | निर्दिष्ट करता है कि लेयर से संबंधित आकारों को चयन या संपादन से रोकने के लिए लॉक किया गया है या नहीं। |
| [getName()](#getName--) | Name तत्व लेयर का नाम निर्दिष्ट करता है। |
| [getNameUniv()](#getNameUniv--) | लेयर का सार्वभौमिक नाम निर्दिष्ट करता है। |
| [getPrint()](#getPrint--) | निर्दिष्ट करता है कि ड्राइंग प्रिंट होने पर लेयर से संबंधित आकार प्रिंट होते हैं या नहीं। |
| [getSnap()](#getSnap--) | निर्दिष्ट करता है कि अन्य आकार लेयर को सौंपे गए आकारों से स्नैप कर सकते हैं या नहीं। |
| [getStatus()](#getStatus--) | निर्दिष्ट करता है कि लेयर दस्तावेज़ के लिए वैध लेयर है या नहीं। |
| [getVisible()](#getVisible--) | निर्दिष्ट करता है कि लेयर से संबंधित आकार ड्राइंग पृष्ठ पर दिखाई देते हैं या नहीं। |
| [hashCode()](#hashCode--) |  |
| [isColorChecked()](#isColorChecked--) | एक फ़्लैग जो दर्शाता है कि तत्व को स्थानीय रूप से जाँच किया गया है या नहीं। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setColorChecked(int value)](#setColorChecked-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [isColorChecked()](../../com.aspose.diagram/layer\#isColorChecked--) |
| [setDel(int value)](#setDel-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getDel()](../../com.aspose.diagram/layer\#getDel--) |
| [setIX(int value)](#setIX-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getIX()](../../com.aspose.diagram/layer\#getIX--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Layer() {#Layer--}
```
public Layer()
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
### getActive() {#getActive--}
```
public BoolValue getActive()
```


निर्दिष्ट करता है कि लेयर सक्रिय है या नहीं। लेयर को पहले से सौंपे न गए आकार ड्राइंग पृष्ठ पर गिराने पर सक्रिय लेयर(ओं) को सौंपे जाते हैं।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public ColorValue getColor()
```


लेयर को प्रदर्शित करने के लिए उपयोग की गई रंग तालिका में रंग का सूचकांक या एक RGB मान जो रंग तालिका में नहीं है (उदाहरण के लिए, \#ff9900)।

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getColorTrans() {#getColorTrans--}
```
public DoubleValue getColorTrans()
```


परत या आकार के पाठ रंग की पारदर्शिता की डिग्री निर्धारित करता है, 0 (पूरी तरह अपारदर्शी) से 1 (पूरी तरह पारदर्शी) तक।

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDel() {#getDel--}
```
public int getDel()
```


एक फ़्लैग जो दर्शाता है कि तत्व स्थानीय रूप से हटाया गया है या नहीं। मान 1 यह संकेत देता है कि तत्व स्थानीय रूप से हटाया गया था।

**Returns:**
int
### getGlue() {#getGlue--}
```
public BoolValue getGlue()
```


निर्दिष्ट करता है कि लेयर से संबंधित आकारों को चिपकाया जा सकता है या नहीं।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getIX() {#getIX--}
```
public int getIX()
```


उसके पैरेंट तत्व के भीतर तत्व का शून्य-आधारित सूचकांक।

**Returns:**
int
### getLock() {#getLock--}
```
public BoolValue getLock()
```


निर्दिष्ट करता है कि लेयर से संबंधित आकारों को चयन या संपादन से रोकने के लिए लॉक किया गया है या नहीं।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getName() {#getName--}
```
public Str2Value getName()
```


Name तत्व लेयर का नाम निर्दिष्ट करता है।

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getNameUniv() {#getNameUniv--}
```
public Str2Value getNameUniv()
```


लेयर का सार्वभौमिक नाम निर्दिष्ट करता है।

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getPrint() {#getPrint--}
```
public BoolValue getPrint()
```


निर्दिष्ट करता है कि ड्राइंग प्रिंट होने पर लेयर से संबंधित आकार प्रिंट होते हैं या नहीं।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getSnap() {#getSnap--}
```
public BoolValue getSnap()
```


निर्दिष्ट करता है कि अन्य आकार लेयर को सौंपे गए आकारों से स्नैप कर सकते हैं या नहीं। लेयर को सौंपे गए आकार अन्य आकारों से स्नैप कर सकते हैं, लेकिन अन्य आकार उनसे स्नैप नहीं कर सकते।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getStatus() {#getStatus--}
```
public BoolValue getStatus()
```


निर्दिष्ट करता है कि लेयर दस्तावेज़ के लिए वैध लेयर है या नहीं।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getVisible() {#getVisible--}
```
public BoolValue getVisible()
```


निर्दिष्ट करता है कि लेयर से संबंधित आकार ड्राइंग पृष्ठ पर दिखाई देते हैं या नहीं।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isColorChecked() {#isColorChecked--}
```
public int isColorChecked()
```


एक फ़्लैग जो दर्शाता है कि तत्व को स्थानीय रूप से जाँच किया गया है। मान 1 यह दर्शाता है कि तत्व स्थानीय रूप से जाँच किया गया था।

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




### setColorChecked(int value) {#setColorChecked-int-}
```
public void setColorChecked(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [isColorChecked()](../../com.aspose.diagram/layer\#isColorChecked--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getDel()](../../com.aspose.diagram/layer\#getDel--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getIX()](../../com.aspose.diagram/layer\#getIX--)

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

