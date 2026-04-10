---
title: सुरक्षा
second_title: Aspose.Diagram for Java API Reference
description: लॉकिंग आकृति में अनजाने परिवर्तन को रोकने में मदद करती है, लेकिन अन्य परिस्थितियों में Microsoft Visio को मान रीसेट करने से नहीं रोकती।
type: docs
weight: 312
url: /hi/java/com.aspose.diagram/protection/
---

**Inheritance:**
java.lang.Object
```
public class Protection
```

लॉकिंग आकृति में अनजाने बदलावों को रोकने में मदद करती है लेकिन यह माइक्रोसॉफ्ट विजियो को अन्य परिस्थितियों में मानों को रीसेट करने से नहीं रोकती। यह ShapeSheet विंडो में किए गए बदलावों से भी सुरक्षा नहीं देती।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDel()](#getDel--) | एक फ़्लैग जो दर्शाता है कि तत्व स्थानीय रूप से हटाया गया है या नहीं। |
| [getLockAspect()](#getLockAspect--) | निर्दिष्ट करता है कि क्या आकार का आस्पेक्ट रेशियो लॉक है। |
| [getLockBegin()](#getLockBegin--) | निर्दिष्ट करता है कि क्या 1-D आकार का प्रारंभ बिंदु किसी विशिष्ट स्थान पर लॉक है। |
| [getLockCalcWH()](#getLockCalcWH--) | निर्दिष्ट करता है कि क्या आकार का चयन आयत लॉक है ताकि जब वर्टेक्स संपादित किया जाए या Geom एलिमेंट में एलिमेंट टाइप बदला जाए तो इसे पुनः गणना न किया जा सके। |
| [getLockCrop()](#getLockCrop--) | निर्दिष्ट करता है कि क्या विदेशी ऑब्जेक्ट को Microsoft Visio में Crop टूल से क्रॉप होने से लॉक किया गया है। |
| [getLockCustProp()](#getLockCustProp--) | निर्धारित करता है कि उपयोगकर्ता Define Custom Properties डायलॉग बॉक्स का उपयोग करके यूज़र इंटरफ़ेस (UI) में कस्टम प्रॉपर्टीज़ को जोड़, हट या संशोधित कर सकता है या नहीं। |
| [getLockDelete()](#getLockDelete--) | निर्दिष्ट करता है कि क्या आकार को हटाने से लॉक किया गया है। |
| [getLockEnd()](#getLockEnd--) | निर्दिष्ट करता है कि क्या 1-D आकार का अंत बिंदु किसी विशिष्ट स्थान पर लॉक है। |
| [getLockFormat()](#getLockFormat--) | निर्दिष्ट करता है कि क्या आकार का फ़ॉर्मेटिंग लॉक है ताकि इसे बदला न जा सके। |
| [getLockFromGroupFormat()](#getLockFromGroupFormat--) | Visio यूज़र इंटरफ़ेस में एक सबशेप को अनुमति देता है कि वह पैरेंट ग्रुप शेप पर लागू फ़ॉर्मेटिंग परिवर्तन को ब्लॉक करे, जो अन्यथा व्यक्तिगत ग्रुप शेप्स तक नीचे तक फैल जाएगा। |
| [getLockGroup()](#getLockGroup--) | निर्दिष्ट करता है कि क्या समूह लॉक है ताकि इसे अनग्रुप नहीं किया जा सके। |
| [getLockHeight()](#getLockHeight--) | निर्दिष्ट करता है कि क्या आकार की ऊँचाई लॉक है। |
| [getLockMoveX()](#getLockMoveX--) | निर्दिष्ट करता है कि क्या आकार की क्षैतिज स्थिति लॉक है ताकि इसे क्षैतिज रूप से नहीं हिलाया जा सके। |
| [getLockMoveY()](#getLockMoveY--) | निर्दिष्ट करता है कि क्या आकार की लंबवत स्थिति लॉक है ताकि इसे लंबवत रूप से नहीं हिलाया जा सके। |
| [getLockRotate()](#getLockRotate--) | निर्दिष्ट करता है कि क्या आकार को Microsoft Visio में Rotation टूल या Rotate Left या Rotate Right कमांड्स से घुमाने से लॉक किया गया है। |
| [getLockSelect()](#getLockSelect--) | निर्दिष्ट करता है कि क्या आकार का चयन आयत लॉक है ताकि जब वर्टेक्स संपादित किया जाए या Geom एलिमेंट में एलिमेंट टाइप बदला जाए तो इसे पुनः गणना न किया जा सके। |
| [getLockTextEdit()](#getLockTextEdit--) | निर्दिष्ट करता है कि क्या आकार का टेक्स्ट लॉक है ताकि इसे संपादित नहीं किया जा सके। |
| [getLockThemeColors()](#getLockThemeColors--) | उपयोगकर्ताओं को आकार पर थीम रंग लागू करने से रोकता है। |
| [getLockThemeEffects()](#getLockThemeEffects--) | उपयोगकर्ताओं को आकार पर थीम प्रभाव लागू करने से रोकता है। |
| [getLockVtxEdit()](#getLockVtxEdit--) | निर्दिष्ट करता है कि क्या आकार के शीर्ष बिंदु लॉक हैं ताकि उन्हें टूलबार के किसी भी उपकरण से संपादित न किया जा सके। |
| [getLockWidth()](#getLockWidth--) | निर्दिष्ट करता है कि क्या आकार की चौड़ाई लॉक है ताकि आकार को पुनः आकार देने पर भी वह अपरिवर्तित रहे। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | इस गुण के विवरण के लिए, कृपया देखें [getDel()](../../com.aspose.diagram/protection\#getDel--) |
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
### getDel() {#getDel--}
```
public int getDel()
```


एक फ़्लैग जो दर्शाता है कि तत्व स्थानीय रूप से हटाया गया है या नहीं। मान 1 यह संकेत देता है कि तत्व स्थानीय रूप से हटाया गया था।

**Returns:**
int
### getLockAspect() {#getLockAspect--}
```
public BoolValue getLockAspect()
```


निर्दिष्ट करता है कि क्या आकार का अनुपात लॉक है। यदि लॉक है, तो आकार केवल अनुपातिक रूप से आकार बदल सकता है; इसे एकल आयाम में नहीं बदला जा सकता।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockBegin() {#getLockBegin--}
```
public BoolValue getLockBegin()
```


निर्दिष्ट करता है कि क्या 1-D आकार का प्रारंभ बिंदु किसी विशिष्ट स्थान पर लॉक है।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockCalcWH() {#getLockCalcWH--}
```
public BoolValue getLockCalcWH()
```


निर्दिष्ट करता है कि क्या आकार का चयन आयत लॉक है ताकि जब वर्टेक्स संपादित किया जाए या Geom एलिमेंट में एलिमेंट टाइप बदला जाए तो इसे पुनः गणना न किया जा सके।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockCrop() {#getLockCrop--}
```
public BoolValue getLockCrop()
```


निर्दिष्ट करता है कि क्या विदेशी ऑब्जेक्ट को Microsoft Visio में Crop टूल से क्रॉप होने से लॉक किया गया है।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockCustProp() {#getLockCustProp--}
```
public BoolValue getLockCustProp()
```


निर्धारित करता है कि उपयोगकर्ता Define Custom Properties डायलॉग बॉक्स का उपयोग करके यूज़र इंटरफ़ेस (UI) में कस्टम प्रॉपर्टीज़ को जोड़, हट या संशोधित कर सकता है या नहीं।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockDelete() {#getLockDelete--}
```
public BoolValue getLockDelete()
```


निर्दिष्ट करता है कि क्या आकार को हटाने से लॉक किया गया है।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockEnd() {#getLockEnd--}
```
public BoolValue getLockEnd()
```


निर्दिष्ट करता है कि क्या 1-D आकार का अंत बिंदु किसी विशिष्ट स्थान पर लॉक है।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockFormat() {#getLockFormat--}
```
public BoolValue getLockFormat()
```


निर्दिष्ट करता है कि क्या आकार का स्वरूपण लॉक है ताकि इसे बदला न जा सके। विशेष रूप से, यह तत्व टेक्स्ट, रेखा और भराव स्वरूपण को बदलने या आकार द्वारा विरासत में मिलने वाले Style तत्व को बदलने से बचाता है।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockFromGroupFormat() {#getLockFromGroupFormat--}
```
public BoolValue getLockFromGroupFormat()
```


Visio यूज़र इंटरफ़ेस में एक सबशेप को अनुमति देता है कि वह पैरेंट ग्रुप शेप पर लागू फ़ॉर्मेटिंग परिवर्तन को ब्लॉक करे, जो अन्यथा व्यक्तिगत ग्रुप शेप्स तक नीचे तक फैल जाएगा।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockGroup() {#getLockGroup--}
```
public BoolValue getLockGroup()
```


निर्दिष्ट करता है कि क्या समूह लॉक है ताकि इसे अनग्रुप नहीं किया जा सके।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockHeight() {#getLockHeight--}
```
public BoolValue getLockHeight()
```


निर्दिष्ट करता है कि क्या आकार की ऊँचाई लॉक है। यदि लॉक है, तो आकार को पुनः आकार देने पर उसकी ऊँचाई अपरिवर्तित रहती है।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockMoveX() {#getLockMoveX--}
```
public BoolValue getLockMoveX()
```


निर्दिष्ट करता है कि क्या आकार की क्षैतिज स्थिति लॉक है ताकि इसे क्षैतिज रूप से नहीं हिलाया जा सके।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockMoveY() {#getLockMoveY--}
```
public BoolValue getLockMoveY()
```


निर्दिष्ट करता है कि क्या आकार की लंबवत स्थिति लॉक है ताकि इसे लंबवत रूप से नहीं हिलाया जा सके।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockRotate() {#getLockRotate--}
```
public BoolValue getLockRotate()
```


निर्दिष्ट करता है कि क्या आकार को Microsoft Visio में Rotation टूल या Rotate Left या Rotate Right कमांड्स से घुमाने से लॉक किया गया है।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockSelect() {#getLockSelect--}
```
public BoolValue getLockSelect()
```


निर्दिष्ट करता है कि क्या आकार का चयन आयत लॉक है ताकि जब वर्टेक्स संपादित किया जाए या Geom एलिमेंट में एलिमेंट टाइप बदला जाए तो इसे पुनः गणना न किया जा सके।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockTextEdit() {#getLockTextEdit--}
```
public BoolValue getLockTextEdit()
```


निर्दिष्ट करता है कि क्या आकार का टेक्स्ट लॉक है ताकि इसे संपादित न किया जा सके। हालांकि, टेक्स्ट को अभी भी एक शैली लागू करके, टेक्स्ट संवाद बॉक्स के फ़ॉन्ट टैब पर Style विकल्पों का उपयोग करके स्वरूपित किया जा सकता है।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockThemeColors() {#getLockThemeColors--}
```
public BoolValue getLockThemeColors()
```


उपयोगकर्ताओं को आकार पर थीम रंग लागू करने से रोकता है।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockThemeEffects() {#getLockThemeEffects--}
```
public BoolValue getLockThemeEffects()
```


उपयोगकर्ताओं को आकार पर थीम प्रभाव लागू करने से रोकता है।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockVtxEdit() {#getLockVtxEdit--}
```
public BoolValue getLockVtxEdit()
```


निर्दिष्ट करता है कि क्या आकार के शीर्ष बिंदु लॉक हैं ताकि उन्हें टूलबार के किसी भी उपकरण से संपादित न किया जा सके।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLockWidth() {#getLockWidth--}
```
public BoolValue getLockWidth()
```


निर्दिष्ट करता है कि क्या आकार की चौड़ाई लॉक है ताकि आकार को पुनः आकार देने पर भी वह अपरिवर्तित रहे।

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


इस गुण के विवरण के लिए, कृपया देखें [getDel()](../../com.aspose.diagram/protection\#getDel--)

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

