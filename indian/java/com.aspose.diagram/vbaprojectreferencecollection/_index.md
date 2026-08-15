---
title: VbaProjectReferenceCollection
second_title: Aspose.Diagram for Java API Reference
description: VBA प्रोजेक्ट के सभी संदर्भों को दर्शाता है।
type: docs
weight: 435
url: /hi/java/com.aspose.diagram/vbaprojectreferencecollection/
---

**Inheritance:**
java.lang.Object, [com.aspose.diagram.CollectionBase](../../com.aspose.diagram/collectionbase)
```
public class VbaProjectReferenceCollection extends CollectionBase
```

VBA प्रोजेक्ट के सभी संदर्भों को दर्शाता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [add(Object o)](#add-java.lang.Object-) | CollectionBase इंस्टेंस में एक आइटम जोड़ता है। |
| [addControlRefrernce(String name, String libid, String twiddledlibid, String extendedLibid)](#addControlRefrernce-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | एक twiddled टाइप लाइब्रेरी और उसकी विस्तारित टाइप लाइब्रेरी के लिए एक रेफ़रेंस जोड़ें। |
| [addProjectRefrernce(String name, String absoluteLibid, String relativeLibid)](#addProjectRefrernce-java.lang.String-java.lang.String-java.lang.String-) | एक बाहरी VBA प्रोजेक्ट के लिए रेफ़रेंस जोड़ें। |
| [addRegisteredReference(String name, String libid)](#addRegisteredReference-java.lang.String-java.lang.String-) | Automation टाइप लाइब्रेरी के लिए रेफ़रेंस जोड़ें। |
| [clear()](#clear--) | CollectionBase इंस्टेंस से सभी ऑब्जेक्ट हटाता है। |
| [contains(Object o)](#contains-java.lang.Object-) | वापस करता है कि इंस्टेंस में यह ऑब्जेक्ट है या नहीं |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int i)](#get-int-) | सूची में इंडेक्स द्वारा रेफ़रेंस प्राप्त करें। |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | CollectionBase इंस्टेंस में मौजूद तत्वों की संख्या प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [indexOf(Object o)](#indexOf-java.lang.Object-) | CollectionBase इंस्टेंस में किसी विशिष्ट आइटम का इंडेक्स निर्धारित करता है। |
| [iterator()](#iterator--) | CollectionBase इंस्टेंस के माध्यम से इटररेट करने वाला एनेमरेटर लौटाता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट इंडेक्स पर आइटम हटाता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(Object o) {#add-java.lang.Object-}
```
public int add(Object o)
```


CollectionBase इंस्टेंस में एक आइटम जोड़ता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| o | java.lang.Object | CollectionBase इंस्टेंस में जोड़ने के लिए ऑब्जेक्ट। |

**Returns:**
int - वह स्थिति जिसमें नया तत्व डाला गया था।
### addControlRefrernce(String name, String libid, String twiddledlibid, String extendedLibid) {#addControlRefrernce-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
```
public int addControlRefrernce(String name, String libid, String twiddledlibid, String extendedLibid)
```


एक twiddled टाइप लाइब्रेरी और उसकी विस्तारित टाइप लाइब्रेरी के लिए एक रेफ़रेंस जोड़ें।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| नाम | java.lang.String | रेफ़रेंस का नाम। |
| libid | java.lang.String | Automation टाइप लाइब्रेरी का पहचानकर्ता। |
| twiddledlibid | java.lang.String | twiddled टाइप लाइब्रेरी का पहचानकर्ता। |
| extendedLibid | java.lang.String | The identifier of an extended type library |

**Returns:**
int -
### addProjectRefrernce(String name, String absoluteLibid, String relativeLibid) {#addProjectRefrernce-java.lang.String-java.lang.String-java.lang.String-}
```
public int addProjectRefrernce(String name, String absoluteLibid, String relativeLibid)
```


एक बाहरी VBA प्रोजेक्ट के लिए रेफ़रेंस जोड़ें।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| नाम | java.lang.String | रेफ़रेंस का नाम। |
| absoluteLibid | java.lang.String | The referenced VBA project\\u9225\\u6a9a identifier with an absolute path. |
| relativeLibid | java.lang.String | The referenced VBA project\\u9225\\u6a9a identifier with an relative path. |

**Returns:**
int -
### addRegisteredReference(String name, String libid) {#addRegisteredReference-java.lang.String-java.lang.String-}
```
public int addRegisteredReference(String name, String libid)
```


Automation टाइप लाइब्रेरी के लिए रेफ़रेंस जोड़ें।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| नाम | java.lang.String | रेफ़रेंस का नाम। |
| libid | java.lang.String | Automation टाइप लाइब्रेरी का पहचानकर्ता। |

**Returns:**
int -
### clear() {#clear--}
```
public void clear()
```


CollectionBase इंस्टेंस से सभी ऑब्जेक्ट हटाता है।

### contains(Object o) {#contains-java.lang.Object-}
```
public boolean contains(Object o)
```


वापस करता है कि इंस्टेंस में यह ऑब्जेक्ट है या नहीं

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| o | java.lang.Object | परीक्षण वस्तु |

**Returns:**
बूलियन - क्या इंस्टेंस में यह वस्तु है
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
### get(int i) {#get-int-}
```
public VbaProjectReference get(int i)
```


सूची में इंडेक्स द्वारा रेफ़रेंस प्राप्त करें।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| i | int | इंडेक्स। |

**Returns:**
[VbaProjectReference](../../com.aspose.diagram/vbaprojectreference) - 
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public int getCount()
```


CollectionBase इंस्टेंस में मौजूद तत्वों की संख्या प्राप्त करता है।

**Returns:**
int - CollectionBase इंस्टेंस में शामिल तत्वों की संख्या।
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### indexOf(Object o) {#indexOf-java.lang.Object-}
```
public int indexOf(Object o)
```


CollectionBase इंस्टेंस में किसी विशिष्ट आइटम का इंडेक्स निर्धारित करता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| o | java.lang.Object | CollectionBase इंस्टेंस में किसी विशिष्ट आइटम का इंडेक्स निर्धारित करता है। |

**Returns:**
int - यदि सूची में मान मिला तो उसका सूचकांक; अन्यथा, -1।
### iterator() {#iterator--}
```
public Iterator iterator()
```


CollectionBase इंस्टेंस के माध्यम से इटररेट करने वाला एनेमरेटर लौटाता है।

**Returns:**
java.util.Iterator - CollectionBase इंस्टेंस के लिए एक इटररेटर।
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeAt(int index) {#removeAt-int-}
```
public void removeAt(int index)
```


निर्दिष्ट इंडेक्स पर आइटम हटाता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| सूचकांक | int | हटाने वाले आइटम का शून्य-आधारित सूचकांक। |

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

