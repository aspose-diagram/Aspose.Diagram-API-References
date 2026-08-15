---
title: CollectionBase
second_title: Aspose.Diagram for Java API Reference
description: एक स्ट्रॉन्गली टाइप्ड संग्रह के लिए एब्स्ट्रैक्ट बेस क्लास प्रदान करता है।
type: docs
weight: 50
url: /hi/java/com.aspose.diagram/collectionbase/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public abstract class CollectionBase implements Iterable
```

एक स्ट्रॉन्गली टाइप्ड संग्रह के लिए एब्स्ट्रैक्ट बेस क्लास प्रदान करता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [CollectionBase()](#CollectionBase--) | CollectionBase क्लास की नई इंस्टेंस को डिफ़ॉल्ट प्रारंभिक क्षमता के साथ इनिशियलाइज़ करता है। |
| [CollectionBase(int capacity)](#CollectionBase-int-) | CollectionBase क्लास की नई इंस्टेंस को निर्दिष्ट क्षमता के साथ इनिशियलाइज़ करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [add(Object o)](#add-java.lang.Object-) | CollectionBase इंस्टेंस में एक आइटम जोड़ता है। |
| [clear()](#clear--) | CollectionBase इंस्टेंस से सभी ऑब्जेक्ट हटाता है। |
| [contains(Object o)](#contains-java.lang.Object-) | वापस करता है कि इंस्टेंस में यह ऑब्जेक्ट है या नहीं |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [get(int index)](#get-int-) | निर्दिष्ट स्थिति पर एक आइटम प्राप्त करें। |
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
### CollectionBase() {#CollectionBase--}
```
public CollectionBase()
```


CollectionBase क्लास की नई इंस्टेंस को डिफ़ॉल्ट प्रारंभिक क्षमता के साथ इनिशियलाइज़ करता है।

### CollectionBase(int capacity) {#CollectionBase-int-}
```
public CollectionBase(int capacity)
```


CollectionBase क्लास की नई इंस्टेंस को निर्दिष्ट क्षमता के साथ इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| क्षमता | int | नई सूची प्रारंभ में जितने तत्व संग्रहीत कर सकती है, उसकी संख्या। |

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
### get(int index) {#get-int-}
```
public Object get(int index)
```


निर्दिष्ट स्थिति पर एक आइटम प्राप्त करें।

**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| सूचकांक | int | निर्दिष्ट स्थिति का सूचकांक। |

**Returns:**
java.lang.Object - निर्दिष्ट स्थिति में आइटम।
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

