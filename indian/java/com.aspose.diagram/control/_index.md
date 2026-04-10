---
title: नियंत्रण
second_title: Aspose.Diagram for Java API Reference
description: एक आकार के लिए परिभाषित प्रत्येक नियंत्रण हैंडल के x- और y-निर्देशांक के तत्वों और उन तत्वों को शामिल करता है जो निर्धारित करते हैं कि नियंत्रण हैंडल कैसे व्यवहार करे।
type: docs
weight: 87
url: /hi/java/com.aspose.diagram/control/
---

**Inheritance:**
java.lang.Object
```
public class Control
```

एक आकार के लिए परिभाषित प्रत्येक नियंत्रण हैंडल के x और y-निर्देशांक के तत्वों को शामिल करता है, तथा उन तत्वों को जो निर्धारित करते हैं कि नियंत्रण हैंडल कैसे व्यवहार करे।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [Control()](#Control--) | कंस्ट्रक्टर। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [canGlue()](#canGlue--) | निर्धारित करता है कि क्या एक नियंत्रण हैंडल को अन्य आकारों से चिपकाया जा सकता है। |
| [deepClone()](#deepClone--) | इस उदाहरण की गहरी प्रतिलिपि बनाता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | एक फ़्लैग जो दर्शाता है कि तत्व स्थानीय रूप से हटाया गया है या नहीं। |
| [getID()](#getID--) | तत्व के अपने पैरेंट तत्व के भीतर अद्वितीय ID। |
| [getIX()](#getIX--) | उसके पैरेंट तत्व के भीतर तत्व का शून्य-आधारित सूचकांक। |
| [getName()](#getName--) | तत्व का नाम। |
| [getNameU()](#getNameU--) | तत्व का सार्वभौमिक नाम। |
| [getPrompt()](#getPrompt--) | प्रॉम्प्ट तत्व वर्णनात्मक पाठ निर्दिष्ट करता है जो तब टूलटिप के रूप में दिखाई देता है जब माउस पॉइंटर को किसी आकार के नियंत्रण हैंडल पर रोका जाता है। |
| [getX()](#getX--) | x-निर्देशांक जो किसी आकार के नियंत्रण हैंडल का स्थान दर्शाता है। |
| [getXCon()](#getXCon--) | नियंत्रण हैंडल के x-निर्देशांक द्वारा हिलाने के बाद प्रदर्शित व्यवहार के प्रकार को निर्दिष्ट करता है। |
| [getXDyn()](#getXDyn--) | स्थानीय निर्देशांकों में नियंत्रण हैंडल के एंकर बिंदु के लिए x-निर्देशांक निर्दिष्ट करता है। |
| [getY()](#getY--) | y-निर्देशांक जो किसी आकार के नियंत्रण हैंडल का स्थान दर्शाता है। |
| [getYCon()](#getYCon--) | नियंत्रण हैंडल के x-निर्देशांक द्वारा हिलाने के बाद प्रदर्शित व्यवहार के प्रकार को निर्दिष्ट करता है। |
| [getYDyn()](#getYDyn--) | स्थानीय निर्देशांकों में नियंत्रण हैंडल के एंकर बिंदु के लिए y-निर्देशांक निर्दिष्ट करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCanGlue(BoolValue value)](#setCanGlue-com.aspose.diagram.BoolValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [canGlue()](../../com.aspose.diagram/control\#canGlue--) |
| [setDel(int value)](#setDel-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getDel()](../../com.aspose.diagram/control\#getDel--) |
| [setID(int value)](#setID-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getID()](../../com.aspose.diagram/control\#getID--) |
| [setIX(int value)](#setIX-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getIX()](../../com.aspose.diagram/control\#getIX--) |
| [setName(String value)](#setName-java.lang.String-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getName()](../../com.aspose.diagram/control\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getNameU()](../../com.aspose.diagram/control\#getNameU--) |
| [setPrompt(Str2Value value)](#setPrompt-com.aspose.diagram.Str2Value-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getPrompt()](../../com.aspose.diagram/control\#getPrompt--) |
| [setX(DoubleValue value)](#setX-com.aspose.diagram.DoubleValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getX()](../../com.aspose.diagram/control\#getX--) |
| [setXCon(ConType value)](#setXCon-com.aspose.diagram.ConType-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getXCon()](../../com.aspose.diagram/control\#getXCon--) |
| [setXDyn(DoubleValue value)](#setXDyn-com.aspose.diagram.DoubleValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getXDyn()](../../com.aspose.diagram/control\#getXDyn--) |
| [setY(DoubleValue value)](#setY-com.aspose.diagram.DoubleValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getY()](../../com.aspose.diagram/control\#getY--) |
| [setYCon(ConType value)](#setYCon-com.aspose.diagram.ConType-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getYCon()](../../com.aspose.diagram/control\#getYCon--) |
| [setYDyn(DoubleValue value)](#setYDyn-com.aspose.diagram.DoubleValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getYDyn()](../../com.aspose.diagram/control\#getYDyn--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Control() {#Control--}
```
public Control()
```


कंस्ट्रक्टर।

### canGlue() {#canGlue--}
```
public BoolValue canGlue()
```


निर्धारित करता है कि क्या एक नियंत्रण हैंडल को अन्य आकारों से चिपकाया जा सकता है।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
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
### getID() {#getID--}
```
public int getID()
```


तत्व के अपने पैरेंट तत्व के भीतर अद्वितीय ID।

**Returns:**
int
### getIX() {#getIX--}
```
public int getIX()
```


उसके पैरेंट तत्व के भीतर तत्व का शून्य-आधारित सूचकांक।

**Returns:**
int
### getName() {#getName--}
```
public String getName()
```


तत्व का नाम।

**Returns:**
java.lang.String
### getNameU() {#getNameU--}
```
public String getNameU()
```


तत्व का सार्वभौमिक नाम।

**Returns:**
java.lang.String
### getPrompt() {#getPrompt--}
```
public Str2Value getPrompt()
```


प्रॉम्प्ट तत्व वर्णनात्मक पाठ निर्दिष्ट करता है जो तब टूलटिप के रूप में दिखाई देता है जब माउस पॉइंटर को किसी आकार के नियंत्रण हैंडल पर रोका जाता है।

**Returns:**
[Str2Value](../../com.aspose.diagram/str2value)
### getX() {#getX--}
```
public DoubleValue getX()
```


x-निर्देशांक जो किसी आकार के नियंत्रण हैंडल का स्थान दर्शाता है।

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getXCon() {#getXCon--}
```
public ConType getXCon()
```


नियंत्रण हैंडल के x-निर्देशांक द्वारा हिलाने के बाद प्रदर्शित व्यवहार के प्रकार को निर्दिष्ट करता है।

**Returns:**
[ConType](../../com.aspose.diagram/contype)
### getXDyn() {#getXDyn--}
```
public DoubleValue getXDyn()
```


स्थानीय निर्देशांक में कंट्रोल हैंडल के एंकर पॉइंट के लिए x-निर्देशांक निर्दिष्ट करता है। एंकर पॉइंट डायनामिक्स के दौरान रबर-बैंडिंग के लिए उपयोग किया जाता है।

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getY() {#getY--}
```
public DoubleValue getY()
```


y-निर्देशांक जो किसी आकार के नियंत्रण हैंडल का स्थान दर्शाता है।

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getYCon() {#getYCon--}
```
public ConType getYCon()
```


नियंत्रण हैंडल के x-निर्देशांक द्वारा हिलाने के बाद प्रदर्शित व्यवहार के प्रकार को निर्दिष्ट करता है।

**Returns:**
[ConType](../../com.aspose.diagram/contype)
### getYDyn() {#getYDyn--}
```
public DoubleValue getYDyn()
```


स्थानीय निर्देशांक में कंट्रोल हैंडल के एंकर पॉइंट के लिए y-निर्देशांक निर्दिष्ट करता है। एंकर पॉइंट डायनामिक्स के दौरान रबर-बैंडिंग के लिए उपयोग किया जाता है।

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




### setCanGlue(BoolValue value) {#setCanGlue-com.aspose.diagram.BoolValue-}
```
public void setCanGlue(BoolValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [canGlue()](../../com.aspose.diagram/control\#canGlue--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getDel()](../../com.aspose.diagram/control\#getDel--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getID()](../../com.aspose.diagram/control\#getID--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getIX()](../../com.aspose.diagram/control\#getIX--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getName()](../../com.aspose.diagram/control\#getName--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getNameU()](../../com.aspose.diagram/control\#getNameU--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setPrompt(Str2Value value) {#setPrompt-com.aspose.diagram.Str2Value-}
```
public void setPrompt(Str2Value value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getPrompt()](../../com.aspose.diagram/control\#getPrompt--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [Str2Value](../../com.aspose.diagram/str2value) |  |

### setX(DoubleValue value) {#setX-com.aspose.diagram.DoubleValue-}
```
public void setX(DoubleValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getX()](../../com.aspose.diagram/control\#getX--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setXCon(ConType value) {#setXCon-com.aspose.diagram.ConType-}
```
public void setXCon(ConType value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getXCon()](../../com.aspose.diagram/control\#getXCon--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [ConType](../../com.aspose.diagram/contype) |  |

### setXDyn(DoubleValue value) {#setXDyn-com.aspose.diagram.DoubleValue-}
```
public void setXDyn(DoubleValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getXDyn()](../../com.aspose.diagram/control\#getXDyn--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setY(DoubleValue value) {#setY-com.aspose.diagram.DoubleValue-}
```
public void setY(DoubleValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getY()](../../com.aspose.diagram/control\#getY--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setYCon(ConType value) {#setYCon-com.aspose.diagram.ConType-}
```
public void setYCon(ConType value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getYCon()](../../com.aspose.diagram/control\#getYCon--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [ConType](../../com.aspose.diagram/contype) |  |

### setYDyn(DoubleValue value) {#setYDyn-com.aspose.diagram.DoubleValue-}
```
public void setYDyn(DoubleValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getYDyn()](../../com.aspose.diagram/control\#getYDyn--)

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

