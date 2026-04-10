---
title: PageLayout
second_title: Aspose.Diagram for Java API Reference
description: पृष्ठ लेआउट सेटिंग्स को नियंत्रित करने वाले सेल्स शामिल हैं, जो आकारों और कनेक्टरों के लिए होते हैं, जैसे पृष्ठ पर सभी आकारों के बीच की दूरी, पृष्ठ पर सभी कनेक्टरों के बीच की दूरी, और पृष्ठ पर सभी कनेक्टरों के लिए रूटिंग शैली।
type: docs
weight: 263
url: /hi/java/com.aspose.diagram/pagelayout/
---

**Inheritance:**
java.lang.Object
```
public class PageLayout
```

पृष्ठ पर आकारों और कनेक्टरों के लेआउट सेटिंग्स को नियंत्रित करने वाले कोशिकाओं को शामिल करता है, जैसे पृष्ठ पर सभी आकारों के बीच की दूरी, पृष्ठ पर सभी कनेक्टरों के बीच की दूरी, और पृष्ठ पर सभी कनेक्टरों की रूटिंग शैली।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAvenueSizeX()](#getAvenueSizeX--) | जब आप Microsoft Visio का उपयोग करके ड्राइंग पेज पर आकारों को व्यवस्थित करते हैं, तो आकारों के बीच की लंबवत जगह की मात्रा निर्धारित करता है। |
| [getAvenueSizeY()](#getAvenueSizeY--) | जब आप Microsoft Visio का उपयोग करके ड्राइंग पेज पर आकारों को व्यवस्थित करते हैं, तो आकारों के बीच की लंबवत जगह की मात्रा निर्धारित करता है। |
| [getAvoidPageBreaks()](#getAvoidPageBreaks--) | जब उपयोगकर्ता Lay Out Shapes (Shape मेनू) चुनता है, तो पृष्ठ पर आकारों को कैसे रखा जाता है, यह निर्दिष्ट करता है। |
| [getBlockSizeX()](#getBlockSizeX--) | जब आप Microsoft Visio का उपयोग करके ड्राइंग पेज पर आकारों को व्यवस्थित करते हैं, तो प्रत्येक आकार को फिट होना चाहिए, इस क्षेत्र के लिए लंबवत ब्लॉक आकार निर्धारित करता है। |
| [getBlockSizeY()](#getBlockSizeY--) | जब आप Microsoft Visio का उपयोग करके ड्राइंग पेज पर आकारों को व्यवस्थित करते हैं, तो आकारों के बीच की क्षैतिज जगह की मात्रा निर्धारित करता है। |
| [getClass()](#getClass--) |  |
| [getCtrlAsInput()](#getCtrlAsInput--) | कंट्रोल हैंडल का उपयोग करके आकारों को उपयोग करने पर यह निर्धारित करता है कि कौन सा आकार पैरेंट है। |
| [getDel()](#getDel--) | एक फ़्लैग जो दर्शाता है कि तत्व स्थानीय रूप से हटाया गया है या नहीं। |
| [getDynamicsOff()](#getDynamicsOff--) | निर्दिष्ट करता है कि क्या प्लेसेबल आकार हिलते हैं और कनेक्टर अन्य आकारों और कनेक्टरों के चारों ओर पुनः मार्गित होते हैं। |
| [getEnableGrid()](#getEnableGrid--) | निर्दिष्ट करता है कि उपयोगकर्ता Lay Out Shapes (Shape मेनू) चुनने पर Microsoft Visio आंतरिक पेज ग्रिड के आधार पर आकारों को व्यवस्थित करता है या नहीं। |
| [getLineAdjustFrom()](#getLineAdjustFrom--) | यदि वे एक-दूसरे के ऊपर रूट होते हैं तो किन डायनेमिक कनेक्टर्स को अलग‑अलग स्थान देना है, यह निर्दिष्ट करता है। |
| [getLineAdjustTo()](#getLineAdjustTo--) | यदि वे एक-दूसरे के ऊपर रूट होते हैं तो किन डायनेमिक कनेक्टर्स को एक‑दूसरे के ऊपर संरेखित करना है, यह निर्दिष्ट करता है। |
| [getLineJumpCode()](#getLineJumpCode--) | ड्राइंग पेज पर उन सभी कनेक्टर्स के लिए लाइन जंप शैली निर्दिष्ट करता है जिनके पास स्थानीय लाइन जंप शैली नहीं है। |
| [getLineJumpFactorX()](#getLineJumpFactorX--) | पेज पर डायनेमिक कनेक्टरों के क्षैतिज खंडों में लाइन जंप का आकार, LineToLineX तत्व के मान के प्रतिशत के रूप में निर्दिष्ट करता है (जो ड्राइंग पेज पर सभी कनेक्टरों के बीच क्षैतिज क्लियरेंस को निर्दिष्ट करता है)। |
| [getLineJumpFactorY()](#getLineJumpFactorY--) | पेज पर डायनेमिक कनेक्टरों के लंबवत खंडों में लाइन जंप का आकार, LineToLineY तत्व के मान के प्रतिशत के रूप में निर्दिष्ट करता है (जो ड्राइंग पेज पर सभी कनेक्टरों के बीच लंबवत क्लियरेंस को निर्दिष्ट करता है)। |
| [getLineJumpStyle()](#getLineJumpStyle--) | ड्राइंग पृष्ठ पर डायनेमिक कनेक्टरों के क्षैतिज खंडों में लाइन जंप की दिशा निर्दिष्ट करता है, जहाँ आपने स्थानीय जंप दिशा लागू नहीं की है। |
| [getLineRouteExt()](#getLineRouteExt--) | पृष्ठ पर सभी कनेक्टर्स के लिए डिफ़ॉल्ट रूप निर्दिष्ट करता है। |
| [getLineToLineX()](#getLineToLineX--) | ड्राइंग पेज पर डायनेमिक कनेक्टरों के बीच न्यूनतम क्षैतिज क्लियरेंस निर्दिष्ट करता है। |
| [getLineToLineY()](#getLineToLineY--) | ड्राइंग पेज पर डायनेमिक कनेक्टरों के बीच न्यूनतम लंबवत क्लियरेंस निर्दिष्ट करता है। |
| [getLineToNodeX()](#getLineToNodeX--) | ड्राइंग पेज पर डायनेमिक कनेक्टरों और आकारों के बीच न्यूनतम लंबवत क्लियरेंस निर्दिष्ट करता है। |
| [getLineToNodeY()](#getLineToNodeY--) | जब आप Microsoft Visio का उपयोग करके ड्राइंग पेज पर आकारों को व्यवस्थित करते हैं, तो प्रत्येक आकार को फिट होना चाहिए, इस क्षेत्र के लिए क्षैतिज ब्लॉक आकार निर्धारित करता है। |
| [getPageLineJumpDirX()](#getPageLineJumpDirX--) | ड्राइंग पृष्ठ पर वर्टिकल डायनेमिक कनेक्टरों में लाइन जंप की दिशा निर्दिष्ट करता है, जहाँ आपने स्थानीय जंप दिशा लागू नहीं की है। |
| [getPageLineJumpDirY()](#getPageLineJumpDirY--) | ड्राइंग पेज पर डायनेमिक कनेक्टरों और आकारों के बीच न्यूनतम क्षैतिज क्लियरेंस निर्दिष्ट करता है। |
| [getPageShapeSplit()](#getPageShapeSplit--) | संकेत करता है कि पेज पर आकारों को स्वचालित रूप से विभाजित किया जा सकता है या नहीं। |
| [getPlaceDepth()](#getPlaceDepth--) | निर्दिष्ट करता है कि उपयोगकर्ता जब ड्राइंग पेज पर एक प्लेसेबल आकार को दूसरे प्लेसेबल आकार के पास खींचता है, तो प्लेसेबल आकार दूर हटते हैं या नहीं। |
| [getPlaceFlip()](#getPlaceFlip--) | Microsoft Visio में Lay Out Shapes कमांड का उपयोग करके आकारों को लेआउट करने पर पृष्ठ पर प्लेसेबल आकारों के फ़्लिप और/या रोटेट होने का तरीका निर्दिष्ट करता है। |
| [getPlaceStyle()](#getPlaceStyle--) | ड्राइंग पेज पर सभी गतिशील कनेक्टरों के लिए रूटिंग शैली और दिशा को निर्दिष्ट करता है जिनकी स्थानीय रूटिंग शैली नहीं है। |
| [getPlowCode()](#getPlowCode--) | उन डायनेमिक कनेक्टर्स को निर्धारित करता है जिनमें आप जंप जोड़ना चाहते हैं। |
| [getResizePage()](#getResizePage--) | निर्दिष्ट करता है कि उपयोगकर्ता Lay Out Shapes (Shapes मेनू) चुनने के बाद ड्राइंग को समेटने के लिए पेज को बड़ा किया जाए या नहीं। |
| [getRouteStyle()](#getRouteStyle--) | स्वचालित रूप से लेआउट किए गए ड्राइंग के लिए, लेआउट बनाने से पहले ड्राइंग का विश्लेषण करने की विधि को निर्दिष्ट करता है और लेआउट प्रकार निर्धारित करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDel(int value)](#setDel-int-) | For the description of this property, please see [getDel()](../../com.aspose.diagram/pagelayout\#getDel--) |
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
### getAvenueSizeX() {#getAvenueSizeX--}
```
public DoubleValue getAvenueSizeX()
```


जब आप Microsoft Visio का उपयोग करके ड्राइंग पेज पर आकारों को व्यवस्थित करते हैं, तो आकारों के बीच की लंबवत जगह की मात्रा निर्धारित करता है।

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getAvenueSizeY() {#getAvenueSizeY--}
```
public DoubleValue getAvenueSizeY()
```


जब आप Microsoft Visio का उपयोग करके ड्राइंग पेज पर आकारों को व्यवस्थित करते हैं, तो आकारों के बीच की लंबवत जगह की मात्रा निर्धारित करता है।

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getAvoidPageBreaks() {#getAvoidPageBreaks--}
```
public BoolValue getAvoidPageBreaks()
```


जब उपयोगकर्ता Lay Out Shapes (Shape मेनू) चुनता है, तो पृष्ठ पर आकारों को कैसे रखा जाता है, यह निर्दिष्ट करता है।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getBlockSizeX() {#getBlockSizeX--}
```
public DoubleValue getBlockSizeX()
```


जब आप Microsoft Visio का उपयोग करके ड्राइंग पेज पर आकारों को व्यवस्थित करते हैं, तो प्रत्येक आकार को फिट होना चाहिए, इस क्षेत्र के लिए लंबवत ब्लॉक आकार निर्धारित करता है।

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getBlockSizeY() {#getBlockSizeY--}
```
public DoubleValue getBlockSizeY()
```


जब आप Microsoft Visio का उपयोग करके ड्राइंग पेज पर आकारों को व्यवस्थित करते हैं, तो आकारों के बीच की क्षैतिज जगह की मात्रा निर्धारित करता है।

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCtrlAsInput() {#getCtrlAsInput--}
```
public BoolValue getCtrlAsInput()
```


कंट्रोल हैंडल का उपयोग करके आकारों को उपयोग करने पर यह निर्धारित करता है कि कौन सा आकार पैरेंट है। यह तत्व ड्राइंग पेज पर सभी आकारों के व्यवहार को सेट करता है।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getDel() {#getDel--}
```
public int getDel()
```


एक फ़्लैग जो दर्शाता है कि तत्व स्थानीय रूप से हटाया गया है या नहीं। मान 1 यह संकेत देता है कि तत्व स्थानीय रूप से हटाया गया था।

**Returns:**
int
### getDynamicsOff() {#getDynamicsOff--}
```
public BoolValue getDynamicsOff()
```


निर्दिष्ट करता है कि क्या प्लेसेबल आकार हिलते हैं और कनेक्टर अन्य आकारों और कनेक्टरों के चारों ओर पुनः मार्गित होते हैं।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getEnableGrid() {#getEnableGrid--}
```
public BoolValue getEnableGrid()
```


निर्दिष्ट करता है कि उपयोगकर्ता Lay Out Shapes (Shape मेनू) चुनने पर Microsoft Visio आंतरिक पेज ग्रिड के आधार पर आकारों को व्यवस्थित करता है या नहीं।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getLineAdjustFrom() {#getLineAdjustFrom--}
```
public LineAdjustFrom getLineAdjustFrom()
```


यदि वे एक-दूसरे के ऊपर रूट होते हैं तो किन डायनेमिक कनेक्टर्स को अलग‑अलग स्थान देना है, यह निर्दिष्ट करता है।

**Returns:**
[LineAdjustFrom](../../com.aspose.diagram/lineadjustfrom)
### getLineAdjustTo() {#getLineAdjustTo--}
```
public LineAdjustTo getLineAdjustTo()
```


यदि वे एक-दूसरे के ऊपर रूट होते हैं तो किन डायनेमिक कनेक्टर्स को एक‑दूसरे के ऊपर संरेखित करना है, यह निर्दिष्ट करता है।

**Returns:**
[LineAdjustTo](../../com.aspose.diagram/lineadjustto)
### getLineJumpCode() {#getLineJumpCode--}
```
public LineJumpCode getLineJumpCode()
```


ड्राइंग पेज पर उन सभी कनेक्टर्स के लिए लाइन जंप शैली निर्दिष्ट करता है जिनके पास स्थानीय लाइन जंप शैली नहीं है।

**Returns:**
[LineJumpCode](../../com.aspose.diagram/linejumpcode)
### getLineJumpFactorX() {#getLineJumpFactorX--}
```
public DoubleValue getLineJumpFactorX()
```


पेज पर डायनेमिक कनेक्टरों के क्षैतिज खंडों में लाइन जंप का आकार, LineToLineX तत्व के मान के प्रतिशत के रूप में निर्दिष्ट करता है (जो ड्राइंग पेज पर सभी कनेक्टरों के बीच क्षैतिज क्लियरेंस को निर्दिष्ट करता है)। इस तत्व का मान 0 से 10 के बीच होता है।

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineJumpFactorY() {#getLineJumpFactorY--}
```
public DoubleValue getLineJumpFactorY()
```


पेज पर डायनेमिक कनेक्टरों के लंबवत खंडों में लाइन जंप का आकार, LineToLineY तत्व के मान के प्रतिशत के रूप में निर्दिष्ट करता है (जो ड्राइंग पेज पर सभी कनेक्टरों के बीच लंबवत क्लियरेंस को निर्दिष्ट करता है)। इस तत्व में 0 से 10 तक का मान हो सकता है।

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineJumpStyle() {#getLineJumpStyle--}
```
public LineJumpStyle getLineJumpStyle()
```


ड्राइंग पृष्ठ पर डायनेमिक कनेक्टरों के क्षैतिज खंडों में लाइन जंप की दिशा निर्दिष्ट करता है, जहाँ आपने स्थानीय जंप दिशा लागू नहीं की है।

**Returns:**
[LineJumpStyle](../../com.aspose.diagram/linejumpstyle)
### getLineRouteExt() {#getLineRouteExt--}
```
public LineRouteExt getLineRouteExt()
```


पृष्ठ पर सभी कनेक्टर्स के लिए डिफ़ॉल्ट रूप निर्दिष्ट करता है।

**Returns:**
[LineRouteExt](../../com.aspose.diagram/linerouteext)
### getLineToLineX() {#getLineToLineX--}
```
public DoubleValue getLineToLineX()
```


ड्राइंग पेज पर डायनेमिक कनेक्टरों के बीच न्यूनतम क्षैतिज क्लियरेंस निर्दिष्ट करता है।

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineToLineY() {#getLineToLineY--}
```
public DoubleValue getLineToLineY()
```


ड्राइंग पेज पर डायनेमिक कनेक्टरों के बीच न्यूनतम लंबवत क्लियरेंस निर्दिष्ट करता है।

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineToNodeX() {#getLineToNodeX--}
```
public DoubleValue getLineToNodeX()
```


ड्राइंग पेज पर डायनेमिक कनेक्टरों और आकारों के बीच न्यूनतम लंबवत क्लियरेंस निर्दिष्ट करता है।

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLineToNodeY() {#getLineToNodeY--}
```
public DoubleValue getLineToNodeY()
```


जब आप Microsoft Visio का उपयोग करके ड्राइंग पेज पर आकारों को व्यवस्थित करते हैं, तो प्रत्येक आकार को फिट होना चाहिए, इस क्षेत्र के लिए क्षैतिज ब्लॉक आकार निर्धारित करता है।

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getPageLineJumpDirX() {#getPageLineJumpDirX--}
```
public PageLineJumpDirX getPageLineJumpDirX()
```


ड्राइंग पृष्ठ पर वर्टिकल डायनेमिक कनेक्टरों में लाइन जंप की दिशा निर्दिष्ट करता है, जहाँ आपने स्थानीय जंप दिशा लागू नहीं की है।

**Returns:**
[PageLineJumpDirX](../../com.aspose.diagram/pagelinejumpdirx)
### getPageLineJumpDirY() {#getPageLineJumpDirY--}
```
public PageLineJumpDirY getPageLineJumpDirY()
```


ड्राइंग पेज पर डायनेमिक कनेक्टरों और आकारों के बीच न्यूनतम क्षैतिज क्लियरेंस निर्दिष्ट करता है।

**Returns:**
[PageLineJumpDirY](../../com.aspose.diagram/pagelinejumpdiry)
### getPageShapeSplit() {#getPageShapeSplit--}
```
public BoolValue getPageShapeSplit()
```


संकेत करता है कि पेज पर आकारों को स्वचालित रूप से विभाजित किया जा सकता है या नहीं।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getPlaceDepth() {#getPlaceDepth--}
```
public PlaceDepth getPlaceDepth()
```


निर्दिष्ट करता है कि उपयोगकर्ता जब ड्राइंग पेज पर एक प्लेसेबल आकार को दूसरे प्लेसेबल आकार के पास खींचता है, तो प्लेसेबल आकार दूर हटते हैं या नहीं।

**Returns:**
[PlaceDepth](../../com.aspose.diagram/placedepth)
### getPlaceFlip() {#getPlaceFlip--}
```
public PlaceFlip getPlaceFlip()
```


जब आकृतियों को Microsoft Visio में Lay Out Shapes कमांड का उपयोग करके पृष्ठ पर व्यवस्थित किया जाता है, तब प्लेसेबल आकृतियों के पृष्ठ पर फ़्लिप और/या घुमाव कैसे होते हैं, यह निर्दिष्ट करता है। निम्नलिखित हेक्साडेसिमल मान अनुमत हैं।

**Returns:**
[PlaceFlip](../../com.aspose.diagram/placeflip)
### getPlaceStyle() {#getPlaceStyle--}
```
public PlaceStyle getPlaceStyle()
```


ड्राइंग पेज पर सभी गतिशील कनेक्टरों के लिए रूटिंग शैली और दिशा को निर्दिष्ट करता है जिनकी स्थानीय रूटिंग शैली नहीं है।

**Returns:**
[PlaceStyle](../../com.aspose.diagram/placestyle)
### getPlowCode() {#getPlowCode--}
```
public BoolValue getPlowCode()
```


उन डायनेमिक कनेक्टर्स को निर्धारित करता है जिनमें आप जंप जोड़ना चाहते हैं।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getResizePage() {#getResizePage--}
```
public BoolValue getResizePage()
```


निर्दिष्ट करता है कि उपयोगकर्ता Lay Out Shapes (Shapes मेनू) चुनने के बाद ड्राइंग को समेटने के लिए पेज को बड़ा किया जाए या नहीं।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getRouteStyle() {#getRouteStyle--}
```
public RouteStyle getRouteStyle()
```


स्वचालित रूप से लेआउट किए गए ड्राइंग के लिए, लेआउट बनाने से पहले ड्राइंग का विश्लेषण करने की विधि को निर्दिष्ट करता है और लेआउट प्रकार निर्धारित करता है।

**Returns:**
[RouteStyle](../../com.aspose.diagram/routestyle)
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


For the description of this property, please see [getDel()](../../com.aspose.diagram/pagelayout\#getDel--)

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

