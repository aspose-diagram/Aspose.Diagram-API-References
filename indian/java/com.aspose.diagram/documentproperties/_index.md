---
title: DocumentProperties
second_title: Aspose.Diagram for Java API Reference
description: दस्तावेज़ प्रॉपर्टी तत्वों को शामिल करता है जैसे दस्तावेज़ का शीर्षक, लेखक आदि।
type: docs
weight: 125
url: /hi/java/com.aspose.diagram/documentproperties/
---

**Inheritance:**
java.lang.Object
```
public class DocumentProperties
```

दस्तावेज़ के शीर्षक, लेखक आदि जैसे दस्तावेज़ गुण तत्व शामिल हैं।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlternateNames()](#getAlternateNames--) | दस्तावेज़ के वैकल्पिक नाम निर्दिष्ट करता है। |
| [getBuildNumberCreated()](#getBuildNumberCreated--) | दस्तावेज़ बनाने के लिए उपयोग किए गए इंस्टेंस का पूर्ण बिल्ड नंबर शामिल करता है। |
| [getBuildNumberEdited()](#getBuildNumberEdited--) | दस्तावेज़ को अंतिम बार संपादित करने के लिए उपयोग किए गए इंस्टेंस का बिल्ड नंबर शामिल करता है। |
| [getCategory()](#getCategory--) | ड्राइंग के प्रकार के लिए वर्णनात्मक पाठ निर्दिष्ट करता है, जैसे फ्लोचार्ट या ऑफिस लेआउट। |
| [getClass()](#getClass--) |  |
| [getCompany()](#getCompany--) | ड्राइंग बनाने वाली कंपनी या जिसके लिए ड्राइंग बनाई जा रही है, को पहचानने वाली उपयोगकर्ता-प्रविष्ट जानकारी शामिल करता है। |
| [getCreator()](#getCreator--) | फ़ाइल को किसने बनाया या अंतिम बार अपडेट किया, यह पहचानता है। |
| [getCustomProps()](#getCustomProps--) | CustomProp का संग्रह। |
| [getDesc()](#getDesc--) | दस्तावेज़ के लिए एक वर्णनात्मक टेक्स्ट स्ट्रिंग शामिल करता है। |
| [getHyperlinkBase()](#getHyperlinkBase--) | रिलेटिव हाइपरलिंक्स के लिए उपयोग किया जाने वाला पाथ शामिल करता है (हाइपरलिंक्स जिनमें लिंक्ड फ़ाइल का स्थान Microsoft Visio डायग्राम के संदर्भ में वर्णित है)। |
| [getKeywords()](#getKeywords--) | फ़ाइल के बारे में विषय या अन्य महत्वपूर्ण जानकारी, जैसे प्रोजेक्ट नाम, क्लाइंट नाम, या संस्करण संख्या, को पहचानने वाला टेक्स्ट स्ट्रिंग शामिल करता है। |
| [getLanguage()](#getLanguage--) | भाषा निर्दिष्ट करता है |
| [getManager()](#getManager--) | प्रोजेक्ट या विभाग के जिम्मेदार व्यक्ति की पहचान करने वाला उपयोगकर्ता-प्रविष्ट टेक्स्ट स्ट्रिंग शामिल करता है। |
| [getPreviewPicture()](#getPreviewPicture--) | दस्तावेज़ का पूर्वावलोकन प्रदान करने वाले मेटाफाइल स्ट्रीम को शामिल करता है। |
| [getSubject()](#getSubject--) | दस्तावेज़ की सामग्री का वर्णन करने वाला उपयोगकर्ता-परिभाषित टेक्स्ट स्ट्रिंग शामिल करता है। |
| [getTemplate()](#getTemplate--) | उस टेम्पलेट की फ़ाइल नाम निर्दिष्ट करने वाला स्ट्रिंग मान शामिल करता है जिससे दस्तावेज़ बनाया गया था। |
| [getTimeCreated()](#getTimeCreated--) | दस्तावेज़ कब बनाया गया था, यह दर्शाने वाली तिथि और समय मान शामिल करता है। |
| [getTimeEdited()](#getTimeEdited--) | दस्तावेज़ आखिरी बार कब संपादित किया गया था, यह दर्शाने वाली तिथि और समय मान शामिल करता है। |
| [getTimePrinted()](#getTimePrinted--) | दस्तावेज़ आखिरी बार कब प्रिंट किया गया था, यह दर्शाने वाली तिथि और समय मान शामिल करता है। |
| [getTimeSaved()](#getTimeSaved--) | दस्तावेज़ आखिरी बार कब सहेजा गया था, यह दर्शाने वाली तिथि और समय मान शामिल करता है। |
| [getTitle()](#getTitle--) | दस्तावेज़ के लिए वर्णनात्मक शीर्षक के रूप में कार्य करने वाला उपयोगकर्ता-परिभाषित टेक्स्ट स्ट्रिंग शामिल करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlternateNames(String value)](#setAlternateNames-java.lang.String-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getAlternateNames()](../../com.aspose.diagram/documentproperties\#getAlternateNames--) |
| [setBuildNumberCreated(String value)](#setBuildNumberCreated-java.lang.String-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getBuildNumberCreated()](../../com.aspose.diagram/documentproperties\#getBuildNumberCreated--) |
| [setBuildNumberEdited(String value)](#setBuildNumberEdited-java.lang.String-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getBuildNumberEdited()](../../com.aspose.diagram/documentproperties\#getBuildNumberEdited--) |
| [setCategory(String value)](#setCategory-java.lang.String-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getCategory()](../../com.aspose.diagram/documentproperties\#getCategory--) |
| [setCompany(String value)](#setCompany-java.lang.String-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getCompany()](../../com.aspose.diagram/documentproperties\#getCompany--) |
| [setCreator(String value)](#setCreator-java.lang.String-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getCreator()](../../com.aspose.diagram/documentproperties\#getCreator--) |
| [setDesc(String value)](#setDesc-java.lang.String-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getDesc()](../../com.aspose.diagram/documentproperties\#getDesc--) |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getHyperlinkBase()](../../com.aspose.diagram/documentproperties\#getHyperlinkBase--) |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getKeywords()](../../com.aspose.diagram/documentproperties\#getKeywords--) |
| [setLanguage(String value)](#setLanguage-java.lang.String-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getLanguage()](../../com.aspose.diagram/documentproperties\#getLanguage--) |
| [setManager(String value)](#setManager-java.lang.String-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getManager()](../../com.aspose.diagram/documentproperties\#getManager--) |
| [setPreviewPicture(byte[] value)](#setPreviewPicture-byte---) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getPreviewPicture()](../../com.aspose.diagram/documentproperties\#getPreviewPicture--) |
| [setSubject(String value)](#setSubject-java.lang.String-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getSubject()](../../com.aspose.diagram/documentproperties\#getSubject--) |
| [setTemplate(String value)](#setTemplate-java.lang.String-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getTemplate()](../../com.aspose.diagram/documentproperties\#getTemplate--) |
| [setTimeCreated(DateTime value)](#setTimeCreated-com.aspose.diagram.DateTime-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getTimeCreated()](../../com.aspose.diagram/documentproperties\#getTimeCreated--) |
| [setTimeEdited(DateTime value)](#setTimeEdited-com.aspose.diagram.DateTime-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getTimeEdited()](../../com.aspose.diagram/documentproperties\#getTimeEdited--) |
| [setTimePrinted(DateTime value)](#setTimePrinted-com.aspose.diagram.DateTime-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getTimePrinted()](../../com.aspose.diagram/documentproperties\#getTimePrinted--) |
| [setTimeSaved(DateTime value)](#setTimeSaved-com.aspose.diagram.DateTime-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getTimeSaved()](../../com.aspose.diagram/documentproperties\#getTimeSaved--) |
| [setTitle(String value)](#setTitle-java.lang.String-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getTitle()](../../com.aspose.diagram/documentproperties\#getTitle--) |
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
### getAlternateNames() {#getAlternateNames--}
```
public String getAlternateNames()
```


दस्तावेज़ के वैकल्पिक नाम निर्दिष्ट करता है।

**Returns:**
java.lang.String
### getBuildNumberCreated() {#getBuildNumberCreated--}
```
public String getBuildNumberCreated()
```


दस्तावेज़ बनाने के लिए उपयोग किए गए इंस्टेंस का पूर्ण बिल्ड नंबर शामिल करता है।

**Returns:**
java.lang.String
### getBuildNumberEdited() {#getBuildNumberEdited--}
```
public String getBuildNumberEdited()
```


दस्तावेज़ को अंतिम बार संपादित करने के लिए उपयोग किए गए इंस्टेंस का बिल्ड नंबर शामिल करता है।

**Returns:**
java.lang.String
### getCategory() {#getCategory--}
```
public String getCategory()
```


ड्राइंग के प्रकार, जैसे फ्लोचार्ट या ऑफिस लेआउट, के लिए वर्णनात्मक पाठ निर्दिष्ट करता है। यह पाठ माइक्रोसॉफ्ट विजियो उपयोगकर्ता इंटरफ़ेस में प्रॉपर्टीज़ संवाद बॉक्स के कैटेगरी बॉक्स में भी दर्ज किया जा सकता है।

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCompany() {#getCompany--}
```
public String getCompany()
```


उपयोगकर्ता द्वारा दर्ज की गई जानकारी जिसमें ड्राइंग बनाने वाली कंपनी या जिसके लिए ड्राइंग बनाई जा रही है, वह कंपनी शामिल है। अधिकतम लंबाई 63 अक्षर है।

**Returns:**
java.lang.String
### getCreator() {#getCreator--}
```
public String getCreator()
```


फ़ाइल को किसने बनाया या आखिरी बार अपडेट किया, यह पहचानता है। अधिकतम लंबाई 63 अक्षर है।

**Returns:**
java.lang.String
### getCustomProps() {#getCustomProps--}
```
public CustomPropCollection getCustomProps()
```


CustomProp का संग्रह।

**Returns:**
[CustomPropCollection](../../com.aspose.diagram/custompropcollection)
### getDesc() {#getDesc--}
```
public String getDesc()
```


दस्तावेज़ के लिए वर्णनात्मक टेक्स्ट स्ट्रिंग रखता है। इस तत्व का उपयोग दस्तावेज़ के बारे में महत्वपूर्ण जानकारी जैसे इसका उद्देश्य, हालिया परिवर्तन, या लंबित परिवर्तन संग्रहीत करने के लिए करें। अधिकतम 191 अक्षर है।

**Returns:**
java.lang.String
### getHyperlinkBase() {#getHyperlinkBase--}
```
public String getHyperlinkBase()
```


रिलेटिव हाइपरलिंक (हाइपरलिंक जहाँ लिंक की फ़ाइल स्थान माइक्रोसॉफ्ट विजियो डायग्राम के सापेक्ष वर्णित है) के लिए उपयोग किया जाने वाला पथ रखता है। डिफ़ॉल्ट रूप से, हाइपरलिंक पथ वर्तमान दस्तावेज़ के सापेक्ष होता है जब तक कि इस तत्व में अलग पथ निर्दिष्ट न किया गया हो। अधिकतम लंबाई 256 अक्षर है।

**Returns:**
java.lang.String
### getKeywords() {#getKeywords--}
```
public String getKeywords()
```


फ़ाइल के बारे में विषय या अन्य महत्वपूर्ण जानकारी जैसे प्रोजेक्ट नाम, क्लाइंट नाम, या संस्करण संख्या पहचानने वाला टेक्स्ट स्ट्रिंग रखता है। अधिकतम स्ट्रिंग लंबाई 63 अक्षर है।

**Returns:**
java.lang.String
### getLanguage() {#getLanguage--}
```
public String getLanguage()
```


भाषा निर्दिष्ट करता है

```
setLanguage("en-GB");
         setLanguage("en-US");
```

**Returns:**
java.lang.String
### getManager() {#getManager--}
```
public String getManager()
```


प्रोजेक्ट या विभाग के जिम्मेदार व्यक्ति की पहचान करने वाला उपयोगकर्ता-प्रविष्ट टेक्स्ट स्ट्रिंग रखता है। अधिकतम लंबाई 63 अक्षर है।

**Returns:**
java.lang.String
### getPreviewPicture() {#getPreviewPicture--}
```
public byte[] getPreviewPicture()
```


दस्तावेज़ का पूर्वावलोकन प्रदान करने वाले मेटाफाइल स्ट्रीम को शामिल करता है।

**Returns:**
बाइट[]
### getSubject() {#getSubject--}
```
public String getSubject()
```


दस्तावेज़ की सामग्री का वर्णन करने वाला उपयोगकर्ता-परिभाषित टेक्स्ट स्ट्रिंग रखता है। अधिकतम लंबाई 63 अक्षर है।

**Returns:**
java.lang.String
### getTemplate() {#getTemplate--}
```
public String getTemplate()
```


उस टेम्पलेट की फ़ाइल नाम निर्दिष्ट करने वाला स्ट्रिंग मान शामिल करता है जिससे दस्तावेज़ बनाया गया था।

**Returns:**
java.lang.String
### getTimeCreated() {#getTimeCreated--}
```
public DateTime getTimeCreated()
```


दस्तावेज़ कब बनाया गया था, यह दर्शाने वाली तिथि और समय मान शामिल करता है।

**Returns:**
[DateTime](../../com.aspose.diagram/datetime)
### getTimeEdited() {#getTimeEdited--}
```
public DateTime getTimeEdited()
```


दस्तावेज़ आखिरी बार कब संपादित किया गया था, यह दर्शाने वाली तिथि और समय मान शामिल करता है।

**Returns:**
[DateTime](../../com.aspose.diagram/datetime)
### getTimePrinted() {#getTimePrinted--}
```
public DateTime getTimePrinted()
```


दस्तावेज़ आखिरी बार कब प्रिंट किया गया था, यह दर्शाने वाली तिथि और समय मान शामिल करता है।

**Returns:**
[DateTime](../../com.aspose.diagram/datetime)
### getTimeSaved() {#getTimeSaved--}
```
public DateTime getTimeSaved()
```


दस्तावेज़ आखिरी बार कब सहेजा गया था, यह दर्शाने वाली तिथि और समय मान शामिल करता है।

**Returns:**
[DateTime](../../com.aspose.diagram/datetime)
### getTitle() {#getTitle--}
```
public String getTitle()
```


दस्तावेज़ के लिए वर्णनात्मक शीर्षक के रूप में कार्य करने वाला उपयोगकर्ता-परिभाषित टेक्स्ट स्ट्रिंग रखता है। अधिकतम लंबाई 63 अक्षर है।

**Returns:**
java.lang.String
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




### setAlternateNames(String value) {#setAlternateNames-java.lang.String-}
```
public void setAlternateNames(String value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getAlternateNames()](../../com.aspose.diagram/documentproperties\#getAlternateNames--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setBuildNumberCreated(String value) {#setBuildNumberCreated-java.lang.String-}
```
public void setBuildNumberCreated(String value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getBuildNumberCreated()](../../com.aspose.diagram/documentproperties\#getBuildNumberCreated--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setBuildNumberEdited(String value) {#setBuildNumberEdited-java.lang.String-}
```
public void setBuildNumberEdited(String value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getBuildNumberEdited()](../../com.aspose.diagram/documentproperties\#getBuildNumberEdited--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setCategory(String value) {#setCategory-java.lang.String-}
```
public void setCategory(String value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getCategory()](../../com.aspose.diagram/documentproperties\#getCategory--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setCompany(String value) {#setCompany-java.lang.String-}
```
public void setCompany(String value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getCompany()](../../com.aspose.diagram/documentproperties\#getCompany--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setCreator(String value) {#setCreator-java.lang.String-}
```
public void setCreator(String value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getCreator()](../../com.aspose.diagram/documentproperties\#getCreator--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setDesc(String value) {#setDesc-java.lang.String-}
```
public void setDesc(String value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getDesc()](../../com.aspose.diagram/documentproperties\#getDesc--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public void setHyperlinkBase(String value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getHyperlinkBase()](../../com.aspose.diagram/documentproperties\#getHyperlinkBase--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public void setKeywords(String value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getKeywords()](../../com.aspose.diagram/documentproperties\#getKeywords--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setLanguage(String value) {#setLanguage-java.lang.String-}
```
public void setLanguage(String value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getLanguage()](../../com.aspose.diagram/documentproperties\#getLanguage--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setManager(String value) {#setManager-java.lang.String-}
```
public void setManager(String value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getManager()](../../com.aspose.diagram/documentproperties\#getManager--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setPreviewPicture(byte[] value) {#setPreviewPicture-byte---}
```
public void setPreviewPicture(byte[] value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getPreviewPicture()](../../com.aspose.diagram/documentproperties\#getPreviewPicture--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | बाइट[] |  |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public void setSubject(String value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getSubject()](../../com.aspose.diagram/documentproperties\#getSubject--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setTemplate(String value) {#setTemplate-java.lang.String-}
```
public void setTemplate(String value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getTemplate()](../../com.aspose.diagram/documentproperties\#getTemplate--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setTimeCreated(DateTime value) {#setTimeCreated-com.aspose.diagram.DateTime-}
```
public void setTimeCreated(DateTime value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getTimeCreated()](../../com.aspose.diagram/documentproperties\#getTimeCreated--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

### setTimeEdited(DateTime value) {#setTimeEdited-com.aspose.diagram.DateTime-}
```
public void setTimeEdited(DateTime value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getTimeEdited()](../../com.aspose.diagram/documentproperties\#getTimeEdited--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

### setTimePrinted(DateTime value) {#setTimePrinted-com.aspose.diagram.DateTime-}
```
public void setTimePrinted(DateTime value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getTimePrinted()](../../com.aspose.diagram/documentproperties\#getTimePrinted--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

### setTimeSaved(DateTime value) {#setTimeSaved-com.aspose.diagram.DateTime-}
```
public void setTimeSaved(DateTime value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getTimeSaved()](../../com.aspose.diagram/documentproperties\#getTimeSaved--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [DateTime](../../com.aspose.diagram/datetime) |  |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getTitle()](../../com.aspose.diagram/documentproperties\#getTitle--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

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

