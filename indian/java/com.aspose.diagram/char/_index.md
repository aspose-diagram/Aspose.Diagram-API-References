---
title: Char
second_title: Aspose.Diagram for Java API Reference
description: आकार के पाठ के स्वरूपण गुणधर्म शामिल करता है जैसे फ़ॉन्ट रंग, पाठ शैली, केस, बेसलाइन के सापेक्ष स्थिति और बिंदु आकार।
type: docs
weight: 45
url: /hi/java/com.aspose.diagram/char/
---

**Inheritance:**
java.lang.Object
```
public class Char
```

आकार के टेक्स्ट के फ़ॉर्मेटिंग एट्रिब्यूट्स को शामिल करता है, जैसे फ़ॉन्ट, रंग, टेक्स्ट शैली, केस, बेसलाइन के सापेक्ष स्थिति, और पॉइंट आकार।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [Char()](#Char--) | कंस्ट्रक्टर। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [deepClone()](#deepClone--) | इस उदाहरण की गहरी प्रतिलिपि बनाता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAsianFont()](#getAsianFont--) | एशियाई अक्षरों वाले पाठ को स्वरूपित करने के लिए उपयोग किए गए फ़ॉन्ट की आईडी संख्या निर्दिष्ट करता है। |
| [getAsianFontName()](#getAsianFontName--) | यह पाठ को स्वरूपित करने के लिए उपयोग किए गए एशियाई फ़ॉन्ट का नाम निर्दिष्ट करता है। यह Visio 2013 के लिए उपयोग किया जाता है। |
| [getCase()](#getCase--) | एक आकार के टेक्स्ट के केस को निर्धारित करता है। |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | जब Char तत्व में सम्मिलित हो, तो Color तत्व। |
| [getColorTrans()](#getColorTrans--) | परत या आकार के पाठ रंग की पारदर्शिता की डिग्री निर्धारित करता है, 0 (पूरी तरह अपारदर्शी) से 1 (पूरी तरह पारदर्शी) तक। |
| [getComplexScriptFont()](#getComplexScriptFont--) | जटिल लिपि अक्षरों वाले पाठ को स्वरूपित करने के लिए उपयोग किए गए फ़ॉन्ट की संख्या शामिल करता है। |
| [getComplexScriptFontName()](#getComplexScriptFontName--) | यह पाठ को स्वरूपित करने के लिए उपयोग किए गए ComplexScript फ़ॉन्ट का नाम निर्दिष्ट करता है। यह Visio 2013 के लिए उपयोग किया जाता है। |
| [getComplexScriptSize()](#getComplexScriptSize--) | जटिल लिपि अक्षरों वाले पाठ को स्वरूपित करने के लिए उपयोग किए गए फ़ॉन्ट का आकार। |
| [getDblUnderline()](#getDblUnderline--) | निर्दिष्ट करता है कि क्या पाठ की सीमा के नीचे दोहरी रेखा है। |
| [getDel()](#getDel--) | एक फ़्लैग जो दर्शाता है कि तत्व स्थानीय रूप से हटाया गया है या नहीं। |
| [getDoubleStrikethrough()](#getDoubleStrikethrough--) | निर्धारित करता है कि क्या पाठ को डबल स्ट्राइकथ्रू के रूप में स्वरूपित किया गया है। |
| [getFont()](#getFont--) | पाठ को स्वरूपित करने के लिए उपयोग किए गए फ़ॉन्ट की आईडी संख्या निर्दिष्ट करता है। |
| [getFontName()](#getFontName--) | यह पाठ को स्वरूपित करने के लिए उपयोग किए गए फ़ॉन्ट का नाम निर्दिष्ट करता है। यह Visio 2013 के लिए उपयोग किया जाता है। |
| [getFontScale()](#getFontScale--) | फ़ॉन्ट की चौड़ाई निर्दिष्ट करता है। |
| [getHighlight()](#getHighlight--) | यह हाइलाइट निर्दिष्ट करता है। |
| [getIX()](#getIX--) | उसके पैरेंट तत्व के भीतर तत्व का शून्य-आधारित सूचकांक। |
| [getLangID()](#getLangID--) | सेल फ़ॉर्मूला, टेक्स्ट, कस्टम प्रॉपर्टी, या टिप्पणी जिस भाषा में दर्ज की गई थी, उसके लोकैल आईडी (LCID) को दर्शाता है। |
| [getLetterspace()](#getLetterspace--) | दो या अधिक अक्षरों के बीच स्थान की मात्रा निर्दिष्ट करता है। |
| [getLocale()](#getLocale--) | यह वर्तनी जाँच के उद्देश्य से टेक्स्ट रन का लोकेल निर्दिष्ट करता है। |
| [getLocalizeFont()](#getLocalizeFont--) | निर्दिष्ट करता है कि आकार का पाठ स्थानीयकृत (दूसरी भाषा में अनूदित) होना चाहिए या नहीं। |
| [getOverline()](#getOverline--) | निर्दिष्ट करता है कि क्या पाठ के ऊपर एक रेखा है। |
| [getPerpendicular()](#getPerpendicular--) | यह निर्दिष्ट करता है कि क्या टेक्स्ट ब्लॉक में एक टेक्स्ट फ़ील्ड अन्य टेक्स्ट के लंबवत दिखाई देता है। |
| [getPos()](#getPos--) | आकार के पाठ की स्थिति को बेसलाइन के सापेक्ष निर्दिष्ट करता है। |
| [getRTLText()](#getRTLText--) | निर्धारित करता है कि वर्तमान अक्षर रन की टेक्स्ट दिशा बाएँ से दाएँ है या दाएँ से बाएँ। |
| [getSize()](#getSize--) | आकार के टेक्स्ट ब्लॉक में पाठ का आकार निर्दिष्ट करता है। |
| [getStrikethru()](#getStrikethru--) | निर्दिष्ट करता है कि क्या पाठ को स्ट्राइकथ्रू के रूप में स्वरूपित किया गया है। |
| [getStyle()](#getStyle--) | शेप के टेक्स्ट ब्लॉक में टेक्स्ट की रेंज पर लागू वर्ण स्वरूपण को निर्दिष्ट करता है। |
| [getUseVertical()](#getUseVertical--) | निर्धारित करता है कि अक्षर रन लंबवत है या क्षैतिज। |
| [hashCode()](#hashCode--) |  |
| [isBold()](#isBold--) | यह दर्शाता है कि फ़ॉन्ट बोल्ड है या नहीं। |
| [isDoubleStrikethrough()](#isDoubleStrikethrough--) | यह दर्शाता है कि फ़ॉन्ट डबल स्ट्राइकथ्रू है या नहीं। |
| [isDoubleUnderline()](#isDoubleUnderline--) | यह दर्शाता है कि फ़ॉन्ट डबल अंडरलाइन है या नहीं। |
| [isItalic()](#isItalic--) | यह दर्शाता है कि फ़ॉन्ट इटैलिक है या नहीं। |
| [isStrikethrough()](#isStrikethrough--) | यह दर्शाता है कि फ़ॉन्ट स्ट्राइकथ्रू है या नहीं। |
| [isSubscript()](#isSubscript--) | यह दर्शाता है कि फ़ॉन्ट सबस्क्रिप्ट है या नहीं। |
| [isSuperscript()](#isSuperscript--) | यह दर्शाता है कि फ़ॉन्ट सुपरस्क्रिप्ट है या नहीं। |
| [isUnderline()](#isUnderline--) | यह दर्शाता है कि फ़ॉन्ट अंडरलाइन है या नहीं। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAsianFont(IntValue value)](#setAsianFont-com.aspose.diagram.IntValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getAsianFont()](../../com.aspose.diagram/char\#getAsianFont--) |
| [setAsianFontName(StrValue value)](#setAsianFontName-com.aspose.diagram.StrValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getAsianFontName()](../../com.aspose.diagram/char\#getAsianFontName--) |
| [setCase(Case value)](#setCase-com.aspose.diagram.Case-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getCase()](../../com.aspose.diagram/char\#getCase--) |
| [setColor(ColorValue value)](#setColor-com.aspose.diagram.ColorValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getColor()](../../com.aspose.diagram/char\#getColor--) |
| [setColorTrans(DoubleValue value)](#setColorTrans-com.aspose.diagram.DoubleValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getColorTrans()](../../com.aspose.diagram/char\#getColorTrans--) |
| [setComplexScriptFont(IntValue value)](#setComplexScriptFont-com.aspose.diagram.IntValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getComplexScriptFont()](../../com.aspose.diagram/char\#getComplexScriptFont--) |
| [setComplexScriptFontName(StrValue value)](#setComplexScriptFontName-com.aspose.diagram.StrValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getComplexScriptFontName()](../../com.aspose.diagram/char\#getComplexScriptFontName--) |
| [setComplexScriptSize(DoubleValue value)](#setComplexScriptSize-com.aspose.diagram.DoubleValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getComplexScriptSize()](../../com.aspose.diagram/char\#getComplexScriptSize--) |
| [setDblUnderline(BoolValue value)](#setDblUnderline-com.aspose.diagram.BoolValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getDblUnderline()](../../com.aspose.diagram/char\#getDblUnderline--) |
| [setDel(int value)](#setDel-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getDel()](../../com.aspose.diagram/char\#getDel--) |
| [setDoubleStrikethrough(BoolValue value)](#setDoubleStrikethrough-com.aspose.diagram.BoolValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getDoubleStrikethrough()](../../com.aspose.diagram/char\#getDoubleStrikethrough--) |
| [setFont(IntValue value)](#setFont-com.aspose.diagram.IntValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getFont()](../../com.aspose.diagram/char\#getFont--) |
| [setFontName(StrValue value)](#setFontName-com.aspose.diagram.StrValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getFontName()](../../com.aspose.diagram/char\#getFontName--) |
| [setFontScale(DoubleValue value)](#setFontScale-com.aspose.diagram.DoubleValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getFontScale()](../../com.aspose.diagram/char\#getFontScale--) |
| [setHighlight(BoolValue value)](#setHighlight-com.aspose.diagram.BoolValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getHighlight()](../../com.aspose.diagram/char\#getHighlight--) |
| [setIX(int value)](#setIX-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getIX()](../../com.aspose.diagram/char\#getIX--) |
| [setLangID(IntValue value)](#setLangID-com.aspose.diagram.IntValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getLangID()](../../com.aspose.diagram/char\#getLangID--) |
| [setLetterspace(DoubleValue value)](#setLetterspace-com.aspose.diagram.DoubleValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getLetterspace()](../../com.aspose.diagram/char\#getLetterspace--) |
| [setLocale(StrValue value)](#setLocale-com.aspose.diagram.StrValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getLocale()](../../com.aspose.diagram/char\#getLocale--) |
| [setLocalizeFont(LocalizeFont value)](#setLocalizeFont-com.aspose.diagram.LocalizeFont-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getLocalizeFont()](../../com.aspose.diagram/char\#getLocalizeFont--) |
| [setOverline(BoolValue value)](#setOverline-com.aspose.diagram.BoolValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getOverline()](../../com.aspose.diagram/char\#getOverline--) |
| [setPerpendicular(StrValue value)](#setPerpendicular-com.aspose.diagram.StrValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getPerpendicular()](../../com.aspose.diagram/char\#getPerpendicular--) |
| [setPos(Pos value)](#setPos-com.aspose.diagram.Pos-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getPos()](../../com.aspose.diagram/char\#getPos--) |
| [setRTLText(BoolValue value)](#setRTLText-com.aspose.diagram.BoolValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getRTLText()](../../com.aspose.diagram/char\#getRTLText--) |
| [setSize(DoubleValue value)](#setSize-com.aspose.diagram.DoubleValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getSize()](../../com.aspose.diagram/char\#getSize--) |
| [setStrikethru(BoolValue value)](#setStrikethru-com.aspose.diagram.BoolValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getStrikethru()](../../com.aspose.diagram/char\#getStrikethru--) |
| [setStyle(Style value)](#setStyle-com.aspose.diagram.Style-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getStyle()](../../com.aspose.diagram/char\#getStyle--) |
| [setUseVertical(BoolValue value)](#setUseVertical-com.aspose.diagram.BoolValue-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getUseVertical()](../../com.aspose.diagram/char\#getUseVertical--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Char() {#Char--}
```
public Char()
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
### getAsianFont() {#getAsianFont--}
```
public IntValue getAsianFont()
```


एशियाई अक्षरों वाले पाठ को स्वरूपित करने के लिए उपयोग किए गए फ़ॉन्ट की आईडी संख्या निर्दिष्ट करता है।

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getAsianFontName() {#getAsianFontName--}
```
public StrValue getAsianFontName()
```


यह पाठ को स्वरूपित करने के लिए उपयोग किए गए एशियाई फ़ॉन्ट का नाम निर्दिष्ट करता है। यह Visio 2013 के लिए उपयोग किया जाता है।

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
### getCase() {#getCase--}
```
public Case getCase()
```


एक आकार के टेक्स्ट के केस को निर्धारित करता है।

**Returns:**
[Case](../../com.aspose.diagram/case)
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


जब Char तत्व में सम्मिलित हो, तो Color तत्व।

**Returns:**
[ColorValue](../../com.aspose.diagram/colorvalue)
### getColorTrans() {#getColorTrans--}
```
public DoubleValue getColorTrans()
```


परत या आकार के पाठ रंग की पारदर्शिता की डिग्री निर्धारित करता है, 0 (पूरी तरह अपारदर्शी) से 1 (पूरी तरह पारदर्शी) तक।

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getComplexScriptFont() {#getComplexScriptFont--}
```
public IntValue getComplexScriptFont()
```


जटिल स्क्रिप्ट अक्षरों से बनी टेक्स्ट को फ़ॉर्मेट करने के लिए उपयोग किए जाने वाले फ़ॉन्ट की संख्या शामिल है। जटिल स्क्रिप्ट वे भाषाएँ हैं जिनके अक्षरों को लिगेशन या शैपिंग की आवश्यकता होती है, जैसे दाएँ‑से‑बाएँ भाषाएँ (अरबी, फ़ारसी, हिब्रू, और उर्दू) और कई दक्षिण एशियाई भाषाएँ।

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getComplexScriptFontName() {#getComplexScriptFontName--}
```
public StrValue getComplexScriptFontName()
```


यह पाठ को स्वरूपित करने के लिए उपयोग किए गए ComplexScript फ़ॉन्ट का नाम निर्दिष्ट करता है। यह Visio 2013 के लिए उपयोग किया जाता है।

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
### getComplexScriptSize() {#getComplexScriptSize--}
```
public DoubleValue getComplexScriptSize()
```


जटिल स्क्रिप्ट वर्णों से बना पाठ को स्वरूपित करने के लिए उपयोग किए जाने वाले फ़ॉन्ट का आकार। जटिल स्क्रिप्ट वे भाषाएँ हैं जिनके वर्णों को लिगेचर या शैपिंग की आवश्यकता होती है, जैसे दाएँ‑से‑बाएँ भाषाएँ (अरबी, फ़ारसी, हिब्रू, और उर्दू) और कई दक्षिण एशियाई भाषाएँ।

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getDblUnderline() {#getDblUnderline--}
```
public BoolValue getDblUnderline()
```


निर्दिष्ट करता है कि क्या पाठ की सीमा के नीचे दोहरी रेखा है।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getDel() {#getDel--}
```
public int getDel()
```


एक फ़्लैग जो दर्शाता है कि तत्व स्थानीय रूप से हटाया गया है या नहीं। मान 1 यह संकेत देता है कि तत्व स्थानीय रूप से हटाया गया था।

**Returns:**
int
### getDoubleStrikethrough() {#getDoubleStrikethrough--}
```
public BoolValue getDoubleStrikethrough()
```


निर्धारित करता है कि क्या पाठ को डबल स्ट्राइकथ्रू के रूप में स्वरूपित किया गया है।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getFont() {#getFont--}
```
public IntValue getFont()
```


पाठ को स्वरूपित करने के लिए उपयोग किए गए फ़ॉन्ट की आईडी संख्या निर्दिष्ट करता है।

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getFontName() {#getFontName--}
```
public StrValue getFontName()
```


यह पाठ को स्वरूपित करने के लिए उपयोग किए गए फ़ॉन्ट का नाम निर्दिष्ट करता है। यह Visio 2013 के लिए उपयोग किया जाता है।

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
### getFontScale() {#getFontScale--}
```
public DoubleValue getFontScale()
```


फ़ॉन्ट की चौड़ाई निर्दिष्ट करता है।

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getHighlight() {#getHighlight--}
```
public BoolValue getHighlight()
```


यह हाइलाइट निर्दिष्ट करता है।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getIX() {#getIX--}
```
public int getIX()
```


उसके पैरेंट तत्व के भीतर तत्व का शून्य-आधारित सूचकांक।

**Returns:**
int
### getLangID() {#getLangID--}
```
public IntValue getLangID()
```


सेल फ़ॉर्मूला, पाठ, कस्टम प्रॉपर्टी, या टिप्पणी जिस भाषा में दर्ज की गई थी, उसके लोकेल ID (LCID) को दर्शाता है। माइक्रोसॉफ्ट ऑफिस अनुप्रयोगों द्वारा समर्थित भाषाओं और उनके संबंधित भाषा IDs की सूची के लिए, DocLangID तत्व देखें।

**Returns:**
[IntValue](../../com.aspose.diagram/intvalue)
### getLetterspace() {#getLetterspace--}
```
public DoubleValue getLetterspace()
```


दो या अधिक वर्णों के बीच की दूरी को निर्दिष्ट करता है। अंतराल को 1/20 पॉइंट वृद्धि में जोड़ा या घटाया जा सकता है।

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getLocale() {#getLocale--}
```
public StrValue getLocale()
```


यह वर्तनी जाँच के उद्देश्य से टेक्स्ट रन का लोकेल निर्दिष्ट करता है।

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
### getLocalizeFont() {#getLocalizeFont--}
```
public LocalizeFont getLocalizeFont()
```


निर्दिष्ट करता है कि आकार का पाठ स्थानीयकृत (दूसरी भाषा में अनूदित) होना चाहिए या नहीं।

**Returns:**
[LocalizeFont](../../com.aspose.diagram/localizefont)
### getOverline() {#getOverline--}
```
public BoolValue getOverline()
```


निर्दिष्ट करता है कि क्या पाठ के ऊपर एक रेखा है।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getPerpendicular() {#getPerpendicular--}
```
public StrValue getPerpendicular()
```


यह निर्दिष्ट करता है कि क्या टेक्स्ट ब्लॉक में एक टेक्स्ट फ़ील्ड अन्य टेक्स्ट के लंबवत दिखाई देता है।

**Returns:**
[StrValue](../../com.aspose.diagram/strvalue)
### getPos() {#getPos--}
```
public Pos getPos()
```


आकार के पाठ की स्थिति को बेसलाइन के सापेक्ष निर्दिष्ट करता है।

**Returns:**
[Pos](../../com.aspose.diagram/pos)
### getRTLText() {#getRTLText--}
```
public BoolValue getRTLText()
```


निर्धारित करता है कि वर्तमान अक्षर रन की टेक्स्ट दिशा बाएँ से दाएँ है या दाएँ से बाएँ।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getSize() {#getSize--}
```
public DoubleValue getSize()
```


आकार के टेक्स्ट ब्लॉक में पाठ का आकार निर्दिष्ट करता है।

**Returns:**
[DoubleValue](../../com.aspose.diagram/doublevalue)
### getStrikethru() {#getStrikethru--}
```
public BoolValue getStrikethru()
```


निर्दिष्ट करता है कि क्या पाठ को स्ट्राइकथ्रू के रूप में स्वरूपित किया गया है।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### getStyle() {#getStyle--}
```
public Style getStyle()
```


शेप के टेक्स्ट ब्लॉक में टेक्स्ट की रेंज पर लागू वर्ण स्वरूपण को निर्दिष्ट करता है।

**Returns:**
[Style](../../com.aspose.diagram/style)
### getUseVertical() {#getUseVertical--}
```
public BoolValue getUseVertical()
```


निर्धारित करता है कि अक्षर रन लंबवत है या क्षैतिज।

**Returns:**
[BoolValue](../../com.aspose.diagram/boolvalue)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isBold() {#isBold--}
```
public boolean isBold()
```


यह दर्शाता है कि फ़ॉन्ट बोल्ड है या नहीं।

**Returns:**
बूलियन
### isDoubleStrikethrough() {#isDoubleStrikethrough--}
```
public boolean isDoubleStrikethrough()
```


यह दर्शाता है कि फ़ॉन्ट डबल स्ट्राइकथ्रू है या नहीं।

**Returns:**
बूलियन
### isDoubleUnderline() {#isDoubleUnderline--}
```
public boolean isDoubleUnderline()
```


यह दर्शाता है कि फ़ॉन्ट डबल अंडरलाइन है या नहीं।

**Returns:**
बूलियन
### isItalic() {#isItalic--}
```
public boolean isItalic()
```


यह दर्शाता है कि फ़ॉन्ट इटैलिक है या नहीं।

**Returns:**
बूलियन
### isStrikethrough() {#isStrikethrough--}
```
public boolean isStrikethrough()
```


यह दर्शाता है कि फ़ॉन्ट स्ट्राइकथ्रू है या नहीं।

**Returns:**
बूलियन
### isSubscript() {#isSubscript--}
```
public boolean isSubscript()
```


यह दर्शाता है कि फ़ॉन्ट सबस्क्रिप्ट है या नहीं।

**Returns:**
बूलियन
### isSuperscript() {#isSuperscript--}
```
public boolean isSuperscript()
```


यह दर्शाता है कि फ़ॉन्ट सुपरस्क्रिप्ट है या नहीं।

**Returns:**
बूलियन
### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


यह दर्शाता है कि फ़ॉन्ट अंडरलाइन है या नहीं।

**Returns:**
बूलियन
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAsianFont(IntValue value) {#setAsianFont-com.aspose.diagram.IntValue-}
```
public void setAsianFont(IntValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getAsianFont()](../../com.aspose.diagram/char\#getAsianFont--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setAsianFontName(StrValue value) {#setAsianFontName-com.aspose.diagram.StrValue-}
```
public void setAsianFontName(StrValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getAsianFontName()](../../com.aspose.diagram/char\#getAsianFontName--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [StrValue](../../com.aspose.diagram/strvalue) |  |

### setCase(Case value) {#setCase-com.aspose.diagram.Case-}
```
public void setCase(Case value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getCase()](../../com.aspose.diagram/char\#getCase--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [Case](../../com.aspose.diagram/case) |  |

### setColor(ColorValue value) {#setColor-com.aspose.diagram.ColorValue-}
```
public void setColor(ColorValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getColor()](../../com.aspose.diagram/char\#getColor--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [ColorValue](../../com.aspose.diagram/colorvalue) |  |

### setColorTrans(DoubleValue value) {#setColorTrans-com.aspose.diagram.DoubleValue-}
```
public void setColorTrans(DoubleValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getColorTrans()](../../com.aspose.diagram/char\#getColorTrans--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setComplexScriptFont(IntValue value) {#setComplexScriptFont-com.aspose.diagram.IntValue-}
```
public void setComplexScriptFont(IntValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getComplexScriptFont()](../../com.aspose.diagram/char\#getComplexScriptFont--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setComplexScriptFontName(StrValue value) {#setComplexScriptFontName-com.aspose.diagram.StrValue-}
```
public void setComplexScriptFontName(StrValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getComplexScriptFontName()](../../com.aspose.diagram/char\#getComplexScriptFontName--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [StrValue](../../com.aspose.diagram/strvalue) |  |

### setComplexScriptSize(DoubleValue value) {#setComplexScriptSize-com.aspose.diagram.DoubleValue-}
```
public void setComplexScriptSize(DoubleValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getComplexScriptSize()](../../com.aspose.diagram/char\#getComplexScriptSize--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setDblUnderline(BoolValue value) {#setDblUnderline-com.aspose.diagram.BoolValue-}
```
public void setDblUnderline(BoolValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getDblUnderline()](../../com.aspose.diagram/char\#getDblUnderline--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setDel(int value) {#setDel-int-}
```
public void setDel(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getDel()](../../com.aspose.diagram/char\#getDel--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setDoubleStrikethrough(BoolValue value) {#setDoubleStrikethrough-com.aspose.diagram.BoolValue-}
```
public void setDoubleStrikethrough(BoolValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getDoubleStrikethrough()](../../com.aspose.diagram/char\#getDoubleStrikethrough--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setFont(IntValue value) {#setFont-com.aspose.diagram.IntValue-}
```
public void setFont(IntValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getFont()](../../com.aspose.diagram/char\#getFont--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setFontName(StrValue value) {#setFontName-com.aspose.diagram.StrValue-}
```
public void setFontName(StrValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getFontName()](../../com.aspose.diagram/char\#getFontName--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [StrValue](../../com.aspose.diagram/strvalue) |  |

### setFontScale(DoubleValue value) {#setFontScale-com.aspose.diagram.DoubleValue-}
```
public void setFontScale(DoubleValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getFontScale()](../../com.aspose.diagram/char\#getFontScale--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setHighlight(BoolValue value) {#setHighlight-com.aspose.diagram.BoolValue-}
```
public void setHighlight(BoolValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getHighlight()](../../com.aspose.diagram/char\#getHighlight--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setIX(int value) {#setIX-int-}
```
public void setIX(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getIX()](../../com.aspose.diagram/char\#getIX--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setLangID(IntValue value) {#setLangID-com.aspose.diagram.IntValue-}
```
public void setLangID(IntValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getLangID()](../../com.aspose.diagram/char\#getLangID--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [IntValue](../../com.aspose.diagram/intvalue) |  |

### setLetterspace(DoubleValue value) {#setLetterspace-com.aspose.diagram.DoubleValue-}
```
public void setLetterspace(DoubleValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getLetterspace()](../../com.aspose.diagram/char\#getLetterspace--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setLocale(StrValue value) {#setLocale-com.aspose.diagram.StrValue-}
```
public void setLocale(StrValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getLocale()](../../com.aspose.diagram/char\#getLocale--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [StrValue](../../com.aspose.diagram/strvalue) |  |

### setLocalizeFont(LocalizeFont value) {#setLocalizeFont-com.aspose.diagram.LocalizeFont-}
```
public void setLocalizeFont(LocalizeFont value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getLocalizeFont()](../../com.aspose.diagram/char\#getLocalizeFont--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [LocalizeFont](../../com.aspose.diagram/localizefont) |  |

### setOverline(BoolValue value) {#setOverline-com.aspose.diagram.BoolValue-}
```
public void setOverline(BoolValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getOverline()](../../com.aspose.diagram/char\#getOverline--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setPerpendicular(StrValue value) {#setPerpendicular-com.aspose.diagram.StrValue-}
```
public void setPerpendicular(StrValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getPerpendicular()](../../com.aspose.diagram/char\#getPerpendicular--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [StrValue](../../com.aspose.diagram/strvalue) |  |

### setPos(Pos value) {#setPos-com.aspose.diagram.Pos-}
```
public void setPos(Pos value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getPos()](../../com.aspose.diagram/char\#getPos--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [Pos](../../com.aspose.diagram/pos) |  |

### setRTLText(BoolValue value) {#setRTLText-com.aspose.diagram.BoolValue-}
```
public void setRTLText(BoolValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getRTLText()](../../com.aspose.diagram/char\#getRTLText--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setSize(DoubleValue value) {#setSize-com.aspose.diagram.DoubleValue-}
```
public void setSize(DoubleValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getSize()](../../com.aspose.diagram/char\#getSize--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [DoubleValue](../../com.aspose.diagram/doublevalue) |  |

### setStrikethru(BoolValue value) {#setStrikethru-com.aspose.diagram.BoolValue-}
```
public void setStrikethru(BoolValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getStrikethru()](../../com.aspose.diagram/char\#getStrikethru--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [BoolValue](../../com.aspose.diagram/boolvalue) |  |

### setStyle(Style value) {#setStyle-com.aspose.diagram.Style-}
```
public void setStyle(Style value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getStyle()](../../com.aspose.diagram/char\#getStyle--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [Style](../../com.aspose.diagram/style) |  |

### setUseVertical(BoolValue value) {#setUseVertical-com.aspose.diagram.BoolValue-}
```
public void setUseVertical(BoolValue value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getUseVertical()](../../com.aspose.diagram/char\#getUseVertical--)

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

