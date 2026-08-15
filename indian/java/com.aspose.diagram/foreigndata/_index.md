---
title: ForeignData
second_title: Aspose.Diagram for Java API Reference
description: चित्र डेटा जैसे Windows मेटाफाइल बिटमैप या OLE डेटा का MIME मल्टीपर्पज इंटरनेट मेल एक्सटेंशन एन्कोडेड BLOB शामिल करता है।
type: docs
weight: 164
url: /hi/java/com.aspose.diagram/foreigndata/
---

**Inheritance:**
java.lang.Object
```
public class ForeignData
```

चित्र डेटा का MIME (Multipurpose Internet Mail Extensions) एन्कोडेड BLOB शामिल करता है, जैसे Windows मेटाफाइल, बिटमैप, या OLE डेटा।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [deepClone()](#deepClone--) | इस उदाहरण की गहरी प्रतिलिपि बनाता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCompressionLevel()](#getCompressionLevel--) | यह विशेषता केवल तभी अर्थपूर्ण होती है जब विदेशी डेटा एक रास्टर-आधारित विदेशी वस्तु हो, जैसे DIB, JPG, PNG, TIFF, या GIF फ़ाइल। |
| [getCompressionType()](#getCompressionType--) | यह विशेषता केवल तभी अर्थपूर्ण होती है जब विदेशी डेटा एक रास्टर-आधारित विदेशी वस्तु हो, जैसे DIB, JPG, PNG, TIFF, या GIF फ़ाइल। |
| [getExtentX()](#getExtentX--) | यह विशेषता केवल तभी अर्थपूर्ण है जब विदेशी डेटा एक मेटाफाइल हो। |
| [getExtentY()](#getExtentY--) | यह विशेषता केवल तभी अर्थपूर्ण है जब विदेशी डेटा एक मेटाफाइल हो। |
| [getForeignType()](#getForeignType--) | डेटा प्रकार। |
| [getImageData()](#getImageData--) | OLE ऑब्जेक्ट की छवि को बाइट एरे के रूप में दर्शाता है। |
| [getMappingMode()](#getMappingMode--) | यह विशेषता केवल तभी अर्थपूर्ण है जब विदेशी डेटा एक मेटाफाइल हो। |
| [getObjectData()](#getObjectData--) | एम्बेडेड OLE ऑब्जेक्ट डेटा को बाइट एरे के रूप में दर्शाता है। |
| [getObjectHeight()](#getObjectHeight--) | यह गुण केवल तभी सार्थक होता है जब विदेशी डेटा OLE2 एम्बेडेड ऑब्जेक्ट हो। |
| [getObjectSourceFullName()](#getObjectSourceFullName--) | लिंक्ड OLE ऑब्जेक्ट के स्रोत फ़ाइल का पूर्ण नाम लौटाता है। |
| [getObjectType()](#getObjectType--) | यदि ForeignType विशेषता "Object" है, तो ForeignData तत्व में भी एक ObjectType विशेषता होनी चाहिए। |
| [getObjectWidth()](#getObjectWidth--) | यह गुण केवल तभी सार्थक होता है जब विदेशी डेटा OLE2 एम्बेडेड ऑब्जेक्ट हो। |
| [getShowAsIcon()](#getShowAsIcon--) | यह गुण केवल तभी सार्थक होता है जब विदेशी डेटा OLE2 एम्बेडेड ऑब्जेक्ट हो। |
| [getValue()](#getValue--) | चित्र डेटा का MIME (Multipurpose Internet Mail Extensions) एन्कोडेड BLOB शामिल करता है, जैसे Windows मेटाफाइल, बिटमैप, या OLE डेटा। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompressionLevel(double value)](#setCompressionLevel-double-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getCompressionLevel()](../../com.aspose.diagram/foreigndata\#getCompressionLevel--) |
| [setCompressionType(int value)](#setCompressionType-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getCompressionType()](../../com.aspose.diagram/foreigndata\#getCompressionType--) |
| [setExtentX(double value)](#setExtentX-double-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getExtentX()](../../com.aspose.diagram/foreigndata\#getExtentX--) |
| [setExtentY(double value)](#setExtentY-double-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getExtentY()](../../com.aspose.diagram/foreigndata\#getExtentY--) |
| [setForeignType(int value)](#setForeignType-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getForeignType()](../../com.aspose.diagram/foreigndata\#getForeignType--) |
| [setImageData(byte[] value)](#setImageData-byte---) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getImageData()](../../com.aspose.diagram/foreigndata\#getImageData--) |
| [setMappingMode(int value)](#setMappingMode-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getMappingMode()](../../com.aspose.diagram/foreigndata\#getMappingMode--) |
| [setObjectData(byte[] value)](#setObjectData-byte---) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getObjectData()](../../com.aspose.diagram/foreigndata\#getObjectData--) |
| [setObjectHeight(double value)](#setObjectHeight-double-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getObjectHeight()](../../com.aspose.diagram/foreigndata\#getObjectHeight--) |
| [setObjectSourceFullName(String value)](#setObjectSourceFullName-java.lang.String-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getObjectSourceFullName()](../../com.aspose.diagram/foreigndata\#getObjectSourceFullName--) |
| [setObjectType(int value)](#setObjectType-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getObjectType()](../../com.aspose.diagram/foreigndata\#getObjectType--) |
| [setObjectWidth(double value)](#setObjectWidth-double-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getObjectWidth()](../../com.aspose.diagram/foreigndata\#getObjectWidth--) |
| [setShowAsIcon(int value)](#setShowAsIcon-int-) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getShowAsIcon()](../../com.aspose.diagram/foreigndata\#getShowAsIcon--) |
| [setValue(byte[] value)](#setValue-byte---) | इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getValue()](../../com.aspose.diagram/foreigndata\#getValue--) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getCompressionLevel() {#getCompressionLevel--}
```
public double getCompressionLevel()
```


यह गुण केवल तभी सार्थक होता है जब विदेशी डेटा एक रास्टर-आधारित विदेशी ऑब्जेक्ट हो, जैसे DIB, JPG, PNG, TIFF, या GIF फ़ाइल। मान फ़ाइल पर लागू संपीड़न स्तर को दर्शाता है। संपीड़न स्तर प्रतिशत के सैंकड़ों में मापा जाता है।

**Returns:**
डबल
### getCompressionType() {#getCompressionType--}
```
public int getCompressionType()
```


यह गुण केवल तभी सार्थक होता है जब विदेशी डेटा एक रास्टर-आधारित विदेशी ऑब्जेक्ट हो, जैसे DIB, JPG, PNG, TIFF, या GIF फ़ाइल। मान फ़ाइल पर लागू संपीड़न प्रकार को दर्शाता है।

**Returns:**
int
### getExtentX() {#getExtentX--}
```
public double getExtentX()
```


यह गुण केवल तभी सार्थक होता है जब विदेशी डेटा एक मेटाफाइल हो। मान मेटाफाइल की क्षैतिज सीमा को दर्शाता है।

**Returns:**
डबल
### getExtentY() {#getExtentY--}
```
public double getExtentY()
```


यह गुण केवल तभी सार्थक होता है जब विदेशी डेटा एक मेटाफाइल हो। मान मेटाफाइल की लंबवत सीमा को दर्शाता है।

**Returns:**
डबल
### getForeignType() {#getForeignType--}
```
public int getForeignType()
```


डेटा प्रकार।

**Returns:**
int
### getImageData() {#getImageData--}
```
public byte[] getImageData()
```


OLE ऑब्जेक्ट की छवि को बाइट एरे के रूप में दर्शाता है।

**Returns:**
बाइट[]
### getMappingMode() {#getMappingMode--}
```
public int getMappingMode()
```


यह गुण केवल तभी सार्थक होता है जब विदेशी डेटा एक मेटाफाइल हो। मान मेटाफाइल मैपिंग मोड को दर्शाता है।

**Returns:**
int
### getObjectData() {#getObjectData--}
```
public byte[] getObjectData()
```


एम्बेडेड OLE ऑब्जेक्ट डेटा को बाइट एरे के रूप में दर्शाता है।

**Returns:**
बाइट[]
### getObjectHeight() {#getObjectHeight--}
```
public double getObjectHeight()
```


यह गुण केवल तभी सार्थक होता है जब विदेशी डेटा OLE2 एम्बेडेड ऑब्जेक्ट हो। मान पृष्ठ इकाइयों में ऑब्जेक्ट की ऊँचाई को व्यक्त करता है।

**Returns:**
डबल
### getObjectSourceFullName() {#getObjectSourceFullName--}
```
public String getObjectSourceFullName()
```


लिंक्ड OLE ऑब्जेक्ट के स्रोत फ़ाइल का पूर्ण नाम लौटाता है। केवल तब स्रोत पूर्ण नाम सेट करने का समर्थन करता है जब फ़ाइल प्रकार OleFileType.Unknown हो। जैसे wav फ़ाइल, avi फ़ाइल आदि।

**Returns:**
java.lang.String
### getObjectType() {#getObjectType--}
```
public int getObjectType()
```


यदि ForeignType विशेषता "Object" है, तो ForeignData तत्व में भी एक ObjectType विशेषता होनी चाहिए।

**Returns:**
int
### getObjectWidth() {#getObjectWidth--}
```
public double getObjectWidth()
```


यह गुण केवल तभी सार्थक होता है जब विदेशी डेटा OLE2 एम्बेडेड ऑब्जेक्ट हो। मान पृष्ठ इकाइयों में ऑब्जेक्ट की चौड़ाई को व्यक्त करता है।

**Returns:**
डबल
### getShowAsIcon() {#getShowAsIcon--}
```
public int getShowAsIcon()
```


यह गुण केवल तभी सार्थक होता है जब विदेशी डेटा OLE2 एम्बेडेड ऑब्जेक्ट हो।

**Returns:**
int
### getValue() {#getValue--}
```
public byte[] getValue()
```


चित्र डेटा का MIME (Multipurpose Internet Mail Extensions) एन्कोडेड BLOB शामिल करता है, जैसे Windows मेटाफाइल, बिटमैप, या OLE डेटा।

**Returns:**
बाइट[]
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




### setCompressionLevel(double value) {#setCompressionLevel-double-}
```
public void setCompressionLevel(double value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getCompressionLevel()](../../com.aspose.diagram/foreigndata\#getCompressionLevel--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | डबल |  |

### setCompressionType(int value) {#setCompressionType-int-}
```
public void setCompressionType(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getCompressionType()](../../com.aspose.diagram/foreigndata\#getCompressionType--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setExtentX(double value) {#setExtentX-double-}
```
public void setExtentX(double value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getExtentX()](../../com.aspose.diagram/foreigndata\#getExtentX--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | डबल |  |

### setExtentY(double value) {#setExtentY-double-}
```
public void setExtentY(double value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getExtentY()](../../com.aspose.diagram/foreigndata\#getExtentY--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | डबल |  |

### setForeignType(int value) {#setForeignType-int-}
```
public void setForeignType(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getForeignType()](../../com.aspose.diagram/foreigndata\#getForeignType--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setImageData(byte[] value) {#setImageData-byte---}
```
public void setImageData(byte[] value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getImageData()](../../com.aspose.diagram/foreigndata\#getImageData--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | बाइट[] |  |

### setMappingMode(int value) {#setMappingMode-int-}
```
public void setMappingMode(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getMappingMode()](../../com.aspose.diagram/foreigndata\#getMappingMode--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setObjectData(byte[] value) {#setObjectData-byte---}
```
public void setObjectData(byte[] value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getObjectData()](../../com.aspose.diagram/foreigndata\#getObjectData--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | बाइट[] |  |

### setObjectHeight(double value) {#setObjectHeight-double-}
```
public void setObjectHeight(double value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getObjectHeight()](../../com.aspose.diagram/foreigndata\#getObjectHeight--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | डबल |  |

### setObjectSourceFullName(String value) {#setObjectSourceFullName-java.lang.String-}
```
public void setObjectSourceFullName(String value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getObjectSourceFullName()](../../com.aspose.diagram/foreigndata\#getObjectSourceFullName--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setObjectType(int value) {#setObjectType-int-}
```
public void setObjectType(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getObjectType()](../../com.aspose.diagram/foreigndata\#getObjectType--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setObjectWidth(double value) {#setObjectWidth-double-}
```
public void setObjectWidth(double value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getObjectWidth()](../../com.aspose.diagram/foreigndata\#getObjectWidth--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | डबल |  |

### setShowAsIcon(int value) {#setShowAsIcon-int-}
```
public void setShowAsIcon(int value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getShowAsIcon()](../../com.aspose.diagram/foreigndata\#getShowAsIcon--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### setValue(byte[] value) {#setValue-byte---}
```
public void setValue(byte[] value)
```


इस प्रॉपर्टी के विवरण के लिए, कृपया देखें [getValue()](../../com.aspose.diagram/foreigndata\#getValue--)

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | बाइट[] |  |

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

