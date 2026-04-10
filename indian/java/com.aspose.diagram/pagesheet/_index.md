---
title: PageSheet
second_title: Aspose.Diagram for Java API Reference
description: पृष्ठ या मास्टर तत्व के लिए पृष्ठ शीट को परिभाषित करने वाले तत्वों को शामिल करता है।
type: docs
weight: 270
url: /hi/java/com.aspose.diagram/pagesheet/
---

**Inheritance:**
java.lang.Object
```
public class PageSheet
```

पृष्ठ या मास्टर तत्व के लिए पृष्ठ शीट को परिभाषित करने वाले तत्वों को शामिल करता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [copy(PageSheet source)](#copy-com.aspose.diagram.PageSheet-) | स्रोत ऑब्जेक्ट से pagesheet की प्रतिलिपि बनाता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getActs()](#getActs--) | Act तत्वों का संग्रह शामिल करता है। |
| [getAnnotations()](#getAnnotations--) | ऐसे तत्व शामिल हैं जिनमें दस्तावेज़ पृष्ठ में डाले गए टिप्पणियों की जानकारी होती है। |
| [getClass()](#getClass--) |  |
| [getConnectionABCDs()](#getConnectionABCDs--) | ConnectionABCD तत्वों का संग्रह शामिल करता है। |
| [getConnections()](#getConnections--) | Connection तत्वों का संग्रह शामिल करता है। |
| [getFillStyle()](#getFillStyle--) | StyleSheet तत्व जिससे PageSheet भराव फ़ॉर्मेटिंग विरासत में लेता है। |
| [getForeign()](#getForeign--) | Microsoft Visio दस्तावेज़ में उपयोग किए गए किसी अन्य प्रोग्राम के ऑब्जेक्ट की चौड़ाई और ऊँचाई निर्दिष्ट करने वाले तत्वों को शामिल करता है। |
| [getForeignData()](#getForeignData--) | चित्र डेटा का MIME (Multipurpose Internet Mail Extensions) एन्कोडेड BLOB शामिल करता है, जैसे Windows मेटाफाइल, बिटमैप, या OLE डेटा। |
| [getHyperlinks()](#getHyperlinks--) | Hyperlink तत्वों का एक संग्रह शामिल करता है। |
| [getLayers()](#getLayers--) | Layer तत्वों का संग्रह शामिल करता है। |
| [getLineStyle()](#getLineStyle--) | StyleSheet तत्व जिससे PageSheet रेखा फ़ॉर्मेटिंग विरासत में लेता है। |
| [getPageLayout()](#getPageLayout--) | Diagram शामिल करता है जो आकारों और कनेक्टरों के पेज लेआउट सेटिंग्स को नियंत्रित करता है, जैसे पेज पर सभी आकारों के बीच की दूरी, पेज पर सभी कनेक्टरों के बीच की दूरी, और पेज पर सभी कनेक्टरों के लिए रूटिंग शैली। |
| [getPageProps()](#getPageProps--) | Diagram शामिल है जो पेज गुणों को नियंत्रित करता है, जैसे पेज की चौड़ाई, ऊँचाई, और स्केल। |
| [getPrintProps()](#getPrintProps--) | ऐसे तत्व शामिल करता है जो नियंत्रित करते हैं कि प्रिंटर पृष्ठ पर ड्राइंग पृष्ठ कैसे स्वरूपित (दिखता) है। |
| [getProps()](#getProps--) | Prop तत्वों का एक संग्रह शामिल करता है। |
| [getRulerGrid()](#getRulerGrid--) | पृष्ठ के रूलर और ग्रिड की सेटिंग्स को निर्दिष्ट करने वाले तत्वों को शामिल करता है। |
| [getScratchs()](#getScratchs--) | Scratch तत्वों का एक संग्रह शामिल करता है। |
| [getSmartTagDefs()](#getSmartTagDefs--) | SmartTagDef तत्वों का संग्रह शामिल करता है। |
| [getTextStyle()](#getTextStyle--) | StyleSheet तत्व जिससे PageSheet पाठ फ़ॉर्मेटिंग विरासत में लेता है। |
| [getUniqueID()](#getUniqueID--) | तत्व के लिए एक GUID (वैश्विक रूप से अद्वितीय पहचानकर्ता)। |
| [getUsers()](#getUsers--) | User तत्वों का एक संग्रह शामिल करता है। |
| [getXForm()](#getXForm--) | आकार के बारे में सामान्य पोजिशनिंग जानकारी निर्दिष्ट करने वाले तत्व शामिल हैं। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFillStyle(StyleSheet value)](#setFillStyle-com.aspose.diagram.StyleSheet-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getFillStyle()](../../com.aspose.diagram/pagesheet\#getFillStyle--) |
| [setLineStyle(StyleSheet value)](#setLineStyle-com.aspose.diagram.StyleSheet-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getLineStyle()](../../com.aspose.diagram/pagesheet\#getLineStyle--) |
| [setTextStyle(StyleSheet value)](#setTextStyle-com.aspose.diagram.StyleSheet-) | For the description of this property, please see [getTextStyle()](../../com.aspose.diagram/pagesheet\#getTextStyle--) |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | For the description of this property, please see [getUniqueID()](../../com.aspose.diagram/pagesheet\#getUniqueID--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### copy(PageSheet source) {#copy-com.aspose.diagram.PageSheet-}
```
public void copy(PageSheet source)
```


स्रोत ऑब्जेक्ट से pagesheet की प्रतिलिपि बनाता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| source | [PageSheet](../../com.aspose.diagram/pagesheet) | source pagesheet. |

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
### getActs() {#getActs--}
```
public ActCollection getActs()
```


Act तत्वों का संग्रह शामिल करता है।

**Returns:**
[ActCollection](../../com.aspose.diagram/actcollection)
### getAnnotations() {#getAnnotations--}
```
public AnnotationCollection getAnnotations()
```


ऐसे तत्व शामिल हैं जिनमें दस्तावेज़ पृष्ठ में डाले गए टिप्पणियों की जानकारी होती है।

**Returns:**
[AnnotationCollection](../../com.aspose.diagram/annotationcollection)
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
### getFillStyle() {#getFillStyle--}
```
public StyleSheet getFillStyle()
```


StyleSheet तत्व जिससे PageSheet भराव फ़ॉर्मेटिंग विरासत में लेता है।

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
### getHyperlinks() {#getHyperlinks--}
```
public HyperlinkCollection getHyperlinks()
```


Hyperlink तत्वों का एक संग्रह शामिल करता है।

**Returns:**
[HyperlinkCollection](../../com.aspose.diagram/hyperlinkcollection)
### getLayers() {#getLayers--}
```
public LayerCollection getLayers()
```


Layer तत्वों का संग्रह शामिल करता है।

**Returns:**
[LayerCollection](../../com.aspose.diagram/layercollection)
### getLineStyle() {#getLineStyle--}
```
public StyleSheet getLineStyle()
```


StyleSheet तत्व जिससे PageSheet रेखा फ़ॉर्मेटिंग विरासत में लेता है।

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getPageLayout() {#getPageLayout--}
```
public PageLayout getPageLayout()
```


Diagram शामिल करता है जो आकारों और कनेक्टरों के पेज लेआउट सेटिंग्स को नियंत्रित करता है, जैसे पेज पर सभी आकारों के बीच की दूरी, पेज पर सभी कनेक्टरों के बीच की दूरी, और पेज पर सभी कनेक्टरों के लिए रूटिंग शैली।

**Returns:**
[PageLayout](../../com.aspose.diagram/pagelayout)
### getPageProps() {#getPageProps--}
```
public PageProps getPageProps()
```


Diagram शामिल है जो पेज गुणों को नियंत्रित करता है, जैसे पेज की चौड़ाई, ऊँचाई, और स्केल।

**Returns:**
[PageProps](../../com.aspose.diagram/pageprops)
### getPrintProps() {#getPrintProps--}
```
public PrintProps getPrintProps()
```


ऐसे तत्व शामिल करता है जो नियंत्रित करते हैं कि प्रिंटर पृष्ठ पर ड्राइंग पृष्ठ कैसे स्वरूपित (दिखता) है।

**Returns:**
[PrintProps](../../com.aspose.diagram/printprops)
### getProps() {#getProps--}
```
public PropCollection getProps()
```


Prop तत्वों का एक संग्रह शामिल करता है।

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getRulerGrid() {#getRulerGrid--}
```
public RulerGrid getRulerGrid()
```


पृष्ठ के रूलर और ग्रिड की सेटिंग्स को निर्दिष्ट करने वाले तत्वों को शामिल करता है।

**Returns:**
[RulerGrid](../../com.aspose.diagram/rulergrid)
### getScratchs() {#getScratchs--}
```
public ScratchCollection getScratchs()
```


Scratch तत्वों का एक संग्रह शामिल करता है।

**Returns:**
[ScratchCollection](../../com.aspose.diagram/scratchcollection)
### getSmartTagDefs() {#getSmartTagDefs--}
```
public SmartTagDefCollection getSmartTagDefs()
```


SmartTagDef तत्वों का संग्रह शामिल करता है।

**Returns:**
[SmartTagDefCollection](../../com.aspose.diagram/smarttagdefcollection)
### getTextStyle() {#getTextStyle--}
```
public StyleSheet getTextStyle()
```


StyleSheet तत्व जिससे PageSheet पाठ फ़ॉर्मेटिंग विरासत में लेता है।

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


तत्व के लिए एक GUID (वैश्विक रूप से अद्वितीय पहचानकर्ता)।

**Returns:**
java.util.UUID
### getUsers() {#getUsers--}
```
public UserCollection getUsers()
```


User तत्वों का एक संग्रह शामिल करता है।

**Returns:**
[UserCollection](../../com.aspose.diagram/usercollection)
### getXForm() {#getXForm--}
```
public XForm getXForm()
```


आकार के बारे में सामान्य पोजिशनिंग जानकारी निर्दिष्ट करने वाले तत्व शामिल हैं।

**Returns:**
[XForm](../../com.aspose.diagram/xform)
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


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getFillStyle()](../../com.aspose.diagram/pagesheet\#getFillStyle--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setLineStyle(StyleSheet value) {#setLineStyle-com.aspose.diagram.StyleSheet-}
```
public void setLineStyle(StyleSheet value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getLineStyle()](../../com.aspose.diagram/pagesheet\#getLineStyle--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setTextStyle(StyleSheet value) {#setTextStyle-com.aspose.diagram.StyleSheet-}
```
public void setTextStyle(StyleSheet value)
```


For the description of this property, please see [getTextStyle()](../../com.aspose.diagram/pagesheet\#getTextStyle--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


For the description of this property, please see [getUniqueID()](../../com.aspose.diagram/pagesheet\#getUniqueID--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.util.UUID |  |

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

