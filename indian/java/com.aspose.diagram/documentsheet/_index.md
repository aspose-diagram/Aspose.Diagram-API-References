---
title: DocumentSheet
second_title: Aspose.Diagram for Java API Reference
description: एक दस्तावेज़ के ShapeSheet संरचना को निर्दिष्ट करता है।
type: docs
weight: 127
url: /hi/java/com.aspose.diagram/documentsheet/
---

**Inheritance:**
java.lang.Object
```
public class DocumentSheet
```

दस्तावेज़ की ShapeSheet संरचना निर्दिष्ट करता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAnnotations()](#getAnnotations--) | ऐसे तत्व शामिल हैं जिनमें दस्तावेज़ पृष्ठ में डाले गए टिप्पणियों की जानकारी होती है। |
| [getClass()](#getClass--) |  |
| [getConnectionABCDs()](#getConnectionABCDs--) | ConnectionABCD तत्वों का संग्रह शामिल करता है। |
| [getConnections()](#getConnections--) | Connection तत्वों का संग्रह शामिल करता है। |
| [getDocProps()](#getDocProps--) | दस्तावेज़ के पूर्वावलोकन गुणवत्ता, दायरा और आउटपुट प्रारूप को नियंत्रित करने वाले तत्व शामिल हैं। |
| [getFillStyle()](#getFillStyle--) | StyleSheet तत्व जिससे यह शैली fill फ़ॉर्मेटिंग विरासत में लेती है। |
| [getForeign()](#getForeign--) | Microsoft Visio दस्तावेज़ में उपयोग किए गए किसी अन्य प्रोग्राम के ऑब्जेक्ट की चौड़ाई और ऊँचाई निर्दिष्ट करने वाले तत्वों को शामिल करता है। |
| [getForeignData()](#getForeignData--) | चित्र डेटा का MIME (Multipurpose Internet Mail Extensions) एन्कोडेड BLOB शामिल करता है, जैसे Windows मेटाफाइल, बिटमैप, या OLE डेटा। |
| [getHyperlinks()](#getHyperlinks--) | Hyperlink तत्वों का एक संग्रह शामिल करता है। |
| [getLineStyle()](#getLineStyle--) | StyleSheet तत्व जिससे यह शैली line फ़ॉर्मेटिंग विरासत में लेती है। |
| [getName()](#getName--) | तत्व का नाम। |
| [getNameU()](#getNameU--) | तत्व का सार्वभौमिक नाम। |
| [getProps()](#getProps--) | Prop तत्वों का एक संग्रह शामिल करता है। |
| [getReviewers()](#getReviewers--) | दस्तावेज़ समीक्षक के बारे में पहचान जानकारी वाले तत्वों को शामिल करता है। |
| [getScratchs()](#getScratchs--) | Scratch तत्वों का एक संग्रह शामिल करता है। |
| [getTextStyle()](#getTextStyle--) | StyleSheet तत्व जिससे यह शैली text फ़ॉर्मेटिंग विरासत में लेती है। |
| [getUniqueID()](#getUniqueID--) | एक GUID (वैश्विक रूप से अद्वितीय पहचानकर्ता) जो आकार की पहचान करता है। |
| [getUsers()](#getUsers--) | User तत्वों का एक संग्रह शामिल करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFillStyle(StyleSheet value)](#setFillStyle-com.aspose.diagram.StyleSheet-) | इस गुण के विवरण के लिए, कृपया देखें [getFillStyle()](../../com.aspose.diagram/documentsheet\#getFillStyle--) |
| [setLineStyle(StyleSheet value)](#setLineStyle-com.aspose.diagram.StyleSheet-) | इस गुण के विवरण के लिए, कृपया देखें [getLineStyle()](../../com.aspose.diagram/documentsheet\#getLineStyle--) |
| [setName(String value)](#setName-java.lang.String-) | इस गुण के विवरण के लिए, कृपया देखें [getName()](../../com.aspose.diagram/documentsheet\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | इस गुण के विवरण के लिए, कृपया देखें [getNameU()](../../com.aspose.diagram/documentsheet\#getNameU--) |
| [setTextStyle(StyleSheet value)](#setTextStyle-com.aspose.diagram.StyleSheet-) | इस गुण के विवरण के लिए, कृपया देखें [getTextStyle()](../../com.aspose.diagram/documentsheet\#getTextStyle--) |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | इस गुण के विवरण के लिए, कृपया देखें [getUniqueID()](../../com.aspose.diagram/documentsheet\#getUniqueID--) |
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
### getDocProps() {#getDocProps--}
```
public DocProps getDocProps()
```


दस्तावेज़ के पूर्वावलोकन गुणवत्ता, दायरा और आउटपुट प्रारूप को नियंत्रित करने वाले तत्व शामिल हैं।

**Returns:**
[DocProps](../../com.aspose.diagram/docprops)
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
### getHyperlinks() {#getHyperlinks--}
```
public HyperlinkCollection getHyperlinks()
```


Hyperlink तत्वों का एक संग्रह शामिल करता है।

**Returns:**
[HyperlinkCollection](../../com.aspose.diagram/hyperlinkcollection)
### getLineStyle() {#getLineStyle--}
```
public StyleSheet getLineStyle()
```


StyleSheet तत्व जिससे यह शैली line फ़ॉर्मेटिंग विरासत में लेती है।

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
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
### getProps() {#getProps--}
```
public PropCollection getProps()
```


Prop तत्वों का एक संग्रह शामिल करता है।

**Returns:**
[PropCollection](../../com.aspose.diagram/propcollection)
### getReviewers() {#getReviewers--}
```
public ReviewerCollection getReviewers()
```


दस्तावेज़ समीक्षक के बारे में पहचान जानकारी वाले तत्वों को शामिल करता है।

**Returns:**
[ReviewerCollection](../../com.aspose.diagram/reviewercollection)
### getScratchs() {#getScratchs--}
```
public ScratchCollection getScratchs()
```


Scratch तत्वों का एक संग्रह शामिल करता है।

**Returns:**
[ScratchCollection](../../com.aspose.diagram/scratchcollection)
### getTextStyle() {#getTextStyle--}
```
public StyleSheet getTextStyle()
```


StyleSheet तत्व जिससे यह शैली text फ़ॉर्मेटिंग विरासत में लेती है।

**Returns:**
[StyleSheet](../../com.aspose.diagram/stylesheet)
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


एक GUID (वैश्विक रूप से अद्वितीय पहचानकर्ता) जो आकार की पहचान करता है।

**Returns:**
java.util.UUID
### getUsers() {#getUsers--}
```
public UserCollection getUsers()
```


User तत्वों का एक संग्रह शामिल करता है।

**Returns:**
[UserCollection](../../com.aspose.diagram/usercollection)
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


इस गुण के विवरण के लिए, कृपया देखें [getFillStyle()](../../com.aspose.diagram/documentsheet\#getFillStyle--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setLineStyle(StyleSheet value) {#setLineStyle-com.aspose.diagram.StyleSheet-}
```
public void setLineStyle(StyleSheet value)
```


इस गुण के विवरण के लिए, कृपया देखें [getLineStyle()](../../com.aspose.diagram/documentsheet\#getLineStyle--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


इस गुण के विवरण के लिए, कृपया देखें [getName()](../../com.aspose.diagram/documentsheet\#getName--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


इस गुण के विवरण के लिए, कृपया देखें [getNameU()](../../com.aspose.diagram/documentsheet\#getNameU--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setTextStyle(StyleSheet value) {#setTextStyle-com.aspose.diagram.StyleSheet-}
```
public void setTextStyle(StyleSheet value)
```


इस गुण के विवरण के लिए, कृपया देखें [getTextStyle()](../../com.aspose.diagram/documentsheet\#getTextStyle--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [StyleSheet](../../com.aspose.diagram/stylesheet) |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


इस गुण के विवरण के लिए, कृपया देखें [getUniqueID()](../../com.aspose.diagram/documentsheet\#getUniqueID--)

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

