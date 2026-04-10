---
title: Master
second_title: Aspose.Diagram for Java API Reference
description: दस्तावेज़ के लिए मास्टर को परिभाषित करने वाले तत्व शामिल करता है।
type: docs
weight: 240
url: /hi/java/com.aspose.diagram/master/
---

**Inheritance:**
java.lang.Object
```
public class Master
```

दस्तावेज़ के लिए master को परिभाषित करने वाले तत्व शामिल हैं। एक master स्टेंसिल पर एक आकार है जिसे आप बार‑बार ड्रॉइंग बनाने के लिए उपयोग करते हैं। जब आप स्टेंसिल से किसी आकार को ड्रॉइंग पृष्ठ पर खींचते हैं, तो वह आकार उस master का एक उदाहरण बन जाता है, और master की एक स्थानीय प्रति दस्तावेज़ में शामिल हो जाती है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [Master()](#Master--) | कंस्ट्रक्टर। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [deepClone()](#deepClone--) | इस उदाहरण की गहरी प्रतिलिपि बनाता है। |
| [dispose()](#dispose--) | अनप्रबंधित संसाधनों को मुक्त करने, रिलीज़ करने या रीसेट करने से संबंधित एप्लिकेशन‑परिभाषित कार्यों को निष्पादित करता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignName()](#getAlignName--) | निर्दिष्ट करता है कि स्टेंसिल विंडो में master के पाठ को बाएँ, दाएँ या केंद्र में संरेखित किया गया है या नहीं। |
| [getBaseID()](#getBaseID--) | एक GUID (वैश्विक रूप से अद्वितीय पहचानकर्ता) जो विभिन्न दस्तावेज़ों में master की पहचान करता है। |
| [getClass()](#getClass--) |  |
| [getConnects()](#getConnects--) | ड्रॉइंग में दो आकारों के बीच प्रत्येक कनेक्शन के लिए एक Connect तत्व शामिल करता है। |
| [getHidden()](#getHidden--) | निर्दिष्ट करता है कि उपयोगकर्ता इंटरफ़ेस में master छिपा हुआ है या नहीं। |
| [getID()](#getID--) | तत्व के अपने पैरेंट तत्व के भीतर अद्वितीय ID। |
| [getIcon()](#getIcon--) | दस्तावेज़ में Master या MasterShortcut तत्व के लिए एक MIME (Multipurpose Internet Mail Extensions) एन्कोडेड बाइनरी आइकन (.ico फ़ॉर्मेट में) निर्दिष्ट करता है। |
| [getIconSize()](#getIconSize--) | तत्व के आइकन का आकार। |
| [getIconUpdate()](#getIconUpdate--) | निर्दिष्ट करता है कि आइकन master से स्वचालित रूप से उत्पन्न किया गया है या नहीं। |
| [getMatchByName()](#getMatchByName--) | MatchByName विशेषता यह निर्धारित करती है कि Microsoft Visio कैसे तय करता है कि जब master का एक उदाहरण ड्रॉइंग पृष्ठ पर गिराया जाता है तो क्या दस्तावेज़ में master पहले से मौजूद है। |
| [getName()](#getName--) | तत्व का नाम। |
| [getNameU()](#getNameU--) | तत्व का सार्वभौमिक नाम। |
| [getPageSheet()](#getPageSheet--) | पृष्ठ या मास्टर तत्व के लिए पृष्ठ शीट को परिभाषित करने वाले तत्वों को शामिल करता है। |
| [getPatternFlags()](#getPatternFlags--) | PatternFlags गुण यह निर्धारित करता है कि कोई मास्टर कस्टम पैटर्न के रूप में व्यवहार करता है या नहीं। |
| [getPrompt()](#getPrompt--) | स्थिति पट्टी और टूलटिप तत्व के लिए संकेत प्रदान करती है। |
| [getShapes()](#getShapes--) | Shape वस्तुओं का संग्रह। |
| [getUniqueID()](#getUniqueID--) | एक GUID जो दस्तावेज़ में मास्टर की पहचान करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignName(int value)](#setAlignName-int-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getAlignName()](../../com.aspose.diagram/master\#getAlignName--) |
| [setBaseID(UUID value)](#setBaseID-java.util.UUID-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getBaseID()](../../com.aspose.diagram/master\#getBaseID--) |
| [setHidden(int value)](#setHidden-int-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getHidden()](../../com.aspose.diagram/master\#getHidden--) |
| [setID(int value)](#setID-int-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getID()](../../com.aspose.diagram/master\#getID--) |
| [setIcon(byte[] value)](#setIcon-byte---) | इस गुण का विवरण देखने के लिए, कृपया देखें [getIcon()](../../com.aspose.diagram/master\#getIcon--) |
| [setIconSize(int value)](#setIconSize-int-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getIconSize()](../../com.aspose.diagram/master\#getIconSize--) |
| [setIconUpdate(int value)](#setIconUpdate-int-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getIconUpdate()](../../com.aspose.diagram/master\#getIconUpdate--) |
| [setMatchByName(int value)](#setMatchByName-int-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getMatchByName()](../../com.aspose.diagram/master\#getMatchByName--) |
| [setName(String value)](#setName-java.lang.String-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getName()](../../com.aspose.diagram/master\#getName--) |
| [setNameU(String value)](#setNameU-java.lang.String-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getNameU()](../../com.aspose.diagram/master\#getNameU--) |
| [setPatternFlags(int value)](#setPatternFlags-int-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getPatternFlags()](../../com.aspose.diagram/master\#getPatternFlags--) |
| [setPrompt(String value)](#setPrompt-java.lang.String-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getPrompt()](../../com.aspose.diagram/master\#getPrompt--) |
| [setUniqueID(UUID value)](#setUniqueID-java.util.UUID-) | इस गुण का विवरण देखने के लिए, कृपया देखें [getUniqueID()](../../com.aspose.diagram/master\#getUniqueID--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Master() {#Master--}
```
public Master()
```


कंस्ट्रक्टर।

### deepClone() {#deepClone--}
```
public Object deepClone()
```


इस उदाहरण की गहरी प्रतिलिपि बनाता है।

**Returns:**
java.lang.Object -
### dispose() {#dispose--}
```
public void dispose()
```


अनप्रबंधित संसाधनों को मुक्त करने, रिलीज़ करने या रीसेट करने से संबंधित एप्लिकेशन‑परिभाषित कार्यों को निष्पादित करता है।

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
### getAlignName() {#getAlignName--}
```
public int getAlignName()
```


निर्दिष्ट करता है कि स्टेंसिल विंडो में master के पाठ को बाएँ, दाएँ या केंद्र में संरेखित किया गया है या नहीं।

**Returns:**
int
### getBaseID() {#getBaseID--}
```
public UUID getBaseID()
```


एक GUID (वैश्विक रूप से अद्वितीय पहचानकर्ता) जो विभिन्न दस्तावेज़ों में master की पहचान करता है।

**Returns:**
java.util.UUID
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConnects() {#getConnects--}
```
public ConnectCollection getConnects()
```


ड्रॉइंग में दो आकारों के बीच प्रत्येक कनेक्शन के लिए एक Connect तत्व शामिल करता है।

**Returns:**
[ConnectCollection](../../com.aspose.diagram/connectcollection)
### getHidden() {#getHidden--}
```
public int getHidden()
```


निर्दिष्ट करता है कि उपयोगकर्ता इंटरफ़ेस में master छिपा हुआ है या नहीं।

**Returns:**
int
### getID() {#getID--}
```
public int getID()
```


तत्व के अपने पैरेंट तत्व के भीतर अद्वितीय ID।

**Returns:**
int
### getIcon() {#getIcon--}
```
public byte[] getIcon()
```


दस्तावेज़ में Master या MasterShortcut तत्व के लिए एक MIME (Multipurpose Internet Mail Extensions) एन्कोडेड बाइनरी आइकन (.ico फ़ॉर्मेट में) निर्दिष्ट करता है।

**Returns:**
बाइट[]
### getIconSize() {#getIconSize--}
```
public int getIconSize()
```


तत्व के आइकन का आकार।

**Returns:**
int
### getIconUpdate() {#getIconUpdate--}
```
public int getIconUpdate()
```


निर्दिष्ट करता है कि आइकन master से स्वचालित रूप से उत्पन्न किया गया है या नहीं।

**Returns:**
int
### getMatchByName() {#getMatchByName--}
```
public int getMatchByName()
```


MatchByName गुण यह निर्धारित करता है कि Microsoft Visio कैसे तय करता है कि जब ड्राइंग पेज पर एक मास्टर का उदाहरण गिराया जाता है तो क्या दस्तावेज़ मास्टर पहले से मौजूद है। यह दस्तावेज़ मास्टर में किए गए परिवर्तन को मास्टर के नए उदाहरणों पर लागू होने देता है, भले ही उदाहरण एक स्वतंत्र स्टेंसिल फ़ाइल से खींचे गए हों।

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
### getPageSheet() {#getPageSheet--}
```
public PageSheet getPageSheet()
```


पृष्ठ या मास्टर तत्व के लिए पृष्ठ शीट को परिभाषित करने वाले तत्वों को शामिल करता है।

**Returns:**
[PageSheet](../../com.aspose.diagram/pagesheet)
### getPatternFlags() {#getPatternFlags--}
```
public int getPatternFlags()
```


PatternFlags गुण यह निर्धारित करता है कि कोई मास्टर कस्टम पैटर्न के रूप में व्यवहार करता है या नहीं।

**Returns:**
int
### getPrompt() {#getPrompt--}
```
public String getPrompt()
```


स्थिति पट्टी और टूलटिप तत्व के लिए संकेत प्रदान करती है।

**Returns:**
java.lang.String
### getShapes() {#getShapes--}
```
public ShapeCollection getShapes()
```


Shape वस्तुओं का संग्रह।

**Returns:**
[ShapeCollection](../../com.aspose.diagram/shapecollection)
### getUniqueID() {#getUniqueID--}
```
public UUID getUniqueID()
```


एक GUID जो दस्तावेज़ में मास्टर की पहचान करता है।

**Returns:**
java.util.UUID
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




### setAlignName(int value) {#setAlignName-int-}
```
public void setAlignName(int value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getAlignName()](../../com.aspose.diagram/master\#getAlignName--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setBaseID(UUID value) {#setBaseID-java.util.UUID-}
```
public void setBaseID(UUID value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getBaseID()](../../com.aspose.diagram/master\#getBaseID--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.util.UUID |  |

### setHidden(int value) {#setHidden-int-}
```
public void setHidden(int value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getHidden()](../../com.aspose.diagram/master\#getHidden--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setID(int value) {#setID-int-}
```
public void setID(int value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getID()](../../com.aspose.diagram/master\#getID--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setIcon(byte[] value) {#setIcon-byte---}
```
public void setIcon(byte[] value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getIcon()](../../com.aspose.diagram/master\#getIcon--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | बाइट[] |  |

### setIconSize(int value) {#setIconSize-int-}
```
public void setIconSize(int value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getIconSize()](../../com.aspose.diagram/master\#getIconSize--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setIconUpdate(int value) {#setIconUpdate-int-}
```
public void setIconUpdate(int value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getIconUpdate()](../../com.aspose.diagram/master\#getIconUpdate--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setMatchByName(int value) {#setMatchByName-int-}
```
public void setMatchByName(int value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getMatchByName()](../../com.aspose.diagram/master\#getMatchByName--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getName()](../../com.aspose.diagram/master\#getName--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setNameU(String value) {#setNameU-java.lang.String-}
```
public void setNameU(String value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getNameU()](../../com.aspose.diagram/master\#getNameU--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setPatternFlags(int value) {#setPatternFlags-int-}
```
public void setPatternFlags(int value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getPatternFlags()](../../com.aspose.diagram/master\#getPatternFlags--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setPrompt(String value) {#setPrompt-java.lang.String-}
```
public void setPrompt(String value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getPrompt()](../../com.aspose.diagram/master\#getPrompt--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setUniqueID(UUID value) {#setUniqueID-java.util.UUID-}
```
public void setUniqueID(UUID value)
```


इस गुण का विवरण देखने के लिए, कृपया देखें [getUniqueID()](../../com.aspose.diagram/master\#getUniqueID--)

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

