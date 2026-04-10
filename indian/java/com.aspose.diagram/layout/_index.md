---
title: लेआउट
second_title: Aspose.Diagram for Java API Reference
description: आकार की प्लेसमेंट और कनेक्टर रूटिंग सेटिंग्स को नियंत्रित करने वाले तत्व शामिल हैं।
type: docs
weight: 215
url: /hi/java/com.aspose.diagram/layout/
---

**Inheritance:**
java.lang.Object
```
public class Layout
```

आकार की प्लेसमेंट और कनेक्टर रूटिंग सेटिंग्स को नियंत्रित करने वाले तत्व शामिल हैं।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getConFixedCode()](#getConFixedCode--) | निर्धारित करता है कि कनेक्टर कब पुनः मार्गित होता है। |
| [getConLineJumpCode()](#getConLineJumpCode--) | निर्धारित करता है कि दो कनेक्टरों के क्रॉस होने पर कनेक्टर कूदता है या नहीं, |
| [getConLineJumpDirX()](#getConLineJumpDirX--) | डायनामिक कनेक्टर के क्षैतिज खंड पर होने वाले लाइन जंप की दिशा निर्धारित करता है। |
| [getConLineJumpDirY()](#getConLineJumpDirY--) | डायनामिक कनेक्टर के लंबवत खंड पर होने वाले लाइन जंप की दिशा निर्धारित करता है। |
| [getConLineJumpStyle()](#getConLineJumpStyle--) | डायनामिक कनेक्टर पर लाइन जंप की शैली निर्धारित करता है। |
| [getConLineRouteExt()](#getConLineRouteExt--) | कनेक्टर की उपस्थिति निर्धारित करता है। |
| [getDel()](#getDel--) | एक फ़्लैग जो दर्शाता है कि तत्व स्थानीय रूप से हटाया गया है या नहीं। |
| [getDisplayLevel()](#getDisplayLevel--) | आकार के लिए डिस्प्ले लेवल बैंड (Z-ऑर्डर ग्रुपिंग की सापेक्ष रेंज) निर्धारित करता है। |
| [getRelationships()](#getRelationships--) | कंटेनर, सूची, कॉलआउट और आकारों के बीच संबंधों को संग्रहीत करता है। |
| [getShapeFixedCode()](#getShapeFixedCode--) | एक प्लेसेबल आकार के लिए प्लेसमेंट व्यवहार निर्दिष्ट करता है। |
| [getShapePermeablePlace()](#getShapePermeablePlace--) | निर्दिष्ट करता है कि जब उपयोगकर्ता ले आउट शैप्स (Shapes मेनू) चुनता है, तो प्लेसेबल शैप्स को किसी आकार के ऊपर रखा जा सकता है या नहीं। |
| [getShapePermeableX()](#getShapePermeableX--) | निर्दिष्ट करता है कि एक कनेक्टर क्षैतिज रूप से किसी आकार के माध्यम से रूट कर सकता है या नहीं। |
| [getShapePermeableY()](#getShapePermeableY--) | निर्दिष्ट करता है कि एक कनेक्टर लंबवत रूप से किसी आकार के माध्यम से रूट कर सकता है या नहीं। |
| [getShapePlaceFlip()](#getShapePlaceFlip--) | जब उपयोगकर्ता ले आउट शैप्स (Shapes मेनू) चुनता है, तो एक प्लेसेबल आकार पेज पर कैसे उलटता/घुमता है, यह निर्दिष्ट करता है। |
| [getShapePlaceStyle()](#getShapePlaceStyle--) | संतानों के लिए प्लेसमेंट शैली निर्धारित करता है। |
| [getShapePlowCode()](#getShapePlowCode--) | निर्दिष्ट करता है कि क्या एक प्लेसेबल आकार दूर चलता है जब आप ड्राइंग पेज पर किसी अन्य प्लेसेबल आकार को उसके पास खींचते हैं। |
| [getShapeRouteStyle()](#getShapeRouteStyle--) | ड्राइंग पेज पर कनेक्टर के लिए रूटिंग शैली और दिशा निर्दिष्ट करता है। |
| [getShapeSplit()](#getShapeSplit--) | निर्धारित करता है कि यह आकार विभाज्य आकारों को विभाजित कर सकता है या नहीं। |
| [getShapeSplittable()](#getShapeSplittable--) | निर्धारित करता है कि यह 1-डी आकार विभाजित किया जा सकता है या नहीं। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getDel()](../../com.aspose.diagram/layout\#getDel--) |
| [setShapePlaceStyle(ShapePlaceStyle value)](#setShapePlaceStyle-com.aspose.diagram.ShapePlaceStyle-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getShapePlaceStyle()](../../com.aspose.diagram/layout\#getShapePlaceStyle--) |
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
### getConFixedCode() {#getConFixedCode--}
```
public ConFixedCode getConFixedCode()
```


निर्धारित करता है कि कनेक्टर कब पुनः मार्गित होता है।

**Returns:**
[ConFixedCode](../../com.aspose.diagram/confixedcode)
### getConLineJumpCode() {#getConLineJumpCode--}
```
public ConLineJumpCode getConLineJumpCode()
```


निर्धारित करता है कि दो कनेक्टरों के क्रॉस होने पर कनेक्टर कूदता है या नहीं,

**Returns:**
[ConLineJumpCode](../../com.aspose.diagram/conlinejumpcode)
### getConLineJumpDirX() {#getConLineJumpDirX--}
```
public ConLineJumpDirX getConLineJumpDirX()
```


डायनामिक कनेक्टर के क्षैतिज खंड पर होने वाले लाइन जंप की दिशा निर्धारित करता है।

**Returns:**
[ConLineJumpDirX](../../com.aspose.diagram/conlinejumpdirx)
### getConLineJumpDirY() {#getConLineJumpDirY--}
```
public ConLineJumpDirY getConLineJumpDirY()
```


डायनामिक कनेक्टर के लंबवत खंड पर होने वाले लाइन जंप की दिशा निर्धारित करता है।

**Returns:**
[ConLineJumpDirY](../../com.aspose.diagram/conlinejumpdiry)
### getConLineJumpStyle() {#getConLineJumpStyle--}
```
public ConLineJumpStyle getConLineJumpStyle()
```


डायनामिक कनेक्टर पर लाइन जंप की शैली निर्धारित करता है।

**Returns:**
[ConLineJumpStyle](../../com.aspose.diagram/conlinejumpstyle)
### getConLineRouteExt() {#getConLineRouteExt--}
```
public ConLineRouteExt getConLineRouteExt()
```


कनेक्टर की उपस्थिति निर्धारित करता है।

**Returns:**
[ConLineRouteExt](../../com.aspose.diagram/conlinerouteext)
### getDel() {#getDel--}
```
public int getDel()
```


एक फ़्लैग जो दर्शाता है कि तत्व स्थानीय रूप से हटाया गया है या नहीं। मान 1 यह संकेत देता है कि तत्व स्थानीय रूप से हटाया गया था।

**Returns:**
int
### getDisplayLevel() {#getDisplayLevel--}
```
public IntValue getDisplayLevel()
```


आकार के लिए डिस्प्ले लेवल बैंड (Z-ऑर्डर ग्रुपिंग की सापेक्ष रेंज) निर्धारित करता है।

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getRelationships() {#getRelationships--}
```
public BoolValue getRelationships()
```


कंटेनर, सूची, कॉलआउट और आकारों के बीच संबंधों को संग्रहीत करता है।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapeFixedCode() {#getShapeFixedCode--}
```
public ShapeFixedCode getShapeFixedCode()
```


एक प्लेसेबल आकार के लिए प्लेसमेंट व्यवहार निर्दिष्ट करता है।

**Returns:**
[ShapeFixedCode](../../com.aspose.diagram/shapefixedcode)
### getShapePermeablePlace() {#getShapePermeablePlace--}
```
public BoolValue getShapePermeablePlace()
```


निर्दिष्ट करता है कि जब उपयोगकर्ता ले आउट शैप्स (Shapes मेनू) चुनता है, तो प्लेसेबल शैप्स को किसी आकार के ऊपर रखा जा सकता है या नहीं।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapePermeableX() {#getShapePermeableX--}
```
public BoolValue getShapePermeableX()
```


निर्दिष्ट करता है कि एक कनेक्टर क्षैतिज रूप से किसी आकार के माध्यम से रूट कर सकता है या नहीं।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapePermeableY() {#getShapePermeableY--}
```
public BoolValue getShapePermeableY()
```


निर्दिष्ट करता है कि एक कनेक्टर लंबवत रूप से किसी आकार के माध्यम से रूट कर सकता है या नहीं।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapePlaceFlip() {#getShapePlaceFlip--}
```
public ShapePlaceFlip getShapePlaceFlip()
```


जब उपयोगकर्ता ले आउट शैप्स (Shapes मेनू) चुनता है, तो एक प्लेसेबल आकार पेज पर कैसे उलटता/घुमता है, यह निर्दिष्ट करता है।

**Returns:**
[ShapePlaceFlip](../../com.aspose.diagram/shapeplaceflip)
### getShapePlaceStyle() {#getShapePlaceStyle--}
```
public ShapePlaceStyle getShapePlaceStyle()
```


संतानों के लिए प्लेसमेंट शैली निर्धारित करता है।

**Returns:**
[ShapePlaceStyle](../../com.aspose.diagram/shapeplacestyle)
### getShapePlowCode() {#getShapePlowCode--}
```
public ShapePlowCode getShapePlowCode()
```


निर्दिष्ट करता है कि क्या एक प्लेसेबल आकार दूर चलता है जब आप ड्राइंग पेज पर किसी अन्य प्लेसेबल आकार को उसके पास खींचते हैं।

**Returns:**
[ShapePlowCode](../../com.aspose.diagram/shapeplowcode)
### getShapeRouteStyle() {#getShapeRouteStyle--}
```
public ShapeRouteStyle getShapeRouteStyle()
```


ड्राइंग पेज पर कनेक्टर के लिए रूटिंग शैली और दिशा निर्दिष्ट करता है।

**Returns:**
[ShapeRouteStyle](../../com.aspose.diagram/shaperoutestyle)
### getShapeSplit() {#getShapeSplit--}
```
public BoolValue getShapeSplit()
```


निर्धारित करता है कि यह आकार विभाज्य आकारों को विभाजित कर सकता है या नहीं।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getShapeSplittable() {#getShapeSplittable--}
```
public BoolValue getShapeSplittable()
```


निर्धारित करता है कि यह 1-डी आकार विभाजित किया जा सकता है या नहीं।

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


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getDel()](../../com.aspose.diagram/layout\#getDel--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setShapePlaceStyle(ShapePlaceStyle value) {#setShapePlaceStyle-com.aspose.diagram.ShapePlaceStyle-}
```
public void setShapePlaceStyle(ShapePlaceStyle value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getShapePlaceStyle()](../../com.aspose.diagram/layout\#getShapePlaceStyle--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [ShapePlaceStyle](../../com.aspose.diagram/shapeplacestyle) |  |

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

