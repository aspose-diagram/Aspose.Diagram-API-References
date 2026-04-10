---
title: StyleSheet
second_title: Aspose.Diagram for Java API Reference
description: दस्तावेज़ में परिभाषित शैली का प्रतिनिधित्व करता है।
type: docs
weight: 393
url: /hi/java/com.aspose.diagram/stylesheet/
---

**Inheritance:**
java.lang.Object
```
public class StyleSheet
```

दस्तावेज़ में परिभाषित शैली का प्रतिनिधित्व करता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [StyleSheet()](#StyleSheet--) | कंस्ट्रक्टर। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [deepClone()](#deepClone--) | इस उदाहरण की गहरी प्रतिलिपि बनाता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChars()](#getChars--) | Char तत्वों का संग्रह शामिल करता है। |
| [getClass()](#getClass--) |  |
| [getConnectionABCDs()](#getConnectionABCDs--) | ConnectionABCD तत्वों का संग्रह शामिल करता है। |
| [getConnections()](#getConnections--) | Connection तत्वों का संग्रह शामिल करता है। |
| [getEvent()](#getEvent--) | आकार घटनाओं को नियंत्रित करने वाले सूत्रों को निर्दिष्ट करने वाले तत्व शामिल हैं। |
| [getFill()](#getFill--) | आकार और उसके ड्रॉप शैडो के लिए वर्तमान भराव फ़ॉर्मेटिंग मानों को शामिल करता है, जिसमें पैटर्न, अग्रभूमि रंग, और पृष्ठभूमि रंग शामिल हैं। |
| [getFillStyle()](#getFillStyle--) | StyleSheet तत्व जिससे यह शैली fill फ़ॉर्मेटिंग विरासत में लेती है। |
| [getForeign()](#getForeign--) | Microsoft Visio दस्तावेज़ में उपयोग किए गए किसी अन्य प्रोग्राम के ऑब्जेक्ट की चौड़ाई और ऊँचाई निर्दिष्ट करने वाले तत्वों को शामिल करता है। |
| [getForeignData()](#getForeignData--) | चित्र डेटा का MIME (Multipurpose Internet Mail Extensions) एन्कोडेड BLOB शामिल करता है, जैसे Windows मेटाफाइल, बिटमैप, या OLE डेटा। |
| [getGroup()](#getGroup--) | ऐसे तत्व शामिल हैं जो नियंत्रित करते हैं कि आप समूह में आकार कैसे जोड़ते हैं, समूह के सदस्यों को कैसे स्थानांतरित करते हैं, और समूहों का चयन कैसे करते हैं। |
| [getHelp()](#getHelp--) | Shape तत्व के हेल्प फ़ाइल टॉपिक और कॉपीराइट जानकारी को निर्दिष्ट करने वाले तत्व शामिल करता है। |
| [getID()](#getID--) | तत्व के अपने पैरेंट तत्व के भीतर अद्वितीय ID। |
| [getImage()](#getImage--) | बिटमैप के लिए गामा, चमक, कंट्रास्ट, ब्लर, शार्पन, डीनॉइज़ और ट्रांसपेरेंसी मानों को शामिल करता है। |
| [getLayout()](#getLayout--) | आकार की प्लेसमेंट और कनेक्टर रूटिंग सेटिंग्स को नियंत्रित करने वाले तत्व शामिल हैं। |
| [getLine()](#getLine--) | एक आकार के लिए रेखा गुणों को नियंत्रित करने वाले तत्वों को शामिल करता है, जैसे पैटर्न, वजन और रंग। |
| [getLineStyle()](#getLineStyle--) | StyleSheet तत्व जिससे यह शैली line फ़ॉर्मेटिंग विरासत में लेती है। |
| [getMisc()](#getMisc--) | Shape तत्व के हेल्प फ़ाइल टॉपिक और कॉपीराइट जानकारी को निर्दिष्ट करने वाले तत्व शामिल करता है। |
| [getName()](#getName--) | तत्व का नाम। |
| [getNameU()](#getNameU--) | तत्व का सार्वभौमिक नाम। |
| [getPageLayout()](#getPageLayout--) | Diagram शामिल करता है जो आकारों और कनेक्टरों के पेज लेआउट सेटिंग्स को नियंत्रित करता है, जैसे पेज पर सभी आकारों के बीच की दूरी, पेज पर सभी कनेक्टरों के बीच की दूरी, और पेज पर सभी कनेक्टरों के लिए रूटिंग शैली। |
| [getParas()](#getParas--) | Para तत्वों का संग्रह शामिल करता है। |
| [getProtection()](#getProtection--) | लॉकिंग आकृति में अनजाने परिवर्तन को रोकने में मदद करती है, लेकिन अन्य परिस्थितियों में Microsoft Visio को मान रीसेट करने से नहीं रोकती। |
| [getRulerGrid()](#getRulerGrid--) | पृष्ठ के रूलर और ग्रिड की सेटिंग्स को निर्दिष्ट करने वाले तत्वों को शामिल करता है। |
| [getStyleProp()](#getStyleProp--) | ऐसे तत्व शामिल हैं जो शैली व्यवहार को नियंत्रित करते हैं, जैसे कि शैली में टेक्स्ट, लाइन और फ़िल एट्रिब्यूट शामिल हैं या नहीं। |
| [getTabsCollection()](#getTabsCollection--) | Tab तत्वों का संग्रह शामिल करता है। |
| [getTextBlock()](#getTextBlock--) | शेप के टेक्स्ट ब्लॉक में टेक्स्ट की संरेखण, मार्जिन और डिफ़ॉल्ट टैब स्टॉप स्थितियों को निर्दिष्ट करने वाले तत्व शामिल करता है। |
| [getTextStyle()](#getTextStyle--) | StyleSheet तत्व जिससे यह शैली text फ़ॉर्मेटिंग विरासत में लेती है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFillStyle(StyleSheet value)](#setFillStyle-com.aspose.diagram.StyleSheet-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getFillStyle()](../../com.aspose.diagram/stylesheet\#getFillStyle--) |
| [setID(int value)](#setID-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getID()](../../com.aspose.diagram/stylesheet\#getID--) |
| [setLineStyle(StyleSheet value)](#setLineStyle-com.aspose.diagram.StyleSheet-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getLineStyle()](../../com.aspose.diagram/stylesheet\#getLineStyle--) |
| [setName(String value)](#setName-java.lang.String-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getName()](../../com.aspose.diagram/stylesheet\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getNameU()](../../com.aspose.diagram/stylesheet\#getNameU--) |
| [setTextStyle(StyleSheet value)](#setTextStyle-com.aspose.diagram.StyleSheet-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getTextStyle()](../../com.aspose.diagram/stylesheet\#getTextStyle--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StyleSheet() {#StyleSheet--}
```
public StyleSheet()
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
### getChars() {#getChars--}
```
public CharCollection getChars()
```


Char तत्वों का संग्रह शामिल करता है।

**Returns:**
[CharCollection](../../com.aspose.diagram/charcollection)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConnectionABCDs() {#getConnectionABCDs--}
```
public ConnectionABCDCollection getConnectionABCDs()
```


ConnectionABCD तत्वों का संग्रह शामिल करता है।

**Returns:**
[ConnectionABCDCollection](../../com.aspose.diagram/connectionabcdcollection)
### getConnections() {#getConnections--}
```
public ConnectionCollection getConnections()
```


Connection तत्वों का संग्रह शामिल करता है।

**Returns:**
[ConnectionCollection](../../com.aspose.diagram/connectioncollection)
### getEvent() {#getEvent--}
```
public Event getEvent()
```


आकार घटनाओं को नियंत्रित करने वाले सूत्रों को निर्दिष्ट करने वाले तत्व शामिल हैं।

**Returns:**
[Event](../../com.aspose.diagram/event)
### getFill() {#getFill--}
```
public Fill getFill()
```


आकार और उसके ड्रॉप शैडो के लिए वर्तमान भराव फ़ॉर्मेटिंग मानों को शामिल करता है, जिसमें पैटर्न, अग्रभूमि रंग, और पृष्ठभूमि रंग शामिल हैं।

**Returns:**
[Fill](../../com.aspose.diagram/fill)
### getFillStyle() {#getFillStyle--}
```
public StyleSheet getFillStyle()
```


StyleSheet तत्व जिससे यह शैली fill फ़ॉर्मेटिंग विरासत में लेती है।

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getForeign() {#getForeign--}
```
public Foreign getForeign()
```


Microsoft Visio दस्तावेज़ में उपयोग किए गए किसी अन्य प्रोग्राम के ऑब्जेक्ट की चौड़ाई और ऊँचाई निर्दिष्ट करने वाले तत्व शामिल करता है। साथ ही ऐसे तत्व भी शामिल करता है जो ऑब्जेक्ट की छवि के उसके सीमाओं के भीतर ऑफ़सेट दूरी को निर्दिष्ट करते हैं।

**Returns:**
[Foreign](../../com.aspose.diagram/foreign)
### getForeignData() {#getForeignData--}
```
public ForeignData getForeignData()
```


चित्र डेटा का MIME (Multipurpose Internet Mail Extensions) एन्कोडेड BLOB शामिल करता है, जैसे Windows मेटाफाइल, बिटमैप, या OLE डेटा।

**Returns:**
[ForeignData](../../com.aspose.diagram/foreigndata)
### getGroup() {#getGroup--}
```
public Group getGroup()
```


ऐसे तत्व शामिल हैं जो नियंत्रित करते हैं कि आप समूह में आकार कैसे जोड़ते हैं, समूह के सदस्यों को कैसे स्थानांतरित करते हैं, और समूहों का चयन कैसे करते हैं।

**Returns:**
[Group](../../com.aspose.diagram/group)
### getHelp() {#getHelp--}
```
public Help getHelp()
```


Shape तत्व के हेल्प फ़ाइल टॉपिक और कॉपीराइट जानकारी को निर्दिष्ट करने वाले तत्व शामिल करता है।

**Returns:**
[Help](../../com.aspose.diagram/help)
### getID() {#getID--}
```
public int getID()
```


तत्व के अपने पैरेंट तत्व के भीतर अद्वितीय ID।

**Returns:**
int
### getImage() {#getImage--}
```
public Image getImage()
```


बिटमैप के लिए गामा, चमक, कंट्रास्ट, ब्लर, शार्पन, डीनॉइज़ और ट्रांसपेरेंसी मानों को शामिल करता है।

**Returns:**
[Image](../../com.aspose.diagram/image)
### getLayout() {#getLayout--}
```
public Layout getLayout()
```


आकार की प्लेसमेंट और कनेक्टर रूटिंग सेटिंग्स को नियंत्रित करने वाले तत्व शामिल हैं।

**Returns:**
[Layout](../../com.aspose.diagram/layout)
### getLine() {#getLine--}
```
public Line getLine()
```


एक आकार के लिए रेखा गुणों को नियंत्रित करने वाले तत्व शामिल करता है, जैसे पैटर्न, वजन, और रंग। ये तत्व निर्धारित करते हैं कि क्या रेखा के अंत स्वरूपित हैं (उदाहरण के लिए, तीर के सिर के साथ), रेखा अंत स्वरूपों का आकार, रेखा पर लागू गोलाई वृत्त का त्रिज्या, और रेखा कैप शैली (गोल या वर्ग)।

**Returns:**
[Line](../../com.aspose.diagram/line)
### getLineStyle() {#getLineStyle--}
```
public StyleSheet getLineStyle()
```


StyleSheet तत्व जिससे यह शैली line फ़ॉर्मेटिंग विरासत में लेती है।

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getMisc() {#getMisc--}
```
public Misc getMisc()
```


Shape तत्व के हेल्प फ़ाइल टॉपिक और कॉपीराइट जानकारी को निर्दिष्ट करने वाले तत्व शामिल करता है।

**Returns:**
[Misc](../../com.aspose.diagram/misc)
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
### getPageLayout() {#getPageLayout--}
```
public PageLayout getPageLayout()
```


Diagram शामिल करता है जो आकारों और कनेक्टरों के पेज लेआउट सेटिंग्स को नियंत्रित करता है, जैसे पेज पर सभी आकारों के बीच की दूरी, पेज पर सभी कनेक्टरों के बीच की दूरी, और पेज पर सभी कनेक्टरों के लिए रूटिंग शैली।

**Returns:**
[PageLayout](../../com.aspose.diagram/pagelayout)
### getParas() {#getParas--}
```
public ParaCollection getParas()
```


Para तत्वों का संग्रह शामिल करता है।

**Returns:**
[ParaCollection](../../com.aspose.diagram/paracollection)
### getProtection() {#getProtection--}
```
public Protection getProtection()
```


लॉकिंग आकृति में अनजाने बदलावों को रोकने में मदद करती है लेकिन यह माइक्रोसॉफ्ट विजियो को अन्य परिस्थितियों में मानों को रीसेट करने से नहीं रोकती। यह ShapeSheet विंडो में किए गए बदलावों से भी सुरक्षा नहीं देती।

**Returns:**
[Protection](../../com.aspose.diagram/protection)
### getRulerGrid() {#getRulerGrid--}
```
public RulerGrid getRulerGrid()
```


पृष्ठ के रूलर और ग्रिड की सेटिंग्स को निर्दिष्ट करने वाले तत्वों को शामिल करता है।

**Returns:**
[RulerGrid](../../com.aspose.diagram/rulergrid)
### getStyleProp() {#getStyleProp--}
```
public StyleProp getStyleProp()
```


ऐसे तत्व शामिल हैं जो शैली व्यवहार को नियंत्रित करते हैं, जैसे कि शैली में टेक्स्ट, लाइन और फ़िल एट्रिब्यूट शामिल हैं या नहीं।

**Returns:**
[StyleProp](../../com.aspose.diagram/styleprop)
### getTabsCollection() {#getTabsCollection--}
```
public TabsCollection getTabsCollection()
```


Tab तत्वों का संग्रह शामिल करता है।

**Returns:**
[TabsCollection](../../com.aspose.diagram/tabscollection)
### getTextBlock() {#getTextBlock--}
```
public TextBlock getTextBlock()
```


शेप के टेक्स्ट ब्लॉक में टेक्स्ट की संरेखण, मार्जिन और डिफ़ॉल्ट टैब स्टॉप स्थितियों को निर्दिष्ट करने वाले तत्व शामिल करता है।

**Returns:**
[TextBlock](../../com.aspose.diagram/textblock)
### getTextStyle() {#getTextStyle--}
```
public StyleSheet getTextStyle()
```


StyleSheet तत्व जिससे यह शैली text फ़ॉर्मेटिंग विरासत में लेती है।

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
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




### setFillStyle(StyleSheet value) {#setFillStyle-com.aspose.diagram.StyleSheet-}
```
public void setFillStyle(StyleSheet value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getFillStyle()](../../com.aspose.diagram/stylesheet\#getFillStyle--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getID()](../../com.aspose.diagram/stylesheet\#getID--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setLineStyle(StyleSheet value) {#setLineStyle-com.aspose.diagram.StyleSheet-}
```
public void setLineStyle(StyleSheet value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getLineStyle()](../../com.aspose.diagram/stylesheet\#getLineStyle--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getName()](../../com.aspose.diagram/stylesheet\#getName--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getNameU()](../../com.aspose.diagram/stylesheet\#getNameU--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setTextStyle(StyleSheet value) {#setTextStyle-com.aspose.diagram.StyleSheet-}
```
public void setTextStyle(StyleSheet value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getTextStyle()](../../com.aspose.diagram/stylesheet\#getTextStyle--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

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

